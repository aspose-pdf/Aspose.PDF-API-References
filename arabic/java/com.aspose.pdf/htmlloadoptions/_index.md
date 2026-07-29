---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تحميل/استيراد ملف HTML إلى مستند PDF."
type: docs
weight: 1960
url: /ar/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

يمثل خيارات تحميل/استيراد ملف HTML إلى مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | ينشئ خيارات التحميل لتحويل HTML إلى مستند PDF مع مسار أساسي فارغ. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | ينشئ خيارات التحميل لتحويل HTML إلى مستند PDF مع مسار أساسي فارغ. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBasePath](#getBasePath--) | مسار/عنوان URL الأساسي لملف html. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها: في هذه الحالة يجب استخدام بعض شفرة العميل التي توضع في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه الخاصية. |
| [getHtmlMediaType](#getHtmlMediaType--) | يحصل أو يضبط أنواع الوسائط الممكنة المستخدمة أثناء التصيير. |
| [getInputEncoding](#getInputEncoding--) | يحصل على الخاصية التي تحدد الترميز المستخدم لهذا المستند في وقت التحليل. إذا كانت هذه الخاصية فارغة، سيتم تحديد الترميز من مجموعة أحرف المستند. |
| [getPageInfo](#getPageInfo--) | يحصل على معلومات صفحة المستند |
| [getPageLayoutOption](#getPageLayoutOption--) | يحصل أو يضبط خيار التخطيط. |
| [isEmbedFonts](#isEmbedFonts--) | يحصل أو يضبط تضمين الخطوط في المستند الناتج |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | يحصل أو يضبط العلامة التي تحدد أن قواعد @page المعرفة في css ستتجاوز القيم المعرفة في PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | يحصل أو يضبط تصيير المستند بالكامل إلى صفحة واحدة |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | يحصل أو يضبط تضمين الخطوط في المستند الناتج |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | يحصل أو يضبط أنواع الوسائط الممكنة المستخدمة أثناء التصيير. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | يضبط الخاصية التي تحدد الترميز المستخدم لهذا المستند في وقت التحليل. إذا كانت هذه الخاصية فارغة، سيتم تحديد الترميز من مجموعة أحرف المستند. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | يضبط معلومات صفحة المستند |
| [setPageLayoutOption](#setPageLayoutOption-int-) | يحصل أو يضبط خيار التخطيط. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | يحصل أو يضبط العلامة التي تحدد أن قواعد @page المعرفة في css ستتجاوز القيم المعرفة في PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | يحصل أو يضبط تصيير المستند بالكامل إلى صفحة واحدة |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

ينشئ خيارات التحميل لتحويل HTML إلى مستند PDF مع مسار أساسي فارغ.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
ينشئ خيارات التحميل لتحويل HTML إلى مستند PDF مع مسار أساسي فارغ.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

مسار/عنوان URL الأساسي لملف html.

**Returns:**
قيمة سلسلة

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما. على سبيل المثال، أثناء استخدام Aspose.PDF في السحابة لا يمكن الوصول مباشرة إلى الملفات المشار إليها: في هذه الحالة يجب استخدام بعض شفرة العميل التي توضع في طريقة خاصة، ويجب تعيين المفوض الذي يشير إلى تلك الطريقة إلى هذه الخاصية.

**Returns:**
مثيل ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

يحصل أو يضبط أنواع الوسائط الممكنة المستخدمة أثناء التصيير.

**Returns:**
عنصر HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

يحصل على الخاصية التي تحدد الترميز المستخدم لهذا المستند في وقت التحليل. إذا كانت هذه الخاصية فارغة، سيتم تحديد الترميز من مجموعة أحرف المستند.

**Returns:**
قيمة سلسلة

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

يحصل على معلومات صفحة المستند

**Returns:**
معلومات الصفحة

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

يحصل أو يضبط خيار التخطيط.

**Returns:**
عنصر HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

يحصل أو يضبط تضمين الخطوط في المستند الناتج

**Returns:**
قيمة منطقية

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

يحصل أو يضبط العلامة التي تحدد أن قواعد @page المعرفة في css ستتجاوز القيم المعرفة في PageInfo.

**Returns:**
قيمة منطقية

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

يحصل أو يضبط تصيير المستند بالكامل إلى صفحة واحدة

**Returns:**
قيمة منطقية

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
في بعض الأحيان يكون من الضروري تجنب استخدام محمل الموارد الخارجية الداخلي (مثل الصور أو ملفات CSS) وتوفير طريقة مخصصة ستحصل على الموارد المطلوبة من مكان ما.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

يحصل أو يضبط تضمين الخطوط في المستند الناتج

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
يحصل أو يضبط أنواع الوسائط الممكنة المستخدمة أثناء التصيير.

### setInputEncoding {#setInputEncoding-java.lang.String-}
يضبط الخاصية التي تحدد الترميز المستخدم لهذا المستند في وقت التحليل. إذا كانت هذه الخاصية فارغة، سيتم تحديد الترميز من مجموعة أحرف المستند.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
يضبط معلومات صفحة المستند

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

يحصل أو يضبط خيار التخطيط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

يحصل أو يضبط العلامة التي تحدد أن قواعد @page المعرفة في css ستتجاوز القيم المعرفة في PageInfo.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

يحصل أو يضبط تصيير المستند بالكامل إلى صفحة واحدة

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |
