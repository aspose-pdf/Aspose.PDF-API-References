---
title: "GraphicalPdfComparer"
linktitle: "GraphicalPdfComparer"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "PDFドキュメントをグラフィカルに比較するクラスを表します。主にグラフィック上の小さな変更を検索するために使用すべきです。テキストコンテンツの変更を比較する場合は、別のクラスを使用してください。"
type: docs
weight: 10
url: /ja/java/com.aspose.pdf.comparison.graphicalcomparison/graphicalpdfcomparer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.GraphicalPdfComparer

```
public class GraphicalPdfComparer extends Object
```

PDF 文書をグラフィカルに比較するクラスを表します。主にグラフィック上の小さな変更を検索するために使用すべきです。テキスト内容の変更を比較する場合は、他の PDF 比較クラスを使用してください。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [GraphicalPdfComparer](#GraphicalPdfComparer--) | {@link GraphicalPdfComparer} クラスのインスタンスを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [compareDocumentsToImages](#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-) | ドキュメントをグラフィカルに比較します。 |
| [compareDocumentsToPdf](#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-) | ドキュメントをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [comparePagesToImage](#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | ページをグラフィカルに比較します。比較結果は画像に配置されます。 |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-) | ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [comparePagesToPdf](#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-) | ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。 |
| [getColor](#getColor--) | 変更フラグの色を取得および設定します。デフォルトの色は赤です。 |
| [getDifference](#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-) | ページ画像間の差分を取得します。結果には比較された最初のページの画像と差分の配列が含まれます。 |
| [getResolution](#getResolution--) | 生成された画像の解像度を取得および設定します。デフォルト値は 150dpi です。 |
| [getThreshold](#getThreshold--) | しきい値（パーセンテージ）を取得および設定します。この値により、重要でない小さな変化を無視できます。デフォルト値は 0% です。 |
| [setColor](#setColor-com.aspose.pdf.Color-) | 変更フラグの色を取得および設定します。デフォルトの色は赤です。 |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | 生成された画像の解像度を取得および設定します。デフォルト値は 150dpi です。 |
| [setThreshold](#setThreshold-double-) | しきい値（パーセンテージ）を取得および設定します。この値により、重要でない小さな変化を無視できます。デフォルト値は 0% です。 |

### GraphicalPdfComparer {#GraphicalPdfComparer--}
```
public GraphicalPdfComparer()
```

{@link GraphicalPdfComparer} クラスのインスタンスを作成します。

### compareDocumentsToImages {#compareDocumentsToImages-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-java.lang.String-com.aspose.ms.System.Drawing.Imaging.ImageFormat-}
ドキュメントをグラフィカルに比較します。

### compareDocumentsToPdf {#compareDocumentsToPdf-com.aspose.pdf.Document-com.aspose.pdf.Document-java.lang.String-}
ドキュメントをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

### comparePagesToImage {#comparePagesToImage-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
ページをグラフィカルに比較します。比較結果は画像に配置されます。

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-com.aspose.pdf.Document-}
ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

### comparePagesToPdf {#comparePagesToPdf-com.aspose.pdf.Page-com.aspose.pdf.Page-java.lang.String-}
ページをグラフィカルに比較します。比較結果は PDF ドキュメントに配置されます。

### getColor {#getColor--}
```
public final Color getColor()
```

変更フラグの色を取得および設定します。デフォルトの色は赤です。

**Returns:**
Color インスタンス

### getDifference {#getDifference-com.aspose.pdf.Page-com.aspose.pdf.Page-}
ページ画像間の差分を取得します。結果には比較された最初のページの画像と差分の配列が含まれます。

### getResolution {#getResolution--}
```
public final Resolution getResolution()
```

生成された画像の解像度を取得および設定します。デフォルト値は 150dpi です。

**Returns:**
解像度インスタンス

### getThreshold {#getThreshold--}
```
public final double getThreshold()
```

しきい値（パーセンテージ）を取得および設定します。この値により、重要でない小さな変化を無視できます。デフォルト値は 0% です。

**Returns:**
double 値

### setColor {#setColor-com.aspose.pdf.Color-}
変更フラグの色を取得および設定します。デフォルトの色は赤です。

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
生成された画像の解像度を取得および設定します。デフォルト値は 150dpi です。

### setThreshold {#setThreshold-double-}
```
public final void setThreshold(double value)
```

しきい値（パーセンテージ）を取得および設定します。この値により、重要でない小さな変化を無視できます。デフォルト値は 0% です。

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 |  | double 値 |
