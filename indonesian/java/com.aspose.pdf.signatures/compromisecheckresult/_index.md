---
title: "CompromiseCheckResult"
linktitle: "CompromiseCheckResult"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk memeriksa tanda tangan digital dokumen terhadap kompromi."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.signatures/compromisecheckresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.signatures.CompromiseCheckResult

```
public final class CompromiseCheckResult extends Object
```

Mewakili kelas untuk memeriksa tanda tangan digital dokumen terhadap kompromi.

## Fields

| Field | Deskripsi |
| --- | --- |
| [CompromisedSignatures](#CompromisedSignatures) | Mendapatkan koleksi tanda tangan digital yang telah diidentifikasi sebagai terkompromi. Properti ini berisi daftar semua tanda tangan yang terkompromi yang terdeteksi dalam dokumen. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSignaturesCoverage](#getSignaturesCoverage--) | Mendapatkan status cakupan tanda tangan digital dalam sebuah dokumen. Jika sama dengan {@code SignaturesCoverage#Undefined}, maka salah satu tanda tangan terkompromi. |
| [hasCompromisedSignatures](#hasCompromisedSignatures--) | Menunjukkan apakah ada tanda tangan digital yang terkompromi dalam dokumen. Mengembalikan true jika setidaknya satu tanda tangan terkompromi; jika tidak, false. |

### CompromisedSignatures {#CompromisedSignatures}
```
public final List < SignatureName > CompromisedSignatures
```

Mendapatkan koleksi tanda tangan digital yang telah diidentifikasi sebagai terkompromi. Properti ini berisi daftar semua tanda tangan yang terkompromi yang terdeteksi dalam dokumen.

### getSignaturesCoverage {#getSignaturesCoverage--}
```
public final int getSignaturesCoverage()
```

Mendapatkan status cakupan tanda tangan digital dalam sebuah dokumen. Jika sama dengan {@code SignaturesCoverage#Undefined}, maka salah satu tanda tangan terkompromi.

**Returns:**
Elemen SignaturesCoverage

### hasCompromisedSignatures {#hasCompromisedSignatures--}
```
public final boolean hasCompromisedSignatures()
```

Menunjukkan apakah ada tanda tangan digital yang terkompromi dalam dokumen. Mengembalikan true jika setidaknya satu tanda tangan terkompromi; jika tidak, false.

**Returns:**
nilai boolean
