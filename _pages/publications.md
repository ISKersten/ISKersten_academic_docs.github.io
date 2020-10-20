---
layout: archive
title: "Einführung"
permalink: /publications/
author_profile: true
---

Einführung
==========

Die Architektur der Geodateninfrastruktur Deutschland
-----------------------------------------------------

Um ein reibungsloses Zusammenwirken der nationalen technischen
Komponenten der GDI-DE zu ermöglichen, sind organisatorische und
technische Rahmenvorgaben erforderlich, die zusammen­fassend als
Architekturkonzept der GDI-DE bezeichnet werden.

Zur leichteren Handhabung ist das Architekturkonzept der GDI-DE aus
einzelnen Dokumenten in drei verschiedenen Kategorien (grundsätzliche
Festlegungen, spezielle technische Festlegungen und Empfehlungen)
aufgebaut:

![Übersicht der Module.png](media/image2.png){width="6.3in"
height="3.245833333333333in"}

Abbildung 1: Architekturkonzept der GDI-DE -- Übersicht über die
Architekturdokumente

Grundsätzliche Festlegungen werden durch Beschluss des LG GDI-DE in
folgenden Dokumenten getroffen:

-   Das Dokument *„Architektur der GDI-DE - Ziele und Grundlagen"*
    erläutert die strategischen Ziele, fachliche und technische
    Grundsätze sowie die rechtlichen und organisatorischen
    Rahmenbedingungen der GDI-DE \[GDI-DE Architektur - Ziele\].

-   Das Dokument *„Architektur der GDI-DE - Technik"* beschreibt die
    verschiedenen Architektur­komponenten und referenziert hierfür
    relevante Normen, Standards und Spezifikationen \[GDI-DE
    Architektur - Technik\].

-   Das Dokument *„Architektur der GDI-DE - Maßnahmenplan"* zeigt die
    für die künftige Entwicklung der GDI-DE erforderlichen Schritte auf
    \[GDI-DE Architektur - Maßnahmen\].

Spezielle technische Festlegungen, vor allem in Bezug auf Technik und
Betrieb von Komponenten der GDI-DE, werden durch Beschluss des LG GDI‑DE
in folgenden Dokumenten getroffen:

-   Profile der GDI-DE zu internationalen oder nationalen Normen und

-   Konventionen, die über eine Norm oder Spezifikation hinausgehen.

Darüber hinausgehende Informationen werden als Handlungsempfehlungen von
Arbeitskreisen weiter konkretisiert.

Konventionen zu Metadaten
-------------------------

Im vorliegenden Dokument werden Konventionen zu Metadaten sowie deren
Bereitstellung erläutert und zusammengefasst. Diese Konventionen werden
im Arbeitskreis (AK) Metadaten erarbeitet. Ältere Vorgängerversionen
gehen auch auf Arbeiten der Projektgruppe Geodatenkatalog.de und einen
Metadaten-Workshop mit Ansprechpartnern der GDI-DE aus Bund und Ländern
zurück. Weitere Hinweise, welche sich auf die Inhalte von Metadaten
beziehen, finden sich in eigenen Handlungsempfehlungen, z. B. der
Länder-GDIs[^1], wieder.

In Geodateninfrastrukturen gibt es grundsätzlich zwei unterschiedliche
Typen von Metadatendokumenten:

-   Typ1: Capabilities-Dokumente, mit welchen Dienste-Schnittstellen
    ihre Eigenschaften beschreiben.

-   Typ2: Metadaten nach ISO 19115/19119, welche in Katalogen erfasst
    und bereitgestellt werden.

Das vorliegende Dokument befasst sich überwiegend mit Konventionen zu
Typ 2. Typ 1 wird in den Konventionsdokumenten bzw.
Handlungsempfehlungen des AK Geodienste behandelt[^2].

Grundsätzlich sollen in der GDI-DE sowohl die Anforderungen aus der
INSPIRE-Richtlinie \[INS VO MD, INS TG MD\] (sofern relevant) als auch
die ISO-Festlegungen \[ISO 19115, ISO 19119, ISO 19139\] erfüllt werden.
Alle Vorgaben der ISO (Belegungspflichten bzw. -bedingungen,
Werteumfänge etc.) gelten somit auch für die GDI-DE. Das bedeutet, dass
es weitere, zwingend zu belegende Metadatenelemente geben kann, die
benötigt werden, um einen ISO- und/oder INSPIRE-konformen Metadatensatz
zu bilden, auch wenn das vorliegende Dokument keine Konvention dazu
aufführt.

Ergänzend bzw. vertiefend werden in diesem Dokument konkrete
Konventionen für einzelne Metadatenelemente in der GDI-DE beschrieben.
Die Festlegungen im vorliegenden Dokument betreffen Metadatenelemente,
für die Regelungsbedarf in der GDI-DE gesehen wird, der über die
grundsätzlichen Regelungen der ISO hinausgehen kann oder aus
verpflichtenden oder bedingten Angaben für INSPIRE resultiert.

Außerdem trifft dieses Dokument keine Festlegungen zur inhaltlichen
Strukturierung von Freitext-Elementen wie z. B. Titel und
Kurzbeschreibung. Etwaige Regelungen für eine einheitliche Vergabe von
Titeln, Kurzbeschreibungen etc. und die Festlegung von Benennungsmustern
liegen im Ermessen der einzelnen Fachnetzwerke und sind durch diese in
eigenen Leitfäden zu treffen.

