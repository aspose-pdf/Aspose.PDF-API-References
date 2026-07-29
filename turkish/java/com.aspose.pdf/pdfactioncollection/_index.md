---
title: "PdfActionCollection"
linktitle: "PdfActionCollection"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf eylemlerin listesini tanımlar."
type: docs
weight: 3680
url: /tr/java/com.aspose.pdf/pdfactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfActionCollection

**All Implemented Interfaces:**
Iterable < PdfAction >

```
public class PdfActionCollection extends Object implements Iterable < PdfAction >
```

Sınıf eylemlerin listesini tanımlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [add](#add-com.aspose.pdf.PdfAction-) | Eylemi eylem listesine ekle. |
| [delete](#delete-int-) | Eylemi indeksle kaldır. |
| [get_Item](#get_Item-int-) | Eylemi indeksine göre alır. |
| [getCount](#getCount--) | Eylemlerin sayısını alır. |
| [iterator_Rename_Namesake](#iterator_Rename_Namesake--) | Dahili yöntem |
| [iterator](#iterator--) | Yineleyiciyi alır. |

### add {#add-com.aspose.pdf.PdfAction-}
Eylemi eylem listesine ekle.

### delete {#delete-int-}
```
public void delete(int index)
```

Eylemi indeksle kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak eylemin indeksi. |

### get_Item {#get_Item-int-}
```
public PdfAction get_Item(int index)
```

Eylemi indeksine göre alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Eylem indeks değeri. |

**Returns:**
PdfAction indeksi bulunursa; aksi takdirde @throws IndexOutOfRangeException IndexOutOfRangeException fırlatır.

### getCount {#getCount--}
```
public int getCount()
```

Eylemlerin sayısını alır.

**Returns:**
int değer

### iterator_Rename_Namesake {#iterator_Rename_Namesake--}
```
public com.aspose.ms.System.Collections.IEnumerator< PdfAction > iterator_Rename_Namesake()
```

Dahili yöntem

**Returns:**
dahili nesne.

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< PdfAction > iterator()
```

Yineleyiciyi alır.

**Returns:**
PDfAction yineleyicisi.
