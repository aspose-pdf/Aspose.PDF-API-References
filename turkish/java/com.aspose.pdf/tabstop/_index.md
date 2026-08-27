---
title: "TabStop"
linktitle: "TabStop"
second_title: "Aspose.PDF for Java API Referansı"
description: "Paragrafta özel bir sekme durak konumunu temsil eder."
type: docs
weight: 4840
url: /tr/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Paragrafta özel bir sekme durak konumunu temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TabStop](#TabStop--) | Yeni bir {@code TabStop} sınıfı örneği oluşturur. |
| [TabStop](#TabStop-float-) | Belirtilen konumla yeni bir {@code TabStop} sınıfı örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Alır veya ayarlar bir {@code AlignmentType} enum değerini, sekme hizalama tipini gösterir. |
| [getLeaderType](#getLeaderType--) | Alır veya ayarlar bir {@code TabLeaderType} enum değerini, sekme lideri tipini gösterir. |
| [getPosition](#getPosition--) | Alır veya ayarlar bir float değerini, sekme durak konumunu gösterir. |
| [isReadOnly](#isReadOnly--) | Bu {@code TabStop} örneğinin zaten {@code TextFragment}'e eklendiğini ve salt okunur hâle geldiğini gösteren değeri alır. |
| [setAlignmentType](#setAlignmentType-int-) | Alır veya ayarlar bir {@code AlignmentType} enum değerini, sekme hizalama tipini gösterir. |
| [setLeaderType](#setLeaderType-int-) | Alır veya ayarlar bir {@code TabLeaderType} enum değerini, sekme lideri tipini gösterir. |
| [setPosition](#setPosition-float-) | Sekme durak konumunu gösteren bir float değerini ayarlar. |

### TabStop {#TabStop--}
```
public TabStop()
```

Yeni bir {@code TabStop} sınıfı örneği oluşturur.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Belirtilen konumla yeni bir {@code TabStop} sınıfı örneği oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| konum |  | Sekme durakının konumu. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Alır veya ayarlar bir {@code AlignmentType} enum değerini, sekme hizalama tipini gösterir.

**Returns:**
TabAlignmentType öğesi @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Alır veya ayarlar bir {@code TabLeaderType} enum değerini, sekme lideri tipini gösterir.

**Returns:**
TabLeaderType öğesi @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Alır veya ayarlar bir float değerini, sekme durak konumunu gösterir.

**Returns:**
float değer

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Bu {@code TabStop} örneğinin zaten {@code TextFragment}'e eklendiğini ve salt okunur hâle geldiğini gösteren değeri alır.

**Returns:**
boolean değer

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Alır veya ayarlar bir {@code AlignmentType} enum değerini, sekme hizalama tipini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TabAlignmentType öğesi @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Alır veya ayarlar bir {@code TabLeaderType} enum değerini, sekme lideri tipini gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TabLeaderType öğesi @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Sekme durak konumunu gösteren bir float değerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |
