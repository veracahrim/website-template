# Weiterführende Aufgaben (Portfolio-Seite)

## Aufgabe 1

Erstellen Sie eine neue index.html sowie eine neue styles.css Datei und verlinken Sie diese.

Ergänzen Sie die HTML Datei mit einer grundlegenden Struktur mit folgenden Punkten:

- Home
- Profil
- CV (Lebenslauf)
- Portfolio
- Kontakt

Fügen Sie eine Navigationsleiste hinzu, die sich am unteren linken Rand der Seite befindet, mit den oben genannten
Punkten als Navigations-Ziele. (die Seite sollte jeweils zum richtigen Bereich scrollen, wenn man auf den
Navigations-Button klickt.)

## Aufgabe 2

Implementieren Sie, dass sich die Navigationsleiste beim runterscrollen in eine Sticky-Navigationsleiste verwandelt 
(damit sie den Bildschirm nie verlässt und am oberen Rand 'kleben' bleibt)

## Aufgabe 3

Suchen Sie im Internet nach einem Cover-Foto das Ihnen gefällt, welches Sie als Hintergrundbild bei der Home Section
einsetzen können. Schauen Sie darauf, dass Sie allfälligen Künstler*innen und/oder Fotograf*innen Anerkennung
zuteilwerden lassen.

Als Beispiel Bild haben Sie das 'mountains.svg' im assets Ordner.

