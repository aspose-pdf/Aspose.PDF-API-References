---
title: "ITaggedContent"
linktitle: "ITaggedContent"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili antarmuka untuk bekerja dengan konten TaggedPdf dokumen."
type: docs
weight: 30
url: /id/java/com.aspose.pdf.tagged/itaggedcontent/
---
```
public interface ITaggedContent
```

Mewakili antarmuka untuk bekerja dengan konten TaggedPdf dokumen.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [createAnnotElement](#createAnnotElement--) | Membuat {@link AnnotElement}. |
| [createArtElement](#createArtElement--) | Membuat {@link ArtElement}. |
| [createBibEntryElement](#createBibEntryElement--) | Membuat {@link BibEntryElement}. |
| [createBlockQuoteElement](#createBlockQuoteElement--) | Membuat {@link BlockQuoteElement}. |
| [createCaptionElement](#createCaptionElement--) | Membuat {@link CaptionElement}. |
| [createCodeElement](#createCodeElement--) | Membuat {@link CodeElement}. |
| [createDivElement](#createDivElement--) | Membuat {@link DivElement}. |
| [createFigureElement](#createFigureElement--) | Membuat {@link FigureElement}. |
| [createFormElement](#createFormElement--) | Membuat {@link FormElement}. |
| [createFormulaElement](#createFormulaElement--) | Membuat {@link FormulaElement}. |
| [createHeaderElement](#createHeaderElement--) | Membuat {@link HeaderElement}. |
| [createHeaderElement](#createHeaderElement-int-) | Membuat {@link HeaderElement} dengan level. |
| [createIndexElement](#createIndexElement--) | Membuat {@link IndexElement}. |
| [createLinkElement](#createLinkElement--) | Membuat {@link LinkElement}. |
| [createListElement](#createListElement--) | Membuat {@link ListElement}. |
| [createListLblElement](#createListLblElement--) | Membuat {@link ListLblElement}. |
| [createListLBodyElement](#createListLBodyElement--) | Membuat {@link ListLBodyElement}. |
| [createListLIElement](#createListLIElement--) | Membuat {@link ListLIElement}. |
| [createNonStructElement](#createNonStructElement--) | Membuat {@link NonStructElement}. |
| [createNoteElement](#createNoteElement--) | Membuat {@link NoteElement}. |
| [createParagraphElement](#createParagraphElement--) | Membuat {@link ParagraphElement}. |
| [createPartElement](#createPartElement--) | Membuat {@link PartElement}. |
| [createPrivateElement](#createPrivateElement--) | Membuat {@link PrivateElement}. |
| [createQuoteElement](#createQuoteElement--) | Membuat {@link QuoteElement}. |
| [createReferenceElement](#createReferenceElement--) | Membuat {@link ReferenceElement}. |
| [createRubyElement](#createRubyElement--) | Membuat {@link RubyElement}. |
| [createSectElement](#createSectElement--) | Membuat {@link SectElement}. |
| [createSpanElement](#createSpanElement--) | Membuat {@link SpanElement}. |
| [createTableElement](#createTableElement--) | Membuat {@link TableElement}. |
| [createTableTBodyElement](#createTableTBodyElement--) | Membuat {@link TableTHeadElement}. |
| [createTableTDElement](#createTableTDElement--) | Membuat {@link TableTDElement}. |
| [createTableTFootElement](#createTableTFootElement--) | Membuat {@link TableTFootElement}. |
| [createTableTHeadElement](#createTableTHeadElement--) | Membuat {@link TableTHeadElement}. |
| [createTableTHElement](#createTableTHElement--) | Membuat {@link TableTHElement}. |
| [createTableTRElement](#createTableTRElement--) | Membuat {@link TableTRElement}. |
| [createTOCElement](#createTOCElement--) | Membuat {@link TOCElement}. |
| [createTOCIElement](#createTOCIElement--) | Membuat {@link TOCIElement}. |
| [createWarichuElement](#createWarichuElement--) | Membuat {@link WarichuElement}. |
| [getRootElement](#getRootElement--) | Mendapatkan root {@link StructureElement} dari struktur logis dokumen PDF. |
| [getStructTreeRootElement](#getStructTreeRootElement--) | Mendapatkan {@link StructTreeRootElement} dokumen PDF. |
| [getStructureTextState](#getStructureTextState--) | Dapatkan pengaturan {@link StructureTextState} untuk seluruh dokumen. |
| [preSave](#preSave--) | Menyiapkan konten ber-tag dokumen untuk disimpan. Metode ini melakukan operasi pra-simpan yang diperlukan, memastikan bahwa pohon struktur dan elemen konten ber-tag lainnya dikonfigurasi dengan benar sebelum dokumen disimpan. |
| [save](#save--) | Menyimpan keadaan saat ini dari konten ber-tag ke dokumen PDF yang terkait. Metode ini memastikan bahwa semua elemen konten ber-tag diperbarui dan disimpan dengan benar dalam dokumen PDF. Ini melakukan operasi yang diperlukan seperti memperbarui MCID untuk elemen MCR, mengatur operator BDC, dan memastikan kepatuhan terhadap standar PDF/UA. |
| [setLanguage](#setLanguage-java.lang.String-) | / * Mendapatkan bahasa alami untuk dokumen pdf. / * Sebuah pengidentifikasi bahasa yang harus menentukan bahasa alami untuk semua teks dalam dokumen kecuali bila / * ditimpa oleh spesifikasi bahasa untuk elemen struktur atau konten yang ditandai. / * / * |
| [setTitle](#setTitle-java.lang.String-) | Mengatur judul untuk dokumen PDF. |

### createAnnotElement {#createAnnotElement--}
```
AnnotElement createAnnotElement()
```

Membuat {@link AnnotElement}.

**Returns:**
Elemen struktur dibuat.

### createArtElement {#createArtElement--}
```
ArtElement createArtElement()
```

Membuat {@link ArtElement}.

**Returns:**
Elemen struktur dibuat.

### createBibEntryElement {#createBibEntryElement--}
```
BibEntryElement createBibEntryElement()
```

Membuat {@link BibEntryElement}.

**Returns:**
Elemen struktur dibuat.

### createBlockQuoteElement {#createBlockQuoteElement--}
```
BlockQuoteElement createBlockQuoteElement()
```

Membuat {@link BlockQuoteElement}.

**Returns:**
Elemen struktur dibuat.

### createCaptionElement {#createCaptionElement--}
```
CaptionElement createCaptionElement()
```

Membuat {@link CaptionElement}.

**Returns:**
Elemen struktur dibuat.

### createCodeElement {#createCodeElement--}
```
CodeElement createCodeElement()
```

Membuat {@link CodeElement}.

**Returns:**
Elemen struktur dibuat.

### createDivElement {#createDivElement--}
```
DivElement createDivElement()
```

Membuat {@link DivElement}.

**Returns:**
Elemen struktur dibuat.

### createFigureElement {#createFigureElement--}
```
FigureElement createFigureElement()
```

Membuat {@link FigureElement}.

**Returns:**
Elemen struktur dibuat.

### createFormElement {#createFormElement--}
```
FormElement createFormElement()
```

Membuat {@link FormElement}.

**Returns:**
Elemen struktur dibuat.

### createFormulaElement {#createFormulaElement--}
```
FormulaElement createFormulaElement()
```

Membuat {@link FormulaElement}.

**Returns:**
Elemen struktur dibuat.

### createHeaderElement {#createHeaderElement--}
```
HeaderElement createHeaderElement()
```

Membuat {@link HeaderElement}.

**Returns:**
Elemen struktur dibuat.

### createHeaderElement {#createHeaderElement-int-}
```
HeaderElement createHeaderElement(int level)
```

Membuat {@link HeaderElement} dengan level.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| level |  | Tingkat Header. Harus 1, 2, 3, 4, 5, atau 6. |

**Returns:**
Elemen struktur dibuat.

### createIndexElement {#createIndexElement--}
```
IndexElement createIndexElement()
```

Membuat {@link IndexElement}.

**Returns:**
Elemen struktur dibuat.

### createLinkElement {#createLinkElement--}
```
LinkElement createLinkElement()
```

Membuat {@link LinkElement}.

**Returns:**
Elemen struktur dibuat.

### createListElement {#createListElement--}
```
ListElement createListElement()
```

Membuat {@link ListElement}.

**Returns:**
Elemen struktur dibuat.

### createListLblElement {#createListLblElement--}
```
ListLblElement createListLblElement()
```

Membuat {@link ListLblElement}.

**Returns:**
Elemen struktur dibuat.

### createListLBodyElement {#createListLBodyElement--}
```
ListLBodyElement createListLBodyElement()
```

Membuat {@link ListLBodyElement}.

**Returns:**
Elemen struktur dibuat.

### createListLIElement {#createListLIElement--}
```
ListLIElement createListLIElement()
```

Membuat {@link ListLIElement}.

**Returns:**
Elemen struktur dibuat.

### createNonStructElement {#createNonStructElement--}
```
NonStructElement createNonStructElement()
```

Membuat {@link NonStructElement}.

**Returns:**
Elemen struktur dibuat.

### createNoteElement {#createNoteElement--}
```
NoteElement createNoteElement()
```

Membuat {@link NoteElement}.

**Returns:**
Elemen struktur dibuat.

### createParagraphElement {#createParagraphElement--}
```
ParagraphElement createParagraphElement()
```

Membuat {@link ParagraphElement}.

**Returns:**
Elemen struktur dibuat.

### createPartElement {#createPartElement--}
```
PartElement createPartElement()
```

Membuat {@link PartElement}.

**Returns:**
Elemen struktur dibuat.

### createPrivateElement {#createPrivateElement--}
```
PrivateElement createPrivateElement()
```

Membuat {@link PrivateElement}.

**Returns:**
Elemen struktur dibuat.

### createQuoteElement {#createQuoteElement--}
```
QuoteElement createQuoteElement()
```

Membuat {@link QuoteElement}.

**Returns:**
Elemen struktur dibuat.

### createReferenceElement {#createReferenceElement--}
```
ReferenceElement createReferenceElement()
```

Membuat {@link ReferenceElement}.

**Returns:**
Elemen struktur dibuat.

### createRubyElement {#createRubyElement--}
```
RubyElement createRubyElement()
```

Membuat {@link RubyElement}.

**Returns:**
Elemen struktur dibuat.

### createSectElement {#createSectElement--}
```
SectElement createSectElement()
```

Membuat {@link SectElement}.

**Returns:**
Elemen struktur dibuat.

### createSpanElement {#createSpanElement--}
```
SpanElement createSpanElement()
```

Membuat {@link SpanElement}.

**Returns:**
Elemen struktur dibuat.

### createTableElement {#createTableElement--}
```
TableElement createTableElement()
```

Membuat {@link TableElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTBodyElement {#createTableTBodyElement--}
```
TableTBodyElement createTableTBodyElement()
```

Membuat {@link TableTHeadElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTDElement {#createTableTDElement--}
```
TableTDElement createTableTDElement()
```

Membuat {@link TableTDElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTFootElement {#createTableTFootElement--}
```
TableTFootElement createTableTFootElement()
```

Membuat {@link TableTFootElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTHeadElement {#createTableTHeadElement--}
```
TableTHeadElement createTableTHeadElement()
```

Membuat {@link TableTHeadElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTHElement {#createTableTHElement--}
```
TableTHElement createTableTHElement()
```

Membuat {@link TableTHElement}.

**Returns:**
Elemen struktur dibuat.

### createTableTRElement {#createTableTRElement--}
```
TableTRElement createTableTRElement()
```

Membuat {@link TableTRElement}.

**Returns:**
Elemen struktur dibuat.

### createTOCElement {#createTOCElement--}
```
TOCElement createTOCElement()
```

Membuat {@link TOCElement}.

**Returns:**
Elemen struktur dibuat.

### createTOCIElement {#createTOCIElement--}
```
TOCIElement createTOCIElement()
```

Membuat {@link TOCIElement}.

**Returns:**
Elemen struktur dibuat.

### createWarichuElement {#createWarichuElement--}
```
WarichuElement createWarichuElement()
```

Membuat {@link WarichuElement}.

**Returns:**
Elemen struktur dibuat.

### getRootElement {#getRootElement--}
```
StructureElement getRootElement()
```

Mendapatkan root {@link StructureElement} dari struktur logis dokumen PDF.

**Returns:**
Root {@link StructureElement} dari struktur logis dokumen PDF.

### getStructTreeRootElement {#getStructTreeRootElement--}
```
StructTreeRootElement getStructTreeRootElement()
```

Mendapatkan {@link StructTreeRootElement} dokumen PDF.

**Returns:**
StructTreeRootElement dokumen PDF.

### getStructureTextState {#getStructureTextState--}
```
StructureTextState getStructureTextState()
```

Dapatkan pengaturan {@link StructureTextState} untuk seluruh dokumen.

**Returns:**
Nilai: pengaturan {@link StructureTextState} untuk seluruh dokumen.

### preSave {#preSave--}
```
void preSave()
```

Menyiapkan konten ber-tag dokumen untuk disimpan. Metode ini melakukan operasi pra-simpan yang diperlukan, memastikan bahwa pohon struktur dan elemen konten ber-tag lainnya dikonfigurasi dengan benar sebelum dokumen disimpan.

### save {#save--}
```
void save()
```

Menyimpan keadaan saat ini dari konten ber-tag ke dokumen PDF yang terkait. Metode ini memastikan bahwa semua elemen konten ber-tag diperbarui dan disimpan dengan benar dalam dokumen PDF. Ini melakukan operasi yang diperlukan seperti memperbarui MCID untuk elemen MCR, mengatur operator BDC, dan memastikan kepatuhan terhadap standar PDF/UA.

### setLanguage {#setLanguage-java.lang.String-}
/ * Mendapatkan bahasa alami untuk dokumen pdf. / * Sebuah pengidentifikasi bahasa yang harus menentukan bahasa alami untuk semua teks dalam dokumen kecuali bila / * ditimpa oleh spesifikasi bahasa untuk elemen struktur atau konten yang ditandai. / * / *

### setTitle {#setTitle-java.lang.String-}
Mengatur judul untuk dokumen PDF.
