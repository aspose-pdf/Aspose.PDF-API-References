---
title: XFA
second_title: Aspose.PDF for Java API Reference
description: Represents XML form regarding XML Forms Architecture (XFA).
type: docs
weight: 5550
url: /java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

Represents XML form regarding XML Forms Architecture (XFA).

## Methods

| Method | Description |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | Append XML value to the template's node that matches the XPath expression |
| [beginCachedUpdates](#beginCachedUpdates--) | Start cached updates mode. All changes made to XFA will be cached and saved into document structure at EndCachedUpdates call. This allows to improve preformacne by avoiding redudant operations on saving XML packets into document when a lot of changes to XFA are made. |
| [endCachedUpdates](#endCachedUpdates--) | Ends cahced updates and saves all data into document structure. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Flatten field of XFA form. |
| [get_Item](#get_Item-java.lang.String-) | Gets data node value according {@code path}. |
| [getConfig](#getConfig--) | XFA Config component of an XFA form. |
| [getDatasets](#getDatasets--) | XFA Datasets component of an XFA form. |
| [getFieldNames](#getFieldNames--) | List of field names in the form template. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> Returns map with short field name and it's string value for all fields. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | Returns XML node of XFA field tempalte. |
| [getFieldTemplates](#getFieldTemplates--) | Returns list of all field templates on XFA form. |
| [getForm](#getForm--) | Gets XFA Form Component of an XFA form. |
| [getNamespaceManager_](#getNamespaceManager_--) | Gets the namespace for the XFA form. The following namepsaces are defined: "data" for form data and "tpl" for form template. |
| [getNamespaceManager](#getNamespaceManager--) | Returns namespace manager with namespaces used for template and data. |
| [getTemplate](#getTemplate--) | XFA Template component of an XFA form. |
| [getXDP](#getXDP--) | XML Data Package (all XFA form components within a surrounding XML container). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | Gets data node value according {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | Sets image for XFA field. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | Tries to export calculation script from XFA form. Otherwise returns the empty string; |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
Append XML value to the template's node that matches the XPath expression

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

Start cached updates mode. All changes made to XFA will be cached and saved into document structure at EndCachedUpdates call. This allows to improve preformacne by avoiding redudant operations on saving XML packets into document when a lot of changes to XFA are made.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

Ends cahced updates and saves all data into document structure.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
Flatten field of XFA form.

### get_Item {#get_Item-java.lang.String-}
Gets data node value according {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA Config component of an XFA form.

**Returns:**
XmlNode object

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA Datasets component of an XFA form.

**Returns:**
XmlNode object

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

List of field names in the form template.

**Returns:**
array of String values

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> Returns map with short field name and it's string value for all fields. </p>

**Returns:**
{@code HashMap<String, String>} object

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
Returns XML node of XFA field tempalte.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

Returns list of all field templates on XFA form.

**Returns:**
List of field templates.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

Gets XFA Form Component of an XFA form.

**Returns:**
XmlNode object

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

Gets the namespace for the XFA form. The following namepsaces are defined: "data" for form data and "tpl" for form template.

**Returns:**
XmlNamespaceManager object

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

Returns namespace manager with namespaces used for template and data.

**Returns:**
XmlNamespaceManager object

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA Template component of an XFA form.

**Returns:**
XmlNode object

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML Data Package (all XFA form components within a surrounding XML container).

**Returns:**
XmlDocument object

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
Gets data node value according {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
Sets image for XFA field.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
Tries to export calculation script from XFA form. Otherwise returns the empty string;
