---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Referência da API Aspose.PDF para Java"
description: "Representa a interface para trabalhar com o conteúdo TaggedPdf do documento."
type: docs
weight: 30
url: /pt/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Representa a interface para trabalhar com o conteúdo TaggedPdf do documento.

## Métodos

| Método | Descrição |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Cria {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Cria {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Cria {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Cria {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Cria {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Cria {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Cria {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Cria {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Cria {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Cria {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Cria {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Cria {@link HeaderElement} com nível. |
| [createIndexElement](#createIndexElement--) | Cria {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Cria {@link LinkElement}. |
| [createListElement](#createListElement--) | Cria {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Cria {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Cria {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Cria {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Cria {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Cria {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Cria {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Cria {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Cria {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Cria {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Cria {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Cria {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Cria {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Cria {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Cria {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Cria {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Cria {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Cria {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Cria {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Cria {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Cria {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Cria {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Cria {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Cria {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Obtém a raiz {@link StructureElement} da estrutura lógica do documento PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Obtém {@link StructTreeRootElement} do documento PDF. |
| [getStructureTextState](#getStructureTextState--) | Obtém as configurações {@link StructureTextState} para todo o documento. |
| [preSave](#preSave--) | Prepara o conteúdo marcado do documento para salvamento. Este método executa as operações necessárias antes de salvar, garantindo que a árvore de estrutura e outros elementos de conteúdo marcado estejam configurados corretamente antes de o documento ser salvo. |
| [save](#save--) | Salva o estado atual do conteúdo marcado no documento PDF associado. Este método garante que todos os elementos de conteúdo marcado sejam atualizados e salvos corretamente no documento PDF. Ele executa operações necessárias, como atualizar MCID para elementos MCR, definir operadores BDC e garantir a conformidade com os padrões PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Obtém a linguagem natural para o documento pdf. / * Um identificador de idioma que deve especificar a linguagem natural para todo o texto no documento, exceto onde / * sobrescrito por especificações de idioma para elementos de estrutura ou conteúdo marcado. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Define o título para o documento PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Cria {@link AnnotElement}.

**Returns:**
Elemento de estrutura criado.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Cria {@link ArtElement}.

**Returns:**
Elemento de estrutura criado.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Cria {@link BibEntryElement}.

**Returns:**
Elemento de estrutura criado.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Cria {@link BlockQuoteElement}.

**Returns:**
Elemento de estrutura criado.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Cria {@link CaptionElement}.

**Returns:**
Elemento de estrutura criado.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Cria {@link CodeElement}.

**Returns:**
Elemento de estrutura criado.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Cria {@link DivElement}.

**Returns:**
Elemento de estrutura criado.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Cria {@link FigureElement}.

**Returns:**
Elemento de estrutura criado.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Cria {@link FormElement}.

**Returns:**
Elemento de estrutura criado.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Cria {@link FormulaElement}.

**Returns:**
Elemento de estrutura criado.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Cria {@link HeaderElement}.

**Returns:**
Elemento de estrutura criado.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Cria {@link HeaderElement} com nível.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level |  | O nível do cabeçalho. Deve ser 1, 2, 3, 4, 5 ou 6. |

**Returns:**
Elemento de estrutura criado.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Cria {@link IndexElement}.

**Returns:**
Elemento de estrutura criado.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Cria {@link LinkElement}.

**Returns:**
Elemento de estrutura criado.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Cria {@link ListElement}.

**Returns:**
Elemento de estrutura criado.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Cria {@link ListLblElement}.

**Returns:**
Elemento de estrutura criado.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Cria {@link ListLBodyElement}.

**Returns:**
Elemento de estrutura criado.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Cria {@link ListLIElement}.

**Returns:**
Elemento de estrutura criado.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Cria {@link NonStructElement}.

**Returns:**
Elemento de estrutura criado.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Cria {@link NoteElement}.

**Returns:**
Elemento de estrutura criado.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Cria {@link ParagraphElement}.

**Returns:**
Elemento de estrutura criado.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Cria {@link PartElement}.

**Returns:**
Elemento de estrutura criado.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Cria {@link PrivateElement}.

**Returns:**
Elemento de estrutura criado.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Cria {@link QuoteElement}.

**Returns:**
Elemento de estrutura criado.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Cria {@link ReferenceElement}.

**Returns:**
Elemento de estrutura criado.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Cria {@link RubyElement}.

**Returns:**
Elemento de estrutura criado.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Cria {@link SectElement}.

**Returns:**
Elemento de estrutura criado.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Cria {@link SpanElement}.

**Returns:**
Elemento de estrutura criado.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Cria {@link TableElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Cria {@link TableTHeadElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Cria {@link TableTDElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Cria {@link TableTFootElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Cria {@link TableTHeadElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Cria {@link TableTHElement}.

**Returns:**
Elemento de estrutura criado.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Cria {@link TableTRElement}.

**Returns:**
Elemento de estrutura criado.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Cria {@link TOCElement}.

**Returns:**
Elemento de estrutura criado.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Cria {@link TOCIElement}.

**Returns:**
Elemento de estrutura criado.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Cria {@link WarichuElement}.

**Returns:**
Elemento de estrutura criado.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Obtém a raiz {@link StructureElement} da estrutura lógica do documento PDF.

**Returns:**
Raiz {@link StructureElement} da estrutura lógica do documento PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Obtém {@link StructTreeRootElement} do documento PDF.

**Returns:**
StructTreeRootElement do documento PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Obtém as configurações {@link StructureTextState} para todo o documento.

**Returns:**
Valor: configurações {@link StructureTextState} para todo o documento.

### preSave {#preSave--}
```
void preSave()
```

Prepara o conteúdo marcado do documento para salvamento. Este método executa as operações necessárias antes de salvar, garantindo que a árvore de estrutura e outros elementos de conteúdo marcado estejam configurados corretamente antes de o documento ser salvo.

### save {#save--}
```
void save()
```

Salva o estado atual do conteúdo marcado no documento PDF associado. Este método garante que todos os elementos de conteúdo marcado sejam atualizados e salvos corretamente no documento PDF. Ele executa operações necessárias, como atualizar MCID para elementos MCR, definir operadores BDC e garantir a conformidade com os padrões PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * Obtém a linguagem natural para o documento pdf. / * Um identificador de idioma que deve especificar a linguagem natural para todo o texto no documento, exceto onde / * sobrescrito por especificações de idioma para elementos de estrutura ou conteúdo marcado. / * / *

### setTitle {#setTitle-java.lang.String-}
Define o título para o documento PDF.
