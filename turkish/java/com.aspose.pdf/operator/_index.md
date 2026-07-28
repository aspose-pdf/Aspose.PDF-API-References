---
title: "Operator"
linktitle: "Operator"
second_title: "Aspose.PDF for Java API Referansı"
description: "Operatörü temsil eden soyut sınıf."
type: docs
weight: 3180
url: /tr/java/com.aspose.pdf/operator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator

```
public abstract class Operator extends Object
```

Operatörü temsil eden soyut sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Operator](#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | Yalnızca dahili kullanım için! |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatör işleme sağlayan IOperatorSelector ziyaretçisini kabul eder. |
| [createFromCommandName](#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-) | com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand örneğinin adıyla bir operatör oluşturur. |
| [equals](#equals-com.aspose.pdf.Operator-) | Bu örneği verilen nesneyle karşılaştırır. |
| [getCommand](#getCommand--) | Komutu alır |
| [getCommandName](#getCommandName--) | Operatör adını alır. |
| [getIndex](#getIndex--) | Sayfa operatörleri listesinde Operatör indeksini al. |
| [isTextShowOperator](#isTextShowOperator-com.aspose.pdf.Operator-) | Operatörün metin çıktısından sorumlu operatör (Tj, TJ vb.) olup olmadığını belirler. |
| [setIndex](#setIndex-int-) | Sayfa operatörleri listesinde Operatör dizinini ayarla. |
| [toString](#toString--) | Komutu ve parametreleri dize temsiline çevirir. |
| [valueEquals](#valueEquals-com.aspose.pdf.Operator-) | Bu örneği verilen nesneyle karşılaştırır. |

### Operator {#Operator-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
Yalnızca dahili kullanım için!

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatör işleme sağlayan IOperatorSelector ziyaretçisini kabul eder.

### createFromCommandName {#createFromCommandName-int-com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand-}
com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand örneğinin adıyla bir operatör oluşturur.

### equals {#equals-com.aspose.pdf.Operator-}
Bu örneği verilen nesneyle karşılaştırır.

### getCommand {#getCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand getCommand()
```

Komutu alır

**Returns:**
ICommand nesnesi

### getCommandName {#getCommandName--}
```
public String getCommandName()
```

Operatör adını alır.

**Returns:**
String değeri

### getIndex {#getIndex--}
```
public int getIndex()
```

Sayfa operatörleri listesinde Operatör indeksini al.

**Returns:**
int değer

### isTextShowOperator {#isTextShowOperator-com.aspose.pdf.Operator-}
Operatörün metin çıktısından sorumlu operatör (Tj, TJ vb.) olup olmadığını belirler.

### setIndex {#setIndex-int-}
```
public void setIndex(int value)
```

Sayfa operatörleri listesinde Operatör dizinini ayarla.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### toString {#toString--}
```
public String toString()
```

Komutu ve parametreleri dize temsiline çevirir.

**Returns:**
Operatör metni

### valueEquals {#valueEquals-com.aspose.pdf.Operator-}
Bu örneği verilen nesneyle karşılaştırır.
