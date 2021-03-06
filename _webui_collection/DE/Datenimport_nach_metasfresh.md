---
title: Datenimport nach metasfresh
layout: default
tags:
  - Datenverwaltung
  - Datenimport
lang: de
sequence: 10
ref: data_import_metasfresh
---

## Überblick
Mithilfe der Importfunktion kannst Du extern gespeicherte Daten (wie z.B. Excel-Tabellen mit Daten zu Geschäftspartnern oder Produkten) ganz schnell nach metasfresh importieren und so ebenfalls bestehende Einträge aktualiseren. Hierzu musst Du die Daten erst entsprechend formatiert als CSV- oder TXT-Datei hochladen und kannst sie dann einfach über das [Aktionsmenü](AktionStarten) importieren.

## Voraussetzungen
1. [Lege ein Importformat mit entsprechender Datenbanktabelle an](Importformat_anlegen), in dem Du die Daten bzw. Spalten sowie deren Datentypen festlegst, welche aus der Importdatei in metasfresh übertragen werden sollen.

   | Zu importierende Daten | Entsprechende DB-Tabelle |
   | :--- | :---: |
   | Bankauszugsdaten | Import - Bankauszug |
   | Benutzerdefinierte Dateneingaben | Import Data Entry Record |
   | Geschäftspartnerdaten | Import - Geschäftspartner |
   | IFA-Herstellerdatenimport | Import Pharma BPartners |
   | IFA-Produktdaten | Import Pharma Product |
   | Kontenrahmendaten | Import - Kontendefinition |
   | Nachbestelldaten | Import Replenishment |
   | Postalische Daten | Import Postal Code Data |
   | Produktdaten | Import - Produkt |
   | Rabattschemadaten | I_DiscountSchema |

1. Halte eine [Importdatei](Importdatei_nuetzliche_Hinweise) mit den dem Importformat entsprechend formatierten Daten bereit.<br> ***Formatbeispiele:***
   - [Bankauszugsdatenimport](Importformat_Beispiel_Bankauszug)
   - [Benutzerdefinierte Dateneingaben (Import)](Importformat_Beispiel_Dateneingabe)
   - [Geschäftspartnerdatenimport](Importformat_Beispiel_GPartner)
   - [IFA-Herstellerdatenimport](Importformat_Beispiel_GPartner_Pharma)
   - [IFA-Produktdatenimport](Importformat_Beispiel_Produkt_Pharma)
   - [Kontenrahmendatenimport](Importformat_Beispiel_Kontenrahmen)
   - [Nachbestelldatenimport](Importformat_Beispiel_Nachbestellung)
   - [Postalische Daten (Import)](Importformat_Beispiel_postalische_Daten)
   - [Produktdatenimport](Importformat_Beispiel_Produkt)
   - [Rabattschemadatenimport](Importformat_Beispiel_Rabattschema)<br><br>

1. Importiere Deine Daten unter Verwendung des entsprechenden Importformats.
   - [Folge dieser Anleitung](Bankauszugsdaten_importieren), um externe Daten zu **Bankauszügen** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Dateneingaben_importieren), um externe Daten zu **benutzerdefinierten Dateneingaben** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](GPartnerdaten_importieren), um externe Daten zu **Geschäftspartnern** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](GPartnerdaten_importieren_Pharma), um externe Daten zu **IFA-Herstellern** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Produktdaten_importieren_Pharma), um externe Daten zu **IFA-Produkten** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Kontenrahmendaten_importieren), um externe Daten zu **Kontenrahmen** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Nachbestelldaten_importieren), um externe Daten zu **Nachbestellungen** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Postalische_Daten_importieren), um externe **postalische Daten** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Produktdaten_importieren), um externe Daten zu **Produkten** nach metasfresh zu importieren.
   - [Folge dieser Anleitung](Rabattschema_importieren), um externe Daten zu **Rabattschemata** nach metasfresh zu importieren.<br><br>

   | **Wichtiger Hinweis:** |
   | :--- |
   | **1)** Beachte dabei, dass das ***Trennzeichen*** aus der Importdatei mit dem aus dem Importformat übereinstimmt (Komma, Tabulatorzeichen, Semikolon usw.).<br> **2)** Beachte außerdem, dass sowohl das ***Dezimaltrennzeichen*** als auch das ***Tausendertrennzeichen*** aus der Importdatei Deinen jeweiligen sprachspezifischen Systemeinstellungen entsprechen (z.B. dt.: *€ 1.999,95* vs. engl.: *$ 1,999.95*). |
