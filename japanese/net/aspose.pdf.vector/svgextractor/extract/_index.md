---
title: SvgExtractor.Extract
second_title: Aspose.PDF for .NET API Reference
description: SvgExtractor メソッド。グラフィック要素から SVG 画像を文字列に抽出します。これは、述語フィルターを持つアブソーバーによって表されます。
type: docs
weight: 20
url: /ja/net/aspose.pdf.vector/svgextractor/extract/
---
## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page) {#extract_1}

グラフィック要素から SVG 画像を文字列に抽出します。これは、述語フィルターを持つ !:absorber によって表されます。

```csharp
public string Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | グラフィック要素を含む GraphicsAbsorber オブジェクト。 |
| filter | Predicate`1 | グラフィック要素をフィルタリングするために使用される述語関数。 |
| page | Page | アブソーバーがグラフィック要素を取得するページ。 |

### 戻り値

SVG コンテンツを含む文字列。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [GraphicsAbsorber](../../graphicsabsorber/)
* クラス [GraphicElement](../../graphicelement/)
* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(GraphicsAbsorber, Predicate&lt;GraphicElement&gt;, Page, string) {#extract_4}

グラフィック要素からファイルに SVG 画像を抽出します。これは、述語フィルターを持つ !:absorber によって表されます。

```csharp
public void Extract(GraphicsAbsorber absorber, Predicate<GraphicElement> filter, Page page, 
    string svgFilePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| absorber | GraphicsAbsorber | グラフィック要素を含む GraphicsAbsorber オブジェクト。 |
| filter | Predicate`1 | グラフィック要素をフィルタリングするために使用される述語関数。 |
| page | Page | アブソーバーがグラフィック要素を取得するページ。 |
| svgFilePath | String | 対象の SVG ファイルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [GraphicsAbsorber](../../graphicsabsorber/)
* クラス [GraphicElement](../../graphicelement/)
* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page) {#extract_2}

グラフィック要素を SVG 文字列に抽出します。オプションは無視されます - グループ化、長方形からの抽出

```csharp
public string Extract(IEnumerable<GraphicElement> elements, Page page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| elements | IEnumerable`1 | 変換するグラフィック要素。 |
| page | Page | アブソーバーがグラフィック要素を取得するページ。 |

### 戻り値

SVG コンテンツを含む文字列。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [GraphicElement](../../graphicelement/)
* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(IEnumerable&lt;GraphicElement&gt;, Page, string) {#extract_5}

グラフィック要素を単一の SVG ファイルに抽出します。オプションは無視されます - グループ化、長方形からの抽出

```csharp
public void Extract(IEnumerable<GraphicElement> elements, Page page, string svgFilePath)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| elements | IEnumerable`1 | 変換するグラフィック要素。 |
| page | Page | アブソーバーがグラフィック要素を取得するページ。 |
| svgFilePath | String | 対象の SVG ファイルパス。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [GraphicElement](../../graphicelement/)
* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(Page) {#extract}

ページから SVG 画像を文字列に抽出します。

```csharp
public List<string> Extract(Page page)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Page | 抽出するページ。 |

### 戻り値

SVG コンテンツ文字列のリスト。

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)

---

## Extract(Page, string) {#extract_3}

ページからファイルに SVG 画像を抽出します。

```csharp
public void Extract(Page page, string directory)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| page | Page | 抽出するページ。 |
| directory | String | SVG 画像を配置する対象ディレクトリ。 |

### 例外

| 例外 | 条件 |
| --- | --- |
| [PdfException](../../../aspose.pdf/pdfexception/) | SVG への変換中にエラーが発生した場合。 |

### 参照

* クラス [Page](../../../aspose.pdf/page/)
* クラス [SvgExtractor](../)
* 名前空間 [Aspose.Pdf.Vector](../../../aspose.pdf.vector/)
* アセンブリ [Aspose.PDF](../../../)