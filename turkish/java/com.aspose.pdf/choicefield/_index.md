---
title: "ChoiceField"
linktitle: "ChoiceField"
second_title: "Aspose.PDF for Java API Referansı"
description: "Seçim alanları için temel sınıfı temsil eder."
type: docs
weight: 590
url: /tr/java/com.aspose.pdf/choicefield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Annotation com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Annotation, com.aspose.pdf.WidgetAnnotation com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.WidgetAnnotation, com.aspose.pdf.Field com.aspose.pdf.ChoiceField, com.aspose.pdf.Field, com.aspose.pdf.ChoiceField

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable< WidgetAnnotation >, com.aspose.ms.System.Collections.IEnumerable< WidgetAnnotation >, com.aspose.ms.System.ICloneable, Cloneable, Iterable < WidgetAnnotation >

```
public abstract class ChoiceField extends Field
```

Seçim alanları için temel sınıfı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-) | Seçim alanı oluşturur (Generator için) |
| [ChoiceField](#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-) | ChoiceField için yapıcı. |
| [ChoiceField](#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-) | ChoiceField için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addOption](#addOption-java.lang.String-) | Belirtilen adla yeni seçenek ekler. |
| [addOption](#addOption-java.lang.String-java.lang.String-) | Belirtilen dışa aktarım değeri ve adla yeni seçenek ekler. |
| [deleteOption](#deleteOption-java.lang.String-) | Seçeneği adından siler. |
| [getCommitImmediately](#getCommitImmediately--) | Seçim değişikliğinde commit bayrağını alır. |
| [getMultiSelect](#getMultiSelect--) | Çoklu seçim bayrağını alır. |
| [getOptions](#getOptions--) | Seçim seçenekleri koleksiyonunu alır. |
| [getSelected](#getSelected--) | Seçilen seçeneğin dizinini alır. Bu özellik seçimi değiştirmeye izin verir. |
| [getSelectedItems](#getSelectedItems--) | Seçilen öğelerin dizisini ayarlar. Çoklu seçim listesi için dizi birden fazla öğe içerir. Tek seçim listesi için tek öğe içerir. |
| [getValue](#getValue--) | Alanın değerini alır. |
| [setCommitImmediately](#setCommitImmediately-boolean-) | Seçim değişikliğinde commit bayrağını ayarlar. |
| [setMultiSelect](#setMultiSelect-boolean-) | Çoklu seçim bayrağını ayarlar. |
| [setOptions](#setOptions-java.util.List-) | Mevcut seçenekleri, seçenek parametresinde verilen adlara sahip olanlarla değiştirir. |
| [setSelected](#setSelected-int-) | Seçilen seçeneğin dizinini ayarlar. Bu özellik seçimi değiştirmeye izin verir. |
| [setSelectedItems](#setSelectedItems-int:A-) | Seçilen öğelerin dizisini ayarlar. Çoklu seçim listesi için dizi birden fazla öğe içerir. Tek seçim listesi için tek öğe içerir. |
| [setValue](#setValue-java.lang.String-) | Alan değerini ayarlar. |

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-}
Seçim alanı oluşturur (Generator için)

### ChoiceField {#ChoiceField-com.aspose.pdf.IDocument-com.aspose.pdf.Rectangle-}
ChoiceField için yapıcı.

### ChoiceField {#ChoiceField-com.aspose.pdf.Page-com.aspose.pdf.Rectangle-}
ChoiceField için yapıcı.

### addOption {#addOption-java.lang.String-}
Belirtilen adla yeni seçenek ekler.

### addOption {#addOption-java.lang.String-java.lang.String-}
Belirtilen dışa aktarım değeri ve adla yeni seçenek ekler.

### deleteOption {#deleteOption-java.lang.String-}
Seçeneği adından siler.

### getCommitImmediately {#getCommitImmediately--}
```
public boolean getCommitImmediately()
```

Seçim değişikliğinde commit bayrağını alır.

**Returns:**
boolean değer

### getMultiSelect {#getMultiSelect--}
```
public boolean getMultiSelect()
```

Çoklu seçim bayrağını alır.

**Returns:**
boolean değer

### getOptions {#getOptions--}
```
public OptionCollection getOptions()
```

Seçim seçenekleri koleksiyonunu alır.

**Returns:**
OptionCollection nesnesi

### getSelected {#getSelected--}
```
public int getSelected()
```

Seçilen seçeneğin dizinini alır. Bu özellik seçimi değiştirmeye izin verir.

**Returns:**
int değer

### getSelectedItems {#getSelectedItems--}
```
public int[] getSelectedItems()
```

Seçilen öğelerin dizisini ayarlar. Çoklu seçim listesi için dizi birden fazla öğe içerir. Tek seçim listesi için tek öğe içerir.

**Returns:**
int değerlerinin dizisi

### getValue {#getValue--}
```
public String getValue()
```

Alanın değerini alır.

**Returns:**
String değeri

### setCommitImmediately {#setCommitImmediately-boolean-}
```
public void setCommitImmediately(boolean value)
```

Seçim değişikliğinde commit bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMultiSelect {#setMultiSelect-boolean-}
```
public void setMultiSelect(boolean value)
```

Çoklu seçim bayrağını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOptions {#setOptions-java.util.List-}
Mevcut seçenekleri, seçenek parametresinde verilen adlara sahip olanlarla değiştirir.

### setSelected {#setSelected-int-}
```
public void setSelected(int value)
```

Seçilen seçeneğin dizinini ayarlar. Bu özellik seçimi değiştirmeye izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setSelectedItems {#setSelectedItems-int:A-}
```
public void setSelectedItems(int[] value)
```

Seçilen öğelerin dizisini ayarlar. Çoklu seçim listesi için dizi birden fazla öğe içerir. Tek seçim listesi için tek öğe içerir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değerlerinin dizisi |

### setValue {#setValue-java.lang.String-}
Alan değerini ayarlar.
