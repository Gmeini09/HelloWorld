<a id="readme-top"></a>
# HelloWorld

Author: Philipp Gmeinbauer <br>
LBS Eibiswald | 2aAPC

Die erste Java-Übung: Ein kleines Konsolenprogramm, das eine Begrüßung ausgibt
und anschließend mit einer `for`-Schleife die Zahlen von 1 bis 5 hochzählt.

## Installation

Voraussetzungen: Java JDK und IntelliJ IDEA.

```cmd
git clone https://github.com/Gmeini09/HelloWorld.git
```

Danach das Projekt in IntelliJ über **File → Open** öffnen.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Verwendung

Technologien im Einsatz:
[![Java][java.com]][java-url]

`Main.java` öffnen und auf den grünen Run-Pfeil klicken.

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello and welcome!");

        for (int i = 1; i <= 5; i++) {
            System.out.println("i = " + i);
        }
    }
}
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Screenshots

[![Screen Shot][product-screenshot]](program.png)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

[MIT](https://choosealicense.com/licenses/mit/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[java.com]: https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white
[java-url]: https://www.java.com/de/
[product-screenshot]: program.png
