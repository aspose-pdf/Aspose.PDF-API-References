---
title: "LightweightOperatorCollection"
linktitle: "LightweightOperatorCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Lättviktig operator-samling. Avsedd att användas i scenarier när underliggande innehållsström inte är bifogad, där endast en operator-samling krävs som resultat."
type: docs
weight: 2700
url: /sv/java/com.aspose.pdf/lightweightoperatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.LightweightOperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.LightweightOperatorCollection

**All Implemented Interfaces:**
Iterable < Operator >

```
public class LightweightOperatorCollection extends BaseOperatorCollection
```

Lättviktig operator-samling. Avsedd att användas i scenarier när underliggande innehållsström inte är bifogad, där endast en operator-samling krävs som resultat.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [LightweightOperatorCollection](#LightweightOperatorCollection--) | Initiera objekt |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-) | Initiera objekt |
| [LightweightOperatorCollection](#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-) | Initiera objekt |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.Operator-) | Lägg till operator |
| [addRange](#addRange-com.aspose.pdf.LightweightOperatorCollection-) | Lägg till LightweightOperatorCollection |
| [cancelUpdate](#cancelUpdate--) | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering. |
| [clear](#clear--) | Rensar samlingen. |
| [contains](#contains-com.aspose.pdf.Operator-) | Kontrollera om objektet finns i samlingen. |
| [deleteUnrestricted](#deleteUnrestricted-int-) | intern radera Unrestrictedelement |
| [get_Item](#get_Item-int-) | <p> Hämtar operatorn efter dess index. </p> <hr> <pre> Exempel visar hur man hämtar operatorn för sidinnehåll efter index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | För internt bruk getUnrestricted-operator |
| [insert](#insert-int-com.aspose.pdf.Operator-) | Infoga operator |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indikerar om samlingen är begränsad till snabb textutvinning |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [iterator](#iterator--) | Returnera iterator |
| [remove](#remove-com.aspose.pdf.Operator-) | Tar bort operator från samlingen. |
| [resumeUpdate](#resumeUpdate--) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Ställer in operatorn efter dess index. <hr> <pre> Exempel visar hur man hämtar operatorn för sidinnehåll efter index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [size](#size--) | Antal operatorer |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| [toList](#toList--) | Returnerar operatorlista. |
| [updateData](#updateData--) | intern |

### LightweightOperatorCollection {#LightweightOperatorCollection--}
```
public LightweightOperatorCollection()
```

Initiera objekt

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.engine.data.ITrailerable-com.aspose.ms.System.Collections.Generic.List-}
Initiera objekt

### LightweightOperatorCollection {#LightweightOperatorCollection-com.aspose.pdf.OperatorCollection-}
Initiera objekt

### add {#add-com.aspose.pdf.Operator-}
Lägg till operator

### addRange {#addRange-com.aspose.pdf.LightweightOperatorCollection-}
Lägg till LightweightOperatorCollection

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering.

### clear {#clear--}
```
public void clear()
```

Rensar samlingen.

### contains {#contains-com.aspose.pdf.Operator-}
Kontrollera om objektet finns i samlingen.

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

intern radera Unrestrictedelement

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Hämtar operatorn efter dess index. </p> <hr> <pre> Exempel visar hur man hämtar operatorn för sidinnehåll efter index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för operator. Numreringen börjar från 1. |

**Returns:**
Operator från begärt index

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

För internt bruk getUnrestricted-operator

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

**Returns:**
Operatorobjekt

### insert {#insert-int-com.aspose.pdf.Operator-}
Infoga operator

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Indikerar om samlingen är begränsad till snabb textutvinning

**Returns:**
booleskt värde

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar ett värde som indikerar om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public Iterator < Operator > iterator()
```

Returnera iterator

**Returns:**
{@code IGenericEnumerator<Operator>} objekt

### remove {#remove-com.aspose.pdf.Operator-}
Tar bort operator från samlingen.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar.

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Ställer in operatorn efter dess index. <hr> <pre> Exempel visar hur man hämtar operatorn för sidinnehåll efter index. Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get_Item(1).getContents(); Operator first = oc.get_Item(1); </pre>

### size {#size--}
```
public int size()
```

Antal operatorer

**Returns:**
int‑värde

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Returnerar operatorlista.

**Returns:**
operatorlista.

### updateData {#updateData--}
```
public void updateData()
```

intern
