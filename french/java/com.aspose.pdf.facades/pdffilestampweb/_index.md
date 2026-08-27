---
title: "PdfFileStampWeb"
linktitle: "PdfFileStampWeb"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe permettant d'ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF. Activez‑la pour travailler avec HttpServletResponse."
type: docs
weight: 550
url: /fr/java/com.aspose.pdf.facades/pdffilestampweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileStampWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileStampWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IPdfFileStamp, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileStampWeb extends SaveableFacade implements IPdfFileStamp
```

Classe permettant d'ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF. Activez‑la pour travailler avec HttpServletResponse.

## Champs

| Champ | Description |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | Position en bas à gauche. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | Position en bas au centre. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | Position en bas à droite. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | Position à gauche. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | Position à droite. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | Position en haut à gauche. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | Position au milieu supérieur. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | Position en haut à droite. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileStampWeb](#PdfFileStampWeb--) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |
| [PdfFileStampWeb](#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-) | <p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | <p> Ajoute un pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre> |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Ajoute un pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-) | <p> Ajoute une image en pied de page de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | <p> Ajoute une image en pied de page de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-) | <p> Ajoute une image en pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre> |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Ajoute une image en pied de page des pages. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | <p> Ajoute un en-tête à la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | <p> Ajoute un en-tête aux pages du fichier. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-) | <p> Ajoute une image en en-tête sur les pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | <p> Ajoute une image en haut de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-) | <p> Ajoute une image en en-tête aux pages du fichier. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre> |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | <p> Ajoute une image en en-tête sur les pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | <p> Ajoute un numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de page. Le numéro de page est placé en bas de la page, centré horizontalement. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | <p> Ajoute un numéro de page à la position spécifiée sur la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | <p> Ajoute le numéro de page aux pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | <p> Ajoute le numéro de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-) | <p> Ajoute un numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page, centré horizontalement. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | <p> Ajoute un numéro de page à la position spécifiée sur la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | <p> Ajoute le numéro de page aux pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre> |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | <p> Ajoute le numéro de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre> |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | <p> Ajoute un tampon au fichier. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [close](#close--) | <p> Ferme les fichiers ouverts et enregistre les modifications. Attention. Si des flux d'entrée ou de sortie sont spécifiés, ils ne sont pas fermés par la méthode Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre> |
| [dispose](#dispose--) | Obsolète. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline. |
| [getInputFile](#getInputFile--) | Obtient le nom et le chemin du fichier d'entrée. |
| [getInputStream](#getInputStream--) | Obtient le flux d'entrée. |
| [getKeepSecurity](#getKeepSecurity--) | Conserve la sécurité si true. (Cette fonctionnalité sera implémentée dans les prochaines versions). |
| [getNumberingStyle](#getNumberingStyle--) | Obtient ou définit le style de numérotation des pages. |
| [getOptimizeSize](#getOptimizeSize--) | Obtient ou définit le drapeau d'optimisation. |
| [getOutputFile](#getOutputFile--) | Obtient le nom et le chemin du fichier de sortie. |
| [getOutputStream](#getOutputStream--) | Obtient le flux de sortie. |
| [getPageHeight](#getPageHeight--) | <p> Obtient la hauteur de la première page du fichier source. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre> |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtient la rotation du numéro de page. La rotation est exprimée en degrés. La valeur par défaut est 0. |
| [getPageWidth](#getPageWidth--) | <p> Obtient la largeur de la première page du fichier d'entrée. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre> |
| [getResponse](#getResponse--) | Obtient l'objet Response où le résultat de l'opération sera stocké. |
| [getSaveOptions](#getSaveOptions--) | Obtient les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [getStampId](#getStampId--) | Identifiant du tampon du prochain tampon ajouté (y compris les en-têtes/pieds de page/nombres de page). |
| [getStartingNumber](#getStartingNumber--) | Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [setInputFile](#setInputFile-java.lang.String-) | Définit le nom et le chemin du fichier d'entrée. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Définit le flux d'entrée. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Conserve la sécurité si true. (Cette fonctionnalité sera implémentée dans les prochaines versions). |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Obtient ou définit le style de numérotation des pages. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtient ou définit le drapeau d'optimisation. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Définit le nom et le chemin du fichier de sortie. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Définit ou définit le flux de sortie. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Définit la rotation du numéro de page. La rotation est exprimée en degrés. La valeur par défaut est 0. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Définit l'objet Response où le résultat de l'opération sera stocké. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [setStampId](#setStampId-int-) | Identifiant du tampon du prochain tampon ajouté (y compris les en-têtes/pieds de page/nombres de page). |
| [setStartingNumber](#setStartingNumber-int-) | <p> Définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est fixé à 100, les pages du document auront les numéros 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre> |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
public static final int POS_BOTTOM_LEFT
```

