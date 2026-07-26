---
title: "TextExtractionOptions.TextFormattingMode"
linktitle: "TextExtractionOptions.TextFormattingMode"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mendefinisikan mode berbeda yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas {@code TextDevice}."
type: docs
weight: 5070
url: /id/java/com.aspose.pdf/textextractionoptions.textformattingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.TextExtractionOptions.TextFormattingMode, com.aspose.ms.System.Enum, com.aspose.pdf.TextExtractionOptions.TextFormattingMode

```
public static final class TextExtractionOptions.TextFormattingMode extends com.aspose.ms.System.Enum
```

Mendefinisikan mode berbeda yang dapat digunakan saat mengonversi dokumen pdf menjadi teks. Lihat kelas {@code TextDevice}.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Flatten](#Flatten) | Mewakili konten pdf dengan fragmen teks yang diposisikan berdasarkan koordinatnya. Pada dasarnya mirip dengan mode "Raw". Namun sementara "Raw" berfokus pada mempertahankan struktur fragmen teks (operator) dalam dokumen, "Flatten" berfokus pada menjaga teks dalam urutan yang dibaca. |
| [MemorySaving](#MemorySaving) | Ekstraksi dengan penghematan memori. Hampir sama dengan mode 'Raw' tetapi bekerja sedikit lebih cepat dan menggunakan lebih sedikit memori. |
| [Pure](#Pure) | Mewakili konten pdf dengan sedikit rutinitas pemformatan. |
| [Raw](#Raw) | Mewakili konten pdf apa adanya, yaitu tanpa pemformatan. |

### Flatten {#Flatten}
```
public static final int Flatten
```

Mewakili konten pdf dengan fragmen teks yang diposisikan berdasarkan koordinatnya. Pada dasarnya mirip dengan mode "Raw". Namun sementara "Raw" berfokus pada mempertahankan struktur fragmen teks (operator) dalam dokumen, "Flatten" berfokus pada menjaga teks dalam urutan yang dibaca.

### MemorySaving {#MemorySaving}
```
public static final int MemorySaving
```

Ekstraksi dengan penghematan memori. Hampir sama dengan mode 'Raw' tetapi bekerja sedikit lebih cepat dan menggunakan lebih sedikit memori.

### Pure {#Pure}
```
public static final int Pure
```

Mewakili konten pdf dengan sedikit rutinitas pemformatan.

### Raw {#Raw}
```
public static final int Raw
```

Mewakili konten pdf apa adanya, yaitu tanpa pemformatan.
