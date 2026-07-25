---
title: "PdfFileMend"
linktitle: "PdfFileMend"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe permettant d'ajouter du texte et des images sur les pages d'un document PDF existant."
type: docs
weight: 500
url: /fr/java/com.aspose.pdf.facades/pdffilemend/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.PdfFileMend, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.PdfFileMend

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, ISaveableFacade, Closeable, AutoCloseable

```
public final class PdfFileMend extends SaveableFacade
```

Représente une classe permettant d'ajouter du texte et des images sur les pages d'un document PDF existant.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileMend](#PdfFileMend--) | Constructeur. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-) | Constructeur. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Constructeur. |
| [PdfFileMend](#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-) | Constructeur. |
| [PdfFileMend](#PdfFileMend-java.io.InputStream-java.io.OutputStream-) | Constructeur. |
| [PdfFileMend](#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-) | Constructeur. |
| [PdfFileMend](#PdfFileMend-java.lang.String-java.lang.String-) | Constructeur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-) | <p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-) | <p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-) | <p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-) | <p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre> |
| [addImage](#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-) | <p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre> |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-) | Non implémenté. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-) | Non implémenté. |
| [addText](#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Non implémenté. |
| [close](#close--) | Ferme l'objet PdfFileMend. |
| [dispose](#dispose--) | Ferme l'objet PdfFileMend. Cette méthode est obsolète, utilisez close() à la place. |
| [getDocument](#getDocument--) | Obtient le document {@code PdfFileMend} sur lequel il travaille. |
| [getInputFile](#getInputFile--) | Obtient le fichier d'entrée. |
| [getInputStream](#getInputStream--) | Obtient le flux d'entrée. |
| [getOutputFile](#getOutputFile--) | Obtient le fichier de sortie. |
| [getOutputStream](#getOutputStream--) | Obtient le flux de sortie. |
| [getTextPositioningMode](#getTextPositioningMode--) | Obtient la stratégie de positionnement du texte. {@code PositioningMode} Le mode par défaut est Legacy. |
| [getWrapMode](#getWrapMode--) | Obtient l'algorithme de retour à la ligne. |
| [save](#save-java.io.OutputStream-) | Enregistre le document PDF dans le fichier spécifié. |
| [save](#save-java.lang.String-) | Enregistre le document PDF dans le fichier spécifié. |
| [setInputFile](#setInputFile-java.lang.String-) | Obsolète. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Définit le flux d'entrée. |
| [setOutputFile](#setOutputFile-java.lang.String-) | Définit le fichier de sortie. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Cette méthode est obsolète. Utilisez la méthode Save(outputStream) pour obtenir les résultats de la façade. |
| [setTextPositioningMode](#setTextPositioningMode-int-) | Définit la stratégie de positionnement du texte. {@code PositioningMode} Le mode par défaut est Legacy. |
| [setWordWrap](#setWordWrap-boolean-) | Définit une valeur booléenne qui indique le retour à la ligne dans les méthodes AddText. Si la valeur est vraie, le texte dans FormattedText sera renvoyé à la ligne. Par défaut, la valeur est false. |
| [setWrapMode](#setWrapMode-int-) | Définit l'algorithme de retour à la ligne. |

### PdfFileMend {#PdfFileMend--}
```
public PdfFileMend()
```

Constructeur.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-}
Constructeur.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Constructeur.

### PdfFileMend {#PdfFileMend-com.aspose.pdf.IDocument-java.lang.String-}
Constructeur.

### PdfFileMend {#PdfFileMend-java.io.InputStream-java.io.OutputStream-}
Constructeur.

### PdfFileMend {#PdfFileMend-com.aspose.ms.System.IO.Stream-com.aspose.ms.System.IO.Stream-}
Constructeur.

### PdfFileMend {#PdfFileMend-java.lang.String-java.lang.String-}
Constructeur.

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-}
<p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg") mendor.addImage(stream, new int[]{1, 2}, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-}
<p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.io.InputStream-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); InputStream stream = new FileInputStream("picture.jpg")) mendor.addImage(stream, 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-}
<p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int:A-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Ajoute une image aux pages spécifiées du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-}
<p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend("example.pdf", "out_example.pdf"); mendor.addImage("picture.jpg", 1, 10, 10, 100, 100); mendor.close(); </pre>

### addImage {#addImage-java.lang.String-int-float-float-float-float-com.aspose.pdf.CompositingParameters-}
<p> Ajoute une image à la page spécifiée du document PDF aux coordonnées spécifiées. </p> <hr> <pre> PdfFileMend mendor = new PdfFileMend(\"example.pdf\", \"out_example.pdf\"); mendor.addImage(\"picture.jpg\", 1, 10, 10, 100, 100, new CompositingParameters(BlendMode.Multiply)); mendor.close(); </pre>

### addText {#addText-com.aspose.pdf.facades.FormattedText-java.lang.Integer:A-float-float-float-float-}
Non implémenté.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-}
Non implémenté.

### addText {#addText-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Non implémenté.

### close {#close--}
```
public void close()
```

Ferme l'objet PdfFileMend.

### dispose {#dispose--}
```
public void dispose()
```

Ferme l'objet PdfFileMend. Cette méthode est obsolète, utilisez close() à la place.

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtient le document {@code PdfFileMend} sur lequel il travaille.

**Returns:**
Objet IDocument

### getInputFile {#getInputFile--}
```
@Deprecated public String getInputFile()
```

Obtient le fichier d'entrée.

**Returns:**
valeur String

### getInputStream {#getInputStream--}
```
public InputStream getInputStream()
```

Obtient le flux d'entrée.

**Returns:**
flux d'entrée.

### getOutputFile {#getOutputFile--}
```
@Deprecated public String getOutputFile()
```

Obtient le fichier de sortie.

**Returns:**
valeur String

### getOutputStream {#getOutputStream--}
```
@Deprecated public OutputStream getOutputStream()
```

Obtient le flux de sortie.

**Returns:**
flux de sortie.

### getTextPositioningMode {#getTextPositioningMode--}
```
public int getTextPositioningMode()
```

Obtient la stratégie de positionnement du texte. {@code PositioningMode} Le mode par défaut est Legacy.

**Returns:**
Élément PositioningMode @see PositioningMode

### getWrapMode {#getWrapMode--}
```
public int getWrapMode()
```

Obtient l'algorithme de retour à la ligne.

**Returns:**
valeur WordWrapMode @see WordWrapMode

### save {#save-java.io.OutputStream-}
Enregistre le document PDF dans le fichier spécifié.

### save {#save-java.lang.String-}
Enregistre le document PDF dans le fichier spécifié.

### setInputFile {#setInputFile-java.lang.String-}
Obsolète.

### setInputStream {#setInputStream-java.io.InputStream-}
Définit le flux d'entrée.

### setOutputFile {#setOutputFile-java.lang.String-}
Définit le fichier de sortie.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
Cette méthode est obsolète. Utilisez la méthode Save(outputStream) pour obtenir les résultats de la façade.

### setTextPositioningMode {#setTextPositioningMode-int-}
```
public void setTextPositioningMode(int value)
```

Définit la stratégie de positionnement du texte. {@code PositioningMode} Le mode par défaut est Legacy.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément PositioningMode @see PositioningMode |

### setWordWrap {#setWordWrap-boolean-}
```
public void setWordWrap(boolean value)
```

Définit une valeur booléenne qui indique le retour à la ligne dans les méthodes AddText. Si la valeur est vraie, le texte dans FormattedText sera renvoyé à la ligne. Par défaut, la valeur est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setWrapMode {#setWrapMode-int-}
```
public void setWrapMode(int value)
```

Définit l'algorithme de retour à la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément WordWrapMode @see WordWrapMode |
