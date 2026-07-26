---
title: "Id"
linktitle: "Id"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili struktur pengenal file. </p> <hr> <pre> Document doc = new Document(\\\"example.pdf\\\"); String original = doc.getId().getOriginal(); String modified =."
type: docs
weight: 2220
url: /id/java/com.aspose.pdf/id/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Id

```
public class Id extends Object
```

<p> Mewakili struktur pengidentifikasi file. </p> <hr> <pre> Document doc = new Document(\"example.pdf\"); String original = doc.getId().getOriginal(); String modified = doc.getId().getModified(); </pre>

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getModified](#getModified--) | Mengubah pengenal berdasarkan isi dokumen pada saat terakhir kali diperbarui. |
| [getOriginal](#getOriginal--) | Pengenal permanen berdasarkan isi dokumen pada saat pertama kali dibuat. |

### getModified {#getModified--}
```
public String getModified()
```

Mengubah pengenal berdasarkan isi dokumen pada saat terakhir kali diperbarui.

**Returns:**
nilai String

### getOriginal {#getOriginal--}
```
public String getOriginal()
```

Pengenal permanen berdasarkan isi dokumen pada saat pertama kali dibuat.

**Returns:**
nilai String
