---
title: "OutlineItemCollection"
linktitle: "OutlineItemCollection"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar dispositionspost i dispositionshierarkin för PDF‑dokumentet."
type: docs
weight: 3270
url: /sv/java/com.aspose.pdf/outlineitemcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Outlines com.aspose.pdf.OutlineItemCollection, com.aspose.pdf.Outlines, com.aspose.pdf.OutlineItemCollection

**All Implemented Interfaces:**
Iterable < OutlineItemCollection >

```
public final class OutlineItemCollection extends Outlines
```

Representerar dispositionspost i dispositionshierarkin för PDF‑dokumentet.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-) | Initierar en ny instans av den här klassen med hjälp av ett internt motor‑outline‑postobjekt. |
| [OutlineItemCollection](#OutlineItemCollection-com.aspose.pdf.OutlineCollection-) | Initierar outline‑objektinstans med rot‑hierarkiobjekt. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [add](#add-com.aspose.pdf.OutlineItemCollection-) | Lägger till ett outline-objekt i samlingen. |
| [clear](#clear--) | Rensar alla objekt från samlingen. |
| [contains](#contains-com.aspose.pdf.OutlineItemCollection-) | Stöds ännu inte. Kastar alltid NotImplementedException. |
| [copyTo](#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-) | Kopierar outline‑poster till en System.Array, med start vid ett specifikt System.Array‑index. |
| [delete](#delete--) | Tar bort detta outline‑objekt från dokumentets outline‑hierarki. |
| [delete](#delete-java.lang.String-) | Tar bort detta outline‑objekt från dokumentets outline‑hierarki. |
| [get_Item](#get_Item-int-) | Hämtar outline‑objekt från samlingen med hjälp av index. |
| [getAction](#getAction--) | Hämtar åtgärden för detta outline‑objekt. |
| [getBold](#getBold--) | Hämtar fetstil‑flagga för titeltexten i detta outline‑objekt. |
| [getColor](#getColor--) | Hämtar färgen för titeltexten i detta outline‑objekt. |
| [getDestination](#getDestination--) | Hämtar destinationen för detta outline‑objekt. |
| [getEngineDict](#getEngineDict--) | Endast intern |
| [getEngineObj](#getEngineObj--) | Endast intern |
| [getFirst](#getFirst--) | Hämtar outline‑objektet som representerar det första top‑nivå‑objektet i outline‑hierarkin. |
| [getItalic](#getItalic--) | Hämtar kursiv‑flagga för titeltexten i detta outline‑objekt. |
| [getLast](#getLast--) | Hämtar outline‑objektet som representerar det sista top‑nivå‑objektet i outline‑hierarkin. |
| [getLevel](#getLevel--) | Hämtar hierarkinivå för outline‑objektet. |
| [getNext](#getNext--) | Hämtar outline‑objektet som representerar nästa objekt relativt detta objekt i outline‑hierarkin. |
| [getOpen](#getOpen--) | Hämta öppet‑status (true/false) för outline‑objekt. |
| [getParent](#getParent--) | Hämtar föräldraobjektet för detta outline‑objekt i outline‑hierarkin. |
| [getPrev](#getPrev--) | Hämtar outline‑objektet som representerar föregående objekt relativt detta objekt i outline‑hierarkin. |
| [getSyncRoot](#getSyncRoot--) | Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling. |
| [getTitle](#getTitle--) | Hämtar titeln för detta dispositionselement. |
| [getVisibleCount](#getVisibleCount--) | Hämtar det totala antalet dispositionselement på alla nivåer i dokumentets dispositionshierarki. |
| [hasNext](#hasNext--) | Kontrollera om dispositionselementet som representerar nästa element relativt detta element i dispositionshierarkin. |
| [insert](#insert-int-com.aspose.pdf.OutlineItemCollection-) | Infogar dispositionselementet i samlingen på den angivna platsen. |
| [isReadOnly](#isReadOnly--) | Hämtar ett värde som indikerar om samlingen är skrivskyddad. |
| [isSynchronized](#isSynchronized--) | Hämtar värdet som indikerar om åtkomst till denna samling är synkroniserad (trådsäker). |
| [iterator](#iterator--) | Returnerar en enumerator som itererar genom samlingen. |
| [next](#next--) |  |
| [remove](#remove-int-) | Ta bort objekt efter index. |
| [remove](#remove-com.aspose.pdf.OutlineItemCollection-) | Stöds ännu inte. Kastar alltid NotImplementedException. |
| [setAction](#setAction-com.aspose.pdf.PdfAction-) | Ställer in åtgärden för detta dispositionselement. |
| [setBold](#setBold-boolean-) | Ställer in fetstil‑flaggan för titeltexten för detta dispositionselement. |
| [setColor](#setColor-java.awt.Color-) | Ställer in färgen för titeltexten för detta dispositionselement. |
| [setDestination](#setDestination-com.aspose.pdf.IAppointment-) | Ställer in destinationen för detta dispositionselement. |
| [setItalic](#setItalic-boolean-) | Ställer in kursiv‑flaggan för titeltexten för detta dispositionselement. |
| [setOpen](#setOpen-boolean-) | Ställer in öppet‑status (true/false) för dispositionselementet. |
| [setTitle](#setTitle-java.lang.String-) | Ställer in titeln för detta dispositionselement. |
| [size](#size--) | Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount ger antalet synliga dispositionselement på alla nivåer. |

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.engine.data.IPdfObject-}
Initierar en ny instans av den här klassen med hjälp av ett internt motor‑outline‑postobjekt.

### OutlineItemCollection {#OutlineItemCollection-com.aspose.pdf.OutlineCollection-}
Initierar outline‑objektinstans med rot‑hierarkiobjekt.

### add {#add-com.aspose.pdf.OutlineItemCollection-}
Lägger till ett outline-objekt i samlingen.

### clear {#clear--}
```
public void clear()
```

Rensar alla objekt från samlingen.

### contains {#contains-com.aspose.pdf.OutlineItemCollection-}
Stöds ännu inte. Kastar alltid NotImplementedException.

### copyTo {#copyTo-com.aspose.pdf.OutlineItemCollection:A-int-}
Kopierar outline‑poster till en System.Array, med start vid ett specifikt System.Array‑index.

### delete {#delete--}
```
public void delete()
```

Tar bort detta outline‑objekt från dokumentets outline‑hierarki.

### delete {#delete-java.lang.String-}
Tar bort detta outline‑objekt från dokumentets outline‑hierarki.

### get_Item {#get_Item-int-}
```
public OutlineItemCollection get_Item(int index)
```

Hämtar outline‑objekt från samlingen med hjälp av index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index inom samlingen. |

**Returns:**
OutlineItemCollection‑objekt.

### getAction {#getAction--}
```
public PdfAction getAction()
```

Hämtar åtgärden för detta outline‑objekt.

**Returns:**
PdfAction‑värde

### getBold {#getBold--}
```
public boolean getBold()
```

Hämtar fetstil‑flagga för titeltexten i detta outline‑objekt.

**Returns:**
booleskt värde

### getColor {#getColor--}
```
public Color getColor()
```

Hämtar färgen för titeltexten i detta outline‑objekt.

**Returns:**
Färgvärde

### getDestination {#getDestination--}
```
public IAppointment getDestination()
```

Hämtar destinationen för detta outline‑objekt.

**Returns:**
IAppointment-värde

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

Endast intern

**Returns:**
IPdfDictionary‑objekt

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

Endast intern

**Returns:**
IPdfObject‑objekt

### getFirst {#getFirst--}
```
public OutlineItemCollection getFirst()
```

Hämtar outline‑objektet som representerar det första top‑nivå‑objektet i outline‑hierarkin.

**Returns:**
OutlineItemCollection‑värde

### getItalic {#getItalic--}
```
public boolean getItalic()
```

Hämtar kursiv‑flagga för titeltexten i detta outline‑objekt.

**Returns:**
booleskt värde

### getLast {#getLast--}
```
public OutlineItemCollection getLast()
```

Hämtar outline‑objektet som representerar det sista top‑nivå‑objektet i outline‑hierarkin.

**Returns:**
OutlineItemCollection‑värde

### getLevel {#getLevel--}
```
public int getLevel()
```

Hämtar hierarkinivå för outline‑objektet.

**Returns:**
int‑värde

### getNext {#getNext--}
```
public OutlineItemCollection getNext()
```

Hämtar outline‑objektet som representerar nästa objekt relativt detta objekt i outline‑hierarkin.

**Returns:**
OutlineItemCollection‑värde

### getOpen {#getOpen--}
```
public boolean getOpen()
```

Hämta öppet‑status (true/false) för outline‑objekt.

**Returns:**
booleskt värde

### getParent {#getParent--}
```
public Outlines getParent()
```

Hämtar föräldraobjektet för detta outline‑objekt i outline‑hierarkin.

**Returns:**
Objektvärde

### getPrev {#getPrev--}
```
public OutlineItemCollection getPrev()
```

Hämtar outline‑objektet som representerar föregående objekt relativt detta objekt i outline‑hierarkin.

**Returns:**
OutlineItemCollection‑värde

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Hämtar objektet som kan användas för att synkronisera åtkomst till denna samling.

**Returns:**
Objektvärde

### getTitle {#getTitle--}
```
public String getTitle()
```

Hämtar titeln för detta dispositionselement.

**Returns:**
String värde

### getVisibleCount {#getVisibleCount--}
```
public int getVisibleCount()
```

Hämtar det totala antalet dispositionselement på alla nivåer i dokumentets dispositionshierarki.

**Returns:**
int‑värde

### hasNext {#hasNext--}
```
public final boolean hasNext()
```

Kontrollera om dispositionselementet som representerar nästa element relativt detta element i dispositionshierarkin.

**Returns:**
booleskt värde

### insert {#insert-int-com.aspose.pdf.OutlineItemCollection-}
Infogar dispositionselementet i samlingen på den angivna platsen.

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Hämtar ett värde som indikerar om samlingen är skrivskyddad.

**Returns:**
booleskt värde

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Hämtar värdet som indikerar om åtkomst till denna samling är synkroniserad (trådsäker).

**Returns:**
booleskt värde

### iterator {#iterator--}
```
public Iterator < OutlineItemCollection > iterator()
```

Returnerar en enumerator som itererar genom samlingen.

**Returns:**
Ett System.Collections.IEnumerator‑objekt som kan användas för att iterera genom samlingen.

### next {#next--}
```
public OutlineItemCollection next()
```



### remove {#remove-int-}
```
public final void remove(int index)
```

Ta bort objekt efter index.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index |  | Index för objektet som ska tas bort. |

### remove {#remove-com.aspose.pdf.OutlineItemCollection-}
Stöds ännu inte. Kastar alltid NotImplementedException.

### setAction {#setAction-com.aspose.pdf.PdfAction-}
Ställer in åtgärden för detta dispositionselement.

### setBold {#setBold-boolean-}
```
public void setBold(boolean value)
```

Ställer in fetstil‑flaggan för titeltexten för detta dispositionselement.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setColor {#setColor-java.awt.Color-}
Ställer in färgen för titeltexten för detta dispositionselement.

### setDestination {#setDestination-com.aspose.pdf.IAppointment-}
Ställer in destinationen för detta dispositionselement.

### setItalic {#setItalic-boolean-}
```
public void setItalic(boolean value)
```

Ställer in kursiv‑flaggan för titeltexten för detta dispositionselement.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

Ställer in öppet‑status (true/false) för dispositionselementet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setTitle {#setTitle-java.lang.String-}
Ställer in titeln för detta dispositionselement.

### size {#size--}
```
public int size()
```

Antal objekt i samlingen. Vänligen förväxla inte med VisibleCount: VisibleCount ger antalet synliga dispositionselement på alla nivåer.

**Returns:**
int‑värde
