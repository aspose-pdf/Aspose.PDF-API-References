---
title: "PdfFileSanitization"
linktitle: "PdfFileSanitization"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili API sanitasi dan pemulihan. Gunakan jika Anda tidak dapat membuat/membuka dokumen dengan cara lain."
type: docs
weight: 510
url: /id/java/com.aspose.pdf.facades/pdffilesanitization/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileSanitization, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileSanitization

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileSanitization extends SaveableFacade implements com.aspose.pdf.engine.security.impl.signatures.sanitization.IRecovery
```

Mewakili API sanitasi dan pemulihan. Gunakan jika Anda tidak dapat membuat/membuka dokumen dengan cara lain.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfFileSanitization](#PdfFileSanitization--) | Menginisialisasi sebuah instance baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Mengikat aliran Pdf untuk Sanitasi. |
| [bindPdf](#bindPdf-java.lang.String-) | Mengikat file Pdf untuk Sanitasi. |
| [close](#close--) | Menutup facade. |
| [getLog](#getLog--) | Setelah file disimpan, Anda dapat memeriksa apa yang telah dilakukan pada file. |
| [getUseRebuildXrefAndTrailer](#getUseRebuildXrefAndTrailer--) | Memungkinkan untuk menghasilkan xref dan trailer baru untuk dokumen. |
| [getUseTrimBottom](#getUseTrimBottom--) | Memungkinkan untuk menghapus data setelah data pdf |
| [getUseTrimTop](#getUseTrimTop--) | Memungkinkan untuk menghapus data sebelum data pdf. |
| [rebuildXrefAndTrailer](#rebuildXrefAndTrailer--) | Menghapus xref lama dengan trailer dan membuat xref baru dengan trailer. |
| [recover](#recover--) | Memulihkan dokumen. Gunakan properti untuk menyesuaikan. |
| [save](#save-java.io.OutputStream-) | Menyimpan PDF hasil ke stream. |
| [save](#save-java.lang.String-) | Menyimpan PDF hasil ke file. |
| [setUseRebuildXrefAndTrailer](#setUseRebuildXrefAndTrailer-boolean-) | Memungkinkan untuk menghasilkan xref dan trailer baru untuk dokumen. |
| [setUseTrimBottom](#setUseTrimBottom-boolean-) | Memungkinkan untuk menghapus data setelah data pdf |
| [setUseTrimTop](#setUseTrimTop-boolean-) | Memungkinkan untuk menghapus data sebelum data pdf. |
| [trimBottom](#trimBottom--) | Menghapus data setelah %%EOF terakhir. |
| [trimTop](#trimTop--) | Menghapus data sebelum %PDF. |

### PdfFileSanitization {#PdfFileSanitization--}
```
public PdfFileSanitization()
```

Menginisialisasi sebuah instance baru.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Mengikat aliran Pdf untuk Sanitasi.

### bindPdf {#bindPdf-java.lang.String-}
Mengikat file Pdf untuk Sanitasi.

### close {#close--}
```
public void close()
```

Menutup facade.

### getLog {#getLog--}
```
public final List < String > getLog()
```

Setelah file disimpan, Anda dapat memeriksa apa yang telah dilakukan pada file.

**Returns:**
daftar elemen String

### getUseRebuildXrefAndTrailer {#getUseRebuildXrefAndTrailer--}
```
public final boolean getUseRebuildXrefAndTrailer()
```

Memungkinkan untuk menghasilkan xref dan trailer baru untuk dokumen.

**Returns:**
nilai boolean

### getUseTrimBottom {#getUseTrimBottom--}
```
public final boolean getUseTrimBottom()
```

Memungkinkan untuk menghapus data setelah data pdf

**Returns:**
nilai boolean

### getUseTrimTop {#getUseTrimTop--}
```
public final boolean getUseTrimTop()
```

Memungkinkan untuk menghapus data sebelum data pdf.

**Returns:**
nilai boolean

### rebuildXrefAndTrailer {#rebuildXrefAndTrailer--}
```
public final void rebuildXrefAndTrailer()
```

Menghapus xref lama dengan trailer dan membuat xref baru dengan trailer.

### recover {#recover--}
```
public final void recover()
```

Memulihkan dokumen. Gunakan properti untuk menyesuaikan.

### save {#save-java.io.OutputStream-}
Menyimpan PDF hasil ke stream.

### save {#save-java.lang.String-}
Menyimpan PDF hasil ke file.

### setUseRebuildXrefAndTrailer {#setUseRebuildXrefAndTrailer-boolean-}
```
public final void setUseRebuildXrefAndTrailer(boolean value)
```

Memungkinkan untuk menghasilkan xref dan trailer baru untuk dokumen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseTrimBottom {#setUseTrimBottom-boolean-}
```
public final void setUseTrimBottom(boolean value)
```

Memungkinkan untuk menghapus data setelah data pdf

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setUseTrimTop {#setUseTrimTop-boolean-}
```
public final void setUseTrimTop(boolean value)
```

Memungkinkan untuk menghapus data sebelum data pdf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### trimBottom {#trimBottom--}
```
public final void trimBottom()
```

Menghapus data setelah %%EOF terakhir.

### trimTop {#trimTop--}
```
public final void trimTop()
```

Menghapus data sebelum %PDF.
