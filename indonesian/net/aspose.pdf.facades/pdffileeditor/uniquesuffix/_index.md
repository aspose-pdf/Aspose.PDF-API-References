---
title: "PdfFileEditor.UniqueSuffix"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti PdfFileEditor. Format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik ketika formulir digabungkan. String ini harus mengandung substring NUM yang akan diganti dengan angka. Misalnya jika UniqueSuffix  ABCNUM maka untuk bidang fieldName nama-nya akan menjadi fieldNameABC1 fieldNameABC2 fieldNameABC3, dll."
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/pdffileeditor/uniquesuffix/
---
## PdfFileEditor.UniqueSuffix property

Format akhiran yang ditambahkan ke nama bidang untuk membuatnya unik saat formulir digabungkan. String ini harus berisi substring %NUM% yang akan diganti dengan angka. Misalnya jika UniqueSuffix = \"ABC%NUM%\" maka untuk bidang \"fieldName\" nama-namanya akan menjadi: fieldNameABC1, fieldNameABC2, fieldNameABC3, dll.

```csharp
public string UniqueSuffix { get; set; }
```

## Contoh

```csharp
PdfFileEditor ed = new PdfFileEditor();
ed.UniqueSuffix = "_%NUM%";
```

### Lihat Juga

* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


