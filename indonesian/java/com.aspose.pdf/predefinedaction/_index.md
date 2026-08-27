---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mendefinisikan berbagai aksi yang dapat dipicu dari file PDF."
type: docs
weight: 3960
url: /id/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Mendefinisikan berbagai aksi yang dapat dipicu dari file PDF.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Aksi bernama untuk menemukan bookmark saat ini. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Aksi bernama untuk menyorot bookmark saat ini. |
| [Document_AttachFile](#Document_AttachFile) | Aksi bernama untuk menambahkan lampiran file. |
| [Document_CropPages](#Document_CropPages) | Aksi bernama untuk memotong halaman dokumen. |
| [Document_DeletePages](#Document_DeletePages) | Aksi bernama untuk menghapus halaman dokumen. |
| [Document_ExtractPages](#Document_ExtractPages) | Aksi bernama untuk mengekstrak halaman dokumen. |
| [Document_InsertPages](#Document_InsertPages) | Aksi bernama untuk menyisipkan halaman dari sebuah dokumen. |
| [Document_ReplacePages](#Document_ReplacePages) | Aksi bernama untuk mengganti halaman dokumen. |
| [Document_RotatePages](#Document_RotatePages) | Aksi bernama untuk memutar halaman dokumen. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Aksi bernama untuk memeriksa ejaan dalam komentar. |
| [Edit_Find](#Edit_Find) | Aksi bernama untuk mencari. |
| [Edit_Preferences](#Edit_Preferences) | Aksi bernama untuk mengedit preferensi. |
| [Edit_Search](#Edit_Search) | Aksi bernama untuk pencarian. |
| [File_AttachToEmail](#File_AttachToEmail) | Aksi bernama untuk melampirkan dokumen pdf saat ini ke pesan email. |
| [File_Close](#File_Close) | Aksi bernama untuk menutup dokumen. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Aksi bernama untuk membuat dokumen pdf dari pemindai. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Aksi bernama untuk membuat dokumen pdf dari halaman web. |
| [File_Exit](#File_Exit) | Aksi bernama untuk keluar dari pembaca pdf. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Sebuah aksi bernama untuk membuka organizer. |
| [File_Print](#File_Print) | Sebuah aksi bernama untuk mencetak dokumen. |
| [File_Properties](#File_Properties) | Sebuah aksi bernama untuk membuka properti dokumen. |
| [File_SaveAs](#File_SaveAs) | Sebuah aksi bernama untuk menyimpan dokumen dengan nama lain. |
| [FirstPage](#FirstPage) | Sebuah aksi bernama untuk pergi ke halaman pertama. |
| [LastPage](#LastPage) | Sebuah aksi bernama untuk pergi ke halaman terakhir. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Sebuah aksi bernama untuk memperbesar dokumen. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Sebuah aksi bernama untuk memperkecil dokumen. |
| [NextPage](#NextPage) | Sebuah aksi bernama untuk pergi ke halaman berikutnya. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Sebuah aksi bernama untuk mencetak halaman dokumen. |
| [PrevPage](#PrevPage) | Sebuah aksi bernama untuk pergi ke halaman sebelumnya. |
| [Print](#Print) | Sebuah aksi bernama untuk membuka dialog cetak. |
| [PrintDialog](#PrintDialog) | Sebuah aksi bernama untuk membuka dialog cetak (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Sebuah aksi bernama untuk pergi ke tampilan berikutnya. |
| [View_GoTo_Page](#View_GoTo_Page) | Sebuah aksi bernama untuk pergi ke halaman tertentu. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Sebuah aksi bernama untuk pergi ke dokumen sebelumnya. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Sebuah aksi bernama untuk pergi ke tampilan sebelumnya. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel artikel. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel lampiran. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel bookmark. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel komentar. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel bidang. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel lapisan. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel pohon model. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel halaman. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | Sebuah aksi bernama untuk menampilkan/menyembunyikan panel tanda tangan. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Sebuah aksi bernama untuk menampilkan satu halaman. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Sebuah aksi bernama untuk menampilkan satu halaman berkelanjutan. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Sebuah aksi bernama untuk menampilkan halaman sebagai Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Sebuah aksi bernama untuk menampilkan halaman sebagai Two-Up berkelanjutan. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat penyuntingan lanjutan. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat komentar. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat edit. |
| [View_Toolbars_File](#View_Toolbars_File) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat file. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pencarian. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat formulir. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pengukuran. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat data objek. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat tampilan halaman. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat navigasi. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat produksi cetak. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat properti. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat redaksi. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pilih & perbesar. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat tugas. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat mesin tik. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Sebuah aksi bernama untuk melihat halaman dalam ukuran sebenarnya. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Sebuah aksi bernama untuk menyesuaikan halaman pada tinggi. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Sebuah aksi bernama untuk menyesuaikan halaman. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Sebuah aksi bernama untuk menyesuaikan visibilitas halaman. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Aksi bernama untuk menyesuaikan halaman dengan lebar. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Aksi bernama untuk memperbesar tampilan. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Aksi bernama untuk melihat dokumen dalam mode layar penuh. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan. |
| [values](#values--) | Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Aksi bernama untuk menemukan bookmark saat ini.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Aksi bernama untuk menyorot bookmark saat ini.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Aksi bernama untuk menambahkan lampiran file.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Aksi bernama untuk memotong halaman dokumen.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Aksi bernama untuk menghapus halaman dokumen.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Aksi bernama untuk mengekstrak halaman dokumen.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Aksi bernama untuk menyisipkan halaman dari sebuah dokumen.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Aksi bernama untuk mengganti halaman dokumen.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Aksi bernama untuk memutar halaman dokumen.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Aksi bernama untuk memeriksa ejaan dalam komentar.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Aksi bernama untuk mencari.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Aksi bernama untuk mengedit preferensi.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Aksi bernama untuk pencarian.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Aksi bernama untuk melampirkan dokumen pdf saat ini ke pesan email.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Aksi bernama untuk menutup dokumen.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Aksi bernama untuk membuat dokumen pdf dari pemindai.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Aksi bernama untuk membuat dokumen pdf dari halaman web.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Aksi bernama untuk keluar dari pembaca pdf.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Sebuah aksi bernama untuk membuka organizer.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Sebuah aksi bernama untuk mencetak dokumen.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Sebuah aksi bernama untuk membuka properti dokumen.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Sebuah aksi bernama untuk menyimpan dokumen dengan nama lain.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

Sebuah aksi bernama untuk pergi ke halaman pertama.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Sebuah aksi bernama untuk pergi ke halaman terakhir.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Sebuah aksi bernama untuk memperbesar dokumen.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Sebuah aksi bernama untuk memperkecil dokumen.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Sebuah aksi bernama untuk pergi ke halaman berikutnya.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Sebuah aksi bernama untuk mencetak halaman dokumen.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Sebuah aksi bernama untuk pergi ke halaman sebelumnya.

### Print {#Print}
```
public static final PredefinedAction Print
```

Sebuah aksi bernama untuk membuka dialog cetak.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Sebuah aksi bernama untuk membuka dialog cetak (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Sebuah aksi bernama untuk pergi ke tampilan berikutnya.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Sebuah aksi bernama untuk pergi ke halaman tertentu.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Sebuah aksi bernama untuk pergi ke dokumen sebelumnya.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Sebuah aksi bernama untuk pergi ke tampilan sebelumnya.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel artikel.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel lampiran.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel bookmark.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel komentar.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel bidang.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel lapisan.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel pohon model.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel halaman.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan panel tanda tangan.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Sebuah aksi bernama untuk menampilkan satu halaman.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Sebuah aksi bernama untuk menampilkan satu halaman berkelanjutan.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Sebuah aksi bernama untuk menampilkan halaman sebagai Two-Up.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Sebuah aksi bernama untuk menampilkan halaman sebagai Two-Up berkelanjutan.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat penyuntingan lanjutan.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat komentar.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat edit.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat file.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pencarian.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat formulir.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pengukuran.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat data objek.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat tampilan halaman.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat navigasi.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat produksi cetak.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat properti.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat redaksi.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat pilih & perbesar.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat tugas.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Sebuah aksi bernama untuk menampilkan/menyembunyikan bilah alat mesin tik.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Sebuah aksi bernama untuk melihat halaman dalam ukuran sebenarnya.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Sebuah aksi bernama untuk menyesuaikan halaman pada tinggi.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Sebuah aksi bernama untuk menyesuaikan halaman.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Sebuah aksi bernama untuk menyesuaikan visibilitas halaman.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Aksi bernama untuk menyesuaikan halaman dengan lebar.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Aksi bernama untuk memperbesar tampilan.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Aksi bernama untuk melihat dokumen dalam mode layar penuh.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Mengembalikan konstanta enum dari tipe ini dengan nama yang ditentukan.

### values {#values--}
```
public static PredefinedAction [] values()
```

Mengembalikan array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan.

**Returns:**
array yang berisi konstanta dari tipe enum ini, dalam urutan mereka dideklarasikan
