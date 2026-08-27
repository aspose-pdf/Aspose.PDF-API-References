---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Interface pour ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF."
type: docs
weight: 320
url: /fr/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

Interface pour ajouter des tampons (filigrane ou arrière‑plan) aux fichiers PDF.

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

## Méthodes

| Méthode | Description |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | Ajoute un pied de page aux pages du document. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | Ajoute un pied de page aux pages du document. |
| [addFooter](#addFooter-java.io.InputStream-float-) | Ajoute une image en pied de page de la page. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | Ajoute une image en pied de page de la page. |
| [addFooter](#addFooter-java.lang.String-float-) | Ajoute une image en pied de page aux pages du document. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | Ajoute une image en pied de page des pages. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | Ajoute un en-tête à la page. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | Ajoute un en-tête aux pages du fichier. |
| [addHeader](#addHeader-java.io.InputStream-float-) | Ajoute une image en en-tête sur les pages. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | Ajoute une image en haut de la page. |
| [addHeader](#addHeader-java.lang.String-float-) | Ajoute une image en en-tête aux pages du fichier. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | Ajoute une image en en-tête sur les pages. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | Ajoute le numéro de page à la page. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | Ajoute le numéro de page à la position spécifiée sur la page. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | Ajoute le numéro de page aux pages. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | Ajoute le numéro de page aux pages du document. |
| [addPageNumber](#addPageNumber-java.lang.String-) | Ajoute le numéro de page au fichier. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | Ajoute le numéro de page à la position spécifiée sur la page. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | Ajoute le numéro de page aux pages. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | Ajoute le numéro de page aux pages du document. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | Ajoute un tampon au fichier. |
| [close](#close--) | Ferme les fichiers ouverts et enregistre les modifications. |
| [dispose](#dispose--) | Obsolète. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [getDocument](#getDocument--) | Obtient le document sur lequel PdfFileStamp travaille. |
| [getInputFile](#getInputFile--) | Obtient le nom et le chemin du fichier d'entrée. |
| [getInputStream](#getInputStream--) | Obtient le flux d'entrée. |
| [getKeepSecurity](#getKeepSecurity--) | Conserve la sécurité si vrai. |
| [getOutputFile](#getOutputFile--) | Obtient le nom et le chemin du fichier de sortie. |
| [getOutputStream](#getOutputStream--) | Obtient le flux de sortie. |
| [getPageHeight](#getPageHeight--) | Obtient la hauteur de la première page du fichier source. |
| [getPageNumberRotation](#getPageNumberRotation--) | Obtient la rotation du numéro de page. |
| [getPageWidth](#getPageWidth--) | Obtient la largeur de la première page du fichier d'entrée. |
| [getSaveOptions](#getSaveOptions--) | Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | Obtient ou définit le numéro de départ pour la première page du fichier d'entrée. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format du fichier PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | Définit le nom et le chemin du fichier d'entrée. |
| [setInputStream](#setInputStream-java.io.InputStream-) | Définit le flux d'entrée. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | Définir Conserver la sécurité |
| [setOutputFile](#setOutputFile-java.lang.String-) | Définit le nom et le chemin du fichier de sortie. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | Définit ou définit le flux de sortie. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | Définit la rotation du numéro de page. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | Définit le numéro de départ pour la première page du fichier d'entrée. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

Position en bas à gauche.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

Position en bas au centre.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

Position en bas à droite.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

Position à gauche.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

Position à droite.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

Position en haut à gauche.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

Position au milieu supérieur.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

Position en haut à droite.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
Ajoute un pied de page aux pages du document.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
Ajoute un pied de page aux pages du document.

### addFooter {#addFooter-java.io.InputStream-float-}
Ajoute une image en pied de page de la page.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
Ajoute une image en pied de page de la page.

### addFooter {#addFooter-java.lang.String-float-}
Ajoute une image en pied de page aux pages du document.

### addFooter {#addFooter-java.lang.String-float-float-float-}
Ajoute une image en pied de page des pages.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
Ajoute un en-tête à la page.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
Ajoute un en-tête aux pages du fichier.

### addHeader {#addHeader-java.io.InputStream-float-}
Ajoute une image en en-tête sur les pages.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
Ajoute une image en haut de la page.

### addHeader {#addHeader-java.lang.String-float-}
Ajoute une image en en-tête aux pages du fichier.

### addHeader {#addHeader-java.lang.String-float-float-float-}
Ajoute une image en en-tête sur les pages.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
Ajoute le numéro de page à la page.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
Ajoute le numéro de page à la position spécifiée sur la page.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
Ajoute le numéro de page aux pages.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
Ajoute le numéro de page aux pages du document.

### addPageNumber {#addPageNumber-java.lang.String-}
Ajoute le numéro de page au fichier.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
Ajoute le numéro de page à la position spécifiée sur la page.

### addPageNumber {#addPageNumber-java.lang.String-int-}
Ajoute le numéro de page aux pages.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
Ajoute le numéro de page aux pages du document.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
Ajoute un tampon au fichier.

### close {#close--}
```
void close()
```

Ferme les fichiers ouverts et enregistre les modifications.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

Obsolète.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
valeur String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

**Returns:**
Élément ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtient le document sur lequel PdfFileStamp travaille.

**Returns:**
Objet IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

Obtient le nom et le chemin du fichier d'entrée.

**Returns:**
Objet String

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

Obtient le flux d'entrée.

**Returns:**
Objet InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

Conserve la sécurité si vrai.

**Returns:**
valeur booléenne

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

Obtient le nom et le chemin du fichier de sortie.

**Returns:**
Objet String

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

Obtient le flux de sortie.

**Returns:**
Objet OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

Obtient la hauteur de la première page du fichier source.

**Returns:**
Valeur flottante

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

Obtient la rotation du numéro de page.

**Returns:**
Valeur flottante

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

Obtient la largeur de la première page du fichier d'entrée.

**Returns:**
Valeur flottante

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

**Returns:**
Objet SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

Obtient ou définit le numéro de départ pour la première page du fichier d'entrée.

**Returns:**
valeur int

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format du fichier PDF.

### setInputFile {#setInputFile-java.lang.String-}
Définit le nom et le chemin du fichier d'entrée.

### setInputStream {#setInputStream-java.io.InputStream-}
Définit le flux d'entrée.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

Définir Conserver la sécurité

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
void setPageNumberRotation(float value)
```

Définit la rotation du numéro de page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

Définit le numéro de départ pour la première page du fichier d'entrée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |
