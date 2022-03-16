# GitLab für Open Educational Resources

In diesem Proof of Concept wollen wir zeigen, wie eifach es ist, mit GitLab offene Lehrmaterialien zu erstellen, gemeinsam zu bearbeiten und diese auf dem zentralen Suchindex OERSI bekannt zu machen. Bei den Materialien liegt hier der Fokus auf Lektionen, Kursen, Skripten oder Aufgabensammlungen und weniger auf kleinteiligem Material.

Die folgenden Abschnitte zeigen in weniger als 5 Minuten alle notwendigen Schritte vom Anlegen des Projekts über die synchrone Bearbeitung der Inhalte bis hin zur Veröffentlichung.

## Projekt erstellen

Das Ergebnis dieses Beispiels ist ein Kurs mit LiaScript. Weitere Beispiele mit Templates für Hugo, Docsify, Grav oder generierten Inhalten als PDF oder EPUB sind geplant.

Einzige Voraussetzung ist ein Account auf gitlab.com oder einer GitLab Instanz die öffentliche Projekte erlaubt.

!?[Kurs mit LiaScript](https://gitlab.com/axel-klinger/gitlab-fuer-open-educational-resources/-/raw/main/GitLab-OER-Teil1.mp4)

## Inhalte bearbeiten

**Dies ist bisher nur ein Proof of Concept und noch nicht öffentlich verfügbar**

Zeigt die Bearbeitung von Markdown Dateien auf GitLab mit HedgeDoc/CodiLIA.

!?[GitLab und CodiLIA](https://gitlab.com/axel-klinger/gitlab-fuer-open-educational-resources/-/raw/main/GitLab-OER-Teil2.m4v)

## Veröffentlichen auf OERSI

Wenn eine GitLab Instanz an den OERSI angebunden ist, können Projekte mit der folgenden Auszeichnung mit Metadaten automatisch aufgenommen werden.

Erforderliche Schritte

1. Projekt taggen mit `Open Educational Resources` in den Project Settings
  - **Settings** -> **General** -> set Topics and Save changes
2. Metadaten erstellen
  - Formular ausfüllen: https://oersi.gitlab.io/metadata-form/metadata-generator.html und generieren
  - generierte Daten in neuer Datei `metadata.yml` im root Verzeichnis des Projekts speichern
3. Veröffentlichen
  - in der Datei `metadata.yml` den creativeWorkStatus auf Published setzen `creativeWorkStatus: "Published"`

video
