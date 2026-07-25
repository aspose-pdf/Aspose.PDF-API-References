---
title: "PdfFileInfo"
linktitle: "PdfFileInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة للوصول إلى المعلومات الوصفية لوثيقة PDF."
type: docs
weight: 490
url: /ar/java/com.aspose.pdf.facades/pdffileinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileInfo, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileInfo

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileInfo extends SaveableFacade
```

يمثل فئة للوصول إلى المعلومات الوصفية لوثيقة PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PdfFileInfo](#PdfFileInfo--) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-com.aspose.pdf.IDocument-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |
| [PdfFileInfo](#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-) | ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | ينشئ الواجهة. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | ينشئ الواجهة. |
| [clearInfo](#clearInfo--) | يمسح جميع معلومات التعريف للوثيقة PDF. |
| [close](#close--) | يغلق جميع الموارد المستخدمة بواسطة هذا المستند. |
| [dispose](#dispose--) | يغلق جميع الموارد المستخدمة بواسطة هذه النسخة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك. |
| [getAuthor](#getAuthor--) | يحصل على معلومات المؤلف للوثيقة PDF. |
| [getCreationDate](#getCreationDate--) | يحصل على معلومات تاريخ الإنشاء للوثيقة PDF. |
| [getCreator](#getCreator--) | يحصل على معلومات المُنشئ للوثيقة PDF. |
| [getDocumentPrivilege](#getDocumentPrivilege--) | يسترجع إعدادات صلاحيات مستند PDF. |
| [getHeader](#getHeader--) | <p> يسترجع المعلومات المخصصة لمستند PDF. </p> |
| [getInputFile](#getInputFile--) | يسترجع ملف الإدخال. |
| [getInputStream](#getInputStream--) | يسترجع تدفق الإدخال. |
| [getKeywords](#getKeywords--) | يسترجع معلومات الكلمات المفتاحية لمستند PDF. |
| [getMetaInfo](#getMetaInfo-java.lang.String-) | يسترجع المعلومات المخصصة لمستند PDF باستخدام اسم الخاصية. إذا لم توجد خاصية تطابق الاسم فسيتم إرجاع سلسلة فارغة. |
| [getModDate](#getModDate--) | يسترجع معلومات تاريخ ModDate لمستند PDF. |
| [getNumberOfPages](#getNumberOfPages--) | يسترجع عدد صفحات المستند. |
| [getPageHeight](#getPageHeight-int-) | يسترجع ارتفاع الصفحة المحددة. |
| [getPageRotation](#getPageRotation-int-) | يسترجع دوران الصفحة المحددة. |
| [getPageWidth](#getPageWidth-int-) | يسترجع عرض الصفحة المحددة. |
| [getPageXOffset](#getPageXOffset-int-) | يسترجع الإزاحة الأفقية لمنطقة عرض الصفحة المحددة. |
| [getPageYOffset](#getPageYOffset-int-) | يسترجع الإزاحة العمودية لمنطقة عرض الصفحة المحددة. |
| [getPasswordType](#getPasswordType--) | يرجع نوع كلمة المرور التي تم تمريرها لإنشاء كائن PdfFileInfo. راجع القيم الممكنة في {@code PasswordType}. لاحظ أن مستند PDF يمكن فتحه باستخدام كل من كلمة مرور المستخدم (أو الفتح) وكلمة مرور المالك (أو الصلاحيات، التحرير). |
| [getPdfVersion](#getPdfVersion--) | يسترجع معلومات الإصدار لمستند PDF. |
| [getProducer](#getProducer--) | يسترجع معلومات المنتج لمستند PDF. |
| [getSubject](#getSubject--) | يسترجع معلومات الموضوع لمستند PDF. |
| [getTitle](#getTitle--) | يسترجع معلومات العنوان لمستند PDF. |
| [getUseStrictValidation](#getUseStrictValidation--) | يستخدم قواعد تحقق صارمة عبر خاصية {@code IsPdfFile}({@link #isPdfFile}). |
| [hasCollection](#hasCollection--) | يرجع true إذا كان ملف الإدخال الحالي ملف 'Portfolio' يحتوي على مجموعة من ملفات PDF. |
| [hasEditPassword](#hasEditPassword--) | يرجع true إذا كانت كلمة المرور مطلوبة لتعديل الصلاحيات أو خاصية أمان المستند. لاحظ أن هذه الخاصية يمكن قراءتها فقط إذا تم توفير كلمة مرور صالحة في مُنشئ {@code PdfFileInfo}. في حالة كون PasswordType هو Inaccessible (يعني أنه تم توفير كلمة مرور غير صالحة) فإن قراءة هذه الخاصية ستفشل مع {@code InvalidPasswordException}. |
| [hasOpenPassword](#hasOpenPassword--) | يرجع true إذا كانت كلمة المرور مطلوبة لفتح مستند PDF محمي بكلمة مرور. |
| [isEncrypted](#isEncrypted--) | يتحقق مما إذا كان مستند PDF مشفرًا. |
| [isPdfFile](#isPdfFile--) | يتحقق مما إذا كان مصدر الإدخال ملف PDF صالح. |
| [save](#save-java.io.OutputStream-) | يحفظ مستند PDF إلى الملف المحدد. |
| [saveNewInfo](#saveNewInfo-java.io.OutputStream-) | احفظ مستند PDF المحدث في الدفق المحدد. |
| [saveNewInfo](#saveNewInfo-java.lang.String-) | احفظ مستند PDF المحدث في الملف المحدد. |
| [saveNewInfoWithXmp](#saveNewInfoWithXmp-java.lang.String-) | يغيّر الخصائص المحددة صراحةً عن طريق تعيين معلومات الملف، وتبقى الخصائص الأخرى كما هي. |
| [setAuthor](#setAuthor-java.lang.String-) | يضبط معلومات المؤلف لمستند PDF. |
| [setCreationDate](#setCreationDate-java.lang.String-) | يضبط معلومات تاريخ الإنشاء لمستند PDF. |
| [setCreator](#setCreator-java.lang.String-) | يضبط معلومات المُنشئ لمستند PDF. |
| [setHeader](#setHeader-java.util.Map-) | يضبط المعلومات المخصصة لمستند PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | يضبط ملف الإدخال. |
| [setInputStream](#setInputStream-java.io.InputStream-) | يضبط دفق الإدخال. |
| [setKeywords](#setKeywords-java.lang.String-) | يضبط معلومات الكلمات المفتاحية لمستند PDF. |
| [setMetaInfo](#setMetaInfo-java.lang.String-java.lang.String-) | يضبط معلومات مخصصة لمستند PDF. |
| [setModDate](#setModDate-java.lang.String-) | يضبط معلومات تاريخ التعديل لمستند PDF. |
| [setSubject](#setSubject-java.lang.String-) | يضبط معلومات الموضوع لمستند PDF. |
| [setTitle](#setTitle-java.lang.String-) | يضبط معلومات العنوان لمستند PDF. |
| [setUseStrictValidation](#setUseStrictValidation-boolean-) | يستخدم قواعد تحقق صارمة عبر خاصية {@code IsPdfFile}({@link #isPdfFile}). |

### PdfFileInfo {#PdfFileInfo--}
```
public PdfFileInfo()
```

ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-com.aspose.pdf.IDocument-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.io.InputStream-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.lang.String-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### PdfFileInfo {#PdfFileInfo-java.lang.String-java.lang.String-com.aspose.pdf.engine.security.impl.handlers.ICustomSecurityHandler-}
ينشئ نسخة جديدة من الفئة com.aspose.pdf.facades.PdfFileInfo بالقيم الافتراضية.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
ينشئ الواجهة.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
ينشئ الواجهة.

### clearInfo {#clearInfo--}
```
public void clearInfo()
```

يمسح جميع معلومات التعريف للوثيقة PDF.

### close {#close--}
```
public void close()
```

يغلق جميع الموارد المستخدمة بواسطة هذا المستند.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

يغلق جميع الموارد المستخدمة بواسطة هذه النسخة. هذه الطريقة مهجورة، استخدم close() بدلاً من ذلك.

### getAuthor {#getAuthor--}
```
public String getAuthor()
```

يحصل على معلومات المؤلف للوثيقة PDF.

**Returns:**
قيمة سلسلة

### getCreationDate {#getCreationDate--}
```
public String getCreationDate()
```

يحصل على معلومات تاريخ الإنشاء للوثيقة PDF.

**Returns:**
قيمة سلسلة

### getCreator {#getCreator--}
```
public String getCreator()
```

يحصل على معلومات المُنشئ للوثيقة PDF.

**Returns:**
قيمة سلسلة

### getDocumentPrivilege {#getDocumentPrivilege--}
```
public DocumentPrivilege getDocumentPrivilege()
```

يسترجع إعدادات صلاحيات مستند PDF.

**Returns:**
إعدادات صلاحيات مستند PDF.

### getHeader {#getHeader--}
```
public Map < String , String > getHeader()
```

<p> يسترجع المعلومات المخصصة لمستند PDF. </p>

**Returns:**
{@code Map<String, String>} كائن

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

يسترجع ملف الإدخال.

**Returns:**
قيمة سلسلة

### getInputStream {#getInputStream--}
```
@Deprecated public InputStream getInputStream()
```

يسترجع تدفق الإدخال.

**Returns:**
كائن InputStream

### getKeywords {#getKeywords--}
```
public String getKeywords()
```

يسترجع معلومات الكلمات المفتاحية لمستند PDF.

**Returns:**
قيمة سلسلة

### getMetaInfo {#getMetaInfo-java.lang.String-}
يسترجع المعلومات المخصصة لمستند PDF باستخدام اسم الخاصية. إذا لم توجد خاصية تطابق الاسم فسيتم إرجاع سلسلة فارغة.

### getModDate {#getModDate--}
```
public String getModDate()
```

يسترجع معلومات تاريخ ModDate لمستند PDF.

**Returns:**
قيمة سلسلة

### getNumberOfPages {#getNumberOfPages--}
```
public int getNumberOfPages()
```

يسترجع عدد صفحات المستند.

**Returns:**
قيمة int

### getPageHeight {#getPageHeight-int-}
```
public float getPageHeight(int pageNum)
```

يسترجع ارتفاع الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNum |  | رقم الصفحة. |

**Returns:**
ارتفاع الصفحة.

### getPageRotation {#getPageRotation-int-}
```
public int getPageRotation(int pageNum)
```

يسترجع دوران الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNum |  | رقم الصفحة. |

**Returns:**
دوران الصفحة. قد تكون القيمة 0،90،180،270.

### getPageWidth {#getPageWidth-int-}
```
public float getPageWidth(int pageNum)
```

يسترجع عرض الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNum |  | رقم الصفحة. |

**Returns:**
عرض الصفحة.

### getPageXOffset {#getPageXOffset-int-}
```
public float getPageXOffset(int pageNum)
```

يسترجع الإزاحة الأفقية لمنطقة عرض الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNum |  | رقم الصفحة. |

**Returns:**
الإزاحة الأفقية من الجانب الأيسر للصفحة.

### getPageYOffset {#getPageYOffset-int-}
```
public float getPageYOffset(int pageNum)
```

يسترجع الإزاحة العمودية لمنطقة عرض الصفحة المحددة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| pageNum |  | رقم الصفحة. |

**Returns:**
الإزاحة العمودية لمنطقة عرض الصفحة.

### getPasswordType {#getPasswordType--}
```
public PasswordType getPasswordType()
```

يرجع نوع كلمة المرور التي تم تمريرها لإنشاء كائن PdfFileInfo. راجع القيم الممكنة في {@code PasswordType}. لاحظ أن مستند PDF يمكن فتحه باستخدام كل من كلمة مرور المستخدم (أو الفتح) وكلمة مرور المالك (أو الصلاحيات، التحرير).

**Returns:**
عنصر PasswordType @see PasswordType

### getPdfVersion {#getPdfVersion--}
```
public String getPdfVersion()
```

يسترجع معلومات الإصدار لمستند PDF.

**Returns:**
سلسلة الإصدار.

### getProducer {#getProducer--}
```
public String getProducer()
```

يسترجع معلومات المنتج لمستند PDF.

**Returns:**
قيمة سلسلة

### getSubject {#getSubject--}
```
public String getSubject()
```

يسترجع معلومات الموضوع لمستند PDF.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public String getTitle()
```

