---
title: XFA
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示有关 XML 表单体系结构 XFA 的 XML 表单。
type: docs
weight: 406
url: /zh/java/com.aspose.pdf/xfa/
---
**遗产：**
java.lang.Object
```
public final class XFA
```

表示有关 XML 表单体系结构 (XFA) 的 XML 表单。
## 方法

| 方法 | 描述 |
| --- | --- |
| [beginCachedUpdates()](#beginCachedUpdates--) | 启动缓存更新模式。 |
| [endCachedUpdates()](#endCachedUpdates--) | 结束缓存更新并将所有数据保存到文档结构中。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flattenXfaField(System.Xml.XmlNode field)](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | 展平 XFA 表单的字段。 |
| [getClass()](#getClass--) |  |
| [getConfig()](#getConfig--) | XFA 表单的 XFA 配置组件。 |
| [getDatasets()](#getDatasets--) | XFA 表单的 XFA 数据集组件。 |
| [getFieldNames()](#getFieldNames--) | 表单模板中的字段名称列表。 |
| [getFieldTemplate(String fieldName)](#getFieldTemplate-java.lang.String-) | 返回 XFA 字段模板的 XML 节点。 |
| [getFieldTemplates()](#getFieldTemplates--) | 返回 XFA 表单上所有字段模板的列表。 |
| [getFieldsWithTextValuesMap()](#getFieldsWithTextValuesMap--) | 返回具有短字段名称的映射及其所有字段的字符串值。 |
| [getForm()](#getForm--) | 获取 XFA 表单的 XFA 表单组件。 |
| [getNamespaceManager()](#getNamespaceManager--) | 返回带有用于模板和数据的命名空间的命名空间管理器。 |
| [getNamespaceManager_()](#getNamespaceManager---) | 获取 XFA 表单的命名空间。 |
| [getTemplate()](#getTemplate--) | XFA 表单的 XFA 模板组件。 |
| [getXDP()](#getXDP--) | XML 数据包（周围 XML 容器中的所有 XFA 表单组件）。 |
| [getXfaField(String path)](#getXfaField-java.lang.String-) |  |
| [get_Item(String path)](#get-Item-java.lang.String-) | 根据路径获取数据节点值。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFieldImage(String fieldName, InputStream image)](#setFieldImage-java.lang.String-java.io.InputStream-) | 为 XFA 字段设置图像。 |
| [setFieldImageInternal(String fieldName, System.IO.Stream image)](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [set_Item(String path, String value)](#set-Item-java.lang.String-java.lang.String-) | 根据路径获取数据节点值。 |
| [toString()](#toString--) |  |
| [tryGetTemplateString(String value)](#tryGetTemplateString-java.lang.String-) | 尝试从 XFA 表单导出计算脚本。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### beginCachedUpdates() {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```


启动缓存更新模式。对 XFA 所做的所有更改都将被缓存并保存到调用 EndCachedUpdates 时的文档结构中。当对 XFA 进行大量更改时，这可以通过避免将 XML 数据包保存到文档中的冗余操作来改进预制。

### endCachedUpdates() {#endCachedUpdates--}
```
public void endCachedUpdates()
```


结束缓存更新并将所有数据保存到文档结构中。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### flattenXfaField(System.Xml.XmlNode field) {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
```
public static void flattenXfaField(System.Xml.XmlNode field)
```


展平 XFA 表单的字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | com.aspose.ms.System.Xml.XmlNode | XFA 表单字段节点。 |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getConfig() {#getConfig--}
```
public System.Xml.XmlNode getConfig()
```


XFA 表单的 XFA 配置组件。

**退货：**
com.aspose.ms.System.Xml.XmlNode - XmlNode 对象
### getDatasets() {#getDatasets--}
```
public System.Xml.XmlNode getDatasets()
```


XFA 表单的 XFA 数据集组件。

**退货：**
com.aspose.ms.System.Xml.XmlNode - XmlNode 对象
### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


表单模板中的字段名称列表。

**退货：**
java.lang.字符串[] - 字符串值数组
### getFieldTemplate(String fieldName) {#getFieldTemplate-java.lang.String-}
```
public System.Xml.XmlNode getFieldTemplate(String fieldName)
```


返回 XFA 字段模板的 XML 节点。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 必须找到模板的字段的路径。 |

**退货：**
com.aspose.ms.System.Xml.XmlNode - 带有字段模板的 XL 节点。
### getFieldTemplates() {#getFieldTemplates--}
```
public System.Xml.XmlNodeList getFieldTemplates()
```


返回 XFA 表单上所有字段模板的列表。

**退货：**
com.aspose.ms.System.Xml.XmlNodeList - 字段模板列表。
### getFieldsWithTextValuesMap() {#getFieldsWithTextValuesMap--}
```
public HashMap<String,String> getFieldsWithTextValuesMap()
```


返回具有短字段名称的映射及其所有字段的字符串值。

**退货：**
java.util.HashMap<java.lang.String,java.lang.String> - HashMap 对象
### getForm() {#getForm--}
```
public System.Xml.XmlNode getForm()
```


获取 XFA 表单的 XFA 表单组件。

**退货：**
com.aspose.ms.System.Xml.XmlNode - XmlNode 对象
### getNamespaceManager() {#getNamespaceManager--}
```
public System.Xml.XmlNamespaceManager getNamespaceManager()
```


返回带有用于模板和数据的命名空间的命名空间管理器。

**退货：**
com.aspose.ms.System.Xml.XmlNamespaceManager - XmlNamespaceManager 对象
### getNamespaceManager_() {#getNamespaceManager---}
```
public System.Xml.XmlNamespaceManager getNamespaceManager_()
```


获取 XFA 表单的命名空间。定义了以下命名空间：表单数据的“数据”和表单模板的“tpl”。

**退货：**
com.aspose.ms.System.Xml.XmlNamespaceManager - XmlNamespaceManager 对象
### getTemplate() {#getTemplate--}
```
public System.Xml.XmlNode getTemplate()
```


XFA 表单的 XFA 模板组件。

**退货：**
com.aspose.ms.System.Xml.XmlNode - XmlNode 对象
### getXDP() {#getXDP--}
```
public System.Xml.XmlDocument getXDP()
```


XML 数据包（周围 XML 容器中的所有 XFA 表单组件）。

**退货：**
com.aspose.ms.System.Xml.XmlDocument - XmlDocument 对象
### getXfaField(String path) {#getXfaField-java.lang.String-}
```
public final XfaFieldInteractive getXfaField(String path)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String |  |

**退货：**
com.aspose.pdf.XfaFieldInteractive
### get_Item(String path) {#get-Item-java.lang.String-}
```
public String get_Item(String path)
```


根据路径获取数据节点值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 数据节点路径，例如 form1[0].子窗体1[0].子窗体2[0].子窗体3[0].文本域[0]。即使数据只包含每个节点的单次出现，也要确保包括索引，即写 node1[0].node2[0]... 而不是 node1.node2... |

**退货：**
java.lang.String - 数据节点值。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setFieldImage(String fieldName, InputStream image) {#setFieldImage-java.lang.String-java.io.InputStream-}
```
public void setFieldImage(String fieldName, InputStream image)
```


为 XFA 字段设置图像。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段名称。 |
| image | java.io.InputStream | 包含图像的流。 |

### setFieldImageInternal(String fieldName, System.IO.Stream image) {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public void setFieldImageInternal(String fieldName, System.IO.Stream image)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String |  |
| image | com.aspose.ms.System.IO.Stream |  |

### set_Item(String path, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public void set_Item(String path, String value)
```


根据路径获取数据节点值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | java.lang.String | 字符串值 |
| value | java.lang.String | 字符串值 |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### tryGetTemplateString(String value) {#tryGetTemplateString-java.lang.String-}
```
public String tryGetTemplateString(String value)
```


尝试从 XFA 表单导出计算脚本。否则返回空字符串；

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 标签名称 |

**退货：**
java.lang.String - 字符串实例
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
