---
title: Form
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示表单对象的类。
type: docs
weight: 139
url: /zh/java/com.aspose.pdf/form/
---
**遗产：**
java.lang.Object

**所有已实现的接口：**
java.lang.Iterable
```
public final class Form implements Iterable<WidgetAnnotation>
```

表示表单对象的类。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) | 构造函数 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(Field field)](#add-com.aspose.pdf.Field-) | 在表单上添加字段。 |
| [add(Field field, int pageNumber)](#add-com.aspose.pdf.Field-int-) | 在表单上添加字段。 |
| [add(Field field, String partialName, int pageNumber)](#add-com.aspose.pdf.Field-java.lang.String-int-) | 向表单添加新字段；如果此字段已放置在其他或此表单上，则创建字段副本。 |
| [add(WidgetAnnotation field)](#add-com.aspose.pdf.WidgetAnnotation-) | 在表单上添加字段。 |
| [addFieldAppearance(Field field, int pageNumber, Rectangle rect)](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | 将字段的附加外观添加到指定位置文档的指定页面。 |
| [addFieldToAcroForm(Field field)](#addFieldToAcroForm-com.aspose.pdf.Field-) | 将字段的附加外观添加到文档的指定页面。 |
| [assignXfa(System.Xml.XmlDocument xml)](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | 将表单的 XFA 设置为指定值。 |
| [clear()](#clear--) | 从表单中删除所有字段。 |
| [contains(WidgetAnnotation field)](#contains-com.aspose.pdf.WidgetAnnotation-) | 确定字段是否显示在表单上。 |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | 将放置在表单上的字段复制到数组中。 |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) | 将表单的字段复制到数组。 |
| [delete(Field field)](#delete-com.aspose.pdf.Field-) | 从表单中删除字段。 |
| [delete(String fieldName)](#delete-java.lang.String-) | 按名称从表单中删除字段。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | 删除所有静态表单字段并将它们的值直接放在页面上。 |
| [get(int index)](#get-int-) |  |
| [get(String name)](#get-java.lang.String-) | 按字段名称搜索字段。 |
| [getAutoRecalculate()](#getAutoRecalculate--) | 如果设置，当任何字段更改时，将重新计算所有表单字段。 |
| [getAutoRestoreForm()](#getAutoRestoreForm--) | 如果设置，如果缺席的表单字段出现在注释中，将自动创建它们。 |
| [getClass()](#getClass--) |  |
| [getDefaultAppearance()](#getDefaultAppearance--) | 获取表单的默认外观（描述表单字段的默认字体、文本大小和颜色的对象）。 |
| [getDefaultResources()](#getDefaultResources--) | 获取放置在该窗体上的默认资源。 |
| [getDocument()](#getDocument--) | 仅供内部使用 |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | 如果此属性为真，则将为所需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少 exclGroup 的类比。 |
| [getFields()](#getFields--) | 获取层次结构形式最低级别的所有字段的列表。 |
| [getFieldsInRect(Rectangle rect)](#getFieldsInRect-com.aspose.pdf.Rectangle-) | 返回指定矩形内的字段。 |
| [getIgnoreNeedsRendering()](#getIgnoreNeedsRendering--) | 如果此属性为真，则在将 XFA 格式转换为标准格式期间将忽略 NeedsRendering 键的值。 |
| [getRemovePermission()](#getRemovePermission--) | 如果此属性为真，则在将动态文档转换为标准后，“Perms”字典将从 pdf 文档中删除。 |
| [getSignDependentElementsRenderingModeWhenConverted()](#getSignDependentElementsRenderingModeWhenConverted--) | 表单可以包含签名信息，即可以签名或不签名。 |
| [getSignaturesAppendOnly()](#getSignaturesAppendOnly--) | 如果设置，文档包含的签名可能会无效，如果文件以改变其先前内容的方式保存（写入），而不是增量更新。 |
| [getSignaturesExist()](#getSignaturesExist--) | 如果设置，文档至少包含一个签名域。 |
| [getSyncRoot()](#getSyncRoot--) | 返回同步对象。 |
| [getType()](#getType--) | 获取表单的类型。 |
| [getXFA()](#getXFA--) | 获取表单的 XFA 数据（如果存在）。 |
| [get_Item(int index)](#get-Item-int-) | 通过字段索引获取表单的字段。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 通过字段名获取表单的字段。 |
| [get_xfa()](#get-xfa--) | 仅供内部使用 |
| [hasField(Field field)](#hasField-com.aspose.pdf.Field-) | 检查表单是否已经有指定字段。 |
| [hasField(String fieldName)](#hasField-java.lang.String-) | 确定具有指定名称的字段是否已添加到表单中。 |
| [hasXfa()](#hasXfa--) | 如果 hasXfa 则返回 true |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | 确定集合是否为只读。 |
| [isSynchronized()](#isSynchronized--) | 如果对象是线程安全的，则返回 true。 |
| [iterator()](#iterator--) | 获取表单字段的枚举。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(WidgetAnnotation field)](#remove-com.aspose.pdf.WidgetAnnotation-) | 从表单中删除字段。 |
| [setAutoRecalculate(boolean value)](#setAutoRecalculate-boolean-) | 如果设置，当任何字段更改时，将重新计算所有表单字段。 |
| [setAutoRestoreForm(boolean value)](#setAutoRestoreForm-boolean-) | 如果设置，如果缺席的表单字段出现在注释中，将自动创建它们。 |
| [setCalculatedFields(List<Field> value)](#setCalculatedFields-java.util.List-com.aspose.pdf.Field--) | 允许设置字段计算顺序。 |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | 设置表单的默认外观（描述表单字段的默认字体、文本大小和颜色的对象）。 |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | 如果此属性为真，则将为所需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少 exclGroup 的类比。 |
| [setIgnoreNeedsRendering(boolean value)](#setIgnoreNeedsRendering-boolean-) | 如果此属性为真，则在将 XFA 格式转换为标准格式期间将忽略 NeedsRendering 键的值。 |
| [setRemovePermission(boolean value)](#setRemovePermission-boolean-) | 如果此属性为真，则在将动态文档转换为标准后，“Perms”字典将从 pdf 文档中删除。 |
| [setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)](#setSignDependentElementsRenderingModeWhenConverted-int-) | 表单可以包含签名信息，即可以签名或不签名。 |
| [setSignaturesAppendOnly(boolean value)](#setSignaturesAppendOnly-boolean-) | 如果设置，文档包含的签名可能会无效，如果文件以改变其先前内容的方式保存（写入），而不是增量更新。 |
| [setSignaturesExist(boolean value)](#setSignaturesExist-boolean-) | 如果设置，文档至少包含一个签名域。 |
| [setType(int value)](#setType-int-) | 获取表单的类型。 |
| [size()](#size--) | 获取此表单上的字段数。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


构造函数

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | 文档对象 |

### add(Field field) {#add-com.aspose.pdf.Field-}
```
public void add(Field field)
```


在表单上添加字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 必须添加的字段。 |

### add(Field field, int pageNumber) {#add-com.aspose.pdf.Field-int-}
```
public void add(Field field, int pageNumber)
```


在表单上添加字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 必须添加的字段。 |
| pageNumber | int | 将放置添加字段的页面索引。 |

### add(Field field, String partialName, int pageNumber) {#add-com.aspose.pdf.Field-java.lang.String-int-}
```
public Field add(Field field, String partialName, int pageNumber)
```


向表单添加新字段；如果此字段已放置在其他或此表单上，则创建字段副本。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 字段名称。 |
| partialName | java.lang.String | 表单上的字段名称。 |
| pageNumber | int | 将添加字段的页码。 |

**退货：**
[Field](../../com.aspose.pdf/field) - 添加返回的字段。如果创建了该字段的副本，它将被返回。
### add(WidgetAnnotation field) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public boolean add(WidgetAnnotation field)
```


在表单上添加字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | 必须添加的字段。 |

**退货：**
boolean - 布尔值
### addFieldAppearance(Field field, int pageNumber, Rectangle rect) {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
```
public void addFieldAppearance(Field field, int pageNumber, Rectangle rect)
```


将字段的附加外观添加到指定位置文档的指定页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 应在表单上添加外观的字段。 |
| pageNumber | int | 必须放置字段的页码。 |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 将放置字段的矩形。 |

### addFieldToAcroForm(Field field) {#addFieldToAcroForm-com.aspose.pdf.Field-}
```
public void addFieldToAcroForm(Field field)
```


将字段的附加外观添加到文档的指定页面。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 字段对象 |

### assignXfa(System.Xml.XmlDocument xml) {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
```
public void assignXfa(System.Xml.XmlDocument xml)
```


将表单的 XFA 设置为指定值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlDocument | 包含新 XFA 数据的 Xml 文档。 |

### clear() {#clear--}
```
public void clear()
```


从表单中删除所有字段。不支持。

### contains(WidgetAnnotation field) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation field)
```


确定字段是否显示在表单上。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | 要搜索的字段。 |

**退货：**
boolean - 布尔值
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


将放置在表单上的字段复制到数组中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | 必须放置字段的数组。 |
| index | int | 起始索引。 |

### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```


将表单的字段复制到数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) | 要复制的数组。 |
| arrayIndex | int | 复制开始的数组项的索引。 |

### delete(Field field) {#delete-com.aspose.pdf.Field-}
```
public void delete(Field field)
```


从表单中删除字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 必须删除的字段。 |

### delete(String fieldName) {#delete-java.lang.String-}
```
public void delete(String fieldName)
```


按名称从表单中删除字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 必须删除的文件的名称。 |

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
### flatten() {#flatten--}
```
public void flatten()
```


删除所有静态表单字段并将它们的值直接放在页面上。

### get(int index) {#get-int-}
```
public WidgetAnnotation get(int index)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int |  |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation)
### get(String name) {#get-java.lang.String-}
```
public WidgetAnnotation get(String name)
```


按字段名称搜索字段。如果未找到字段，则返回 null。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字段名称。 |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - 字段对象。
### getAutoRecalculate() {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```


如果设置，当任何字段更改时，将重新计算所有表单字段。默认值为真。设置为 false 以在使用大量计算字段填充表单时提高性能。

**退货：**
boolean - 布尔值
### getAutoRestoreForm() {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```


如果设置，如果缺席的表单字段出现在注释中，将自动创建它们。

**退货：**
boolean - 布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


获取表单的默认外观（描述表单字段的默认字体、文本大小和颜色的对象）。

**退货：**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) 默认外观对象
### getDefaultResources() {#getDefaultResources--}
```
public Resources getDefaultResources()
```


获取放置在该窗体上的默认资源。

**退货：**
[Resources](../../com.aspose.pdf/resources) - 资源价值
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


仅供内部使用

**退货：**
[IDocument](../../com.aspose.pdf/idocument) IDocument 对象
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


如果此属性为真，则将为所需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少 exclGroup 的类比。默认情况下为假。

**退货：**
boolean - 布尔值
### getFields() {#getFields--}
```
public Field[] getFields()
```


获取层次结构形式最低级别的所有字段的列表。

**退货：**
com.aspose.pdf.字段[- 包含找到的字段的数组。
### getFieldsInRect(Rectangle rect) {#getFieldsInRect-com.aspose.pdf.Rectangle-}
```
public Field[] getFieldsInRect(Rectangle rect)
```


返回指定矩形内的字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | 应在其中找到字段的矩形。 |

**退货：**
com.aspose.pdf.字段[- 包含找到的字段的数组。
### getIgnoreNeedsRendering() {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```


如果此属性为真，则在将 XFA 格式转换为标准格式期间将忽略 NeedsRendering 键的值。默认情况下为假。

**退货：**
boolean - 布尔值
### getRemovePermission() {#getRemovePermission--}
```
public boolean getRemovePermission()
```


如果此属性为真，则在将动态文档转换为标准后，“Perms”字典将从 pdf 文档中删除。 “Perms”字典可能包含干扰在 Adobe Acrobat 阅读器中显示必填字段选择的规则。默认情况下为假。

**退货：**
boolean - 布尔值
### getSignDependentElementsRenderingModeWhenConverted() {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```


表单可以包含签名信息，即可以签名或不签名。有时表单的视图必须取决于表单是否已签名。此属性告诉表单的转换器（fe 在将 XFA 表单转换为标准表单期间）是否必须将结果表单呈现为已签名或未签名。

**退货：**
int - SignDependentElementsRenderingModes 元素
### getSignaturesAppendOnly() {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```


如果设置，文档包含的签名可能会无效，如果文件以改变其先前内容的方式保存（写入），而不是增量更新。

**退货：**
boolean - 布尔值
### getSignaturesExist() {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```


如果设置，文档至少包含一个签名域。

**退货：**
boolean - 布尔值
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


返回同步对象。

**退货：**
java.lang.Object - 同步对象
### getType() {#getType--}
```
public int getType()
```


获取表单的类型。可能的值有：标准、静态、动态。

**退货：**
int - FormType 值
### getXFA() {#getXFA--}
```
public XFA getXFA()
```


获取表单的 XFA 数据（如果存在）。

**退货：**
[XFA](../../com.aspose.pdf/xfa) XFA值
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


通过字段索引获取表单的字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 字段的索引。 |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - 检索领域。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


通过字段名获取表单的字段。如果未找到该字段，则抛出异常。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字段名称。 |

**退货：**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - 检索领域。
### get_xfa() {#get-xfa--}
```
public XFA get_xfa()
```


仅供内部使用

**退货：**
[XFA](../../com.aspose.pdf/xfa) - XFA对象
### hasField(Field field) {#hasField-com.aspose.pdf.Field-}
```
public final boolean hasField(Field field)
```


检查表单是否已经有指定字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | 要检查的字段。 |

**退货：**
boolean - 如果将指定的字段名称添加到 Form 则为 true；否则，假的。
### hasField(String fieldName) {#hasField-java.lang.String-}
```
public final boolean hasField(String fieldName)
```


确定具有指定名称的字段是否已添加到表单中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | java.lang.String | 字段的部分名称。 |

**退货：**
boolean - 如果将指定的字段名称添加到 Form 则为 true；否则，假的。
### hasXfa() {#hasXfa--}
```
public boolean hasXfa()
```


如果 hasXfa 则返回 true

**退货：**
boolean - 布尔值
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


确定集合是否为只读。总是返回错误。

**退货：**
boolean - 布尔值
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


如果对象是线程安全的，则返回 true。

**退货：**
boolean - 布尔值
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


获取表单字段的枚举。

**退货：**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - 字段枚举器。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### remove(WidgetAnnotation field) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation field)
```


从表单中删除字段。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | 要删除的字段。 |

**退货：**
boolean - 如果字段被删除则为真。如果在表单上找不到字段，则为 False。
### setAutoRecalculate(boolean value) {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```


如果设置，当任何字段更改时，将重新计算所有表单字段。默认值为真。设置为 false 以在使用大量计算字段填充表单时提高性能。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setAutoRestoreForm(boolean value) {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```


如果设置，如果缺席的表单字段出现在注释中，将自动创建它们。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setCalculatedFields(List<Field> value) {#setCalculatedFields-java.util.List-com.aspose.pdf.Field--}
```
public void setCalculatedFields(List<Field> value)
```


允许设置字段计算顺序。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.Field> | java.util.List 对象。 |

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


设置表单的默认外观（描述表单字段的默认字体、文本大小和颜色的对象）。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance 对象 |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


如果此属性为真，则将为所需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。引入此属性是因为在将 Xfa 表示形式转换为标准期间缺少 exclGroup 的类比。默认情况下为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setIgnoreNeedsRendering(boolean value) {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```


如果此属性为真，则在将 XFA 格式转换为标准格式期间将忽略 NeedsRendering 键的值。默认情况下为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setRemovePermission(boolean value) {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```


如果此属性为真，则在将动态文档转换为标准后，“Perms”字典将从 pdf 文档中删除。 “Perms”字典可能包含干扰在 Adobe Acrobat 阅读器中显示必填字段选择的规则。默认情况下为假。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted) {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```


表单可以包含签名信息，即可以签名或不签名。有时表单的视图必须取决于表单是否已签名。此属性告诉表单的转换器（fe 在将 XFA 表单转换为标准表单期间）是否必须将结果表单呈现为已签名或未签名。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted | int | SignDependentElementsRenderingModes 元素 |

### setSignaturesAppendOnly(boolean value) {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```


如果设置，文档包含的签名可能会无效，如果文件以改变其先前内容的方式保存（写入），而不是增量更新。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setSignaturesExist(boolean value) {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```


如果设置，文档至少包含一个签名域。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean | 布尔值 |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


获取表单的类型。可能的值有：标准、静态、动态。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 表单类型值 |

### size() {#size--}
```
public final int size()
```


获取此表单上的字段数。

**退货：**
int - 整数值
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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