يسترجع معلومات العنوان لمستند PDF.

**Returns:**
قيمة سلسلة

### getUseStrictValidation {#getUseStrictValidation--}
```
public final boolean getUseStrictValidation()
```

يستخدم قواعد تحقق صارمة عبر خاصية {@code IsPdfFile}({@link #isPdfFile}).

**Returns:**
قيمة منطقية

### hasCollection {#hasCollection--}
```
public boolean hasCollection()
```

يرجع true إذا كان ملف الإدخال الحالي ملف 'Portfolio' يحتوي على مجموعة من ملفات PDF.

**Returns:**
قيمة منطقية

### hasEditPassword {#hasEditPassword--}
```
public boolean hasEditPassword()
```

يرجع true إذا كانت كلمة المرور مطلوبة لتعديل الصلاحيات أو خاصية أمان المستند. لاحظ أن هذه الخاصية يمكن قراءتها فقط إذا تم توفير كلمة مرور صالحة في مُنشئ {@code PdfFileInfo}. في حالة كون PasswordType هو Inaccessible (يعني أنه تم توفير كلمة مرور غير صالحة) فإن قراءة هذه الخاصية ستفشل مع {@code InvalidPasswordException}.

**Returns:**
قيمة منطقية

### hasOpenPassword {#hasOpenPassword--}
```
public boolean hasOpenPassword()
```

يرجع true إذا كانت كلمة المرور مطلوبة لفتح مستند PDF محمي بكلمة مرور.

**Returns:**
قيمة منطقية

### isEncrypted {#isEncrypted--}
```
public boolean isEncrypted()
```

يتحقق مما إذا كان مستند PDF مشفرًا.

**Returns:**
قيمة منطقية

### isPdfFile {#isPdfFile--}
```
public boolean isPdfFile()
```

يتحقق مما إذا كان مصدر الإدخال ملف PDF صالح.

**Returns:**
قيمة منطقية

### save {#save-java.io.OutputStream-}
يحفظ مستند PDF إلى الملف المحدد.

### saveNewInfo {#saveNewInfo-java.io.OutputStream-}
احفظ مستند PDF المحدث في الدفق المحدد.

### saveNewInfo {#saveNewInfo-java.lang.String-}
احفظ مستند PDF المحدث في الملف المحدد.

### saveNewInfoWithXmp {#saveNewInfoWithXmp-java.lang.String-}
يغيّر الخصائص المحددة صراحةً عن طريق تعيين معلومات الملف، وتبقى الخصائص الأخرى كما هي.

### setAuthor {#setAuthor-java.lang.String-}
يضبط معلومات المؤلف لمستند PDF.

### setCreationDate {#setCreationDate-java.lang.String-}
يضبط معلومات تاريخ الإنشاء لمستند PDF.

### setCreator {#setCreator-java.lang.String-}
يضبط معلومات المُنشئ لمستند PDF.

### setHeader {#setHeader-java.util.Map-}
يضبط المعلومات المخصصة لمستند PDF.

### setInputFile {#setInputFile-java.lang.String-}
يضبط ملف الإدخال.

### setInputStream {#setInputStream-java.io.InputStream-}
يضبط دفق الإدخال.

### setKeywords {#setKeywords-java.lang.String-}
يضبط معلومات الكلمات المفتاحية لمستند PDF.

### setMetaInfo {#setMetaInfo-java.lang.String-java.lang.String-}
يضبط معلومات مخصصة لمستند PDF.

### setModDate {#setModDate-java.lang.String-}
يضبط معلومات تاريخ التعديل لمستند PDF.

### setSubject {#setSubject-java.lang.String-}
يضبط معلومات الموضوع لمستند PDF.

### setTitle {#setTitle-java.lang.String-}
يضبط معلومات العنوان لمستند PDF.

### setUseStrictValidation {#setUseStrictValidation-boolean-}
```
public final void setUseStrictValidation(boolean value)
```

يستخدم قواعد تحقق صارمة عبر خاصية {@code IsPdfFile}({@link #isPdfFile}).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
