---
title: "Çizgi"
linktitle: "Çizgi"
second_title: "Aspose.PDF for Java API Referansı"
description: "Çizgi kesik desenini temsil eden sınıf."
type: docs
weight: 910
url: /tr/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Çizgi kesik desenini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Dash](#Dash-int:A-) | Dash için yapıcı. Kesikli bir kenarlık çizerken kullanılacak tire ve boşluk desenini tanımlar. |
| [Dash](#Dash-int-int-) | Dash için yapıcı. Belirtilen tire ve boşlukla kesikli kenarlık tanımlar; bu değerler tüm kesikli kenarlık boyunca değişmez. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOff](#getOff--) | Tireler arasındaki ilk boşluğun uzunluğunu alır veya ayarlar. |
| [getOn](#getOn--) | İlk tırnin uzunluğunu alır veya ayarlar. |
| [getPattern](#getPattern--) | Kesikli bir kenarlık çizerken kullanılacak tire ve boşluk desenini tanımlayan tire dizisini alır. |
| [setOff](#setOff-int-) | Tireler arasındaki ilk boşluğun uzunluğunu alır veya ayarlar. |
| [setOn](#setOn-int-) | İlk tırnin uzunluğunu alır veya ayarlar. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Dash için yapıcı. Kesikli bir kenarlık çizerken kullanılacak tire ve boşluk desenini tanımlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| desen |  | Kesikli bir kenarlık çizerken kullanılacak tire ve boşluk desenini tanımlayan (en az iki değer içeren) bir tire dizisi. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Dash için yapıcı. Belirtilen tire ve boşlukla kesikli kenarlık tanımlar; bu değerler tüm kesikli kenarlık boyunca değişmez.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| açık |  | Tırnin uzunluğu. |
| kapalı |  | Boşluğun uzunluğu. |

### getOff {#getOff--}
```
public final int getOff()
```

Tireler arasındaki ilk boşluğun uzunluğunu alır veya ayarlar.

**Returns:**
int değer

### getOn {#getOn--}
```
public final int getOn()
```

İlk tırnin uzunluğunu alır veya ayarlar.

**Returns:**
int değer

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Kesikli bir kenarlık çizerken kullanılacak tire ve boşluk desenini tanımlayan tire dizisini alır.

**Returns:**
int dizisi

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Tireler arasındaki ilk boşluğun uzunluğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

İlk tırnin uzunluğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
