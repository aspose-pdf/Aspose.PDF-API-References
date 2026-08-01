---
title: "SvgExtractor.Extract"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SvgExtractor メソッド。absorber が表すグラフィック要素から、述語フィルタを使用して SVG 画像を文字列に抽出します。"
type: docs
weight: 20
url: /ja/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

グラフィック要素（!:absorber で表され、述語フィルタ付き）から SVG 画像を文字列に抽出します。

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | グラフィック要素を含む GraphicsAbsorber オブジェクト。 |
| フィルタ | Predicate`1 | グラフィック要素をフィルタリングするために使用される述語関数。 |
| ページ | ページ | absorber がグラフィック要素を取得するページ。 |

### 戻り値

SVG コンテンツを含む文字列。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

グラフィック要素（!:absorber で表され、述語フィルタ付き）から SVG 画像をファイルに抽出します。

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | グラフィック要素を含む GraphicsAbsorber オブジェクト。 |
| フィルタ | Predicate`1 | グラフィック要素をフィルタリングするために使用される述語関数。 |
| ページ | ページ | absorber がグラフィック要素を取得するページ。 |
| svgFilePath | String | 対象 SVG ファイルのパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [GraphicsAbsorber](../../graphicsabsorber/)
* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

グラフィック要素を SVG 文字列に抽出します。オプションは無視されます - グルーピング、矩形からの抽出

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 要素 | IEnumerable`1 | 変換するグラフィック要素。 |
| ページ | ページ | absorber がグラフィック要素を取得するページ。 |

### 戻り値

SVG コンテンツを含む文字列。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

グラフィック要素を単一の SVG ファイルに抽出します。オプションは無視されます - グルーピング、矩形からの抽出

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| 要素 | IEnumerable`1 | 変換するグラフィック要素。 |
| ページ | ページ | absorber がグラフィック要素を取得するページ。 |
| svgFilePath | String | 対象 SVG ファイルのパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [GraphicElement](../../graphicelement/)
* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

ページから SVG 画像を文字列に抽出します。

```csharp
public List<string> Extract(Page page)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | 抽出対象のページ。 |

### 戻り値

SVG コンテンツ文字列のリスト。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

ページから SVG 画像をファイルに抽出します。

```csharp
public void Extract(Page page, string directory)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| ページ | ページ | 抽出対象のページ。 |
| ディレクトリ | String | SVG画像を配置する対象ディレクトリです。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG に変換中にエラーが発生した場合。 |

### 関連項目

* class [Page](../../../aspose.pdf/page/)
* class [SvgExtractor](../)
* namespace [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../../)


