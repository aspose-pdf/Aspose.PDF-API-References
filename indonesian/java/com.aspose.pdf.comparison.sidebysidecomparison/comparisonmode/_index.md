---
title: "ComparisonMode"
linktitle: "ComparisonMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Enumerasi mode perbandingan."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.comparison.sidebysidecomparison/comparisonmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode, com.aspose.ms.System.Enum, com.aspose.pdf.comparison.sidebysidecomparison.ComparisonMode

```
public final class ComparisonMode extends com.aspose.ms.System.Enum
```

Enumerasi mode perbandingan.

## Fields

| Field | Deskripsi |
| --- | --- |
| [IgnoreSpaces](#IgnoreSpaces) | Semua spasi diabaikan. Perubahan hanya dicari dalam kata. |
| [Normal](#Normal) | Mode normal. Hanya spasi dalam fragmen teks yang diperhitungkan (tergantung pada cara dokumen dihasilkan.) |
| [ParseSpaces](#ParseSpaces) | Mode ini mirip dengan mode normal, tetapi berusaha memperhitungkan jarak visual antar fragmen teks berdasarkan jarak. Mengenali jumlah spasi antar fragmen mungkin tidak akurat karena sangat bergantung pada cara dokumen dihasilkan. Jika dokumen dibuat oleh generator yang berbeda, mungkin terjadi ketidakakuratan dalam membandingkan spasi antar fragmen teks. Opsi ini dapat menghasilkan hasil yang, meskipun logis, berbeda dari hasil perbandingan yang diharapkan ketika diterapkan pada dokumen dengan struktur yang kompleks. |

### IgnoreSpaces {#IgnoreSpaces}
```
public static final int IgnoreSpaces
```

Semua spasi diabaikan. Perubahan hanya dicari dalam kata.

### Normal {#Normal}
```
public static final int Normal
```

Mode normal. Hanya spasi dalam fragmen teks yang diperhitungkan (tergantung pada cara dokumen dihasilkan.)

### ParseSpaces {#ParseSpaces}
```
public static final int ParseSpaces
```

Mode ini mirip dengan mode normal, tetapi berusaha memperhitungkan jarak visual antar fragmen teks berdasarkan jarak. Mengenali jumlah spasi antar fragmen mungkin tidak akurat karena sangat bergantung pada cara dokumen dihasilkan. Jika dokumen dibuat oleh generator yang berbeda, mungkin terjadi ketidakakuratan dalam membandingkan spasi antar fragmen teks. Opsi ini dapat menghasilkan hasil yang, meskipun logis, berbeda dari hasil perbandingan yang diharapkan ketika diterapkan pada dokumen dengan struktur yang kompleks.
