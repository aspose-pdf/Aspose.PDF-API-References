---
title: "IPdfFileEditor.ContentsResizeValue"
linktitle: "IPdfFileEditor.ContentsResizeValue"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Nilai margin atau ukuran konten yang ditentukan dalam persentase satuan ruang default. Kelas ini digunakan dalam ContentsResizeParameters."
type: docs
weight: 310
url: /id/java/com.aspose.pdf.facades/ipdffileeditor.contentsresizevalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeValue

```
public static class IPdfFileEditor.ContentsResizeValue extends Object
```

Nilai margin atau ukuran konten yang ditentukan dalam persentase satuan ruang default. Kelas ini digunakan dalam ContentsResizeParameters.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [auto](#auto--) | Menginisialisasi nilai yang dihitung secara otomatis. |
| [getValue](#getValue--) | Mendapatkan nilai yang ditentukan. Gunakan properti Unit untuk mendapatkan satuan nilai. |
| [isPercent](#isPercent--) | Mengembalikan true jika nilai dinyatakan dalam persen; False jika nilai dinyatakan dalam satuan default. |
| [percents](#percents-double-) | Menginisialisasi nilai dalam persen. |
| [setPercentValue](#setPercentValue-double-) | Mengatur nilai dalam persen dari ukuran halaman. |
| [setUnitValue](#setUnitValue-double-) | Mengatur nilai dalam satuan ruang default. |
| [units](#units-double-) | Menginisialisasi nilai dalam satuan ruang default. |

### auto {#auto--}
```
public static IPdfFileEditor.ContentsResizeValue auto()
```

Menginisialisasi nilai yang dihitung secara otomatis.

**Returns:**
Instansi nilai baru.

### getValue {#getValue--}
```
public final double getValue()
```

Mendapatkan nilai yang ditentukan. Gunakan properti Unit untuk mendapatkan satuan nilai.

**Returns:**
nilai double

### isPercent {#isPercent--}
```
public final boolean isPercent()
```

Mengembalikan true jika nilai dinyatakan dalam persen; False jika nilai dinyatakan dalam satuan default.

**Returns:**
nilai boolean

### percents {#percents-double-}
```
public static IPdfFileEditor.ContentsResizeValue percents(double value)
```

Menginisialisasi nilai dalam persen.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai dalam persen. |

**Returns:**
Instansi nilai baru.

### setPercentValue {#setPercentValue-double-}
```
public final void setPercentValue(double value)
```

Mengatur nilai dalam persen dari ukuran halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### setUnitValue {#setUnitValue-double-}
```
public final void setUnitValue(double value)
```

Mengatur nilai dalam satuan ruang default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai double |

### units {#units-double-}
```
public static IPdfFileEditor.ContentsResizeValue units(double value)
```

Menginisialisasi nilai dalam satuan ruang default.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Nilai dalam satuan. |

**Returns:**
Instansi nilai baru.
