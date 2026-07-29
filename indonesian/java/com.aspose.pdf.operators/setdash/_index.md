---
title: "SetDash"
linktitle: "SetDash"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator d (mengatur pola dash garis)."
type: docs
weight: 610
url: /id/java/com.aspose.pdf.operators/setdash/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetDash, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetDash

```
public class SetDash extends Operator
```

Kelas yang mewakili operator d (mengatur pola dash garis).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetDash](#SetDash-int:A-int-) | Membuat operator pola dash set. |
| [SetDash](#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getPattern](#getPattern--) | Pola dash. Elemen array harus berupa angka yang menentukan panjang dash dan celah yang bergantian. Jika array hanya memiliki satu elemen, panjang dash dan celah adalah sama. |
| [getPhase](#getPhase--) | Fase dash. Sebelum memulai menggambar (stroke) sebuah jalur, array dash harus diputar, menambahkan panjang dash dan celah. Ketika panjang yang terakumulasi sama dengan nilai yang ditentukan oleh fase dash, proses menggambar jalur akan dimulai, dan array dash akan digunakan secara siklik dari titik itu ke depan. |
| [setPattern](#setPattern-int:A-) | Pola dash. Elemen array harus berupa angka yang menentukan panjang dash dan celah yang bergantian. Jika array hanya memiliki satu elemen, panjang dash dan celah adalah sama. |
| [setPhase](#setPhase-int-) | Fase dash. Sebelum memulai menggambar (stroke) sebuah jalur, array dash harus diputar, menambahkan panjang dash dan celah. Ketika panjang yang terakumulasi sama dengan nilai yang ditentukan oleh fase dash, proses menggambar jalur akan dimulai, dan array dash akan digunakan secara siklik dari titik itu ke depan. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |
| [toString](#toString--) | Mendapatkan representasi string operator. |

### SetDash {#SetDash-int:A-int-}
```
public SetDash(int[] pattern, int phase)
```

Membuat operator pola dash set.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pola |  | Array yang mendefinisikan pola dash. |
| fase |  | Fase dash. |

### SetDash {#SetDash-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetLineDashPattern-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getPattern {#getPattern--}
```
public int[] getPattern()
```

Pola dash. Elemen array harus berupa angka yang menentukan panjang dash dan celah yang bergantian. Jika array hanya memiliki satu elemen, panjang dash dan celah adalah sama.

**Returns:**
array int

### getPhase {#getPhase--}
```
public int getPhase()
```

Fase dash. Sebelum memulai menggambar (stroke) sebuah jalur, array dash harus diputar, menambahkan panjang dash dan celah. Ketika panjang yang terakumulasi sama dengan nilai yang ditentukan oleh fase dash, proses menggambar jalur akan dimulai, dan array dash akan digunakan secara siklik dari titik itu ke depan.

**Returns:**
nilai int

### setPattern {#setPattern-int:A-}
```
public void setPattern(int[] value)
```

Pola dash. Elemen array harus berupa angka yang menentukan panjang dash dan celah yang bergantian. Jika array hanya memiliki satu elemen, panjang dash dan celah adalah sama.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | array int |

### setPhase {#setPhase-int-}
```
public void setPhase(int value)
```

Fase dash. Sebelum memulai menggambar (stroke) sebuah jalur, array dash harus diputar, menambahkan panjang dash dan celah. Ketika panjang yang terakumulasi sama dengan nilai yang ditentukan oleh fase dash, proses menggambar jalur akan dimulai, dan array dash akan digunakan secara siklik dari titik itu ke depan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Hanya untuk penggunaan internal!

**Returns:**
ICommand nilai objek ICommand

### toString {#toString--}
```
public String toString()
```

Mendapatkan representasi string operator.

**Returns:**
[x1 x2] y d, where x1 - dash length, x2 - gap length, y - phase.
