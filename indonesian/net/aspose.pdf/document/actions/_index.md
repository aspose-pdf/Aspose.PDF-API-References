---
title: "Document.Actions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Document. Mendapatkan aksi dokumen. Properti ini merupakan instance dari kelas DocumentActions yang memungkinkan untuk get/set BeforClosing BeforSaving, dll. aksi"
type: docs
weight: 30
url: /id/net/aspose.pdf/document/actions/
---
## Document.Actions property

Mendapatkan aksi dokumen. Properti ini adalah instance dari kelas DocumentActions yang memungkinkan untuk mendapatkan/mengatur aksi BeforClosing, BeforSaving, dll.

```csharp
public DocumentActionCollection Actions { get; }
```

## Contoh

Contoh ini menunjukkan cara memperoleh aksi setelah membuka dokumen:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### Lihat Juga

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


