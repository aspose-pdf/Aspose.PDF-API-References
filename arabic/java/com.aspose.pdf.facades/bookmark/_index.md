---
title: "Bookmark"
linktitle: "Bookmark"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل إشارة مرجعية."
type: docs
weight: 60
url: /ar/java/com.aspose.pdf.facades/bookmark/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Bookmark

```
public final class Bookmark extends Object
```

يمثل إشارة مرجعية.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [Bookmark](#Bookmark--) | يُنشئ مثيلاً جديداً للفئة {@code Bookmark}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getAction](#getAction--) | يحصل على الإجراء المرتبط بالعلامة. إذا تم تقديم PageNumber لا يمكن تحديد الإجراء. نوع الإجراء يشمل: "GoTo", "GoToR", "Launch", "Named". |
| [getBoldFlag](#getBoldFlag--) | يحصل على علامة الغامق لعنوان العلامة. |
| [getChildItem](#getChildItem--) | يحصل على عناصر العلامة الفرعية. مهمل("Use getChildItems() property instead of this one.") |
| [getChildItems](#getChildItems--) | يحصل على عناصر العلامة الفرعية. |
| [getCustomAcorbatViewerMenuActionName](#getCustomAcorbatViewerMenuActionName--) | غير مدعوم بعد. اسم الإجراء المقابل لتنفيذ عنصر قائمة في عارض Acrobat. |
| [getDestination](#getDestination--) | يحصل على صفحة الوجهة للعلامة. مطلوب إذا تم تعيين الإجراء كـ "". |
| [getItalicFlag](#getItalicFlag--) | يحصل على علامة المائل لعنوان العلامة. |
| [getLevel](#getLevel--) | يحصل على مستوى تسلسل العلامة. |
| [getPageDisplay_Bottom](#getPageDisplay_Bottom--) | يحصل على الإحداثي السفلي لعرض الصفحة. |
| [getPageDisplay_Left](#getPageDisplay_Left--) | يحصل على الإحداثي الأيسر لعرض الصفحة. |
| [getPageDisplay_Right](#getPageDisplay_Right--) | يحصل على الإحداثي الأيمن لعرض الصفحة. |
| [getPageDisplay_Top](#getPageDisplay_Top--) | يحصل على الإحداثي العلوي لعرض الصفحة. |
| [getPageDisplay_Zoom](#getPageDisplay_Zoom--) | يحصل على معامل التكبير لعرض الصفحة. |
| [getPageDisplay](#getPageDisplay--) | يحصل على نوع صفحة الوجهة للعلامة المرجعية المعروضة. |
| [getPageNumber](#getPageNumber--) | يحصل على رقم صفحة الوجهة للعلامة المرجعية. |
| [getRemoteFile](#getRemoteFile--) | يحصل على الملف (المسار) المطلوب لإجراء "GoToR" للعلامة المرجعية. |
| [getTitle](#getTitle--) | يحصل على عنوان العلامة المرجعية. |
| [getTitleColor](#getTitleColor--) | يحصل على لون عنوان العلامة المرجعية. |
| [isOpen](#isOpen--) | يحصل على حالة العلامة المرجعية (مفتوحة، مغلقة). |
| [setAction](#setAction-java.lang.String-) | يضبط الإجراء المرتبط بالعلامة المرجعية. إذا تم تقديم PageNumber لا يمكن تحديد الإجراء. نوع الإجراء يشمل: "GoTo", "GoToR", "Launch", "Named". |
| [setBoldFlag](#setBoldFlag-boolean-) | يضبط علامة الخط العريض لعنوان العلامة المرجعية. |
| [setChildItem](#setChildItem-com.aspose.pdf.facades.Bookmarks-) | يضبط عناصر العلامة المرجعية الفرعية. Obsolete("Use setChildItems() property instead of this one.") |
| [setChildItems](#setChildItems-com.aspose.pdf.facades.Bookmarks-) | يضبط عناصر العلامة المرجعية الفرعية. |
| [setCustomAcorbatViewerMenuActionName](#setCustomAcorbatViewerMenuActionName-int:A-) | غير مدعوم بعد. يضبط اسم الإجراء المقابل لتنفيذ عنصر قائمة في عارض Acrobat. |
| [setDestination](#setDestination-java.lang.String-) | يضبط صفحة وجهة العلامة المرجعية. مطلوب إذا تم تعيين الإجراء كـ "". |
| [setItalicFlag](#setItalicFlag-boolean-) | يضبط علامة الخط المائل لعنوان العلامة المرجعية. |
| [setLevel](#setLevel-int-) | يضبط مستوى تسلسل العلامة المرجعية الهرمي. |
| [setOpen](#setOpen-boolean-) | يضبط حالة العلامة المرجعية (مفتوحة، مغلقة). |
| [setPageDisplay_Bottom](#setPageDisplay_Bottom-int-) | يضبط الإحداثي السفلي لعرض الصفحة. |
| [setPageDisplay_Left](#setPageDisplay_Left-int-) | يضبط الإحداثي الأيسر لعرض الصفحة. |
| [setPageDisplay_Right](#setPageDisplay_Right-int-) | يضبط الإحداثي الأيمن لعرض الصفحة. |
| [setPageDisplay_Top](#setPageDisplay_Top-int-) | يضبط الإحداثي العلوي لعرض الصفحة. |
| [setPageDisplay_Zoom](#setPageDisplay_Zoom-int-) | يضبط معامل التكبير لعرض الصفحة. |
| [setPageDisplay](#setPageDisplay-java.lang.String-) | يضبط نوع صفحة الوجهة للعلامة المرجعية المعروضة. |
| [setPageNumber](#setPageNumber-int-) | يضبط رقم صفحة الوجهة للعلامة المرجعية. |
| [setRemoteFile](#setRemoteFile-java.lang.String-) | يضبط الملف (المسار) المطلوب لإجراء "GoToR" للعلامة المرجعية. |
| [setTitle](#setTitle-java.lang.String-) | يضبط عنوان العلامة المرجعية. |
| [setTitleColor](#setTitleColor-java.awt.Color-) | يضبط لون عنوان العلامة المرجعية. |
| [toOutlineItemCollection](#toOutlineItemCollection-com.aspose.pdf.IDocument-) | تحويل إلى OutlineItemCollection |

### Bookmark {#Bookmark--}
```
public Bookmark()
```

يُنشئ مثيلاً جديداً للفئة {@code Bookmark}.

### getAction {#getAction--}
```
public String getAction()
```

يحصل على الإجراء المرتبط بالعلامة. إذا تم تقديم PageNumber لا يمكن تحديد الإجراء. نوع الإجراء يشمل: "GoTo", "GoToR", "Launch", "Named".

**Returns:**
قيمة سلسلة

### getBoldFlag {#getBoldFlag--}
```
public boolean getBoldFlag()
```

يحصل على علامة الغامق لعنوان العلامة.

**Returns:**
قيمة منطقية

### getChildItem {#getChildItem--}
```
@Deprecated public Bookmarks getChildItem()
```

يحصل على عناصر العلامة الفرعية. مهمل("Use getChildItems() property instead of this one.")

**Returns:**
عنصر العلامات المرجعية

### getChildItems {#getChildItems--}
```
public Bookmarks getChildItems()
```

يحصل على عناصر العلامة الفرعية.

**Returns:**
عناصر الأطفال للعلامة المرجعية.

### getCustomAcorbatViewerMenuActionName {#getCustomAcorbatViewerMenuActionName--}
```
public int[] getCustomAcorbatViewerMenuActionName()
```

غير مدعوم بعد. اسم الإجراء المقابل لتنفيذ عنصر قائمة في عارض Acrobat.

**Returns:**
مصفوفة من قيم int

### getDestination {#getDestination--}
```
public String getDestination()
```

يحصل على صفحة الوجهة للعلامة. مطلوب إذا تم تعيين الإجراء كـ "".

**Returns:**
قيمة سلسلة

### getItalicFlag {#getItalicFlag--}
```
public boolean getItalicFlag()
```

يحصل على علامة المائل لعنوان العلامة.

**Returns:**
قيمة منطقية

### getLevel {#getLevel--}
```
public int getLevel()
```

يحصل على مستوى تسلسل العلامة.

**Returns:**
قيمة int

### getPageDisplay_Bottom {#getPageDisplay_Bottom--}
```
public int getPageDisplay_Bottom()
```

يحصل على الإحداثي السفلي لعرض الصفحة.

**Returns:**
قيمة int

### getPageDisplay_Left {#getPageDisplay_Left--}
```
public int getPageDisplay_Left()
```

يحصل على الإحداثي الأيسر لعرض الصفحة.

**Returns:**
قيمة int

### getPageDisplay_Right {#getPageDisplay_Right--}
```
public int getPageDisplay_Right()
```

يحصل على الإحداثي الأيمن لعرض الصفحة.

**Returns:**
قيمة int

### getPageDisplay_Top {#getPageDisplay_Top--}
```
public int getPageDisplay_Top()
```

يحصل على الإحداثي العلوي لعرض الصفحة.

**Returns:**
قيمة int

### getPageDisplay_Zoom {#getPageDisplay_Zoom--}
```
public int getPageDisplay_Zoom()
```

يحصل على معامل التكبير لعرض الصفحة.

**Returns:**
قيمة int

### getPageDisplay {#getPageDisplay--}
```
public String getPageDisplay()
```

يحصل على نوع صفحة الوجهة للعلامة المرجعية المعروضة.

**Returns:**
قيمة سلسلة

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

يحصل على رقم صفحة الوجهة للعلامة المرجعية.

**Returns:**
قيمة int

### getRemoteFile {#getRemoteFile--}
```
public String getRemoteFile()
```

يحصل على الملف (المسار) المطلوب لإجراء "GoToR" للعلامة المرجعية.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public String getTitle()
```

يحصل على عنوان العلامة المرجعية.

**Returns:**
قيمة سلسلة

### getTitleColor {#getTitleColor--}
```
public Color getTitleColor()
```

يحصل على لون عنوان العلامة المرجعية.

**Returns:**
عنصر اللون

### isOpen {#isOpen--}
```
public boolean isOpen()
```

يحصل على حالة العلامة المرجعية (مفتوحة، مغلقة).

**Returns:**
قيمة منطقية

### setAction {#setAction-java.lang.String-}
يضبط الإجراء المرتبط بالعلامة المرجعية. إذا تم تقديم PageNumber لا يمكن تحديد الإجراء. نوع الإجراء يشمل: "GoTo", "GoToR", "Launch", "Named".

### setBoldFlag {#setBoldFlag-boolean-}
```
public void setBoldFlag(boolean value)
```

يضبط علامة الخط العريض لعنوان العلامة المرجعية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setChildItem {#setChildItem-com.aspose.pdf.facades.Bookmarks-}
يضبط عناصر العلامة المرجعية الفرعية. Obsolete("Use setChildItems() property instead of this one.")

### setChildItems {#setChildItems-com.aspose.pdf.facades.Bookmarks-}
يضبط عناصر العلامة المرجعية الفرعية.

### setCustomAcorbatViewerMenuActionName {#setCustomAcorbatViewerMenuActionName-int:A-}
```
public void setCustomAcorbatViewerMenuActionName(int[] value)
```

غير مدعوم بعد. يضبط اسم الإجراء المقابل لتنفيذ عنصر قائمة في عارض Acrobat.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | مصفوفة من قيم int |

### setDestination {#setDestination-java.lang.String-}
يضبط صفحة وجهة العلامة المرجعية. مطلوب إذا تم تعيين الإجراء كـ "".

### setItalicFlag {#setItalicFlag-boolean-}
```
public void setItalicFlag(boolean value)
```

يضبط علامة الخط المائل لعنوان العلامة المرجعية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

يضبط مستوى تسلسل العلامة المرجعية الهرمي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setOpen {#setOpen-boolean-}
```
public void setOpen(boolean value)
```

يضبط حالة العلامة المرجعية (مفتوحة، مغلقة).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setPageDisplay_Bottom {#setPageDisplay_Bottom-int-}
```
public void setPageDisplay_Bottom(int value)
```

يضبط الإحداثي السفلي لعرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPageDisplay_Left {#setPageDisplay_Left-int-}
```
public void setPageDisplay_Left(int value)
```

يضبط الإحداثي الأيسر لعرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPageDisplay_Right {#setPageDisplay_Right-int-}
```
public void setPageDisplay_Right(int value)
```

يضبط الإحداثي الأيمن لعرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPageDisplay_Top {#setPageDisplay_Top-int-}
```
public void setPageDisplay_Top(int value)
```

يضبط الإحداثي العلوي لعرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPageDisplay_Zoom {#setPageDisplay_Zoom-int-}
```
public void setPageDisplay_Zoom(int value)
```

يضبط معامل التكبير لعرض الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setPageDisplay {#setPageDisplay-java.lang.String-}
يضبط نوع صفحة الوجهة للعلامة المرجعية المعروضة.

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

يضبط رقم صفحة الوجهة للعلامة المرجعية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setRemoteFile {#setRemoteFile-java.lang.String-}
يضبط الملف (المسار) المطلوب لإجراء "GoToR" للعلامة المرجعية.

### setTitle {#setTitle-java.lang.String-}
يضبط عنوان العلامة المرجعية.

### setTitleColor {#setTitleColor-java.awt.Color-}
يضبط لون عنوان العلامة المرجعية.

### toOutlineItemCollection {#toOutlineItemCollection-com.aspose.pdf.IDocument-}
تحويل إلى OutlineItemCollection
