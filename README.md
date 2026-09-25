# Eili-Automat, Quizseite

Barbaras Eili-Automat. Die Seite zeigt das Quiz und schickt bei richtiger
Antwort einen Auslösebefehl an einen MQTT-Broker. Ein ESP32 lauscht dort und
gibt das Ei aus.

Erreichbar unter https://stefs72.github.io/eili/

Die Fragen werden zur Laufzeit aus einem GitHub-Gist geladen und lassen sich
dort ändern, ohne diese Seite anzufassen.

Die Zugangsdaten im Quelltext sind bewusst öffentlich. Der Zugang darf nur
senden und nur auf ein einziges Thema, das ein Ei auslöst. Er gewährt kein
Mitlesen und schützt keine Daten.
