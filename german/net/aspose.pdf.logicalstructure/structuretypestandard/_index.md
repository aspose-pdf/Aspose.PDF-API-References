---
title: Class StructureTypeStandard
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.StructureTypeStandard-Klasse. Stellt Standardstrukturtypen dar
type: docs
weight: 6730
url: /de/net/aspose.pdf.logicalstructure/structuretypestandard/
---
## StructureTypeStandard-Klasse

Stellt Standardstrukturtypen dar.

```csharp
public sealed class StructureTypeStandard
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Kategorie](../../aspose.pdf.logicalstructure/structuretypestandard/category/) { get; } | Gibt die Kategorie des Standardstrukturtyps zurück. |
| [Tag](../../aspose.pdf.logicalstructure/structuretypestandard/tag/) { get; } | Gibt den Tag-Namen des [`StructureElement`](../structureelement/) zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [ToString](../../aspose.pdf.logicalstructure/structuretypestandard/tostring/)() | Gibt eine Zeichenfolge zurück, die das aktuelle Objekt darstellt. |
| [expliziter Operator](../../aspose.pdf.logicalstructure/structuretypestandard/op_explicit/) | Führt eine explizite Umwandlung von String in `StructureTypeStandard` durch. |

## Felder

| Name | Beschreibung |
| --- | --- |
| static readonly [Annot](../../aspose.pdf.logicalstructure/structuretypestandard/annot/) | (Annotation; PDF 1.5) Eine Zuordnung zwischen einem Teil des Inhalts der ILSE und einer entsprechenden PDF-Annotation. Annot sollte für alle PDF-Annotationen außer Link-Annotationen und Widget-Annotationen verwendet werden. |
| static readonly [Art](../../aspose.pdf.logicalstructure/structuretypestandard/art/) | (Artikel) Ein relativ eigenständiger Textkörper, der eine einzelne Erzählung oder Exposition darstellt. Artikel sollten disjunkt sein; das heißt, sie sollten keine anderen Artikel als Bestandteile enthalten. |
| static readonly [BibEntry](../../aspose.pdf.logicalstructure/structuretypestandard/bibentry/) | (Bibliographieeintrag) Ein Verweis, der die externe Quelle eines zitierten Inhalts identifiziert. Er kann ein Label (Strukturtyp Lbl) als Kind enthalten. |
| static readonly [BlockQuote](../../aspose.pdf.logicalstructure/structuretypestandard/blockquote/) | (Blockzitat) Ein Textabschnitt, der aus einem oder mehreren Absätzen besteht, die einer anderen Person als dem Autor des umgebenden Textes zugeschrieben werden. |
| static readonly [Caption](../../aspose.pdf.logicalstructure/structuretypestandard/caption/) | (Bildunterschrift) Ein kurzer Textabschnitt, der eine Tabelle oder Abbildung beschreibt. |
| static readonly [Code](../../aspose.pdf.logicalstructure/structuretypestandard/code/) | (Code) Ein Fragment von Computerprogrammiertext. |
| static readonly [Div](../../aspose.pdf.logicalstructure/structuretypestandard/div/) | (Division) Ein generisches Blockelement oder eine Gruppe von Elementen. |
| static readonly [Document](../../aspose.pdf.logicalstructure/structuretypestandard/document/) | (Dokument) Ein vollständiges Dokument. Dies ist das Wurzelelement eines Strukturbaums, der mehrere Teile oder mehrere Artikel enthält. |
| static readonly [Figure](../../aspose.pdf.logicalstructure/structuretypestandard/figure/) | (Abbildung) Ein Element grafischer Inhalte. Seine Platzierung kann mit dem Platzierungslayoutattribut angegeben werden. |
| static readonly [Form](../../aspose.pdf.logicalstructure/structuretypestandard/form/) | (Form) Eine Widget-Annotation, die ein interaktives Formularfeld darstellt. |
| static readonly [Formula](../../aspose.pdf.logicalstructure/structuretypestandard/formula/) | (Formel) Eine mathematische Formel. |
| static readonly [H](../../aspose.pdf.logicalstructure/structuretypestandard/h/) | (Überschrift) Ein Label für eine Unterteilung des Inhalts eines Dokuments. Es sollte das erste Kind der Division sein, die es anführt. |
| static readonly [H1](../../aspose.pdf.logicalstructure/structuretypestandard/h1/) | Überschrift der Stufe 1, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [H2](../../aspose.pdf.logicalstructure/structuretypestandard/h2/) | Überschrift der Stufe 2, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [H3](../../aspose.pdf.logicalstructure/structuretypestandard/h3/) | Überschrift der Stufe 3, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [H4](../../aspose.pdf.logicalstructure/structuretypestandard/h4/) | Überschrift der Stufe 4, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [H5](../../aspose.pdf.logicalstructure/structuretypestandard/h5/) | Überschrift der Stufe 5, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [H6](../../aspose.pdf.logicalstructure/structuretypestandard/h6/) | Überschrift der Stufe 6, für die Verwendung in konformen Schreibern, die ihre Abschnitte nicht hierarchisch verschachteln können und daher das Niveau einer Überschrift nicht aus ihrem Verschachtelungsgrad bestimmen können. |
| static readonly [Index](../../aspose.pdf.logicalstructure/structuretypestandard/index/) | (Index) Eine Sequenz von Einträgen, die identifizierenden Text enthält, begleitet von Referenzelementen, die auf Vorkommen des angegebenen Textes im Hauptteil eines Dokuments hinweisen. |
| static readonly [L](../../aspose.pdf.logicalstructure/structuretypestandard/l/) | (Liste) Eine Sequenz von Elementen mit ähnlicher Bedeutung und Wichtigkeit. Ihre unmittelbaren Kinder sollten eine optionale Bildunterschrift (Strukturtyp Caption) gefolgt von einem oder mehreren Listenelementen (Strukturtyp LI) sein. |
| static readonly [Lbl](../../aspose.pdf.logicalstructure/structuretypestandard/lbl/) | (Label) Ein Name oder eine Nummer, die ein bestimmtes Element von anderen in derselben Liste oder anderen Gruppen ähnlicher Elemente unterscheidet. |
| static readonly [LBody](../../aspose.pdf.logicalstructure/structuretypestandard/lbody/) | (Listeninhalt) Der beschreibende Inhalt eines Listenelements. In einer Wörterbuchliste enthält es beispielsweise die Definition des Begriffs. Es kann entweder den Inhalt direkt enthalten oder andere BLSEs, möglicherweise einschließlich verschachtelter Listen, als Kinder haben. |
| static readonly [LI](../../aspose.pdf.logicalstructure/structuretypestandard/li/) | (Listenelement) Ein einzelnes Mitglied einer Liste. Seine Kinder können ein oder mehrere Labels, Listeninhalte oder beides (Strukturtypen Lbl oder LBody) sein. |
| static readonly [Link](../../aspose.pdf.logicalstructure/structuretypestandard/link/) | (Link) Eine Zuordnung zwischen einem Teil des Inhalts der ILSE und einer entsprechenden Link-Annotation oder -Annotationen. Seine Kinder sollten ein oder mehrere Inhaltsobjekte oder untergeordnete ILSEs und ein oder mehrere Objektverweise enthalten, die die zugehörigen Link-Annotationen identifizieren. |
| static readonly [NonStruct](../../aspose.pdf.logicalstructure/structuretypestandard/nonstruct/) | (Nichtstrukturelement) Ein Gruppierungselement ohne inhärente strukturelle Bedeutung; es dient ausschließlich Gruppierungszwecken. Dieser Typ von Element unterscheidet sich von einer Division (Strukturtyp Div) darin, dass es nicht interpretiert oder in andere Dokumentformate exportiert werden soll; jedoch sollen seine Nachkommen normal verarbeitet werden. |
| static readonly [Note](../../aspose.pdf.logicalstructure/structuretypestandard/note/) | (Anmerkung) Ein Element erklärenden Textes, wie eine Fußnote oder eine Endnote, auf das im Text des Dokuments verwiesen wird. Es kann ein Label (Strukturtyp Lbl) als Kind haben. Die Anmerkung kann als Kind des Strukturelements im Fließtext, das darauf verweist, enthalten sein oder an anderer Stelle (z. B. in einem Endnotenteil) enthalten sein und über einen Verweis (Strukturtyp Reference) aufgerufen werden. |
| static readonly [P](../../aspose.pdf.logicalstructure/structuretypestandard/p/) | (Absatz) Eine niedrigstufige Unterteilung von Text. |
| static readonly [Part](../../aspose.pdf.logicalstructure/structuretypestandard/part/) | (Teil) Eine großflächige Unterteilung eines Dokuments. Dieser Typ von Element ist geeignet, um Artikel oder Abschnitte zu gruppieren. |
| static readonly [Private](../../aspose.pdf.logicalstructure/structuretypestandard/private/) | (Privates Element) Ein Gruppierungselement, das private Inhalte enthält, die der Anwendung gehören, die es erzeugt. Die strukturelle Bedeutung dieses Typs von Element ist unbestimmt und wird vollständig vom konformen Schreiber bestimmt. Weder das Private Element noch eines seiner Nachkommen sollen interpretiert oder in andere Dokumentformate exportiert werden. |
| static readonly [Quote](../../aspose.pdf.logicalstructure/structuretypestandard/quote/) | (Zitat) Ein Inline-Textabschnitt, der einer anderen Person als dem Autor des umgebenden Textes zugeschrieben wird. |
| static readonly [RB](../../aspose.pdf.logicalstructure/structuretypestandard/rb/) | (Ruby-Basistext) Der Volltext, auf den die Ruby-Annotation angewendet wird. RB kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Es kann das RubyAlign-Attribut haben. |
| static readonly [Reference](../../aspose.pdf.logicalstructure/structuretypestandard/reference/) | (Referenz) Ein Zitat zu Inhalten an anderer Stelle im Dokument. |
| static readonly [RP](../../aspose.pdf.logicalstructure/structuretypestandard/rp/) | (Ruby-Zeichensetzung) Zeichensetzung, die den Ruby-Annotationstext umgibt. Sie wird nur verwendet, wenn eine Ruby-Annotation nicht ordnungsgemäß im Ruby-Stil formatiert werden kann und stattdessen als normaler Kommentar formatiert wird, oder wenn sie als Warichu formatiert wird. Sie enthält Text (normalerweise eine einzelne linke oder rechte Klammer oder ein ähnliches umschließendes Zeichen). |
| static readonly [RT](../../aspose.pdf.logicalstructure/structuretypestandard/rt/) | (Ruby-Annotationstext) Der kleinere Text, der neben dem Ruby-Basistext platziert werden soll. Er kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Er kann die RubyAlign- und RubyPosition-Attribute haben. |
| static readonly [Ruby](../../aspose.pdf.logicalstructure/structuretypestandard/ruby/) | (Ruby; PDF 1.5) Eine Fußnote (Annotation), die in einer kleineren Schriftgröße geschrieben und neben dem Basistext platziert wird, auf den sie sich bezieht. Ein Ruby-Element kann auch die RB-, RT- und RP-Elemente enthalten. |
| static readonly [Sect](../../aspose.pdf.logicalstructure/structuretypestandard/sect/) | (Sektion) Ein Container zum Gruppieren verwandter Inhaltselemente. |
| static readonly [Span](../../aspose.pdf.logicalstructure/structuretypestandard/span/) | (Span) Ein generischer Inline-Textabschnitt ohne besondere inhärente Eigenschaften. Er kann beispielsweise verwendet werden, um einen Textbereich mit einem bestimmten Satz von Stilattributen zu begrenzen. |
| static readonly [Tabelle](../../aspose.pdf.logicalstructure/structuretypestandard/table/) | (Tabelle) Ein zweidimensionales Layout von rechteckigen Datenzellen, möglicherweise mit einer komplexen Unterstruktur. Sie enthält entweder eine oder mehrere Tabellenzeilen (Strukturtyp TR) als Kinder; oder einen optionalen Tabellenkopf (Strukturtyp THead), gefolgt von einem oder mehreren Tabellenkörper-Elementen (Strukturtyp TBody) und einem optionalen Tabellenfuß (Strukturtyp TFoot). Darüber hinaus kann eine Tabelle eine Bildunterschrift (Strukturtyp Caption) als ihr erstes oder letztes Kind haben. |
| static readonly [TBody](../../aspose.pdf.logicalstructure/structuretypestandard/tbody/) | (Tabellenkörperzeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die den Hauptteil einer Tabelle bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, kann der Körperbereich an einer Zeilenbegrenzung getrennt werden. Eine Tabelle kann mehrere TBody-Elemente haben, um das Zeichnen eines Rahmens oder Hintergrunds für eine Gruppe von Zeilen zu ermöglichen. |
| static readonly [TD](../../aspose.pdf.logicalstructure/structuretypestandard/td/) | (Tabellendatenzelle) Eine Tabellenzelle, die Daten enthält, die Teil des Inhalts der Tabelle sind. |
| static readonly [TFoot](../../aspose.pdf.logicalstructure/structuretypestandard/tfoot/) | (Tabellenfußzeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die den Fuß einer Tabelle bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen am Ende jedes Tabellenfragmentes neu gezeichnet werden (obwohl es nur ein TFoot-Element gibt). |
| static readonly [TH](../../aspose.pdf.logicalstructure/structuretypestandard/th/) | (Tabellenkopfzelle) Eine Tabellenzelle, die Kopftext enthält, der eine oder mehrere Zeilen oder Spalten der Tabelle beschreibt. |
| static readonly [THead](../../aspose.pdf.logicalstructure/structuretypestandard/thead/) | (Tabellenkopfzeilengruppe; PDF 1.5) Eine Gruppe von Zeilen, die den Kopf einer Tabelle bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen am Anfang jedes Tabellenfragmentes neu gezeichnet werden (obwohl es nur ein THead-Element gibt). |
| static readonly [TOC](../../aspose.pdf.logicalstructure/structuretypestandard/toc/) | (Inhaltsverzeichnis) Eine Liste, die aus Einträgen von Inhaltsverzeichnis-Elementen (Strukturtyp TOCI) und/oder anderen verschachtelten Inhaltsverzeichniseinträgen (TOC) besteht. |
| static readonly [TOCI](../../aspose.pdf.logicalstructure/structuretypestandard/toci/) | (Inhaltsverzeichniselement) Ein einzelnes Mitglied eines Inhaltsverzeichnisses. Die Kinder dieses Eintrags können einer der folgenden Strukturtypen sein: |
| static readonly [TR](../../aspose.pdf.logicalstructure/structuretypestandard/tr/) | (Tabellenzeile) Eine Zeile von Überschriften oder Daten in einer Tabelle. Sie kann Tabellenkopfzellen und Tabellendatenzellen (Strukturtypen TH und TD) enthalten. |
| static readonly [Warichu](../../aspose.pdf.logicalstructure/structuretypestandard/warichu/) | (Warichu; PDF 1.5) Ein Kommentar oder eine Annotation in einer kleineren Schriftgröße, die auf zwei kleinere Zeilen innerhalb der Höhe der umgebenden Textzeile formatiert und nach (inline) dem Basistext platziert wird, auf den sie sich bezieht. Ein Warichu-Element kann auch die WT- und WP-Elemente enthalten. |
| static readonly [WP](../../aspose.pdf.logicalstructure/structuretypestandard/wp/) | (Warichu-Zeichensetzung) Die Zeichensetzung, die den WT-Text umgibt. Sie enthält Text (normalerweise eine einzelne linke oder rechte Klammer oder ein ähnliches umschließendes Zeichen). Laut JIS X 4051-1995 können die Klammern, die einen Warichu umgeben, nach Ermessen des Formatierers in einen LEERZEICHEN (nominal 1/4 EM in Breite) umgewandelt werden. |
| static readonly [WT](../../aspose.pdf.logicalstructure/structuretypestandard/wt/) | (Warichu-Text) Der kleinere Text eines Warichu-Kommentars, der in zwei Zeilen formatiert und zwischen den umgebenden WP-Elementen platziert wird. |

### Siehe auch

* Namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* Assembly [Aspose.PDF](../../)