---
title: StructureTypeStandard
second_title: Aspose.PDF für .NET-API-Referenz
description: steht für Standardstrukturtypen.
type: docs
weight: 4560
url: /de/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard class

steht für Standardstrukturtypen.

```csharp
public sealed class StructureTypeStandard
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Category](../../aspose.pdf.logicalstructure/structuretypestandard/category) { get; } | Ruft die Kategorie des Standardstrukturtyps ab. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag) { get; } | Ruft den Tag-Namen von ab[`StructureElement`](../structureelement) . |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| [explicit operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit) | Führt eine explizite Konvertierung von ausString zu[`StructureTypeStandard`](../structuretypestandard) . |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot) | (Anmerkung; PDF 1.5) Eine Zuordnung zwischen einem Teil des ILSE-Inhalts und einer entsprechenden PDF-Anmerkung. Annot soll für alle PDF-Anmerkungen außer Link-Anmerkungen und Widget-Anmerkungen verwendet werden. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art) | (Artikel) Ein relativ in sich geschlossener Textkörper, der eine einzelne Erzählung oder Darstellung darstellt. Artikel sollten disjunkt sein; das heißt, sie sollten keine anderen Artikel als konstituierende Elemente enthalten. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry) | (Bibliographieeintrag) Eine Referenz, die die externe Quelle einiger zitierter Inhalte identifiziert. Es kann als Kind ein Label (Strukturtyp Lbl) enthalten. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote) | (Blockzitat) Ein Textabschnitt, der aus einem oder mehreren Absätzen besteht, die jemand anderem als dem Autor des umgebenden Textes zugeschrieben werden. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption) | (Bildunterschrift) Ein kurzer Textabschnitt, der eine Tabelle oder Abbildung beschreibt. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code) | (Code) Ein Fragment des Computerprogrammtexts. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div) | (Division) Ein generisches Element auf Blockebene oder eine Gruppe von Elementen. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document) | (Dokument) Ein vollständiges Dokument. Dies ist das Wurzelelement jedes Strukturbaums, der mehrere Teile oder mehrere Artikel enthält. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure) | (Abbildung) Ein Element mit grafischem Inhalt. Seine Platzierung kann mit dem Attribut Placement layout angegeben werden. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form) | (Formular) Eine Widget-Anmerkung, die ein interaktives Formularfeld darstellt. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula) | (Formel) Eine mathematische Formel. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h) | (Überschrift) Eine Bezeichnung für eine Unterteilung des Inhalts eines Dokuments. Es sollte das erste Kind der Abteilung sein, die es leitet. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1) | Überschrift der Ebene 1, zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2) | Überschrift der Ebene 2, zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3) | Überschrift der Ebene 3, zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4) | Überschrift der Ebene 4, zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5) | Überschrift der Ebene 5 zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6) | Überschrift der Ebene 6, zur Verwendung in konformen Autoren, die ihre Abschnitte nicht hierarchisch verschachteln und daher die Ebene einer Überschrift nicht anhand ihrer Verschachtelungsebene bestimmen können. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index) | (Index) Eine Folge von Einträgen mit identifizierendem Text, begleitet von Referenzelementen, die auf Vorkommen des angegebenen Textes im Hauptteil eines Dokuments hinweisen. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l) | (Liste) Eine Folge von Elementen gleicher Bedeutung und Wichtigkeit. Seine unmittelbaren Kinder sollten eine optionale Beschriftung (Strukturtyp Beschriftung) sein, gefolgt von einem oder mehreren Listenelementen (Strukturtyp LI). |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl) | (Label) Ein Name oder eine Nummer, die ein bestimmtes Element von anderen in derselben Liste oder einer anderen Gruppe ähnlicher Elemente unterscheidet. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody) | (Listentext) Der beschreibende Inhalt eines Listenelements. In einer Wörterbuchliste beispielsweise enthält es die Definition des Begriffs. Es kann entweder den Inhalt direkt enthalten oder andere BLSEs, vielleicht einschließlich verschachtelter Listen, als Kinder haben. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li) | (Listenelement) Ein einzelnes Mitglied einer Liste. Seine Kinder können ein oder mehrere Labels, Listenkörper oder beides sein (Strukturtypen Lbl oder LBody). |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link) | (Link) Eine Zuordnung zwischen einem Teil des Inhalts der ILSE und einer entsprechenden Link-Anmerkung oder -Anmerkungen. Seine untergeordneten Elemente sollten ein oder mehrere Inhaltselemente oder untergeordnete ILSEs und eine oder mehrere Objektreferenzen sein, die die zugehörigen Linkanmerkungen identifizieren. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct) | (Nichtstrukturelles Element) Ein Gruppierungselement ohne inhärente strukturelle Bedeutung; es dient ausschließlich Gruppierungszwecken. Dieser Elementtyp unterscheidet sich von einer Division (Strukturtyp Div) dadurch, dass es nicht interpretiert oder in andere Dokumentformate exportiert werden darf; seine Nachkommen werden jedoch normal verarbeitet. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note) | (Anmerkung) Ein erläuternder Text, wie z. B. eine Fußnote oder eine Endnote, auf die im Hauptteil des Dokuments verwiesen wird. Es kann als Kind ein Label (Strukturtyp Lbl) haben. Die Notiz kann als untergeordnetes Element des Strukturelements in den Fließtext eingefügt werden, der darauf verweist, oder sie kann an anderer Stelle (z. B. in einem Endnotenabschnitt) eingefügt und über eine Referenz (Strukturtyp Referenz) aufgerufen werden. |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p) | (Absatz) Eine Unterteilung von Text auf niedriger Ebene. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part) | (Teil) Eine groß angelegte Teilung eines Dokuments. Dieser Elementtyp eignet sich zum Gruppieren von Artikeln oder Abschnitten. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private) | (Privates Element) Ein Gruppierungselement, das privaten Inhalt enthält, der zu der Anwendung gehört, die es erzeugt. Die strukturelle Bedeutung dieses Elementtyps ist nicht spezifiziert und wird vollständig vom konformen Verfasser bestimmt. Weder das Private-Element noch seine Nachkommen dürfen interpretiert oder in andere Dokumentformate exportiert werden. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote) | (Zitat) Ein eingebetteter Textteil, der jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb) | (Ruby-Basistext) Der Text in voller Größe, auf den die Ruby-Anmerkung angewendet wird. RB kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Es kann das RubyAlignattribute. haben. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference) | (Referenz) Ein Zitat zu Inhalten an anderer Stelle im Dokument. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp) | (Ruby-Interpunktion) Interpunktion, die den Ruby-Anmerkungstext umgibt. Es wird nur verwendet, wenn eine Ruby-Anmerkung nicht richtig in einem Ruby-Stil formatiert werden kann und stattdessen als normaler Kommentar formatiert wird, oder wenn sie als Warichu formatiert wird. Es enthält Text (normalerweise eine einzelne LINKE oder RECHTE KLAMMERN oder ähnliche Klammerzeichen). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt) | (Ruby-Anmerkungstext) Der kleinere Text, der neben dem Ruby-Basistext platziert werden soll. Es kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Es kann die Attribute RubyAlign und RubyPosition haben. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby) | (Ruby; PDF 1.5) Eine Randnotiz (Anmerkung), die in einer kleineren Textgröße geschrieben und neben dem Basistext platziert wird, auf den sie sich bezieht. Ein Ruby-Element kann auch die Elemente RB, RT und RP enthalten. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect) | (Abschnitt) Ein Container zum Gruppieren verwandter Inhaltselemente. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span) | (Span) Ein generischer Inline-Textabschnitt ohne besondere inhärente Eigenschaften. Es kann beispielsweise verwendet werden, um einen Textbereich mit einem bestimmten Satz von Stilattributen abzugrenzen. |
| static readonly [Table](../../aspose.pdf.logicalstructure/structuretypestandard/table) | (Tabelle) Ein zweidimensionales Layout von rechteckigen Datenzellen, möglicherweise mit einer komplexen Unterstruktur. Sie enthält entweder eine oder mehrere Tabellenzeilen (Strukturtyp TR) als Kinder; oder ein optionaler Tabellenkopf (Strukturtyp THead), gefolgt von einem oder mehreren Tabellenkörperelementen (Strukturtyp TBody) und einem optionalen Tabellenfuß (Strukturtyp TFoot). Zusätzlich kann eine Tabelle als erstes oder letztes Kind eine Beschriftung (Strukturtyp Caption) haben. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody) | (Tabellenkörper-Zeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die den Hauptteil einer Tabelle bilden. Wenn die Tabelle auf mehrere Seiten aufgeteilt ist, kann der Körperbereich an einer Zeilengrenze auseinander gebrochen werden. Eine Tabelle kann mehrere TBody-Elemente haben, um das Zeichnen eines Rahmens oder Hintergrunds für eine Reihe von Zeilen zu ermöglichen. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td) | (Tabellendatenzelle) Eine Tabellenzelle, die Daten enthält, die Teil des Tabelleninhalts sind. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot) | (Tabellenfußzeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die die Fußzeile einer Tabelle bilden. Wenn die Tabelle auf mehrere Seiten aufgeteilt ist, können diese Zeilen am Ende jedes Tabellenfragments neu gezeichnet werden (obwohl es nur ein TFoot-Element gibt.) |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th) | (Tabellenkopfzelle) Eine Tabellenzelle, die Kopfzeilentext enthält, der eine oder mehrere Zeilen oder Spalten der Tabelle beschreibt. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead) | (Tabellenkopf-Zeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die den Kopf einer Tabelle bilden. Wenn die Tabelle auf mehrere Seiten aufgeteilt ist, können diese Zeilen oben in jedem Tabellenfragment neu gezeichnet werden (obwohl es nur ein THead-Element gibt). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc) | (Inhaltsverzeichnis) Eine Liste, die aus Inhaltsverzeichniseinträgen (Strukturtyp TOCI) und/oder anderen verschachtelten Inhaltsverzeichniseinträgen (TOC) besteht. |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci) | (Element des Inhaltsverzeichnisses) Ein einzelnes Element eines Inhaltsverzeichnisses. Die untergeordneten Elemente dieses Eintrags können einer der folgenden Strukturtypen sein: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr) | (Tabellenzeile) Eine Zeile mit Überschriften oder Daten in einer Tabelle. Sie kann Tabellenkopfzellen und Tabellendatenzellen enthalten (Strukturtypen TH und TD). |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu) | (Warichu; PDF 1.5) Ein Kommentar oder eine Anmerkung in einer kleineren Textgröße und formatiert auf zwei kleinere Zeilen innerhalb der Höhe der enthaltenden Textzeile und nach (inline) dem Basistext platziert, auf den er sich bezieht. Ein Warichu-Element kann auch die WT- und WP-Elemente enthalten. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp) | (Warichu-Interpunktion) Die Interpunktion, die den WT-Text umgibt. Es enthält Text (normalerweise eine einzelne LINKE oder RECHTE KLAMMER oder ein ähnliches Klammerzeichen). Gemäß JIS X 4051-1995 können die Klammern, die ein Warichu umgeben, nach Ermessen des Formatierers in ein LEERZEICHEN (nominell 1/4 EM breit) umgewandelt werden. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt) | (Warichu-Text) Der kleinere Text eines Warichu-Kommentars, der in zwei Zeilen formatiert und zwischen umgebenden WP-Elementen platziert wird. |

### Siehe auch

* namensraum [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
