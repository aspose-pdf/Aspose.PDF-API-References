---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "تمثل واجهة للعمل مع محتوى TaggedPdf للوثيقة."
type: docs
weight: 30
url: /ar/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

تمثل واجهة للعمل مع محتوى TaggedPdf للوثيقة.

## الطرق

| طريقة | الوصف |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | ينشئ {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | ينشئ {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | ينشئ {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | ينشئ {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | ينشئ {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | ينشئ {@link CodeElement}. |
| [createDivElement](#createDivElement--) | ينشئ {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | ينشئ {@link FigureElement}. |
| [createFormElement](#createFormElement--) | ينشئ {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | ينشئ {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | ينشئ {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | ينشئ {@link HeaderElement} مع المستوى. |
| [createIndexElement](#createIndexElement--) | ينشئ {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | ينشئ {@link LinkElement}. |
| [createListElement](#createListElement--) | ينشئ {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | ينشئ {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | ينشئ {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | ينشئ {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | ينشئ {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | ينشئ {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | ينشئ {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | ينشئ {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | ينشئ {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | ينشئ {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | ينشئ {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | ينشئ {@link RubyElement}. |
| [createSectElement](#createSectElement--) | ينشئ {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | ينشئ {@link SpanElement}. |
| [createTableElement](#createTableElement--) | ينشئ {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | ينشئ {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | ينشئ {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | ينشئ {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | ينشئ {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | ينشئ {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | ينشئ {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | ينشئ {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | ينشئ {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | ينشئ {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | يحصل على العنصر الجذري {@link StructureElement} للهيكل المنطقي لمستند PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | يحصل على {@link StructTreeRootElement} لمستند PDF. |
| [getStructureTextState](#getStructureTextState--) | احصل على إعدادات {@link StructureTextState} لكامل المستند. |
| [preSave](#preSave--) | يُعد المحتوى الموسوم للمستند للحفظ. تقوم هذه الطريقة بتنفيذ العمليات الضرورية قبل الحفظ، مما يضمن تكوين شجرة الهيكل وعناصر المحتوى الموسومة الأخرى بشكل صحيح قبل حفظ المستند. |
| [save](#save--) | يحفظ الحالة الحالية للمحتوى الموسوم إلى مستند PDF المرتبط. تضمن هذه الطريقة تحديث جميع عناصر المحتوى الموسومة وحفظها بشكل صحيح داخل مستند PDF. تقوم بتنفيذ العمليات الضرورية مثل تحديث MCID لعناصر MCR، وضبط عوامل BDC، وضمان الامتثال لمعايير PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * يحصل على اللغة الطبيعية لمستند pdf. / * معرف اللغة الذي يحدد اللغة الطبيعية لجميع النصوص في المستند باستثناء الحالات التي / * يتم فيها تجاوز ذلك بواسطة مواصفات اللغة لعناصر الهيكل أو المحتوى المميز. / * / * |
| [setTitle](#setTitle-java.lang.String-) | يضبط العنوان لمستند PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

ينشئ {@link AnnotElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

ينشئ {@link ArtElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

ينشئ {@link BibEntryElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

ينشئ {@link BlockQuoteElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

ينشئ {@link CaptionElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

ينشئ {@link CodeElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

ينشئ {@link DivElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

ينشئ {@link FigureElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

ينشئ {@link FormElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

ينشئ {@link FormulaElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

ينشئ {@link HeaderElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

ينشئ {@link HeaderElement} مع المستوى.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| المستوى |  | مستوى العنوان. يجب أن يكون 1 أو 2 أو 3 أو 4 أو 5 أو 6. |

**Returns:**
تم إنشاء عنصر الهيكل.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

ينشئ {@link IndexElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

ينشئ {@link LinkElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

ينشئ {@link ListElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

ينشئ {@link ListLblElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

ينشئ {@link ListLBodyElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

ينشئ {@link ListLIElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

ينشئ {@link NonStructElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

ينشئ {@link NoteElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

ينشئ {@link ParagraphElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

ينشئ {@link PartElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

ينشئ {@link PrivateElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

ينشئ {@link QuoteElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

ينشئ {@link ReferenceElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

ينشئ {@link RubyElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

ينشئ {@link SectElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

ينشئ {@link SpanElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

ينشئ {@link TableElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

ينشئ {@link TableTHeadElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

ينشئ {@link TableTDElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

ينشئ {@link TableTFootElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

ينشئ {@link TableTHeadElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

ينشئ {@link TableTHElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

ينشئ {@link TableTRElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

ينشئ {@link TOCElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

ينشئ {@link TOCIElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

ينشئ {@link WarichuElement}.

**Returns:**
تم إنشاء عنصر الهيكل.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

يحصل على العنصر الجذري {@link StructureElement} للهيكل المنطقي لمستند PDF.

**Returns:**
العنصر الجذري {@link StructureElement} للهيكل المنطقي لمستند PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

يحصل على {@link StructTreeRootElement} لمستند PDF.

**Returns:**
StructTreeRootElement لمستند PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

احصل على إعدادات {@link StructureTextState} لكامل المستند.

**Returns:**
القيمة: إعدادات {@link StructureTextState} لكامل المستند.

### preSave {#preSave--}
```
void preSave()
```

يُعد المحتوى الموسوم للمستند للحفظ. تقوم هذه الطريقة بتنفيذ العمليات الضرورية قبل الحفظ، مما يضمن تكوين شجرة الهيكل وعناصر المحتوى الموسومة الأخرى بشكل صحيح قبل حفظ المستند.

### save {#save--}
```
void save()
```

يحفظ الحالة الحالية للمحتوى الموسوم إلى مستند PDF المرتبط. تضمن هذه الطريقة تحديث جميع عناصر المحتوى الموسومة وحفظها بشكل صحيح داخل مستند PDF. تقوم بتنفيذ العمليات الضرورية مثل تحديث MCID لعناصر MCR، وضبط عوامل BDC، وضمان الامتثال لمعايير PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * يحصل على اللغة الطبيعية لمستند pdf. / * معرف اللغة الذي يحدد اللغة الطبيعية لجميع النصوص في المستند باستثناء الحالات التي / * يتم فيها تجاوز ذلك بواسطة مواصفات اللغة لعناصر الهيكل أو المحتوى المميز. / * / *

### setTitle {#setTitle-java.lang.String-}
يضبط العنوان لمستند PDF.
