---
title: "HtmlFragment"
linktitle: "HtmlFragment"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili fragmen HTML."
type: docs
weight: 1950
url: /id/java/com.aspose.pdf/htmlfragment/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FormattedFragment com.aspose.pdf.HtmlFragment, com.aspose.pdf.FormattedFragment, com.aspose.pdf.HtmlFragment

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class HtmlFragment extends FormattedFragment
```

Mewakili fragmen HTML.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [HtmlFragment](#HtmlFragment-java.lang.String-) | Menginisialisasi instance baru dari kelas HtmlFragment. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [deepClone](#deepClone--) | Mengkloning fragmen html. |
| [getHtmlLoadOptions](#getHtmlLoadOptions--) | Mendapatkan HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ketika diperlukan pengaturan khusus untuk impor HTML bagi instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk HTML yang diimpor atau harus menggunakan pemuat sumber daya eksternal khusus). Jika parameter bernilai default (null), maka opsi pemuatan HTML standar akan digunakan. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang HtmlFragment |
| [getTextState](#getTextState--) | Mendapatkan atau mengatur font |
| [isBreakWords](#isBreakWords--) | Mendapatkan atau mengatur pemisahan kata |
| [isParagraphHasMargin](#isParagraphHasMargin--) | Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0 |
| [setBreakWords](#setBreakWords-boolean-) | Mendapatkan atau mengatur pemisahan kata |
| [setHtmlLoadOptions](#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-) | Mengatur HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ketika diperlukan pengaturan khusus untuk impor HTML bagi instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk HTML yang diimpor atau harus menggunakan pemuat sumber daya eksternal khusus). Jika parameter bernilai default (null), maka opsi pemuatan HTML standar akan digunakan. |
| [setParagraphHasMargin](#setParagraphHasMargin-boolean-) | Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0 |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Mendapatkan atau mengatur font |

### HtmlFragment {#HtmlFragment-java.lang.String-}
Menginisialisasi instance baru dari kelas HtmlFragment.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Mengkloning fragmen html.

**Returns:**
Objek fragmen html yang dikloning.

### getHtmlLoadOptions {#getHtmlLoadOptions--}
```
public HtmlLoadOptions getHtmlLoadOptions()
```

Mendapatkan HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ketika diperlukan pengaturan khusus untuk impor HTML bagi instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk HTML yang diimpor atau harus menggunakan pemuat sumber daya eksternal khusus). Jika parameter bernilai default (null), maka opsi pemuatan HTML standar akan digunakan.

**Returns:**
Nilai HtmlLoadOptions

### getRectangle {#getRectangle--}
```
public final Rectangle2D.Float getRectangle()
```

Mendapatkan persegi panjang HtmlFragment

**Returns:**
java.awt.geom.Rectangle2D.Float instance

### getTextState {#getTextState--}
```
public TextState getTextState()
```

Mendapatkan atau mengatur font

**Returns:**
Objek TextState

### isBreakWords {#isBreakWords--}
```
public final boolean isBreakWords()
```

Mendapatkan atau mengatur pemisahan kata

**Returns:**
nilai boolean

### isParagraphHasMargin {#isParagraphHasMargin--}
```
public final boolean isParagraphHasMargin()
```

Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0

**Returns:**
nilai boolean

### setBreakWords {#setBreakWords-boolean-}
```
public final void setBreakWords(boolean value)
```

Mendapatkan atau mengatur pemisahan kata

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setHtmlLoadOptions {#setHtmlLoadOptions-com.aspose.pdf.HtmlLoadOptions-}
Mengatur HtmlLoadOptions yang akan digunakan untuk memuat (dan merender) HTML ke dalam instance kelas ini. Harap gunakan ketika diperlukan pengaturan khusus untuk impor HTML bagi instance ini atau itu (misalnya ketika instance ini atau itu harus menggunakan BasePath khusus untuk HTML yang diimpor atau harus menggunakan pemuat sumber daya eksternal khusus). Jika parameter bernilai default (null), maka opsi pemuatan HTML standar akan digunakan.

### setParagraphHasMargin {#setParagraphHasMargin-boolean-}
```
public final void setParagraphHasMargin(boolean value)
```

Mendapatkan atau mengatur apakah paragraf memiliki margin default, jika tidak margin adalah 0

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Mendapatkan atau mengatur font
