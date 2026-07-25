---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "<p> يمثل كائن ماص لعناصر الجدول. يقوم بالبحث ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TableAbsorber.TableList}. </p> <hr> <pre> ال"
type: docs
weight: 4800
url: /ar/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> يمثل كائن ماص لعناصر الجدول. يقوم بالبحث ويوفر الوصول إلى نتائج البحث عبر مجموعة {@code TableAbsorber.TableList}. </p> <hr> <pre> يوضح المثال كيفية العثور على جدول في الصفحة الأولى من مستند PDF واستبدال النص داخل خلية الجدول. // فتح المستند Document doc = new Document("D:\\Tests\\input.pdf"); // إنشاء كائن TableAbsorber للعثور على الجداول TableAbsorber absorber = new TableAbsorber(); // زيارة الصفحة الأولى باستخدام الكائن absorber.visit(doc.getPages().get_Item(1)); // الحصول على الوصول إلى أول جدول في الصفحة، خليةه الأولى وقطع النص داخلها TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // تغيير نص أول قطعة نصية في الخلية fragment.setText("hi world"); // حفظ المستند doc.save("D:\\Tests\\output.pdf"); </pre>

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> يقوم بإنشاء نسخة جديدة من {@code TableAbsorber}. </p> <hr> يقوم بالبحث عن الجداول ويوفر الوصول إلى الجداول عبر كائن {@code TableList}. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> يقوم بإنشاء نسخة جديدة من {@code TableAbsorber}. </p> <hr> يقوم بالبحث عن الجداول ويوفر الوصول إلى الجداول عبر كائن {@code TableList}. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getTableList](#getTableList--) | <p> يُرجع IList للقراءة فقط يحتوي على الجداول التي تم العثور عليها </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> يحصل على خيارات البحث النصي. </p> <hr> يسمح بتعريف عدة خيارات سيتم استخدامها أثناء البحث عن النص داخل الجداول. |
| [isUseFlowEngine](#isUseFlowEngine--) | تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات ويستطيع التعرف على الجداول بدون حدود. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> يزيل {@code AbsorbedTable} من الصفحة. </p> <hr> <p> يرجى مراعاة أن ذلك يغيّر مجموعة TableList. في حالة إزالة/استبدال الجداول داخل حلقة يرجى استخدام نسخة من مجموعة TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> يستبدل {@code AbsorbedTable} بـ {@code Table} على الصفحة. </p> <hr> <p> يرجى مراعاة أن ذلك يغيّر مجموعة TableList. في حالة إزالة/استبدال الجداول داخل حلقة يرجى استخدام نسخة من مجموعة TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> يحصل أو يعيّن خيارات البحث النصي. </p> <hr> يسمح بتعريف عدة خيارات سيتم استخدامها أثناء البحث عن النص داخل الجداول. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات ويستطيع التعرف على الجداول بدون حدود. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> يستخرج الجداول في المستند المحدد. </p> <hr> <pre> يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF. // فتح المستند Document doc = new Document(@"D:\\Tests\\input.pdf"); // إنشاء كائن TableAbsorber للعثور على الجداول TableAbsorber absorber = new TableAbsorber(); // زيارة الصفحة الأولى باستخدام الكائن absorber.visit(pdfDocument); // الحصول على الوصول إلى أول جدول في الصفحة، خليةه الأولى وقطع النص داخلها TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // تغيير نص أول قطعة نصية في الخلية fragment.setText ("hi world"); // حفظ المستند doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> يستخرج الجداول في الصفحة المحددة </p> <hr> <pre> يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF. // فتح المستند Document doc = new Document(@"D:\\Tests\\input.pdf"); // إنشاء كائن TableAbsorber للعثور على الجداول TableAbsorber absorber = new TableAbsorber(); // زيارة الصفحة الأولى باستخدام الكائن absorber.visit(doc.getPages.get_item(1)); // الحصول على الوصول إلى أول جدول في الصفحة، خليةه الأولى وقطع النص داخلها TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // تغيير نص أول قطعة نصية في الخلية fragment.setText ("hi world"); // حفظ المستند doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> يقوم بإنشاء نسخة جديدة من {@code TableAbsorber}. </p> <hr> يقوم بالبحث عن الجداول ويوفر الوصول إلى الجداول عبر كائن {@code TableList}.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> يقوم بإنشاء نسخة جديدة من {@code TableAbsorber}. </p> <hr> يقوم بالبحث عن الجداول ويوفر الوصول إلى الجداول عبر كائن {@code TableList}.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> يُرجع IList للقراءة فقط يحتوي على الجداول التي تم العثور عليها </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> يحصل على خيارات البحث النصي. </p> <hr> يسمح بتعريف عدة خيارات سيتم استخدامها أثناء البحث عن النص داخل الجداول.

**Returns:**
كائن TextSearchOptions

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات ويستطيع التعرف على الجداول بدون حدود.

**Returns:**
قيمة منطقية

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> يزيل {@code AbsorbedTable} من الصفحة. </p> <hr> <p> يرجى مراعاة أن ذلك يغيّر مجموعة TableList. في حالة إزالة/استبدال الجداول داخل حلقة يرجى استخدام نسخة من مجموعة TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> يستبدل {@code AbsorbedTable} بـ {@code Table} على الصفحة. </p> <hr> <p> يرجى مراعاة أن ذلك يغيّر مجموعة TableList. في حالة إزالة/استبدال الجداول داخل حلقة يرجى استخدام نسخة من مجموعة TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> يحصل أو يعيّن خيارات البحث النصي. </p> <hr> يسمح بتعريف عدة خيارات سيتم استخدامها أثناء البحث عن النص داخل الجداول.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

تمكين محرك التعرف على الجداول البديل الذي يتفوق في العديد من السيناريوهات ويستطيع التعرف على الجداول بدون حدود.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| useFlowEngine |  | قيمة منطقية |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> يستخرج الجداول في المستند المحدد. </p> <hr> <pre> يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(pdfDocument); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> يستخرج الجداول في الصفحة المحددة </p> <hr> <pre> يوضح المثال كيفية استخراج جدول في الصفحة الأولى من مستند PDF. // Open document Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Create TableAbsorber object to find tables TableAbsorber absorber = new TableAbsorber(); // Visit first page with absorber absorber.visit(doc.getPages.get_item(1)); // Get access to first table on page, their first cell and text fragments in it TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Change text of the first text fragment in the cell fragment.setText (\"hi world\"); // Save document doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
