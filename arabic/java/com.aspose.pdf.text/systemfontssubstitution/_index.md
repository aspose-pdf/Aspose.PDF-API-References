---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل فئة لاستراتيجية استبدال الخطوط التي تستبدل الخطوط بخطوط النظام."
type: docs
weight: 110
url: /ar/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

يمثل فئة لاستراتيجية استبدال الخطوط التي تستبدل الخطوط بخطوط النظام.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | يُهيئ مثيلًا جديدًا من الفئة {@code SystemFontsSubstitution}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | يحصل أو يعيّن خط الاستبدال الافتراضي. يُستخدم الخط عندما لا يتم العثور على أي استبدال صالح آخر ولكن الخط الأصلي ينتمي إلى فئة الاستبدال المستهدفة ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | يحصل أو يعيّن فئات خطوط الاستبدال التي يجب استبدالها بالخطوط النظامية. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | يحصل أو يعيّن خط الاستبدال الافتراضي. يُستخدم الخط عندما لا يتم العثور على أي استبدال صالح آخر ولكن الخط الأصلي ينتمي إلى فئة الاستبدال المستهدفة ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | يحصل أو يعيّن فئات خطوط الاستبدال التي يجب استبدالها بالخطوط النظامية. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

يُهيئ مثيلًا جديدًا من الفئة {@code SystemFontsSubstitution}.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| fontCategories |  | فئات الخط المستهدفة لاستبدالها بالخطوط النظامية |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

يحصل أو يعيّن خط الاستبدال الافتراضي. يُستخدم الخط عندما لا يتم العثور على أي استبدال صالح آخر ولكن الخط الأصلي ينتمي إلى فئة الاستبدال المستهدفة ({@code FontCategories}).

**Returns:**
كائن الخط

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

يحصل أو يعيّن فئات خطوط الاستبدال التي يجب استبدالها بالخطوط النظامية.

**Returns:**
عنصر SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
يحصل أو يعيّن خط الاستبدال الافتراضي. يُستخدم الخط عندما لا يتم العثور على أي استبدال صالح آخر ولكن الخط الأصلي ينتمي إلى فئة الاستبدال المستهدفة ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

يحصل أو يعيّن فئات خطوط الاستبدال التي يجب استبدالها بالخطوط النظامية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | عنصر SubstitutionFontCategories @see SubstitutionFontCategories |
