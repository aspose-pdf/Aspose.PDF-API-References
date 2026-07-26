---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "ドキュメントの TaggedPdf コンテンツを操作するためのインターフェイスを表します。"
type: docs
weight: 30
url: /ja/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

ドキュメントの TaggedPdf コンテンツを操作するためのインターフェイスを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | {@link AnnotElement} を作成します。 |
| [createArtElement](#createArtElement--) | {@link ArtElement} を作成します。 |
| [createBibEntryElement](#createBibEntryElement--) | {@link BibEntryElement} を作成します。 |
| [createBlockQuoteElement](#createBlockQuoteElement--) | {@link BlockQuoteElement} を作成します。 |
| [createCaptionElement](#createCaptionElement--) | {@link CaptionElement} を作成します。 |
| [createCodeElement](#createCodeElement--) | {@link CodeElement} を作成します。 |
| [createDivElement](#createDivElement--) | {@link DivElement} を作成します。 |
| [createFigureElement](#createFigureElement--) | {@link FigureElement} を作成します。 |
| [createFormElement](#createFormElement--) | {@link FormElement} を作成します。 |
| [createFormulaElement](#createFormulaElement--) | {@link FormulaElement} を作成します。 |
| [createHeaderElement](#createHeaderElement--) | {@link HeaderElement} を作成します。 |
| [createHeaderElement](#createHeaderElement-int-) | レベルを指定して {@link HeaderElement} を作成します。 |
| [createIndexElement](#createIndexElement--) | {@link IndexElement} を作成します。 |
| [createLinkElement](#createLinkElement--) | {@link LinkElement} を作成します。 |
| [createListElement](#createListElement--) | {@link ListElement} を作成します。 |
| [createListLblElement](#createListLblElement--) | {@link ListLblElement} を作成します。 |
| [createListLBodyElement](#createListLBodyElement--) | {@link ListLBodyElement} を作成します。 |
| [createListLIElement](#createListLIElement--) | {@link ListLIElement} を作成します。 |
| [createNonStructElement](#createNonStructElement--) | {@link NonStructElement} を作成します。 |
| [createNoteElement](#createNoteElement--) | {@link NoteElement} を作成します。 |
| [createParagraphElement](#createParagraphElement--) | {@link ParagraphElement} を作成します。 |
| [createPartElement](#createPartElement--) | {@link PartElement} を作成します。 |
| [createPrivateElement](#createPrivateElement--) | {@link PrivateElement} を作成します。 |
| [createQuoteElement](#createQuoteElement--) | {@link QuoteElement} を作成します。 |
| [createReferenceElement](#createReferenceElement--) | {@link ReferenceElement} を作成します。 |
| [createRubyElement](#createRubyElement--) | {@link RubyElement} を作成します。 |
| [createSectElement](#createSectElement--) | 作成します {@link SectElement}。 |
| [createSpanElement](#createSpanElement--) | 作成します {@link SpanElement}。 |
| [createTableElement](#createTableElement--) | 作成します {@link TableElement}。 |
| [createTableTBodyElement](#createTableTBodyElement--) | 作成します {@link TableTHeadElement}。 |
| [createTableTDElement](#createTableTDElement--) | 作成します {@link TableTDElement}。 |
| [createTableTFootElement](#createTableTFootElement--) | 作成します {@link TableTFootElement}。 |
| [createTableTHeadElement](#createTableTHeadElement--) | 作成します {@link TableTHeadElement}。 |
| [createTableTHElement](#createTableTHElement--) | 作成します {@link TableTHElement}。 |
| [createTableTRElement](#createTableTRElement--) | 作成します {@link TableTRElement}。 |
| [createTOCElement](#createTOCElement--) | 作成します {@link TOCElement}。 |
| [createTOCIElement](#createTOCIElement--) | 作成します {@link TOCIElement}。 |
| [createWarichuElement](#createWarichuElement--) | 作成します {@link WarichuElement}。 |
| [getRootElement](#getRootElement--) | PDFドキュメントの論理構造のルート {@link StructureElement} を取得します。 |
| [getStructTreeRootElement](#getStructTreeRootElement--) | PDFドキュメントの {@link StructTreeRootElement} を取得します。 |
| [getStructureTextState](#getStructureTextState--) | ドキュメント全体の {@link StructureTextState} 設定を取得します。 |
| [preSave](#preSave--) | ドキュメントのタグ付けされたコンテンツを保存のために準備します。このメソッドは必要な保存前操作を実行し、構造ツリーやその他のタグ付けコンテンツ要素がドキュメントの保存前に適切に構成されていることを保証します。 |
| [save](#save--) | タグ付けされたコンテンツの現在の状態を関連付けられた PDF ドキュメントに保存します。このメソッドは、すべてのタグ付けコンテンツ要素が適切に更新され、PDF ドキュメント内に保存されることを保証します。MCR 要素の MCID の更新、BDC 演算子の設定、PDF/UA 標準への準拠など、必要な操作を実行します。 |
| [setLanguage](#setLanguage-java.lang.String-) | / * PDF ドキュメントの自然言語を取得します。 / * 構造要素やマークドコンテンツの言語指定で上書きされる場合を除き、ドキュメント内のすべてのテキストの自然言語を指定する言語識別子です。 / * / * |
| [setTitle](#setTitle-java.lang.String-) | PDF ドキュメントのタイトルを設定します。 |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

{@link AnnotElement} を作成します。

**Returns:**
構造要素が作成されました。

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

{@link ArtElement} を作成します。

**Returns:**
構造要素が作成されました。

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

{@link BibEntryElement} を作成します。

**Returns:**
構造要素が作成されました。

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

{@link BlockQuoteElement} を作成します。

**Returns:**
構造要素が作成されました。

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

{@link CaptionElement} を作成します。

**Returns:**
構造要素が作成されました。

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

{@link CodeElement} を作成します。

**Returns:**
構造要素が作成されました。

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

{@link DivElement} を作成します。

**Returns:**
構造要素が作成されました。

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

{@link FigureElement} を作成します。

**Returns:**
構造要素が作成されました。

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

{@link FormElement} を作成します。

**Returns:**
構造要素が作成されました。

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

{@link FormulaElement} を作成します。

**Returns:**
構造要素が作成されました。

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

{@link HeaderElement} を作成します。

**Returns:**
構造要素が作成されました。

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

レベルを指定して {@link HeaderElement} を作成します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| level |  | ヘッダーのレベルです。1、2、3、4、5、または 6 である必要があります。 |

**Returns:**
構造要素が作成されました。

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

{@link IndexElement} を作成します。

**Returns:**
構造要素が作成されました。

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

{@link LinkElement} を作成します。

**Returns:**
構造要素が作成されました。

### createListElement {#createListElement--}
```
ListElement createListElement()
```

{@link ListElement} を作成します。

**Returns:**
構造要素が作成されました。

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

{@link ListLblElement} を作成します。

**Returns:**
構造要素が作成されました。

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

{@link ListLBodyElement} を作成します。

**Returns:**
構造要素が作成されました。

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

{@link ListLIElement} を作成します。

**Returns:**
構造要素が作成されました。

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

{@link NonStructElement} を作成します。

**Returns:**
構造要素が作成されました。

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

{@link NoteElement} を作成します。

**Returns:**
構造要素が作成されました。

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

{@link ParagraphElement} を作成します。

**Returns:**
構造要素が作成されました。

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

{@link PartElement} を作成します。

**Returns:**
構造要素が作成されました。

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

{@link PrivateElement} を作成します。

**Returns:**
構造要素が作成されました。

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

{@link QuoteElement} を作成します。

**Returns:**
構造要素が作成されました。

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

{@link ReferenceElement} を作成します。

**Returns:**
構造要素が作成されました。

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

{@link RubyElement} を作成します。

**Returns:**
構造要素が作成されました。

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

作成します {@link SectElement}。

**Returns:**
構造要素が作成されました。

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

作成します {@link SpanElement}。

**Returns:**
構造要素が作成されました。

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

作成します {@link TableElement}。

**Returns:**
構造要素が作成されました。

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

作成します {@link TableTHeadElement}。

**Returns:**
構造要素が作成されました。

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

作成します {@link TableTDElement}。

**Returns:**
構造要素が作成されました。

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

作成します {@link TableTFootElement}。

**Returns:**
構造要素が作成されました。

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

作成します {@link TableTHeadElement}。

**Returns:**
構造要素が作成されました。

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

作成します {@link TableTHElement}。

**Returns:**
構造要素が作成されました。

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

作成します {@link TableTRElement}。

**Returns:**
構造要素が作成されました。

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

作成します {@link TOCElement}。

**Returns:**
構造要素が作成されました。

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

作成します {@link TOCIElement}。

**Returns:**
構造要素が作成されました。

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

作成します {@link WarichuElement}。

**Returns:**
構造要素が作成されました。

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

PDFドキュメントの論理構造のルート {@link StructureElement} を取得します。

**Returns:**
PDF ドキュメントの論理構造のルート {@link StructureElement}。

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

PDFドキュメントの {@link StructTreeRootElement} を取得します。

**Returns:**
PDF ドキュメントの StructTreeRootElement。

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

ドキュメント全体の {@link StructureTextState} 設定を取得します。

**Returns:**
値: ドキュメント全体の {@link StructureTextState} 設定。

### preSave {#preSave--}
```
void preSave()
```

ドキュメントのタグ付けされたコンテンツを保存のために準備します。このメソッドは必要な保存前操作を実行し、構造ツリーやその他のタグ付けコンテンツ要素がドキュメントの保存前に適切に構成されていることを保証します。

### save {#save--}
```
void save()
```

タグ付けされたコンテンツの現在の状態を関連付けられた PDF ドキュメントに保存します。このメソッドは、すべてのタグ付けコンテンツ要素が適切に更新され、PDF ドキュメント内に保存されることを保証します。MCR 要素の MCID の更新、BDC 演算子の設定、PDF/UA 標準への準拠など、必要な操作を実行します。

### setLanguage {#setLanguage-java.lang.String-}
/ * PDF ドキュメントの自然言語を取得します。 / * 構造要素やマークドコンテンツの言語指定で上書きされる場合を除き、ドキュメント内のすべてのテキストの自然言語を指定する言語識別子です。 / * / *

### setTitle {#setTitle-java.lang.String-}
PDF ドキュメントのタイトルを設定します。
