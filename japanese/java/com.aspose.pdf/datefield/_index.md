---
title: "DateField"
linktitle: "DateField"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "カレンダー表示付きの日付フィールドです。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField"
type: docs
weight: 920
url: /ja/java/com.aspose.pdf/datefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.Field, com.aspose.pdf.TextBoxField com.aspose.pdf.DateField, com.aspose.pdf.TextBoxField, com.aspose.pdf.DateField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public class DateField extends TextBoxField
```

カレンダー表示付きの日付フィールドです。DateField dateField = new DateField(page, rect); doc.getForm().add(dateField); dateField.init(page); @see TextBoxField

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [DateField](#DateField--) | 新しい {@link DateField} のインスタンスを初期化します。 |
| [DateField](#DateField-com.aspose.pdf.Document-) | 新しい {@link DateField} のインスタンスを初期化します。 |
| [DateField](#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-) | 新しい {@link DateField} のインスタンスを初期化します。 |
| [DateField](#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | 新しい {@link DateField} のインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addImage_DateField_New](#addImage_DateField_New-java.awt.image.BufferedImage-) | このフィールドへの画像追加は許可されていません。 |
| [getDateFormat](#getDateFormat--) | 取得または設定 日付形式。値: 日付形式。デフォルトは dd/MM/yyyy。 |
| [getValue_DateField_New](#getValue_DateField_New--) | 取得または設定 日付。 |
| [init](#init-com.aspose.pdf.Page-) | JS アクションを初期化します。 |
| [setDateFormat](#setDateFormat-java.lang.String-) | 取得または設定 日付形式。値: 日付形式。デフォルトは dd/MM/yyyy。 |
| [setValue_DateField_New](#setValue_DateField_New-java.util.Date-) | 取得または設定 日付。 |

### DateField {#DateField--}
```
public DateField()
```

新しい {@link DateField} のインスタンスを初期化します。

### DateField {#DateField-com.aspose.pdf.Document-}
新しい {@link DateField} のインスタンスを初期化します。

### DateField {#DateField-com.aspose.pdf.Document-com.aspose.pdf.Rectangle-}
新しい {@link DateField} のインスタンスを初期化します。

### DateField {#DateField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
新しい {@link DateField} のインスタンスを初期化します。

### addImage_DateField_New {#addImage_DateField_New-java.awt.image.BufferedImage-}
このフィールドへの画像追加は許可されていません。

### getDateFormat {#getDateFormat--}
```
public final String getDateFormat()
```

取得または設定 日付形式。値: 日付形式。デフォルトは dd/MM/yyyy。

**Returns:**
文字列値

### getValue_DateField_New {#getValue_DateField_New--}
```
public final Date getValue_DateField_New()
```

取得または設定 日付。

**Returns:**
java.util.Date instance

### init {#init-com.aspose.pdf.Page-}
JS アクションを初期化します。

### setDateFormat {#setDateFormat-java.lang.String-}
取得または設定 日付形式。値: 日付形式。デフォルトは dd/MM/yyyy。

### setValue_DateField_New {#setValue_DateField_New-java.util.Date-}
取得または設定 日付。