Position en bas à gauche.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
public static final int POS_BOTTOM_MIDDLE
```

Position en bas au centre.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
public static final int POS_BOTTOM_RIGHT
```

Position en bas à droite.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
public static final int POS_SIDES_LEFT
```

Position à gauche.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
public static final int POS_SIDES_RIGHT
```

Position à droite.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
public static final int POS_UPPER_LEFT
```

Position en haut à gauche.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
public static final int POS_UPPER_MIDDLE
```

Position au milieu supérieur.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
public static final int POS_UPPER_RIGHT
```

Position en haut à droite.

### PdfFileStampWeb {#PdfFileStampWeb--}
```
public PdfFileStampWeb()
```

<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.io.InputStream-java.io.OutputStream-boolean-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### PdfFileStampWeb {#PdfFileStampWeb-java.lang.String-java.lang.String-boolean-}
<p> Constructeur de PdfFileStamp. Le fichier d'entrée et le fichier de sortie peuvent être spécifiés via les propriétés correspondantes. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(); fileStamp.setInputFile ( \"input.pdf\"); fileStamp.setOutputFile ( \"output.pdf\"); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
<p> Ajoute un pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10); </pre>

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Ajoute un pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addFooter(new FormattedText(\"Foot of the page\"), 10, 50, 50); </pre>

### addFooter {#addFooter-java.io.InputStream-float-}
<p> Ajoute une image en pied de page de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
<p> Ajoute une image en pied de page de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addFooter(input, 50, 50, 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-}
<p> Ajoute une image en pied de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addFooter("image.jpg", 50); fileStamp.close(); </pre>

### addFooter {#addFooter-java.lang.String-float-float-float-}
Ajoute une image en pied de page des pages.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
<p> Ajoute un en-tête à la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addHeader(new FormattedText(\"Head of the page\"), 50); fileStamp.close(); </pre>

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
<p> Ajoute un en-tête aux pages du fichier. </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); stamp.addHeader(new FormattedText(\"Head of the page\"), 10, 50, 50); </pre>

### addHeader {#addHeader-java.io.InputStream-float-}
<p> Ajoute une image en en-tête sur les pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
<p> Ajoute une image en haut de la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); InputStream input = new FileInputStream("test.jpg"); fileStamp.addHeader(input, 50, 100, 100); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-}
<p> Ajoute une image en en-tête aux pages du fichier. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50); fileStamp.close(); </pre>

### addHeader {#addHeader-java.lang.String-float-float-float-}
<p> Ajoute une image en en-tête sur les pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", output.pdf"); fileStamp.addHeader("image.jpg", 50, 100, 100); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
<p> Ajoute un numéro de page à la page. Le numéro de page peut contenir le signe # qui sera remplacé par le numéro de page. Le numéro de page est placé en bas de la page, centré horizontalement. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\")); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
<p> Ajoute un numéro de page à la position spécifiée sur la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
<p> Ajoute le numéro de page aux pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
<p> Ajoute le numéro de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber(new FormattedText("Page #"), PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-}
<p> Ajoute un numéro de page au fichier. Le texte du numéro de page peut contenir le signe # qui sera remplacé par le numéro de la page. Le numéro de page est placé en bas de la page, centré horizontalement. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(\"Page #\"); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
<p> Ajoute un numéro de page à la position spécifiée sur la page. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); fileStamp.addPageNumber(new FormattedText(\"Page #\"), 123, 357); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-}
<p> Ajoute le numéro de page aux pages. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.PosUpperRight); fileStamp.close(); </pre>

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
<p> Ajoute le numéro de page aux pages du document. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.addPageNumber("Page #", PdfFileStamp.POS_BOTTOM_LEFT, 100, 100, 200, 200); fileStamp.close(); </pre>

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
<p> Ajoute un tampon au fichier. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.setOrigin(140, 400); stamp.setImageSize(50, 50); stamp.setOpacity ( 0.8f); stamp.isBackground ( true); stamp.bindImage("image.jpg"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### close {#close--}
```
public void close()
```

<p> Ferme les fichiers ouverts et enregistre les modifications. Attention. Si des flux d'entrée ou de sortie sont spécifiés, ils ne sont pas fermés par la méthode Close(). </p> <hr> <pre> PdfFileStamp stamp = new PdfFileStamp("input.pdf", "output.pdf"); //do some work... stamp.close(); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsolète.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
objet string

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline.

**Returns:**
Élément ContentDisposition

### getInputFile {#getInputFile--}
```
public String getInputFile()
```

Obtient le nom et le chemin du fichier d'entrée.

**Returns:**
Objet String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Obtient le flux d'entrée.

**Returns:**
Objet InputStream

### getKeepSecurity {#getKeepSecurity--}
```
public boolean getKeepSecurity()
```

Conserve la sécurité si true. (Cette fonctionnalité sera implémentée dans les prochaines versions).

**Returns:**
valeur booléenne

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Obtient ou définit le style de numérotation des pages.

**Returns:**
Élément NumberingStyle

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtient ou définit le drapeau d'optimisation.

**Returns:**
valeur booléenne

### getOutputFile {#getOutputFile--}
```
public String getOutputFile()
```

Obtient le nom et le chemin du fichier de sortie.

**Returns:**
Objet String

### getOutputStream {#getOutputStream--}
```
public OutputStream getOutputStream()
```

Obtient le flux de sortie.

**Returns:**
Objet OutputStream

### getPageHeight {#getPageHeight--}
```
public float getPageHeight()
```

<p> Obtient la hauteur de la première page du fichier source. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Height = " + fileStamp.getPageHeight()); fileStamp.close(); </pre>

**Returns:**
Valeur flottante

### getPageNumberRotation {#getPageNumberRotation--}
```
public float getPageNumberRotation()
```

Obtient la rotation du numéro de page. La rotation est exprimée en degrés. La valeur par défaut est 0.

**Returns:**
Valeur flottante

### getPageWidth {#getPageWidth--}
```
public float getPageWidth()
```

<p> Obtient la largeur de la première page du fichier d'entrée. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); System.out.println("Width = " + fileStamp.getPageWidth()); fileStamp.close(); </pre>

**Returns:**
Valeur flottante

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtient l'objet Response où le résultat de l'opération sera stocké.

**Returns:**
Objet HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

**Returns:**
Objet SaveOptions

### getStampId {#getStampId--}
```
public int getStampId()
```

Identifiant du tampon du prochain tampon ajouté (y compris les en-têtes/pieds de page/nombres de page).

**Returns:**
valeur int

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur.

**Returns:**
valeur int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion.

### setInputFile {#setInputFile-java.lang.String-}
Définit le nom et le chemin du fichier d'entrée.

### setInputStream {#setInputStream-java.io.InputStream-}
Définit le flux d'entrée.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
public void setKeepSecurity(boolean value)
```

Conserve la sécurité si true. (Cette fonctionnalité sera implémentée dans les prochaines versions).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Obtient ou définit le style de numérotation des pages.

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtient ou définit le drapeau d'optimisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOutputFile {#setOutputFile-java.lang.String-}
Définit le nom et le chemin du fichier de sortie.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Définit ou définit le flux de sortie.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
public void setPageNumberRotation(float value)
```

Définit la rotation du numéro de page. La rotation est exprimée en degrés. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Définit l'objet Response où le résultat de l'opération sera stocké.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Identifiant du tampon du prochain tampon ajouté (y compris les en-têtes/pieds de page/nombres de page).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

<p> Définit le numéro de départ pour la première page du fichier d'entrée. Les pages suivantes seront numérotées à partir de cette valeur. Par exemple, si StartingNumber est fixé à 100, les pages du document auront les numéros 100, 101, 102... </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); fileStamp.setStartingNumber( 100); fileStamp.addPageNumber("Page #"); fileStamp.close(); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
