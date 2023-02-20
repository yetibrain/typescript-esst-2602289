# TypeScript Grundkurs

Dies ist das Repository für den **LinkedIn Learning** Kurs `[TypeScript Grundkurs]`. Den gesamten Kurs finden Sie auf [LinkedIn Learning][lil-course-url].

![COURSENAME][lil-thumbnail-url]

Als Obermenge von JavaScript fügt die von Microsoft entwickelte Programmiersprache TypeScript einige Schlüsselworte zu JavaScript hinzu, die die Stabilität und Lesbarkeit des Codes wesentlich verbessern. In diesem Grundlagenkurs zeigt Ihnen der erfahrene Front-end-Entwickler David Lorenz, wie Sie Typen definieren, kombinieren und ableiten und erläutert, wie Sie TypeScript-Typen vor allem in komplexen Anwendungen erfolgreich einsetzen.<br><br>

Mit der Hilfe von Challenge/Solution-Einheiten können Sie das Erlernte sofort testen und Ihre Lösung auch gleich mit der vom Trainer angebotenen Solution vergleichen. Zudem zeichnet sich der Kurs durch eine nahtlose Integration in GitHub Codespaces, einer cloudbasierten Entwicklungsumgebung (IDE), aus. Sie müssen keinen lokalen Rechner einrichten und können direkt zu jeder Zeit praktische Übungen durchführen.

## Anleitung

Dieses Repository hat Branches für jedes Video im Kurs. Verwenden Sie das Ausklappmenü "Branch: ..." in GitHub um zwischen den unterschiedlichen Branches hin und her zu wechseln bzw. um bei einem spezifischen Status einzusteigen. Oder Sie fügen `/tree/BRANCH_NAME` der URL hinzu um direkt in den gewünschten Branch zu wechseln.

## Branches

Die Git Branches sind passend zu den Videos im Kurs strukturiert. Die Namenskonvention lautet `Kapitel#_Video#`. Der Branch `02_03` beinhaltet zum Beispiel die Übungen für das dritte Video im zweiten Kapitel. 
Einige Branches haben einen Anfangsstatus (`b`) für "beginning" und einen Endstatus (`e`). Der Branch mit dem `e` am Ende beinhaltet in diesem Fall stets den Code der am Ende des Videos zu sehen ist. Der `master` Branch beinhaltet den initialen Quellcode und wird nicht für die Übungen innerhalb des Kurses genutzt.

Wenn Sie von einem Branch nach Änderungen zum nächsten Branch wechseln, erhalten Sie möglicherweise die folgende Meldung:

```
error: Your local changes to the following files would be overwritten by checkout:        [files]
Please commit your changes or stash them before you switch branches.
Aborting
```

Dieses Problem lösen Sie wie folgt:
    Add changes to git using this command: git add .
    Commit changes using this command: git commit -m "some message"

## Installation

1. Um diese Übungsdateien nutzen zu können, müssen Sie folgendes installiert haben:
   - [list of requirements for course]
2. Klonen Sie das Repository in Ihre lokale Maschine unter Verwendung von terminal (Mac), CMD (Windows) oder ein anderes Werkzeug mit grafischer Bedienoberfläche wie SourceTree.
3. [Course-specific instructions]

### Autor

**David Lorenz**

_Frontend-Architekt_

Sehen Sie sich andere Kurse des Autors auf [LinkedIn Learning](https://www.linkedin.com/learning/instructors/david-lorenz) an.

[0]: # (Replace these placeholder URLs with actual course URLs)
[lil-course-url]: https://www.linkedin.com/learning/typescript-grundkurs-17656849
[lil-thumbnail-url]: https://media.licdn.com/dms/image/C4E0DAQEb1nao7Vcv5g/learning-public-crop_675_1200/0/1676880121131?e=2147483647&v=beta&t=pafnCwENtj_WOsNYSTBWo34ehuWsaYF8njv65LR8rFM
