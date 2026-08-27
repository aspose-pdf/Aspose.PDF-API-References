---
title: "TocInfo"
linktitle: "TocInfo"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل معلومات جدول المحتويات."
type: docs
weight: 5370
url: /ar/java/com.aspose.pdf/tocinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TocInfo

```
public final class TocInfo extends Object
```

يمثل معلومات جدول المحتويات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TocInfo](#TocInfo--) | يُهيئ مثيلًا جديدًا من الفئة {@code TocInfo}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getColumnInfo](#getColumnInfo--) | يحصل على معلومات العمود. |
| [getCopyToOutlines](#getCopyToOutlines--) | يحصل أو يضبط ما إذا كان TOC يُنسخ إلى المخططات. |
| [getFormatArray](#getFormatArray--) | يحصل على مصفوفة التنسيق لفهرس المحتويات. |
| [getFormatArrayLength](#getFormatArrayLength--) | يحصل على طول مصفوفة التنسيق |
| [getLevelIndentation](#getLevelIndentation--) | احصل على إزاحة المستوى |
| [getLineDash](#getLineDash--) | يحصل أو يضبط نمط الخط المتقطع لـ TOC. |
| [getPageNumbersPrefix](#getPageNumbersPrefix--) | يحصل على ما إذا كان هناك بادئة قبل رقم الصفحة. |
| [getTitle](#getTitle--) | يحصل على عنوان فهرس المحتويات. |
| [isCountTocPages](#isCountTocPages--) | يحصل على ما إذا كان عدد صفحات toc الممررة. |
| [isShowPageNumbers](#isShowPageNumbers--) | يحصل على ما إذا كان يتم إظهار أرقام الصفحات في Toc. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | يضبط معلومات العمود. |
| [setCopyToOutlines](#setCopyToOutlines-boolean-) | يحصل أو يضبط ما إذا كان TOC يُنسخ إلى المخططات. |
| [setCountTocPages](#setCountTocPages-boolean-) | يحدد عدد أو صفحات الفهرس التي تم تمريرها. |
| [setFormatArray](#setFormatArray-com.aspose.pdf.LevelFormat:A-) | يحدد مصفوفة التنسيق للفهرس. |
| [setFormatArrayLength](#setFormatArrayLength-int-) | يحدد طول مصفوفة التنسيق |
| [setLevelIndentation](#setLevelIndentation-int-) | تعيين مسافة إزاحة المستوى |
| [setLineDash](#setLineDash-int-) | يحصل أو يضبط نمط الخط المتقطع لـ TOC. |
| [setPageNumbersPrefix](#setPageNumbersPrefix-java.lang.String-) | يحدد البادئة قبل رقم الصفحة. |
| [setShowPageNumbers](#setShowPageNumbers-boolean-) | يحدد إظهار أرقام الصفحات في الفهرس. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | يحدد عنوان الفهرس. |

### TocInfo {#TocInfo--}
```
public TocInfo()
```

يُهيئ مثيلًا جديدًا من الفئة {@code TocInfo}.

### getColumnInfo {#getColumnInfo--}
```
public final ColumnInfo getColumnInfo()
```

يحصل على معلومات العمود.

**Returns:**
مثيل ColumnInfo

### getCopyToOutlines {#getCopyToOutlines--}
```
public final boolean getCopyToOutlines()
```

يحصل أو يضبط ما إذا كان TOC يُنسخ إلى المخططات.

**Returns:**
قيمة منطقية

### getFormatArray {#getFormatArray--}
```
public final LevelFormat [] getFormatArray()
```

يحصل على مصفوفة التنسيق لفهرس المحتويات.

**Returns:**
مصفوفة LevelFormat

### getFormatArrayLength {#getFormatArrayLength--}
```
public final int getFormatArrayLength()
```

يحصل على طول مصفوفة التنسيق

**Returns:**
قيمة منطقية

### getLevelIndentation {#getLevelIndentation--}
```
public int getLevelIndentation()
```

احصل على إزاحة المستوى

**Returns:**
قيمة int

### getLineDash {#getLineDash--}
```
public final int getLineDash()
```

يحصل أو يضبط نمط الخط المتقطع لـ TOC.

**Returns:**
قيمة TabLeaderType

### getPageNumbersPrefix {#getPageNumbersPrefix--}
```
public final String getPageNumbersPrefix()
```

يحصل على ما إذا كان هناك بادئة قبل رقم الصفحة.

**Returns:**
قيمة سلسلة

### getTitle {#getTitle--}
```
public final TextFragment getTitle()
```

يحصل على عنوان فهرس المحتويات.

**Returns:**
مثيل TextFragment

### isCountTocPages {#isCountTocPages--}
```
public final boolean isCountTocPages()
```

يحصل على ما إذا كان عدد صفحات toc الممررة.

**Returns:**
قيمة منطقية

### isShowPageNumbers {#isShowPageNumbers--}
```
public final boolean isShowPageNumbers()
```

يحصل على ما إذا كان يتم إظهار أرقام الصفحات في Toc.

**Returns:**
قيمة منطقية

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
يضبط معلومات العمود.

### setCopyToOutlines {#setCopyToOutlines-boolean-}
```
public final void setCopyToOutlines(boolean value)
```

يحصل أو يضبط ما إذا كان TOC يُنسخ إلى المخططات.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setCountTocPages {#setCountTocPages-boolean-}
```
public final void setCountTocPages(boolean value)
```

يحدد عدد أو صفحات الفهرس التي تم تمريرها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setFormatArray {#setFormatArray-com.aspose.pdf.LevelFormat:A-}
يحدد مصفوفة التنسيق للفهرس.

### setFormatArrayLength {#setFormatArrayLength-int-}
```
public final void setFormatArrayLength(int value)
```

يحدد طول مصفوفة التنسيق

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setLevelIndentation {#setLevelIndentation-int-}
```
public void setLevelIndentation(int value)
```

تعيين مسافة إزاحة المستوى

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setLineDash {#setLineDash-int-}
```
public final void setLineDash(int value)
```

يحصل أو يضبط نمط الخط المتقطع لـ TOC.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة TabLeaderType |

### setPageNumbersPrefix {#setPageNumbersPrefix-java.lang.String-}
يحدد البادئة قبل رقم الصفحة.

### setShowPageNumbers {#setShowPageNumbers-boolean-}
```
public final void setShowPageNumbers(boolean value)
```

يحدد إظهار أرقام الصفحات في الفهرس.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
يحدد عنوان الفهرس.
