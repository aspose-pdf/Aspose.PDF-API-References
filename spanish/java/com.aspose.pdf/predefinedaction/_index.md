---
title: "PredefinedAction"
linktitle: "PredefinedAction"
second_title: "Referencia de la API de Aspose.PDF para Java"
description: "Define diferentes acciones que pueden activarse desde un archivo PDF."
type: docs
weight: 3960
url: /es/java/com.aspose.pdf/predefinedaction/
---
**Inheritance:**
java.lang.Object, java.lang.Enum < PredefinedAction > com.aspose.pdf.PredefinedAction, java.lang.Enum < PredefinedAction >, com.aspose.pdf.PredefinedAction

**All Implemented Interfaces:**
Serializable, Comparable < PredefinedAction >

```
public enum PredefinedAction extends Enum < PredefinedAction >
```

Define diferentes acciones que pueden activarse desde un archivo PDF.

## Campos

| Campo | Descripción |
| --- | --- |
| [Bookmarks_ExpanCurrentBookmark](#Bookmarks_ExpanCurrentBookmark) | Una acción con nombre para encontrar el marcador actual. |
| [Bookmarks_HightlightCurrentBookmark](#Bookmarks_HightlightCurrentBookmark) | Una acción con nombre para resaltar el marcador actual. |
| [Document_AttachFile](#Document_AttachFile) | Una acción con nombre para agregar un archivo adjunto. |
| [Document_CropPages](#Document_CropPages) | Una acción con nombre para recortar páginas del documento. |
| [Document_DeletePages](#Document_DeletePages) | Una acción con nombre para eliminar páginas del documento. |
| [Document_ExtractPages](#Document_ExtractPages) | Una acción con nombre para extraer páginas del documento. |
| [Document_InsertPages](#Document_InsertPages) | Una acción con nombre para insertar páginas desde un documento. |
| [Document_ReplacePages](#Document_ReplacePages) | Una acción con nombre para reemplazar páginas del documento. |
| [Document_RotatePages](#Document_RotatePages) | Una acción con nombre para rotar páginas del documento. |
| [Edit_CheckSpelling_InComFieldEdit](#Edit_CheckSpelling_InComFieldEdit) | Una acción con nombre para comprobar la ortografía en los comentarios. |
| [Edit_Find](#Edit_Find) | Una acción con nombre para buscar. |
| [Edit_Preferences](#Edit_Preferences) | Una acción con nombre para editar preferencias. |
| [Edit_Search](#Edit_Search) | Una acción con nombre para buscar. |
| [File_AttachToEmail](#File_AttachToEmail) | Una acción con nombre para adjuntar el documento pdf actual en un mensaje de correo electrónico. |
| [File_Close](#File_Close) | Una acción con nombre para cerrar el documento. |
| [File_CreatePDF_FromScanner](#File_CreatePDF_FromScanner) | Una acción con nombre para crear un documento pdf a partir de un escáner. |
| [File_CreatePDF_FromWebPage](#File_CreatePDF_FromWebPage) | Una acción con nombre para crear un documento pdf a partir de una página web. |
| [File_Exit](#File_Exit) | Una acción con nombre para salir del lector pdf. |
| [File_Organizer_OpenOrganizer](#File_Organizer_OpenOrganizer) | Una acción nombrada para abrir el organizador. |
| [File_Print](#File_Print) | Una acción nombrada para imprimir el documento. |
| [File_Properties](#File_Properties) | Una acción nombrada para abrir las propiedades del documento. |
| [File_SaveAs](#File_SaveAs) | Una acción nombrada para guardar el documento con otro nombre. |
| [FirstPage](#FirstPage) | Una acción nombrada para ir a la primera página. |
| [LastPage](#LastPage) | Una acción nombrada para ir a la última página. |
| [Miscellaneous_ZoomIn](#Miscellaneous_ZoomIn) | Una acción nombrada para acercar el documento. |
| [Miscellaneous_ZoomOut](#Miscellaneous_ZoomOut) | Una acción nombrada para alejar el documento. |
| [NextPage](#NextPage) | Una acción nombrada para ir a la página siguiente. |
| [PageImages_PrintPages](#PageImages_PrintPages) | Una acción nombrada para imprimir las páginas del documento. |
| [PrevPage](#PrevPage) | Una acción nombrada para ir a la página anterior. |
| [Print](#Print) | Una acción nombrada para abrir un cuadro de diálogo de impresión. |
| [PrintDialog](#PrintDialog) | Una acción nombrada para abrir un cuadro de diálogo de impresión (JavaScript). |
| [View_GoTo_NextView](#View_GoTo_NextView) | Una acción nombrada para ir a la vista siguiente. |
| [View_GoTo_Page](#View_GoTo_Page) | Una acción nombrada para ir a la página determinada. |
| [View_GoTo_PreDocument](#View_GoTo_PreDocument) | Una acción nombrada para ir al documento anterior. |
| [View_GoTo_PreView](#View_GoTo_PreView) | Una acción nombrada para ir a la vista anterior. |
| [View_NavigationPanels_Articles](#View_NavigationPanels_Articles) | Una acción nombrada para mostrar/ocultar el panel de artículos. |
| [View_NavigationPanels_Attachments](#View_NavigationPanels_Attachments) | Una acción nombrada para mostrar/ocultar el panel de adjuntos. |
| [View_NavigationPanels_Boomarks](#View_NavigationPanels_Boomarks) | Una acción nombrada para mostrar/ocultar el panel de marcadores. |
| [View_NavigationPanels_Comments](#View_NavigationPanels_Comments) | Una acción nombrada para mostrar/ocultar el panel de comentarios. |
| [View_NavigationPanels_Fields](#View_NavigationPanels_Fields) | Una acción nombrada para mostrar/ocultar el panel de campos. |
| [View_NavigationPanels_Layers](#View_NavigationPanels_Layers) | Una acción nombrada para mostrar/ocultar el panel de capas. |
| [View_NavigationPanels_ModelTree](#View_NavigationPanels_ModelTree) | Una acción nombrada para mostrar/ocultar el panel de árbol de modelo. |
| [View_NavigationPanels_Pages](#View_NavigationPanels_Pages) | Una acción nombrada para mostrar/ocultar el panel de páginas. |
| [View_NavigationPanels_Signatures](#View_NavigationPanels_Signatures) | Una acción nombrada para mostrar/ocultar el panel de firmas. |
| [View_PageDisplay_SinglePage](#View_PageDisplay_SinglePage) | Una acción nombrada para mostrar una sola página. |
| [View_PageDisplay_SinglePageContinuous](#View_PageDisplay_SinglePageContinuous) | Una acción nombrada para mostrar una página continua única. |
| [View_PageDisplay_TwoUp](#View_PageDisplay_TwoUp) | Una acción nombrada para mostrar páginas como Two-Up. |
| [View_PageDisplay_TwoUpContinuous](#View_PageDisplay_TwoUpContinuous) | Una acción nombrada para mostrar páginas como Two-Up continuo. |
| [View_Toolbars_AdvanceEditing](#View_Toolbars_AdvanceEditing) | Una acción nombrada para mostrar/ocultar la barra de herramientas de edición avanzada. |
| [View_Toolbars_CommentMarkup](#View_Toolbars_CommentMarkup) | Una acción nombrada para mostrar/ocultar la barra de herramientas de comentarios. |
| [View_Toolbars_Edit](#View_Toolbars_Edit) | Una acción nombrada para mostrar/ocultar la barra de herramientas de edición. |
| [View_Toolbars_File](#View_Toolbars_File) | Una acción nombrada para mostrar/ocultar la barra de herramientas de archivo. |
| [View_Toolbars_Find](#View_Toolbars_Find) | Una acción nombrada para mostrar/ocultar la barra de herramientas de búsqueda. |
| [View_Toolbars_Forms](#View_Toolbars_Forms) | Una acción nombrada para mostrar/ocultar la barra de herramientas de formularios. |
| [View_Toolbars_Measuring](#View_Toolbars_Measuring) | Una acción nombrada para mostrar/ocultar la barra de herramientas de medición. |
| [View_Toolbars_ObjectData](#View_Toolbars_ObjectData) | Una acción nombrada para mostrar/ocultar la barra de herramientas de datos de objeto. |
| [View_Toolbars_PageDisplay](#View_Toolbars_PageDisplay) | Una acción nombrada para mostrar/ocultar la barra de herramientas de visualización de página. |
| [View_Toolbars_PageNavigation](#View_Toolbars_PageNavigation) | Una acción nombrada para mostrar/ocultar la barra de herramientas de navegación. |
| [View_Toolbars_PrintProduction](#View_Toolbars_PrintProduction) | Una acción nombrada para mostrar/ocultar la barra de herramientas de producción de impresión. |
| [View_Toolbars_PropertiesBar](#View_Toolbars_PropertiesBar) | Una acción nombrada para mostrar/ocultar la barra de herramientas de propiedades. |
| [View_Toolbars_Redaction](#View_Toolbars_Redaction) | Una acción nombrada para mostrar/ocultar la barra de herramientas de redacción. |
| [View_Toolbars_SelectZoom](#View_Toolbars_SelectZoom) | Una acción nombrada para mostrar/ocultar la barra de herramientas de selección y zoom. |
| [View_Toolbars_Tasks](#View_Toolbars_Tasks) | Una acción nombrada para mostrar/ocultar la barra de herramientas de tareas. |
| [View_Toolbars_Typewriter](#View_Toolbars_Typewriter) | Una acción nombrada para mostrar/ocultar la barra de herramientas de máquina de escribir. |
| [View_Zoom_ActualSize](#View_Zoom_ActualSize) | Una acción nombrada para ver las páginas en su tamaño real. |
| [View_Zoom_FitHeight](#View_Zoom_FitHeight) | Una acción nombrada para ajustar la página a la altura. |
| [View_Zoom_FitPage](#View_Zoom_FitPage) | Una acción nombrada para ajustar la página. |
| [View_Zoom_FitVisible](#View_Zoom_FitVisible) | Una acción nombrada para ajustar la visibilidad de la página. |
| [View_Zoom_FitWidth](#View_Zoom_FitWidth) | Una acción nombrada para ajustar la página al ancho. |
| [View_Zoom_ZoomTo](#View_Zoom_ZoomTo) | Una acción nombrada para hacer zoom. |
| [Window_FullScreenMode](#Window_FullScreenMode) | Una acción nombrada para ver el documento en modo pantalla completa. |

## Métodos

| Método | Descripción |
| --- | --- |
| [getByValue](#getByValue-int-) |  |
| [getValue](#getValue--) |  |
| [valueOf](#valueOf-java.lang.String-) | Devuelve la constante enum de este tipo con el nombre especificado. |
| [values](#values--) | Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran. |

### Bookmarks_ExpanCurrentBookmark {#Bookmarks_ExpanCurrentBookmark}
```
public static final PredefinedAction Bookmarks_ExpanCurrentBookmark
```

Una acción con nombre para encontrar el marcador actual.

### Bookmarks_HightlightCurrentBookmark {#Bookmarks_HightlightCurrentBookmark}
```
public static final PredefinedAction Bookmarks_HightlightCurrentBookmark
```

Una acción con nombre para resaltar el marcador actual.

### Document_AttachFile {#Document_AttachFile}
```
public static final PredefinedAction Document_AttachFile
```

Una acción con nombre para agregar un archivo adjunto.

### Document_CropPages {#Document_CropPages}
```
public static final PredefinedAction Document_CropPages
```

Una acción con nombre para recortar páginas del documento.

### Document_DeletePages {#Document_DeletePages}
```
public static final PredefinedAction Document_DeletePages
```

Una acción con nombre para eliminar páginas del documento.

### Document_ExtractPages {#Document_ExtractPages}
```
public static final PredefinedAction Document_ExtractPages
```

Una acción con nombre para extraer páginas del documento.

### Document_InsertPages {#Document_InsertPages}
```
public static final PredefinedAction Document_InsertPages
```

Una acción con nombre para insertar páginas desde un documento.

### Document_ReplacePages {#Document_ReplacePages}
```
public static final PredefinedAction Document_ReplacePages
```

Una acción con nombre para reemplazar páginas del documento.

### Document_RotatePages {#Document_RotatePages}
```
public static final PredefinedAction Document_RotatePages
```

Una acción con nombre para rotar páginas del documento.

### Edit_CheckSpelling_InComFieldEdit {#Edit_CheckSpelling_InComFieldEdit}
```
public static final PredefinedAction Edit_CheckSpelling_InComFieldEdit
```

Una acción con nombre para comprobar la ortografía en los comentarios.

### Edit_Find {#Edit_Find}
```
public static final PredefinedAction Edit_Find
```

Una acción con nombre para buscar.

### Edit_Preferences {#Edit_Preferences}
```
public static final PredefinedAction Edit_Preferences
```

Una acción con nombre para editar preferencias.

### Edit_Search {#Edit_Search}
```
public static final PredefinedAction Edit_Search
```

Una acción con nombre para buscar.

### File_AttachToEmail {#File_AttachToEmail}
```
public static final PredefinedAction File_AttachToEmail
```

Una acción con nombre para adjuntar el documento pdf actual en un mensaje de correo electrónico.

### File_Close {#File_Close}
```
public static final PredefinedAction File_Close
```

Una acción con nombre para cerrar el documento.

### File_CreatePDF_FromScanner {#File_CreatePDF_FromScanner}
```
public static final PredefinedAction File_CreatePDF_FromScanner
```

Una acción con nombre para crear un documento pdf a partir de un escáner.

### File_CreatePDF_FromWebPage {#File_CreatePDF_FromWebPage}
```
public static final PredefinedAction File_CreatePDF_FromWebPage
```

Una acción con nombre para crear un documento pdf a partir de una página web.

### File_Exit {#File_Exit}
```
public static final PredefinedAction File_Exit
```

Una acción con nombre para salir del lector pdf.

### File_Organizer_OpenOrganizer {#File_Organizer_OpenOrganizer}
```
public static final PredefinedAction File_Organizer_OpenOrganizer
```

Una acción nombrada para abrir el organizador.

### File_Print {#File_Print}
```
public static final PredefinedAction File_Print
```

Una acción nombrada para imprimir el documento.

### File_Properties {#File_Properties}
```
public static final PredefinedAction File_Properties
```

Una acción nombrada para abrir las propiedades del documento.

### File_SaveAs {#File_SaveAs}
```
public static final PredefinedAction File_SaveAs
```

Una acción nombrada para guardar el documento con otro nombre.

### FirstPage {#FirstPage}
```
public static final PredefinedAction FirstPage
```

Una acción nombrada para ir a la primera página.

### LastPage {#LastPage}
```
public static final PredefinedAction LastPage
```

Una acción nombrada para ir a la última página.

### Miscellaneous_ZoomIn {#Miscellaneous_ZoomIn}
```
public static final PredefinedAction Miscellaneous_ZoomIn
```

Una acción nombrada para acercar el documento.

### Miscellaneous_ZoomOut {#Miscellaneous_ZoomOut}
```
public static final PredefinedAction Miscellaneous_ZoomOut
```

Una acción nombrada para alejar el documento.

### NextPage {#NextPage}
```
public static final PredefinedAction NextPage
```

Una acción nombrada para ir a la página siguiente.

### PageImages_PrintPages {#PageImages_PrintPages}
```
public static final PredefinedAction PageImages_PrintPages
```

Una acción nombrada para imprimir las páginas del documento.

### PrevPage {#PrevPage}
```
public static final PredefinedAction PrevPage
```

Una acción nombrada para ir a la página anterior.

### Print {#Print}
```
public static final PredefinedAction Print
```

Una acción nombrada para abrir un cuadro de diálogo de impresión.

### PrintDialog {#PrintDialog}
```
public static final PredefinedAction PrintDialog
```

Una acción nombrada para abrir un cuadro de diálogo de impresión (JavaScript).

### View_GoTo_NextView {#View_GoTo_NextView}
```
public static final PredefinedAction View_GoTo_NextView
```

Una acción nombrada para ir a la vista siguiente.

### View_GoTo_Page {#View_GoTo_Page}
```
public static final PredefinedAction View_GoTo_Page
```

Una acción nombrada para ir a la página determinada.

### View_GoTo_PreDocument {#View_GoTo_PreDocument}
```
public static final PredefinedAction View_GoTo_PreDocument
```

Una acción nombrada para ir al documento anterior.

### View_GoTo_PreView {#View_GoTo_PreView}
```
public static final PredefinedAction View_GoTo_PreView
```

Una acción nombrada para ir a la vista anterior.

### View_NavigationPanels_Articles {#View_NavigationPanels_Articles}
```
public static final PredefinedAction View_NavigationPanels_Articles
```

Una acción nombrada para mostrar/ocultar el panel de artículos.

### View_NavigationPanels_Attachments {#View_NavigationPanels_Attachments}
```
public static final PredefinedAction View_NavigationPanels_Attachments
```

Una acción nombrada para mostrar/ocultar el panel de adjuntos.

### View_NavigationPanels_Boomarks {#View_NavigationPanels_Boomarks}
```
public static final PredefinedAction View_NavigationPanels_Boomarks
```

Una acción nombrada para mostrar/ocultar el panel de marcadores.

### View_NavigationPanels_Comments {#View_NavigationPanels_Comments}
```
public static final PredefinedAction View_NavigationPanels_Comments
```

Una acción nombrada para mostrar/ocultar el panel de comentarios.

### View_NavigationPanels_Fields {#View_NavigationPanels_Fields}
```
public static final PredefinedAction View_NavigationPanels_Fields
```

Una acción nombrada para mostrar/ocultar el panel de campos.

### View_NavigationPanels_Layers {#View_NavigationPanels_Layers}
```
public static final PredefinedAction View_NavigationPanels_Layers
```

Una acción nombrada para mostrar/ocultar el panel de capas.

### View_NavigationPanels_ModelTree {#View_NavigationPanels_ModelTree}
```
public static final PredefinedAction View_NavigationPanels_ModelTree
```

Una acción nombrada para mostrar/ocultar el panel de árbol de modelo.

### View_NavigationPanels_Pages {#View_NavigationPanels_Pages}
```
public static final PredefinedAction View_NavigationPanels_Pages
```

Una acción nombrada para mostrar/ocultar el panel de páginas.

### View_NavigationPanels_Signatures {#View_NavigationPanels_Signatures}
```
public static final PredefinedAction View_NavigationPanels_Signatures
```

Una acción nombrada para mostrar/ocultar el panel de firmas.

### View_PageDisplay_SinglePage {#View_PageDisplay_SinglePage}
```
public static final PredefinedAction View_PageDisplay_SinglePage
```

Una acción nombrada para mostrar una sola página.

### View_PageDisplay_SinglePageContinuous {#View_PageDisplay_SinglePageContinuous}
```
public static final PredefinedAction View_PageDisplay_SinglePageContinuous
```

Una acción nombrada para mostrar una página continua única.

### View_PageDisplay_TwoUp {#View_PageDisplay_TwoUp}
```
public static final PredefinedAction View_PageDisplay_TwoUp
```

Una acción nombrada para mostrar páginas como Two-Up.

### View_PageDisplay_TwoUpContinuous {#View_PageDisplay_TwoUpContinuous}
```
public static final PredefinedAction View_PageDisplay_TwoUpContinuous
```

Una acción nombrada para mostrar páginas como Two-Up continuo.

### View_Toolbars_AdvanceEditing {#View_Toolbars_AdvanceEditing}
```
public static final PredefinedAction View_Toolbars_AdvanceEditing
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de edición avanzada.

### View_Toolbars_CommentMarkup {#View_Toolbars_CommentMarkup}
```
public static final PredefinedAction View_Toolbars_CommentMarkup
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de comentarios.

### View_Toolbars_Edit {#View_Toolbars_Edit}
```
public static final PredefinedAction View_Toolbars_Edit
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de edición.

### View_Toolbars_File {#View_Toolbars_File}
```
public static final PredefinedAction View_Toolbars_File
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de archivo.

### View_Toolbars_Find {#View_Toolbars_Find}
```
public static final PredefinedAction View_Toolbars_Find
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de búsqueda.

### View_Toolbars_Forms {#View_Toolbars_Forms}
```
public static final PredefinedAction View_Toolbars_Forms
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de formularios.

### View_Toolbars_Measuring {#View_Toolbars_Measuring}
```
public static final PredefinedAction View_Toolbars_Measuring
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de medición.

### View_Toolbars_ObjectData {#View_Toolbars_ObjectData}
```
public static final PredefinedAction View_Toolbars_ObjectData
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de datos de objeto.

### View_Toolbars_PageDisplay {#View_Toolbars_PageDisplay}
```
public static final PredefinedAction View_Toolbars_PageDisplay
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de visualización de página.

### View_Toolbars_PageNavigation {#View_Toolbars_PageNavigation}
```
public static final PredefinedAction View_Toolbars_PageNavigation
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de navegación.

### View_Toolbars_PrintProduction {#View_Toolbars_PrintProduction}
```
public static final PredefinedAction View_Toolbars_PrintProduction
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de producción de impresión.

### View_Toolbars_PropertiesBar {#View_Toolbars_PropertiesBar}
```
public static final PredefinedAction View_Toolbars_PropertiesBar
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de propiedades.

### View_Toolbars_Redaction {#View_Toolbars_Redaction}
```
public static final PredefinedAction View_Toolbars_Redaction
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de redacción.

### View_Toolbars_SelectZoom {#View_Toolbars_SelectZoom}
```
public static final PredefinedAction View_Toolbars_SelectZoom
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de selección y zoom.

### View_Toolbars_Tasks {#View_Toolbars_Tasks}
```
public static final PredefinedAction View_Toolbars_Tasks
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de tareas.

### View_Toolbars_Typewriter {#View_Toolbars_Typewriter}
```
public static final PredefinedAction View_Toolbars_Typewriter
```

Una acción nombrada para mostrar/ocultar la barra de herramientas de máquina de escribir.

### View_Zoom_ActualSize {#View_Zoom_ActualSize}
```
public static final PredefinedAction View_Zoom_ActualSize
```

Una acción nombrada para ver las páginas en su tamaño real.

### View_Zoom_FitHeight {#View_Zoom_FitHeight}
```
public static final PredefinedAction View_Zoom_FitHeight
```

Una acción nombrada para ajustar la página a la altura.

### View_Zoom_FitPage {#View_Zoom_FitPage}
```
public static final PredefinedAction View_Zoom_FitPage
```

Una acción nombrada para ajustar la página.

### View_Zoom_FitVisible {#View_Zoom_FitVisible}
```
public static final PredefinedAction View_Zoom_FitVisible
```

Una acción nombrada para ajustar la visibilidad de la página.

### View_Zoom_FitWidth {#View_Zoom_FitWidth}
```
public static final PredefinedAction View_Zoom_FitWidth
```

Una acción nombrada para ajustar la página al ancho.

### View_Zoom_ZoomTo {#View_Zoom_ZoomTo}
```
public static final PredefinedAction View_Zoom_ZoomTo
```

Una acción nombrada para hacer zoom.

### Window_FullScreenMode {#Window_FullScreenMode}
```
public static final PredefinedAction Window_FullScreenMode
```

Una acción nombrada para ver el documento en modo pantalla completa.

### getByValue {#getByValue-int-}
```
public static PredefinedAction getByValue(int value)
```



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor |  |  |

### getValue {#getValue--}
```
public int getValue()
```



### valueOf {#valueOf-java.lang.String-}
Devuelve la constante enum de este tipo con el nombre especificado.

### values {#values--}
```
public static PredefinedAction [] values()
```

Devuelve una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran.

**Returns:**
una matriz que contiene las constantes de este tipo enum, en el orden en que se declaran
