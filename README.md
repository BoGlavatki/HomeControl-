# HomeControl-
HomeControl+ ist eine Smart-Home-App für iOS, die Geräte wie Pflanzenbewässerung, Aquarien aus der Ferne steuert. Sie bietet Echtzeit-Daten, Automatisierung und Benachrichtigungen. Entwickelt in Swift und optimiert für das iPhone 14 Pro, ermöglicht sie kostengünstige, flexible Smart-Home-Lösungen und einfache Integration weiterer Systeme.
# HomeControl+ - Eine persönliche Smart-Home-Lösung

## Motivation
Die Entwicklung der App HomeControl+ entspringt einem persönlichen Bedarf, den viele Menschen teilen, die ihr Zuhause effizienter und smarter steuern wollen. In meinem Fall besitze ich ein Aquarium, das tägliche Aufmerksamkeit erfordert. Jeden Tag musste ich manuell die Sauerstoffpumpe ein- und ausschalten sowie das Licht abhängig von der Sonneneinstrahlung regulieren. Diese Aufgaben sind zeitintensiv und können schnell zu einer Belastung werden, insbesondere wenn man unterwegs ist oder einen strukturierten Alltag hat.

### Problemstellung
Ein weiteres Problem, das mich zur Entwicklung der App motivierte, ist die Pflanzenbewässerung während meiner Abwesenheit. Wenn ich in den Urlaub fahre, muss ich immer jemanden bitten, der sich um die Bewässerung meiner Pflanzen kümmert. Leider klappt das nicht immer wie geplant, und es ist zudem mühsam, jemanden zu finden, der zuverlässig Zeit dafür hat. Um diese Schwierigkeiten zu umgehen, hatte ich im Rahmen eines früheren Projekts ein Embedded-System entwickelt, das die Pflanzen automatisch bewässerte und die Beleuchtung je nach Bedarf ein- und ausschaltete. Dieses System arbeitet autonom und bietet bereits eine deutliche Erleichterung im Alltag. Doch diese Automatisierung hat eine entscheidende Schwäche: Sie kann nur vor Ort bedient und überwacht werden.

## Die Lösung: HomeControl+
Hier setzt die App HomeControl+ an, die den Schritt von einer reinen Automatisierung hin zu einer intelligenten Fernsteuerung ermöglicht. Mit dieser App kann das bestehende Embedded-System für die Pflanzenbewässerung in ein smartes System umgewandelt werden, das nicht nur automatisiert arbeitet, sondern auch von unterwegs aus gesteuert und überwacht werden kann. Die App erlaubt es, über das Smartphone auf wichtige Werte wie Bodenfeuchtigkeit und Lichtverhältnisse zuzugreifen und diese anzupassen. So kann man beispielsweise die Feuchtigkeit der Erde überwachen und gegebenenfalls manuell die Bewässerung aktivieren. Auch das Licht für die Pflanzen kann in Prozenten der täglichen Beleuchtungsdauer (z.B. 65% des Tageslichts) individuell gesteuert werden.

## Funktionen
- **Fernzugriff**: Wichtige Parameter wie Bodenfeuchtigkeit und Lichtverhältnisse von überall aus einsehen und anpassen.
- **Individuelle Automatisierung**: Automatisierung der Pflanzenbewässerung oder Aquariumbeleuchtung auf Basis vordefinierter Schwellenwerte.
- **Flexibles Smart-Home-Konzept**: Die App wurde zunächst für die Pflanzenbewässerung entwickelt, ist jedoch offen für beliebige weitere Systeme (z.B. Aquarium, Heizung).
- **Offen für eigene Integration**: Technisch versierte Nutzer können weitere Mikrocontroller-basierte Systeme einbinden und ein personalisiertes Smart-Home-System schaffen.

## Technische Spezifikationen
- **Plattform**: Optimiert für iPhone 14 Pro (iOS 13+)
- **Programmiersprache**: Swift 5
- **Architektur**: Client-Server mit HTTP für die Kommunikation zwischen App und Geräten
- **Datenbank**: InfluxDB (oder ähnliche Lösung) zur Speicherung von Sensordaten
- **Versionskontrolle**: GitHub zur sicheren Verwaltung des Codes

## Erste Schritte
1. **Einrichten**: App installieren, Verbindungen über IP und Port konfigurieren und mit einem Token authentifizieren.
2. **Steuern & Überwachen**: Echtzeit-Daten der Systeme abrufen und steuern.
3. **Automatisieren**: Automatisierung einrichten, z.B. zur Bewässerung basierend auf Bodenfeuchtigkeit.

HomeControl+ bietet eine flexible, kostengünstige Lösung für die Heimautomatisierung, erleichtert alltägliche Aufgaben und bringt den Komfort der Smart-Home-Technologie direkt auf das Smartphone.
