---
title: "Garis"
linktitle: "Garis"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang merepresentasikan pola dash garis."
type: docs
weight: 910
url: /id/java/com.aspose.pdf/dash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Dash

```
public final class Dash extends Object
```

Kelas yang merepresentasikan pola dash garis.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Dash](#Dash-int:A-) | Konstruktor untuk Dash. Mendefinisikan pola garis putus-putus dan celah yang akan digunakan dalam menggambar batas bergaris putus. |
| [Dash](#Dash-int-int-) | Konstruktor untuk Dash. Mendefinisikan batas bergaris putus dengan dash dan celah yang ditentukan, yang tidak berubah untuk seluruh batas bergaris putus. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOff](#getOff--) | Mendapatkan atau mengatur panjang celah pertama antara dash. |
| [getOn](#getOn--) | Mendapatkan atau mengatur panjang dash pertama. |
| [getPattern](#getPattern--) | Mendapatkan array dash yang mendefinisikan pola dash dan celah yang akan digunakan dalam menggambar batas bergaris putus. |
| [setOff](#setOff-int-) | Mendapatkan atau mengatur panjang celah pertama antara dash. |
| [setOn](#setOn-int-) | Mendapatkan atau mengatur panjang dash pertama. |

### Dash {#Dash-int:A-}
```
public Dash(int[] pattern)
```

Konstruktor untuk Dash. Mendefinisikan pola garis putus-putus dan celah yang akan digunakan dalam menggambar batas bergaris putus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pola |  | Array dash (minimal dua nilai) yang mendefinisikan pola dash dan celah yang akan digunakan dalam menggambar batas bergaris putus. |

### Dash {#Dash-int-int-}
```
public Dash(int on, int off)
```

Konstruktor untuk Dash. Mendefinisikan batas bergaris putus dengan dash dan celah yang ditentukan, yang tidak berubah untuk seluruh batas bergaris putus.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nyala |  | Panjang dash. |
| mati |  | Panjang celah. |

### getOff {#getOff--}
```
public final int getOff()
```

Mendapatkan atau mengatur panjang celah pertama antara dash.

**Returns:**
nilai int

### getOn {#getOn--}
```
public final int getOn()
```

Mendapatkan atau mengatur panjang dash pertama.

**Returns:**
nilai int

### getPattern {#getPattern--}
```
public final int[] getPattern()
```

Mendapatkan array dash yang mendefinisikan pola dash dan celah yang akan digunakan dalam menggambar batas bergaris putus.

**Returns:**
array int

### setOff {#setOff-int-}
```
public final void setOff(int value)
```

Mendapatkan atau mengatur panjang celah pertama antara dash.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setOn {#setOn-int-}
```
public final void setOn(int value)
```

Mendapatkan atau mengatur panjang dash pertama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
