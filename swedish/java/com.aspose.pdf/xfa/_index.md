---
title: "XFA"
linktitle: "XFA"
second_title: "Aspose.PDF för Java API-referens"
description: "Representerar XML-formulär enligt XML Forms Architecture (XFA)."
type: docs
weight: 5550
url: /sv/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Representerar XML-formulär enligt XML Forms Architecture (XFA).

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Lägg till XML-värde till mallens nod som matchar XPath-uttrycket |
| [beginCachedUpdates](#beginCachedUpdates--) | Starta läge för cachade uppdateringar. Alla ändringar som görs i XFA kommer att cachas och sparas i dokumentstrukturen vid anropet EndCachedUpdates. Detta möjliggör förbättrad prestanda genom att undvika redundanta operationer vid sparande av XML-paket i dokumentet när många ändringar i XFA görs. |
| [endCachedUpdates](#endCachedUpdates--) | Avslutar cachade uppdateringar och sparar all data i dokumentstrukturen. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Platta ut fältet i XFA-formuläret. |
| [get_Item](#get_Item-java.lang.String-) | Hämtar värdet för datanoden enligt {@code path}. |
| [getConfig](#getConfig--) | XFA Config-komponent i ett XFA-formulär. |
| [getDatasets](#getDatasets--) | XFA Datasets-komponent i ett XFA-formulär. |
| [getFieldNames](#getFieldNames--) | Lista över fältnamn i formulärmallen. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Returnerar en karta med kort fältnamn och dess strängvärde för alla fält. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Returnerar XML-nod för XFA-fältmall. |
| [getFieldTemplates](#getFieldTemplates--) | Returnerar en lista med alla fältmallar i XFA-formuläret. |
| [getForm](#getForm--) | Hämtar XFA Form Component i ett XFA-formulär. |
| [getNamespaceManager_](#getNamespaceManager_--) | Hämtar namnutrymmet för XFA-formuläret. Följande namnrymder är definierade: "data" för formulärdata och "tpl" för formulärmall. |
| [getNamespaceManager](#getNamespaceManager--) | Returnerar namnrymdshanterare med namnrymder som används för mall och data. |
| [getTemplate](#getTemplate--) | XFA Template-komponent i ett XFA-formulär. |
| [getXDP](#getXDP--) | XML Data Package (alla XFA-formulärkomponenter inom en omgivande XML-behållare). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Hämtar värdet för datanoden enligt {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Ställer in bild för XFA-fält. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Försöker exportera beräkningsskript från XFA-formuläret. Returnerar annars den tomma strängen; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Lägg till XML-värde till mallens nod som matchar XPath-uttrycket

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Starta läge för cachade uppdateringar. Alla ändringar som görs i XFA kommer att cachas och sparas i dokumentstrukturen vid anropet EndCachedUpdates. Detta möjliggör förbättrad prestanda genom att undvika redundanta operationer vid sparande av XML-paket i dokumentet när många ändringar i XFA görs.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Avslutar cachade uppdateringar och sparar all data i dokumentstrukturen.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Platta ut fältet i XFA-formuläret.

### get_Item {#get_Item-java.lang.String-}
Hämtar värdet för datanoden enligt {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA Config-komponent i ett XFA-formulär.

**Returns:**
XmlNode-objekt

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA Datasets-komponent i ett XFA-formulär.

**Returns:**
XmlNode-objekt

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Lista över fältnamn i formulärmallen.

**Returns:**
array av String-värden

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Returnerar en karta med kort fältnamn och dess strängvärde för alla fält. </p>

**Returns:**
{@code HashMap<String, String>}-objekt

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Returnerar XML-nod för XFA-fältmall.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Returnerar en lista med alla fältmallar i XFA-formuläret.

**Returns:**
Lista över fältmallar.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Hämtar XFA Form Component i ett XFA-formulär.

**Returns:**
XmlNode-objekt

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Hämtar namnutrymmet för XFA-formuläret. Följande namnrymder är definierade: "data" för formulärdata och "tpl" för formulärmall.

**Returns:**
XmlNamespaceManager-objekt

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Returnerar namnrymdshanterare med namnrymder som används för mall och data.

**Returns:**
XmlNamespaceManager-objekt

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA Template-komponent i ett XFA-formulär.

**Returns:**
XmlNode-objekt

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML Data Package (alla XFA-formulärkomponenter inom en omgivande XML-behållare).

**Returns:**
XmlDocument-objekt

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Hämtar värdet för datanoden enligt {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Ställer in bild för XFA-fält.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Försöker exportera beräkningsskript från XFA-formuläret. Returnerar annars den tomma strängen;
