---
title: "StructureTypeStandard"
linktitle: "StructureTypeStandard"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt Standard-Strukturtypen dar."
type: docs
weight: 130
url: /de/java/com.aspose.pdf.tagged.logicalstructure/structuretypestandard/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard

```
public final class StructureTypeStandard extends Object
```

Stellt Standard-Strukturtypen dar.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [Annot](#Annot) | (Annotation; PDF 1.5) Eine Zuordnung zwischen einem Teil des ILSE-Inhalts und einer entsprechenden PDF-Annotation. Annot soll für alle PDF-Annotationen verwendet werden, außer Link-Annotationen und Widget-Annotationen. |
| [Art](#Art) | (Article) Ein relativ eigenständiger Textkörper, der eine einzelne Erzählung oder Darstellung bildet. Artikel sollten disjunkt sein; das heißt, sie sollten keine anderen Artikel als Bestandteile enthalten. |
| [BibEntry](#BibEntry) | (Bibliography entry) Ein Verweis, der die externe Quelle eines zitierten Inhalts identifiziert. Er kann ein Label (Strukturtyp Lbl) als Kind enthalten. Obwohl ein Bibliographieeintrag wahrscheinlich Komponenten enthält, die den Autor, das Werk, den Verlag usw. des zitierten Inhalts identifizieren, sind auf dieser Detailebene keine Standard-Strukturtypen definiert. |
| [BlockQuote](#BlockQuote) | (Block quotation) Ein Textabschnitt, der aus einem oder mehreren Absätzen besteht und jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird. |
| [Caption](#Caption) | (Caption) Ein kurzer Textabschnitt, der eine Tabelle oder Abbildung beschreibt. |
| [Code](#Code) | (Code) Ein Fragment von Computerprogrammtext. |
| [Div](#Div) | (Division) Ein generisches Block-Element oder eine Gruppe von Elementen. |
| [Document](#Document) | (Document) Ein vollständiges Dokument. Dies ist das Wurzelelement jedes Strukturbaums, der mehrere Teile oder mehrere Artikel enthält. |
| [Figure](#Figure) | (Figure) Ein Element grafischer Inhalte. Seine Platzierung kann mit dem Layout-Attribut Placement angegeben werden. |
| [Form](#Form) | (Form) Eine Widget-Annotation, die ein interaktives Formularfeld darstellt. |
| [Formula](#Formula) | (Formula) Eine mathematische Formel. Dieser Strukturtyp ist nur nützlich, um ein gesamtes Inhaltselement als Formel zu kennzeichnen. Es sind keine Standard-Strukturtypen definiert, um einzelne Komponenten innerhalb der Formel zu identifizieren. Aus formatierungstechnischer Sicht soll die Formel ähnlich wie eine Abbildung (Strukturtyp Figure) behandelt werden. |
| [H](#H) | (Heading) Ein Label für eine Unterteilung des Dokumenteninhalts. Es sollte das erste Kind der Division sein, die es überschreibt. |
| [H1](#H1) | Level‑1‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| [H2](#H2) | Level‑2‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| [H3](#H3) | Level‑3‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| [H4](#H4) | Level‑4‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| [H5](#H5) | Level‑5‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelungsebene bestimmen können. |
| [H6](#H6) | Level‑6‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelungsebene bestimmen können. |
| [Index](#Index) | (Index) Eine Sequenz von Einträgen, die identifizierenden Text enthalten, begleitet von Referenzelementen, die Vorkommen des angegebenen Textes im Hauptteil eines Dokuments aufzeigen. |
| [L](#L) | (List) Eine Sequenz von Elementen gleicher Bedeutung und Wichtigkeit. Seine unmittelbaren Kinder sollten eine optionale Beschriftung (Strukturtyp Caption) gefolgt von einem oder mehreren Listeneinträgen (Strukturtyp LI) sein. |
| [Lbl](#Lbl) | (Label) Ein Name oder eine Nummer, die ein bestimmtes Element von anderen im selben Verzeichnis oder einer anderen Gruppe ähnlicher Elemente unterscheidet. |
| [LBody](#LBody) | (List body) Der beschreibende Inhalt eines Listeneintrags. In einer Wörterbuchliste enthält er beispielsweise die Definition des Begriffs. Er kann den Inhalt direkt enthalten oder weitere BLSEs, möglicherweise verschachtelte Listen, als Kinder haben. |
| [LI](#LI) | (List item) Ein einzelnes Element einer Liste. Seine Kinder können ein oder mehrere Labels, Listenkörper oder beides sein (Strukturtypen Lbl oder LBody). |
| [Link](#Link) | (Link) Eine Zuordnung zwischen einem Teil des ILSE‑Inhalts und einer entsprechenden Link‑Annotation oder Annotationen. Seine Kinder sollten ein oder mehrere Inhaltsobjekte oder untergeordnete ILSEs sowie ein oder mehrere Objektverweise, die die zugehörigen Link‑Annotationen identifizieren, sein. |
| [NonStruct](#NonStruct) | (Nonstructural element) Ein Gruppierungselement ohne inhärente strukturelle Bedeutung; es dient ausschließlich Gruppierungszwecken. Dieser Elementtyp unterscheidet sich von einer Division (Strukturtyp Div) darin, dass er nicht interpretiert oder in andere Dokumentformate exportiert werden darf; seine Nachkommen hingegen werden normal verarbeitet. |
| [Note](#Note) | (Note) Ein Element erklärenden Textes, wie eine Fußnote oder Endnote, das aus dem Haupttext des Dokuments referenziert wird. Es kann ein Label (Strukturtyp Lbl) als Kind besitzen. Die Notiz kann als Kind des Strukturelements im Fließtext, das darauf verweist, eingebettet sein oder an anderer Stelle (z. B. in einem Endnoten‑Abschnitt) platziert und über einen Verweis (Strukturtyp Reference) aufgerufen werden. Tagged PDF legt die Platzierung von Fußnoten in der Seiteninhaltsreihenfolge nicht fest. Sie können sowohl inline als auch am Seitenende, nach Ermessen des konformen Schreibprogramms, erscheinen. |
| [P](#P) | (Paragraph) Eine niedrigstufige Unterteilung von Text. |
| [Part](#Part) | (Part) Eine großflächige Unterteilung eines Dokuments. Dieser Elementtyp eignet sich zum Gruppieren von Artikeln oder Abschnitten. |
| [Private](#Private) | (Private element) Ein Gruppierungselement, das privaten Inhalt enthält, der zur erzeugenden Anwendung gehört. Die strukturelle Bedeutung dieses Elementtyps ist nicht festgelegt und wird vollständig vom konformen Schreibprogramm bestimmt. Weder das Private‑Element noch seine Nachkommen dürfen interpretiert oder in andere Dokumentformate exportiert werden. |
| [Quote](#Quote) | (Quotation) Ein Inline‑Abschnitt Text, der jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird. Der zitierte Text sollte inline innerhalb eines einzelnen Absatzes enthalten sein. Dies unterscheidet sich vom Block‑Element BlockQuote, das aus einem oder mehreren vollständigen Absätzen (oder anderen Elementen, die so dargestellt werden, als wären sie vollständige Absätze) besteht. |
| [RB](#RB) | (Ruby base text) Der Volltext, auf den die Ruby‑Annotation angewendet wird. RB kann Text, andere Inline‑Elemente oder eine Mischung aus beidem enthalten. Es kann das RubyAlignattribute besitzen. |
| [Reference](#Reference) | (Reference) Ein Verweis auf Inhalte an anderer Stelle im Dokument. |
| [RP](#RP) | (Ruby punctuation) Satzzeichen, die den Ruby‑Annotationstext umgeben. Sie werden nur verwendet, wenn eine Ruby‑Annotation nicht korrekt im Ruby‑Stil formatiert werden kann und stattdessen als normaler Kommentar formatiert wird, oder wenn sie als Warichu formatiert ist. Sie enthalten Text (in der Regel eine einzelne LINKSKLAMMER oder RECHTSKLAMMER bzw. ein ähnliches Klammerzeichen). |
| [RT](#RT) | (Ruby annotation text) Der kleinformatige Text, der neben dem Ruby‑Basistext platziert werden soll. Er kann Text, andere Inline‑Elemente oder eine Mischung aus beidem enthalten. Er kann die Attribute RubyAlign und RubyPosition besitzen. |
| [Ruby](#Ruby) | (Ruby; PDF 1.5) Eine Randnotiz (Annotation), die in kleinerer Schriftgröße geschrieben und neben dem Basistext platziert wird, auf den sie sich bezieht. Ein Ruby‑Element kann außerdem die Elemente RB, RT und RP enthalten. (Ruby) Der Wrapper um die gesamte Ruby‑Zusammenstellung. Er muss ein RB‑Element enthalten, gefolgt entweder von einem RT‑Element oder einer Dreiergruppe bestehend aus RP, RT und RP. Ruby‑Elemente und ihre Inhaltselemente dürfen nicht über mehrere Zeilen hinweg umbrochen werden. |
| [Sect](#Sect) | (Section) Ein Container zum Gruppieren verwandter Inhaltselemente. |
| [Span](#Span) | (Span) Ein generischer Inline‑Abschnitt von Text ohne besondere inhärente Merkmale. Er kann beispielsweise verwendet werden, um einen Textbereich mit einer bestimmten Menge von Stil‑Attributen abzugrenzen. |
| [Table](#Table) | (Table) Ein zweidimensionales Layout aus rechteckigen Datenzellen, das möglicherweise eine komplexe Unterstruktur aufweist. Es enthält entweder eine oder mehrere Tabellenzeilen (Strukturtyp TR) als Kinder; oder einen optionalen Tabellenkopf (Strukturtyp THead), gefolgt von einer oder mehreren Tabellenkörper‑Elementen (Strukturtyp TBody) und einem optionalen Tabellenfuß (Strukturtyp TFoot). Zusätzlich kann eine Tabelle eine Beschriftung (Strukturtyp Caption) als erstes oder letztes Kind besitzen. |
| [TBody](#TBody) | (Table body row group; PDF 1.5) Eine Gruppe von Zeilen, die den Hauptkörperteil einer Tabelle bilden. Wird die Tabelle über mehrere Seiten verteilt, kann der Körperbereich an einer Zeilen­grenze aufgeteilt werden. Eine Tabelle kann mehrere TBody‑Elemente besitzen, um für eine Reihe von Zeilen einen Rahmen oder Hintergrund zu zeichnen. |
| [TD](#TD) | (Table data cell) Eine Tabellenzelle, die Daten enthält und Teil des Tabelleninhalts ist. |
| [TFoot](#TFoot) | (Table footer row group; PDF 1.5) Eine Gruppe von Zeilen, die den Fußbereich einer Tabelle bilden. Wird die Tabelle über mehrere Seiten verteilt, können diese Zeilen am unteren Ende jedes Tabellenteils neu gezeichnet werden (obwohl es nur ein TFoot‑Element gibt). |
| [TH](#TH) | (Table header cell) Eine Tabellenzelle, die Überschriftstext enthält, der eine oder mehrere Zeilen oder Spalten der Tabelle beschreibt. |
| [THead](#THead) | (Table header row group; PDF 1.5) Eine Gruppe von Zeilen, die den Tabellenkopf bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen oben in jedem Tabellenfragment neu gezeichnet werden (obwohl es nur ein THead-Element gibt). |
| [TOC](#TOC) | (Table of contents) Eine Liste, die aus Einträgen von Inhaltsverzeichniselementen (Strukturtyp TOCI) und/oder anderen verschachtelten Inhaltsverzeichniseinträgen (TOC) besteht. Ein TOC-Eintrag, der nur TOCI-Einträge enthält, stellt eine flache Hierarchie dar. Ein TOC-Eintrag, der andere verschachtelte TOC-Einträge (und möglicherweise TOCI-Einträge) enthält, stellt eine komplexere Hierarchie dar. Idealerweise spiegelt die Hierarchie eines TOC-Eintrags der obersten Ebene die Struktur des Hauptkörpers des Dokuments wider. |
| [TOCI](#TOCI) | (Table of contents item) Ein einzelnes Element eines Inhaltsverzeichnisses. Die Unterelemente dieses Eintrags können einer der folgenden Strukturtypen sein: Lbl – Ein Etikett, Reference – Eine Referenz zum Titel und zur Seitenzahl, NonStruct – Nicht‑Strukturelemente zum Einhüllen eines Führungsartefakts, P – Beschreibender Text, TOC – Inhaltsverzeichniselemente für hierarchische Inhaltsverzeichnisse, wie für den TOC‑Eintrag beschrieben. |
| [TR](#TR) | (Table row) Eine Zeile mit Überschriften oder Daten in einer Tabelle. Sie kann Tabellenkopf‑Zellen und Tabellendaten‑Zellen (Strukturtypen TH und TD) enthalten. |
| [Warichu](#Warichu) | (Warichu; PDF 1.5) Ein Kommentar oder eine Anmerkung in kleinerer Schriftgröße, die auf zwei kleinere Zeilen innerhalb der Höhe der umgebenden Textzeile formatiert wird und dem Basistext (inline) folgt, auf den sie sich bezieht. Ein Warichu‑Element kann auch die WT‑ und WP‑Elemente enthalten. (Warichu) Der Wrapper um die gesamte Warichu‑Zusammenstellung. Er kann eine dreiteilige Gruppe bestehend aus WP, WT und WP enthalten. Warichu‑Elemente (und ihre Inhaltselemente) können sich über mehrere Zeilen erstrecken, gemäß den Warichu‑Umbruchregeln, die im Japanese Industrial Standard (JIS) X 4051-1995 beschrieben sind. |
| [WP](#WP) | (Warichu punctuation) Die Interpunktion, die den WT‑Text umgibt. Sie enthält Text (in der Regel eine einzelne linke oder rechte Klammer oder ein ähnliches Klammerzeichen). Laut JIS X 4051-1995 können die Klammern, die ein Warichu umschließen, nach Ermessen des Formatierers in ein LEERZEICHEN (nominal 1/4 EM in der Breite) umgewandelt werden. |
| [WT](#WT) | (Warichu text) Der kleinformatige Text eines Warichu‑Kommentars, der in zwei Zeilen formatiert und zwischen den umgebenden WP‑Elementen platziert wird. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canBeAppended](#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-) |  |
| [createElement](#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
| [getCategory](#getCategory--) | Liefert die Kategorie des Standard‑Strukturtyps. |
| [getTag](#getTag--) | Liefert den Tag-Namen von {@code StructureElement}. |
| [to_StructureTypeStandard](#to_StructureTypeStandard-java.lang.String-) | Führt eine explizite Konvertierung von {@link String} zu {@link StructureTypeStandard} durch. |
| [toString](#toString--) | Gibt einen String zurück, der das aktuelle Objekt darstellt. |

### Annot {#Annot}
```
public static final StructureTypeStandard Annot
```

(Annotation; PDF 1.5) Eine Zuordnung zwischen einem Teil des ILSE-Inhalts und einer entsprechenden PDF-Annotation. Annot soll für alle PDF-Annotationen verwendet werden, außer Link-Annotationen und Widget-Annotationen.

### Art {#Art}
```
public static final StructureTypeStandard Art
```

(Article) Ein relativ eigenständiger Textkörper, der eine einzelne Erzählung oder Darstellung bildet. Artikel sollten disjunkt sein; das heißt, sie sollten keine anderen Artikel als Bestandteile enthalten.

### BibEntry {#BibEntry}
```
public static final StructureTypeStandard BibEntry
```

(Bibliography entry) Ein Verweis, der die externe Quelle eines zitierten Inhalts identifiziert. Er kann ein Label (Strukturtyp Lbl) als Kind enthalten. Obwohl ein Bibliographieeintrag wahrscheinlich Komponenten enthält, die den Autor, das Werk, den Verlag usw. des zitierten Inhalts identifizieren, sind auf dieser Detailebene keine Standard-Strukturtypen definiert.

### BlockQuote {#BlockQuote}
```
public static final StructureTypeStandard BlockQuote
```

(Block quotation) Ein Textabschnitt, der aus einem oder mehreren Absätzen besteht und jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird.

### Caption {#Caption}
```
public static final StructureTypeStandard Caption
```

(Caption) Ein kurzer Textabschnitt, der eine Tabelle oder Abbildung beschreibt.

### Code {#Code}
```
public static final StructureTypeStandard Code
```

(Code) Ein Fragment von Computerprogrammtext.

### Div {#Div}
```
public static final StructureTypeStandard Div
```

(Division) Ein generisches Block-Element oder eine Gruppe von Elementen.

### Document {#Document}
```
public static final StructureTypeStandard Document
```

(Document) Ein vollständiges Dokument. Dies ist das Wurzelelement jedes Strukturbaums, der mehrere Teile oder mehrere Artikel enthält.

### Figure {#Figure}
```
public static final StructureTypeStandard Figure
```

(Figure) Ein Element grafischer Inhalte. Seine Platzierung kann mit dem Layout-Attribut Placement angegeben werden.

### Form {#Form}
```
public static final StructureTypeStandard Form
```

(Form) Eine Widget-Annotation, die ein interaktives Formularfeld darstellt.

### Formula {#Formula}
```
public static final StructureTypeStandard Formula
```

(Formula) Eine mathematische Formel. Dieser Strukturtyp ist nur nützlich, um ein gesamtes Inhaltselement als Formel zu kennzeichnen. Es sind keine Standard-Strukturtypen definiert, um einzelne Komponenten innerhalb der Formel zu identifizieren. Aus formatierungstechnischer Sicht soll die Formel ähnlich wie eine Abbildung (Strukturtyp Figure) behandelt werden.

### H {#H}
```
public static final StructureTypeStandard H
```

(Heading) Ein Label für eine Unterteilung des Dokumenteninhalts. Es sollte das erste Kind der Division sein, die es überschreibt.

### H1 {#H1}
```
public static final StructureTypeStandard H1
```

Level‑1‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können.

### H2 {#H2}
```
public static final StructureTypeStandard H2
```

Level‑2‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können.

### H3 {#H3}
```
public static final StructureTypeStandard H3
```

Level‑3‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können.

### H4 {#H4}
```
public static final StructureTypeStandard H4
```

Level‑4‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können.

### H5 {#H5}
```
public static final StructureTypeStandard H5
```

Level‑5‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelungsebene bestimmen können.

### H6 {#H6}
```
public static final StructureTypeStandard H6
```

Level‑6‑Überschrift, zur Verwendung in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelungsebene bestimmen können.

### Index {#Index}
```
public static final StructureTypeStandard Index
```

(Index) Eine Sequenz von Einträgen, die identifizierenden Text enthalten, begleitet von Referenzelementen, die Vorkommen des angegebenen Textes im Hauptteil eines Dokuments aufzeigen.

### L {#L}
```
public static final StructureTypeStandard L
```

(List) Eine Sequenz von Elementen gleicher Bedeutung und Wichtigkeit. Seine unmittelbaren Kinder sollten eine optionale Beschriftung (Strukturtyp Caption) gefolgt von einem oder mehreren Listeneinträgen (Strukturtyp LI) sein.

### Lbl {#Lbl}
```
public static final StructureTypeStandard Lbl
```

(Label) Ein Name oder eine Nummer, die ein bestimmtes Element von anderen im selben Verzeichnis oder einer anderen Gruppe ähnlicher Elemente unterscheidet.

### LBody {#LBody}
```
public static final StructureTypeStandard LBody
```

(List body) Der beschreibende Inhalt eines Listeneintrags. In einer Wörterbuchliste enthält er beispielsweise die Definition des Begriffs. Er kann den Inhalt direkt enthalten oder weitere BLSEs, möglicherweise verschachtelte Listen, als Kinder haben.

### LI {#LI}
```
public static final StructureTypeStandard LI
```

(List item) Ein einzelnes Element einer Liste. Seine Kinder können ein oder mehrere Labels, Listenkörper oder beides sein (Strukturtypen Lbl oder LBody).

### Link {#Link}
```
public static final StructureTypeStandard Link
```

(Link) Eine Zuordnung zwischen einem Teil des ILSE‑Inhalts und einer entsprechenden Link‑Annotation oder Annotationen. Seine Kinder sollten ein oder mehrere Inhaltsobjekte oder untergeordnete ILSEs sowie ein oder mehrere Objektverweise, die die zugehörigen Link‑Annotationen identifizieren, sein.

### NonStruct {#NonStruct}
```
public static final StructureTypeStandard NonStruct
```

(Nonstructural element) Ein Gruppierungselement ohne inhärente strukturelle Bedeutung; es dient ausschließlich Gruppierungszwecken. Dieser Elementtyp unterscheidet sich von einer Division (Strukturtyp Div) darin, dass er nicht interpretiert oder in andere Dokumentformate exportiert werden darf; seine Nachkommen hingegen werden normal verarbeitet.

### Note {#Note}
```
public static final StructureTypeStandard Note
```

(Note) Ein Element erklärenden Textes, wie eine Fußnote oder Endnote, das aus dem Haupttext des Dokuments referenziert wird. Es kann ein Label (Strukturtyp Lbl) als Kind besitzen. Die Notiz kann als Kind des Strukturelements im Fließtext, das darauf verweist, eingebettet sein oder an anderer Stelle (z. B. in einem Endnoten‑Abschnitt) platziert und über einen Verweis (Strukturtyp Reference) aufgerufen werden. Tagged PDF legt die Platzierung von Fußnoten in der Seiteninhaltsreihenfolge nicht fest. Sie können sowohl inline als auch am Seitenende, nach Ermessen des konformen Schreibprogramms, erscheinen.

### P {#P}
```
public static final StructureTypeStandard P
```

(Paragraph) Eine niedrigstufige Unterteilung von Text.

### Part {#Part}
```
public static final StructureTypeStandard Part
```

(Part) Eine großflächige Unterteilung eines Dokuments. Dieser Elementtyp eignet sich zum Gruppieren von Artikeln oder Abschnitten.

### Private {#Private}
```
public static final StructureTypeStandard Private
```

(Private element) Ein Gruppierungselement, das privaten Inhalt enthält, der zur erzeugenden Anwendung gehört. Die strukturelle Bedeutung dieses Elementtyps ist nicht festgelegt und wird vollständig vom konformen Schreibprogramm bestimmt. Weder das Private‑Element noch seine Nachkommen dürfen interpretiert oder in andere Dokumentformate exportiert werden.

### Quote {#Quote}
```
public static final StructureTypeStandard Quote
```

(Quotation) Ein Inline‑Abschnitt Text, der jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird. Der zitierte Text sollte inline innerhalb eines einzelnen Absatzes enthalten sein. Dies unterscheidet sich vom Block‑Element BlockQuote, das aus einem oder mehreren vollständigen Absätzen (oder anderen Elementen, die so dargestellt werden, als wären sie vollständige Absätze) besteht.

### RB {#RB}
```
public static final StructureTypeStandard RB
```

(Ruby base text) Der Volltext, auf den die Ruby‑Annotation angewendet wird. RB kann Text, andere Inline‑Elemente oder eine Mischung aus beidem enthalten. Es kann das RubyAlignattribute besitzen.

### Reference {#Reference}
```
public static final StructureTypeStandard Reference
```

(Reference) Ein Verweis auf Inhalte an anderer Stelle im Dokument.

### RP {#RP}
```
public static final StructureTypeStandard RP
```

(Ruby punctuation) Satzzeichen, die den Ruby‑Annotationstext umgeben. Sie werden nur verwendet, wenn eine Ruby‑Annotation nicht korrekt im Ruby‑Stil formatiert werden kann und stattdessen als normaler Kommentar formatiert wird, oder wenn sie als Warichu formatiert ist. Sie enthalten Text (in der Regel eine einzelne LINKSKLAMMER oder RECHTSKLAMMER bzw. ein ähnliches Klammerzeichen).

### RT {#RT}
```
public static final StructureTypeStandard RT
```

(Ruby annotation text) Der kleinformatige Text, der neben dem Ruby‑Basistext platziert werden soll. Er kann Text, andere Inline‑Elemente oder eine Mischung aus beidem enthalten. Er kann die Attribute RubyAlign und RubyPosition besitzen.

### Ruby {#Ruby}
```
public static final StructureTypeStandard Ruby
```

(Ruby; PDF 1.5) Eine Randnotiz (Annotation), die in kleinerer Schriftgröße geschrieben und neben dem Basistext platziert wird, auf den sie sich bezieht. Ein Ruby‑Element kann außerdem die Elemente RB, RT und RP enthalten. (Ruby) Der Wrapper um die gesamte Ruby‑Zusammenstellung. Er muss ein RB‑Element enthalten, gefolgt entweder von einem RT‑Element oder einer Dreiergruppe bestehend aus RP, RT und RP. Ruby‑Elemente und ihre Inhaltselemente dürfen nicht über mehrere Zeilen hinweg umbrochen werden.

### Sect {#Sect}
```
public static final StructureTypeStandard Sect
```

(Section) Ein Container zum Gruppieren verwandter Inhaltselemente.

### Span {#Span}
```
public static final StructureTypeStandard Span
```

(Span) Ein generischer Inline‑Abschnitt von Text ohne besondere inhärente Merkmale. Er kann beispielsweise verwendet werden, um einen Textbereich mit einer bestimmten Menge von Stil‑Attributen abzugrenzen.

### Table {#Table}
```
public static final StructureTypeStandard Table
```

(Table) Ein zweidimensionales Layout aus rechteckigen Datenzellen, das möglicherweise eine komplexe Unterstruktur aufweist. Es enthält entweder eine oder mehrere Tabellenzeilen (Strukturtyp TR) als Kinder; oder einen optionalen Tabellenkopf (Strukturtyp THead), gefolgt von einer oder mehreren Tabellenkörper‑Elementen (Strukturtyp TBody) und einem optionalen Tabellenfuß (Strukturtyp TFoot). Zusätzlich kann eine Tabelle eine Beschriftung (Strukturtyp Caption) als erstes oder letztes Kind besitzen.

### TBody {#TBody}
```
public static final StructureTypeStandard TBody
```

(Table body row group; PDF 1.5) Eine Gruppe von Zeilen, die den Hauptkörperteil einer Tabelle bilden. Wird die Tabelle über mehrere Seiten verteilt, kann der Körperbereich an einer Zeilen­grenze aufgeteilt werden. Eine Tabelle kann mehrere TBody‑Elemente besitzen, um für eine Reihe von Zeilen einen Rahmen oder Hintergrund zu zeichnen.

### TD {#TD}
```
public static final StructureTypeStandard TD
```

(Table data cell) Eine Tabellenzelle, die Daten enthält und Teil des Tabelleninhalts ist.

### TFoot {#TFoot}
```
public static final StructureTypeStandard TFoot
```

(Table footer row group; PDF 1.5) Eine Gruppe von Zeilen, die den Fußbereich einer Tabelle bilden. Wird die Tabelle über mehrere Seiten verteilt, können diese Zeilen am unteren Ende jedes Tabellenteils neu gezeichnet werden (obwohl es nur ein TFoot‑Element gibt).

### TH {#TH}
```
public static final StructureTypeStandard TH
```

(Table header cell) Eine Tabellenzelle, die Überschriftstext enthält, der eine oder mehrere Zeilen oder Spalten der Tabelle beschreibt.

### THead {#THead}
```
public static final StructureTypeStandard THead
```

(Table header row group; PDF 1.5) Eine Gruppe von Zeilen, die den Tabellenkopf bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen oben in jedem Tabellenfragment neu gezeichnet werden (obwohl es nur ein THead-Element gibt).

### TOC {#TOC}
```
public static final StructureTypeStandard TOC
```

(Table of contents) Eine Liste, die aus Einträgen von Inhaltsverzeichniselementen (Strukturtyp TOCI) und/oder anderen verschachtelten Inhaltsverzeichniseinträgen (TOC) besteht. Ein TOC-Eintrag, der nur TOCI-Einträge enthält, stellt eine flache Hierarchie dar. Ein TOC-Eintrag, der andere verschachtelte TOC-Einträge (und möglicherweise TOCI-Einträge) enthält, stellt eine komplexere Hierarchie dar. Idealerweise spiegelt die Hierarchie eines TOC-Eintrags der obersten Ebene die Struktur des Hauptkörpers des Dokuments wider.

### TOCI {#TOCI}
```
public static final StructureTypeStandard TOCI
```

(Table of contents item) Ein einzelnes Element eines Inhaltsverzeichnisses. Die Unterelemente dieses Eintrags können einer der folgenden Strukturtypen sein: Lbl – Ein Etikett, Reference – Eine Referenz zum Titel und zur Seitenzahl, NonStruct – Nicht‑Strukturelemente zum Einhüllen eines Führungsartefakts, P – Beschreibender Text, TOC – Inhaltsverzeichniselemente für hierarchische Inhaltsverzeichnisse, wie für den TOC‑Eintrag beschrieben.

### TR {#TR}
```
public static final StructureTypeStandard TR
```

(Table row) Eine Zeile mit Überschriften oder Daten in einer Tabelle. Sie kann Tabellenkopf‑Zellen und Tabellendaten‑Zellen (Strukturtypen TH und TD) enthalten.

### Warichu {#Warichu}
```
public static final StructureTypeStandard Warichu
```

(Warichu; PDF 1.5) Ein Kommentar oder eine Anmerkung in kleinerer Schriftgröße, die auf zwei kleinere Zeilen innerhalb der Höhe der umgebenden Textzeile formatiert wird und dem Basistext (inline) folgt, auf den sie sich bezieht. Ein Warichu‑Element kann auch die WT‑ und WP‑Elemente enthalten. (Warichu) Der Wrapper um die gesamte Warichu‑Zusammenstellung. Er kann eine dreiteilige Gruppe bestehend aus WP, WT und WP enthalten. Warichu‑Elemente (und ihre Inhaltselemente) können sich über mehrere Zeilen erstrecken, gemäß den Warichu‑Umbruchregeln, die im Japanese Industrial Standard (JIS) X 4051-1995 beschrieben sind.

### WP {#WP}
```
public static final StructureTypeStandard WP
```

(Warichu punctuation) Die Interpunktion, die den WT‑Text umgibt. Sie enthält Text (in der Regel eine einzelne linke oder rechte Klammer oder ein ähnliches Klammerzeichen). Laut JIS X 4051-1995 können die Klammern, die ein Warichu umschließen, nach Ermessen des Formatierers in ein LEERZEICHEN (nominal 1/4 EM in der Breite) umgewandelt werden.

### WT {#WT}
```
public static final StructureTypeStandard WT
```

(Warichu text) Der kleinformatige Text eines Warichu‑Kommentars, der in zwei Zeilen formatiert und zwischen den umgebenden WP‑Elementen platziert wird.

### canBeAppended {#canBeAppended-com.aspose.pdf.tagged.logicalstructure.StructureTypeStandard-}


### createElement {#createElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}


### getCategory {#getCategory--}
```
public final StructureTypeCategory getCategory()
```

Liefert die Kategorie des Standard‑Strukturtyps.

**Returns:**
Wert: Kategorie des Standard‑Strukturtyps.

### getTag {#getTag--}
```
public final String getTag()
```

Liefert den Tag-Namen von {@code StructureElement}.

**Returns:**
Tag-Name von {@code StructureElement}.

### to_StructureTypeStandard {#to_StructureTypeStandard-java.lang.String-}
Führt eine explizite Konvertierung von {@link String} zu {@link StructureTypeStandard} durch.

### toString {#toString--}
```
public String toString()
```

Gibt einen String zurück, der das aktuelle Objekt darstellt.

**Returns:**
String, der das aktuelle Objekt darstellt.
