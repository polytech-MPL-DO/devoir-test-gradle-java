# Autograding Example: Java
This example project is written in Java, and tested with Gradle/JUnit.

L'avantage si je comprends bien c'est qu'on n'a pas besoin de déclarer les tests qu'on veut faire, il doit lancer tout ce qu'il trouve dans le dossier `test` (A VERIFIER)


Le soucis est que les étudiants voient les tests, car ils sont dans le dépôt de ce qu'ils copient ?!

### The assignment
The tests are currently failing because of an output mismatch. 
Fixing the `System.out.println` in the main method will make the tests green.


### Setup command
N/A

### Run command
`gradle test`

### Notes
- The JDK is installed on GitHub Actions machines, so you're also able to directly invoke `javac`, `java`, or any other CLI command included in the JDK. 
