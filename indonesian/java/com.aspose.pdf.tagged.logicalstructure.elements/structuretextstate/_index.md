---
title: "StructureTextState"
linktitle: "StructureTextState"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili pengaturan status teks untuk Elemen Struktur Teks dan TaggedContent (ITextElement, ITaggedContent)"
type: docs
weight: 120
url: /id/java/com.aspose.pdf.tagged.logicalstructure.elements/structuretextstate/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState

```
public class StructureTextState extends Object
```

Mewakili pengaturan status teks untuk Elemen Struktur Teks dan TaggedContent (ITextElement, ITaggedContent)

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [StructureTextState](#StructureTextState--) | Konstruktor default |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [createTextState](#createTextState--) | Buat Status Teks |
| [getBackgroundColor](#getBackgroundColor--) | Mendapatkan atau mengatur warna latar belakang teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code BackgroundColor} dari elemen struktur induk. |
| [getCharacterSpacing](#getCharacterSpacing--) | Mendapatkan atau mengatur spasi karakter teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code CharacterSpacing} dari elemen struktur induk. |
| [getFont](#getFont--) | Mendapatkan atau mengatur font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Font} dari elemen struktur induk. |
| [getFontSize](#getFontSize--) | Mendapatkan atau mengatur ukuran font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code FontSize} dari elemen struktur induk. |
| [getFontStyle](#getFontStyle--) | Mendapatkan atau mengatur gaya font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code FontStyle} dari elemen struktur induk. |
| [getForegroundColor](#getForegroundColor--) | Mendapatkan atau mengatur warna latar depan teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code ForegroundColor} dari elemen struktur induk. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan atau mengatur perataan horizontal paragraf |
| [getHorizontalScaling](#getHorizontalScaling--) | Mendapatkan atau mengatur skala horizontal teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code HorizontalScaling} dari elemen struktur induk. |
| [getLineSpacing](#getLineSpacing--) | Mendapatkan atau mengatur spasi baris teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code LineSpacing} dari elemen struktur induk. |
| [getMarginInfo](#getMarginInfo--) | Mendapatkan atau mengatur margin untuk elemen struktur blok. |
| [getStrikeOut](#getStrikeOut--) | Mendapatkan atau mengatur garis coret pada teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code StrikeOut} dari elemen struktur induk. |
| [getSubscript](#getSubscript--) | Mendapatkan atau mengatur subskrip teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Subscript} dari elemen struktur induk. |
| [getSuperscript](#getSuperscript--) | Mendapatkan atau mengatur superskrip teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Superscript} dari elemen struktur induk. |
| [getUnderline](#getUnderline--) | Mendapatkan atau mengatur garis bawah pada teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Underline} dari elemen struktur induk. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan atau mengatur perataan vertikal paragraf |
| [getWordSpacing](#getWordSpacing--) | Mendapatkan atau mengatur spasi kata teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code WordSpacing} dari elemen struktur induk. |
| [isFirstParagraphInColumn](#isFirstParagraphInColumn--) | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false. |
| [isInLineParagraph](#isInLineParagraph--) | Mendapatkan atau mengatur apakah paragraf bersifat inline. Defaultnya false. |
| [isInNewPage](#isInNewPage--) | Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false. |
| [isKeptWithNext](#isKeptWithNext--) | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar belakang teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code BackgroundColor} dari elemen struktur induk. |
| [setCharacterSpacing](#setCharacterSpacing-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur spasi karakter teks. |
| [setFont](#setFont-com.aspose.pdf.Font-) | Mendapatkan atau mengatur font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Font} dari elemen struktur induk. |
| [setFontSize](#setFontSize-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur ukuran font teks. |
| [setFontStyle](#setFontStyle-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur gaya font teks. |
| [setForegroundColor](#setForegroundColor-com.aspose.pdf.Color-) | Mendapatkan atau mengatur warna latar depan teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code ForegroundColor} dari elemen struktur induk. |
| [setHorizontalScaling](#setHorizontalScaling-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur skala horizontal teks. |
| [setLineSpacing](#setLineSpacing-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur jarak baris teks. |
| [setMarginInfo](#setMarginInfo-com.aspose.pdf.MarginInfo-) | Mendapatkan atau mengatur margin untuk elemen struktur blok. |
| [setStrikeOut](#setStrikeOut-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur coret untuk teks. |
| [setSubscript](#setSubscript-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur subskrip teks. |
| [setSuperscript](#setSuperscript-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur superskrip teks. |
| [setUnderline](#setUnderline-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur garis bawah teks. |
| [setWordSpacing](#setWordSpacing-com.aspose.ms.System.Nullable-) | Mendapatkan atau mengatur jarak kata teks. |
| [update](#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-) | Perbarui elemen |

### StructureTextState {#StructureTextState--}
```
public StructureTextState()
```

Konstruktor default

### createTextState {#createTextState--}
```
public final TextState createTextState()
```

Buat Status Teks

**Returns:**
instansi TextState

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Mendapatkan atau mengatur warna latar belakang teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code BackgroundColor} dari elemen struktur induk.

**Returns:**
Instansi Color

### getCharacterSpacing {#getCharacterSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getCharacterSpacing()
```

Mendapatkan atau mengatur spasi karakter teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code CharacterSpacing} dari elemen struktur induk.

**Returns:**
Array float

### getFont {#getFont--}
```
public final Font getFont()
```

Mendapatkan atau mengatur font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Font} dari elemen struktur induk.

**Returns:**
Instansi Font

### getFontSize {#getFontSize--}
```
public final com.aspose.ms.System.Nullable< Float > getFontSize()
```

Mendapatkan atau mengatur ukuran font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code FontSize} dari elemen struktur induk.

**Returns:**
Array float

### getFontStyle {#getFontStyle--}
```
public final com.aspose.ms.System.Nullable< Integer > getFontStyle()
```

Mendapatkan atau mengatur gaya font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code FontStyle} dari elemen struktur induk.

**Returns:**
Array integer

### getForegroundColor {#getForegroundColor--}
```
public final Color getForegroundColor()
```

Mendapatkan atau mengatur warna latar depan teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code ForegroundColor} dari elemen struktur induk.

**Returns:**
Instansi Color

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public final com.aspose.ms.System.Nullable< HorizontalAlignment > getHorizontalAlignment()
```

Mendapatkan atau mengatur perataan horizontal paragraf

**Returns:**
Elemen HorizontalAlignment

### getHorizontalScaling {#getHorizontalScaling--}
```
public final com.aspose.ms.System.Nullable< Float > getHorizontalScaling()
```

Mendapatkan atau mengatur skala horizontal teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code HorizontalScaling} dari elemen struktur induk.

**Returns:**
Array float

### getLineSpacing {#getLineSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getLineSpacing()
```

Mendapatkan atau mengatur spasi baris teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code LineSpacing} dari elemen struktur induk.

**Returns:**
Array float

### getMarginInfo {#getMarginInfo--}
```
@Deprecated public final MarginInfo getMarginInfo()
```

Mendapatkan atau mengatur margin untuk elemen struktur blok.

**Returns:**
Instansi MarginInfo @deprecated Gunakan metode IAdjustPosition.AdjustPosition(PositionSettings positionSettings) untuk mengatur pengaturan posisi

### getStrikeOut {#getStrikeOut--}
```
public final com.aspose.ms.System.Nullable< Boolean > getStrikeOut()
```

Mendapatkan atau mengatur garis coret pada teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code StrikeOut} dari elemen struktur induk.

**Returns:**
Array boolean

### getSubscript {#getSubscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSubscript()
```

Mendapatkan atau mengatur subskrip teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Subscript} dari elemen struktur induk.

**Returns:**
Array boolean

### getSuperscript {#getSuperscript--}
```
public final com.aspose.ms.System.Nullable< Boolean > getSuperscript()
```

Mendapatkan atau mengatur superskrip teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Superscript} dari elemen struktur induk.

**Returns:**
Array boolean

### getUnderline {#getUnderline--}
```
public final com.aspose.ms.System.Nullable< Boolean > getUnderline()
```

Mendapatkan atau mengatur garis bawah pada teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Underline} dari elemen struktur induk.

**Returns:**
Array boolean

### getVerticalAlignment {#getVerticalAlignment--}
```
public final com.aspose.ms.System.Nullable< VerticalAlignment > getVerticalAlignment()
```

Mendapatkan atau mengatur perataan vertikal paragraf

**Returns:**
Elemen VerticalAlignment

### getWordSpacing {#getWordSpacing--}
```
public final com.aspose.ms.System.Nullable< Float > getWordSpacing()
```

Mendapatkan atau mengatur spasi kata teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code WordSpacing} dari elemen struktur induk.

**Returns:**
Array float

### isFirstParagraphInColumn {#isFirstParagraphInColumn--}
```
public final com.aspose.ms.System.Nullable< Boolean > isFirstParagraphInColumn()
```

Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf ini akan berada di kolom berikutnya. Defaultnya false.

**Returns:**
Nilai boolean

### isInLineParagraph {#isInLineParagraph--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInLineParagraph()
```

Mendapatkan atau mengatur apakah paragraf bersifat inline. Defaultnya false.

**Returns:**
Nilai boolean

### isInNewPage {#isInNewPage--}
```
public final com.aspose.ms.System.Nullable< Boolean > isInNewPage()
```

Mendapatkan atau mengatur nilai bool yang memaksa paragraf ini dihasilkan pada halaman baru. Defaultnya false.

**Returns:**
Nilai boolean

### isKeptWithNext {#isKeptWithNext--}
```
public final com.aspose.ms.System.Nullable< Boolean > isKeptWithNext()
```

Mendapatkan atau mengatur nilai bool yang menunjukkan apakah paragraf saat ini tetap berada di halaman yang sama bersama paragraf berikutnya. Defaultnya false.

**Returns:**
Nilai boolean

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar belakang teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code BackgroundColor} dari elemen struktur induk.

### setCharacterSpacing {#setCharacterSpacing-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur spasi karakter teks.

### setFont {#setFont-com.aspose.pdf.Font-}
Mendapatkan atau mengatur font teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code Font} dari elemen struktur induk.

### setFontSize {#setFontSize-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur ukuran font teks.

### setFontStyle {#setFontStyle-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur gaya font teks.

### setForegroundColor {#setForegroundColor-com.aspose.pdf.Color-}
Mendapatkan atau mengatur warna latar depan teks. Bisa bernilai null. Gunakan null untuk mewarisi properti {@code ForegroundColor} dari elemen struktur induk.

### setHorizontalScaling {#setHorizontalScaling-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur skala horizontal teks.

### setLineSpacing {#setLineSpacing-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur jarak baris teks.

### setMarginInfo {#setMarginInfo-com.aspose.pdf.MarginInfo-}
Mendapatkan atau mengatur margin untuk elemen struktur blok.

### setStrikeOut {#setStrikeOut-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur coret untuk teks.

### setSubscript {#setSubscript-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur subskrip teks.

### setSuperscript {#setSuperscript-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur superskrip teks.

### setUnderline {#setUnderline-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur garis bawah teks.

### setWordSpacing {#setWordSpacing-com.aspose.ms.System.Nullable-}
Mendapatkan atau mengatur jarak kata teks.

### update {#update-com.aspose.pdf.tagged.logicalstructure.elements.StructureTextState-}
Perbarui elemen
