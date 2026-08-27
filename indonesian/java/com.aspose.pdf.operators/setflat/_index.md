---
title: "SetFlat"
linktitle: "SetFlat"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator i (mengatur toleransi kelandutan)."
type: docs
weight: 620
url: /id/java/com.aspose.pdf.operators/setflat/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.SetFlat, com.aspose.pdf.Operator, com.aspose.pdf.operators.SetFlat

```
public class SetFlat extends Operator
```

Kelas yang mewakili operator i (mengatur toleransi kelandutan).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetFlat](#SetFlat-double-) | Menginisialisasi operator. |
| [SetFlat](#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-) | Konstruktor untuk kelas operator. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getFlatness](#getFlatness--) | Mendapatkan kelancaran. |
| [setFlatness](#setFlatness-double-) | Mengatur kelancaran. |
| [toCommand](#toCommand--) | Hanya untuk penggunaan internal! |

### SetFlat {#SetFlat-double-}
```
public SetFlat(double flatness)
```

Menginisialisasi operator.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| kekasaran |  | Nilai kekasaran. |

### SetFlat {#SetFlat-int-com.aspose.pdf.engine.commondata.pagecontent.operators.graphicstateoperators.SetFlatnessTolerance-}
Konstruktor untuk kelas operator.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getFlatness {#getFlatness--}
```
public double getFlatness()
```

Mendapatkan kelancaran.

**Returns:**
nilai double

### setFlatness {#setFlatness-double-}
```
public void setFlatness(double value)
```

Mengatur kelancaran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

Hanya untuk penggunaan internal!

**Returns:**
ICommand nilai objek ICommand
