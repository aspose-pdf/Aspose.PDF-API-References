---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يجري البحث عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط PDF القياسية. كما يوفر وظيفة لفتح الخطوط المخصصة. </p> <hr> <pre> المثال يوضح."
type: docs
weight: 1690
url: /ar/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> يجري البحث عن الخطوط. يبحث في الخطوط المثبتة على النظام وخطوط PDF القياسية. كما يوفر وظيفة لفتح الخطوط المخصصة. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط نص الصفحة الأولى. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | أضف مسارًا آخر للخطوط. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> أضف خط نظام بالخط المحدد. </p> <hr> <pre> يوضح المثال كيفية إضافة خط نظام. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> يبحث ويعيد الخط بالاسم المحدد للخط. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى. // العثور على الخط Font font = FontRepository.findFont("Arial"); // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماصة للصفحة الأولى doc.getPages().get_Item(1).accept(absorber); // تغيير خط أول ظهور للنص absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> يبحث ويعيد الخط بالاسم المحدد للخط مع تجاهل أو احترام حساسية الأحرف. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى. // العثور على الخط Font font = FontRepository.findFont("Arial", FontStyles.Italic); // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماصة للصفحة الأولى doc.getPages().get_Item(1).accept(absorber); // تغيير خط أول ظهور للنص absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> يبحث ويعيد الخط بالاسم المحدد للخط ونمط الخط. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى. // العثور على الخط Font font = FontRepository.findFont("Arial", FontStyles.Italic); // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماصة للصفحة الأولى doc.getPages().get_Item(1).accept(absorber); // تغيير خط أول ظهور للنص absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> يبحث ويعيد الخط بالاسم المحدد للخط ونمط الخط مع تجاهل أو احترام حساسية الأحرف. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى. // العثور على الخط Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // فتح المستند Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // إنشاء كائن TextFragmentAbsorber للعثور على جميع مرات ظهور النص "hello world" TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // قبول الماصة للصفحة الأولى doc.getPages().get_Item(1).accept(absorber); // تغيير خط أول ظهور للنص absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // حفظ المستند doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | نسخة من القائمة مع دلائل الخطوط الفعلية. |
| [getSources](#getSources--) | يحصل على مجموعة مصادر الخطوط. |
| [getSubstitutions](#getSubstitutions--) | يحصل على مجموعة استراتيجيات استبدال الخطوط. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | <p> يعيد حالة تكوين تخزين مصادر الخطوط. <br> إذا كان true، يتم استخدام ThreadStatic وكل خيط له مصادر الخطوط الخاصة به. <br> إذا كان false، يتم استخدام تكوين ثابت عالمي لجميع الخيوط. </p> <hr> القيمة الافتراضية هي True. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | يقوم بتحميل الخطوط المثبتة على النظام وخطوط Pdf القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي، يتم تحميل الخطوط عند أول طلب لأي خط. استخدام هذه الطريقة يحمل الخطوط النظامية والقياسية لـ Pdf فورًا قبل فتح أي مستند Pdf. |
| [loadFonts](#loadFonts--) | يقوم بتحميل الخطوط المثبتة على النظام وخطوط PDF القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي، يتم تحميل الخطوط عند الطلب الأول لأي خط. استخدام هذه الطريقة يحمل خطوط النظام وخطوط PDF القياسية فورًا قبل فتح أي مستند PDF. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> يفتح الخط باستخدام تدفق الخط المحدد. </p> <hr> <pre> يوضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى. // Open font InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> يفتح الخط باستخدام مسار ملف الخط المحدد. </p> <hr> <pre> يوضح المثال كيفية فتح الخط واستبدال خط النص في الصفحة الأولى. // Open font Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> يفتح الخط باستخدام مسار ملف الخط المحدد ومسار ملف المقاييس. </p> <hr> <pre> يوضح المثال كيفية فتح خط Type1 مع المقاييس واستبدال خط النص في الصفحة الأولى. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | يعيد تحميل جميع الخطوط المحددة بواسطة الخاصية {@code Sources}({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | يستعيد القائمة لدلائل الخطوط القياسية بشكل افتراضي. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | يضبط قائمة المستخدم بمسارات الخطوط |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | عيّن TRUE إذا كان من الضروري استبدال الخطوط غير الموجودة بالخط الافتراضي. القيمة الافتراضية هي false. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | خيار لتعيين تكوين تخزين مصادر الخطوط. إذا كان true، يُستخدم ThreadStatic ولكل خيط مصدر خطوط خاص به. إذا كان false، يُستخدم تكوين ثابت عالمي لجميع الخيوط. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
أضف مسارًا آخر للخطوط.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> أضف خط نظام باستخدام الخط المحدد. </p> <hr> <pre> يوضح المثال كيفية إضافة خط نظام. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> يبحث ويعيد الخط بالاسم المحدد للخط. </p> <hr> <pre> يوضح المثال كيفية العثور على الخط واستبدال خط النص في الصفحة الأولى. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> يبحث ويعيد الخط بالاسم المحدد للخط مع تجاهل أو احترام حساسية الأحرف. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> يبحث ويعيد الخط بالاسم المحدد للخط ونمط الخط. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> يبحث ويعيد الخط بالاسم المحدد للخط ونمط الخط مع تجاهل أو احترام حساسية الأحرف. </p> <hr> <pre> The example demonstrates how to find font and replace the font of text of first page. // Find font Font font = FontRepository.findFont("Arial", FontStyles.Italic, true); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

نسخة من القائمة مع دلائل الخطوط الفعلية.

**Returns:**
قائمة من String

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

يحصل على مجموعة مصادر الخطوط.

**Returns:**
كائن FontSourceCollection

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

يحصل على مجموعة استراتيجيات استبدال الخطوط.

**Returns:**
كائن FontSubstitutionCollection

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

<p> يعيد حالة تكوين تخزين مصادر الخطوط. <br> إذا كان true، يتم استخدام ThreadStatic وكل خيط له مصادر الخطوط الخاصة به. <br> إذا كان false، يتم استخدام تكوين ثابت عالمي لجميع الخيوط. </p> <hr> القيمة الافتراضية هي True.

**Returns:**
قيمة منطقية

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

يقوم بتحميل الخطوط المثبتة على النظام وخطوط Pdf القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي، يتم تحميل الخطوط عند أول طلب لأي خط. استخدام هذه الطريقة يحمل الخطوط النظامية والقياسية لـ Pdf فورًا قبل فتح أي مستند Pdf.

**Returns:**
قيمة منطقية

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

يقوم بتحميل الخطوط المثبتة على النظام وخطوط PDF القياسية. تم تصميم هذه الطريقة لتسريع عملية تحميل الخطوط. بشكل افتراضي، يتم تحميل الخطوط عند الطلب الأول لأي خط. استخدام هذه الطريقة يحمل خطوط النظام وخطوط PDF القياسية فورًا قبل فتح أي مستند PDF.

### openFont {#openFont-java.io.InputStream-int-}
<p> يفتح الخط باستخدام تدفق الخط المحدد. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> يفتح الخط باستخدام مسار ملف الخط المحدد. </p> <hr> <pre> The example demonstrates how to open font and replace the font of text of first page. // Open font Font font = FontRepository.openFont("C:\\WINDOWS\\Fonts\\arial.ttf"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> يفتح الخط بالمسار المحدد لملف الخط ومسار ملف المقاييس. </p> <hr> <pre> يوضح المثال كيفية فتح خط Type1 مع المقاييس واستبدال خط النص في الصفحة الأولى. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

يعيد تحميل جميع الخطوط المحددة بواسطة الخاصية {@code Sources}({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

يستعيد القائمة لدلائل الخطوط القياسية بشكل افتراضي.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
يضبط قائمة المستخدم بمسارات الخطوط

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

عيّن TRUE إذا كان من الضروري استبدال الخطوط غير الموجودة بالخط الافتراضي. القيمة الافتراضية هي false.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

خيار لتعيين تكوين تخزين مصادر الخطوط. إذا كان true، يُستخدم ThreadStatic ولكل خيط مصدر خطوط خاص به. إذا كان false، يُستخدم تكوين ثابت عالمي لجميع الخيوط.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| isTheadLocal |  | قيمة منطقية |
