---
title: "XFA"
linktitle: "XFA"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Stellt ein XML-Formular in Bezug auf die XML Forms Architecture (XFA) dar."
type: docs
weight: 5550
url: /de/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Stellt ein XML-Formular in Bezug auf die XML Forms Architecture (XFA) dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Füge den XML-Wert dem Knoten der Vorlage hinzu, der dem XPath-Ausdruck entspricht |
| [beginCachedUpdates](#beginCachedUpdates--) | Starte den Modus für zwischengespeicherte Updates. Alle Änderungen an XFA werden zwischengespeichert und bei Aufruf von EndCachedUpdates in die Dokumentstruktur gespeichert. Dies ermöglicht eine Leistungsverbesserung, indem redundante Vorgänge beim Speichern von XML-Paketen im Dokument vermieden werden, wenn viele Änderungen an XFA vorgenommen werden. |
| [endCachedUpdates](#endCachedUpdates--) | Beendet zwischengespeicherte Updates und speichert alle Daten in die Dokumentstruktur. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Flacht das Feld des XFA-Formulars ab. |
| [get_Item](#get_Item-java.lang.String-) | Liest den Wert des Datenknotens gemäß {@code path}. |
| [getConfig](#getConfig--) | XFA‑Config‑Komponente eines XFA‑Formulars. |
| [getDatasets](#getDatasets--) | XFA‑Datasets‑Komponente eines XFA‑Formulars. |
| [getFieldNames](#getFieldNames--) | Liste der Feldnamen in der Formularvorlage. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Gibt eine Map mit kurzem Feldnamen und dessen Zeichenkettenwert für alle Felder zurück. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Gibt den XML‑Knoten des XFA‑Feldtemplates zurück. |
| [getFieldTemplates](#getFieldTemplates--) | Gibt eine Liste aller Feldtemplates im XFA‑Formular zurück. |
| [getForm](#getForm--) | Liest die XFA‑Formular‑Komponente eines XFA‑Formulars. |
| [getNamespaceManager_](#getNamespaceManager_--) | Liest den Namensraum für das XFA‑Formular. Die folgenden Namensräume sind definiert: \"data\" für Formulardaten und \"tpl\" für die Formularvorlage. |
| [getNamespaceManager](#getNamespaceManager--) | Gibt den Namensraum‑Manager zurück, der für Vorlage und Daten verwendete Namensräume enthält. |
| [getTemplate](#getTemplate--) | XFA‑Template‑Komponente eines XFA‑Formulars. |
| [getXDP](#getXDP--) | XML‑Datenpaket (alle XFA‑Formular‑Komponenten innerhalb eines umgebenden XML‑Containers). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Liest den Wert des Datenknotens gemäß {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Setzt das Bild für ein XFA‑Feld. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Versucht, das Berechnungsskript aus dem XFA‑Formular zu exportieren. Andernfalls wird die leere Zeichenkette zurückgegeben; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Füge den XML-Wert dem Knoten der Vorlage hinzu, der dem XPath-Ausdruck entspricht

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Starte den Modus für zwischengespeicherte Updates. Alle Änderungen an XFA werden zwischengespeichert und bei Aufruf von EndCachedUpdates in die Dokumentstruktur gespeichert. Dies ermöglicht eine Leistungsverbesserung, indem redundante Vorgänge beim Speichern von XML-Paketen im Dokument vermieden werden, wenn viele Änderungen an XFA vorgenommen werden.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Beendet zwischengespeicherte Updates und speichert alle Daten in die Dokumentstruktur.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Flacht das Feld des XFA-Formulars ab.

### get_Item {#get_Item-java.lang.String-}
Liest den Wert des Datenknotens gemäß {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA‑Config‑Komponente eines XFA‑Formulars.

**Returns:**
XmlNode‑Objekt

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA‑Datasets‑Komponente eines XFA‑Formulars.

**Returns:**
XmlNode‑Objekt

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Liste der Feldnamen in der Formularvorlage.

**Returns:**
Array von String-Werten

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Gibt eine Map mit kurzem Feldnamen und dessen Zeichenkettenwert für alle Felder zurück. </p>

**Returns:**
{@code HashMap<String, String>}-Objekt

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Gibt den XML‑Knoten des XFA‑Feldtemplates zurück.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Gibt eine Liste aller Feldtemplates im XFA‑Formular zurück.

**Returns:**
Liste von Feldtemplates.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Liest die XFA‑Formular‑Komponente eines XFA‑Formulars.

**Returns:**
XmlNode‑Objekt

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Liest den Namensraum für das XFA‑Formular. Die folgenden Namensräume sind definiert: \"data\" für Formulardaten und \"tpl\" für die Formularvorlage.

**Returns:**
XmlNamespaceManager‑Objekt

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Gibt den Namensraum‑Manager zurück, der für Vorlage und Daten verwendete Namensräume enthält.

**Returns:**
XmlNamespaceManager‑Objekt

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA‑Template‑Komponente eines XFA‑Formulars.

**Returns:**
XmlNode‑Objekt

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML‑Datenpaket (alle XFA‑Formular‑Komponenten innerhalb eines umgebenden XML‑Containers).

**Returns:**
XmlDocument‑Objekt

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Liest den Wert des Datenknotens gemäß {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Setzt das Bild für ein XFA‑Feld.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Versucht, das Berechnungsskript aus dem XFA‑Formular zu exportieren. Andernfalls wird die leere Zeichenkette zurückgegeben;
