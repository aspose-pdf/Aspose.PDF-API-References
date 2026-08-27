---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt eine Schnittstelle für die Arbeit mit TaggedPdf-Inhalt des Dokuments dar."
type: docs
weight: 30
url: /de/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Stellt eine Schnittstelle für die Arbeit mit TaggedPdf-Inhalt des Dokuments dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Erstellt {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Erstellt {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Erstellt {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Erstellt {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Erstellt {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Erstellt {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Erstellt {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Erstellt {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Erstellt {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Erstellt {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Erstellt {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Erstellt {@link HeaderElement} mit Ebene. |
| [createIndexElement](#createIndexElement--) | Erstellt {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Erstellt {@link LinkElement}. |
| [createListElement](#createListElement--) | Erstellt {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Erstellt {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Erstellt {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Erstellt {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Erstellt {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Erstellt {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Erstellt {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Erstellt {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Erstellt {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Erstellt {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Erstellt {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Erstellt {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Erstellt {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Erstellt {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Erstellt {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Erstellt {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Erstellt {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Erstellt {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Erstellt {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Erstellt {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Erstellt {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Erstellt {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Erstellt {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Erstellt {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Ermittelt das Root-{@link StructureElement} der logischen Struktur des PDF-Dokuments. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Ermittelt {@link StructTreeRootElement} des PDF-Dokuments. |
| [getStructureTextState](#getStructureTextState--) | Erhalte {@link StructureTextState}-Einstellungen für das gesamte Dokument. |
| [preSave](#preSave--) | Bereitet den getaggten Inhalt des Dokuments zum Speichern vor. Diese Methode führt notwendige Vor‑Speicher‑Operationen durch und stellt sicher, dass der Strukturbaum und andere getaggte Inhaltselemente korrekt konfiguriert sind, bevor das Dokument gespeichert wird. |
| [save](#save--) | Speichert den aktuellen Zustand des getaggten Inhalts im zugehörigen PDF-Dokument. Diese Methode stellt sicher, dass alle getaggten Inhaltselemente korrekt aktualisiert und im PDF-Dokument gespeichert werden. Sie führt notwendige Vorgänge wie das Aktualisieren von MCID für MCR-Elemente, das Setzen von BDC-Operatoren und die Einhaltung der PDF/UA-Standards durch. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Ermittelt die natürliche Sprache für das PDF-Dokument. / * Ein Sprachidentifikator, der die natürliche Sprache für den gesamten Text im Dokument festlegt, außer wenn / * durch Sprachspezifikationen für Strukturelemente oder markierten Inhalt überschrieben wird. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Setzt den Titel für das PDF-Dokument. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Erstellt {@link AnnotElement}.

**Returns:**
Strukturelement erstellt.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Erstellt {@link ArtElement}.

**Returns:**
Strukturelement erstellt.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Erstellt {@link BibEntryElement}.

**Returns:**
Strukturelement erstellt.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Erstellt {@link BlockQuoteElement}.

**Returns:**
Strukturelement erstellt.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Erstellt {@link CaptionElement}.

**Returns:**
Strukturelement erstellt.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Erstellt {@link CodeElement}.

**Returns:**
Strukturelement erstellt.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Erstellt {@link DivElement}.

**Returns:**
Strukturelement erstellt.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Erstellt {@link FigureElement}.

**Returns:**
Strukturelement erstellt.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Erstellt {@link FormElement}.

**Returns:**
Strukturelement erstellt.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Erstellt {@link FormulaElement}.

**Returns:**
Strukturelement erstellt.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Erstellt {@link HeaderElement}.

**Returns:**
Strukturelement erstellt.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Erstellt {@link HeaderElement} mit Ebene.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Ebene |  | Die Ebene der Überschrift. Muss 1, 2, 3, 4, 5 oder 6 sein. |

**Returns:**
Strukturelement erstellt.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Erstellt {@link IndexElement}.

**Returns:**
Strukturelement erstellt.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Erstellt {@link LinkElement}.

**Returns:**
Strukturelement erstellt.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Erstellt {@link ListElement}.

**Returns:**
Strukturelement erstellt.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Erstellt {@link ListLblElement}.

**Returns:**
Strukturelement erstellt.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Erstellt {@link ListLBodyElement}.

**Returns:**
Strukturelement erstellt.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Erstellt {@link ListLIElement}.

**Returns:**
Strukturelement erstellt.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Erstellt {@link NonStructElement}.

**Returns:**
Strukturelement erstellt.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Erstellt {@link NoteElement}.

**Returns:**
Strukturelement erstellt.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Erstellt {@link ParagraphElement}.

**Returns:**
Strukturelement erstellt.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Erstellt {@link PartElement}.

**Returns:**
Strukturelement erstellt.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Erstellt {@link PrivateElement}.

**Returns:**
Strukturelement erstellt.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Erstellt {@link QuoteElement}.

**Returns:**
Strukturelement erstellt.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Erstellt {@link ReferenceElement}.

**Returns:**
Strukturelement erstellt.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Erstellt {@link RubyElement}.

**Returns:**
Strukturelement erstellt.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Erstellt {@link SectElement}.

**Returns:**
Strukturelement erstellt.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Erstellt {@link SpanElement}.

**Returns:**
Strukturelement erstellt.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Erstellt {@link TableElement}.

**Returns:**
Strukturelement erstellt.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Erstellt {@link TableTHeadElement}.

**Returns:**
Strukturelement erstellt.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Erstellt {@link TableTDElement}.

**Returns:**
Strukturelement erstellt.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Erstellt {@link TableTFootElement}.

**Returns:**
Strukturelement erstellt.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Erstellt {@link TableTHeadElement}.

**Returns:**
Strukturelement erstellt.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Erstellt {@link TableTHElement}.

**Returns:**
Strukturelement erstellt.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Erstellt {@link TableTRElement}.

**Returns:**
Strukturelement erstellt.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Erstellt {@link TOCElement}.

**Returns:**
Strukturelement erstellt.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Erstellt {@link TOCIElement}.

**Returns:**
Strukturelement erstellt.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Erstellt {@link WarichuElement}.

**Returns:**
Strukturelement erstellt.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Ermittelt das Root-{@link StructureElement} der logischen Struktur des PDF-Dokuments.

**Returns:**
Root {@link StructureElement} der logischen Struktur des PDF-Dokuments.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Ermittelt {@link StructTreeRootElement} des PDF-Dokuments.

**Returns:**
StructTreeRootElement des PDF-Dokuments.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Erhalte {@link StructureTextState}-Einstellungen für das gesamte Dokument.

**Returns:**
Wert: {@link StructureTextState}-Einstellungen für das gesamte Dokument.

### preSave {#preSave--}
```
void preSave()
```

Bereitet den getaggten Inhalt des Dokuments zum Speichern vor. Diese Methode führt notwendige Vor‑Speicher‑Operationen durch und stellt sicher, dass der Strukturbaum und andere getaggte Inhaltselemente korrekt konfiguriert sind, bevor das Dokument gespeichert wird.

### save {#save--}
```
void save()
```

Speichert den aktuellen Zustand des getaggten Inhalts im zugehörigen PDF-Dokument. Diese Methode stellt sicher, dass alle getaggten Inhaltselemente korrekt aktualisiert und im PDF-Dokument gespeichert werden. Sie führt notwendige Vorgänge wie das Aktualisieren von MCID für MCR-Elemente, das Setzen von BDC-Operatoren und die Einhaltung der PDF/UA-Standards durch.

### setLanguage {#setLanguage-java.lang.String-}
/ * Ermittelt die natürliche Sprache für das PDF-Dokument. / * Ein Sprachidentifikator, der die natürliche Sprache für den gesamten Text im Dokument festlegt, außer wenn / * durch Sprachspezifikationen für Strukturelemente oder markierten Inhalt überschrieben wird. / * / *

### setTitle {#setTitle-java.lang.String-}
Setzt den Titel für das PDF-Dokument.
