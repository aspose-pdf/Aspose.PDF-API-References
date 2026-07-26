---
title: "TabStop"
linktitle: "TabStop"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili posisi henti Tab khusus dalam paragraf."
type: docs
weight: 4840
url: /id/java/com.aspose.pdf/tabstop/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TabStop

```
public class TabStop extends Object
```

Mewakili posisi henti Tab khusus dalam paragraf.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TabStop](#TabStop--) | Menginisialisasi sebuah instance baru dari kelas {@code TabStop}. |
| [TabStop](#TabStop-float-) | Menginisialisasi sebuah instance baru dari kelas {@code TabStop} dengan posisi yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAlignmentType](#getAlignmentType--) | Mendapatkan atau mengatur enum {@code AlignmentType} yang menunjukkan jenis perataan tab. |
| [getLeaderType](#getLeaderType--) | Mendapatkan atau mengatur enum {@code TabLeaderType} yang menunjukkan jenis pemimpin tab. |
| [getPosition](#getPosition--) | Mendapatkan atau mengatur nilai float yang menunjukkan posisi tab stop. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan bahwa instance {@code TabStop} ini sudah terlampir pada {@code TextFragment} dan menjadi readonly |
| [setAlignmentType](#setAlignmentType-int-) | Mendapatkan atau mengatur enum {@code AlignmentType} yang menunjukkan jenis perataan tab. |
| [setLeaderType](#setLeaderType-int-) | Mendapatkan atau mengatur enum {@code TabLeaderType} yang menunjukkan jenis pemimpin tab. |
| [setPosition](#setPosition-float-) | Mengatur nilai float yang menunjukkan posisi tab stop. |

### TabStop {#TabStop--}
```
public TabStop()
```

Menginisialisasi sebuah instance baru dari kelas {@code TabStop}.

### TabStop {#TabStop-float-}
```
public TabStop(float position)
```

Menginisialisasi sebuah instance baru dari kelas {@code TabStop} dengan posisi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| posisi |  | Posisi tab stop. |

### getAlignmentType {#getAlignmentType--}
```
public int getAlignmentType()
```

Mendapatkan atau mengatur enum {@code AlignmentType} yang menunjukkan jenis perataan tab.

**Returns:**
TabAlignmentType elemen @see TabAlignmentType

### getLeaderType {#getLeaderType--}
```
public int getLeaderType()
```

Mendapatkan atau mengatur enum {@code TabLeaderType} yang menunjukkan jenis pemimpin tab.

**Returns:**
TabLeaderType elemen @see TabLeaderType

### getPosition {#getPosition--}
```
public float getPosition()
```

Mendapatkan atau mengatur nilai float yang menunjukkan posisi tab stop.

**Returns:**
nilai float

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan bahwa instance {@code TabStop} ini sudah terlampir pada {@code TextFragment} dan menjadi readonly

**Returns:**
nilai boolean

### setAlignmentType {#setAlignmentType-int-}
```
public void setAlignmentType(int value)
```

Mendapatkan atau mengatur enum {@code AlignmentType} yang menunjukkan jenis perataan tab.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | TabAlignmentType elemen @see TabAlignmentType |

### setLeaderType {#setLeaderType-int-}
```
public void setLeaderType(int value)
```

Mendapatkan atau mengatur enum {@code TabLeaderType} yang menunjukkan jenis pemimpin tab.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | TabLeaderType elemen @see TabLeaderType |

### setPosition {#setPosition-float-}
```
public void setPosition(float value)
```

Mengatur nilai float yang menunjukkan posisi tab stop.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai float |
