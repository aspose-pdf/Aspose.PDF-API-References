---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'interface pour travailler avec le contenu TaggedPdf du document."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Représente l'interface pour travailler avec le contenu TaggedPdf du document.

## Méthodes

| Méthode | Description |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Crée {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Crée {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Crée {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Crée {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Crée {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Crée {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Crée {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Crée {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Crée {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Crée {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Crée {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Crée {@link HeaderElement} avec niveau. |
| [createIndexElement](#createIndexElement--) | Crée {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Crée {@link LinkElement}. |
| [createListElement](#createListElement--) | Crée {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Crée {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Crée {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Crée {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Crée {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Crée {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Crée {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Crée {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Crée {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Crée {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Crée {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Crée {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Crée {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Crée {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Crée {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Crée {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Crée {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Crée {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Crée {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Crée {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Crée {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Crée {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Crée {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Crée {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Obtient l'élément racine {@link StructureElement} de la structure logique du document PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Obtient {@link StructTreeRootElement} du document PDF. |
| [getStructureTextState](#getStructureTextState--) | Obtenez les paramètres {@link StructureTextState} pour l'ensemble du document. |
| [preSave](#preSave--) | Prépare le contenu balisé du document pour l'enregistrement. Cette méthode effectue les opérations pré-enregistrement nécessaires, garantissant que l'arbre de structure et les autres éléments de contenu balisé sont correctement configurés avant que le document ne soit enregistré. |
| [save](#save--) | Enregistre l'état actuel du contenu balisé dans le document PDF associé. Cette méthode garantit que tous les éléments de contenu balisé sont correctement mis à jour et enregistrés dans le document PDF. Elle effectue les opérations nécessaires telles que la mise à jour du MCID pour les éléments MCR, la définition des opérateurs BDC, et l'assurance de la conformité aux normes PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Obtient la langue naturelle du document pdf. / * Un identifiant de langue qui doit spécifier la langue naturelle pour tout le texte du document, sauf lorsque / * remplacé par des spécifications de langue pour les éléments de structure ou le contenu marqué. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Définit le titre du document PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Crée {@link AnnotElement}.

**Returns:**
Élément de structure créé.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Crée {@link ArtElement}.

**Returns:**
Élément de structure créé.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Crée {@link BibEntryElement}.

**Returns:**
Élément de structure créé.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Crée {@link BlockQuoteElement}.

**Returns:**
Élément de structure créé.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Crée {@link CaptionElement}.

**Returns:**
Élément de structure créé.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Crée {@link CodeElement}.

**Returns:**
Élément de structure créé.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Crée {@link DivElement}.

**Returns:**
Élément de structure créé.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Crée {@link FigureElement}.

**Returns:**
Élément de structure créé.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Crée {@link FormElement}.

**Returns:**
Élément de structure créé.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Crée {@link FormulaElement}.

**Returns:**
Élément de structure créé.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Crée {@link HeaderElement}.

**Returns:**
Élément de structure créé.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Crée {@link HeaderElement} avec niveau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| level |  | Le niveau de l'en-tête. Doit être 1, 2, 3, 4, 5 ou 6. |

**Returns:**
Élément de structure créé.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Crée {@link IndexElement}.

**Returns:**
Élément de structure créé.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Crée {@link LinkElement}.

**Returns:**
Élément de structure créé.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Crée {@link ListElement}.

**Returns:**
Élément de structure créé.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Crée {@link ListLblElement}.

**Returns:**
Élément de structure créé.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Crée {@link ListLBodyElement}.

**Returns:**
Élément de structure créé.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Crée {@link ListLIElement}.

**Returns:**
Élément de structure créé.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Crée {@link NonStructElement}.

**Returns:**
Élément de structure créé.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Crée {@link NoteElement}.

**Returns:**
Élément de structure créé.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Crée {@link ParagraphElement}.

**Returns:**
Élément de structure créé.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Crée {@link PartElement}.

**Returns:**
Élément de structure créé.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Crée {@link PrivateElement}.

**Returns:**
Élément de structure créé.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Crée {@link QuoteElement}.

**Returns:**
Élément de structure créé.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Crée {@link ReferenceElement}.

**Returns:**
Élément de structure créé.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Crée {@link RubyElement}.

**Returns:**
Élément de structure créé.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Crée {@link SectElement}.

**Returns:**
Élément de structure créé.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Crée {@link SpanElement}.

**Returns:**
Élément de structure créé.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Crée {@link TableElement}.

**Returns:**
Élément de structure créé.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Crée {@link TableTHeadElement}.

**Returns:**
Élément de structure créé.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Crée {@link TableTDElement}.

**Returns:**
Élément de structure créé.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Crée {@link TableTFootElement}.

**Returns:**
Élément de structure créé.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Crée {@link TableTHeadElement}.

**Returns:**
Élément de structure créé.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Crée {@link TableTHElement}.

**Returns:**
Élément de structure créé.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Crée {@link TableTRElement}.

**Returns:**
Élément de structure créé.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Crée {@link TOCElement}.

**Returns:**
Élément de structure créé.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Crée {@link TOCIElement}.

**Returns:**
Élément de structure créé.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Crée {@link WarichuElement}.

**Returns:**
Élément de structure créé.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Obtient l'élément racine {@link StructureElement} de la structure logique du document PDF.

**Returns:**
Racine {@link StructureElement} de la structure logique du document PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Obtient {@link StructTreeRootElement} du document PDF.

**Returns:**
StructTreeRootElement du document PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Obtenez les paramètres {@link StructureTextState} pour l'ensemble du document.

**Returns:**
Valeur : paramètres {@link StructureTextState} pour l'ensemble du document.

### preSave {#preSave--}
```
void preSave()
```

Prépare le contenu balisé du document pour l'enregistrement. Cette méthode effectue les opérations pré-enregistrement nécessaires, garantissant que l'arbre de structure et les autres éléments de contenu balisé sont correctement configurés avant que le document ne soit enregistré.

### save {#save--}
```
void save()
```

Enregistre l'état actuel du contenu balisé dans le document PDF associé. Cette méthode garantit que tous les éléments de contenu balisé sont correctement mis à jour et enregistrés dans le document PDF. Elle effectue les opérations nécessaires telles que la mise à jour du MCID pour les éléments MCR, la définition des opérateurs BDC, et l'assurance de la conformité aux normes PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * Obtient la langue naturelle du document pdf. / * Un identifiant de langue qui doit spécifier la langue naturelle pour tout le texte du document, sauf lorsque / * remplacé par des spécifications de langue pour les éléments de structure ou le contenu marqué. / * / *

### setTitle {#setTitle-java.lang.String-}
Définit le titre du document PDF.
