---
title: "OperatorCollection"
linktitle: "OperatorCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse stellt eine Sammlung von Operatoren dar"
type: docs
weight: 3190
url: /de/java/com.aspose.pdf/operatorcollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseOperatorCollection com.aspose.pdf.OperatorCollection, com.aspose.pdf.BaseOperatorCollection, com.aspose.pdf.OperatorCollection

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Iterable < Operator >

```
public class OperatorCollection extends BaseOperatorCollection implements com.aspose.ms.System.IDisposable
```

Klasse stellt eine Sammlung von Operatoren dar

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-) | Nur für den internen Gebrauch! |
| [OperatorCollection](#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-) | Nur für den internen Gebrauch! |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Akzeptiert ein IOperatorSelector-Besucherobjekt, um Operatoren zu verarbeiten. |
| [add](#add-java.lang.Iterable-) | Fügt der Sammlung alle Operatoren aus einer anderen Sammlung hinzu. |
| [add](#add-com.aspose.pdf.Operator-) | <p> Fügt einen neuen Operator zur Sammlung hinzu. </p> <hr> <p> Beispiel zeigt, wie Operatoren am Ende von page.contents hinzugefügt werden. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p> |
| [add](#add-com.aspose.pdf.Operator:A-) | <p> Fügt Operatoren am Ende der Inhaltsoperatoren hinzu. </p> <hr> <p> Beispiel zeigt, wie ein Operator am Ende des Seiteninhalts hinzugefügt wird. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [cancelUpdate](#cancelUpdate--) | Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll. |
| [clear](#clear--) | <p> Entfernt alle Operatoren aus der Liste. </p> <hr> <p> Beispiel zeigt, wie Seiteninhalte gelöscht werden. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p> |
| [close](#close--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [contains](#contains-com.aspose.pdf.Operator-) | Gibt true zurück, wenn die Sammlung den angegebenen Operator enthält. |
| [delete](#delete-int-) | <p> Löscht einen Operator aus der Sammlung. </p> <hr> <p> Beispiel zeigt, wie ein Operator anhand seines Index gelöscht wird. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p> |
| [delete](#delete-java.lang.Iterable-) | Löscht Operatoren aus der Sammlung. |
| [delete](#delete-com.aspose.pdf.Operator:A-) | <p> Löscht Operatoren aus der Sammlung. </p> <hr> <p> Beispiel zeigt, wie ein Operator aus den Seiteninhalten entfernt wird. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p> |
| [deleteUnrestricted](#deleteUnrestricted-int-) | interne uneingeschränkte Version von Delete(index) |
| [dispose](#dispose--) | Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind. |
| [get_Item](#get_Item-int-) | <p> Ruft einen Operator anhand seines Index ab. </p> <hr> Beispiel zeigt, wie ein Operator des Seiteninhalts anhand des Index abgerufen wird. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre> |
| [getUnrestricted](#getUnrestricted-int-) | Interne uneingeschränkte Version des Indexers |
| [insert](#insert-int-java.lang.Iterable-) | Operatoren an der angegebenen Position einfügen. |
| [insert](#insert-int-com.aspose.pdf.Operator-) | <p> Fügt einen Operator in die Sammlung ein. </p> <hr> <p> Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p> |
| [insert](#insert-int-com.aspose.pdf.Operator:A-) | <p> Operatoren an der angegebenen Position einfügen. </p> <hr> <p> Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p> |
| [isBracketed](#isBracketed--) | Ermittelt den geklammerten Status der Operatorsequenz, d.h. ob diese Operatoren innerhalb von q - Q Blöcken liegen. |
| [isCommandsParsed](#isCommandsParsed--) | Ermittelt die geparsten Befehle |
| [isFastTextExtractionMode](#isFastTextExtractionMode--) | Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist |
| [isReadOnly](#isReadOnly--) | Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist. |
| [iterator](#iterator--) | Gibt einen Enumerator für die Sammlung zurück |
| [precalculateOperatorsCount](#precalculateOperatorsCount--) | Ermittelt die Anzahl der Operatoren, die den Seiteninhalt beschreiben, ohne sie zu initialisieren. |
| [remove](#remove-com.aspose.pdf.Operator-) | Entfernt einen Operator aus der Sammlung. |
| [replace](#replace-java.lang.Iterable-) | Ersetzt Operatoren in der Sammlung durch andere Operatoren. |
| [replace](#replace-com.aspose.pdf.Operator:A-) | Ersetzt Operatoren in der Sammlung durch andere Operatoren. |
| [resumeUpdate](#resumeUpdate--) | Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind. |
| [resumeUpdate](#resumeUpdate-boolean-) | Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind. Markiert alle Operatoren als \"geändert\", wenn der Parameter invalidate true ist. |
| [set_Item](#set_Item-int-com.aspose.pdf.Operator-) | Setzt den Operator anhand seines Index. |
| [size](#size--) | Ermittelt die Anzahl der Operatoren in der Sammlung. |
| [suppressUpdate](#suppressUpdate--) | Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhaltsstream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird. |
| [toList](#toList--) | Gibt die Operatorliste zurück. |
| [toString](#toString--) | Gibt die Textdarstellung des Operators zurück. |
| [updateData](#updateData--) | Objektstream aktualisieren. |
| [updateNormalizedData](#updateNormalizedData--) | Objektstream aktualisieren und fehlende GSave/GRestore-Operatoren hinzufügen. |

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-}
Nur für den internen Gebrauch!

### OperatorCollection {#OperatorCollection-com.aspose.pdf.engine.data.IPdfPrimitive-com.aspose.pdf.engine.IOperatorContainer-}
Nur für den internen Gebrauch!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Akzeptiert ein IOperatorSelector-Besucherobjekt, um Operatoren zu verarbeiten.

### add {#add-java.lang.Iterable-}
Fügt der Sammlung alle Operatoren aus einer anderen Sammlung hinzu.

### add {#add-com.aspose.pdf.Operator-}
<p> Fügt einen neuen Operator zur Sammlung hinzu. </p> <hr> <p> Beispiel zeigt, wie Operatoren am Ende von page.contents hinzugefügt werden. <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.q()); doc.getPages().get(1).getContents().add(new com.aspose.pdf.operators.Q()); </p>

### add {#add-com.aspose.pdf.Operator:A-}
<p> Fügt Operatoren am Ende der Inhaltsoperatoren hinzu. </p> <hr> <p> Beispiel zeigt, wie ein Operator am Ende des Seiteninhalts hinzugefügt wird. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.add(new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### cancelUpdate {#cancelUpdate--}
```
public void cancelUpdate()
```

Bricht das letzte Update ab. Diese Methode kann aufgerufen werden, wenn die Änderung keine Inhaltsaktualisierung auslösen soll.

### clear {#clear--}
```
public void clear()
```

<p> Entfernt alle Operatoren aus der Liste. </p> <hr> <p> Beispiel zeigt, wie Seiteninhalte gelöscht werden. </p> <p> Document doc = new Document("input.pdf"); doc.getPages().get(1).clear(); </p>

### close {#close--}
```
public final void close()
```

Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind.

### contains {#contains-com.aspose.pdf.Operator-}
Gibt true zurück, wenn die Sammlung den angegebenen Operator enthält.

### delete {#delete-int-}
```
public void delete(int index)
```

<p> Löscht einen Operator aus der Sammlung. </p> <hr> <p> Beispiel zeigt, wie ein Operator anhand seines Index gelöscht wird. <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages(1).getContents(); oc.delete(3); </p>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des zu löschenden Operators. Die Nummerierung der Operatoren beginnt bei 1. |

### delete {#delete-java.lang.Iterable-}
Löscht Operatoren aus der Sammlung.

### delete {#delete-com.aspose.pdf.Operator:A-}
<p> Löscht Operatoren aus der Sammlung. </p> <hr> <p> Beispiel zeigt, wie ein Operator aus den Seiteninhalten entfernt wird. </p> <p> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.delete(new Operator[] { oc[1] } ); </p>

### deleteUnrestricted {#deleteUnrestricted-int-}
```
public void deleteUnrestricted(int index)
```

interne uneingeschränkte Version von Delete(index)

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

### dispose {#dispose--}
```
public final void dispose()
```

Führt anwendungsspezifische Aufgaben aus, die mit dem Freigeben, Freisetzen oder Zurücksetzen von nicht verwalteten Ressourcen verbunden sind.

### get_Item {#get_Item-int-}
```
public Operator get_Item(int index)
```

<p> Ruft einen Operator anhand seines Index ab. </p> <hr> Beispiel zeigt, wie ein Operator des Seiteninhalts anhand des Index abgerufen wird. <pre> Document doc = new Document("input.pdf"); OperatorCollection oc = doc.getPages().get(1).getContents(); Operator first = oc.get_Item(1); </pre>

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des Operators. Die Nummerierung beginnt bei 1. |

**Returns:**
Operator vom angegebenen Index

### getUnrestricted {#getUnrestricted-int-}
```
public Operator getUnrestricted(int index)
```

Interne uneingeschränkte Version des Indexers

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | int-Wert |

**Returns:**
Operatorobjekt

### insert {#insert-int-java.lang.Iterable-}
Operatoren an der angegebenen Position einfügen.

### insert {#insert-int-com.aspose.pdf.Operator-}
<p> Fügt einen Operator in die Sammlung ein. </p> <hr> <p> Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt. <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages(1).getContents(); oc.insert(1, new com.aspose.pdf.operators.q()); oc.add(new com.aspose.pdf.operators.Q()); </p>

### insert {#insert-int-com.aspose.pdf.Operator:A-}
<p> Operatoren an der angegebenen Position einfügen. </p> <hr> <p> Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt. </p> <p> Document doc = new Document(\"input.pdf\"); OperatorCollection oc = doc.getPages().get(1).getContents(); oc.insert(1, new Operator[] { new com.aspose.pdf.operators.q(), new com.aspose.pdf.operators.Q() } ); </p>

### isBracketed {#isBracketed--}
```
public boolean isBracketed()
```

Ermittelt den geklammerten Status der Operatorsequenz, d.h. ob diese Operatoren innerhalb von q - Q Blöcken liegen.

**Returns:**
boolescher Wert

### isCommandsParsed {#isCommandsParsed--}
```
public boolean isCommandsParsed()
```

Ermittelt die geparsten Befehle

**Returns:**
boolescher Wert

### isFastTextExtractionMode {#isFastTextExtractionMode--}
```
public boolean isFastTextExtractionMode()
```

Gibt an, ob die Sammlung auf schnelle Textextraktion beschränkt ist

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Ermittelt einen Wert, der angibt, ob die Sammlung schreibgeschützt ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.IGenericEnumerator< Operator > iterator()
```

Gibt einen Enumerator für die Sammlung zurück

**Returns:**
Sammlungsenumerator

### precalculateOperatorsCount {#precalculateOperatorsCount--}
```
public int precalculateOperatorsCount()
```

Ermittelt die Anzahl der Operatoren, die den Seiteninhalt beschreiben, ohne sie zu initialisieren.

**Returns:**
int-Wert

### remove {#remove-com.aspose.pdf.Operator-}
Entfernt einen Operator aus der Sammlung.

### replace {#replace-java.lang.Iterable-}
Ersetzt Operatoren in der Sammlung durch andere Operatoren.

### replace {#replace-com.aspose.pdf.Operator:A-}
Ersetzt Operatoren in der Sammlung durch andere Operatoren.

### resumeUpdate {#resumeUpdate--}
```
public void resumeUpdate()
```

Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind.

### resumeUpdate {#resumeUpdate-boolean-}
```
public final void resumeUpdate(boolean updateAll)
```

Setzt die Dokumentaktualisierung fort. Aktualisiert den Inhaltsstream, falls ausstehende Änderungen vorhanden sind. Markiert alle Operatoren als \"geändert\", wenn der Parameter invalidate true ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| updateAll |  | Wenn true, werden alle Operatoren in der Sammlung als aktualisiert markiert. |

### set_Item {#set_Item-int-com.aspose.pdf.Operator-}
Setzt den Operator anhand seines Index.

### size {#size--}
```
public int size()
```

Ermittelt die Anzahl der Operatoren in der Sammlung.

**Returns:**
int-Wert

### suppressUpdate {#suppressUpdate--}
```
public void suppressUpdate()
```

Unterdrückt das Aktualisieren von Inhaltsdaten. Der Inhaltsstream wird nicht aktualisiert, bis ResumeUpdate aufgerufen wird.

### toList {#toList--}
```
public com.aspose.ms.System.Collections.Generic.List< Operator > toList()
```

Gibt die Operatorliste zurück.

**Returns:**
Operatorliste.

### toString {#toString--}
```
public String toString()
```

Gibt die Textdarstellung des Operators zurück.

**Returns:**
Textdarstellung des Operators.

### updateData {#updateData--}
```
public void updateData()
```

Objektstream aktualisieren.

### updateNormalizedData {#updateNormalizedData--}
```
public void updateNormalizedData()
```

Objektstream aktualisieren und fehlende GSave/GRestore-Operatoren hinzufügen.
