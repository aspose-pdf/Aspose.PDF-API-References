---
title: "DP"
linktitle: "DP"
second_title: "Aspose.PDF for Java API Referansı"
description: "DP operatörünü temsil eden sınıf (işaretli içerik noktasını belirtir)."
type: docs
weight: 190
url: /tr/java/com.aspose.pdf.operators/dp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.DP, com.aspose.pdf.Operator, com.aspose.pdf.operators.DP

```
public class DP extends Operator
```

DP operatörünü temsil eden sınıf (işaretli içerik noktasını belirtir).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DP](#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-) | Operatör sınıfı için yapıcı. |
| [DP](#DP-java.lang.String-) | Operatörü başlatır. |
| [DP](#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getPropertiesDictionary](#getPropertiesDictionary--) | Özellikler sözlüğünü alır |
| [getTag](#getTag--) | İşaretlenmiş içerik etiketini alır |
| [setPropertiesDictionary](#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-) | Özelliklerin sözlüğünü ayarlar |
| [setTag](#setTag-java.lang.String-) | İşaretlenmiş içerik etiketini ayarlar |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün metin temsilini döndürür. |

### DP {#DP-int-com.aspose.pdf.engine.commondata.pagecontent.operators.markedcontent.DesignateMarkedContentWithProperties-}
Operatör sınıfı için yapıcı.

### DP {#DP-java.lang.String-}
Operatörü başlatır.

### DP {#DP-java.lang.String-com.aspose.ms.System.Collections.Generic.Dictionary-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getPropertiesDictionary {#getPropertiesDictionary--}
```
public com.aspose.ms.System.Collections.Generic.Dictionary< String ,com.aspose.pdf.engine.commondata.pagecontent.operators.commands.CommandParameter> getPropertiesDictionary()
```

Özellikler sözlüğünü alır

**Returns:**
IPdfDictionary değeri

### getTag {#getTag--}
```
public String getTag()
```

İşaretlenmiş içerik etiketini alır

**Returns:**
String değeri

### setPropertiesDictionary {#setPropertiesDictionary-com.aspose.ms.System.Collections.Generic.Dictionary-}
Özelliklerin sözlüğünü ayarlar

### setTag {#setTag-java.lang.String-}
İşaretlenmiş içerik etiketini ayarlar

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Yalnızca dahili kullanım için!

**Returns:**
ICommand değeri ICommand nesnesi

### toString {#toString--}
```
public String toString()
```

Operatörün metin temsilini döndürür.

**Returns:**
Operatörün metin temsili.
