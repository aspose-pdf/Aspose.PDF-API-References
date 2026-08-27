---
title: "SetTextLeading"
linktitle: "SetTextLeading"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas yang mewakili operator TL (mengatur leading teks)."
type: docs
weight: 740
url: /id/java/com.aspose.pdf.operators/settextleading/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.Operator, com.aspose.pdf.operators.TextOperator com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextOperator, com.aspose.pdf.operators.TextStateOperator com.aspose.pdf.operators.SetTextLeading, com.aspose.pdf.operators.TextStateOperator, com.aspose.pdf.operators.SetTextLeading

```
public class SetTextLeading extends TextStateOperator
```

Kelas yang mewakili operator TL (mengatur leading teks).

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SetTextLeading](#SetTextLeading-double-) | Konstruktor untuk operator teks leadign. |
| [SetTextLeading](#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Menerima objek pengunjung untuk memproses operator. |
| [getLeading](#getLeading--) | Mendapatkan leading teks. |
| [setLeading](#setLeading-double-) | Mengatur leading teks. |
| [toString](#toString--) | Menghasilkan kode teks operator. |

### SetTextLeading {#SetTextLeading-double-}
```
public SetTextLeading(double leading)
```

Konstruktor untuk operator teks leadign.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| leading |  | Leading teks. |

### SetTextLeading {#SetTextLeading-int-com.aspose.pdf.engine.commondata.pagecontent.operators.textstateoperators.SetTextLeading-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Menerima objek pengunjung untuk memproses operator.

### getLeading {#getLeading--}
```
public double getLeading()
```

Mendapatkan leading teks.

**Returns:**
nilai double

### setLeading {#setLeading-double-}
```
public void setLeading(double value)
```

Mengatur leading teks.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### toString {#toString--}
```
public String toString()
```

Menghasilkan kode teks operator.

**Returns:**
Representasi teks dari operator.
