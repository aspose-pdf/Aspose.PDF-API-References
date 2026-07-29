---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Skema PDF/A ValueType diperlukan untuk semua tipe nilai properti yang tidak didefinisikan dalam spesifikasi XMP 2004, yaitu untuk tipe nilai di luar daftar berikut: -."
type: docs
weight: 5740
url: /id/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

Skema PDF/A ValueType diperlukan untuk semua tipe nilai properti yang tidak didefinisikan dalam spesifikasi XMP 2004, yaitu untuk tipe nilai di luar daftar berikut: - Tipe array (ini adalah tipe kontainer yang dapat berisi satu atau lebih bidang): Alt, Bag, Seq - Tipe nilai dasar: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - Tipe nilai Manajemen Media: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - Tipe nilai Job/Workflow dasar: Job - Tipe nilai skema EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Menginisialisasi objek baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | Tambahkan bidang baru. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | Menambahkan rentang bidang. |
| [clear](#clear--) | Menghapus semua bidang. |
| [getFields](#getFields--) | Mendapatkan daftar bidang. |
| [getNamespaceUri](#getNamespaceUri--) | Mendapatkan URI namespace. |
| [getPrefix](#getPrefix--) | Mendapatkan prefiks. |
| [getType](#getType--) | Mendapatkan tipe nilai. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | Mengembalikan daftar elemen xml yang mewakili bidang dalam pohon xml. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | Mengembalikan daftar elemen xml yang mewakili tipe nilai dalam pohon xml. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | Menghapus bidang dari daftar bidang. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Menginisialisasi objek baru.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
Tambahkan bidang baru.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
Menambahkan rentang bidang.

### clear {#clear--}
```
public void clear()
```

Menghapus semua bidang.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

Mendapatkan daftar bidang.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

Mendapatkan URI namespace.

**Returns:**
String

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

Mendapatkan prefiks.

**Returns:**
String

### getType {#getType--}
```
public String getType()
```

Mendapatkan tipe nilai.

**Returns:**
String

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
Mengembalikan daftar elemen xml yang mewakili bidang dalam pohon xml.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
Mengembalikan daftar elemen xml yang mewakili tipe nilai dalam pohon xml.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
Menghapus bidang dari daftar bidang.
