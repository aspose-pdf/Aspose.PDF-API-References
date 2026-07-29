---
title: "PdfExtractor"
linktitle: "PdfExtractor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour extraire les images et le texte d'un document PDF."
type: docs
weight: 400
url: /fr/java/com.aspose.pdf.facades/pdfextractor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfExtractor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfExtractor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfExtractor extends Facade
```

Classe pour extraire les images et le texte d'un document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfExtractor](#PdfExtractor--) | / * / * Lie un document Pdf pour l'édition. / * / * / * |
| [PdfExtractor](#PdfExtractor-com.aspose.pdf.IDocument-) | / * / * Lie un document Pdf pour l'édition. / * / * / * |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-) | <p> Lie le document PDF depuis un flux. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre> |
| [bindPdf](#bindPdf-java.lang.String-) | <p> Lie le fichier PDF d'entrée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre> |
| [extractAttachment](#extractAttachment--) | Extrait les pièces jointes d'un document Pdf. |
| [extractAttachment](#extractAttachment-java.lang.String-) | Extrait les pièces jointes d'un document Pdf. |
| [extractImage](#extractImage--) | <p> Extrait les images d'un fichier PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [extractMarkedContentAsImages](#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-) | <p> Obtient tous les conteneurs de contenu marqué sous forme d'images séparées. </p> <p> Chaque contenu marqué sera enregistré comme image au format png nommée avec {@code MCID_<ID number of block for the page>.png}</p> |
| [extractText](#extractText--) | <p> Extrait le texte d'un document Pdf. </p> <hr> <pre> Le premier exemple montre comment extraire tout le texte d'un fichier PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Le deuxième exemple montre comment extraire le texte de chaque page dans un seul fichier txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractText](#extractText-java.nio.charset.Charset-) | <p> Extrait le texte d'un document Pdf. </p> <hr> <pre> Le premier exemple montre comment extraire tout le texte d'un fichier PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Le deuxième exemple montre comment extraire le texte de chaque page dans un seul fichier txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [extractTextInternal](#extractTextInternal-com.aspose.pdf.TextEncodingInternal-) | Pour usage interne uniquement |
| [getAttachment](#getAttachment--) | <p> Enregistre tous les fichiers de pièces jointes dans des flux. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachment](#getAttachment-java.lang.String-) | <p> Enregistre tous les fichiers de pièces jointes dans des flux. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre> |
| [getAttachmentInfo](#getAttachmentInfo--) | Obtient la liste des pièces jointes. |
| [getAttachNames](#getAttachNames--) | <p> Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelée avant d'utiliser cette méthode. </p> <hr> <pre> L'exemple montre comment extraire les noms des pièces jointes du fichier PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre> |
| [getEndPage](#getEndPage--) | <p> Obtient la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [getExtractImageMode](#getExtractImageMode--) | <p> Définit le mode du processus d'extraction d'images. </p> <hr> La valeur par défaut est ExtractImageMode.DefinedInResources qui extrait toutes les images définies dans les ressources. Pour extraire les images réellement affichées, le mode ExtractImageMode.ActuallyUsed doit être utilisé. |
| [getExtractTextMode](#getExtractTextMode--) | <p> Obtient le mode du résultat d'extraction de texte. </p> <hr> <pre> L'exemple montre l'utilisation de la propriété {@code ExtractTextMode} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Valeur : 0 est le mode texte pur et 1 est le mode d'ordre brut. La valeur par défaut est 0.</p> |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Récupère l'image suivante du fichier PDF et la stocke dans le flux. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Récupère l'image suivante du fichier PDF et la stocke dans le flux avec le format d'image spécifié. |
| [getNextImage](#getNextImage-java.lang.String-) | <p> Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | Récupère l'image suivante du document PDF avec le format d'image spécifié. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. |
| [getNextPageText](#getNextPageText-java.io.OutputStream-) | <p> Enregistre le texte d'une page dans le flux. </p> <hr> <pre> L'exemple montre l'utilisation de la méthode {@code GetNextPageText} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre> |
| [getNextPageText](#getNextPageText-java.lang.String-) | <p> Enregistre le texte d'une page dans un fichier. </p> <hr> <pre> L'exemple montre l'utilisation de la méthode GetNextPageText dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [getPassword](#getPassword--) | Obtient le mot de passe du fichier d'entrée. |
| [getResolution](#getResolution--) | Obtient la résolution des images extraites. La valeur par défaut est 150. Les images dont la résolution est supérieure sont plus nettes. Cependant, augmenter la résolution entraîne une augmentation du temps et de la mémoire nécessaires à l'extraction des images. En général, pour obtenir une image nette, il suffit de régler la résolution à 150 ou 300. |
| [getStartPage](#getStartPage--) | Objet Pdf.Engine représentant le document PDF. |
| [getText](#getText-java.io.OutputStream-) | Enregistre le texte dans le flux.voir aussi:{@code ExtractText} |
| [getText](#getText-java.io.OutputStream-boolean-) | Enregistre le texte dans le flux.voir aussi:{@code ExtractText} |
| [getText](#getText-java.lang.String-) | Enregistre le texte dans un fichier.voir aussi:{@code ExtractText} |
| [getTextSearchOptions](#getTextSearchOptions--) | Obtient les options de recherche de texte. |
| [hasNextImage](#hasNextImage--) | <p> Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre> |
| [hasNextPageText](#hasNextPageText--) | <p> Indique s'il est possible d'obtenir plus de texte ou non. </p> <hr> <pre> L'exemple montre l'utilisation de la propriété {@code HasNextPageText} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre> |
| [isBidi](#isBidi--) | Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être spécialement pris en compte car les fonctions de chaîne modifient leur comportement et traitent le texte de droite à gauche (sauf les chiffres et autres caractères non textuels). |
| [setEndPage](#setEndPage-int-) | <p> Définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre> |
| [setExtractImageMode](#setExtractImageMode-com.aspose.pdf.ExtractImageMode-) | <p> Définit le mode du processus d'extraction d'images. </p> <hr> La valeur par défaut est ExtractImageMode.DefinedInResources qui extrait toutes les images définies dans les ressources. Pour extraire les images réellement affichées, le mode ExtractImageMode.ActuallyUsed doit être utilisé. |
| [setExtractTextMode](#setExtractTextMode-int-) | <p> Définit le mode du résultat d'extraction de texte. </p> <hr> <pre> L'exemple montre l'utilisation de la propriété {@code ExtractTextMode} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Valeur : 0 correspond au mode texte pur et 1 au mode ordre brut. La valeur par défaut est 0. |
| [setPassword](#setPassword-java.lang.String-) | Définit le mot de passe du fichier d'entrée. |
| [setResolution](#setResolution-int-) | Définissez la résolution pour les images extraites. La valeur par défaut est 150. Les images dont la résolution est plus élevée sont plus nettes. Cependant, augmenter la résolution entraîne une augmentation du temps et de la mémoire nécessaires à l'extraction des images. En général, pour obtenir une image nette, il suffit de régler la résolution à 150 ou 300. |
| [setStartPage](#setStartPage-int-) | <p> Définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | Définit les options de recherche de texte. |

### PdfExtractor {#PdfExtractor--}
```
public PdfExtractor()
```

/ * / * Lie un document Pdf pour l'édition. / * / * / *

### PdfExtractor {#PdfExtractor-com.aspose.pdf.IDocument-}
/ * / * Lie un document Pdf pour l'édition. / * / * / *

### bindPdf {#bindPdf-java.io.InputStream-}
<p> Lie le document PDF depuis un flux. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); InputStream stream = new FileInputStream("sample.pdf"); ext.bindPdf(stream); </pre>

### bindPdf {#bindPdf-java.lang.String-}
<p> Lie le fichier PDF d'entrée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindPdf("sample.pdf"); </pre>

### extractAttachment {#extractAttachment--}
```
public void extractAttachment()
```

Extrait les pièces jointes d'un document Pdf.

### extractAttachment {#extractAttachment-java.lang.String-}
Extrait les pièces jointes d'un document Pdf.

### extractImage {#extractImage--}
```
public void extractImage()
```

<p> Extrait les images d'un fichier PDF. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.HasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### extractMarkedContentAsImages {#extractMarkedContentAsImages-com.aspose.pdf.Page-java.lang.String-}
<p> Obtient tous les conteneurs de contenu marqué sous forme d'images séparées. </p> <p> Chaque contenu marqué sera enregistré comme image au format png nommée avec {@code MCID_<ID number of block for the page>.png}</p>

### extractText {#extractText--}
```
public void extractText()
```

<p> Extrait le texte d'un document PDF. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Le deuxième exemple montre comment extraire le texte de chaque page dans un seul fichier txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractText {#extractText-java.nio.charset.Charset-}
<p> Extrait le texte d'un document PDF. </p> <hr> <pre> First example demonstrates how to extract all the text from PDF file. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("D:\\Text\\text.pdf"); extractor.extractText(); extractor.getText("D:\\Text\\text.txt"); </pre> <p> Le deuxième exemple montre comment extraire le texte de chaque page dans un seul fichier txt. <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### extractTextInternal {#extractTextInternal-com.aspose.pdf.TextEncodingInternal-}
Pour usage interne uniquement

### getAttachment {#getAttachment--}
```
public ByteArrayOutputStream [] getAttachment()
```

<p> Enregistre tous les fichiers de pièces jointes dans des flux. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Le tableau de flux du fichier joint dans le document PDF.

### getAttachment {#getAttachment-java.lang.String-}
<p> Enregistre tous les fichiers de pièces jointes dans des flux. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(path + "Attach.pdf"); extractor.extractAttachment(); IList names = extractor.getAttachNames(); ByteArrayOutputStream[] tempStreams = extractor.getAttachment(); for (int i=0; i<tempStreams.Length; i++) { string name = (string)names[i]; OutputStream fs = new FileOutputStream(path + name); fs.write(tempStreams[i].toByteArray()); fs.close(); } </pre>

**Returns:**
Le tableau de flux du fichier joint dans le document PDF.

### getAttachmentInfo {#getAttachmentInfo--}
```
public List < FileSpecification > getAttachmentInfo()
```

Obtient la liste des pièces jointes.

**Returns:**
Renvoie une List<FileSpecificatio>.

### getAttachNames {#getAttachNames--}
```
public List < String > getAttachNames()
```

<p> Renvoie la liste des pièces jointes dans le fichier PDF. Remarque : ExtractAttachments doit être appelée avant d'utiliser cette méthode. </p> <hr> <pre> L'exemple montre comment extraire les noms des pièces jointes du fichier PDF. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestSettings.GetInputFile("sample.pdf")); extractor.ExtractAttachment(); List attachments = extractor.getAttachNames(); for (String name : {@code (Iterable<String>)}attachments) System.out.println(name); </pre>

**Returns:**
Liste des pièces jointes

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

<p> Obtient la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Returns:**
page de fin.

### getExtractImageMode {#getExtractImageMode--}
```
public ExtractImageMode getExtractImageMode()
```

<p> Définit le mode du processus d'extraction d'images. </p> <hr> La valeur par défaut est ExtractImageMode.DefinedInResources qui extrait toutes les images définies dans les ressources. Pour extraire les images réellement affichées, le mode ExtractImageMode.ActuallyUsed doit être utilisé.

**Returns:**
Valeur ExtractImageMode @see ExtractImageMode

### getExtractTextMode {#getExtractTextMode--}
```
public int getExtractTextMode()
```

<p> Obtient le mode du résultat d'extraction de texte. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> <p> Valeur : 0 est le mode texte pur et 1 est le mode ordre brut. La valeur par défaut est 0.

**Returns:**
résultat de l'extraction de texte.

### getNextImage {#getNextImage-java.io.OutputStream-}
Récupère l'image suivante du fichier PDF et la stocke dans le flux.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Récupère l'image suivante du fichier PDF et la stocke dans le flux avec le format d'image spécifié.

### getNextImage {#getNextImage-java.lang.String-}
<p> Récupère l'image suivante du document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
Récupère l'image suivante du document PDF avec le format d'image spécifié. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode.

### getNextPageText {#getNextPageText-java.io.OutputStream-}
<p> Enregistre le texte d'une page dans le flux. </p> <hr> <pre> L'exemple montre l'utilisation de la méthode {@code GetNextPageText} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { FileInputStream fs = new FileInputStream(prefix + pageCount + suffix, FileMode.Create); extractor.getNextPageText(fs); fs.close(); pageCount++; } </pre>

### getNextPageText {#getNextPageText-java.lang.String-}
<p> Enregistre le texte d'une page dans un fichier. </p> <hr> <pre> L'exemple montre l'utilisation de la méthode GetNextPageText dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + @"Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + @"Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

### getPassword {#getPassword--}
```
public String getPassword()
```

Obtient le mot de passe du fichier d'entrée.

**Returns:**
valeur String

### getResolution {#getResolution--}
```
public int getResolution()
```

Obtient la résolution des images extraites. La valeur par défaut est 150. Les images dont la résolution est supérieure sont plus nettes. Cependant, augmenter la résolution entraîne une augmentation du temps et de la mémoire nécessaires à l'extraction des images. En général, pour obtenir une image nette, il suffit de régler la résolution à 150 ou 300.

**Returns:**
valeur int

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Objet Pdf.Engine représentant le document PDF.

**Returns:**
page de début dans la plage de pages.

### getText {#getText-java.io.OutputStream-}
Enregistre le texte dans le flux.voir aussi:{@code ExtractText}

### getText {#getText-java.io.OutputStream-boolean-}
Enregistre le texte dans le flux.voir aussi:{@code ExtractText}

### getText {#getText-java.lang.String-}
Enregistre le texte dans un fichier.voir aussi:{@code ExtractText}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

Obtient les options de recherche de texte.

**Returns:**
options de recherche de texte.

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

<p> Vérifie si d'autres images sont accessibles dans le document PDF. Remarque : ExtractImage doit être appelé avant d'utiliser cette méthode. </p> <hr> <pre> PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf("sample.pdf"); extractor.extractImage(); int i = 1; while (extractor.hasNextImage()) { extractor.getNextImage("image-" + i +".pdf"); } </pre>

**Returns:**
Vrai si plus d'images sont accessibles

### hasNextPageText {#hasNextPageText--}
```
public boolean hasNextPageText()
```

<p> Indique s'il est possible d'obtenir plus de texte ou non. </p> <hr> <pre> L'exemple montre l'utilisation de la propriété {@code HasNextPageText} dans un scénario d'extraction de texte. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(TestPath + "Aspose.Pdf.Kit.Pdf"); extractor.extractText(Encoding.Unicode); String prefix = TestPath + "Aspose.Pdf.Kit"; String suffix = ".txt"; int pageCount = 1; while (extractor.hasNextPageText()) { extractor.getNextPageText(prefix + pageCount + suffix); pageCount++; } </pre>

**Returns:**
Peut obtenir plus de texte ou non, vrai signifie oui, faux signifie non.

### isBidi {#isBidi--}
```
public boolean isBidi()
```

Est vrai lorsque le texte contient des symboles hébreux ou arabes. Ce cas doit être spécialement pris en compte car les fonctions de chaîne modifient leur comportement et traitent le texte de droite à gauche (sauf les chiffres et autres caractères non textuels).

**Returns:**
valeur booléenne

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

<p> Définit la page de fin dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(3); ext.extractText(); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | page de fin. |

### setExtractImageMode {#setExtractImageMode-com.aspose.pdf.ExtractImageMode-}
<p> Définit le mode du processus d'extraction d'images. </p> <hr> La valeur par défaut est ExtractImageMode.DefinedInResources qui extrait toutes les images définies dans les ressources. Pour extraire les images réellement affichées, le mode ExtractImageMode.ActuallyUsed doit être utilisé.

### setExtractTextMode {#setExtractTextMode-int-}
```
public void setExtractTextMode(int value)
```

<p> Définit le mode du résultat d'extraction de texte. </p> <hr> <pre> The example demonstrates the {@code ExtractTextMode} property usage in text extraction scenario. PdfExtractor extractor = new PdfExtractor(); extractor.bindPdf(@"D:\\Text\\text.pdf"); extractor.setExtractTextMode(1); extractor.extractText(); extractor.getText(@"D:\\Text\\text.txt"); </pre> Valeur : 0 est le mode texte pur et 1 est le mode ordre brut. La valeur par défaut est 0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | résultat de l'extraction de texte. |

### setPassword {#setPassword-java.lang.String-}
Définit le mot de passe du fichier d'entrée.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Définissez la résolution pour les images extraites. La valeur par défaut est 150. Les images dont la résolution est plus élevée sont plus nettes. Cependant, augmenter la résolution entraîne une augmentation du temps et de la mémoire nécessaires à l'extraction des images. En général, pour obtenir une image nette, il suffit de régler la résolution à 150 ou 300.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

<p> Définit la page de début dans la plage de pages où l'opération d'extraction sera effectuée. </p> <hr> <pre> PdfExtractor ext = new PdfExtractor(); ext.bindBdf("sample.pdf"); ext.setStartPage(2); ext.setEndPage(5); ext.extractText(); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | page de début dans la plage de pages. |

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
Définit les options de recherche de texte.
