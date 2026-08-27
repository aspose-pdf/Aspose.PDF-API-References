---
title: "表单"
linktitle: "表单"
second_title: "Aspose.PDF for Java API 参考"
description: "表示表单对象的类。"
type: docs
weight: 1740
url: /zh/java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object，com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

表示表单对象的类。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | 构造函数 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | 在表单上添加字段。 |
| [add](#add-com.aspose.pdf.Field-int-) | 在表单上添加字段。 |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | 向表单添加新字段；如果该字段已放置在其他表单或此表单上，则会创建字段的副本。 |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | 在表单上添加字段。 |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | 在文档的指定页面的指定位置添加字段的附加外观。 |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | 在文档的指定页面添加字段的附加外观。 |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | 将表单的 XFA 设置为指定值。 |
| [clear](#clear--) | 删除表单中的所有字段。此功能不受支持。 |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | 确定字段是否出现在表单上。 |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | 将放置在表单上的字段复制到数组中。 |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | 将表单的字段复制到数组中。 |
| [delete](#delete-com.aspose.pdf.Field-) | 从表单中删除字段。 |
| [delete](#delete-java.lang.String-) | 按名称从表单中删除字段。 |
| [flatten](#flatten--) | 移除所有静态表单字段并将其值直接放置在页面上。 |
| [get_Item](#get_Item-int-) | 通过字段索引获取表单的字段。 |
| [get_Item](#get_Item-java.lang.String-) | 通过字段名称获取表单的字段。如果未找到该字段则抛出异常。 |
| [get_xfa](#get_xfa--) | 仅供内部使用 |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | 按字段名称搜索字段。如果未找到字段则返回 null。 |
| [getAutoRecalculate](#getAutoRecalculate--) | 如果设置为 true，则在任何字段更改时所有表单字段都会重新计算。默认值为 true。为了在填充大量计算字段的表单时提升性能，可将其设为 false。 |
| [getAutoRestoreForm](#getAutoRestoreForm--) | 如果设置，则在注释中出现的缺失表单字段将自动创建。 |
| [getDefaultAppearance](#getDefaultAppearance--) | 获取表单的默认外观（描述表单字段默认字体、文本大小和颜色的对象）。 |
| [getDefaultResources](#getDefaultResources--) | 获取放置在此表单上的默认资源。 |
| [getDocument](#getDocument--) | 仅供内部使用 |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | 如果此属性为 true，则会为必需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。之所以引入此属性，是因为在将 Xfa 表单表示转换为标准时缺少 exclGroup 的对应实现。默认值为 false。 |
| [getFields](#getFields--) | 获取层次结构表单最低层级中所有字段的列表。 |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | 返回位于指定矩形内的字段。 |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | 如果此属性为 true，则在将 XFA 表单转换为标准表单期间会忽略 NeedsRendering 键的值。默认值为 false。 |
| [getNeedsRendering](#getNeedsRendering--) | 获取一个值，指示文档是否需要移除动态 XFA 表单。引入此属性是为了确定在 XFA 表单存在且 {@code NeedsRendering}({@link #getNeedsRendering}) 为 false 的情况下，是否应使用 {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) 来移除 XFA 表单。 |
| [getRemovePermission](#getRemovePermission--) | 如果此属性为 true，则在将动态文档转换为标准文档后，pdf 文档中的 "Perms" 字典将被移除。"Perms" 字典可能包含会干扰 Adobe Acrobat Reader 中必填字段选择显示的规则。默认值为 false。 |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | 如果设置，则文档包含的签名可能会在文件以改变其先前内容的方式保存（写入）时失效，而不是增量更新。 |
| [getSignaturesExist](#getSignaturesExist--) | 如果设置，则文档至少包含一个签名字段。 |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | 表单可以包含签名信息，即可以是已签名或未签名。表单的视图有时必须取决于表单是否已签名。此属性告知表单转换器（例如在将 XFA 表单转换为标准表单期间），结果表单应以已签名还是未签名的方式呈现。 |
| [getSyncRoot](#getSyncRoot--) | 返回同步对象。 |
| [getType](#getType--) | 获取表单的类型。可能的取值有：Standard、Static、Dynamic。 |
| [getXFA](#getXFA--) | 获取表单的 XFA 数据（如果存在）。 |
| [hasField](#hasField-com.aspose.pdf.Field-) | 检查表单是否已经拥有指定字段。 |
| [hasField](#hasField-java.lang.String-) | 确定具有指定名称的字段是否已添加到表单中。 |
| [hasField](#hasField-java.lang.String-boolean-) | 确定具有指定名称的字段是否已添加到表单中，并能够查看子层级字段的层次结构。 |
| [hasXfa](#hasXfa--) | 获取一个值，指示文档是否包含 XFA 表单。引入此属性是为了确定在 XFA 表单存在且 {@code NeedsRendering}({@link #getNeedsRendering}) 为 false 的情况下，是否应使用 {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) 来移除 XFA 表单。 |
| [isReadOnly](#isReadOnly--) | 确定集合是否为只读。始终返回 false。 |
| [isSynchronized](#isSynchronized--) | 如果对象是线程安全的，则返回 true。 |
| [iterator](#iterator--) | 获取表单字段的枚举。 |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * 将 PDF 表单字段导出为 JSON 格式并将结果写入提供的流。 / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | 从表单中删除字段。 |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | 移除指定索引处字段的外观。如果只剩下一个子外观，方法会将其嵌入到字段中。 |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | 如果设置为 true，则在任何字段更改时所有表单字段都会重新计算。默认值为 true。为了在填充大量计算字段的表单时提升性能，可将其设为 false。 |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | 如果设置，则在注释中出现的缺失表单字段将自动创建。 |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | 允许设置字段计算的顺序。 |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | 设置表单的默认外观（描述表单字段默认字体、文本大小和颜色的对象）。 |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | 如果此属性为 true，则会为必需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。之所以引入此属性，是因为在将 Xfa 表单表示转换为标准时缺少 exclGroup 的对应实现。默认值为 false。 |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | 如果此属性为 true，则在将 XFA 表单转换为标准表单期间会忽略 NeedsRendering 键的值。默认值为 false。 |
| [setRemovePermission](#setRemovePermission-boolean-) | 如果此属性为 true，则在将动态文档转换为标准文档后，pdf 文档中的 "Perms" 字典将被移除。"Perms" 字典可能包含会干扰 Adobe Acrobat Reader 中必填字段选择显示的规则。默认值为 false。 |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | 如果设置，则文档包含的签名可能会在文件以改变其先前内容的方式保存（写入）时失效，而不是增量更新。 |
| [setSignaturesExist](#setSignaturesExist-boolean-) | 如果设置，则文档至少包含一个签名字段。 |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | 表单可以包含签名信息，即可以是已签名或未签名。表单的视图有时必须取决于表单是否已签名。此属性告知表单转换器（例如在将 XFA 表单转换为标准表单期间），结果表单应以已签名还是未签名的方式呈现。 |
| [setType](#setType-com.aspose.pdf.FormType-) | 获取表单的类型。可能的取值有：Standard、Static、Dynamic。 |
| [size](#size--) | 获取此表单上字段的数量。 |

### Form {#Form-com.aspose.pdf.IDocument-}
构造函数

### add {#add-com.aspose.pdf.Field-}
在表单上添加字段。

### add {#add-com.aspose.pdf.Field-int-}
在表单上添加字段。

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
向表单添加新字段；如果该字段已放置在其他表单或此表单上，则会创建字段的副本。

### add {#add-com.aspose.pdf.WidgetAnnotation-}
在表单上添加字段。

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
在文档的指定页面的指定位置添加字段的附加外观。

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
在文档的指定页面添加字段的附加外观。

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
将表单的 XFA 设置为指定值。

### clear {#clear--}
```
public void clear()
```

删除表单中的所有字段。此功能不受支持。

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
确定字段是否出现在表单上。

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
将放置在表单上的字段复制到数组中。

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
将表单的字段复制到数组中。

### delete {#delete-com.aspose.pdf.Field-}
从表单中删除字段。

### delete {#delete-java.lang.String-}
按名称从表单中删除字段。

### flatten {#flatten--}
```
public void flatten()
```

移除所有静态表单字段并将其值直接放置在页面上。

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

通过字段索引获取表单的字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  | 字段的索引。 |

**Returns:**
检索到的字段。

### get_Item {#get_Item-java.lang.String-}
通过字段名称获取表单的字段。如果未找到该字段则抛出异常。

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

仅供内部使用

**Returns:**
XFA 对象

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 |  |  |

### get {#get-java.lang.String-}
按字段名称搜索字段。如果未找到字段则返回 null。

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

如果设置为 true，则在任何字段更改时所有表单字段都会重新计算。默认值为 true。为了在填充大量计算字段的表单时提升性能，可将其设为 false。

**Returns:**
布尔值

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

如果设置，则在注释中出现的缺失表单字段将自动创建。

**Returns:**
布尔值

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

获取表单的默认外观（描述表单字段默认字体、文本大小和颜色的对象）。

**Returns:**
DefaultAppearance 对象

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

获取放置在此表单上的默认资源。

**Returns:**
Resources 值

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

仅供内部使用

**Returns:**
IDocument 对象

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

如果此属性为 true，则会为必需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。之所以引入此属性，是因为在将 Xfa 表单表示转换为标准时缺少 exclGroup 的对应实现。默认值为 false。

**Returns:**
布尔值

### getFields {#getFields--}
```
public Field [] getFields()
```

获取层次结构表单最低层级中所有字段的列表。

**Returns:**
包含找到的字段的数组。

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
返回位于指定矩形内的字段。

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

如果此属性为 true，则在将 XFA 表单转换为标准表单期间会忽略 NeedsRendering 键的值。默认值为 false。

**Returns:**
布尔值

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

获取一个值，指示文档是否需要移除动态 XFA 表单。引入此属性是为了确定在 XFA 表单存在且 {@code NeedsRendering}({@link #getNeedsRendering}) 为 false 的情况下，是否应使用 {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) 来移除 XFA 表单。

**Returns:**
布尔值

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

如果此属性为 true，则在将动态文档转换为标准文档后，pdf 文档中的 "Perms" 字典将被移除。"Perms" 字典可能包含会干扰 Adobe Acrobat Reader 中必填字段选择显示的规则。默认值为 false。

**Returns:**
布尔值

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

如果设置，则文档包含的签名可能会在文件以改变其先前内容的方式保存（写入）时失效，而不是增量更新。

**Returns:**
布尔值

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

如果设置，则文档至少包含一个签名字段。

**Returns:**
布尔值

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

表单可以包含签名信息，即可以是已签名或未签名。表单的视图有时必须取决于表单是否已签名。此属性告知表单转换器（例如在将 XFA 表单转换为标准表单期间），结果表单应以已签名还是未签名的方式呈现。

**Returns:**
SignDependentElementsRenderingModes 元素 @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

返回同步对象。

**Returns:**
用于同步的对象

### getType {#getType--}
```
public FormType getType()
```

获取表单的类型。可能的取值有：Standard、Static、Dynamic。

**Returns:**
FormType 值 @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

获取表单的 XFA 数据（如果存在）。

**Returns:**
XFA 值

### hasField {#hasField-com.aspose.pdf.Field-}
检查表单是否已经拥有指定字段。

### hasField {#hasField-java.lang.String-}
确定具有指定名称的字段是否已添加到表单中。

### hasField {#hasField-java.lang.String-boolean-}
确定具有指定名称的字段是否已添加到表单中，并能够查看子层级字段的层次结构。

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

获取一个值，指示文档是否包含 XFA 表单。引入此属性是为了确定在 XFA 表单存在且 {@code NeedsRendering}({@link #getNeedsRendering}) 为 false 的情况下，是否应使用 {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) 来移除 XFA 表单。

**Returns:**
布尔值

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

确定集合是否为只读。始终返回 false。

**Returns:**
布尔值

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

如果对象是线程安全的，则返回 true。

**Returns:**
布尔值

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

获取表单字段的枚举。

**Returns:**
字段枚举器。

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * 将 PDF 表单字段导出为 JSON 格式并将结果写入提供的流。 / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
从表单中删除字段。

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
移除指定索引处字段的外观。如果只剩下一个子外观，方法会将其嵌入到字段中。

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

如果设置为 true，则在任何字段更改时所有表单字段都会重新计算。默认值为 true。为了在填充大量计算字段的表单时提升性能，可将其设为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

如果设置，则在注释中出现的缺失表单字段将自动创建。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
允许设置字段计算的顺序。

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
设置表单的默认外观（描述表单字段默认字体、文本大小和颜色的对象）。

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

如果此属性为 true，则会为必需的 Xfa exclGroup 元素容器绘制额外的红色边界矩形。之所以引入此属性，是因为在将 Xfa 表单表示转换为标准时缺少 exclGroup 的对应实现。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

如果此属性为 true，则在将 XFA 表单转换为标准表单期间会忽略 NeedsRendering 键的值。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

如果此属性为 true，则在将动态文档转换为标准文档后，pdf 文档中的 "Perms" 字典将被移除。"Perms" 字典可能包含会干扰 Adobe Acrobat Reader 中必填字段选择显示的规则。默认值为 false。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

如果设置，则文档包含的签名可能会在文件以改变其先前内容的方式保存（写入）时失效，而不是增量更新。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

如果设置，则文档至少包含一个签名字段。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | 布尔值 |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

表单可以包含签名信息，即可以是已签名或未签名。表单的视图有时必须取决于表单是否已签名。此属性告知表单转换器（例如在将 XFA 表单转换为标准表单期间），结果表单应以已签名还是未签名的方式呈现。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes 元素 @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
获取表单的类型。可能的取值有：Standard、Static、Dynamic。

### size {#size--}
```
public final int size()
```

获取此表单上字段的数量。

**Returns:**
int 值
