# Aufgabe 1.1
- Layered Architecture kann man sich vorstellen wie ein stack. Bsp.: MVC: Ganz oben View, dann Controller, dann Model und ganz unten ist die Datenbank.
- Modules sind die groben Bestandteile der Architektur. Controller wäre ein Modul.
- Anti-Corruption-Layer ist der Adapter zwischen zwei Subsysteme. Dadurch kann ein Subsystem gewartet werden, während das andere unverändert bleiben kann.
- Eine Service ist eine Funktionalität, die in keiner anderen Klasse zugeordnet werden kann. Sie definiert Regeln, wie mit anderen Klassen zu arbeiten ist.
- Ein Entity ist ein Objekt mit einer eindeutigen Identität, das sich über die Laufzeit ändern kann. Eine Session-Entity hat z.B. eine Session-ID, womit diese Instanz sich identifizieren lässt.
- Ein Object-Value ist ein unveränderliches Objekt, das einen bestimmten Wert repräsentiert und keine eigene Identität besitzt. (Wird durch seine Attribute definiert)
- Eine repository ist eine Schnittstelle, zwischen dem Modell und der Datenbank.
- Ein Aggregat ist eine Gruppe von verbundenen Entitäten und Wertobjekten (object-value), die als eine einzige Einheit betrachtet werden. Externe Objekte können nur mit dem Aggregat-Root interagieren, was die Integrität des gesamten Aggregats sicherstellt.
- Eine Factory ist ein Entwurfsmuster, das die Erstellung komplexer Objekte, insbesondere von Aggregaten, kapselt. Die Factory enthält die Logik zur Instanziierung und Konfiguration eines Objekts, die für ein Objekt selbst zu komplex wäre, und sorgt dafür, dass das erzeugte Objekt in einem konsistenten Zustand ist und alle Regeln eingehalten werden.

# Aufgabe 1.2
