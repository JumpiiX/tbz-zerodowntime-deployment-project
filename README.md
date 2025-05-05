# Zero-Downtime Deployment eines Rust-basierten Blockchain-Indexers

<p align="center">
  <img src="docs/images/penumbra_logo.png" alt="Penumbra Logo">
</p>

Dieses Projekt implementiert ein Zero-Downtime Deployment-System für  Penumbra Blockchain Explorer, der kryptographische Blockchain-Daten für Endbenutzer verständlich visualisiert. [Penumbra](https://penumbra.zone/) ist eine datenschutzorientierte Zero-Knowledge-Blockchain, deren komplexe Datenstrukturen ohne spezielle Indexierung und Aufbereitung für normale Anwender nicht lesbar wären.


## Wichtige Links

| Beschreibung | Link |
|--------------|------|
| **Doku-Repository** | [tbz-zerodowntime-deployment-project](https://github.com/JumpiiX/tbz-zerodowntime-deployment-project) |
| **Rust Blockchain Indexer** | [penumbra-explorer-backend](https://github.com/pk-labs/penumbra-explorer-backend) |
| **Scrum Board** | [GitHub Projects Board](https://github.com/users/JumpiiX/projects/2/views/1) |
| **Roadmap** | [Projekt Roadmap](https://github.com/users/JumpiiX/projects/2/views/4) |
| **Sprints** | [Milestones Übersicht](https://github.com/JumpiiX/tbz-zerodowntime-deployment-project/milestones) |

## Inhaltsverzeichnis

1. [Einführung und Problemstellung](#einführung-und-problemstellung)
2. [Projektziele](#projektziele)
3. [Projektmanagement](#projektmanagement)
4. [Sprints und Fortschritt](#sprints-und-fortschritt)
5. [Technische Dokumentation](#technische-dokumentation)
6. [Risiken](#risiken)

## Einführung und Problemstellung

### Problemstellung

Blockchain-Daten müssen kontinuierlich und zuverlässig indiziert werden, um sie in Echtzeit für Endanwender bereitzustellen – beispielsweise in einem Block Explorer. Da sich das Datenmodell oder die Indizierungslogik regelmässig ändert, müssen bestehende Indexer-Instanzen ersetzt und Daten neu aufgebaut werden (Reindexing).

Ohne geeignete Strategie führt dies zu:
- **Downtime** für Endnutzer
- **Inkonsistenten Daten** während der Umschaltung
- **Benutzerfehlern** durch unvollständige Daten

### Für wen lösen wir das Problem?

Mein aktueller Arbeitgeber [PK Labs](https://www.pklabs.me/) benötigt eine Lösung, um unsere Rust-basierten Blockchain-Indexer für die Penumbra-Blockchain ohne Unterbrechungen aktualisieren zu können. Dies betrifft sowohl:
- Interne Entwicklungsteams, die kontinuierlichen Zugriff auf Blockchain-Daten benötigen
- Externe Kunden und Nutzer, die auf die API des Indexers für ihre Anwendungen angewiesen sind
- Unseren [Penumbra Blockchain Explorer](https://explorer.penumbra.zone/) 

---
<p align="left">
  <img src="docs/images/pklabs_logo.png" alt="PK Labs Logo">
</p>
*Dieses Projekt wird im Rahmen der TBZ Semesterarbeit für PK Labs umgesetzt.*

*Letzte Aktualisierung: 05.05.2025*
