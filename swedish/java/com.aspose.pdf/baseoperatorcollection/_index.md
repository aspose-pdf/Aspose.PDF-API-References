---
title: "BaseOperatorCollection"
linktitle: "BaseOperatorCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar basklass för operatörssamling."
type: docs
weight: 270
url: /sv/java/com.aspose.pdf/baseoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public abstract class BaseOperatorCollection extends Object implements Iterable < Operator >
```

Representerar basklass för operatörssamling.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [BaseOperatorCollection](#BaseOperatorCollection--) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Lägger till en ny operator i samlingen. |
| [cancelUpdate](#cancelUpdate--) | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering. |
| [clear](#clear--) | Rensar samlingen. |
| [contains](#contains-com.aspose.pdf.Operator-) | Kontrollera om objektet finns i samlingen. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | intern |
| [get_Item](#get_Item-int-) | Hämtar operatorn efter dess index. |
| [getUnrestricted](#getUnrestricted-int-) | Endast för internt bruk |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Infogar operator i samlingen. |
| [isEmpty](#isEmpty--) | Returnerar TRUE om samlingen är tom. |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indikerar om samlingen är begränsad till snabb textutvinning |
| [isReadOnly](#isReadOnly--) | Returnerar true om samlingen är skrivskyddad. |
| [iterator](#iterator--) | Returnerar en enumerator för samlingen |
| [remove](#remove-com.aspose.pdf.Operator-) | Tar bort operator från samlingen. |
| [resumeUpdate](#resumeUpdate--) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Ställer in operatorn med dess index. |
| [size](#size--) | Hämtar antalet operatorer i samlingen. |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| [toList](#toList--) | Returnerar opetator list. |
| [updateData](#updateData--) | intern |

### BaseOperatorCollection {#BaseOperatorCollection--}
```
public BaseOperatorCollection()
```



### add {#add-com.aspose.pdf.Operator-}
Lägger till en ny operator i samlingen.

### cancelUpdate {#cancelUpdate--}
```
public abstract void cancelUpdate()
```

Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering.

### clear {#clear--}
```
public abstract void clear()
```

Rensar samlingen.

### contains {#contains-com.aspose.pdf.Operator-}
Kontrollera om objektet finns i samlingen.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public abstract void deleteUnrestricted(int index)
```

intern

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

### get_Item {#get_Item-int-}
```
public abstract Operator get_Item(int index)
```

Hämtar operatorn efter dess index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för operator. Numreringen börjar från 1. |

**Returns:**
Operator från begärt index

### getUnrestricted {#getUnrestricted-int-}
```
public abstract Operator getUnrestricted(int index)
```

Endast för internt bruk

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

**Returns:**
Operatorobjekt

### insert {#insert-int-com.aspose.pdf.Operator-}
Infogar operator i samlingen.

### isEmpty {#isEmpty--}
```
public boolean isEmpty()
```

Returnerar TRUE om samlingen är tom.

**Returns:**
booleskt värde

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public abstract boolean isFastTextExtractionMode()
```

Indikerar om samlingen är begränsad till snabb textutvinning

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public abstract boolean isReadOnly()
```

Returnerar true om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public abstract Iterator < Operator > iterator()
```

Returnerar en enumerator för samlingen

**Returns:**
Samlingsenumerator

### remove {#remove-com.aspose.pdf.Operator-}
Tar bort operator från samlingen.

### resumeUpdate {#resumeUpdate--}
```
public abstract void resumeUpdate()
```

Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Ställer in operatorn med dess index.

### size {#size--}
```
public abstract int size()
```

Hämtar antalet operatorer i samlingen.

**Returns:**
heltalvärde

### suppressUpdate {#suppressUpdate--}
```
public abstract void suppressUpdate()
```

Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas.

### toList {#toList--}
```
public abstract com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Returnerar opetator list.

**Returns:**
opetator lista.

### updateData {#updateData--}
```
public abstract void updateData()
```

intern
