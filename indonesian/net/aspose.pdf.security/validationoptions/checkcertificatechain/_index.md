---
title: "ValidationOptions.CheckCertificateChain"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti ValidationOptions. Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi"
type: docs
weight: 20
url: /id/net/aspose.pdf.security/validationoptions/checkcertificatechain/
---
## ValidationOptions.CheckCertificateChain property

Mendapatkan atau mengatur nilai yang menunjukkan apakah rantai sertifikat harus diperiksa selama proses validasi.

```csharp
public bool CheckCertificateChain { get; set; }
```

## Catatan

Ketika properti diatur, keberadaan rantai sertifikat akan diperiksa; jika tidak ada, maka hasil verifikasi akan menjadi Undefined, yang sesuai dengan perilaku Adobe Acrobat. Jika Anda hanya ingin memeriksa status pencabutan secara daring, maka setel bidang tersebut ke `false`. Nilai default adalah `false`.

### Lihat Juga

* class [ValidationOptions](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