Bzgl. der Vorgaben seitens INSPIRE wird an dieser Stelle explizit darauf
hingewiesen, dass zzt. für die GDI-DE keine Betrachtung der sog.
„aufrufbaren Geodatendienste", die keine INSPIRE-Netzdienste sind,
erfolgt. Aus der INSPIRE Technical Guidance zu Metadaten V2.0.1 wurden
daher nur die Belange für Metadaten zu Datensätzen und --serien
(geregelt in Chapter 2, 3.1 und 3.2 \[INS TG MD\]) sowie zu Netzdiensten
(geregelt in Chapter 4.1 und 4.2 \[INS TG MD\] berücksichtigt. Die
Vorgaben für aufrufbare Geodatendienste (geregelt in Chapter 4.3 bis 4.5
\[INS TG MD\]) gelten seitens INSPIRE davon unbenommen; eine
Präzisierung durch die GDI-DE bleibt jedoch zzt. aus, weil momentan
keine Anwendungsfälle existieren. Bei Bedarf wird dies zu einem späteren
Zeitpunkt im Rahmen der Fortschreibung dieses Dokumentes ergänzt.

![](media/image3.png){width="6.558333333333334in"
height="3.601350612423447in"}

Abbildung 2: „Figure 4: Structure of the conformance classes in this
Technical Guidance document" \[INS TG MD\] -- Metadaten für aufrufbare
Geodatendienste (rote Kennzeichnung) werden aktuell in diesem Dokument
nicht präzisiert.

Die Topologie der Metadatenkataloge
-----------------------------------

In der GDI-DE existieren eine Vielzahl verteilter, eigenständiger
Metadatenkataloge, deren Inhalte im zentralen Geodatenkatalog.de
zusammengeführt werden. Eine ähnliche Aggregation geschieht auch in
anderen Knoten. Beispielsweise laufen in den Katalogen der Bundesländer
die Metadaten aus verschiedenen Bereichen und Ebenen der Verwaltung
zusammen. 3Abbildung (Seite 9) verdeutlicht diesen Zusammenhang.

Eine Beschreibung der zentralen Komponente „Geodatenkatalog.de" der
GDI-DE erfolgt in diesem Dokument nicht, sondern ist im Dokument
„Architektur der GDI-DE -- Technik" zu finden \[[GDI-DE
Architektur](#REF12) - Technik\]. Dort werden auch die Voraussetzungen
für die Einbindung einer dezentralen Katalogschnittstelle in die GDI-DE
beschrieben.

![](media/image4.png){width="6.495833333333334in"
height="4.370833333333334in"}

Abbildung 3: Topologie der Metadatenkataloge

Durch die Topologie der Metadatenkataloge ist es notwendig, dass
Änderungen eines Katalogs überall dort nachvollzogen werden, wo dessen
Bestand übernommen wird. Wird also ein Metadatensatz in einem Katalog
gelöscht, so wird er auch in allen anderen Katalogen entfernt, welche
diesen Katalog harvesten, da der *fileIdentifier* des Metadatensatzes
und damit der Metadatensatz selbst nicht mehr auffindbar ist. Übernommen
werden zugleich alle „neuen" Metadaten mit einem bisher nicht
vorhandenen *fileIdentifier* und alle geänderten Metadaten, deren
*fileIdentifier* bereits bekannt sind, die jedoch einen aktualisierten
Zeitstempel tragen.

Hinweise zum Dokument
---------------------

Die Festlegungen in diesem Dokument sind für die Metadaten-Sprache
„Deutsch" getroffen, sofern durch ISO oder INSPIRE keine anderen
Forderungen bestehen.

Den einzelnen Festlegungen in diesem Dokument ist jeweils ein
XPath-Ausdruck vorangestellt:

Dieser adressiert bzw. beschreibt die Position des betreffenden
Metadatenelementes im XML-Dokument. Die Kodierung des Elementes in XML
wird jeweils wie folgt exemplarisch dargestellt:

Die einzelnen Festlegungen des Dokumentes enthalten am Anfang jeweils
folgende Tabelle:

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Diese Tabelle gibt einen Überblick über die jeweilige Forderung der
GDI-DE bzw. zusätzlich für INSPIRE. Dabei gelten folgende Festlegungen:

-   „GDI-DE" -- generelle Konventionen für [alle]{.ul} Metadaten, um
    eine Einheitlichkeit in den Metadaten der GDI-DE zu fördern und
    deren Interoperabilität zu gewährleisten. Diese Anforderungen können
    begründet sein

    -   über \[ISO 19115\] und \[ISO 19119\] hinausgehende Festlegungen
        zwecks Einheitlichkeit;

    -   durch die Verwendung der Metadaten für Open Data (siehe Kapitel
        6);

    -   durch Vorgaben seitens INSPIRE, für die eine Verallgemeinerung
        und Übertragung auf die gesamte GDI-DE als sinnvoll erachtet
        wurde.

-   „zusätzlich für INSPIRE" - Konventionen, die sich aus der RICHTLINIE
    2007/2/EG DES EUROPÄISCHEN PARLAMENTS UND DES RATES vom 14. März
    2007 zur Schaffung einer Geodateninfrastruktur in der Europäischen
    Gemeinschaft (INSPIRE), den INSPIRE Implementing Rules oder den
    zugehörigen Technical Guidance-Dokumenten ergeben. Hierbei handelt
    es sich um Klarstellungen oder Präzisierungen der GDI-DE, um die
    Metadaten, die Ressourcen für INSPIRE beschreiben, einheitlich zu
    gestalten (z. B. in Fällen, in denen INSPIRE Freiräume zulässt).
    Grundsätzlich betrifft dies nur Metadaten, die Datensätze, -serien
    oder Netzdienste für INSPIRE beschreiben. [Die Konventionen unter
    „GDI-DE" (s.o.) sind dabei ebenfalls zu beachten und
    einzuhalten]{.ul}.

-   *verpflichtend* -- generelle Verpflichtungen zur Erfüllung der
    Anforderungen seitens der GDI-DE bzw. für INSPIRE.

-   *konditional* - Verpflichtungen unter bestimmten Bedingungen, um die
    Anforderungen seitens der GDI-DE bzw. für INSPIRE zu erfüllen. Die
    jeweilige Konvention ist dann verpflichtend, wenn die benötigten
    Informationen vorliegen bzw. eine beschriebene Situation zutrifft.

-   *optional* - keine Verpflichtung zur Führung der jeweiligen
    Information. Für den Fall, dass diese Information aber erfasst
    werden soll, gelten die jeweils genannten Konventionen.

Im Fließtext sind die Bezeichnungen von Metadatenelementen kursiv
gesetzt, z. B.: *MD_Metadata*. Die Attributwerte sind in
Anführungszeichen angegeben, z. B.: „Es gelten keine Bedingungen".

Die dabei verwendeten Bezeichnungen von Metadatenelementen beziehen sich
auf die Nomenklatur der Spezifikationen der \[ISO 19115\] und \[ISO
19119\] sowie der INSPIRE-Verordnung für Metadaten \[INS VO MD\].

Jede Festlegung in diesem Dokument endet mit einem Verweis auf die
dazugehörige Testbeschreibung in Form einer *Abstract Testsuite* (ATS).
Dort sind die jeweiligen Testschritte, welche in der GDI-DE Testsuite
implementiert wurden, im Detail beschrieben:

Als Referenz werden unter

[*https://ims.geoportal.de/git/tree/AK-Metadaten.git/version2.0.0/konventionen!beispiel_xml*](https://ims.geoportal.de/git/tree/AK-Metadaten.git/version2.0.0/konventionen!beispiel_xml)

Beispieldokumente bereitgestellt:

-   *[dataset.xm](https://ims.geoportal.de/git/blob/AK-Metadaten.git/version0.9/konventionen!beispiel_xml!dataset.xml)l*
    (Daten-Metadatensatz)

-   [*service.xml*](https://ims.geoportal.de/git/blob/AK-Metadaten.git/version0.9/konventionen!beispiel_xml!service.xml)
    (Dienst-Metadatensatz)

-   [*wms.xml*](https://ims.geoportal.de/git/blob/AK-Metadaten.git/version0.9/konventionen!beispiel_xml!wms.xml)
    (WMS-Capabilities-Dokument)

-   *opendata_dataset.xml* (Daten-Metadatensatz)

In diesen Muster-Metadatensätzen sind die Konventionen, wie in diesem
Dokument dargelegt, umgesetzt.

Dieses Dokument wird in einem stetigen Prozess fortgeschrieben und
veröffentlicht. Je nach Veränderungen im Dokument werden die
Versionsnummern wie folgt angepasst:

  **Änderungen in der Versionsnummer**   **Anlass bzw. Umfang der Änderung**
  -------------------------------------- -----------------------------------------------------------------------------------------------------------------------
  1\.                                    Änderungen in den gesetzlichen Bestimmungen und damit grundsätzliche Änderungen im Dokument
  1.1                                    Geringfügige Änderungen oder Ergänzungen in den Kapiteln, Ergänzung von neuen Kapiteln
  1.1.1                                  Berichtigung von Schreibfehlern, Fehlerbehebung, redaktionelle Änderungen in den Kapiteln ohne fachliche Auswirkungen

**\
**

Grundsätzliche Konventionen für alle Metadaten
==============================================

Die Konventionen in diesem Kapitel betreffen die Metadaten zu allen
Ressourcen in der GDI-DE, unabhängig von der Art der Ressource im
*hierarchyLevel*-Element (siehe 2.3).

Multiplizität des identificationInfo-Elementes
----------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Um die Einheitlichkeit und eindeutige Interpretierbarkeit der Metadaten
in der GDI-DE zu fördern, gilt als Konvention für [alle]{.ul} Metadaten
in der GDI-DE:

Alle relevanten Informationen sind im ersten
*identificationInfo*-Element anzugeben.

Gemäß \[ISO 19115\] kann das *identificationInfo*-Element innerhalb
eines Metadatensatzes mehrfach verwendet werden. Im Rahmen von INSPIRE
wird jedoch nur das erste *identificationInfo*-Element ausgewertet
(siehe \[[INS TG MD](#REF2)\], 2.3). Auch im Geoportal.de finden nur
Informationen Berücksichtigung, die im ersten
*identificationInfo*-Element angegeben sind.

Eindeutiger Metadatensatzidentifikator
--------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Ein Metadatensatz besitzt immer einen eindeutigen Identifikator. Die
Verwendung einer UUID gemäß RFC 4122[^3] wird empfohlen. Sollte der
bisher verwendete Metadatensatzidentifikator historisch bedingt nicht
den Regeln einer UUID entsprechen, so ist dieser im Sinne des
Bestandsschutzes weiterhin zulässig. Der Identifikator soll, unabhängig
von Überarbeitung am Metadatensatz selbst, nicht verändert werden. Beim
Replizieren muss dieser beibehalten und darf nicht überschrieben werden.
Nur so sind eine eindeutige Identifizierung von Metadaten, die
zuverlässige Filterung von Dubletten sowie die Aktualisierung
vorhandener Metadatensätze anhand von *fileIdentifier* (\[ISO 19115\],
B.2.1, No. 2) und *dateStamp* (\[ISO 19115\], B.2.1, No. 9) innerhalb
der GDI-DE möglich.

Art der Ressource
-----------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Ein Metadatensatz muss immer eine Information über die Art der
Ressource, die er beschreibt, beinhalten. Dies geht über die Regelungen
aus \[ISO 19115\] für das *hierarchyLevel*-Element (\[ISO 19115\],
B.2.1, No. 6) hinaus und soll eine eindeutige Interpretierbarkeit des
Metadatensatzes innerhalb der GDI-DE ermöglichen.

Sprache der Metadaten
---------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Ein Metadatensatz muss immer eine Information über die in den Metadaten
verwendete Sprache beinhalten.

Diese Konvention beruht auf den Vorgaben aus \[INS TG MD\], 2.2.2
(Requirement C.5) und geht über die Regelungen aus \[ISO 19115\] für das
*language*-Element in \[ISO 19115\], B.2.1, No. 3, hinaus.

Um die Einheitlichkeit und die eindeutige Interpretierbarkeit der
Metadaten in der GDI-DE zu fördern, wird diese Konvention für
[alle]{.ul} Metadaten in der GDI-DE übernommen.

Kontakt (Verantwortliche Stelle Metadaten)
------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Ein Metadatensatz muss immer eine Information über die für die
Erstellung und Pflege der Metadaten zuständige Stelle beinhalten. Diese
Information muss mindestens Folgendes beinhalten:

-   einen Namen im *organisationName*-Element*;*

-   eine E-Mail-Adresse im *electronicMailAddress*-Element;

-   die Rolle „pointOfContact" im *role*-Element.

Diese Konvention beruht auf den Vorgaben aus \[INS TG MD\], 2.2.3
(Requirement C.6) und geht über die Regelungen aus \[ISO 19115\] für das
*CI_ResponsibleParty*-Element in \[ISO 19115\], B.3.2.1, No. 374,
hinaus.

Um die Einheitlichkeit der Metadaten in der GDI-DE zu fördern, wird
diese Konvention für [alle]{.ul} Metadaten in der GDI-DE übernommen.

Kontakt (Verantwortliche Stelle für die Ressource)
--------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Ein Metadatensatz muss immer eine Information über die für die Ressource
zuständige Stelle beinhalten. Diese Information muss mindestens
Folgendes beinhalten:

-   einen Namen im *organisationName*-Element*;*

-   eine E-Mail-Adresse im *electronicMailAddress*-Element.

Diese Konvention beruht auf den Vorgaben aus \[INS TG MD\], 2.3.3
(Requirement C.10) und geht über die Regelungen aus \[ISO 19115\] für
das *CI_ResponsibleParty*-Element in \[ISO 19115\], B.3.2.1, No. 374,
hinaus.

Um die Einheitlichkeit der Metadaten in der GDI-DE zu fördern, wird
diese Konvention für [alle]{.ul} Metadaten in der GDI-DE übernommen.

Als **[zusätzliche Empfehlung]{.ul}** gilt: Im *role*-Element wird die
Rolle „pointOfContact" verwendet.

[Hintergrund]{.ul}: Sowohl die Auswertung in der GDI-DE zum
INSPIRE-Monitoring sowie die Ableitung der Metadaten für GovData
berücksichtigen diese Rolle in besonderer Art, d. h. derart
gekennzeichnete Kontakte sind diejenigen, die übernommen bzw. bevorzugt
werden.

Weitere Kontakte mit anderen Rollen bleiben davon unberührt.

Schlüsselwörter
---------------

Schlüsselwörter dienen der schnellen Auffindbarkeit von Daten und
Diensten. Häufig werden Schlüsselwörter verwendet, um Geodatenressourcen
zu bestimmten Fachthemen such- bzw. auffindbar zu machen oder um die
Geodatenressourcen in einem lokalen Zusammenhang, z. B. in einem Portal
gesammelt darstellen zu können. In diesem Dokument wird jedoch nur Bezug
auf Schlüsselwörter genommen, die für die GDI-DE in ihrer Gesamtheit
gültig sind.

### Schlüsselwort „inspireidentifiziert"

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☐
  zusätzlich für INSPIRE   ☒               ☐             ☐

Metadatensätze, die von INSPIRE betroffene Geodatensätze oder --dienste
beschreiben, werden mit dem Eintrag des Schlüsselworts
„**inspireidentifiziert**" im *keyword*-Element (\[[ISO 19115](#REF7)\],
B.2.2.3, No. 53) gekennzeichnet und werden dadurch beim
INSPIRE-Monitoring berücksichtigt.

Das Schlüsselwort „inspireidentifiziert" ist keinem Thesaurus entnommen
und ist ohne Quellenangabe in den Metadaten zu führen.

Beschränkungen des öffentlichen Zugangs (\[INS VO MD\], B 8.2)
--------------------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☐
  zusätzlich für INSPIRE   ☒               ☐             ☐

Dieser Abschnitt beschreibt, wie Zugriffseinschränkungen im Sinne des
INSPIRE-Elements \"Beschränkungen des öffentlichen Zugangs\"
entsprechend der \[INS TG MD\] zu erfassen sind. Dabei sind
Beschränkungen des öffentlichen Zugangs nur in den in Artikel
13(1) a) - h) der INSPIRE-Richtlinie genannten Fällen zulässig.

Die Beschränkungen des öffentlichen Zugangs sind nach \[INS TG MD\],
2.3.6 (Requirement C.17), innerhalb eines gemeinsamen
*MD_LegalConstraints*-Objekts in folgenden Elementen anzugeben:

-   [genau ein]{.ul} *accessConstraints*-Element, Codelisten-Wert
    \"**otherRestrictions**\" aus *MD_RestrictionCode* (\[ISO 19115\],
    B.5.24)

[und]{.ul}

-   [ein oder mehrere]{.ul} *otherConstraints*-Elemente; jedes enthält
    einen Grund für die Beschränkung des öffentlichen Zugangs nach
    Artikel 13(1) a) - h) der INSPIRE-Richtlinie als
    *gmx:Anchor*-Element (Verweis auf einen Eintrag in der seitens
    INSPIRE bereitgestellten Codeliste zu LimitationsOnPublicAccess). Da
    die Metadaten-Sprache Deutsch ist, soll die zusätzliche
    Text-Ausprägung die deutsche Übersetzung des angegebenen
    Codelisten-Wertes beinhalten. Die Tabelle im *Anhang 3:
    Beschränkungen des öffentlichen Zugangs bei INSPIRE* enthält die o.
    g. Gründe nach Artikel 13 der INSPIRE-Richtlinie und listet den
    jeweils benötigten Eintrag für das *gmx:Anchor*-Element sowie für
    den deutschsprachigen Begleittext auf.

Liegen [keine]{.ul} Beschränkungen vor, so ist im
*otherConstraints*-Element statt eines Grundes für die Beschränkung der
Verweis zum Codelisten-Wert \"**noLimitations**\" der INSPIRE-Codeliste
zu LimitationsOnPublicAccess[^4] ebenfalls als *gmx:Anchor*-Element
einzutragen. Zur semantischen Abgrenzung gegenüber den
Nutzungsbedingungen (siehe 2.9) wird als deutschsprachige Entsprechung
der Freitext „Es gelten keine Zugriffsbeschränkungen" empfohlen.
Alternativ kann der für diesen Zweck bisher dokumentierte Freitext „Es
gelten keine Bedingungen" beibehalten werden.

Nutzungs- und Zugriffsbedingungen
---------------------------------

### Nutzungs- und Zugriffsbedingungen in der GDI-DE (ohne INSPIRE)

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Dieser Abschnitt beschreibt, wie Nutzungs- und Zugriffsbedingungen in
den Metadaten der GDI-DE dokumentiert werden, sofern es sich um eine
Ressource handelt, die [nicht]{.ul} unter die INSPIRE-Richtlinie fällt.
Sonst gelten stattdessen die Regelungen für das INSPIRE-Element
\"Bedingungen für den Zugang und die Nutzung\" unter 2.9.2.

Die Bedingungen für den Zugang und die Nutzung sind innerhalb eines
gemeinsamen *MD_LegalConstraints*-Objekts anzugeben. Dadurch wird
sichergestellt, dass textliche Erläuterungen zweifelsfrei der ggf.
dokumentierten Beschränkungsart zugeordnet werden können.

In den Metadaten der GDI-DE besteht das *MD_LegalConstraints*-Objekt für
Nutzungs- und Zugriffsbedingungen aus folgenden Elementen:

-   [verpflichtend mindestens ein]{.ul} *useConstraints*-Element; Inhalt
    ist Codelisten-Wert aus *MD_RestrictionCode* (\[ISO 19115\],
    B.5.24); empfohlener Inhalt: „**otherRestrictions**";

[und]{.ul}

-   [bedingt verpflichtend]{.ul} (falls *useConstraints* mit
    „**otherRestrictions**" belegt wurde) [mindestens ein]{.ul}
    *otherConstraints*-Element; in welchem die Nutzungs- und
    Zugriffsbedingungen sowie Informationen über etwaige Gebühren in
    Textform oder als Verweis (URL) zu dokumentieren sind.

*Anmerkung: In Anlehnung an die INSPIRE-Anforderung, immer eine Aussage
zu Nutzungs- und Zugriffsbedingungen in den Metadaten zu führen und
diese in der GDI-DE ausschließlich und einheitlich in den ISO-Elementen
useConstraints/otherConstraints abzulegen (siehe* *2.9.2), wird an
dieser Stelle zwecks Einheitlichkeit auch für diejenigen Ressourcen, die
[nicht]{.ul} unter die INSPIRE-Richtlinie fallen, als GDI-DE-Konvention
festgelegt, die gleiche Struktur (d. h. die ISO-Elemente
useConstraints/otherConstraints) zu verwenden. Die inhaltliche Belegung
ist für Ressourcen, die unter die INSPIRE-Richtlinie fallen, jedoch
restriktiver.*

Für den Fall, dass [keine]{.ul} Bedingungen gelten oder die Bedingungen
[unbekannt]{.ul} sind, ist dies ebenfalls zu dokumentieren. Der Eintrag
erfolgt als deutschsprachiger Freitext „Es gelten keine Bedingungen"
(siehe folgendes Beispiel) oder „Bedingungen unbekannt".

*Anmerkung: Eine „unbekannte" Bedingung ist für den Nutzer nicht
hilfreich und sollte möglichst konkretisiert werden.*

### Bedingungen für den Zugang und die Nutzung bei INSPIRE (\[INS VO MD\], B 8.1)

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☐
  zusätzlich für INSPIRE   ☒               ☐             ☐

Dieser Abschnitt beschreibt, wie Nutzungs- und Zugriffsbedingungen im
Sinne des INSPIRE-Elements \"Bedingungen für den Zugang und die
Nutzung\" entsprechend der \[INS TG MD\] zu erfassen sind.

Die Bedingungen für den Zugang und die Nutzung sind nach \[INS TG MD\],
2.3.7 (Requirement C.18), innerhalb eines gemeinsamen
*MD_LegalConstraints*-Objekts nach einer vorgegebenen Bildungsregel
anzugeben. Für die GDI-DE wird diese zwecks Einheitlichkeit weiter
spezifiziert, so dass folgende Elemente erforderlich sind:

-   [genau ein]{.ul} *useConstraints*-Element, Codelisten-Wert
    \"**otherRestrictions**\" aus *MD_RestrictionCode* (\[ISO 19115\],
    B.5.24)

> [und]{.ul}

-   [mindestens ein]{.ul} *otherConstraints*-Element; in welchem die
    Nutzungs- und Zugriffsbedingungen sowie Informationen über etwaige
    Gebühren in Textform oder als Verweis (URL) zu dokumentieren sind.

*Anmerkung: Seitens INSPIRE besteht die Anforderung, immer eine Aussage
zu den Bedingungen für den Zugang und die Nutzung in den Metadaten zu
führen und diese entweder in den ISO-Elementen
useConstraints/otherConstraints oder accessConstraints/otherConstraints
abzulegen. Zwecks Einheitlichkeit in der GDI-DE und zur Abgrenzung von
den Beschränkungen des öffentlichen Zugangs (siehe* *2.8) wurde
festgelegt, hier ausschließlich die ISO-Elemente
useConstraints/otherConstraints zu verwenden.*

Für den Fall, dass [keine]{.ul} Bedingungen gelten oder die Bedingungen
[unbekannt]{.ul} sind, ist dies entsprechend \[INS VO MD\], Teil B 8.1,
zu dokumentieren. Die Einträge erfolgen gem. \[INS TG MD\], 2.3.7
(Requirement C.18), als *gmx:Anchor*-Element mit Verweis auf einen
Eintrag in der seitens INSPIRE bereitgestellten Codeliste
ConditionsApplyingToAccessAndUse[^5] über die Werte
\"**noConditionsApply"** bzw. „**conditionsUnknown**" sowie den
zugehörigen deutschsprachigen Texten (siehe folgende Beispiele).

*Anmerkung: Eine „unbekannte" Bedingung ist für den Nutzer nicht
hilfreich und sollte möglichst konkretisiert werden.*

Regionalschlüssel
-----------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☒
  zusätzlich für INSPIRE   ☐               ☐             ☐

**[Empfehlung:]{.ul}** Geodaten und Geodatendienste, die einen
räumlichen Bereich in Form einer bestimmten Verwaltungseinheit abdecken,
können über deren 12-stelligen Regionalschlüssel (RS) gezielt auffindbar
gemacht werden, wenn der entsprechende Schlüssel in den Metadaten
hinterlegt wird. Die Angabe in den Metadaten ist optional, wird aber
empfohlen, um Auswertungen zu ermöglichen.

Alternativ kann die Kodierung auch in einem *CharacterString*-Element
erfolgen:

Der Regionalschlüssel wird vom Statistischen Bundesamt veröffentlicht
\[DESTATIS\].

Die in den Beispielen genannten URL (z. B.
https://registry.gdi-de.org/id/\<namespaceRS\>/033595407004) enthalten
persistente Identifikatoren für den Schlüssel. Diese verweisen auf einen
WFS, der u. a. die Geometrie der Verwaltungseinheit ausgibt.

Kennzeichnung der Verbindlichkeit von per Darstellungs- und/oder Downloaddienst bereitgestellten Daten
------------------------------------------------------------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☒
  zusätzlich für INSPIRE   ☐               ☐             ☐

Um in Zukunft rechtsgültige Auskunftssysteme auf Basis von
Geodatendiensten zu ermöglichen, soll die Verbindlichkeit von Daten, die
mittels Diensten bereitgestellt werden, automatisiert ausgewertet werden
können. Eine mögliche Ausprägung dieser Verbindlichkeit kann der Status
„amtliche Daten" sein. Damit Planer und Entscheider unmittelbar erkennen
können, inwieweit die vorliegenden Informationen für die Beantwortung
ihrer jeweiligen Fragestellung ausreichend verbindlich sind, wird eine
Information darüber in der Qualitätsaussage in den Metadaten hinterlegt.

Die Angabe der Verbindlichkeit in den Daten- und den Dienst-Metadaten
ist optional, wird aber wie folgt empfohlen:

Unter *dataQualityInfo* wird im entsprechenden
*DQ_ConformanceResult*-Element in

-   *specification* die rechtliche Grundlage (z. B. Verordnung,
    gesetzlicher Rahmen) zitiert;

-   *explanation* ein Freitext wie z. B.

    -   „amtlicher Dateninhalt",

    -   „Bei diesen Daten handelt es sich um einen amtlichen
        Dateninhalt." oder

    -   „Dieser Dienst präsentiert amtliche Daten." angegeben;

-   *pass* der Wert „true" gesetzt, um zu kennzeichnen, dass die
    benannte Rechtsgrundlage tatsächlich zu Grunde liegt.

Das folgende Beispiel zeigt, wie die Verbindlichkeit in Bezug auf eine
konkrete gesetzliche Regelung im Metadatensatz abgebildet werden kann:

Konformität (Übereinstimmung mit Spezifikationen, \[INS VO MD\], B 7)
---------------------------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☐             ☐
  zusätzlich für INSPIRE   ☒               ☐             ☐

Gemäß \[INS VO MD\], B 7 und \[[INS TG MD](#REF1)\], 2.4.1 (Requirements
C.20 bis C.22) ist in den Metadaten zu dokumentieren, ob die
beschriebene Ressource gegenüber einer Spezifikation geprüft wurde und
ob diese Überprüfung erfolgreich war. Grundsätzlich ist die Konformität
mindestens bzgl. der jeweils relevanten Durchführungsbestimmung
anzugeben. Mit der Aussage zur Konformität wird ausgedrückt, ob

-   die Daten bereits im INSPIRE-Datenmodell vorliegen und
    bereitgestellt werden (Daten-Metadaten: Übereinstimmung mit der
    Durchführungsbestimmung zur Interoperabilität, IR 1089/2010);

-   der Dienst die Vorgaben (Funktionen, Performanz, Capabilities etc.)
    für Netzdienste einhält (Dienst-Metadaten: Übereinstimmung mit der
    Durchführungsbestimmung zu Netzdiensten, IR 976/2009);

In [zusätzlichen]{.ul} Elementen können weitere Spezifikationen wie
z. B. Änderungsverordnungen, die die Durchführungsbestimmungen
betreffen, sowie Technical Guidance-Dokumente, z. B.
Datenspezifikationen oder zu Darstellungs- bzw. Downloaddiensten,
referenziert werden.

Die Informationen werden je zitierter Spezifikation in einem eigenen
*DQ_ConformanceResult*-Element mit *specification*, *explanation* und
*pass* (\[ISO 19115\], B.2.4.4, No. 129 bis No. 132) angegeben:

-   *specification*-Element: Für den Titel der Spezifikation wird das
    *title*-Element (\[ISO 19115\], B.3.2.1, No. 360) aus *CI_Citation*
    verwendet. Das Element kann als Freitext (gco:CharacterString) oder
    Verweis (gmx:Anchor mit xlink:href auf einen seitens der EU
    festgelegten Link plus Freitext) codiert werden. Die Abschnitte 3.5
    (für Datensätze und -serien) bzw. 4.6 (für Netzdienste) regeln
    Benennung und Schreibweise der jeweiligen Durchführungsbestimmung,
    die zusammen mit dem angegebenen Veröffentlichungsdatum zu verwenden
    ist. Dort ist auch der jeweilige Link für den Verweis mittels
    gmx:Anchor dokumentiert und Beispiele abgebildet. Im *Anhang 1:
    INSPIRE-Spezifikationen (Durchführungsbestimmungen)* sind die in
    Frage kommenden INSPIRE Durchführungsbestimmungen abermals
    aufgelistet.

-   *explanation*-Element: Hier kann grundsätzlich Freitext eingetragen
    werden. Beispielsweise können Angaben zu den verwendeten Anwendungen
    bei der Überprüfung der Konformität gemacht werden (siehe Kapitel
    7).

-   *pass-*Element: Gemäß \[ISO 19115\] ist der Wertebereich von *pass*
    auf 0 (= nein) und 1 (= ja) festgelegt. INSPIRE definiert abweichend
    davon, aber in Übereinstimmung mit \[ISO 19139\], die zulässigen
    Werte als **true** und **false**. Wurde die Übereinstimmung mit der
    Spezifikation noch nicht überprüft, kann das Element leer bleiben,
    sofern im *pass-*Element das Attribut **nilReason="unknown"**
    angegeben wird.

Angaben zum Raumbezug / Koordinatenreferenzsystem (EPSG-Code)
-------------------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☐               ☒             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

**Bedingung für das Gelten dieser Konvention:** Die zu beschreibende
Ressource besitzt einen absoluten Raumbezug.

Für Geodaten soll das Koordinatenreferenzsystem, in dem die
beschriebenen Geodaten tatsächlich vorliegen, als EPSG-Code[^6] in den
Metadaten hinterlegt werden. Für Geodatendienste sollen die EPSG-Codes,
in denen der Dienst die Geodaten bereitstellen kann, in den Metadaten
hinterlegt werden.

Der EPSG-Code (z. B. „4326" für das Koordinatenreferenzsystem „WGS 84")
ist ein konkreter Identifikator für das Referenzsystem gemäß
http://www.epsg-registry.org/. Im Zusammenspiel mit dem Namensraum kann
eine abstrakte und maschinenlesbare Beschreibung der Projektion im
GML-Format abgerufen werden[^7].

Für alle Daten und Dienste in der GDI-DE ist der entsprechende
Identifikator mindestens in Textform zu hinterlegen (siehe erstes
Beispiel). Alternativ kann dies in Form eines Verweises als gmx:Anchor
erfolgen (siehe zweites Beispiel). Für beide Varianten wird analog zu
den INSPIRE-Vorgaben als Identifier der HTTP URI Identifier für das
opengis.net-Repository[^8] vorgeschrieben.

In Metadaten zu INSPIRE-Datensätzen oder -serien ist bereits nach \[INS
TG MD\], 3.2.1.1 (Requirement 2.2) die Angabe des Referenzsystems als
HTTP URI Identifier verpflichtend, [sofern]{.ul} der anzugebende
Identifikator im Anhang D.4 „Default Coordinate Reference System
Identifiers" aufgeführt ist. Diese Verpflichtung gilt unverändert und
wird durch die vorliegende Konvention mit abgedeckt. Um die
Einheitlichkeit der Metadaten in der GDI-DE zu fördern, wird diese
Konvention für alle Metadaten in der GDI-DE übernommen.

Für die empfohlene Referenzierung mittels gmx:Anchor (\[INS TG MD\],
3.2.1.1, Recommendation 2.2) ist für den genannten HTTP URI Identifier
http://www.opengis.net/def/crs/EPSG/0/\[EPSG-Code\] zu verwenden (siehe
zweites Beispiel).

*Hinweis: Für Projektionen der World Meteorological Organisation (WMO)
ist das WMO-Register entsprechend zu zitieren*[^9]*.*

Konventionen für Metadaten zu Datenbeständen und Anwendungen
============================================================

Die Konventionen in diesem Kapitel betreffen die Metadaten zu allen
Ressourcen in der GDI-DE, die keine Dienste sind, d. h. deren Inhalt im
*hierarchyLevel*-Element [ungleich]{.ul} „service" ist (siehe 2.3).
Somit fallen auch Metadaten zu Anwendungen (z. B. Portale) darunter,
deren Metadatenstruktur in ISO 19115 analog zu Metadaten zu
Datenbeständen geregelt ist.

Eindeutiger Ressourcenidentifikator (\[INS VO MD\], B 1.5)
----------------------------------------------------------

                           verpflichtend   konditional   optional
  ------------------------ --------------- ------------- ----------
  GDI-DE                   ☒               ☐             ☐
  zusätzlich für INSPIRE   ☐               ☐             ☐

Die Angabe des eindeutigen Ressourcenidentifikators erfolgt im
*identificationInfo*-Element (ISO 19115, B.2.1, No. 15). Gemäß den
INSPIRE-Vorgaben in \[INS TG MD\], 3.1.2.1, Requirement 1.3, ist dieser
aus einem **Namensraum** (**namespace**) und einem lokalen
**Identifikator** (**localID**) zu bilden. Der lokale Identifikator ist
eine Zeichenkette und wird i. d. R. vom Eigentümer der Daten vergeben.
Der Namensraum, z. B. für eine Organisation, definiert den Kontext, in
dem der lokale Identifikator vergeben wird. Innerhalb eines Namensraumes
identifiziert ein lokaler Identifikator eindeutig eine Ressource (\[INS
VO MD\], B.1.5; \[INS Generic Conceptual Model\], 14.2).

Für die Bildung des eindeutigen Ressourcenidentifikators gelten folgende
Regeln:

1.  Der Ressourcenidentifikator ist ein gültiger „Unique Resource
    Identifier" (URI) \[RFC 3986\].

2.  Die Abbildung des Ressourcenidentifikators erfolgt über das
    *MD_Identifier/code*-Element (ISO 19115, B.2.7.3, No. 205/207)[^10].

3.  Der *code* wird aus Namensraum und lokalem Identifikator
    zusammengesetzt. Hierfür wird die localID an den namespace
    angehängt, getrennt durch „/" (namespace/localId).

4.  Nach Möglichkeit soll der verwendete Namensraum über die GDI-DE
    Registry[^11] verwaltet werden. Weitere Informationen dazu sind im
    GDI-DE Wiki[^12] zu finden.

5.  Sofern der verwendete Namensraum [nicht]{.ul} über die GDI-DE
    Registry verwaltet wird, ist (technisch) selbstständig
    sicherzustellen, dass dieser im Hinblick auf die gewünschte Funktion
    (Direktzugriff auf das XML des Daten-Metadatensatzes) dennoch
    aufgelöst werden kann, um die erforderliche Konformität zu
    gewährleisten.

*Hinweis: Der im Beispiel genannte Namensraum
„**https://registry.gdi-de.org/id/de.nw**" ist ein Platzhalter. Dieser
setzt sich aus einem für alle Namensräume festgelegten Prefix (z. B.
<https://registry.gdi-de.org/id/> ) und einem domänenspezifischen Teil
(z. B. „de.nw") zusammen. Der domänenspezifische Teil entsteht erst
durch Registrierung des Namensraums in der GDI-DE Registry.*

Schlüsselwörter 
---------------
