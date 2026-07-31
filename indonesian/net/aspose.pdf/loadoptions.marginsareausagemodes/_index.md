---
title: "Enum LoadOptions.MarginsAreaUsageModes"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.LoadOptionsMarginsAreaUsageModes enum. Mewakili mode penggunaan area margin selama konversi seperti HTML, EPUB, dll., yang mendefinisikan penanganan instruksi format yang diimpor terkait penggunaan margin"
type: docs
weight: 6270
url: /id/net/aspose.pdf/loadoptions.marginsareausagemodes/
---
## LoadOptions.MarginsAreaUsageModes enumeration

Mewakili mode penggunaan area margin selama konversi (seperti HTML, EPUB, dll.), mendefinisikan penanganan instruksi format yang diimpor terkait penggunaan margin.

```csharp
public enum MarginsAreaUsageModes
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | `0` | Dalam mode ini konverter mematuhi format dokumen yang diimpor (misalnya CSS dari HTML yang diimpor) dalam penggunaan area margin. Jadi, jika format dokumen yang diimpor memerlukan penggunaan area margin untuk rendering, konverter akan mengizinkannya. |
| NeverPutContentOnMarginArea | `1` | Mode ini secara tegas melarang penggunaan area margin, sehingga konverter tidak akan pernah menggunakan area margin untuk rendering, bahkan jika CSS atau format dokumen sumber mengizinkan atau memerlukannya. |

### Lihat Juga

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


