---
title: "ICustomSecurityHandler.Initialize"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode ICustomSecurityHandler. Dipanggil untuk menginisialisasi instance saat ini untuk enkripsi. Perhatikan bahwa saat mengenkripsi, instance akan diisi dengan data properti yang dipindahkan ICustomSecurityHandler dan saat membuka dokumen dari kamus enkripsi. Jika metode dipanggil selama enkripsi baru, maka UserKey dan OwnerKey akan bernilai null."
type: docs
weight: 120
url: /id/net/aspose.pdf.security/icustomsecurityhandler/initialize/
---
## ICustomSecurityHandler.Initialize method

Dipanggil untuk menginisialisasi instance saat ini untuk enkripsi. Perhatikan bahwa saat mengenkripsi, akan diisi dengan data properti yang dipindahkan [`ICustomSecurityHandler`](../), dan saat membuka dokumen dari kamus enkripsi. Jika metode dipanggil selama enkripsi baru, maka [`UserKey`](../../encryptionparameters/userkey/) dan [`OwnerKey`](../../encryptionparameters/ownerkey/) akan bernilai null.

```csharp
public void Initialize(EncryptionParameters parameters)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| parameter | EncryptionParameters | Parameter enkripsi. |

### Lihat Juga

* class [EncryptionParameters](../../encryptionparameters/)
* interface [ICustomSecurityHandler](../)
* namespace [Aspose.Pdf.Security](../../../aspose.pdf.security/)
* assembly [Aspose.PDF](../../../)


