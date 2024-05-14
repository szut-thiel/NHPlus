# NHPlus

Dieses Projekt umfasst zwei voneinander unabhängige Anwendungen:

1. NHPlus mit der ausführbaren Klasse `Main`
2. Ein Hilfsprogramm, mit dem die gegebene Datenbank in den ursprünglichen Zustand versetzt werden kann, mit der
ausführbaren Klasse `SetUpDB`

Bitte beachten Sie, dass das Programm `SetUpDB` nicht nur die Datensätze löscht (DML-Befehl `DELETE`), sondern die
 Relationen selbst löscht (DDL-Befehl `DROP`). Sollten Sie Veränderungen an der Struktur der Datenbank vorgenommen
haben, werden diese nach dem Aufruf von `SetUpDB` nicht mehr vorhanden sein.


