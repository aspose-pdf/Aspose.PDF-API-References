---
title: "注釈"
linktitle: "注釈"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "アノテーションオブジェクトを表すクラスです。"
type: docs
weight: 60
url: /ja/java/com.aspose.pdf/annotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public abstract class Annotation extends BaseParagraph
```

アノテーションオブジェクトを表すクラスです。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈処理のためのビジターを受け入れます。 |
| [changeAfterResize](#changeAfterResize-com.aspose.pdf.Matrix-) | 行列変換に従ってパラメータと外観を更新します。 |
| [createAnnotation](#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-) | 内部使用のみです。 |
| [flatten](#flatten--) | 注釈の内容をページに直接配置し、注釈オブジェクトは削除されます。 |
| [getActiveState](#getActiveState--) | 現在の注釈外観状態を取得します。 |
| [getAlignment](#getAlignment--) | ff / * / * 既存の状態名に従って \"checked\" 状態の名前を返します。 / * / * / * |
| [getAnnotationType](#getAnnotationType--) | 注釈のタイプを取得します。 |
| [getAppearance](#getAppearance--) | 注釈の外観ディクショナリを取得します。 |
| [getAssignedPageIndex](#getAssignedPageIndex--) | 注釈が表示されるページのインデックス（1ベース）を取得します。 |
| [getBorder](#getBorder--) | 注釈の境界特性を取得します。 {@code Border} |
| [getCharacteristics](#getCharacteristics--) | 注釈の特性を取得します。 |
| [getColor](#getColor--) | 注釈の色を取得します。 |
| [getContents](#getContents--) | 注釈のテキストを取得します。 |
| [getEngineDict](#getEngineDict--) | 内部のみ |
| [getEngineObj](#getEngineObj--) | 内部使用のみ |
| [getFlags](#getFlags--) | 注釈のフラグを取得します。 |
| [getFullName](#getFullName--) | 注釈の完全修飾名を取得します。 |
| [getHeight](#getHeight--) | 注釈の高さを取得します。 |
| [getHorizontalAlignment_Annotation_New](#getHorizontalAlignment_Annotation_New--) | 注釈のテキスト配置を取得または設定します。 |
| [getModified](#getModified--) | 注釈が最近変更された日時を取得します。 |
| [getModifiedInternal](#getModifiedInternal--) | 注釈が最近変更された日時を取得します。 |
| [getName](#getName--) | ページ上の注釈名を取得します。 |
| [getNormalAppearance](#getNormalAppearance--) | 標準の外観を取得します。 |
| [getPage](#getPage--) | この注釈が関連付けられているページオブジェクトを取得します。 |
| [getPageIndex](#getPageIndex--) | 注釈を含むページのインデックスを取得します。 |
| [getPageIndex](#getPageIndex-com.aspose.pdf.Annotation-) | 注釈を含むページのインデックスを取得します。 |
| [getPdfActions](#getPdfActions--) | 注釈アクションの一覧を取得します。 |
| [getRect](#getRect--) | 注釈の矩形を取得します。 |
| [getRectangle](#getRectangle-boolean-) | ページ回転を考慮した注釈の矩形を返します。 |
| [getStates](#getStates--) | 注釈の外観辞書を取得します。 |
| [getTextHorizontalAlignment](#getTextHorizontalAlignment--) | 注釈のテキスト配置を取得します。 |
| [getWidth](#getWidth--) | 注釈の幅を取得します。 |
| [initialize](#initialize-com.aspose.pdf.IDocument-) | インスタンスの初期化 |
| [isUpdateAppearanceOnConvert](#isUpdateAppearanceOnConvert--) | true の場合、PDF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。 |
| [isUseFontSubset](#isUseFontSubset--) | このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。 |
| [setActiveState](#setActiveState-java.lang.String-) | 現在の注釈の外観状態を設定します。 |
| [setAlignment](#setAlignment-com.aspose.pdf.TextAlignment-) | 注釈の配置。 このプロパティは廃止予定です。代わりに getHorizontalAlignment_Annotation_New を使用してください。 |
| [setAssignedPageIndex](#setAssignedPageIndex-com.aspose.ms.System.Nullable-) | 注釈が表示されるページインデックス（1 から始まる）を設定します。 |
| [setBorder](#setBorder-com.aspose.pdf.Border-) | 注釈の境界線特性を設定します。 {@code Border} |
| [setColor](#setColor-com.aspose.pdf.Color-) | 注釈の色を設定します。 |
| [setContents](#setContents-java.lang.String-) | 注釈のテキストを設定します。 |
| [setFlags](#setFlags-int-) | 注釈のフラグを設定します。 |
| [setHeight](#setHeight-double-) | 注釈の高さを設定します。 |
| [setHorizontalAlignment_Annotation_New](#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-) | 注釈のテキスト配置を取得または設定します。 |
| [setModified](#setModified-java.util.Date-) | 注釈が最近変更された日時を設定します。 |
| [setModifiedInternal](#setModifiedInternal-com.aspose.ms.System.DateTime-) | 注釈が最近変更された日時を設定します。 |
| [setName](#setName-java.lang.String-) | ページ上の注釈名を設定します。 |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | 注釈の矩形を設定します。 |
| [setTextHorizontalAlignment](#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | 注釈のテキスト配置を設定します。 |
| [setUpdateAppearanceOnConvert](#setUpdateAppearanceOnConvert-boolean-) | true の場合、PDF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。 |
| [setUseFontSubset](#setUseFontSubset-boolean-) | このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。 |
| [setWidth](#setWidth-double-) | 注釈の幅を設定します。 |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈処理のためのビジターを受け入れます。

### changeAfterResize {#changeAfterResize-com.aspose.pdf.Matrix-}
行列変換に従ってパラメータと外観を更新します。

### createAnnotation {#createAnnotation-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.Page-}
内部使用のみです。

### flatten {#flatten--}
```
public void flatten()
```

注釈の内容をページに直接配置し、注釈オブジェクトは削除されます。

### getActiveState {#getActiveState--}
```
public String getActiveState()
```

現在の注釈外観状態を取得します。

**Returns:**
文字列値

### getAlignment {#getAlignment--}
```
@Deprecated public TextAlignment getAlignment()
```

ff / * / * 既存の状態名に従って \"checked\" 状態の名前を返します。 / * / * / *

**Returns:**
文字列値 /

### getAnnotationType {#getAnnotationType--}
```
public abstract AnnotationType getAnnotationType()
```

注釈のタイプを取得します。

**Returns:**
整数値 @see AnnotationType

### getAppearance {#getAppearance--}
```
public AppearanceDictionary getAppearance()
```

注釈の外観ディクショナリを取得します。

**Returns:**
AppearanceDictionary オブジェクト

### getAssignedPageIndex {#getAssignedPageIndex--}
```
public final com.aspose.ms.System.Nullable< Integer > getAssignedPageIndex()
```

注釈が表示されるページのインデックス（1ベース）を取得します。

**Returns:**
注釈が表示されるページインデックス（1ベース）です。

### getBorder {#getBorder--}
```
public Border getBorder()
```

注釈の境界特性を取得します。 {@code Border}

**Returns:**
Border オブジェクト

### getCharacteristics {#getCharacteristics--}
```
public Characteristics getCharacteristics()
```

注釈の特性を取得します。

**Returns:**
Characteristics オブジェクト

### getColor {#getColor--}
```
public Color getColor()
```

注釈の色を取得します。

**Returns:**
Color オブジェクト

### getContents {#getContents--}
```
public String getContents()
```

注釈のテキストを取得します。

**Returns:**
文字列値

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

内部のみ

**Returns:**
IPdfDictionary オブジェクト

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

内部使用のみ

**Returns:**
内部オブジェクト

### getFlags {#getFlags--}
```
public int getFlags()
```

注釈のフラグを取得します。

**Returns:**
注釈のフラグ @see AnnotationFlags

### getFullName {#getFullName--}
```
public String getFullName()
```

注釈の完全修飾名を取得します。

**Returns:**
文字列値

### getHeight {#getHeight--}
```
public double getHeight()
```

注釈の高さを取得します。

**Returns:**
注釈の高さ

### getHorizontalAlignment_Annotation_New {#getHorizontalAlignment_Annotation_New--}
```
@Deprecated public final HorizontalAlignment getHorizontalAlignment_Annotation_New()
```

注釈のテキスト配置を取得または設定します。

**Returns:**
注釈のテキスト配置。 @see HorizontalAlignment @deprecated TextHorizontalAlignment プロパティを使用してください

### getModified {#getModified--}
```
public Date getModified()
```

注釈が最近変更された日時を取得します。

**Returns:**
注釈が最近変更された日時。

### getModifiedInternal {#getModifiedInternal--}
```
public com.aspose.ms.System.DateTime getModifiedInternal()
```

注釈が最近変更された日時を取得します。

**Returns:**
DateTime オブジェクト

### getName {#getName--}
```
public String getName()
```

ページ上の注釈名を取得します。

**Returns:**
文字列値

### getNormalAppearance {#getNormalAppearance--}
```
public XForm getNormalAppearance()
```

標準の外観を取得します。

**Returns:**
XForm オブジェクト

### getPage {#getPage--}
```
public Page getPage()
```

この注釈が関連付けられているページオブジェクトを取得します。

**Returns:**
Page オブジェクト

### getPageIndex {#getPageIndex--}
```
public int getPageIndex()
```

注釈を含むページのインデックスを取得します。

**Returns:**
int 値です。

### getPageIndex {#getPageIndex-com.aspose.pdf.Annotation-}
注釈を含むページのインデックスを取得します。

**Returns:**
int 値です。

### getPdfActions {#getPdfActions--}
```
public PdfActionCollection getPdfActions()
```

注釈アクションの一覧を取得します。

**Returns:**
PdfActionCollection インスタンス

### getRect {#getRect--}
```
public Rectangle getRect()
```

注釈の矩形を取得します。

**Returns:**
Rectangle オブジェクト

### getRectangle {#getRectangle-boolean-}
```
public Rectangle getRectangle(boolean considerRotation)
```

ページ回転を考慮した注釈の矩形を返します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| considerRotation |  | true の場合、ページの回転が考慮されます。 |

**Returns:**
Rectangle オブジェクト

### getStates {#getStates--}
```
public AppearanceDictionary getStates()
```

注釈の外観辞書を取得します。

**Returns:**
AppearanceDictionary オブジェクト

### getTextHorizontalAlignment {#getTextHorizontalAlignment--}
```
public HorizontalAlignment getTextHorizontalAlignment()
```

注釈のテキスト配置を取得します。

**Returns:**
注釈のテキスト配置。 @see HorizontalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

注釈の幅を取得します。

**Returns:**
double 値、注釈の幅。

### initialize {#initialize-com.aspose.pdf.IDocument-}
インスタンスの初期化

### isUpdateAppearanceOnConvert {#isUpdateAppearanceOnConvert--}
```
public static boolean isUpdateAppearanceOnConvert()
```

true の場合、PDF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。

**Returns:**
ブール値

### isUseFontSubset {#isUseFontSubset--}
```
public static boolean isUseFontSubset()
```

このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。

**Returns:**
ブール値

### setActiveState {#setActiveState-java.lang.String-}
現在の注釈の外観状態を設定します。

### setAlignment {#setAlignment-com.aspose.pdf.TextAlignment-}
注釈の配置。 このプロパティは廃止予定です。代わりに getHorizontalAlignment_Annotation_New を使用してください。

### setAssignedPageIndex {#setAssignedPageIndex-com.aspose.ms.System.Nullable-}
注釈が表示されるページインデックス（1 から始まる）を設定します。

### setBorder {#setBorder-com.aspose.pdf.Border-}
注釈の境界線特性を設定します。 {@code Border}

### setColor {#setColor-com.aspose.pdf.Color-}
注釈の色を設定します。

### setContents {#setContents-java.lang.String-}
注釈のテキストを設定します。

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

注釈のフラグを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 注釈のフラグ @see AnnotationFlags |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

注釈の高さを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 注釈の高さ |

### setHorizontalAlignment_Annotation_New {#setHorizontalAlignment_Annotation_New-com.aspose.pdf.HorizontalAlignment-}
注釈のテキスト配置を取得または設定します。

### setModified {#setModified-java.util.Date-}
注釈が最近変更された日時を設定します。

### setModifiedInternal {#setModifiedInternal-com.aspose.ms.System.DateTime-}
注釈が最近変更された日時を設定します。

### setName {#setName-java.lang.String-}
ページ上の注釈名を設定します。

### setRect {#setRect-com.aspose.pdf.Rectangle-}
注釈の矩形を設定します。

### setTextHorizontalAlignment {#setTextHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
注釈のテキスト配置を設定します。

### setUpdateAppearanceOnConvert {#setUpdateAppearanceOnConvert-boolean-}
```
public static void setUpdateAppearanceOnConvert(boolean value)
```

true の場合、PDF ドキュメントを画像に変換する前に注釈の外観が更新されます。これによりフィールドが正しく変換されますが、時間がかかる可能性があります。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setUseFontSubset {#setUseFontSubset-boolean-}
```
public static void setUseFontSubset(boolean value)
```

このプロパティが true に設定されている場合、フォントはサブセットとしてドキュメントに追加されます。デフォルト値は true です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | ブール値 |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

注釈の幅を設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | 注釈の幅。 |
