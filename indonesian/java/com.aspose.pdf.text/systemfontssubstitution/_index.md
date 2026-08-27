---
title: "SystemFontsSubstitution"
linktitle: "SystemFontsSubstitution"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk strategi substitusi font yang menggantikan font dengan font sistem."
type: docs
weight: 110
url: /id/java/com.aspose.pdf.text/systemfontssubstitution/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.text.FontSubstitution com.aspose.pdf.text.SystemFontsSubstitution, com.aspose.pdf.text.FontSubstitution, com.aspose.pdf.text.SystemFontsSubstitution

```
public final class SystemFontsSubstitution extends FontSubstitution
```

Mewakili kelas untuk strategi substitusi font yang menggantikan font dengan font sistem.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [SystemFontsSubstitution](#SystemFontsSubstitution-int-) | Menginisialisasi instance baru dari kelas {@code SystemFontsSubstitution}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDefaultFont](#getDefaultFont--) | Mendapatkan atau mengatur font substitusi default. Font ini digunakan ketika tidak ada substitusi valid lain yang ditemukan tetapi font awal termasuk dalam kategori substitusi target ({@code FontCategories}). |
| [getFontCategories](#getFontCategories--) | Mendapatkan atau mengatur kategori font substitusi yang harus diganti dengan font sistem. |
| [setDefaultFont](#setDefaultFont-com.aspose.pdf.Font-) | Mendapatkan atau mengatur font substitusi default. Font ini digunakan ketika tidak ada substitusi valid lain yang ditemukan tetapi font awal termasuk dalam kategori substitusi target ({@code FontCategories}). |
| [setFontCategories](#setFontCategories-int-) | Mendapatkan atau mengatur kategori font substitusi yang harus diganti dengan font sistem. |

### SystemFontsSubstitution {#SystemFontsSubstitution-int-}
```
public SystemFontsSubstitution(int fontCategories)
```

Menginisialisasi instance baru dari kelas {@code SystemFontsSubstitution}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontCategories |  | Kategori font target untuk diganti dengan font sistem |

### getDefaultFont {#getDefaultFont--}
```
public Font getDefaultFont()
```

Mendapatkan atau mengatur font substitusi default. Font ini digunakan ketika tidak ada substitusi valid lain yang ditemukan tetapi font awal termasuk dalam kategori substitusi target ({@code FontCategories}).

**Returns:**
objek Font

### getFontCategories {#getFontCategories--}
```
public int getFontCategories()
```

Mendapatkan atau mengatur kategori font substitusi yang harus diganti dengan font sistem.

**Returns:**
elemen SubstitutionFontCategories @see SubstitutionFontCategories

### setDefaultFont {#setDefaultFont-com.aspose.pdf.Font-}
Mendapatkan atau mengatur font substitusi default. Font ini digunakan ketika tidak ada substitusi valid lain yang ditemukan tetapi font awal termasuk dalam kategori substitusi target ({@code FontCategories}).

### setFontCategories {#setFontCategories-int-}
```
public void setFontCategories(int value)
```

Mendapatkan atau mengatur kategori font substitusi yang harus diganti dengan font sistem.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen SubstitutionFontCategories @see SubstitutionFontCategories |
