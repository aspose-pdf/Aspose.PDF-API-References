---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfAnnotationEditor メソッド。XFDF ファイルからすべての注釈をインポートします。"
type: docs
weight: 110
url: /ja/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

XFDF ファイルからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xfdfFile | String | 入力 XFDF ファイルです。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

XFDF データストリームからすべての注釈をインポートします。

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| xfdfStream | Stream | 入力 XFDF データ ストリームです。 |

## 例

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