Für gratis Bilder bietet sich [Pixabay](https://pixabay.com/) an.

Fügen Sie das Bild nun in der Home Section als Hintergrund hinzu.

Fügen Sie unten links beim Bild einen kurzen Credit Text (woher haben Sie das Bild) hinzu, und verlinken Sie ein
entsprechendes Profil (e.g. Pixabay, Instagram, etc.)

## Aufgabe 4

Stellen Sie sich nun anhand des Bildes eine Farbpalette zusammen, mit welcher Sie ihre Webseite anschliessend gestalten
werden.

Um Farben aus Bildern zu erhalten, gibt es zahlreiche Methoden, die einfachste ist wahrscheinlich die Pipetten-Funktion in
Bildbearbeitungsprogrammen oder dem Internetbrowser direkt.

Es gibt auch etliche Online Tools, die Ihnen automatisch eine Farbpalette zusammenstellen. Probieren Sie etwas aus.

Benutzen Sie anschliessend ihre neuen Farben um die Seite etwas neu einzufärben.

## Aufgabe 4 Bonus

Auf unserem Beispielbild sehen Sie einen Gradienten am unteren Rand der Seite. Idealerweise wollen wir einen
nahtlosen Übergang von Titelseite zu Content. Um dies zu erreichen, müssen wir westens herausfinden, welche Farben unser
Gradient auf dem Bild hat, dann denselben Gradienten als Hintergrundfarbe bei unserem Content bereich definieren, und am
schluss noch einen blurred Bereich über den direkten übergang legen.

## Aufgabe 5

Bei einem Marktanteil von über 50 % sind Mobile Endgeräte heutzutage wichtiger zu bedienen als Desktop PCs.

Um eine responsive Webseite zu gestalten ist es am einfachsten, von kleinen Bildschirmgrössen auszugehen und dann später
für grössere Screens einzelne Layout Einstellungen anzupassen.

Öffnen Sie die Entwicklertools in Ihrem Browser-of-choice und stellen Sie den Viewport auf Mobile ein. Hier können Sie
ebenfalls verschiedene Bildschirmgrössen definieren. Während den weiteren Entwicklungsschritten sollte diese Einstellung
stets eingeschaltet sein, damit unsere Website Mobile-Friendly wird.

Wir werden uns dann später um den Desktop PC Support kümmern.

Erstellen Sie anschliessend ein neues Navigationsmenu für unsere Mobile-Ansicht. Schauen Sie sich verschiedene
Mobile-Friendly Webseiten an und entscheiden Sie sich für eine Lösung, die Ihnen entspricht und implementieren Sie diese.

## Aufgabe 6

Fügen Sie ein paar Icons beim Navigationsmenu ein. Sie haben ein paar Beispiel-Icons im assets Ordner bereitgestellt.
Falls ihnen diese nicht entsprechen, suchen Sie online nach anderen Icons oder erstellen Sie ihre eigenen.

Mithilfe von Media Queries, schauen Sie dass nun das Mobile-Nav standardmässig sichtbar ist, jedoch ab einer
Bildschirmbreite von mindestens 768px das Desktop-Nav sichtbar wird.

## Aufgabe 7

Fügen Sie Ihrer Profile-Komponente einige Inhalte aus dem Lebenslauf ein.

- Bild
- Kurzer Intro-Text
- Skills
- Sprachen
- Hobbies

Fügen Sie bei den Skills einige passende Icons hinzu.

Fügen Sie bei den Sprachen die entsprechende Länderflagge als Icon hinzu.

Suchen Sie passende Icons für ihre Hobbies und stellen Sie die Hobbies inklusive Icons dar.

Fügen Sie bei den einzelnen Skills einen Progress-bar hinzu, welcher darstellen soll, wie sehr versiert Sie im
entsprechenden Skill sind. Tun Sie dasselbe für die Sprachen.

## Aufgabe 8

Fügen Sie der CV Komponente eine Timeline hinzu, mit diversen kleinen Einträgen zu ihrem jeweiligen Werdegang.

Die Timeline soll links am Rand (Mobile) angezeigt werden. Die einzelnen Einträge sollen Chronologisch geordnet sein 
(neueste zuerst)

## Aufgabe 9

Langsam aber sicher wird unsere styles.css Datei etwas gross und unübersichtlich.

Unterteilen Sie die Inhalte von styles.css in weitere Dateien:

- profile.css
- cv.css
- portfolio.css
- contact.css

Verlinken Sie die entsprechenden Dateien mit dem index.html und lagern sie den entsprechenden Code in die neuen CSS
Dateien aus. (Code der die Profile Section stylt ins profile.css file, etc.)

Von nun an schauen Sie darauf, dass beim Ergänzen der Stylings der einzelnen Sections die korrekte Datei verwendet wird.

## Aufgabe 10

Fügen Sie bei der Contact Section folgendes hinzu:

- Titel
- Input felder für folgendes:
    - Name
    - E-Mail Adresse
    - Betreff
    - Nachricht
- Button um das ganze formular zu senden

Mithilfe von CSS, entfernen Sie das Standard-styling der einzelnen Komponenten und fügen Sie ihr eigenes Design hinzu.

Wichtig ist, dass die Input-Felder die momentan aktiv sind, sich nach wie vor von den Inaktiven unterscheiden.

## Aufgabe 11

Ein grosser Bestandteil eines Web-Entwicklers ist die Online Recherche für das Lösen von Problemen die man selber
eventuell noch nicht zu lösen weiß.

Für den Portfolio bereich unserer Webseite wollen wir einen interessanten CSS Effekt einsetzen. Wir wollen eine Art
visuelles Magazin haben, welches sich von selber weiterblättert und Bilder zeigt, von Webseiten (oder anderen Dingen),
die wir bisher kreiert haben.

So einen Effekt von selber zu implementieren ist sehr anspruchsvoll, weshalb wir uns dem Internet-Hivemind bedienen.

Recherchieren Sie verschiedene CSS-Effekte und versuchen Sie einen der Ihnen gefällt in ihr Projekt zu integrieren.

## Aufgabe 12

Implementieren Sie einen Parallax-Effekt zwischen den einzelnen Sections (z.b. zwischen Profil und CV) mithilfe von
Javascript oder CSS

Parallax Effekt: Hintergrund scrollt langsamer als Vordergrund, dadurch entsteht ein 3D
Effekt. [Beispiel](http://www.firewatchgame.com/) (einen solchen mehrschichtigen Parallax Effekt ist etwas schwieriger
zu implementieren als ein einschichtiger, weshalb es erst am Ende als Bonus-Aufgabe vorgesehen ist.)

([Haikei](https://haikei.app/) ist ein gratis online-tool um einige interessante SVG Formen zu generieren. Im Beispiel
verwende ich ein SVG, welches ich da generiert habe.)

## Aufgabe 13

Stellen Sie sicher, dass ihr Parallax-Effekt (und auch alle anderen Stylings) in allen gängigen Browsern funktioniert (
Chrome, Firefox, Safari, Edge).

## Aufgabe 14

Desktop Support, Folgende Punkte müssen behandelt werden:

- Generell:
    - Content in der Mitte bei Widescreens und Ultra-Widescreens können wir sowieso nicht den ganzen Platz füllen.
    - Nicht alles ober einander wie bei der Mobile ansicht, wir haben nun mehr Platz.

- Profil:
    - Text, Skills und Sprachen links, Bild und Hobbies rechts
- CV
    - Timeline in der Mitte, jeweils jeder zweite Eintrag soll auf der linken Seite der Timeline erscheinen.
- Portfolio
    - Grösse anpassen
- Kontakt
    - Eingabefelder für Name und E-Mail-Adresse nun nebeneinander.

## Bonus: Mehrschichtige Parallaxe

Disclaimer: könnte Kopfschmerzen, Verzweiflung und ähnliche Frustrationen verursachen.

Implementieren Sie eine mehrschichtige Parallaxe auf der Homepage.

Könnte sein, dass Sie deshalb einige Bereiche des bisherigen Projekts etwas anpassen müssen.

Um einzelne layers erstellen zu können, müssen Sie erst ein passendes Bild finden und einzelne Schichten via
Photoshop (oder ähnlichen Programmen) extrahieren. Falls Sie auf diesen Schritt keine Lust haben, können Sie auch das
Beispielbild verwenden.
