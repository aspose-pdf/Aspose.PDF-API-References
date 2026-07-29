---
title: "XFA"
linktitle: "XFA"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل نموذج XML فيما يتعلق بهندسة نماذج XML (XFA)."
type: docs
weight: 5550
url: /ar/java/com.aspose.pdf/xfa/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XFA

```
public final class XFA extends Object
```

يمثل نموذج XML فيما يتعلق بهندسة نماذج XML (XFA).

## الطرق

| طريقة | الوصف |
| --- | --- |
| [appendToTemplate](#appendToTemplate-java.lang.String-java.lang.String-) | إلحاق قيمة XML بالعقدة في القالب التي تطابق تعبير XPath |
| [beginCachedUpdates](#beginCachedUpdates--) | ابدأ وضع التحديثات المؤقتة. سيتم تخزين جميع التغييرات التي تُجرى على XFA مؤقتًا وحفظها في بنية المستند عند استدعاء EndCachedUpdates. يتيح ذلك تحسين الأداء عن طريق تجنب العمليات المتكررة عند حفظ حزم XML في المستند عندما يتم إجراء الكثير من التغييرات على XFA. |
| [endCachedUpdates](#endCachedUpdates--) | ينهي التحديثات المؤقتة ويحفظ جميع البيانات في بنية المستند. |
| [flattenXfaField](#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-) | تسطيح حقل نموذج XFA. |
| [get_Item](#get_Item-java.lang.String-) | يحصل على قيمة عقدة البيانات وفقًا لـ {@code path}. |
| [getConfig](#getConfig--) | مكوّن تكوين XFA لنموذج XFA. |
| [getDatasets](#getDatasets--) | مكوّن مجموعات بيانات XFA لنموذج XFA. |
| [getFieldNames](#getFieldNames--) | قائمة بأسماء الحقول في قالب النموذج. |
| [getFieldsWithTextValuesMap](#getFieldsWithTextValuesMap--) | <p> إرجاع خريطة بالاسم المختصر للحقول وقيمتها النصية لجميع الحقول. </p> |
| [getFieldTemplate](#getFieldTemplate-java.lang.String-) | إرجاع عقدة XML لحقل XFA في القالب. |
| [getFieldTemplates](#getFieldTemplates--) | إرجاع قائمة بجميع قوالب الحقول في نموذج XFA. |
| [getForm](#getForm--) | يحصل على مكوّن نموذج XFA لنموذج XFA. |
| [getNamespaceManager_](#getNamespaceManager_--) | يحصل على مساحة الاسم لنموذج XFA. تم تعريف مساحات الاسم التالية: "data" لبيانات النموذج و "tpl" لقالب النموذج. |
| [getNamespaceManager](#getNamespaceManager--) | إرجاع مدير مساحة الاسم مع مساحات الاسم المستخدمة للقالب والبيانات. |
| [getTemplate](#getTemplate--) | مكوّن قالب XFA لنموذج XFA. |
| [getXDP](#getXDP--) | حزمة بيانات XML (جميع مكوّنات نموذج XFA داخل حاوية XML محيطة). |
| [getXfaField](#getXfaField-java.lang.String-) |  |
| [set_Item](#set_Item-java.lang.String-java.lang.String-) | يحصل على قيمة عقدة البيانات وفقًا لـ {@code path}. |
| [setFieldImage](#setFieldImage-java.lang.String-java.io.InputStream-) | يضبط الصورة لحقل XFA. |
| [setFieldImageInternal](#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-) |  |
| [tryGetTemplateString](#tryGetTemplateString-java.lang.String-) | يحاول تصدير سكريبت الحساب من نموذج XFA. وإلا يُرجع سلسلة فارغة؛ |

### appendToTemplate {#appendToTemplate-java.lang.String-java.lang.String-}
إلحاق قيمة XML بالعقدة في القالب التي تطابق تعبير XPath

### beginCachedUpdates {#beginCachedUpdates--}
```
public void beginCachedUpdates()
```

ابدأ وضع التحديثات المؤقتة. سيتم تخزين جميع التغييرات التي تُجرى على XFA مؤقتًا وحفظها في بنية المستند عند استدعاء EndCachedUpdates. يتيح ذلك تحسين الأداء عن طريق تجنب العمليات المتكررة عند حفظ حزم XML في المستند عندما يتم إجراء الكثير من التغييرات على XFA.

### endCachedUpdates {#endCachedUpdates--}
```
public void endCachedUpdates()
```

ينهي التحديثات المؤقتة ويحفظ جميع البيانات في بنية المستند.

### flattenXfaField {#flattenXfaField-com.aspose.ms.System.Xml.XmlNode-}
تسطيح حقل نموذج XFA.

### get_Item {#get_Item-java.lang.String-}
يحصل على قيمة عقدة البيانات وفقًا لـ {@code path}.

### getConfig {#getConfig--}
```
public com.aspose.ms.System.Xml.XmlNode getConfig()
```

مكوّن تكوين XFA لنموذج XFA.

**Returns:**
كائن XmlNode

### getDatasets {#getDatasets--}
```
public com.aspose.ms.System.Xml.XmlNode getDatasets()
```

مكوّن مجموعات بيانات XFA لنموذج XFA.

**Returns:**
كائن XmlNode

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

قائمة بأسماء الحقول في قالب النموذج.

**Returns:**
مصفوفة من قيم String

### getFieldsWithTextValuesMap {#getFieldsWithTextValuesMap--}
```
public HashMap < String , String > getFieldsWithTextValuesMap()
```

<p> إرجاع خريطة بالاسم المختصر للحقول وقيمتها النصية لجميع الحقول. </p>

**Returns:**
كائن {@code HashMap<String, String>}

### getFieldTemplate {#getFieldTemplate-java.lang.String-}
إرجاع عقدة XML لحقل XFA في القالب.

### getFieldTemplates {#getFieldTemplates--}
```
public com.aspose.ms.System.Xml.XmlNodeList getFieldTemplates()
```

إرجاع قائمة بجميع قوالب الحقول في نموذج XFA.

**Returns:**
قائمة قوالب الحقول.

### getForm {#getForm--}
```
public com.aspose.ms.System.Xml.XmlNode getForm()
```

يحصل على مكوّن نموذج XFA لنموذج XFA.

**Returns:**
كائن XmlNode

### getNamespaceManager_ {#getNamespaceManager_--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager_()
```

يحصل على مساحة الاسم لنموذج XFA. تم تعريف مساحات الاسم التالية: "data" لبيانات النموذج و "tpl" لقالب النموذج.

**Returns:**
كائن XmlNamespaceManager

### getNamespaceManager {#getNamespaceManager--}
```
public com.aspose.ms.System.Xml.XmlNamespaceManager getNamespaceManager()
```

إرجاع مدير مساحة الاسم مع مساحات الاسم المستخدمة للقالب والبيانات.

**Returns:**
كائن XmlNamespaceManager

### getTemplate {#getTemplate--}
```
public com.aspose.ms.System.Xml.XmlNode getTemplate()
```

مكوّن قالب XFA لنموذج XFA.

**Returns:**
كائن XmlNode

### getXDP {#getXDP--}
```
public com.aspose.ms.System.Xml.XmlDocument getXDP()
```

حزمة بيانات XML (جميع مكوّنات نموذج XFA داخل حاوية XML محيطة).

**Returns:**
كائن XmlDocument

### getXfaField {#getXfaField-java.lang.String-}


### set_Item {#set_Item-java.lang.String-java.lang.String-}
يحصل على قيمة عقدة البيانات وفقًا لـ {@code path}.

### setFieldImage {#setFieldImage-java.lang.String-java.io.InputStream-}
يضبط الصورة لحقل XFA.

### setFieldImageInternal {#setFieldImageInternal-java.lang.String-com.aspose.ms.System.IO.Stream-}


### tryGetTemplateString {#tryGetTemplateString-java.lang.String-}
يحاول تصدير سكريبت الحساب من نموذج XFA. وإلا يُرجع سلسلة فارغة؛
