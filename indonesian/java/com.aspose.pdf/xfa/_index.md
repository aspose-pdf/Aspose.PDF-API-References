---
title: "XFA"
linktitle: "XFA"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili formulir XML terkait XML Forms Architecture (XFA)."
type: docs
weight: 5550
url: /id/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Mewakili formulir XML terkait XML Forms Architecture (XFA).

## Metode

| Metode | Deskripsi |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Tambahkan nilai XML ke node templat yang cocok dengan ekspresi XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | Mulai mode pembaruan cache. Semua perubahan yang dibuat pada XFA akan di-cache dan disimpan ke dalam struktur dokumen pada pemanggilan EndCachedUpdates. Ini memungkinkan meningkatkan kinerja dengan menghindari operasi berulang saat menyimpan paket XML ke dokumen ketika banyak perubahan pada XFA dilakukan. |
| [endCachedUpdates](#endCachedUpdates--) | Mengakhiri pembaruan cache dan menyimpan semua data ke dalam struktur dokumen. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Ratakan bidang formulir XFA. |
| [get_Item](#get_Item-java.lang.String-) | Mendapatkan nilai node data sesuai {@code path}. |
| [getConfig](#getConfig--) | Komponen XFA Config dari formulir XFA. |
| [getDatasets](#getDatasets--) | Komponen XFA Datasets dari formulir XFA. |
| [getFieldNames](#getFieldNames--) | Daftar nama bidang dalam templat formulir. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Mengembalikan peta dengan nama bidang singkat dan nilai stringnya untuk semua bidang. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Mengembalikan node XML dari templat bidang XFA. |
| [getFieldTemplates](#getFieldTemplates--) | Mengembalikan daftar semua templat bidang pada formulir XFA. |
| [getForm](#getForm--) | Mendapatkan Komponen Formulir XFA dari formulir XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | Mendapatkan namespace untuk formulir XFA. Namespace berikut didefinisikan: "data" untuk data formulir dan "tpl" untuk templat formulir. |
| [getNamespaceManager](#getNamespaceManager--) | Mengembalikan manajer namespace dengan namespace yang digunakan untuk templat dan data. |
| [getTemplate](#getTemplate--) | Komponen XFA Template dari formulir XFA. |
| [getXDP](#getXDP--) | Paket Data XML (semua komponen formulir XFA dalam sebuah kontainer XML yang mengelilinginya). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Mendapatkan nilai node data sesuai {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Mengatur gambar untuk bidang XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Mencoba mengekspor skrip perhitungan dari formulir XFA. Jika tidak, mengembalikan string kosong; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Tambahkan nilai XML ke node templat yang cocok dengan ekspresi XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Mulai mode pembaruan cache. Semua perubahan yang dibuat pada XFA akan di-cache dan disimpan ke dalam struktur dokumen pada pemanggilan EndCachedUpdates. Ini memungkinkan meningkatkan kinerja dengan menghindari operasi berulang saat menyimpan paket XML ke dokumen ketika banyak perubahan pada XFA dilakukan.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Mengakhiri pembaruan cache dan menyimpan semua data ke dalam struktur dokumen.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Ratakan bidang formulir XFA.

### get_Item {#get_Item-java.lang.String-}
Mendapatkan nilai node data sesuai {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

Komponen XFA Config dari formulir XFA.

**Returns:**
Objek XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

Komponen XFA Datasets dari formulir XFA.

**Returns:**
Objek XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Daftar nama bidang dalam templat formulir.

**Returns:**
array nilai String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Mengembalikan peta dengan nama bidang singkat dan nilai stringnya untuk semua bidang. </p>

**Returns:**
objek {@code HashMap<String, String>}

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Mengembalikan node XML dari templat bidang XFA.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Mengembalikan daftar semua templat bidang pada formulir XFA.

**Returns:**
Daftar templat bidang.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Mendapatkan Komponen Formulir XFA dari formulir XFA.

**Returns:**
Objek XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Mendapatkan namespace untuk formulir XFA. Namespace berikut didefinisikan: "data" untuk data formulir dan "tpl" untuk templat formulir.

**Returns:**
Objek XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Mengembalikan manajer namespace dengan namespace yang digunakan untuk templat dan data.

**Returns:**
Objek XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

Komponen XFA Template dari formulir XFA.

**Returns:**
Objek XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

Paket Data XML (semua komponen formulir XFA dalam sebuah kontainer XML yang mengelilinginya).

**Returns:**
Objek XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Mendapatkan nilai node data sesuai {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Mengatur gambar untuk bidang XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Mencoba mengekspor skrip perhitungan dari formulir XFA. Jika tidak, mengembalikan string kosong;
