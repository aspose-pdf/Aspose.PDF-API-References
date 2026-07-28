---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir PDF dosyasından tetiklenebilecek farklı eylemleri tanımlar."
type: docs
weight: 3960
url: /tr/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Bir PDF dosyasından tetiklenebilecek farklı eylemleri tanımlar.

## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Geçerli yer imini bulmak için adlandırılmış bir eylem. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Geçerli yer imini vurgulamak için adlandırılmış bir eylem. |
| [Document_AttachFile](#Document_AttachFile) | Dosya eki eklemek için adlandırılmış bir eylem. |
| [Document_CropPages](#Document_CropPages) | Belge sayfalarını kırpmak için adlandırılmış bir eylem. |
| [Document_DeletePages](#Document_DeletePages) | Belge sayfalarını silmek için adlandırılmış bir eylem. |
| [Document_ExtractPages](#Document_ExtractPages) | Belge sayfalarını çıkarmak için adlandırılmış bir eylem. |
| [Document_InsertPages](#Document_InsertPages) | Bir belgeden sayfalar eklemek için adlandırılmış bir eylem. |
| [Document_ReplacePages](#Document_ReplacePages) | Belge sayfalarını değiştirmek için adlandırılmış bir eylem. |
| [Document_RotatePages](#Document_RotatePages) | Belge sayfalarını döndürmek için adlandırılmış bir eylem. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Yorumlarda yazım denetimi yapmak için adlandırılmış bir eylem. |
| [Edit_Find](#Edit_Find) | Bulmak için adlandırılmış bir eylem. |
| [Edit_Preferences](#Edit_Preferences) | Tercihleri düzenlemek için adlandırılmış bir eylem. |
| [Edit_Search](#Edit_Search) | Arama yapmak için adlandırılmış bir eylem. |
| [File_AttachToEmail](#File_AttachToEmail) | Geçerli pdf belgesini e-posta mesajına eklemek için adlandırılmış bir eylem. |
| [File_Close](#File_Close) | Belgeyi kapatmak için adlandırılmış bir eylem. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Tarayıcıdan pdf belge oluşturmak için adlandırılmış bir eylem. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Web sayfasından pdf belge oluşturmak için adlandırılmış bir eylem. |
| [File_Exit](#File_Exit) | Pdf okuyucudan çıkmak için adlandırılmış bir eylem. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Organizatörü açmak için adlandırılmış bir eylem. |
| [File_Print](#File_Print) | Belgeyi yazdırmak için adlandırılmış bir eylem. |
| [File_Properties](#File_Properties) | Belge özelliklerini açmak için adlandırılmış bir eylem. |
| [File_SaveAs](#File_SaveAs) | Belgeyi başka bir adla kaydetmek için adlandırılmış bir eylem. |
| [FirstPage](#FirstPage) | İlk sayfaya gitmek için adlandırılmış bir eylem. |
| [LastPage](#LastPage) | Son sayfaya gitmek için adlandırılmış bir eylem. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Belgeyi yakınlaştırmak için adlandırılmış bir eylem. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Belgeyi uzaklaştırmak için adlandırılmış bir eylem. |
| [NextPage](#NextPage) | Sonraki sayfaya gitmek için adlandırılmış bir eylem. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Belge sayfalarını yazdırmak için adlandırılmış bir eylem. |
| [PrevPage](#PrevPage) | Önceki sayfaya gitmek için adlandırılmış bir eylem. |
| [Print](#Print) | Yazdırma iletişim kutusunu açmak için adlandırılmış bir eylem. |
| [PrintDialog](#PrintDialog) | Yazdırma iletişim kutusunu açmak için adlandırılmış bir eylem (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Sonraki görünüme gitmek için adlandırılmış bir eylem. |
| [View_GoTo_Page](#View_GoTo_Page) | Belirli bir sayfaya gitmek için adlandırılmış bir eylem. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Önceki belgeye gitmek için adlandırılmış bir eylem. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Önceki görünüme gitmek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Makaleler panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Ekler panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Yer imleri panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Yorumlar panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Alanlar panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Katmanlar panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Model ağacı panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Sayfalar panelini göster/gizlemek için adlandırılmış bir eylem. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | İmzalar panelini göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Tek sayfayı görüntülemek için bir isimlendirilmiş eylem. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Tek sürekli sayfayı görüntülemek için bir isimlendirilmiş eylem. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Sayfaları Two-Up olarak görüntülemek için bir isimlendirilmiş eylem. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Sayfaları Two-Up sürekli olarak görüntülemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Gelişmiş düzenleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Yorumlama araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Düzenleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_File](#View_Toolbars_File) | Dosya araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Bulma araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Formlar araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Ölçüm araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Nesne verileri araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Sayfa görüntüleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Gezinti araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Yazdırma üretim araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Özellik araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Kırpma araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Seç ve yakınlaştır araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Görevler araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Yazı makinesi araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Sayfaları gerçek boyutunda görüntülemek için bir isimlendirilmiş eylem. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Sayfayı yüksekliğe sığdırmak için bir isimlendirilmiş eylem. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Sayfayı sığdırmak için bir isimlendirilmiş eylem. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Sayfa görünürlüğünü sığdırmak için bir isimlendirilmiş eylem. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Genişliğe göre sayfayı sığdıran adlandırılmış bir eylem. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Yakınlaştırma yapan adlandırılmış bir eylem. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Belgeyi tam ekran modunda görüntüleyen adlandırılmış bir eylem. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Bu tipin belirtilen adla enum sabitini döndürür. |
| [values](#values--) | Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Geçerli yer imini bulmak için adlandırılmış bir eylem.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Geçerli yer imini vurgulamak için adlandırılmış bir eylem.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Dosya eki eklemek için adlandırılmış bir eylem.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Belge sayfalarını kırpmak için adlandırılmış bir eylem.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Belge sayfalarını silmek için adlandırılmış bir eylem.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Belge sayfalarını çıkarmak için adlandırılmış bir eylem.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Bir belgeden sayfalar eklemek için adlandırılmış bir eylem.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Belge sayfalarını değiştirmek için adlandırılmış bir eylem.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Belge sayfalarını döndürmek için adlandırılmış bir eylem.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Yorumlarda yazım denetimi yapmak için adlandırılmış bir eylem.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Bulmak için adlandırılmış bir eylem.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Tercihleri düzenlemek için adlandırılmış bir eylem.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Arama yapmak için adlandırılmış bir eylem.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Geçerli pdf belgesini e-posta mesajına eklemek için adlandırılmış bir eylem.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Belgeyi kapatmak için adlandırılmış bir eylem.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Tarayıcıdan pdf belge oluşturmak için adlandırılmış bir eylem.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Web sayfasından pdf belge oluşturmak için adlandırılmış bir eylem.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Pdf okuyucudan çıkmak için adlandırılmış bir eylem.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Organizatörü açmak için adlandırılmış bir eylem.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Belgeyi yazdırmak için adlandırılmış bir eylem.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Belge özelliklerini açmak için adlandırılmış bir eylem.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Belgeyi başka bir adla kaydetmek için adlandırılmış bir eylem.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

İlk sayfaya gitmek için adlandırılmış bir eylem.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Son sayfaya gitmek için adlandırılmış bir eylem.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Belgeyi yakınlaştırmak için adlandırılmış bir eylem.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Belgeyi uzaklaştırmak için adlandırılmış bir eylem.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Sonraki sayfaya gitmek için adlandırılmış bir eylem.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Belge sayfalarını yazdırmak için adlandırılmış bir eylem.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Önceki sayfaya gitmek için adlandırılmış bir eylem.

### Print {#Print}
```
public static final PredefinedAction Print
```

Yazdırma iletişim kutusunu açmak için adlandırılmış bir eylem.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Yazdırma iletişim kutusunu açmak için adlandırılmış bir eylem (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Sonraki görünüme gitmek için adlandırılmış bir eylem.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Belirli bir sayfaya gitmek için adlandırılmış bir eylem.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Önceki belgeye gitmek için adlandırılmış bir eylem.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Önceki görünüme gitmek için adlandırılmış bir eylem.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Makaleler panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Ekler panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Yer imleri panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Yorumlar panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Alanlar panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Katmanlar panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Model ağacı panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Sayfalar panelini göster/gizlemek için adlandırılmış bir eylem.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

İmzalar panelini göster/gizlemek için bir isimlendirilmiş eylem.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Tek sayfayı görüntülemek için bir isimlendirilmiş eylem.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Tek sürekli sayfayı görüntülemek için bir isimlendirilmiş eylem.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Sayfaları Two-Up olarak görüntülemek için bir isimlendirilmiş eylem.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Sayfaları Two-Up sürekli olarak görüntülemek için bir isimlendirilmiş eylem.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Gelişmiş düzenleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Yorumlama araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Düzenleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Dosya araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Bulma araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Formlar araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Ölçüm araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Nesne verileri araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Sayfa görüntüleme araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Gezinti araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Yazdırma üretim araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Özellik araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Kırpma araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Seç ve yakınlaştır araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Görevler araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Yazı makinesi araç çubuğunu göster/gizlemek için bir isimlendirilmiş eylem.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Sayfaları gerçek boyutunda görüntülemek için bir isimlendirilmiş eylem.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Sayfayı yüksekliğe sığdırmak için bir isimlendirilmiş eylem.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Sayfayı sığdırmak için bir isimlendirilmiş eylem.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Sayfa görünürlüğünü sığdırmak için bir isimlendirilmiş eylem.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Genişliğe göre sayfayı sığdıran adlandırılmış bir eylem.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Yakınlaştırma yapan adlandırılmış bir eylem.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Belgeyi tam ekran modunda görüntüleyen adlandırılmış bir eylem.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Bu tipin belirtilen adla enum sabitini döndürür.

### values {#values--}
```
public static PredefinedAction [] values()
```

Bu enum tipinin sabitlerini içeren bir dizi döndürür, tanımlandıkları sırada.

**Returns:**
Bu enum tipinin sabitlerini içeren bir dizi, tanımlandıkları sırada
