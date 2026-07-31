---
title: "Page.Contents"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Page. Mendapatkan koleksi operator dalam aliran konten halaman. OperatorCollection"
type: docs
weight: 90
url: /id/net/aspose.pdf/page/contents/
---
## Page.Contents property

Mendapatkan koleksi operator dalam aliran konten halaman. [`OperatorCollection`](../../operatorcollection/)

```csharp
public OperatorCollection Contents { get; }
```

## Contoh

Contoh ini menunjukkan cara memindai aliran operator halaman.

```csharp
Document document = new Document("sample.pdf");
Operators contents = document.Pages[1].Contents;
foreach(Operator op in contents)
{
    Console.WriteLine(op);
}
```

### Lihat Juga

* class [OperatorCollection](../../operatorcollection/)
* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


