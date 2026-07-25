---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant de visualiser ou d'imprimer un PDF."
type: docs
weight: 610
url: /fr/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Représente une classe permettant de visualiser ou d'imprimer un PDF.

## Champs

| Champ | Description |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Ajoute/supprime l'abonnement à l'événement d'impression de la dernière page. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Ajoute/supprime l'abonnement à l'événement d'impression de la dernière page. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Initialise un nouvel objet {@code PdfViewer}. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Initialise un nouvel objet {@code PdfViewer}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-) | Initialise la façade. |
| [close](#close--) | Ferme le fichier PDF actuel. |
| [closePdfFile](#closePdfFile--) | Ferme le fichier PDF actuel. |
| [decodeAllPages](#decodeAllPages--) | Obtient les pages du fichier PDF actuel. |
| [decodePage](#decodePage-int-) | Décode une page d'un fichier PDF. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Décode la page en BufferedImage |
| [dispose](#dispose--) | Libère les ressources de la façade. Cette méthode est obsolète, utilisez close() à la place. |
| [getAutoResize](#getAutoResize--) | Définit une valeur booléenne indiquant si le fichier doit être imprimé avec une taille optimisée. |
| [getAutoRotate](#getAutoRotate--) | Obtient une valeur bool qui indique si le fichier doit être imprimé avec rotation automatique |
| [getAutoRotateMode](#getAutoRotateMode--) | Obtient une valeur AutoRotateMode qui indique la direction de la rotation |
| [getCoordinateType](#getCoordinateType--) | Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [getCopiesPrinted](#getCopiesPrinted--) | Obtient le nombre de copies imprimées |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Obtient les paramètres de page par défaut. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Obtient les paramètres d'imprimante par défaut. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtient le mode de présentation du formulaire. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient une valeur qui indique l'alignement horizontal |
| [getPageCount](#getPageCount--) | Obtient le nombre de pages du fichier Pdf actuel. |
| [getPassword](#getPassword--) | Obtient le mot de passe du document d'entrée. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Obtient ou définit une valeur bool qui indique si la page est imprimée en niveaux de gris. Par défaut, false est false. </p> <hr> False par défaut est false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Obtient un mode pour PdfViewer afin d'imprimer en tant qu'image. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Obtient le nom du document dans la file d'attente de l'imprimante lorsque le document est imprimé. La valeur par défaut est le nom du fichier. |
| [getPrintPageDialog](#getPrintPageDialog--) | Obtient une valeur bool qui indique s'il faut produire la boîte de dialogue du numéro de page lors de l'impression. |
| [getPrintStatus](#getPrintStatus--) | Obtient le résultat de la tâche d'impression. En cas de succès, null ; sinon, un objet d'exception. |
| [getRenderingOptions](#getRenderingOptions--) | Obtient les options de rendu. |
| [getResolution](#getResolution--) | Obtient ou définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. Cette propriété modifie la résolution d'image dans les flux de conversion page‑vers‑image : lorsque {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) est définie sur {@code }, ou lorsque la méthode {@link #decodePage(int)} ou {@link #decodeAllPages} est appelée. Pour définir une résolution d'imprimante pour l'impression directe sur une imprimante, utilisez la propriété {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dans la classe {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Obtient une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Obtient l'utilisation de la conversion d'une page pdf en fichier png intermédiaire lors de l'impression en mode fichier. À utiliser lorsque la taille du fichier de sortie est importante. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient une valeur qui indique l'alignement vertical |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Cette méthode est obsolète. Obtient le drapeau qui contrôle la visibilité des zones cachées sur la page. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Ouvre un flux de fichier Pdf. Mais ne décode pas réellement les pages du fichier Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\\\test.pdf"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Ouvre un fichier Pdf, mais ne décode pas réellement les pages du fichier Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Imprime le document Pdf en utilisant l'imprimante par défaut. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime le fichier avec taille ajustée viewer.setAutoRotate ( true); //imprime le fichier avec rotation ajustée viewer.setPrintPageDialog ( false); //ne pas produire la boîte de dialogue du numéro de page lors de l'impression viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime le document Pdf avec les paramètres d'imprimante. La taille de la page de sortie s'adaptera à la taille de la première page du document. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime le fichier avec taille ajustée viewer.setAutoRotate ( true); //imprime le fichier avec rotation ajustée viewer.setPrintPageDialog ( false); //ne pas produire la boîte de dialogue du numéro de page lors de l'impression PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Imprime le document Pdf avec les paramètres. Si la taille du document n'est pas compatible avec la taille de la page, pdf.kit l'étendra pour s'adapter à la taille de la page. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //imprime le fichier avec une taille ajustée viewer.setAutoRotate ( true); //imprime le fichier avec une rotation ajustée viewer.setPrintPageDialog ( false);//ne pas afficher la boîte de dialogue du numéro de page lors de l'impression PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Ouvre et imprime un flux Pdf volumineux. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //imprime le fichier avec une taille ajustée viewer.setAutoRotate ( true); //imprime le fichier avec une rotation ajustée viewer.printPageDialog=false;//ne pas afficher la boîte de dialogue du numéro de page lors de l'impression viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler OpenPdfFile() explicitement. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Ouvre et imprime un flux Pdf volumineux avec des paramètres d'imprimante spécifiés. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime le fichier avec une taille ajustée viewer.setAutoRotate(true); // imprime le fichier avec une rotation ajustée viewer.setPrintPageDialog(false); // ne pas produire la boîte de dialogue du numéro de page lorsque // impression PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler OpenPdfFile() explicitement. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Ouvre et imprime un flux Pdf volumineux avec des paramètres de page et d'imprimante spécifiés. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //imprime le fichier avec une taille ajustée viewer.setAutoRotate ( true); //imprime le fichier avec une rotation ajustée viewer.setPrintPageDialog ( false);//ne pas produire la boîte de dialogue du numéro de page lors de l'impression PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler OpenPdfFile() explicitement. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Ouvre et imprime un fichier Pdf volumineux. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // imprime le fichier avec une taille ajustée viewer.setAutoRotate(true); // imprime le fichier avec une rotation ajustée viewer.setPrintPageDialog(false);// ne pas produire la boîte de dialogue du numéro de page lorsque // impression viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Ouvre et imprime un gros fichier Pdf avec les paramètres d'imprimante spécifiés. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile(). |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Ouvre et imprime un gros fichier Pdf avec les paramètres de page et d'imprimante spécifiés. Si votre fichier Pdf compte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile(). |
| [save](#save-java.io.InputStream-) | Enregistre le document PDF résultant dans un flux. |
| [save](#save-java.lang.String-) | Enregistre le document PDF résultant dans un fichier. |
| [setAutoResize](#setAutoResize-boolean-) | Définit une valeur booléenne indiquant si le fichier doit être imprimé avec une taille optimisée. |
| [setAutoRotate](#setAutoRotate-boolean-) | Définit une valeur booléenne qui indique si le fichier doit être imprimé avec rotation automatique |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Définit une valeur AutoRotateMode qui indique la direction de la rotation |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Définit le mode de présentation du formulaire. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit une valeur qui indique l'alignement horizontal |
| [setPassword](#setPassword-java.lang.String-) | Définit le mot de passe du document d'entrée. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Obtient ou définit une valeur bool qui indique si la page est imprimée en niveaux de gris. Par défaut, false est false. </p> <hr> False par défaut est false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Définit un mode pour PdfViewer afin d'imprimer en tant qu'image. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Définit le nom du document dans la file d'attente de l'imprimante lors de l'impression du document. La valeur par défaut est le nom du fichier. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Définit une valeur booléenne qui indique s'il faut produire la boîte de dialogue du numéro de page lors de l'impression. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Définit les options de rendu. |
| [setResolution](#setResolution-int-) | Définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. Cette propriété modifie la résolution d'image dans les flux de conversion page‑vers‑image : lorsque {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) est définie sur {@code }, ou lorsque la méthode {@link #decodePage(int)} ou {@link #decodeAllPages} est appelée. Pour définir une résolution d'imprimante pour l'impression directe sur une imprimante, utilisez la propriété {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dans la classe {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | Définit une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1,0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Obsolète. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Définit l'utilisation de la conversion d'une page pdf en fichier png intermédiaire lors de l'impression en mode fichier. À utiliser lorsque la taille du fichier de sortie est importante. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit une valeur qui indique l'alignement vertical |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Ajoute/supprime l'abonnement à l'événement d'impression de la dernière page.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Ajoute/supprime l'abonnement à l'événement d'impression de la dernière page.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Initialise un nouvel objet {@code PdfViewer}.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Initialise un nouvel objet {@code PdfViewer}.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Initialise la façade.

### bindPdf {#bindPdf-java.io.InputStream-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-}
Initialise la façade.

### close {#close--}
```
public void close()
```

Ferme le fichier PDF actuel.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Ferme le fichier PDF actuel.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Obtient les pages du fichier PDF actuel.

**Returns:**
renvoie le tableau d'images de pages Pdf.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Décode une page d'un fichier PDF.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber |  | Le numéro de page d'un fichier Pdf qui doit être compris entre 1 et PageCount. |

**Returns:**
renvoie l'image de la page Pdf.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Décode la page en BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Libère les ressources de la façade. Cette méthode est obsolète, utilisez close() à la place.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Définit une valeur booléenne indiquant si le fichier doit être imprimé avec une taille optimisée.

**Returns:**
valeur booléenne : si false, imprime la page sans mise à l'échelle. Si true, imprime la page avec mise à l'échelle pour s'adapter à la zone imprimable.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Obtient une valeur bool qui indique si le fichier doit être imprimé avec rotation automatique

**Returns:**
valeur booléenne

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Obtient une valeur AutoRotateMode qui indique la direction de la rotation

**Returns:**
Élément AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

**Returns:**
PageCoordinateType élément @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Obtient le nombre de copies imprimées

**Returns:**
valeur int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Obtient les paramètres de page par défaut.

**Returns:**
Objet de paramètres de page.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Obtient les paramètres d'imprimante par défaut.

**Returns:**
Objet de paramètres de page.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtient le mode de présentation du formulaire.

**Returns:**
FormPresentationMode élément @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient une valeur qui indique l'alignement horizontal

**Returns:**
Élément HorizontalAlignment @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Obtient le nombre de pages du fichier Pdf actuel.

**Returns:**
renvoie le nombre de pages.

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtient le mot de passe du document d'entrée.

**Returns:**
valeur String

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Obtient ou définit une valeur bool qui indique si la page est imprimée en niveaux de gris. Par défaut, false est false. </p> <hr> False par défaut est false.

**Returns:**
valeur booléenne

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Obtient un mode pour PdfViewer afin d'imprimer en tant qu'image. </p>

**Returns:**
valeur booléenne <hr> Si true, imprime toujours en tant qu'image (génère l'image qui est imprimée). Si false, imprime directement sur le dispositif si toutes les fonctionnalités sont prises en charge. Dans le cas où le document contient des fonctionnalités non prises en charge, le système peut automatiquement décider d'imprimer en tant qu'image. La valeur par défaut est false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Obtient le nom du document dans la file d'attente de l'imprimante lorsque le document est imprimé. La valeur par défaut est le nom du fichier.

**Returns:**
valeur String

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Obtient une valeur bool qui indique s'il faut produire la boîte de dialogue du numéro de page lors de l'impression.

**Returns:**
valeur booléenne

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Obtient le résultat de la tâche d'impression. En cas de succès, null ; sinon, un objet d'exception.

**Returns:**
objet d'exception ou null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtient les options de rendu.

**Returns:**
Objet RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtient ou définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. Cette propriété modifie la résolution d'image dans les flux de conversion page‑vers‑image : lorsque {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) est définie sur {@code }, ou lorsque la méthode {@link #decodePage(int)} ou {@link #decodeAllPages} est appelée. Pour définir une résolution d'imprimante pour l'impression directe sur une imprimante, utilisez la propriété {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dans la classe {@code PageSettings}.

**Returns:**
valeur int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Obtient une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1.0.

**Returns:**
valeur à virgule flottante.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Obtient l'utilisation de la conversion d'une page pdf en fichier png intermédiaire lors de l'impression en mode fichier. À utiliser lorsque la taille du fichier de sortie est importante.

**Returns:**
valeur booléenne.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient une valeur qui indique l'alignement vertical

**Returns:**
Élément VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Cette méthode est obsolète. Obtient le drapeau qui contrôle la visibilité des zones cachées sur la page.

**Returns:**
valeur booléenne

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Ouvre un flux de fichier Pdf. Mais ne décode pas réellement les pages du fichier Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Ouvre un fichier Pdf, mais ne décode pas réellement les pages du fichier Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Imprime le document Pdf en utilisant l'imprimante par défaut. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime le document Pdf avec les paramètres de l'imprimante. La taille de la page de sortie s'ajustera à la taille de la première page du document. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false); //do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Imprime le document Pdf avec les paramètres. Si la taille du document n'est pas compatible avec la taille de la page, pdf.kit l'étendra pour l'adapter à la taille de la page. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Ouvre et imprime un grand flux Pdf. Si votre fichier Pdf comporte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.printPageDialog=false;//do not produce the page number dialog when printing viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Ouvre et imprime un grand flux Pdf avec des paramètres d'imprimante spécifiés. Si votre fichier Pdf comporte des centaines de pages ou plus ou si sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Ouvre et imprime un flux PDF volumineux avec les paramètres de page et d'imprimante spécifiés. Si votre fichier PDF comporte des centaines de pages ou plus ou que sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize(\"A4\", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream(\"d:\\\\middleware.pdf\"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Ouvre et imprime un fichier PDF volumineux. Si votre fichier PDF comporte des centaines de pages ou plus ou que sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf(\"d:\\test.pdf\"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Ouvre et imprime un fichier PDF volumineux avec les paramètres d'imprimante spécifiés. Si votre fichier PDF comporte des centaines de pages ou plus ou que sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(\"d:\\\\test.pdf\",ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Ouvre et imprime un fichier PDF volumineux avec les paramètres de page et d'imprimante spécifiés. Si votre fichier PDF comporte des centaines de pages ou plus ou que sa taille dépasse 3 Mo, cette méthode est recommandée pour obtenir de meilleures performances. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize(\"A4\", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf(\"d:\\\\test.pdf\", pgs, ps); viewer.closePdfFile(); </pre> <hr> Cette méthode intègre l'ouverture et l'impression du fichier et vous n'avez pas besoin d'appeler explicitement OpenPdfFile().

### save {#save-java.io.InputStream-}
Enregistre le document PDF résultant dans un flux.

### save {#save-java.lang.String-}
Enregistre le document PDF résultant dans un fichier.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Définit une valeur booléenne indiquant si le fichier doit être imprimé avec une taille optimisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne : si false, imprime la page sans mise à l'échelle. Si true, imprime la page avec mise à l'échelle pour s'adapter à la zone imprimable. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Définit une valeur booléenne qui indique si le fichier doit être imprimé avec rotation automatique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Définit une valeur AutoRotateMode qui indique la direction de la rotation

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Définit le mode de présentation du formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément FormPresentationMode |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit une valeur qui indique l'alignement horizontal

### setPassword {#setPassword-java.lang.String-}
Définit le mot de passe du document d'entrée.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Obtient ou définit une valeur bool qui indique si la page est imprimée en niveaux de gris. Par défaut, false est false. </p> <hr> False par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Définit un mode pour PdfViewer afin d'imprimer en tant qu'image. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne <hr> Si true, imprime toujours en tant qu'image (génère l'image qui est imprimée). Si false, imprime directement sur le dispositif si toutes les fonctionnalités sont prises en charge. Dans le cas où le document contient des fonctionnalités non prises en charge, le système peut automatiquement décider d'imprimer en tant qu'image. La valeur par défaut est false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Définit le nom du document dans la file d'attente de l'imprimante lors de l'impression du document. La valeur par défaut est le nom du fichier.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Définit une valeur booléenne qui indique s'il faut produire la boîte de dialogue du numéro de page lors de l'impression.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Définit les options de rendu.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Définit la résolution lors de la visualisation et de l'impression. Plus la résolution est élevée, plus la vitesse est lente. La valeur par défaut est 150. Cette propriété modifie la résolution d'image dans les flux de conversion page‑vers‑image : lorsque {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) est définie sur {@code }, ou lorsque la méthode {@link #decodePage(int)} ou {@link #decodeAllPages} est appelée. Pour définir une résolution d'imprimante pour l'impression directe sur une imprimante, utilisez la propriété {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dans la classe {@code PageSettings}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Définit une valeur à virgule flottante qui indique le facteur d'échelle. La valeur par défaut est 1,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur à virgule flottante. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Obsolète.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Définit l'utilisation de la conversion d'une page pdf en fichier png intermédiaire lors de l'impression en mode fichier. À utiliser lorsque la taille du fichier de sortie est importante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit une valeur qui indique l'alignement vertical
