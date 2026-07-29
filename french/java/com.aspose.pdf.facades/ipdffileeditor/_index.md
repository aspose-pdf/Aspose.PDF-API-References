---
title: "IPdfFileEditor"
linktitle: "IPdfFileEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc."
type: docs
weight: 290
url: /fr/java/com.aspose.pdf.facades/ipdffileeditor/
---
```
public interface IPdfFileEditor
```

Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc.

## Méthodes

| Méthode | Description |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Ajoute des pages, qui sont choisies parmi un tableau de documents dans portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Ajoute des pages, qui sont choisies parmi les documents portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatène les documents. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatène les fichiers |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatène deux fichiers. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatène des fichiers en un seul fichier. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatène deux fichiers. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | est Autoriser les Exceptions de Concatenation |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si défini sur true, les flux sont fermés après l'opération. |
| [getContentDisposition](#getContentDisposition--) | Obtient comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtient le journal du processus de conversion. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés. |
| [getLastException](#getLastException--) | Obtient la dernière exception survenue. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si true, les contours dupliqués sont fusionnés. |
| [getOwnerPassword](#getOwnerPassword--) | Obtient le mot de passe du propriétaire si le fichier PDF source d'entrée est chiffré. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtient le format du suffixe ajouté au nom de champ pour le rendre unique lorsque les formulaires sont concaténés. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Insère des pages d'un autre fichier dans le fichier PDF à une position donnée. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crée un livret à partir de l'InputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crée un livret à partir du firstInputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crée un livret à partir du inputFile vers l'outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crée un document N-Up à partir de plusieurs flux PDF d'entrée vers l'outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crée un document N-Up à partir de deux flux PDF d'entrée vers l'outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crée un document N-Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crée un document N-Up à partir du firstInputFile vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crée un document N-Up à partir du fichier d'entrée vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crée un document N-Up à partir de deux fichiers PDF d'entrée vers l'outputFile. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Si défini sur true, des exceptions sont levées si une erreur s'est produite. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Si défini sur true, les flux sont fermés après l'opération. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format du fichier PDF. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si true, les contours dupliqués sont fusionnés. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Définit le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Définit le format du suffixe ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |
| [splitToPages](#splitToPages-java.lang.String-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Ajoute des pages, qui sont choisies parmi un tableau de documents dans portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Ajoute des pages, qui sont choisies parmi les documents portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatène les documents.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatène les fichiers

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatène deux fichiers.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatène des fichiers en un seul fichier.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatène deux fichiers.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
boolean getAllowConcatenateExceptions()
```

est Autoriser les Exceptions de Concatenation

**Returns:**
valeur booléenne

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

**Returns:**
valeur de chaîne

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
boolean getCloseConcatenatedStreams()
```

Si défini sur true, les flux sont fermés après l'opération.

**Returns:**
valeur booléenne

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtient comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse.

**Returns:**
Élément ContentDisposition

### getConversionLog {#getConversionLog--}
```
String getConversionLog()
```

Obtient le journal du processus de conversion.

**Returns:**
valeur de chaîne

### getCorruptedFileAction {#getCorruptedFileAction--}
```
int getCorruptedFileAction()
```

Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus.

**Returns:**
Élément ConcatenateCorruptedFileAction

### getIncrementalUpdates {#getIncrementalUpdates--}
```
boolean getIncrementalUpdates()
```

Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation.

**Returns:**
valeur booléenne

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
boolean getKeepFieldsUnique()
```

Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés.

**Returns:**
valeur booléenne

### getLastException {#getLastException--}
```
Exception getLastException()
```

Obtient la dernière exception survenue.

**Returns:**
java.lang.Exception objet

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
boolean getMergeDuplicateLayers()
```

Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true.

**Returns:**
valeur booléenne

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
boolean getMergeDuplicateOutlines()
```

Si true, les contours dupliqués sont fusionnés.

**Returns:**
valeur booléenne

### getOwnerPassword {#getOwnerPassword--}
```
String getOwnerPassword()
```

Obtient le mot de passe du propriétaire si le fichier PDF source d'entrée est chiffré.

**Returns:**
valeur de chaîne

### getPreserveUserRights {#getPreserveUserRights--}
```
boolean getPreserveUserRights()
```

Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé.

**Returns:**
valeur booléenne

### getRemoveSignatures {#getRemoveSignatures--}
```
boolean getRemoveSignatures()
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Returns:**
valeur booléenne

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse.

**Returns:**
Objet SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
String getUniqueSuffix()
```

Obtient le format du suffixe ajouté au nom de champ pour le rendre unique lorsque les formulaires sont concaténés.

**Returns:**
valeur de chaîne

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Insère des pages d'un autre fichier dans le fichier PDF à une position donnée.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crée un livret à partir de l'InputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crée un livret personnalisé à partir du firstInputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crée un livret à partir du firstInputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
Crée un livret à partir du fichier d'entrée vers le fichier de sortie.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
Crée un livret personnalisé à partir du firstInputFile vers l'outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
Crée un livret à partir du inputFile vers l'outputFile.

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
Crée un livret personnalisé à partir du firstInputFile vers l'outputFile.

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
Crée un document N-Up à partir de plusieurs flux PDF d'entrée vers l'outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Crée un document N-Up à partir de deux flux PDF d'entrée vers l'outputStream.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crée un document N-Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crée un document N-Up à partir du firstInputFile vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crée un document N-Up à partir du fichier d'entrée vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crée un document N-Up à partir de deux fichiers PDF d'entrée vers l'outputFile.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensionne le contenu des pages du document.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
void setAllowConcatenateExceptions(boolean value)
```

Si défini sur true, des exceptions sont levées si une erreur s'est produite.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
void setCloseConcatenatedStreams(boolean value)
```

Si défini sur true, les flux sont fermés après l'opération.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format du fichier PDF.

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
void setCorruptedFileAction(int value)
```

Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ConcatenateCorruptedFileAction |

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
void setIncrementalUpdates(boolean value)
```

Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
void setKeepFieldsUnique(boolean value)
```

Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
void setMergeDuplicateLayers(boolean value)
```

Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
void setMergeDuplicateOutlines(boolean value)
```

Si true, les contours dupliqués sont fusionnés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Définit le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
void setPreserveUserRights(boolean value)
```

Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
void setRemoveSignatures(boolean value)
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse.

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Définit le format du suffixe ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier.

### splitToPages {#splitToPages-java.io.InputStream-}
Divise le fichier PDF en documents d'une seule page.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié.

### splitToPages {#splitToPages-java.lang.String-}
Divise le fichier PDF en documents d'une seule page.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié.
