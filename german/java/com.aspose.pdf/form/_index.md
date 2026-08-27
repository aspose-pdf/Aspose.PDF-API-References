---
title: "Formular"
linktitle: "Formular"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die ein Formularobjekt darstellt."
type: docs
weight: 1740
url: /de/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Klasse, die ein Formularobjekt darstellt.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Konstruktor |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Fügt ein Feld zum Formular hinzu. |
| [add](#add-com.aspose.pdf.Field-int-) | Fügt ein Feld zum Formular hinzu. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Fügt ein neues Feld zum Formular hinzu; Wenn dieses Feld bereits in einem anderen oder diesem Formular platziert ist, wird eine Kopie des Feldes erstellt. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Fügt ein Feld zum Formular hinzu. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Fügt ein zusätzliches Erscheinungsbild des Feldes auf der angegebenen Seite des Dokuments an der angegebenen Position hinzu. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Fügt ein zusätzliches Erscheinungsbild des Feldes auf der angegebenen Seite des Dokuments hinzu. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Setzt XFA des Formulars auf den angegebenen Wert. |
| [clear](#clear--) | Löscht alle Felder aus dem Formular. Nicht unterstützt. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Bestimmt, ob ein Feld im Formular vorhanden ist. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Kopiert Felder, die im Formular platziert sind, in ein Array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Kopiert die Felder des Formulars in ein Array. |
| [delete](#delete-com.aspose.pdf.Field-) | Lösche Feld aus dem Formular. |
| [delete](#delete-java.lang.String-) | Löscht das Feld aus dem Formular anhand seines Namens. |
| [flatten](#flatten--) | Entfernt alle statischen Formularfelder und legt deren Werte direkt auf der Seite ab. |
| [get_Item](#get_Item-int-) | Liest das Feld des Formulars über den Feldindex. |
| [get_Item](#get_Item-java.lang.String-) | Liest das Feld des Formulars über den Feldnamen. Wirft eine Ausnahme, wenn das Feld nicht gefunden wurde. |
| [get_xfa](#get_xfa--) | Nur für den internen Gebrauch. |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Sucht ein Feld nach Feldnamen. Gibt null zurück, wenn das Feld nicht gefunden wurde. |
| [getAutoRecalculate](#getAutoRecalculate--) | Wenn aktiviert, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Setzen Sie ihn auf false, um die Leistung zu steigern, wenn das Formular mit einer großen Anzahl berechneter Felder ausgefüllt wird. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind. |
| [getDefaultAppearance](#getDefaultAppearance--) | Liest das Standardaussehen des Formulars (Objekt, das die Standardschriftart, Textgröße und Farbe für Felder im Formular beschreibt). |
| [getDefaultResources](#getDefaultResources--) | Liest die Standardressourcen, die in diesem Formular abgelegt sind. |
| [getDocument](#getDocument--) | Nur für den internen Gebrauch. |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | Wenn diese Eigenschaft true ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche Xfa‑exclGroup‑Elementcontainer gezeichnet. Diese Eigenschaft wurde eingeführt, weil bei der Konvertierung der Xfa‑Darstellung von Formularen zum Standard Analogien für die exclGroup fehlen. Sie ist standardmäßig false. |
| [getFields](#getFields--) | Liest die Liste aller Felder auf der untersten Ebene des hierarchischen Formulars. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Gibt die Felder innerhalb des angegebenen Rechtecks zurück. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | Wenn diese Eigenschaft true ist, wird der Wert des Schlüssels NeedsRendering während der Konvertierung des XFA‑Formulars zum Standardformular ignoriert. Sie ist standardmäßig false. |
| [getNeedsRendering](#getNeedsRendering--) | Liest einen Wert, der angibt, ob das Dokument die Entfernung des dynamischen XFA‑Formulars erfordert. Diese Eigenschaft wurde eingeführt, um zu bestimmen, ob {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) verwendet werden sollte, um das XFA‑Formular zu entfernen, wenn das XFA‑Formular vorhanden ist und {@code NeedsRendering}({@link #getNeedsRendering}) false ist. |
| [getRemovePermission](#getRemovePermission--) | Wenn diese Eigenschaft true ist, wird das \"Perms\"-Dictionary nach der Konvertierung dynamischer Dokumente zum Standard aus dem PDF‑Dokument entfernt. Das \"Perms\"-Dictionary kann Regeln enthalten, die die Anzeigeauswahl obligatorischer Felder im Adobe‑Acrobat‑Reader stören. Sie ist standardmäßig false. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei (geschrieben) auf eine Weise gespeichert wird, die ihren vorherigen Inhalt ändert, im Gegensatz zu einem inkrementellen Update. |
| [getSignaturesExist](#getSignaturesExist--) | Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Formulare können Signaturinformationen enthalten, d. h. sie können signiert oder unsigniert sein. Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft teilt dem Formularkonverter (z. B. während der Konvertierung eines XFA‑Formulars zum Standardformular) mit, ob das Ergebnisformular als signiert oder als unsigniert gerendert werden muss. |
| [getSyncRoot](#getSyncRoot--) | Gibt das Synchronisationsobjekt zurück. |
| [getType](#getType--) | Liest den Typ des Formulars. Mögliche Werte sind: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Liest die XFA‑Daten des Formulars (falls vorhanden). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Prüft, ob das Formular das angegebene Feld bereits enthält. |
| [hasField](#hasField-java.lang.String-) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde. |
| [hasField](#hasField-java.lang.String-boolean-) | Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde, mit der Möglichkeit, in die Kindhierarchie der Felder zu schauen. |
| [hasXfa](#hasXfa--) | Liest einen Wert, der angibt, ob das Dokument ein XFA‑Formular enthält. Diese Eigenschaft wurde eingeführt, um zu bestimmen, ob {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) verwendet werden sollte, um das XFA‑Formular zu entfernen, wenn das XFA‑Formular vorhanden ist und {@code NeedsRendering}({@link #getNeedsRendering}) false ist. |
| [isReadOnly](#isReadOnly--) | Bestimmt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück. |
| [isSynchronized](#isSynchronized--) | Gibt true zurück, wenn das Objekt thread‑sicher ist. |
| [iterator](#iterator--) | Liest die Aufzählung der Formularfelder. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Löscht das Feld aus dem Formular. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Entfernt das Erscheinungsbild des Feldes am angegebenen Index. Wenn nur ein untergeordnetes Erscheinungsbild übrig bleibt, bettet die Methode es in das Feld ein. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | Wenn aktiviert, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Setzen Sie ihn auf false, um die Leistung zu steigern, wenn das Formular mit einer großen Anzahl berechneter Felder ausgefüllt wird. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Ermöglicht das Festlegen der Reihenfolge der Feldberechnung. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Setzt das Standard‑Erscheinungsbild des Formulars (Objekt, das die Standardschriftart, Textgröße und Farbe für Felder im Formular beschreibt). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | Wenn diese Eigenschaft true ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche Xfa‑exclGroup‑Elementcontainer gezeichnet. Diese Eigenschaft wurde eingeführt, weil bei der Konvertierung der Xfa‑Darstellung von Formularen zum Standard Analogien für die exclGroup fehlen. Sie ist standardmäßig false. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | Wenn diese Eigenschaft true ist, wird der Wert des Schlüssels NeedsRendering während der Konvertierung des XFA‑Formulars zum Standardformular ignoriert. Sie ist standardmäßig false. |
| [setRemovePermission](#setRemovePermission-boolean-) | Wenn diese Eigenschaft true ist, wird das \"Perms\"-Dictionary nach der Konvertierung dynamischer Dokumente zum Standard aus dem PDF‑Dokument entfernt. Das \"Perms\"-Dictionary kann Regeln enthalten, die die Anzeigeauswahl obligatorischer Felder im Adobe‑Acrobat‑Reader stören. Sie ist standardmäßig false. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei (geschrieben) auf eine Weise gespeichert wird, die ihren vorherigen Inhalt ändert, im Gegensatz zu einem inkrementellen Update. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Formulare können Signaturinformationen enthalten, d. h. sie können signiert oder unsigniert sein. Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft teilt dem Formularkonverter (z. B. während der Konvertierung eines XFA‑Formulars zum Standardformular) mit, ob das Ergebnisformular als signiert oder als unsigniert gerendert werden muss. |
| [setType](#setType-com.aspose.pdf.FormType-) | Liest den Typ des Formulars. Mögliche Werte sind: Standard, Static, Dynamic. |
| [size](#size--) | Ermittelt die Anzahl der Felder in diesem Formular. |

### Form {#Form-com.aspose.pdf.IDocument-}
Konstruktor

### add {#add-com.aspose.pdf.Field-}
Fügt ein Feld zum Formular hinzu.

### add {#add-com.aspose.pdf.Field-int-}
Fügt ein Feld zum Formular hinzu.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Fügt ein neues Feld zum Formular hinzu; Wenn dieses Feld bereits in einem anderen oder diesem Formular platziert ist, wird eine Kopie des Feldes erstellt.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Fügt ein Feld zum Formular hinzu.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Fügt ein zusätzliches Erscheinungsbild des Feldes auf der angegebenen Seite des Dokuments an der angegebenen Position hinzu.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Fügt ein zusätzliches Erscheinungsbild des Feldes auf der angegebenen Seite des Dokuments hinzu.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Setzt XFA des Formulars auf den angegebenen Wert.

### clear {#clear--}
```
public void clear()
```

Löscht alle Felder aus dem Formular. Nicht unterstützt.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Bestimmt, ob ein Feld im Formular vorhanden ist.

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Kopiert Felder, die im Formular platziert sind, in ein Array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Kopiert die Felder des Formulars in ein Array.

### delete {#delete-com.aspose.pdf.Field-}
Lösche Feld aus dem Formular.

### delete {#delete-java.lang.String-}
Löscht das Feld aus dem Formular anhand seines Namens.

### flatten {#flatten--}
```
public void flatten()
```

Entfernt alle statischen Formularfelder und legt deren Werte direkt auf der Seite ab.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Liest das Feld des Formulars über den Feldindex.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  | Index des Feldes. |

**Returns:**
Abgerufenes Feld.

### get_Item {#get_Item-java.lang.String-}
Liest das Feld des Formulars über den Feldnamen. Wirft eine Ausnahme, wenn das Feld nicht gefunden wurde.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

Nur für den internen Gebrauch.

**Returns:**
XFA‑Objekt

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Sucht ein Feld nach Feldnamen. Gibt null zurück, wenn das Feld nicht gefunden wurde.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

Wenn aktiviert, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Setzen Sie ihn auf false, um die Leistung zu steigern, wenn das Formular mit einer großen Anzahl berechneter Felder ausgefüllt wird.

**Returns:**
boolescher Wert

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind.

**Returns:**
boolescher Wert

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Liest das Standardaussehen des Formulars (Objekt, das die Standardschriftart, Textgröße und Farbe für Felder im Formular beschreibt).

**Returns:**
DefaultAppearance-Objekt

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Liest die Standardressourcen, die in diesem Formular abgelegt sind.

**Returns:**
Ressourcenwert

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Nur für den internen Gebrauch.

**Returns:**
IDocument‑Objekt

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

Wenn diese Eigenschaft true ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche Xfa‑exclGroup‑Elementcontainer gezeichnet. Diese Eigenschaft wurde eingeführt, weil bei der Konvertierung der Xfa‑Darstellung von Formularen zum Standard Analogien für die exclGroup fehlen. Sie ist standardmäßig false.

**Returns:**
boolescher Wert

### getFields {#getFields--}
```
public Field [] getFields()
```

Liest die Liste aller Felder auf der untersten Ebene des hierarchischen Formulars.

**Returns:**
Array mit gefundenen Feldern.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Gibt die Felder innerhalb des angegebenen Rechtecks zurück.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

Wenn diese Eigenschaft true ist, wird der Wert des Schlüssels NeedsRendering während der Konvertierung des XFA‑Formulars zum Standardformular ignoriert. Sie ist standardmäßig false.

**Returns:**
boolescher Wert

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Liest einen Wert, der angibt, ob das Dokument die Entfernung des dynamischen XFA‑Formulars erfordert. Diese Eigenschaft wurde eingeführt, um zu bestimmen, ob {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) verwendet werden sollte, um das XFA‑Formular zu entfernen, wenn das XFA‑Formular vorhanden ist und {@code NeedsRendering}({@link #getNeedsRendering}) false ist.

**Returns:**
boolescher Wert

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

Wenn diese Eigenschaft true ist, wird das \"Perms\"-Dictionary nach der Konvertierung dynamischer Dokumente zum Standard aus dem PDF‑Dokument entfernt. Das \"Perms\"-Dictionary kann Regeln enthalten, die die Anzeigeauswahl obligatorischer Felder im Adobe‑Acrobat‑Reader stören. Sie ist standardmäßig false.

**Returns:**
boolescher Wert

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei (geschrieben) auf eine Weise gespeichert wird, die ihren vorherigen Inhalt ändert, im Gegensatz zu einem inkrementellen Update.

**Returns:**
boolescher Wert

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld.

**Returns:**
boolescher Wert

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Formulare können Signaturinformationen enthalten, d. h. sie können signiert oder unsigniert sein. Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft teilt dem Formularkonverter (z. B. während der Konvertierung eines XFA‑Formulars zum Standardformular) mit, ob das Ergebnisformular als signiert oder als unsigniert gerendert werden muss.

**Returns:**
SignDependentElementsRenderingModes‑Element @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Gibt das Synchronisationsobjekt zurück.

**Returns:**
Objekt für Synchronisation

### getType {#getType--}
```
public FormType getType()
```

Liest den Typ des Formulars. Mögliche Werte sind: Standard, Static, Dynamic.

**Returns:**
FormType‑Wert @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Liest die XFA‑Daten des Formulars (falls vorhanden).

**Returns:**
XFA‑Wert

### hasField {#hasField-com.aspose.pdf.Field-}
Prüft, ob das Formular das angegebene Feld bereits enthält.

### hasField {#hasField-java.lang.String-}
Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde.

### hasField {#hasField-java.lang.String-boolean-}
Bestimmt, ob das Feld mit dem angegebenen Namen bereits zum Formular hinzugefügt wurde, mit der Möglichkeit, in die Kindhierarchie der Felder zu schauen.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Liest einen Wert, der angibt, ob das Dokument ein XFA‑Formular enthält. Diese Eigenschaft wurde eingeführt, um zu bestimmen, ob {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) verwendet werden sollte, um das XFA‑Formular zu entfernen, wenn das XFA‑Formular vorhanden ist und {@code NeedsRendering}({@link #getNeedsRendering}) false ist.

**Returns:**
boolescher Wert

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Bestimmt, ob die Sammlung schreibgeschützt ist. Gibt immer false zurück.

**Returns:**
boolescher Wert

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Gibt true zurück, wenn das Objekt thread‑sicher ist.

**Returns:**
boolescher Wert

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Liest die Aufzählung der Formularfelder.

**Returns:**
Feld‑Enumerator.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Löscht das Feld aus dem Formular.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Entfernt das Erscheinungsbild des Feldes am angegebenen Index. Wenn nur ein untergeordnetes Erscheinungsbild übrig bleibt, bettet die Methode es in das Feld ein.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

Wenn aktiviert, werden alle Formularfelder neu berechnet, wenn ein Feld geändert wird. Der Standardwert ist true. Setzen Sie ihn auf false, um die Leistung zu steigern, wenn das Formular mit einer großen Anzahl berechneter Felder ausgefüllt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

Wenn gesetzt, werden fehlende Formularfelder automatisch erstellt, wenn sie in Anmerkungen vorhanden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Ermöglicht das Festlegen der Reihenfolge der Feldberechnung.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Setzt das Standard‑Erscheinungsbild des Formulars (Objekt, das die Standardschriftart, Textgröße und Farbe für Felder im Formular beschreibt).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

Wenn diese Eigenschaft true ist, werden zusätzliche rote Begrenzungsrechtecke für erforderliche Xfa‑exclGroup‑Elementcontainer gezeichnet. Diese Eigenschaft wurde eingeführt, weil bei der Konvertierung der Xfa‑Darstellung von Formularen zum Standard Analogien für die exclGroup fehlen. Sie ist standardmäßig false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

Wenn diese Eigenschaft true ist, wird der Wert des Schlüssels NeedsRendering während der Konvertierung des XFA‑Formulars zum Standardformular ignoriert. Sie ist standardmäßig false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

Wenn diese Eigenschaft true ist, wird das \"Perms\"-Dictionary nach der Konvertierung dynamischer Dokumente zum Standard aus dem PDF‑Dokument entfernt. Das \"Perms\"-Dictionary kann Regeln enthalten, die die Anzeigeauswahl obligatorischer Felder im Adobe‑Acrobat‑Reader stören. Sie ist standardmäßig false.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

Wenn gesetzt, enthält das Dokument Signaturen, die ungültig werden können, wenn die Datei (geschrieben) auf eine Weise gespeichert wird, die ihren vorherigen Inhalt ändert, im Gegensatz zu einem inkrementellen Update.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

Wenn gesetzt, enthält das Dokument mindestens ein Signaturfeld.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Formulare können Signaturinformationen enthalten, d. h. sie können signiert oder unsigniert sein. Und die Ansicht des Formulars muss manchmal davon abhängen, ob das Formular signiert ist oder nicht. Diese Eigenschaft teilt dem Formularkonverter (z. B. während der Konvertierung eines XFA‑Formulars zum Standardformular) mit, ob das Ergebnisformular als signiert oder als unsigniert gerendert werden muss.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes‑Element @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Liest den Typ des Formulars. Mögliche Werte sind: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Ermittelt die Anzahl der Felder in diesem Formular.

**Returns:**
int-Wert
