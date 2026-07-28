---
title: "SoundData"
linktitle: "SoundData"
second_title: "Aspose.PDF for Java API Referansı"
description: "Açıklama etkinleştirildiğinde çalınacak sesi tanımlayan ses verisini temsil eder."
type: docs
weight: 4540
url: /tr/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Açıklama etkinleştirildiğinde çalınacak sesi tanımlayan ses verisini temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBits](#getBits--) | Kanal başına örnek değeri başına bit sayısını alır. |
| [getChannels](#getChannels--) | Ses kanallarının sayısını alır. |
| [getContents](#getContents--) | Ek açıklama etkinleştirildiğinde çalınacak ses akışını alır. |
| [getContentsInternal](#getContentsInternal--) | Ek açıklama etkinleştirildiğinde çalınacak ses akışını alır. |
| [getEncoding](#getEncoding--) | Örnek verileri için kodlama biçimini alır. |
| [getRate](#getRate--) | Saniyedeki örnek sayısı olarak örnekleme oranını alır. |
| [setBits](#setBits-int-) | Kanal başına örnek değeri başına bit sayısını ayarlar. |
| [setChannels](#setChannels-int-) | Ses kanallarının sayısını ayarlar. |
| [setEncoding](#setEncoding-int-) | Örnek verileri için kodlama biçimini ayarlar. |
| [setRate](#setRate-int-) | Saniyedeki örnek sayısı olarak örnekleme oranını ayarlar. |

### getBits {#getBits--}
```
public int getBits()
```

Kanal başına örnek değeri başına bit sayısını alır.

**Returns:**
int değer bit sayısı

### getChannels {#getChannels--}
```
public int getChannels()
```

Ses kanallarının sayısını alır.

**Returns:**
Ses kanallarının sayısı.

### getContents {#getContents--}
```
public InputStream getContents()
```

Ek açıklama etkinleştirildiğinde çalınacak ses akışını alır.

**Returns:**
InputStream değeri

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Ek açıklama etkinleştirildiğinde çalınacak ses akışını alır.

**Returns:**
Akış değeri

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Örnek verileri için kodlama biçimini alır.

**Returns:**
SoundEncoding değeri @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Saniyedeki örnek sayısı olarak örnekleme oranını alır.

**Returns:**
int değer

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Kanal başına örnek değeri başına bit sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | bit sayısı |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Ses kanallarının sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | Ses kanallarının sayısı. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Örnek verileri için kodlama biçimini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | SoundEncoding değeri @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Saniyedeki örnek sayısı olarak örnekleme oranını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
