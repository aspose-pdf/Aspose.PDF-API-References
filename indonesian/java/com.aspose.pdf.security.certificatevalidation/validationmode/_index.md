---
title: "ValidationMode"
linktitle: "ValidationMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan mode validasi untuk proses validasi tanda tangan PDF."
type: docs
weight: 20
url: /id/java/com.aspose.pdf.security.certificatevalidation/validationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.security.certificatevalidation.ValidationMode, com.aspose.ms.System.Enum, com.aspose.pdf.security.certificatevalidation.ValidationMode

```
public final class ValidationMode extends com.aspose.ms.System.Enum
```

Menentukan mode validasi untuk proses validasi tanda tangan PDF.

## Fields

| Field | Deskripsi |
| --- | --- |
| [None](#None) | Mewakili mode di mana validasi tidak dilakukan. |
| [OnlyCheck](#OnlyCheck) | Mewakili mode di mana validasi dilakukan, tetapi hasilnya tidak memengaruhi validasi tanda tangan digital. Anda dapat memeriksa hasil validasi sendiri. |
| [Strict](#Strict) | Mewakili mode di mana validasi dilakukan dan hasilnya memengaruhi validasi tanda tangan digital. Jika sertifikat tidak dapat diverifikasi, maka tanda tangan digital akan dianggap tidak valid. Anda dapat memeriksa hasil validasi sendiri. |

### None {#None}
```
public static final int None
```

Mewakili mode di mana validasi tidak dilakukan.

### OnlyCheck {#OnlyCheck}
```
public static final int OnlyCheck
```

Mewakili mode di mana validasi dilakukan, tetapi hasilnya tidak memengaruhi validasi tanda tangan digital. Anda dapat memeriksa hasil validasi sendiri.

### Strict {#Strict}
```
public static final int Strict
```

Mewakili mode di mana validasi dilakukan dan hasilnya memengaruhi validasi tanda tangan digital. Jika sertifikat tidak dapat diverifikasi, maka tanda tangan digital akan dianggap tidak valid. Anda dapat memeriksa hasil validasi sendiri.
