---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang dirancang untuk mengekstrak konten RTF yang dialirkan sebagai sekumpulan token."
type: docs
weight: 40
url: /id/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Kelas yang dirancang untuk mengekstrak konten RTF yang dialirkan sebagai sekumpulan token.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [readNextToken](#readNextToken--) | Membaca aliran masukan dan mengembalikan token berikutnya. |
| [skip](#skip-int-) | Mengonsumsi dan membuang sejumlah karakter yang ditentukan dari aliran masukan. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Membaca aliran masukan dan mengembalikan token berikutnya.

### skip {#skip-int-}
```
public final void skip(int count)
```

Mengonsumsi dan membuang sejumlah karakter yang ditentukan dari aliran masukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| jumlah |  | Jumlah karakter yang akan dilewati. |
