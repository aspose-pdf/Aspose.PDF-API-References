---
title: "PDF3DAnnotation"
linktitle: "PDF3DAnnotation"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDF3DAnnotation クラス。このクラスは継承できません。 @see Annotation"
type: docs
weight: 3560
url: /ja/java/com.aspose.pdf/pdf3dannotation/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.PDF3DAnnotation, com.aspose.pdf.Annotation, com.aspose.pdf.PDF3DAnnotation

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class PDF3DAnnotation extends Annotation
```

PDF3DAnnotation クラス。このクラスは継承できません。 @see Annotation

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-) | 新しい {@code PDF3DAnnotation} クラスのインスタンスを初期化します。 |
| [PDF3DAnnotation](#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-) | 新しい {@code PDF3DAnnotation} クラスのインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | 注釈処理のためのビジターを受け入れます。 |
| [clearImagePreview](#clearImagePreview--) | 画像プレビューをクリアします。 |
| [getAnnotationType](#getAnnotationType--) | アノテーションのタイプを取得します。値: アノテーションのタイプです。 |
| [getContent](#getContent--) | コンテンツを取得または設定します。値: コンテンツです。 |
| [getImagePreview](#getImagePreview--) | 画像プレビューを取得します。 |
| [getLightingScheme](#getLightingScheme--) | 照明スキームを取得します。値: 照明スキームです。 |
| [getPdf3DArtwork](#getPdf3DArtwork--) | 3D アートワークを取得します。値: PDF3 d アートワークです。 |
| [getRenderMode](#getRenderMode--) | レンダーモードを取得します。値: レンダーモードです。 |
| [getViewArray](#getViewArray--) | ビュー配列を取得します。値: ビュー配列です。 |
| [setContent](#setContent-com.aspose.pdf.PDF3DContent-) | コンテンツを取得または設定します。値: コンテンツです。 |
| [setDefaultViewIndex](#setDefaultViewIndex-int-) | デフォルトビューのインデックスを設定します。 |
| [setImagePreview](#setImagePreview-java.io.InputStream-) | 画像プレビューを設定します。 |
| [setImagePreview](#setImagePreview-java.lang.String-) | 画像プレビューを設定します。 |

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-}
新しい {@code PDF3DAnnotation} クラスのインスタンスを初期化します。

### PDF3DAnnotation {#PDF3DAnnotation-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-com.aspose.pdf.PDF3DArtwork-com.aspose.pdf.PDF3DActivation-}
新しい {@code PDF3DAnnotation} クラスのインスタンスを初期化します。

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
注釈処理のためのビジターを受け入れます。

### clearImagePreview {#clearImagePreview--}
```
public void clearImagePreview()
```

画像プレビューをクリアします。

### getAnnotationType {#getAnnotationType--}
```
public AnnotationType getAnnotationType()
```

アノテーションのタイプを取得します。値: アノテーションのタイプです。

**Returns:**
int 値です。

### getContent {#getContent--}
```
public PDF3DContent getContent()
```

コンテンツを取得または設定します。値: コンテンツです。

**Returns:**
PDF3DContent オブジェクト

### getImagePreview {#getImagePreview--}
```
public InputStream getImagePreview()
```

画像プレビューを取得します。

**Returns:**
ストリームとしての画像プレビュー。

### getLightingScheme {#getLightingScheme--}
```
public PDF3DLightingScheme getLightingScheme()
```

照明スキームを取得します。値: 照明スキームです。

**Returns:**
PDF3DLightingScheme オブジェクト

### getPdf3DArtwork {#getPdf3DArtwork--}
```
public PDF3DArtwork getPdf3DArtwork()
```

3D アートワークを取得します。値: PDF3 d アートワークです。

**Returns:**
PDF3DArtwork オブジェクト

### getRenderMode {#getRenderMode--}
```
public PDF3DRenderMode getRenderMode()
```

レンダーモードを取得します。値: レンダーモードです。

**Returns:**
PDF3DRenderMode オブジェクト

### getViewArray {#getViewArray--}
```
public PDF3DViewArray getViewArray()
```

ビュー配列を取得します。値: ビュー配列です。

**Returns:**
PDF3DViewArray オブジェクト

### setContent {#setContent-com.aspose.pdf.PDF3DContent-}
コンテンツを取得または設定します。値: コンテンツです。

### setDefaultViewIndex {#setDefaultViewIndex-int-}
```
public void setDefaultViewIndex(int index)
```

デフォルトビューのインデックスを設定します。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| インデックス |  | デフォルトビューインデックスです。 |

### setImagePreview {#setImagePreview-java.io.InputStream-}
画像プレビューを設定します。

### setImagePreview {#setImagePreview-java.lang.String-}
画像プレビューを設定します。
