# Fellogg

En rad per fel. Skriv medan du minns hur du gjorde.

| Nr | Vad stod i loggen? | Lokalt eller på GitHub? | Hur tog du reda på orsaken? | Hur löste du det? |
|----|--------------------|-------------------------|-----------------------------|-------------------|
| 1  | Syntax error line 11                    |Github actions                          | Genom att läsa workflow file                            |  Fixade till syntax                 |
| 2  | Unable to find lockfile                   | Github                         |   Felsökning av workflow                          |      UV sync            |
| 3  | Remove unused import                   |  Github                       |  Identifierade felet genom att granska loggarna för check-jobbet                           |  Tog bort en unused import från src/baseline.py                |
| 4  | Ruff formatted src tests                 |  Github                       |  Identifierade felet genom att granska loggarna för check-jobbet                           |  Ruff formatted src tests
| 5  | ModuleNotFoundError                 |  Github                       |  Identifierade felet genom att granska loggarna för check-jobbet                           |  Added numpy and redefined moving_average function

Fortsätt tabellen med fler rader vid behov.
