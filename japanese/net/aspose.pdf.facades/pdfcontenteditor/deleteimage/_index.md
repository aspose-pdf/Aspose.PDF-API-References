---
title: PdfContentEditor.DeleteImage
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。指定されたページの指定された画像を削除します
type: docs
weight: 320
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

指定されたページの指定された画像を削除します。

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 画像を削除するページの番号。 |
| index | Int32[] | 画像のインデックスを表す配列。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

PDF ドキュメントからすべての画像を削除します。

```csharp
public void DeleteImage()
```

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage();
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)