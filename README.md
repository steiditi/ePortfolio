ePortfolio PID Regler am Beispiel eines Lego Roboters

Um die Programme mit zu schreiben wird die Programmieroberfläche von Lego Mindstorms benötigt. Diese kann für Windows von der Homepage von Lego unter dem folgenden Link heruntergeladen werden:

Windows: https://go.api.education.lego.com/v1/lms-ev3_de-de_win32#noUrlRewrite

Die Installationsdatei ausführen und den Anweisungen des Installers folgen.



Die Datei "Regler Programme.ev3" kann mit diesem Programm geöffnet werden. In der Datei befinden sich die Implementierungen der vier Regler P, I, D und PID-Regler, sowie drei Beispielprogramme.

Das Programm "Gerade Fahren" lässt den Roboter mithilfe eines Gyro Sensors und des PID-Reglers geradeaus fahren, selbst wenn er aus der Bahn gebracht wird. 

Das Programm "Motor Drehen" implementiert eine kontrollierte Motorbewegung für einen einzigen Motor. Es wird auf eine Geschwindigkeit in °/s geregelt, die zu Beginn auf 90 steht und sich dort ändern lässt.

Das Programm "Linie Folgen" verannlasst den Roboter mithilfe seines Farb-/Lichtsensors einer schwarzen Linie zu folgen. Dabei wird auf die Graustufe geregelt, die der Sensor wahrnimmt, wenn dieser sich genau an der Grenze zwischen schwarz und weiß befindet.
