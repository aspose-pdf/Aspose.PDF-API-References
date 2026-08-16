---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Representa la interfaz para trabajar con el contenido TaggedPdf del documento."
type: docs
weight: 30
url: /es/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Representa la interfaz para trabajar con el contenido TaggedPdf del documento.

## Métodos

| Método | Descripción |
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
| [createHeaderElement](#createHeaderElement-int-) | Crea {@link HeaderElement} con nivel. |
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
| [getRootElement](#getRootElement--) | Obtiene la raíz {@link StructureElement} de la estructura lógica del documento PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Obtiene {@link StructTreeRootElement} del documento PDF. |
| [getStructureTextState](#getStructureTextState--) | Obtiene la configuración {@link StructureTextState} para todo el documento. |
| [preSave](#preSave--) | Prepara el contenido etiquetado del documento para guardarlo. Este método realiza las operaciones previas al guardado necesarias, asegurando que el árbol de estructura y otros elementos de contenido etiquetado estén configurados correctamente antes de que el documento se guarde. |
| [save](#save--) | Guarda el estado actual del contenido etiquetado en el documento PDF asociado. Este método garantiza que todos los elementos de contenido etiquetado se actualicen y guarden correctamente dentro del documento PDF. Realiza operaciones necesarias como actualizar MCID para elementos MCR, establecer operadores BDC y asegurar el cumplimiento de los estándares PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Obtiene el lenguaje natural para el documento pdf. / * Un identificador de idioma que debe especificar el lenguaje natural para todo el texto en el documento, excepto donde / * sea sobrescrito por especificaciones de idioma para elementos de estructura o contenido marcado. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Establece el título para el documento PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Crea {@link AnnotElement}.

**Returns:**
Elemento de estructura creado.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Crea {@link ArtElement}.

**Returns:**
Elemento de estructura creado.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Crea {@link BibEntryElement}.

**Returns:**
Elemento de estructura creado.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Crea {@link BlockQuoteElement}.

**Returns:**
Elemento de estructura creado.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Crea {@link CaptionElement}.

**Returns:**
Elemento de estructura creado.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Crea {@link CodeElement}.

**Returns:**
Elemento de estructura creado.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Crea {@link DivElement}.

**Returns:**
Elemento de estructura creado.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Crea {@link FigureElement}.

**Returns:**
Elemento de estructura creado.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Crea {@link FormElement}.

**Returns:**
Elemento de estructura creado.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Crea {@link FormulaElement}.

**Returns:**
Elemento de estructura creado.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Crea {@link HeaderElement}.

**Returns:**
Elemento de estructura creado.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Crea {@link HeaderElement} con nivel.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level |  | El nivel del encabezado. Debe ser 1, 2, 3, 4, 5 o 6. |

**Returns:**
Elemento de estructura creado.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Crea {@link IndexElement}.

**Returns:**
Elemento de estructura creado.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Crea {@link LinkElement}.

**Returns:**
Elemento de estructura creado.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Crea {@link ListElement}.

**Returns:**
Elemento de estructura creado.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Crea {@link ListLblElement}.

**Returns:**
Elemento de estructura creado.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Crea {@link ListLBodyElement}.

**Returns:**
Elemento de estructura creado.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Crea {@link ListLIElement}.

**Returns:**
Elemento de estructura creado.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Crea {@link NonStructElement}.

**Returns:**
Elemento de estructura creado.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Crea {@link NoteElement}.

**Returns:**
Elemento de estructura creado.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Crea {@link ParagraphElement}.

**Returns:**
Elemento de estructura creado.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Crea {@link PartElement}.

**Returns:**
Elemento de estructura creado.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Crea {@link PrivateElement}.

**Returns:**
Elemento de estructura creado.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Crea {@link QuoteElement}.

**Returns:**
Elemento de estructura creado.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Crea {@link ReferenceElement}.

**Returns:**
Elemento de estructura creado.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Crea {@link RubyElement}.

**Returns:**
Elemento de estructura creado.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Crea {@link SectElement}.

**Returns:**
Elemento de estructura creado.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Crea {@link SpanElement}.

**Returns:**
Elemento de estructura creado.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Crea {@link TableElement}.

**Returns:**
Elemento de estructura creado.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Crea {@link TableTHeadElement}.

**Returns:**
Elemento de estructura creado.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Crea {@link TableTDElement}.

**Returns:**
Elemento de estructura creado.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Crea {@link TableTFootElement}.

**Returns:**
Elemento de estructura creado.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Crea {@link TableTHeadElement}.

**Returns:**
Elemento de estructura creado.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Crea {@link TableTHElement}.

**Returns:**
Elemento de estructura creado.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Crea {@link TableTRElement}.

**Returns:**
Elemento de estructura creado.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Crea {@link TOCElement}.

**Returns:**
Elemento de estructura creado.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Crea {@link TOCIElement}.

**Returns:**
Elemento de estructura creado.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Crea {@link WarichuElement}.

**Returns:**
Elemento de estructura creado.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Obtiene la raíz {@link StructureElement} de la estructura lógica del documento PDF.

**Returns:**
Raíz {@link StructureElement} de la estructura lógica del documento PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Obtiene {@link StructTreeRootElement} del documento PDF.

**Returns:**
StructTreeRootElement del documento PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Obtiene la configuración {@link StructureTextState} para todo el documento.

**Returns:**
Valor: configuración {@link StructureTextState} para todo el documento.

### preSave {#preSave--}
```
void preSave()
```

Prepara el contenido etiquetado del documento para guardarlo. Este método realiza las operaciones previas al guardado necesarias, asegurando que el árbol de estructura y otros elementos de contenido etiquetado estén configurados correctamente antes de que el documento se guarde.

### save {#save--}
```
void save()
```

Guarda el estado actual del contenido etiquetado en el documento PDF asociado. Este método garantiza que todos los elementos de contenido etiquetado se actualicen y guarden correctamente dentro del documento PDF. Realiza operaciones necesarias como actualizar MCID para elementos MCR, establecer operadores BDC y asegurar el cumplimiento de los estándares PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * Obtiene el lenguaje natural para el documento pdf. / * Un identificador de idioma que debe especificar el lenguaje natural para todo el texto en el documento, excepto donde / * sea sobrescrito por especificaciones de idioma para elementos de estructura o contenido marcado. / * / *

### setTitle {#setTitle-java.lang.String-}
Establece el título para el documento PDF.
