# PKV-IK-Liste
Institutionskennzeichen der privaten Krankenversicherer (IK-Liste)

## Formate
Die Liste mit den Institutionskennzeichen der privaten Krankenversicherer werden in zwei Formaten dargestellt
- csv-Datei
- FHIR-Datei

## Grundlagen
Das FHIR-Profil der PKV-IK-Liste basiert auf der Organisation-Struktur (de.gematik.fhir.directory 0.9.0 - https://simplifier.net/packages/de.gematik.fhir.directory/0.9.0) aus dem VZD-Projekt der gematik https://simplifier.net/vzd-fhir-directory.
Die Beschreibung findet sich hier https://simplifier.net/VZD-FHIR-Directory/OrganizationDirectory/~overview.

## Ausnahmen
Die privaten Krankenversicherer werden aktuell mit Identitäten ausgestattet. Einige Informationen für die Befüllung des Datensatzes liegen aktuell noch nicht vor. Aus diesem Grund werden in der FHIR-Datei folgende Werte mit Platzhaltern belegt:
- telematik-id mit "9-02-99999999"
- Organization identifier mit "XX"

## IK-Stammdatei der KBV
Perspektivisch ist auch die Umsetzung der Daten anlog der IK-Stammdatei der KBV angedacht.

## Aktualisierungsprozess der IK-Liste
Aktualisierungswünsche können
- über ein Issue eingestellt oder
- über den PKV-Verband
\ngemeldet werden. Die Historie der Datei wird über github gepflegt.
Bei der nächsten Aktualisierung werden im Bundle-Header Aktualisierungsinformationen hinterlegt.
