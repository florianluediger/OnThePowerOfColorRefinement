# OnThePowerOfColorRefinement

Dieses Repository enthält meine Ausarbeitung für das Seminar "Algorithm Engineering" an der TU Dortmund.
Es wurde das Paper "On the Power of Color Refinement" von Arvind et al. untersucht und aufgearbeitet.

Die finale Version steht [als Release zum Download](https://github.com/florianluediger/OnThePowerOfColorRefinement/releases/tag/endergebnis) zur Verfügung.

## Einführung

>Dieses Dokument stellt eine Aufarbeitung der Veröffentlichung "On the Power of
>Color Refinement" von Arvind et al. (2015) dar. In dieser wird ein Verfahren zur
>Überprüfung von Isomorphieeigenschaften von Graphen vorgestellt, welches die bekannte
>Color-Refinement-Heuristik erweitert. Graph-Isomorphie ist ein viel gefragtes
>Thema, da diese in vielen unterschiedlichen Bereichen von Wissenschaft und Technik
>benötigt wird. Ein bekanntes Anwendungsgebiet stellt die Chemieinformatik
>dar, welche die Gleichheit von Molekülen untersucht und zur Verarbeitung großer
>Datenmengen die Unterstützung eines performanten Algorithmus benötigt.
>
>Eine weit verbreitete Heuristik zur Lösung des Isomorphie-Problems stellt der
>Color-Refinement-Algorithmus dar, welcher in vielen Fällen zwei nicht isomorphe
>Graphen unterscheiden kann, nicht aber in allen Fällen. Somit wird die Frage aufgeworfen,
>ob sich eine Klasse von Graphen, nachfolgend CR-Graphen genannt, definieren lässt,
>für die der Algorithmus sicher sein kann, dass sowohl nicht isomorphe,
>als auch isomorphe Paare von Graphen korrekt erkannt werden können. Diese Frage
>wird im Folgenden beantwortet und eine Definition der Menge der CR-Graphen
>aufgestellt werden.
>
>Zunächst werden Graph-Isomorphie und Color-Refinement genauer vorgestellt
>und eine formale Definition für die Anforderungen an CR-Graphen aufgestellt. Wie
>sich herausstellen wird, lassen sich die erforderlichen Eigenschaften von CR-Graphen
>in eine lokale Struktur und eine globale Struktur einordnen, welche in den folgenden
>Kapiteln detailliert definiert werden. Die Ergebnisse bezüglich hinreichender
>Bedingungen zur Erkennung von CR-Graphen sowie Laufzeit und Fazit werden im
>abschlieÿenden Kapitel behandelt.
