---
title: XFA
second_title: Aspose.PDF for Java API Reference
description: Represents XML form regarding XML Forms Architecture XFA.
type: docs
weight: 410
url: /java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object
```
public final class XFA
```

Represents XML form regarding XML Forms Architecture (XFA).
## Methods

| Method | Description |
| --- | --- |
| [getTemplate()](#getTemplate--) | XFA Template component of an XFA form. |
| [tryGetTemplateString(String value)](#tryGetTemplateString-java.lang.String-) | Tries to export calculation script from XFA form. |
| [getForm()](#getForm--) | Gets XFA Form Component of an XFA form. |
| [getDatasets()](#getDatasets--) | XFA Datasets component of an XFA form. |
| [getConfig()](#getConfig--) | XFA Config component of an XFA form. |
| [getXDP()](#getXDP--) | XML Data Package (all XFA form components within a surrounding XML container). |
| [get_Item(String path)](#get-Item-java.lang.String-) | Gets data node value according  path . |
| [set_Item(String path, String value)](#set-Item-java.lang.String-java.lang.String-) | Gets data node value according  path . |
| [getFieldNames()](#getFieldNames--) | List of field names in the form template. |
| [getFieldTemplate(String fieldName)](#getFieldTemplate-java.lang.String-) | Returns XML node of XFA field tempalte. |
| [getFieldTemplates()](#getFieldTemplates--) | Returns list of all field templates on XFA form. |
| [getNamespaceManager()](#getNamespaceManager--) | Returns namespace manager with namespaces used for template and data. |
| [getNamespaceManager_()](#getNamespaceManager---) | Gets the namespace for the XFA form. |
| [flattenXfaField(System.Xml.XmlNode field)](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | Flatten field of XFA form. |
| [beginCachedUpdates()](#beginCachedUpdates--) | Start cached updates mode. |
| [endCachedUpdates()](#endCachedUpdates--) | Ends cahced updates and saves all data into document structure. |
| [setFieldImage(String fieldName, InputStream image)](#setFieldImage-java.lang.String-java.io.InputStream-) | Sets image for XFA field. |
| [setFieldImageInternal(String fieldName, System.IO.Stream image)](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [getFieldsWithTextValuesMap()](#getFieldsWithTextValuesMap--) | Returns map with short field name and it's string value for all fields. |
| [getXfaField(String path)](#getXfaField-java.lang.String-) |  |
### getTemplate() {#getTemplate--}
```
public System.Xml.XmlNode getTemplate()
```


XFA Template component of an XFA form.

**Returns:**
com.aspose.ms.System.Xml.XmlNode - XmlNode object
### tryGetTemplateString(String value) {#tryGetTemplateString-java.lang.String-}
```
public String tryGetTemplateString(String value)
```


Tries to export calculation script from XFA form. Otherwise returns the empty string;

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The tag name |

**Returns:**
java.lang.String - String instance
### getForm() {#getForm--}
```
public System.Xml.XmlNode getForm()
```


Gets XFA Form Component of an XFA form.

**Returns:**
com.aspose.ms.System.Xml.XmlNode - XmlNode object
### getDatasets() {#getDatasets--}
```
public System.Xml.XmlNode getDatasets()
```


XFA Datasets component of an XFA form.

**Returns:**
com.aspose.ms.System.Xml.XmlNode - XmlNode object
### getConfig() {#getConfig--}
```
public System.Xml.XmlNode getConfig()
```


XFA Config component of an XFA form.

**Returns:**
com.aspose.ms.System.Xml.XmlNode - XmlNode object
### getXDP() {#getXDP--}
```
public System.Xml.XmlDocument getXDP()
```


XML Data Package (all XFA form components within a surrounding XML container).

**Returns:**
com.aspose.ms.System.Xml.XmlDocument - XmlDocument object
### get_Item(String path) {#get-Item-java.lang.String-}
```
public String get_Item(String path)
```


Gets data node value according  path .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Data node path, e.g. form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Be sure to include indices even if data contains only single occurences of each nodes, i.e. write node1[0].node2[0]... instead of node1.node2... |

**Returns:**
java.lang.String - Data node value.
### set_Item(String path, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String path, String value)
```


Gets data node value according  path .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | String value |
| value | java.lang.String | String value |

### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


List of field names in the form template.

**Returns:**
java.lang.String[] - array of String values
### getFieldTemplate(String fieldName) {#getFieldTemplate-java.lang.String-}
```
public System.Xml.XmlNode getFieldTemplate(String fieldName)
```


Returns XML node of XFA field tempalte.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Path of the field which template must be found. |

**Returns:**
com.aspose.ms.System.Xml.XmlNode - XL node with field template.
### getFieldTemplates() {#getFieldTemplates--}
```
public System.Xml.XmlNodeList getFieldTemplates()
```


Returns list of all field templates on XFA form.

**Returns:**
com.aspose.ms.System.Xml.XmlNodeList - List of field templates.
### getNamespaceManager() {#getNamespaceManager--}
```
public System.Xml.XmlNamespaceManager getNamespaceManager()
```


Returns namespace manager with namespaces used for template and data.

**Returns:**
com.aspose.ms.System.Xml.XmlNamespaceManager - XmlNamespaceManager object
### getNamespaceManager_() {#getNamespaceManager---}
```
public System.Xml.XmlNamespaceManager getNamespaceManager_()
```


Gets the namespace for the XFA form. The following namepsaces are defined: "data" for form data and "tpl" for form template.

**Returns:**
com.aspose.ms.System.Xml.XmlNamespaceManager - XmlNamespaceManager object
### flattenXfaField(System.Xml.XmlNode field) {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
```
public static void flattenXfaField(System.Xml.XmlNode field)
```


Flatten field of XFA form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | com.aspose.ms.System.Xml.XmlNode | XFA form field node. |

### beginCachedUpdates() {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```


Start cached updates mode. All changes made to XFA will be cached and saved into document structure at EndCachedUpdates call. This allows to improve preformacne by avoiding redudant operations on saving XML packets into document when a lot of changes to XFA are made.

### endCachedUpdates() {#endCachedUpdates--}
```
public void endCachedUpdates()
```


Ends cahced updates and saves all data into document structure.

### setFieldImage(String fieldName, InputStream image) {#setFieldImage-java.lang.String-java.io.InputStream-}
```
public void setFieldImage(String fieldName, InputStream image)
```


Sets image for XFA field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the field. |
| image | java.io.InputStream | Stream which contains image. |

### setFieldImageInternal(String fieldName, System.IO.Stream image) {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public void setFieldImageInternal(String fieldName, System.IO.Stream image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String |  |
| image | com.aspose.ms.System.IO.Stream |  |

### getFieldsWithTextValuesMap() {#getFieldsWithTextValuesMap--}
```
public HashMap<String,String> getFieldsWithTextValuesMap()
```


Returns map with short field name and it's string value for all fields.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> -  HashMap  object
### getXfaField(String path) {#getXfaField-java.lang.String-}
```
public final XfaFieldInteractive getXfaField(String path)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String |  |

**Returns:**
com.aspose.pdf.XfaFieldInteractive
