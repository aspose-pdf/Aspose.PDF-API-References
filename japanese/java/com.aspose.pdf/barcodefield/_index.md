---
title: "BarcodeField"
linktitle: "BarcodeField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "バーコードフィールドを表すクラスです。"
type: docs
weight: 250
url: /ja/java/com.aspose.pdf/barcodefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.BarcodeField, com.aspose.pdf.TextBoxField, com.aspose.pdf.BarcodeField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public final class BarcodeField extends TextBoxField
```

バーコードフィールドを表すクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [BarcodeField](#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) |  {@code BarcodeField} クラスの新しいインスタンスを初期化します。 |
| [BarcodeField](#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) |  {@code BarcodeField} クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaption](#getCaption--) | バーコードオブジェクトのキャプションを取得します。 |
| [getECC](#getECC--) | エラー訂正係数を表す整数値を取得します。PDF417の場合、0から8の範囲です。QRCodeの場合、0から3の範囲です（0は 'L'、1は 'M'、2は 'Q'、3は 'H'）。 |
| [getResolution](#getResolution--) | バーコードオブジェクトがレンダリングされる解像度（ドット毎インチ (dpi)）を取得します。 |
| [getSymbology](#getSymbology--) | このアノテーションで使用するバーコードまたはグリフ技術を指定します。詳細は {@code Symbology} を参照してください。 |
| [getXSymHeight](#getXSymHeight--) | 2つのバーコードモジュール間の垂直距離をピクセル単位で取得します。比率 XSymHeight/XSymWidth は整数でなければなりません。PDF417の場合、許容される比率範囲は1から4です。QRCode および DataMatrix の場合、この比率は常に 1 です。 |
| [getXSymWidth](#getXSymWidth--) | 2つのバーコードモジュール間の水平距離をピクセル単位で取得します。 |

### BarcodeField {#BarcodeField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
 {@code BarcodeField} クラスの新しいインスタンスを初期化します。

### BarcodeField {#BarcodeField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
 {@code BarcodeField} クラスの新しいインスタンスを初期化します。

### getCaption {#getCaption--}
```
public String getCaption()
```

バーコードオブジェクトのキャプションを取得します。

**Returns:**
文字列値

### getECC {#getECC--}
```
public int getECC()
```

エラー訂正係数を表す整数値を取得します。PDF417の場合、0から8の範囲です。QRCodeの場合、0から3の範囲です（0は 'L'、1は 'M'、2は 'Q'、3は 'H'）。

**Returns:**
int 値です。

### getResolution {#getResolution--}
```
public int getResolution()
```

バーコードオブジェクトがレンダリングされる解像度（ドット毎インチ (dpi)）を取得します。

**Returns:**
int 値です。

### getSymbology {#getSymbology--}
```
public int getSymbology()
```

このアノテーションで使用するバーコードまたはグリフ技術を指定します。詳細は {@code Symbology} を参照してください。

**Returns:**
Symbology 要素 @see Symbology

### getXSymHeight {#getXSymHeight--}
```
public int getXSymHeight()
```

2つのバーコードモジュール間の垂直距離をピクセル単位で取得します。比率 XSymHeight/XSymWidth は整数でなければなりません。PDF417の場合、許容される比率範囲は1から4です。QRCode および DataMatrix の場合、この比率は常に 1 です。

**Returns:**
int 値です。

### getXSymWidth {#getXSymWidth--}
```
public int getXSymWidth()
```

2つのバーコードモジュール間の水平距離をピクセル単位で取得します。

**Returns:**
int 値です。
