---
title: "SoundData"
linktitle: "SoundData"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili data suara yang menentukan suara yang akan diputar saat anotasi diaktifkan."
type: docs
weight: 4540
url: /id/java/com.aspose.pdf/sounddata/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SoundData

```
public final class SoundData extends Object
```

Mewakili data suara yang menentukan suara yang akan diputar saat anotasi diaktifkan.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBits](#getBits--) | Mendapatkan jumlah bit per nilai sampel per kanal. |
| [getChannels](#getChannels--) | Mendapatkan jumlah saluran suara. |
| [getContents](#getContents--) | Mendapatkan aliran suara yang akan diputar ketika anotasi diaktifkan. |
| [getContentsInternal](#getContentsInternal--) | Mendapatkan aliran suara yang akan diputar ketika anotasi diaktifkan. |
| [getEncoding](#getEncoding--) | Mendapatkan format enkoding untuk data sampel. |
| [getRate](#getRate--) | Mendapatkan laju sampling, dalam sampel per detik. |
| [setBits](#setBits-int-) | Mengatur jumlah bit per nilai sampel per kanal. |
| [setChannels](#setChannels-int-) | Mengatur jumlah saluran suara. |
| [setEncoding](#setEncoding-int-) | Mengatur format enkoding untuk data sampel. |
| [setRate](#setRate-int-) | Mengatur laju sampling, dalam sampel per detik. |

### getBits {#getBits--}
```
public int getBits()
```

Mendapatkan jumlah bit per nilai sampel per kanal.

**Returns:**
int nilai jumlah bit

### getChannels {#getChannels--}
```
public int getChannels()
```

Mendapatkan jumlah saluran suara.

**Returns:**
Jumlah saluran suara.

### getContents {#getContents--}
```
public InputStream getContents()
```

Mendapatkan aliran suara yang akan diputar ketika anotasi diaktifkan.

**Returns:**
nilai InputStream

### getContentsInternal {#getContentsInternal--}
```
public com.aspose.ms.System.IO.Stream getContentsInternal()
```

Mendapatkan aliran suara yang akan diputar ketika anotasi diaktifkan.

**Returns:**
nilai Stream

### getEncoding {#getEncoding--}
```
public int getEncoding()
```

Mendapatkan format enkoding untuk data sampel.

**Returns:**
nilai SoundEncoding @see SoundEncoding

### getRate {#getRate--}
```
public int getRate()
```

Mendapatkan laju sampling, dalam sampel per detik.

**Returns:**
nilai int

### setBits {#setBits-int-}
```
public void setBits(int value)
```

Mengatur jumlah bit per nilai sampel per kanal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | jumlah bit |

### setChannels {#setChannels-int-}
```
public void setChannels(int value)
```

Mengatur jumlah saluran suara.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Jumlah saluran suara. |

### setEncoding {#setEncoding-int-}
```
public void setEncoding(int value)
```

Mengatur format enkoding untuk data sampel.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai SoundEncoding @see SoundEncoding |

### setRate {#setRate-int-}
```
public void setRate(int value)
```

Mengatur laju sampling, dalam sampel per detik.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
