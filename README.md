# WebCaisseFX

Prototype JavaFX + JDBC pour le module GRC de WebCaisse.
Étude de cas BTS SIO SLAM 2ème année.

## Structure du projet

- `modele/` : Classes Conso et ConsoFidele
- `dao/` : Accès BDD sécurisé avec PreparedStatement
- `controleur/` : Contrôleur JavaFX
- `resources/` : Vue FXML
- `test/` : Tests unitaires JUnit 5

## Lancement

1. Démarrer MySQL (Laragon/XAMPP)
2. Exécuter le script SQL (src/main/resources ou dans le sujet)
3. Lancer `Launcher.java`
