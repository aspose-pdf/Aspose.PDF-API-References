---
title: "XFA"
linktitle: "XFA"
second_title: "Aspose.PDF for Java API 参考"
description: "表示与 XML Forms Architecture (XFA) 相关的 XML 表单。"
type: docs
weight: 5550
url: /zh/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

表示与 XML Forms Architecture (XFA) 相关的 XML 表单。

## 方法

| 方法 | 描述 |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | 将 XML 值追加到匹配 XPath 表达式的模板节点 |
| [beginCachedUpdates](#beginCachedUpdates--) | 启动缓存更新模式。对 XFA 所做的所有更改将被缓存，并在调用 EndCachedUpdates 时保存到文档结构中。这样可以通过避免在对 XFA 进行大量更改时重复将 XML 包保存到文档中，从而提升性能。 |
| [endCachedUpdates](#endCachedUpdates--) | 结束缓存更新并将所有数据保存到文档结构中。 |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | 展平 XFA 表单字段。 |
| [get_Item](#get_Item-java.lang.String-) | 获取数据节点值，依据 {@code path}。 |
| [getConfig](#getConfig--) | XFA 表单的 XFA Config 组件。 |
| [getDatasets](#getDatasets--) | XFA 表单的 XFA Datasets 组件。 |
| [getFieldNames](#getFieldNames--) | 表单模板中字段名称的列表。 |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> 返回包含所有字段的短字段名及其字符串值的映射。 </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | 返回 XFA 字段模板的 XML 节点。 |
| [getFieldTemplates](#getFieldTemplates--) | 返回 XFA 表单上所有字段模板的列表。 |
| [getForm](#getForm--) | 获取 XFA 表单的 XFA Form Component。 |
| [getNamespaceManager_](#getNamespaceManager_--) | 获取 XFA 表单的命名空间。已定义以下命名空间："data" 用于表单数据，"tpl" 用于表单模板。 |
| [getNamespaceManager](#getNamespaceManager--) | 返回使用模板和数据的命名空间管理器。 |
| [getTemplate](#getTemplate--) | XFA 表单的 XFA Template 组件。 |
| [getXDP](#getXDP--) | XML 数据包（包含在外围 XML 容器中的所有 XFA 表单组件）。 |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | 获取数据节点值，依据 {@code path}。 |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | 为 XFA 字段设置图像。 |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | 尝试从 XFA 表单导出计算脚本。否则返回空字符串； |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
将 XML 值追加到匹配 XPath 表达式的模板节点

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

启动缓存更新模式。对 XFA 所做的所有更改将被缓存，并在调用 EndCachedUpdates 时保存到文档结构中。这样可以通过避免在对 XFA 进行大量更改时重复将 XML 包保存到文档中，从而提升性能。

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

结束缓存更新并将所有数据保存到文档结构中。

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
展平 XFA 表单字段。

### get_Item {#get_Item-java.lang.String-}
获取数据节点值，依据 {@code path}。

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

XFA 表单的 XFA Config 组件。

**Returns:**
XmlNode 对象

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

XFA 表单的 XFA Datasets 组件。

**Returns:**
XmlNode 对象

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

表单模板中字段名称的列表。

**Returns:**
String 值数组

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> 返回包含所有字段的短字段名及其字符串值的映射。 </p>

**Returns:**
{@code HashMap<String, String>} 对象

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
返回 XFA 字段模板的 XML 节点。

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

返回 XFA 表单上所有字段模板的列表。

**Returns:**
字段模板列表。

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

获取 XFA 表单的 XFA Form Component。

**Returns:**
XmlNode 对象

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

获取 XFA 表单的命名空间。已定义以下命名空间："data" 用于表单数据，"tpl" 用于表单模板。

**Returns:**
XmlNamespaceManager 对象

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

返回使用模板和数据的命名空间管理器。

**Returns:**
XmlNamespaceManager 对象

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

XFA 表单的 XFA Template 组件。

**Returns:**
XmlNode 对象

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

XML 数据包（包含在外围 XML 容器中的所有 XFA 表单组件）。

**Returns:**
XmlDocument 对象

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
获取数据节点值，依据 {@code path}。

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
为 XFA 字段设置图像。

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
尝试从 XFA 表单导出计算脚本。否则返回空字符串；
