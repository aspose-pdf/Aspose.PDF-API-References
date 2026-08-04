---
title: "StructureTypeStandard"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt Standardstrukturtypen dar."
type: docs
weight: 560
url: /de/python-net/aspose.pdf.logicalstructure/structuretypestandard/
---

## StructureTypeStandard class

Stellt Standardstrukturtypen dar.

Der Typ StructureTypeStandard stellt die folgenden Mitglieder bereit:
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| tag | Ermittelt den Tag-Namen von [StructureElement](/pdf/python-net/aspose.pdf.logicalstructure/structureelement/). |
| category | Ermittelt die Kategorie des Standard-Strukturtyps. |
| DOKUMENT | (Dokument) Ein vollständiges Dokument. Dies ist das Wurzelelement eines beliebigen Strukturbaums, der mehrere Teile oder mehrere Artikel enthält. |
| TEIL | (Teil) Eine groß angelegte Unterteilung eines Dokuments. Dieser Elementtyp eignet sich zum Gruppieren von Artikeln oder Abschnitten. |
| ART | (Artikel) Ein relativ eigenständiger Textkörper, der eine einzelne Erzählung oder Darstellung bildet. Artikel sollten disjunkt sein; das heißt, sie sollten keine anderen Artikel als Bestandteile enthalten. |
| SECT | (Abschnitt) Ein Behälter zum Gruppieren verwandter Inhaltselemente. |
| DIV | (Division) Ein generisches Block-Element oder eine Gruppe von Elementen. |
| BLOCK_QUOTE | (Blockzitat) Ein Textabschnitt, der aus einem oder mehreren Absätzen besteht und jemand anderem als dem Autor des umgebenden Textes zugeschrieben wird. |
| UNTERSCHRIFT | (Unterschrift) Ein kurzer Textabschnitt, der eine Tabelle oder Abbildung beschreibt. |
| INHALTSVERZEICHNIS | (Inhaltsverzeichnis) Eine Liste, die aus Einträgen von Inhaltsverzeichnis-Elementen (Strukturtyp TOCI) und/oder anderen verschachtelten Inhaltsverzeichnis-Einträgen (TOC) besteht. |
| TOCI | (Inhaltsverzeichnis-Eintrag) Ein einzelnes Mitglied eines Inhaltsverzeichnisses. Die Unterelemente dieses Eintrags können beliebige der folgenden Strukturtypen sein: |
| INDEX | (Index) Eine Reihe von Einträgen, die identifizierenden Text enthalten, begleitet von Referenzelementen, die Vorkommen des angegebenen Textes im Hauptteil eines Dokuments aufzeigen. |
| NON_STRUCT | (Nichtstrukturelles Element) Ein Gruppierungselement ohne inhärente strukturelle Bedeutung; es dient ausschließlich Gruppierungszwecken. Dieser Elementtyp unterscheidet sich von einer Division (Strukturtyp Div) darin, dass er nicht interpretiert oder in andere Dokumentformate exportiert werden darf; seine Nachkommen werden jedoch normal verarbeitet. |
| PRIVAT | (Privates Element) Ein Gruppierungselement, das privaten Inhalt enthält, der zur erzeugenden Anwendung gehört. Die strukturelle Bedeutung dieses Elementtyps ist nicht festgelegt und wird vollständig vom konformen Autor bestimmt. Weder das Private-Element noch irgendeine seiner Nachkommen dürfen interpretiert oder in andere Dokumentformate exportiert werden. |
| P | (Paragraph) Eine niedrigstufige Unterteilung von Text. |
| H | (Heading) Eine Bezeichnung für eine Unterteilung des Inhalts eines Dokuments. Sie sollte das erste Kind der Division sein, die sie überschreibt. |
| H1 | Überschrift Ebene 1, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| H2 | Überschrift Ebene 2, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| H3 | Überschrift Ebene 3, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| H4 | Überschrift Ebene 4, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| H5 | Überschrift Ebene 5, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| H6 | Überschrift Ebene 6, für den Einsatz in konformen Schreibprogrammen, die ihre Abschnitte nicht hierarchisch verschachteln können und daher die Ebene einer Überschrift nicht aus ihrer Verschachtelung ableiten können. |
| L | (List) Eine Folge von Elementen gleicher Bedeutung und Wichtigkeit. Seine unmittelbaren Kinder sollten eine optionale Beschriftung (Strukturtyp Caption) gefolgt von einem oder mehreren Listenelementen (Strukturtyp LI) sein. |
| LI | (List item) Ein einzelnes Element einer Liste. Seine Kinder können ein oder mehrere Labels, Listenkörper oder beides sein (Strukturtypen Lbl oder LBody). |
| LBL | (Label) Ein Name oder eine Nummer, die ein bestimmtes Element von anderen im selben Liste oder einer anderen Gruppe ähnlicher Elemente unterscheidet. |
| L_BODY | (List body) Der beschreibende Inhalt eines Listenelements. In einer Wörterbuchliste enthält er zum Beispiel die Definition des Begriffs. Er kann den Inhalt direkt enthalten oder andere BLSEs als Kinder haben, möglicherweise verschachtelte Listen. |
| TABLE | (Table) Ein zweidimensionales Layout aus rechteckigen Datenzellen, das möglicherweise eine komplexe Unterstruktur hat. Es enthält entweder eine oder mehrere Tabellenzeilen (Strukturtyp TR) als Kinder; oder einen optionalen Tabellenkopf (Strukturtyp THead), gefolgt von einem oder mehreren Tabellenkörper-Elementen (Strukturtyp TBody) und einem optionalen Tabellenfuß (Strukturtyp TFoot). Zusätzlich kann eine Tabelle eine Beschriftung (Strukturtyp Caption) als erstes oder letztes Kind haben. |
| T_HEAD | (Table header row group; PDF 1.5) Eine Gruppe von Zeilen, die den Tabellenkopf bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen oben in jedem Tabellenteil neu gezeichnet werden (obwohl es nur ein THead-Element gibt). |
| T_BODY | (Table body row group; PDF 1.5) Eine Gruppe von Zeilen, die den Hauptkörperteil einer Tabelle bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, kann der Körperbereich an einer Zeilenbegrenzung aufgeteilt werden. Eine Tabelle kann mehrere TBody-Elemente haben, um das Zeichnen eines Rahmens oder Hintergrunds für einen Satz von Zeilen zu ermöglichen. |
| T_FOOT | (Table footer row group; PDF 1.5) Eine Gruppe von Zeilen, die die Fußzeile einer Tabelle bilden. Wenn die Tabelle über mehrere Seiten verteilt ist, können diese Zeilen am unteren Rand jedes Tabellenfragments neu gezeichnet werden (obwohl es nur ein TFoot-Element gibt). |
| TR | (Table row) Eine Zeile mit Überschriften oder Daten in einer Tabelle. Sie kann Tabellenkopfzellen und Tabellendatenzellen enthalten (Strukturtypen TH und TD). |
| TH | (Table header cell) Eine Tabellenzelle, die Kopfzeilentext enthält, der eine oder mehrere Zeilen oder Spalten der Tabelle beschreibt. |
| TD | (Table data cell) Eine Tabellenzelle, die Daten enthält, die Teil des Tabelleninhalts sind. |
| SPAN | (Span) Ein generischer Inline-Textabschnitt ohne besondere inhärente Merkmale. Er kann beispielsweise verwendet werden, um einen Textbereich mit einer bestimmten Menge von Stilattributen zu begrenzen. |
| QUOTE | (Quotation) Ein Inline-Textabschnitt, der einer anderen Person als dem Autor des umgebenden Textes zugeschrieben wird. |
| NOTE | (Note) Ein Element erklärenden Textes, wie eine Fußnote oder Endnote, das aus dem Hauptteil des Dokuments referenziert wird. Es kann ein Etikett (Strukturtyp Lbl) als Kind haben. Die Notiz kann als Kind des Strukturelements im Haupttext, das darauf verweist, eingebunden sein, oder sie kann an anderer Stelle (z. B. in einem Endnotenabschnitt) eingefügt und über eine Referenz (Strukturtyp Reference) aufgerufen werden. |
| REFERENCE | (Reference) Ein Verweis auf Inhalt an anderer Stelle im Dokument. |
| BIB_ENTRY | (Bibliography entry) Ein Verweis, der die externe Quelle eines zitierten Inhalts identifiziert. Er kann ein Etikett (Strukturtyp Lbl) als Kind enthalten. |
| CODE | (Code) Ein Fragment von Computerprogrammtext. |
| LINK | (Link) Eine Zuordnung zwischen einem Teil des ILSE-Inhalts und einer entsprechenden Link-Annotation oder mehreren Annotationen. Seine Kinder sollten ein oder mehrere Inhaltselemente oder Kind-ILSEs sowie ein oder mehrere Objektverweise sein, die die zugehörigen Link-Annotationen identifizieren. |
| ANNOT | (Annotation; PDF 1.5) Eine Zuordnung zwischen einem Teil des ILSE-Inhalts und einer entsprechenden PDF-Annotation. Annot soll für alle PDF-Annotationen außer Link-Annotationen und Widget-Annotationen verwendet werden. |
| RUBY | (Ruby; PDF 1.5) Eine Randnotiz (Annotation), die in kleinerer Schriftgröße geschrieben ist und neben dem Basistext platziert wird, auf den sie sich bezieht. Ein Ruby-Element kann auch die Elemente RB, RT und RP enthalten. |
| RB | (Ruby base text) Der Volltext, auf den die Ruby-Annotation angewendet wird. RB kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Es kann das Attribut RubyAlign besitzen. |
| RT | (Ruby annotation text) Der kleinformatige Text, der neben dem Ruby-Basistext platziert werden soll. Er kann Text, andere Inline-Elemente oder eine Mischung aus beidem enthalten. Er kann die Attribute RubyAlign und RubyPosition besitzen. |
| RP | (Ruby punctuation) Interpunktion, die den Ruby-Annotationstext umgibt. Sie wird nur verwendet, wenn eine Ruby-Annotation nicht korrekt im Ruby-Stil formatiert werden kann und stattdessen als normaler Kommentar formatiert wird, oder wenn sie als Warichu formatiert ist. Sie enthält Text (in der Regel ein einzelnes LINKES oder RECHTES KLAMMERZEICHEN oder ein ähnliches Klammerzeichen). |
| WARICHU | (Warichu; PDF 1.5) Ein Kommentar oder eine Annotation in kleinerer Schriftgröße, die auf zwei kleinere Zeilen innerhalb der Höhe der umgebenden Textzeile formatiert wird und nach (inline) dem Basistext platziert wird, auf den sie sich bezieht. Ein Warichu-Element kann auch die Elemente WT und WP enthalten. |
| WT | (Warichu text) Der kleinformatige Text eines Warichu-Kommentars, der in zwei Zeilen formatiert und zwischen den umgebenden WP-Elementen platziert wird. |
| WP | (Warichu punctuation) Die Interpunktion, die den WT-Text umgibt. Sie enthält Text (in der Regel ein einzelnes LINKES oder RECHTES KLAMMERZEICHEN oder ein ähnliches Klammerzeichen). Laut JIS X 4051-1995 können die Klammern, die einen Warichu umgeben, nach Ermessen des Formatierers in ein LEERZEICHEN (nominal 1/4 EM breit) umgewandelt werden. |
| FIGURE | (Figure) Ein grafisches Inhaltselement. Seine Platzierung kann mit dem Layout-Attribut Placement angegeben werden. |
| FORMULA | (Formula) Eine mathematische Formel. |
| FORM | (Form) Eine Widget-Annotation, die ein interaktives Formularfeld darstellt. |

### Siehe auch

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

