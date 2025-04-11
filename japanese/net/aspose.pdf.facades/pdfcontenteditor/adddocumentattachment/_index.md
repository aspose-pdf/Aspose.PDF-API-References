---
title: PdfContentEditor.AddDocumentAttachment
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor メソッド。注釈なしでドキュメント添付ファイルを追加します
type: docs
weight: 70
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/adddocumentattachment/
---
## AddDocumentAttachment(string, string) {#adddocumentattachment_1}

注釈なしでドキュメント添付ファイルを追加します。

```csharp
public void AddDocumentAttachment(string fileAttachmentPath, string description)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileAttachmentPath | String | 添付されるファイルのパス。 |
| description | String | 説明情報。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.AddDocumentAttachment("attachment_file.pdf", "description of attachment_file");
editor.Save("example_out.pdf");
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## AddDocumentAttachment(Stream, string, string) {#adddocumentattachment}

注釈なしでドキュメント添付ファイルを追加します。

```csharp
public void AddDocumentAttachment(Stream fileAttachmentStream, string fileAttachmentName, 
    string description)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileAttachmentStream | Stream | 添付されるファイルのストリーム。 |
| fileAttachmentName | String | 添付ファイル名。 |
| description | String | 説明情報。 |

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
using(System.IO.FileStream attStream = System.IO.File.OpenRead("attachment_file.pdf"))
{
    editor.AddDocumentAttachment(attStream, "attachment_file.pdf", "description of attachment_file");
    editor.Save("example_out.pdf");
}    
```

### 参照

* クラス [PdfContentEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)