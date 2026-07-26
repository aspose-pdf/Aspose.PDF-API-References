---
title: "AnnotationActionCollection"
linktitle: "AnnotationActionCollection"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt die Sammlung von Annotationsaktionen dar."
type: docs
weight: 70
url: /de/java/com.aspose.pdf/annotationactioncollection/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseActionCollection com.aspose.pdf.AnnotationActionCollection, com.aspose.pdf.BaseActionCollection, com.aspose.pdf.AnnotationActionCollection

```
public final class AnnotationActionCollection extends BaseActionCollection
```

Stellt die Sammlung von Annotationsaktionen dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getOnCalculate](#getOnCalculate--) | Liefert eine Aktion zum Berechnen des Feldwerts. |
| [getOnClosePage](#getOnClosePage--) | Liefert eine Aktion, die ausgeführt wird, wenn die Seite mit der Anmerkung geschlossen wird. |
| [getOnEnter](#getOnEnter--) | Liefert eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung betritt. |
| [getOnExit](#getOnExit--) | Liefert eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung verlässt. |
| [getOnFormat](#getOnFormat--) | Liefert eine Aktion, die zum Formatieren des Feldwerts ausgeführt wird. |
| [getOnHidePage](#getOnHidePage--) | Liefert eine Aktion, die ausgeführt wird, wenn die Seite mit der Anmerkung in der Benutzeroberfläche der Anzeiganwendung nicht mehr sichtbar ist. |
| [getOnLostFocus](#getOnLostFocus--) | Erhält eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus verliert. |
| [getOnModifyCharacter](#getOnModifyCharacter--) | Erhält eine Aktion, die ausgeführt wird, wenn der Benutzer ein Zeichen des Feldes ändert. |
| [getOnOpenPage](#getOnOpenPage--) | Erhält eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geöffnet wird. |
| [getOnPressMouseBtn](#getOnPressMouseBtn--) | Erhält eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung gedrückt wird. |
| [getOnReceiveFocus](#getOnReceiveFocus--) | Erhält eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus erhält. |
| [getOnReleaseMouseBtn](#getOnReleaseMouseBtn--) | Erhält eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung losgelassen wird. |
| [getOnShowPage](#getOnShowPage--) | Erhalte eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung sichtbar wird. |
| [getOnValidate](#getOnValidate--) | Erhält eine Aktion, die ausgeführt wird, wenn der Benutzer den Inhalt des Feldes ändert. |
| [setOnCalculate](#setOnCalculate-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, um den Feldwert zu berechnen. |
| [setOnClosePage](#setOnClosePage-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geschlossen wird. |
| [setOnEnter](#setOnEnter-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung betritt. |
| [setOnExit](#setOnExit-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung verlässt. |
| [setOnFormat](#setOnFormat-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, um den Feldwert zu formatieren. |
| [setOnHidePage](#setOnHidePage-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung nicht mehr sichtbar ist. |
| [setOnLostFocus](#setOnLostFocus-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus verliert. |
| [setOnModifyCharacter](#setOnModifyCharacter-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn der Benutzer ein Zeichen des Feldes ändert. |
| [setOnOpenPage](#setOnOpenPage-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geöffnet wird. |
| [setOnPressMouseBtn](#setOnPressMouseBtn-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung gedrückt wird. |
| [setOnReceiveFocus](#setOnReceiveFocus-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus erhält. |
| [setOnReleaseMouseBtn](#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung losgelassen wird. |
| [setOnShowPage](#setOnShowPage-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung sichtbar wird. |
| [setOnValidate](#setOnValidate-com.aspose.pdf.PdfAction-) | Setzt eine Aktion, die ausgeführt wird, wenn der Benutzer den Inhalt des Feldes ändert. |

### getOnCalculate {#getOnCalculate--}
```
public PdfAction getOnCalculate()
```

Liefert eine Aktion zum Berechnen des Feldwerts.

**Returns:**
Aktion, um den Feldwert zu berechnen.

### getOnClosePage {#getOnClosePage--}
```
public PdfAction getOnClosePage()
```

Liefert eine Aktion, die ausgeführt wird, wenn die Seite mit der Anmerkung geschlossen wird.

**Returns:**
PdfAction-Objekt

### getOnEnter {#getOnEnter--}
```
public PdfAction getOnEnter()
```

Liefert eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung betritt.

**Returns:**
PdfAction-Objekt

### getOnExit {#getOnExit--}
```
public PdfAction getOnExit()
```

Liefert eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung verlässt.

**Returns:**
PdfAction-Objekt

### getOnFormat {#getOnFormat--}
```
public PdfAction getOnFormat()
```

Liefert eine Aktion, die zum Formatieren des Feldwerts ausgeführt wird.

**Returns:**
Aktion, die ausgeführt wird, um den Feldwert zu formatieren.

### getOnHidePage {#getOnHidePage--}
```
public PdfAction getOnHidePage()
```

Liefert eine Aktion, die ausgeführt wird, wenn die Seite mit der Anmerkung in der Benutzeroberfläche der Anzeiganwendung nicht mehr sichtbar ist.

**Returns:**
PdfAction-Objekt

### getOnLostFocus {#getOnLostFocus--}
```
public PdfAction getOnLostFocus()
```

Erhält eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus verliert.

**Returns:**
PdfAction-Objekt

### getOnModifyCharacter {#getOnModifyCharacter--}
```
public PdfAction getOnModifyCharacter()
```

Erhält eine Aktion, die ausgeführt wird, wenn der Benutzer ein Zeichen des Feldes ändert.

**Returns:**
Aktion, die ausgeführt werden soll, wenn der Benutzer das Zeichen des Feldes ändert.

### getOnOpenPage {#getOnOpenPage--}
```
public PdfAction getOnOpenPage()
```

Erhält eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geöffnet wird.

**Returns:**
PdfAction-Objekt

### getOnPressMouseBtn {#getOnPressMouseBtn--}
```
public PdfAction getOnPressMouseBtn()
```

Erhält eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung gedrückt wird.

**Returns:**
PdfAction-Objekt

### getOnReceiveFocus {#getOnReceiveFocus--}
```
public PdfAction getOnReceiveFocus()
```

Erhält eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus erhält.

**Returns:**
PdfAction-Objekt

### getOnReleaseMouseBtn {#getOnReleaseMouseBtn--}
```
public PdfAction getOnReleaseMouseBtn()
```

Erhält eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung losgelassen wird.

**Returns:**
PdfAction-Objekt

### getOnShowPage {#getOnShowPage--}
```
public PdfAction getOnShowPage()
```

Erhalte eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung sichtbar wird.

**Returns:**
PdfAction-Objekt

### getOnValidate {#getOnValidate--}
```
public PdfAction getOnValidate()
```

Erhält eine Aktion, die ausgeführt wird, wenn der Benutzer den Inhalt des Feldes ändert.

**Returns:**
Aktion, die ausgeführt werden soll, wenn der Benutzer den Inhalt des Feldes ändert.

### setOnCalculate {#setOnCalculate-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, um den Feldwert zu berechnen.

### setOnClosePage {#setOnClosePage-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geschlossen wird.

### setOnEnter {#setOnEnter-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung betritt.

### setOnExit {#setOnExit-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn der Cursor den aktiven Bereich der Anmerkung verlässt.

### setOnFormat {#setOnFormat-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, um den Feldwert zu formatieren.

### setOnHidePage {#setOnHidePage-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung nicht mehr sichtbar ist.

### setOnLostFocus {#setOnLostFocus-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus verliert.

### setOnModifyCharacter {#setOnModifyCharacter-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn der Benutzer ein Zeichen des Feldes ändert.

### setOnOpenPage {#setOnOpenPage-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, geöffnet wird.

### setOnPressMouseBtn {#setOnPressMouseBtn-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung gedrückt wird.

### setOnReceiveFocus {#setOnReceiveFocus-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Anmerkung den Eingabefokus erhält.

### setOnReleaseMouseBtn {#setOnReleaseMouseBtn-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Maustaste im aktiven Bereich der Anmerkung losgelassen wird.

### setOnShowPage {#setOnShowPage-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn die Seite, die die Anmerkung enthält, in der Benutzeroberfläche der Viewer-Anwendung sichtbar wird.

### setOnValidate {#setOnValidate-com.aspose.pdf.PdfAction-}
Setzt eine Aktion, die ausgeführt wird, wenn der Benutzer den Inhalt des Feldes ändert.
