---
title: "PdfContentEditor.DeleteImage"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。指定されたページ上の指定された画像を削除します。"
type: docs
weight: 320
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/deleteimage/
---
## DeleteImage(int, int[]) {#deleteimage_1}

指定されたページ上の指定された画像を削除します。

```csharp
public void DeleteImage(int pageNumber, int[] index)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| pageNumber | Int32 | 画像を削除するページ番号です。 |
| インデックス | Int32[] | 画像のインデックスを表す配列です。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.DeleteImage(1, new int[] {1, 2});
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteImage() {#deleteimage}

PDFドキュメントからすべての画像を削除します。

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

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


