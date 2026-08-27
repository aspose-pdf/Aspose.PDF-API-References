---
title: "FileSpecification"
linktitle: "FileSpecification"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تمثل ملفًا مضمّنًا."
type: docs
weight: 1510
url: /ar/java/com.aspose.pdf/filespecification/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FileSpecification

```
public final class FileSpecification extends Object
```

فئة تمثل ملفًا مضمّنًا.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FileSpecification](#FileSpecification--) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-) | إنشاء مواصفة ملف فارغة جديدة. |
| [FileSpecification](#FileSpecification-java.lang.String-java.lang.String-) | إنشاء مواصفة ملف فارغة جديدة. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAFRelationship](#getAFRelationship--) | العلاقة المرتبطة بالملف. |
| [getCollectionItem](#getCollectionItem--) | يحصل على عنصر من مجموعة مواصفة الملف. |
| [getContents](#getContents--) | يحصل على ملف المحتويات. |
| [getContentsInternal](#getContentsInternal--) | يحصل على ملف المحتويات. |
| [getDescription](#getDescription--) | يحصل على النص المرتبط بمواصفات الملف. |
| [getEncoding](#getEncoding--) | يحصل على تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط. |
| [getEncryptedPayload](#getEncryptedPayload--) | يحصل على الحمولة المشفرة. |
| [getEngineDict](#getEngineDict--) | قاموس PDF يحتوي على معلومات حول الملف. داخلي فقط |
| [getEngineObj](#getEngineObj--) | داخلي فقط |
| [getFileSystem](#getFileSystem--) | يحصل على اسم نظام الملفات. |
| [getMIMEType](#getMIMEType--) | يحصل على النوع الفرعي للملف المضمّن |
| [getName](#getName--) | يحصل على اسم مواصفات الملف. |
| [getParams](#getParams--) | يحصل على معلمات الملف. |
| [getStreamContents](#getStreamContents--) | يحصل على محتوى الملف كتيار. لا يتم تحميل المحتوى في الذاكرة مما يسمح بتقليل استهلاك الذاكرة. لكن هذا التيار لا يدعم التحديد ومخاصية Length. إذا كنت بحاجة إلى هذه الميزات يرجى استخدام خاصية Contents بدلاً من ذلك. |
| [getUnicodeName](#getUnicodeName--) | يحصل على اسم مواصفات الملف بصيغة Unicode. |
| [getValue](#getValue-java.lang.String-) | يحصل على معلمة خاصة بالتطبيق. |
| [isIncludeContents](#isIncludeContents--) | إذا كان صحيحًا، سيتم تضمين محتوى الملف في مواصفات الملف. |
| [setAFRelationship](#setAFRelationship-com.aspose.pdf.AFRelationship-) | العلاقة المرتبطة بالملف. |
| [setContents](#setContents-byte:A-) | يضبط محتوى الملف. |
| [setContents](#setContents-java.io.InputStream-) | يضبط محتوى الملف. |
| [setDescription](#setDescription-java.lang.String-) | يضبط النص المرتبط بمواصفات الملف. |
| [setEncoding](#setEncoding-com.aspose.pdf.FileEncoding-) | يضبط تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط. |
| [setFileSystem](#setFileSystem-java.lang.String-) | يضبط اسم نظام الملفات. |
| [setIncludeContents](#setIncludeContents-boolean-) | إذا كان صحيحًا، سيتم تضمين محتوى الملف في مواصفات الملف. |
| [setMIMEType](#setMIMEType-java.lang.String-) | يضبط نوع MIME. |
| [setName](#setName-java.lang.String-) | يضبط اسم مواصفات الملف. |
| [setParams](#setParams-com.aspose.pdf.FileParams-) | يضبط معلمات الملف. |
| [setUnicodeName](#setUnicodeName-java.lang.String-) | يضبط اسم مواصفات الملف بصيغة Unicode. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | يضبط معلمة خاصة بالتطبيق. |

### FileSpecification {#FileSpecification--}
```
public FileSpecification()
```

إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-java.io.InputStream-java.lang.String-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-com.aspose.pdf.engine.data.IPdfPrimitive-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-com.aspose.ms.System.IO.Stream-java.lang.String-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-java.lang.String-com.aspose.pdf.Annotation-}
إنشاء مواصفة ملف فارغة جديدة.

### FileSpecification {#FileSpecification-java.lang.String-java.lang.String-}
إنشاء مواصفة ملف فارغة جديدة.

### getAFRelationship {#getAFRelationship--}
```
public final AFRelationship getAFRelationship()
```

العلاقة المرتبطة بالملف.

**Returns:**
عنصر AFRelationship

### getCollectionItem {#getCollectionItem--}
```
public final CollectionItem getCollectionItem()
```

يحصل على عنصر من مجموعة مواصفة الملف.

**Returns:**
مثيل CollectionItem

### getContents {#getContents--}
```
public InputStream getContents()
```

يحصل على ملف المحتويات.

**Returns:**
كائن InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

يحصل على ملف المحتويات.

**Returns:**
كائن Stream

### getDescription {#getDescription--}
```
public String getDescription()
```

يحصل على النص المرتبط بمواصفات الملف.

**Returns:**
قيمة سلسلة

### getEncoding {#getEncoding--}
```
public FileEncoding getEncoding()
```

يحصل على تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط.

**Returns:**
قيمة int @see FileEncoding

### getEncryptedPayload {#getEncryptedPayload--}
```
public final EncryptedPayload getEncryptedPayload()
```

يحصل على الحمولة المشفرة.

**Returns:**
مثيل EncryptedPayload

### getEngineDict {#getEngineDict--}
```
public com.aspose.pdf.engine.data.IPdfDictionary getEngineDict()
```

قاموس PDF يحتوي على معلومات حول الملف. داخلي فقط

**Returns:**
كائن IPdfDictionary

### getEngineObj {#getEngineObj--}
```
public com.aspose.pdf.engine.data.IPdfObject getEngineObj()
```

داخلي فقط

**Returns:**
كائن IPdfObject

### getFileSystem {#getFileSystem--}
```
public String getFileSystem()
```

يحصل على اسم نظام الملفات.

**Returns:**
قيمة سلسلة

### getMIMEType {#getMIMEType--}
```
public String getMIMEType()
```

يحصل على النوع الفرعي للملف المضمّن

**Returns:**
قيمة السلسلة

### getName {#getName--}
```
public String getName()
```

يحصل على اسم مواصفات الملف.

**Returns:**
قيمة سلسلة

### getParams {#getParams--}
```
public FileParams getParams()
```

يحصل على معلمات الملف.

**Returns:**
كائن FileParams

### getStreamContents {#getStreamContents--}
```
public InputStream getStreamContents()
```

يحصل على محتوى الملف كتيار. لا يتم تحميل المحتوى في الذاكرة مما يسمح بتقليل استهلاك الذاكرة. لكن هذا التيار لا يدعم التحديد ومخاصية Length. إذا كنت بحاجة إلى هذه الميزات يرجى استخدام خاصية Contents بدلاً من ذلك.

**Returns:**
كائن InputStream

### getUnicodeName {#getUnicodeName--}
```
public String getUnicodeName()
```

يحصل على اسم مواصفات الملف بصيغة Unicode.

**Returns:**
قيمة سلسلة

### getValue {#getValue-java.lang.String-}
يحصل على معلمة خاصة بالتطبيق.

### isIncludeContents {#isIncludeContents--}
```
public boolean isIncludeContents()
```

إذا كان صحيحًا، سيتم تضمين محتوى الملف في مواصفات الملف.

**Returns:**
قيمة منطقية

### setAFRelationship {#setAFRelationship-com.aspose.pdf.AFRelationship-}
العلاقة المرتبطة بالملف.

### setContents {#setContents-byte:A-}
```
public void setContents(byte[] value)
```

يضبط محتوى الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة من البايتات |

### setContents {#setContents-java.io.InputStream-}
يضبط محتوى الملف.

### setDescription {#setDescription-java.lang.String-}
يضبط النص المرتبط بمواصفات الملف.

### setEncoding {#setEncoding-com.aspose.pdf.FileEncoding-}
يضبط تنسيق الترميز. القيم الممكنة: Zip - الملف مضغوط باستخدام ZIP، None - الملف غير مضغوط.

### setFileSystem {#setFileSystem-java.lang.String-}
يضبط اسم نظام الملفات.

### setIncludeContents {#setIncludeContents-boolean-}
```
public void setIncludeContents(boolean value)
```

إذا كان صحيحًا، سيتم تضمين محتوى الملف في مواصفات الملف.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setMIMEType {#setMIMEType-java.lang.String-}
يضبط نوع MIME.

### setName {#setName-java.lang.String-}
يضبط اسم مواصفات الملف.

### setParams {#setParams-com.aspose.pdf.FileParams-}
يضبط معلمات الملف.

### setUnicodeName {#setUnicodeName-java.lang.String-}
يضبط اسم مواصفات الملف بصيغة Unicode.

### setValue {#setValue-java.lang.String-java.lang.String-}
يضبط معلمة خاصة بالتطبيق.
