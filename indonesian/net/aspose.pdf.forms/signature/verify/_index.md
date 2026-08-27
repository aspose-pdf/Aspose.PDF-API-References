---
title: "Signature.Verify"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Signature. Memverifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya"
type: docs
weight: 170
url: /id/net/aspose.pdf.forms/signature/verify/
---
## Verify() {#verify}

Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya.

```csharp
public bool Verify()
```

### Nilai Kembalian

true jika dokumen valid.

### Lihat Juga

* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(ValidationOptions, out ValidationResult) {#verify_1}

Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya.

```csharp
public bool Verify(ValidationOptions options, out ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | ValidationOptions | Opsi verifikasi. |
| validationResult | ValidationResult& | Hasil validasi sertifikat. |

### Nilai Kembalian

true jika dokumen valid.

### Lihat Juga

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Verify(X509Certificate2, ValidationOptions, out ValidationResult) {#verify_2}

Verifikasi dokumen terkait tanda tangan ini dan mengembalikan true jika dokumen valid atau false sebaliknya. Verifikasi dilakukan menggunakan sertifikat kunci publik eksternal.

```csharp
public bool Verify(X509Certificate2 publicKeyCertificate, ValidationOptions options, 
    out ValidationResult validationResult)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| publicKeyCertificate | X509Certificate2 | Sertifikat kunci publik untuk verifikasi. |
| options | ValidationOptions | Opsi verifikasi. |
| validationResult | ValidationResult& | Hasil validasi sertifikat. |

### Nilai Kembalian

true jika dokumen valid.

### Lihat Juga

* class [ValidationOptions](../../../aspose.pdf.security/validationoptions/)
* class [ValidationResult](../../../aspose.pdf.security/validationresult/)
* class [Signature](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


