---
title: "SetDash"
linktitle: "SetDash"
second_title: "Aspose.PDF for Java API Referansı"
description: "d operatörünü temsil eden sınıf (çizgi kesikli desenini ayarlar)."
type: docs
weight: 610
url: /tr/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

d operatörünü temsil eden sınıf (çizgi kesikli desenini ayarlar).

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Dash deseni ayarlama operatörünü oluşturur. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Operatör sınıfı için yapıcı. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Operatörü işlemek için ziyaretçi nesnesini kabul eder. |
| [getPattern](#getPattern--) | Dash deseni. Dizinin elemanları, dönüşümlü tire ve boşluk uzunluklarını belirten sayılar olmalıdır. Tek elemanlı bir dizi durumunda tire ve boşluk uzunlukları eşittir. |
| [getPhase](#getPhase--) | Dash aşaması. Bir yolu çizmeye başlamadan önce, dash dizisi döngüsel olarak kullanılacak ve dash ve boşlukların uzunlukları toplanacaktır. Birikmiş uzunluk dash aşaması tarafından belirtilen değere eşit olduğunda, yolun çizimi başlayacak ve dash dizisi o noktadan itibaren döngüsel olarak kullanılacaktır. |
| [setPattern](#setPattern-int:A-) | Dash deseni. Dizinin elemanları, dönüşümlü tire ve boşluk uzunluklarını belirten sayılar olmalıdır. Tek elemanlı bir dizi durumunda tire ve boşluk uzunlukları eşittir. |
| [setPhase](#setPhase-int-) | Dash aşaması. Bir yolu çizmeye başlamadan önce, dash dizisi döngüsel olarak kullanılacak ve dash ve boşlukların uzunlukları toplanacaktır. Birikmiş uzunluk dash aşaması tarafından belirtilen değere eşit olduğunda, yolun çizimi başlayacak ve dash dizisi o noktadan itibaren döngüsel olarak kullanılacaktır. |
| [toCommand](#toCommand--) | Yalnızca dahili kullanım için! |
| [toString](#toString--) | Operatörün dize temsili alınır. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Dash deseni ayarlama operatörünü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desen |  | Dash desenini tanımlayan dizi. |
| aşama |  | Dash aşaması. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Operatör sınıfı için yapıcı.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Operatörü işlemek için ziyaretçi nesnesini kabul eder.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Dash deseni. Dizinin elemanları, dönüşümlü tire ve boşluk uzunluklarını belirten sayılar olmalıdır. Tek elemanlı bir dizi durumunda tire ve boşluk uzunlukları eşittir.

**Returns:**
int dizisi

### getPhase {#getPhase--}
```
public int getPhase()
```

Dash aşaması. Bir yolu çizmeye başlamadan önce, dash dizisi döngüsel olarak kullanılacak ve dash ve boşlukların uzunlukları toplanacaktır. Birikmiş uzunluk dash aşaması tarafından belirtilen değere eşit olduğunda, yolun çizimi başlayacak ve dash dizisi o noktadan itibaren döngüsel olarak kullanılacaktır.

**Returns:**
int değer

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Dash deseni. Dizinin elemanları, dönüşümlü tire ve boşluk uzunluklarını belirten sayılar olmalıdır. Tek elemanlı bir dizi durumunda tire ve boşluk uzunlukları eşittir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int dizisi |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Dash aşaması. Bir yolu çizmeye başlamadan önce, dash dizisi döngüsel olarak kullanılacak ve dash ve boşlukların uzunlukları toplanacaktır. Birikmiş uzunluk dash aşaması tarafından belirtilen değere eşit olduğunda, yolun çizimi başlayacak ve dash dizisi o noktadan itibaren döngüsel olarak kullanılacaktır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

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

Operatörün dize temsili alınır.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
