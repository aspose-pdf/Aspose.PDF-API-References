---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Klassen representerar en samling av operatörer"
type: docs
weight: 3190
url: /sv/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Klassen representerar en samling av operatörer

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Endast för internt bruk! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Endast för internt bruk! |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepterar IOperatorSelector‑besökareobjekt för att bearbeta operatorer. |
| [add](#add-java.lang.Iterable-) | Lägger till alla operatorer från en annan samling i samlingen. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Lägger till en ny operator i samlingen. </p> <hr> <p> Exempel visar hur man lägger till operatorer i slutet av page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Lägg till operatorer i slutet av innehållsoperatorerna. </p> <hr> <p> Exemplet visar hur man lägger till en operator i slutet av sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering. |
| [clear](#clear--) | <p> Tar bort alla operatorer från listan. </p> <hr> <p> Exemplet visar hur man rensar sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Utför programdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [contains](#contains-com.aspose.pdf.Operator-) | Returnerar true om samlingen innehåller den angivna operatorn. |
| [delete](#delete-int-) | <p> Tar bort en operator från samlingen. </p> <hr> <p> Exemplet visar hur man tar bort en operator med dess index. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Tar bort operatorer från samlingen. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Tar bort operatorer från samlingen. </p> <hr> <p> Exemplet visar hur man tar bort en operator från sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | intern obegränsad version av Delete(index) |
| [dispose](#dispose--) | Utför programdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [get_Item](#get_Item-int-) | <p> Hämtar operatorn med dess index. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Intern obegränsad version av indexeraren |
| [insert](#insert-int-java.lang.Iterable-) | Infoga operatorer på den angivna positionen. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Infogar en operator i samlingen. </p> <hr> <p> Exemplet visar hur man infogar en operator i sidans innehåll. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Infoga operatorer på den angivna positionen. </p> <hr> <p> Exemplet visar hur man infogar en operator i sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Hämtar hakparentesstatus för operatorsekvensen, dvs. om dessa operatorer är inom q‑Q‑block. |
| [isCommandsParsed](#isCommandsParsed--) | Hämtar analyserade kommandon |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Indikerar om samlingen är begränsad till snabb textutvinning |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [iterator](#iterator--) | Returnerar en enumerator för samlingen |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Hämta antalet operatorer som beskriver innehållet för sidan utan att initiera dem. |
| [remove](#remove-com.aspose.pdf.Operator-) | Ta bort en operator från samlingen. |
| [replace](#replace-java.lang.Iterable-) | Ersätt operatorer i samlingen med andra operatorer. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Ersätt operatorer i samlingen med andra operatorer. |
| [resumeUpdate](#resumeUpdate--) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. |
| [resumeUpdate](#resumeUpdate-boolean-) | Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. Markerar alla operatorer som \"changed\" om invalidate‑parametern är true. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Ställer in operatorn med dess index. |
| [size](#size--) | Hämtar antalet operatorer i samlingen. |
| [suppressUpdate](#suppressUpdate--) | Undertrycker uppdatering av innehållsdata. Innehållsströmmen uppdateras inte förrän ResumeUpdate anropas. |
| [toList](#toList--) | Returnerar operatorlista. |
| [toString](#toString--) | Returnerar textrepresentation av operatorn. |
| [updateData](#updateData--) | Uppdatera objektström. |
| [updateNormalizedData](#updateNormalizedData--) | Uppdatera objektström med korrigering av saknade GSave/GRestore-operatorer. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Endast för internt bruk!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Endast för internt bruk!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepterar IOperatorSelector‑besökareobjekt för att bearbeta operatorer.

### add {#add-java.lang.Iterable-}
Lägger till alla operatorer från en annan samling i samlingen.

### add {#add-com.aspose.pdf.Operator-}
<p> Lägger till en ny operator i samlingen. </p> <hr> <p> Exempel visar hur man lägger till operatorer i slutet av page.contents. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Lägg till operatorer i slutet av innehållsoperatorerna. </p> <hr> <p> Exemplet visar hur man lägger till en operator i slutet av sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Avbryter den senaste uppdateringen. Denna metod kan anropas när ändringen inte ska trigga en innehållsuppdatering.

### clear {#clear--}
```
public void clear()
```

<p> Tar bort alla operatorer från listan. </p> <hr> <p> Exemplet visar hur man rensar sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Utför programdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser.

### contains {#contains-com.aspose.pdf.Operator-}
Returnerar true om samlingen innehåller den angivna operatorn.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Tar bort en operator från samlingen. </p> <hr> <p> Exemplet visar hur man tar bort en operator med dess index. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för operator som måste tas bort. Operatorernas numrering börjar från 1. |

### delete {#delete-java.lang.Iterable-}
Tar bort operatorer från samlingen.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Tar bort operatorer från samlingen. </p> <hr> <p> Exemplet visar hur man tar bort en operator från sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

intern obegränsad version av Delete(index)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

### dispose {#dispose--}
```
public final void dispose()
```

Utför programdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Hämtar operatorn med dess index. </p> <hr> Example demonstrates how to get operator of page contents by index. <pre> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

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

Intern obegränsad version av indexeraren

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | int‑värde |

**Returns:**
Operatorobjekt

### insert {#insert-int-java.lang.Iterable-}
Infoga operatorer på den angivna positionen.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Infogar en operator i samlingen. </p> <hr> <p> Exemplet visar hur man infogar en operator i sidans innehåll. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Infoga operatorer på den angivna positionen. </p> <hr> <p> Exemplet visar hur man infogar en operator i sidans innehåll. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Hämtar hakparentesstatus för operatorsekvensen, dvs. om dessa operatorer är inom q‑Q‑block.

**Returns:**
booleskt värde

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Hämtar analyserade kommandon

**Returns:**
booleskt värde

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
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Returnerar en enumerator för samlingen

**Returns:**
Samlingsenumerator

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Hämta antalet operatorer som beskriver innehållet för sidan utan att initiera dem.

**Returns:**
int‑värde

### remove {#remove-com.aspose.pdf.Operator-}
Ta bort en operator från samlingen.

### replace {#replace-java.lang.Iterable-}
Ersätt operatorer i samlingen med andra operatorer.

### replace {#replace-com.aspose.pdf.Operator:A-}
Ersätt operatorer i samlingen med andra operatorer.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Återupptar dokumentuppdatering. Uppdaterar innehållsströmmen om det finns några väntande ändringar. Markerar alla operatorer som \"changed\" om invalidate‑parametern är true.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| updateAll |  | Om true, markeras alla operatorer i samlingen som uppdaterade. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Ställer in operatorn med dess index.

### size {#size--}
```
public int size()
```

Hämtar antalet operatorer i samlingen.

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

### toString {#toString--}
```
public String toString()
```

Returnerar textrepresentation av operatorn.

**Returns:**
Textrepresentation av operator.

### updateData {#updateData--}
```
public void updateData()
```

Uppdatera objektström.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Uppdatera objektström med korrigering av saknade GSave/GRestore-operatorer.
