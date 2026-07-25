---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Aspose.PDF for Java API 参考"
description: "表示用于处理文档 TaggedPdf 内容的接口。"
type: docs
weight: 30
url: /zh/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

表示用于处理文档 TaggedPdf 内容的接口。

## 方法

| 方法 | 描述 |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | 创建 {@link AnnotElement}。 |
| [createArtElement](#createArtElement--) | 创建 {@link ArtElement}。 |
| [createBibEntryElement](#createBibEntryElement--) | 创建 {@link BibEntryElement}。 |
| [createBlockQuoteElement](#createBlockQuoteElement--) | 创建 {@link BlockQuoteElement}。 |
| [createCaptionElement](#createCaptionElement--) | 创建 {@link CaptionElement}。 |
| [createCodeElement](#createCodeElement--) | 创建 {@link CodeElement}。 |
| [createDivElement](#createDivElement--) | 创建 {@link DivElement}。 |
| [createFigureElement](#createFigureElement--) | 创建 {@link FigureElement}。 |
| [createFormElement](#createFormElement--) | 创建 {@link FormElement}。 |
| [createFormulaElement](#createFormulaElement--) | 创建 {@link FormulaElement}。 |
| [createHeaderElement](#createHeaderElement--) | 创建 {@link HeaderElement}。 |
| [createHeaderElement](#createHeaderElement-int-) | 创建 {@link HeaderElement}，带有级别。 |
| [createIndexElement](#createIndexElement--) | 创建 {@link IndexElement}。 |
| [createLinkElement](#createLinkElement--) | 创建 {@link LinkElement}。 |
| [createListElement](#createListElement--) | 创建 {@link ListElement}。 |
| [createListLblElement](#createListLblElement--) | 创建 {@link ListLblElement}。 |
| [createListLBodyElement](#createListLBodyElement--) | 创建 {@link ListLBodyElement}。 |
| [createListLIElement](#createListLIElement--) | 创建 {@link ListLIElement}。 |
| [createNonStructElement](#createNonStructElement--) | 创建 {@link NonStructElement}。 |
| [createNoteElement](#createNoteElement--) | 创建 {@link NoteElement}。 |
| [createParagraphElement](#createParagraphElement--) | 创建 {@link ParagraphElement}。 |
| [createPartElement](#createPartElement--) | 创建 {@link PartElement}。 |
| [createPrivateElement](#createPrivateElement--) | 创建 {@link PrivateElement}。 |
| [createQuoteElement](#createQuoteElement--) | 创建 {@link QuoteElement}。 |
| [createReferenceElement](#createReferenceElement--) | 创建 {@link ReferenceElement}。 |
| [createRubyElement](#createRubyElement--) | 创建 {@link RubyElement}。 |
| [createSectElement](#createSectElement--) | 创建 {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | 创建 {@link SpanElement}. |
| [createTableElement](#createTableElement--) | 创建 {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | 创建 {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | 创建 {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | 创建 {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | 创建 {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | 创建 {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | 创建 {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | 创建 {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | 创建 {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | 创建 {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | 获取根 {@link StructureElement} 的 PDF 文档逻辑结构。 |
| [getStructTreeRootElement](#getStructTreeRootElement--) | 获取 PDF 文档的 {@link StructTreeRootElement}。 |
| [getStructureTextState](#getStructureTextState--) | 获取 {@link StructureTextState} 设置，用于整个文档。 |
| [preSave](#preSave--) | 为保存准备文档的标记内容。此方法执行必要的预保存操作，确保在保存文档之前结构树和其他标记内容元素已正确配置。 |
| [save](#save--) | 将标记内容的当前状态保存到关联的 PDF 文档。此方法确保所有标记内容元素在 PDF 文档中得到正确更新和保存。它执行必要的操作，例如为 MCR 元素更新 MCID、设置 BDC 操作符，并确保符合 PDF/UA 标准。 |
| [setLanguage](#setLanguage-java.lang.String-) | / * 获取 pdf 文档的自然语言。 / * 语言标识符，用于指定文档中所有文本的自然语言，除非在 / * 被结构元素或标记内容的语言规范覆盖。 / * / * |
| [setTitle](#setTitle-java.lang.String-) | 设置 PDF 文档的标题。 |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

创建 {@link AnnotElement}。

**Returns:**
已创建结构元素。

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

创建 {@link ArtElement}。

**Returns:**
已创建结构元素。

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

创建 {@link BibEntryElement}。

**Returns:**
已创建结构元素。

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

创建 {@link BlockQuoteElement}。

**Returns:**
已创建结构元素。

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

创建 {@link CaptionElement}。

**Returns:**
已创建结构元素。

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

创建 {@link CodeElement}。

**Returns:**
已创建结构元素。

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

创建 {@link DivElement}。

**Returns:**
已创建结构元素。

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

创建 {@link FigureElement}。

**Returns:**
已创建结构元素。

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

创建 {@link FormElement}。

**Returns:**
已创建结构元素。

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

创建 {@link FormulaElement}。

**Returns:**
已创建结构元素。

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

创建 {@link HeaderElement}。

**Returns:**
已创建结构元素。

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

创建 {@link HeaderElement}，带有级别。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level |  | 标题的级别。必须是 1、2、3、4、5 或 6。 |

**Returns:**
已创建结构元素。

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

创建 {@link IndexElement}。

**Returns:**
已创建结构元素。

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

创建 {@link LinkElement}。

**Returns:**
已创建结构元素。

### createListElement {#createListElement--}
```
ListElement createListElement()
```

创建 {@link ListElement}。

**Returns:**
已创建结构元素。

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

创建 {@link ListLblElement}。

**Returns:**
已创建结构元素。

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

创建 {@link ListLBodyElement}。

**Returns:**
已创建结构元素。

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

创建 {@link ListLIElement}。

**Returns:**
已创建结构元素。

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

创建 {@link NonStructElement}。

**Returns:**
已创建结构元素。

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

创建 {@link NoteElement}。

**Returns:**
已创建结构元素。

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

创建 {@link ParagraphElement}。

**Returns:**
已创建结构元素。

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

创建 {@link PartElement}。

**Returns:**
已创建结构元素。

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

创建 {@link PrivateElement}。

**Returns:**
已创建结构元素。

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

创建 {@link QuoteElement}。

**Returns:**
已创建结构元素。

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

创建 {@link ReferenceElement}。

**Returns:**
已创建结构元素。

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

创建 {@link RubyElement}。

**Returns:**
已创建结构元素。

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

创建 {@link SectElement}.

**Returns:**
已创建结构元素。

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

创建 {@link SpanElement}.

**Returns:**
已创建结构元素。

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

创建 {@link TableElement}.

**Returns:**
已创建结构元素。

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

创建 {@link TableTHeadElement}.

**Returns:**
已创建结构元素。

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

创建 {@link TableTDElement}.

**Returns:**
已创建结构元素。

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

创建 {@link TableTFootElement}.

**Returns:**
已创建结构元素。

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

创建 {@link TableTHeadElement}.

**Returns:**
已创建结构元素。

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

创建 {@link TableTHElement}.

**Returns:**
已创建结构元素。

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

创建 {@link TableTRElement}.

**Returns:**
已创建结构元素。

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

创建 {@link TOCElement}.

**Returns:**
已创建结构元素。

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

创建 {@link TOCIElement}.

**Returns:**
已创建结构元素。

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

创建 {@link WarichuElement}.

**Returns:**
已创建结构元素。

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

获取根 {@link StructureElement} 的 PDF 文档逻辑结构。

**Returns:**
PDF 文档逻辑结构的根 {@link StructureElement}。

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

获取 PDF 文档的 {@link StructTreeRootElement}。

**Returns:**
PDF 文档的 StructTreeRootElement。

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

获取 {@link StructureTextState} 设置，用于整个文档。

**Returns:**
值：整个文档的 {@link StructureTextState} 设置。

### preSave {#preSave--}
```
void preSave()
```

为保存准备文档的标记内容。此方法执行必要的预保存操作，确保在保存文档之前结构树和其他标记内容元素已正确配置。

### save {#save--}
```
void save()
```

将标记内容的当前状态保存到关联的 PDF 文档。此方法确保所有标记内容元素在 PDF 文档中得到正确更新和保存。它执行必要的操作，例如为 MCR 元素更新 MCID、设置 BDC 操作符，并确保符合 PDF/UA 标准。

### setLanguage {#setLanguage-java.lang.String-}
/ * 获取 pdf 文档的自然语言。 / * 语言标识符，用于指定文档中所有文本的自然语言，除非在 / * 被结构元素或标记内容的语言规范覆盖。 / * / *

### setTitle {#setTitle-java.lang.String-}
设置 PDF 文档的标题。
