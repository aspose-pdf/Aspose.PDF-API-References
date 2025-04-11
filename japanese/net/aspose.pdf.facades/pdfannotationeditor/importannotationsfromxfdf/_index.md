---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor メソッド。XFDF ファイルからすべての注釈をインポートします
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

XFDF ファイルからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xfdfFile | String | 入力 XFDF ファイル。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

XFDF データストリームからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| xfdfStream | Stream | 入力 XFDF データストリーム。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfAnnotationEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)