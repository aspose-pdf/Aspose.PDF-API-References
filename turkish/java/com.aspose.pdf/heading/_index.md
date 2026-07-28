---
title: "Başlık"
linktitle: "Başlık"
second_title: "Aspose.PDF for Java API Referansı"
description: "Başlığı temsil eder."
type: docs
weight: 1890
url: /tr/java/com.aspose.pdf/heading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.BaseParagraph, com.aspose.pdf.TextFragment com.aspose.pdf.Heading, com.aspose.pdf.TextFragment, com.aspose.pdf.Heading

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Heading extends TextFragment
```

Başlığı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Heading](#Heading--) | Yalnızca dahili kullanım için |
| [Heading](#Heading-int-) | Cell sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [cloneWithSegments](#cloneWithSegments--) | Başlığı tüm bölümleriyle kopyalar. |
| [deepClone](#deepClone--) | Başlığı kopyalar. |
| [getDestinationPage](#getDestinationPage--) | Hedef sayfayı alır. |
| [getLevel](#getLevel--) | Seviyeyi alır. |
| [getStartNumber](#getStartNumber--) | Başlık başlangıç numarasını alır. |
| [getStyle](#getStyle--) | Stili alır veya ayarlar. |
| [getTocPage](#getTocPage--) | Bu başlığı içeren sayfayı alır. |
| [getTop](#getTop--) | Bu başlıkların üst Y değerini alır (dahili kullanım için). |
| [getUserLabel](#getUserLabel--) | Kullanıcı etiketini alır veya ayarlar. |
| [isAutoSequence](#isAutoSequence--) | Başlığın otomatik olarak numaralandırılması gerekip gerekmediğini alır. |
| [isInList](#isInList--) | Başlığın içindekiler listesinde olup olmadığını alır. |
| [setAutoSequence](#setAutoSequence-boolean-) | Başlığın otomatik olarak numaralandırılması gerektiğini ayarlar. |
| [setDestinationPage](#setDestinationPage-com.aspose.pdf.Page-) | Hedef sayfayı ayarlar. |
| [setInList](#setInList-boolean-) | Başlığın içindekiler listesinde olması gerektiğini ayarlar. |
| [setLevel](#setLevel-int-) | seviyeyi ayarlar. |
| [setStartNumber](#setStartNumber-int-) | Başlığın başlangıç numarasını alır. Değer: The startNumber. |
| [setStyle](#setStyle-com.aspose.pdf.NumberingStyle-) | stili ayarlar ya da ayarlar. |
| [setTocPage](#setTocPage-com.aspose.pdf.Page-) | Bu başlığı içeren sayfayı ayarlar. |
| [setTop](#setTop-double-) | Bu başlıkların üst Y değerini ayarlar (iç kullanım için). |
| [setUserLabel](#setUserLabel-com.aspose.pdf.TextSegment-) | Kullanıcı etiketini alır veya ayarlar. |

### Heading {#Heading--}
```
public Heading()
```

Yalnızca dahili kullanım için

### Heading {#Heading-int-}
```
public Heading(int level)
```

Cell sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| seviye |  | Başlık seviyesi. |

### cloneWithSegments {#cloneWithSegments--}
```
public Object cloneWithSegments()
```

Başlığı tüm bölümleriyle kopyalar.

**Returns:**
Klonlanmış nesne

### deepClone {#deepClone--}
```
public Object deepClone()
```

Başlığı kopyalar.

**Returns:**
Klonlanmış nesne

### getDestinationPage {#getDestinationPage--}
```
public Page getDestinationPage()
```

Hedef sayfayı alır.

**Returns:**
Hedef sayfa.

### getLevel {#getLevel--}
```
public int getLevel()
```

Seviyeyi alır.

**Returns:**
Başlık seviyesi.

### getStartNumber {#getStartNumber--}
```
public int getStartNumber()
```

Başlık başlangıç numarasını alır.

**Returns:**
Değer: The startNumber.

### getStyle {#getStyle--}
```
public NumberingStyle getStyle()
```

Stili alır veya ayarlar.

**Returns:**
Başlık stili.

### getTocPage {#getTocPage--}
```
public Page getTocPage()
```

Bu başlığı içeren sayfayı alır.

**Returns:**
Sayfa.

### getTop {#getTop--}
```
public double getTop()
```

Bu başlıkların üst Y değerini alır (dahili kullanım için).

**Returns:**
Üst Y değeri

### getUserLabel {#getUserLabel--}
```
public TextSegment getUserLabel()
```

Kullanıcı etiketini alır veya ayarlar.

**Returns:**
TextSegment nesnesi

### isAutoSequence {#isAutoSequence--}
```
public boolean isAutoSequence()
```

Başlığın otomatik olarak numaralandırılması gerekip gerekmediğini alır.

**Returns:**
Bu IsAutoSequens.

### isInList {#isInList--}
```
public boolean isInList()
```

Başlığın içindekiler listesinde olup olmadığını alır.

**Returns:**
Bu IsInList.

### setAutoSequence {#setAutoSequence-boolean-}
```
public void setAutoSequence(boolean value)
```

Başlığın otomatik olarak numaralandırılması gerektiğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Bu IsAutoSequens. |

### setDestinationPage {#setDestinationPage-com.aspose.pdf.Page-}
Hedef sayfayı ayarlar.

### setInList {#setInList-boolean-}
```
public void setInList(boolean value)
```

Başlığın içindekiler listesinde olması gerektiğini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Bu IsInList. |

### setLevel {#setLevel-int-}
```
public void setLevel(int value)
```

seviyeyi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Başlık seviyesi. |

### setStartNumber {#setStartNumber-int-}
```
public void setStartNumber(int value)
```

Başlığın başlangıç numarasını alır. Değer: The startNumber.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Bu startNumber. |

### setStyle {#setStyle-com.aspose.pdf.NumberingStyle-}
stili ayarlar ya da ayarlar.

### setTocPage {#setTocPage-com.aspose.pdf.Page-}
Bu başlığı içeren sayfayı ayarlar.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Bu başlıkların üst Y değerini ayarlar (iç kullanım için).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Üst Y değeri |

### setUserLabel {#setUserLabel-com.aspose.pdf.TextSegment-}
Kullanıcı etiketini alır veya ayarlar.
