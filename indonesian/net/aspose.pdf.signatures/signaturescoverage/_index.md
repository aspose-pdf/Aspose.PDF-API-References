---
title: Enum SignaturesCoverage
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Signatures.SignaturesCoverage. Mewakili enum untuk tingkat cakupan yang diberikan oleh tanda tangan digital dalam sebuah dokumen
type: docs
weight: 10110
url: /id/net/aspose.pdf.signatures/signaturescoverage/
---
## Enumerasi SignaturesCoverage

Mewakili enum untuk tingkat cakupan yang diberikan oleh tanda tangan digital dalam sebuah dokumen.

```csharp
public enum SignaturesCoverage
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Undefined | `0` | Menunjukkan bahwa status cakupan tanda tangan digital dalam dokumen tidak terdefinisi. Nilai ini biasanya digunakan ketika satu atau lebih tanda tangan dalam dokumen telah dikompromikan atau tidak dapat diverifikasi, mencegah penilaian definitif terhadap cakupan tanda tangan dokumen. |
| EntirelySigned | `1` | Menunjukkan bahwa dokumen sepenuhnya dicakup oleh tanda tangan digital. Nilai ini menandakan bahwa semua bagian yang diperlukan dari dokumen telah ditandatangani dan tidak ada tanda tangan yang dikompromikan. |
| PartiallySigned | `2` | Menunjukkan bahwa dokumen sebagian ditandatangani, yang berarti bahwa beberapa, tetapi tidak semua, kontennya dicakup oleh tanda tangan digital. Nilai ini digunakan ketika bagian tertentu dari dokumen tetap tidak ditandatangani atau dikecualikan dari cakupan tanda tangan. |

### Lihat Juga

* namespace [Aspose.Pdf.Signatures](../../aspose.pdf.signatures/)
* assembly [Aspose.PDF](../../)