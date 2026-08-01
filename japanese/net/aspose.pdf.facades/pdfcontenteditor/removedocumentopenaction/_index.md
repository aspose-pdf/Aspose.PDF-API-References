---
title: "PdfContentEditor.RemoveDocumentOpenAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "PdfContentEditor メソッド。Document からオープンアクションを削除します。この操作は、起動時に明示的な GoTo アクションを使用する複数の Document を結合する際に便利です。"
type: docs
weight: 430
url: /ja/net/aspose.pdf.facades/pdfcontenteditor/removedocumentopenaction/
---
## PdfContentEditor.RemoveDocumentOpenAction method

ドキュメントからオープンアクションを削除します。この操作は、起動時に明示的な 'GoTo' アクションを使用する複数のドキュメントを連結する際に便利です。

```csharp
public void RemoveDocumentOpenAction()
```

## 例

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
editor.RemoveDocumentOpenAction();
editor.Save("example_out.pdf");
```

### 関連項目

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


