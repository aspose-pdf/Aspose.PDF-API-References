---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta l'interfaccia per lavorare con il contenuto TaggedPdf del documento."
type: docs
weight: 30
url: /it/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Rappresenta l'interfaccia per lavorare con il contenuto TaggedPdf del documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Crea {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Crea {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Crea {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Crea {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Crea {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Crea {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Crea {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Crea {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Crea {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Crea {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Crea {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Crea {@link HeaderElement} con livello. |
| [createIndexElement](#createIndexElement--) | Crea {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Crea {@link LinkElement}. |
| [createListElement](#createListElement--) | Crea {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Crea {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Crea {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Crea {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Crea {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Crea {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Crea {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Crea {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Crea {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Crea {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Crea {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Crea {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Crea {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Crea {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Crea {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Crea {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Crea {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Crea {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Crea {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Crea {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Crea {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Crea {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Crea {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Crea {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Ottiene l'elemento radice {@link StructureElement} della struttura logica del documento PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Ottiene {@link StructTreeRootElement} del documento PDF. |
| [getStructureTextState](#getStructureTextState--) | Ottieni le impostazioni {@link StructureTextState} per l'intero documento. |
| [preSave](#preSave--) | Prepara il contenuto marcato del documento per il salvataggio. Questo metodo esegue le operazioni necessarie prima del salvataggio, garantendo che l'albero di struttura e gli altri elementi di contenuto marcato siano configurati correttamente prima che il documento venga salvato. |
| [save](#save--) | Salva lo stato attuale del contenuto marcato nel documento PDF associato. Questo metodo garantisce che tutti gli elementi di contenuto marcato siano aggiornati e salvati correttamente all'interno del documento PDF. Esegue le operazioni necessarie, come l'aggiornamento del MCID per gli elementi MCR, l'impostazione degli operatori BDC e l'assicurare la conformità agli standard PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Ottiene la lingua naturale per il documento pdf. / * Un identificatore di lingua che deve specificare la lingua naturale per tutto il testo nel documento, eccetto dove / * sovrascritto dalle specifiche di lingua per gli elementi di struttura o il contenuto marcato. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Imposta il titolo per il documento PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Crea {@link AnnotElement}.

**Returns:**
Elemento di struttura creato.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Crea {@link ArtElement}.

**Returns:**
Elemento di struttura creato.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Crea {@link BibEntryElement}.

**Returns:**
Elemento di struttura creato.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Crea {@link BlockQuoteElement}.

**Returns:**
Elemento di struttura creato.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Crea {@link CaptionElement}.

**Returns:**
Elemento di struttura creato.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Crea {@link CodeElement}.

**Returns:**
Elemento di struttura creato.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Crea {@link DivElement}.

**Returns:**
Elemento di struttura creato.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Crea {@link FigureElement}.

**Returns:**
Elemento di struttura creato.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Crea {@link FormElement}.

**Returns:**
Elemento di struttura creato.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Crea {@link FormulaElement}.

**Returns:**
Elemento di struttura creato.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Crea {@link HeaderElement}.

**Returns:**
Elemento di struttura creato.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Crea {@link HeaderElement} con livello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level |  | Il livello dell'intestazione. Deve essere 1, 2, 3, 4, 5 o 6. |

**Returns:**
Elemento di struttura creato.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Crea {@link IndexElement}.

**Returns:**
Elemento di struttura creato.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Crea {@link LinkElement}.

**Returns:**
Elemento di struttura creato.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Crea {@link ListElement}.

**Returns:**
Elemento di struttura creato.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Crea {@link ListLblElement}.

**Returns:**
Elemento di struttura creato.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Crea {@link ListLBodyElement}.

**Returns:**
Elemento di struttura creato.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Crea {@link ListLIElement}.

**Returns:**
Elemento di struttura creato.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Crea {@link NonStructElement}.

**Returns:**
Elemento di struttura creato.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Crea {@link NoteElement}.

**Returns:**
Elemento di struttura creato.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Crea {@link ParagraphElement}.

**Returns:**
Elemento di struttura creato.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Crea {@link PartElement}.

**Returns:**
Elemento di struttura creato.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Crea {@link PrivateElement}.

**Returns:**
Elemento di struttura creato.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Crea {@link QuoteElement}.

**Returns:**
Elemento di struttura creato.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Crea {@link ReferenceElement}.

**Returns:**
Elemento di struttura creato.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Crea {@link RubyElement}.

**Returns:**
Elemento di struttura creato.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Crea {@link SectElement}.

**Returns:**
Elemento di struttura creato.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Crea {@link SpanElement}.

**Returns:**
Elemento di struttura creato.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Crea {@link TableElement}.

**Returns:**
Elemento di struttura creato.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Crea {@link TableTHeadElement}.

**Returns:**
Elemento di struttura creato.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Crea {@link TableTDElement}.

**Returns:**
Elemento di struttura creato.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Crea {@link TableTFootElement}.

**Returns:**
Elemento di struttura creato.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Crea {@link TableTHeadElement}.

**Returns:**
Elemento di struttura creato.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Crea {@link TableTHElement}.

**Returns:**
Elemento di struttura creato.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Crea {@link TableTRElement}.

**Returns:**
Elemento di struttura creato.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Crea {@link TOCElement}.

**Returns:**
Elemento di struttura creato.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Crea {@link TOCIElement}.

**Returns:**
Elemento di struttura creato.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Crea {@link WarichuElement}.

**Returns:**
Elemento di struttura creato.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Ottiene l'elemento radice {@link StructureElement} della struttura logica del documento PDF.

**Returns:**
Radice {@link StructureElement} della struttura logica del documento PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Ottiene {@link StructTreeRootElement} del documento PDF.

**Returns:**
StructTreeRootElement del documento PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Ottieni le impostazioni {@link StructureTextState} per l'intero documento.

**Returns:**
Valore: impostazioni {@link StructureTextState} per l'intero documento.

### preSave {#preSave--}
```
void preSave()
```

Prepara il contenuto marcato del documento per il salvataggio. Questo metodo esegue le operazioni necessarie prima del salvataggio, garantendo che l'albero di struttura e gli altri elementi di contenuto marcato siano configurati correttamente prima che il documento venga salvato.

### save {#save--}
```
void save()
```

Salva lo stato attuale del contenuto marcato nel documento PDF associato. Questo metodo garantisce che tutti gli elementi di contenuto marcato siano aggiornati e salvati correttamente all'interno del documento PDF. Esegue le operazioni necessarie, come l'aggiornamento del MCID per gli elementi MCR, l'impostazione degli operatori BDC e l'assicurare la conformità agli standard PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * Ottiene la lingua naturale per il documento pdf. / * Un identificatore di lingua che deve specificare la lingua naturale per tutto il testo nel documento, eccetto dove / * sovrascritto dalle specifiche di lingua per gli elementi di struttura o il contenuto marcato. / * / *

### setTitle {#setTitle-java.lang.String-}
Imposta il titolo per il documento PDF.
