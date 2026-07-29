---
title: "PdfFileEditorWeb"
linktitle: "PdfFileEditorWeb"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe PdfFileEditorWeb qui implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc."
type: docs
weight: 480
url: /fr/java/com.aspose.pdf.facades/pdffileeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditorWeb

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditorWeb extends Object implements IPdfFileEditor
```

Représente la classe PdfFileEditorWeb qui implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileEditorWeb](#PdfFileEditorWeb--) | Constructeur de PdfFileEditorWeb. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | Redimensionne le contenu des pages et ajoute les marges spécifiées. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-) | Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | Ajoute des pages, qui sont choisies parmi un tableau de documents dans portStreams. |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-) | Ajoute des documents au document source et enregistre le résultat dans l'objet HttpServletResponse. |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | Ajoute des pages, qui sont choisies parmi les documents portFiles. |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatène les documents. |
| [concatenate](#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-) | Concatène les fichiers et stocke le résultat dans l'objet HttpServletResponse. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | Concatène les fichiers |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Concatène deux fichiers. |
| [concatenate](#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-) | Concatène les fichiers et enregistre le reslt dans l'objet HttpResposnse. |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | Concatène des fichiers en un seul fichier. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | Concatène deux fichiers. |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpServletResponse. |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf. |
| [delete](#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpServletResponse. |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf. |
| [extract](#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpServletResponse. |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier Pdf. |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf. |
| [extract](#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpServletResponse. |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier PDF. |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf. |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | Obsolète. Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si défini sur true, les flux sont fermés après l'opération. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
| [getContentDisposition](#getContentDisposition--) | Obtient comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse. |
| [getConversionLog](#getConversionLog--) | Obtient le journal du processus de conversion. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Si true, la structure logique du fichier est copiée lors de la concaténation. |
| [getCopyOutlines](#getCopyOutlines--) | Si true, les contours seront copiés. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus. |
| [getCorruptedItems](#getCorruptedItems--) | Tableau des problèmes rencontrés lors de la concaténation. |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [getKeepActions](#getKeepActions--) | Si true, les actions seront copiées depuis les documents source. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés. |
| [getLastException](#getLastException--) | Obtient la dernière exception survenue. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si true, les contours dupliqués sont fusionnés. |
| [getOptimizeSize](#getOptimizeSize--) | Obtient ou définit le drapeau d'optimisation. |
| [getOwnerPassword](#getOwnerPassword--) | Obtient le mot de passe du propriétaire si le fichier PDF source d'entrée est chiffré. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtient le format du suffixe ajouté au nom de champ pour le rendre unique lorsque les formulaires sont concaténés. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-) | Insère le document dans un autre document et stocke le résultat dans l'objet réponse. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-) | Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpServletResponse. |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | Insère des pages d'un autre fichier dans le fichier PDF à une position donnée. |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | Crée un livret à partir de l'InputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | Crée un livret à partir du firstInputStream vers l'outputStream. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crée un livret à partir du fichier source et stocke le résultat dans HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crée un livret à partir d'un fichier PDF et le stocke dans HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-) | Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpServletResponse. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | Crée un livret à partir du inputFile vers l'outputFile. |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | Crée un document N-Up à partir de plusieurs flux PDF d'entrée vers l'outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | Crée un document N-Up à partir de deux flux PDF d'entrée vers l'outputStream. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-) | Crée un document N-up et stocke le résultat dans HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crée un document N-up et stocke le résultat dans l'objet HttpServletResponse. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie. |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | Crée un document N-Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-) | Crée un document N-up et stocke le résultat dans HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-) | Crée un document N-up et stocke le résultat dans l'objet HttpServletResponse. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | Crée un document N-Up à partir du firstInputFile vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | Crée un document N-Up à partir du fichier d'entrée vers l'outputFile. |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | Crée un document N-Up à partir de deux fichiers PDF d'entrée vers l'outputFile. |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne le contenu des pages du document. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | Redimensionne le contenu des pages du document. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | Obsolète. Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | Si défini sur true, les flux sont fermés après l'opération. |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format du fichier PDF. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Si true, la structure logique du fichier est copiée lors de la concaténation. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Si true, les contours seront copiés. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [setKeepActions](#setKeepActions-boolean-) | Si true, les actions seront copiées depuis les documents source. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si true, les contours dupliqués sont fusionnés. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtient ou définit le drapeau d'optimisation. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Définit le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | Définit le format du suffixe ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divise le document du début jusqu'à l'emplacement spécifié et stocke le résultat dans l'objet HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divise le document de la première page jusqu'à l'emplacement et enregistre le résultat dans les objets HttpServletResponse. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier. |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-) | Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier. |
| [splitToEnd](#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-) | Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpServletResponse. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier. |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |
| [splitToPages](#splitToPages-java.lang.String-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |

### PdfFileEditorWeb {#PdfFileEditorWeb--}
```
public PdfFileEditorWeb()
```

Constructeur de PdfFileEditorWeb.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
Redimensionne le contenu des pages et ajoute les marges spécifiées.

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-javax.servlet.http.HttpServletResponse-}
Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
Ajoute des pages, qui sont choisies parmi un tableau de documents dans portStreams.

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream.

### append {#append-java.lang.String-java.lang.String:A-int-int-javax.servlet.http.HttpServletResponse-}
Ajoute des documents au document source et enregistre le résultat dans l'objet HttpServletResponse.

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
Ajoute des pages, qui sont choisies parmi les documents portFiles.

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile.

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatène les documents.

### concatenate {#concatenate-java.io.InputStream:A-javax.servlet.http.HttpServletResponse-}
Concatène les fichiers et stocke le résultat dans l'objet HttpServletResponse.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
Concatène les fichiers

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches.

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
Concatène deux fichiers.

### concatenate {#concatenate-java.lang.String:A-javax.servlet.http.HttpServletResponse-}
Concatène les fichiers et enregistre le reslt dans l'objet HttpResposnse.

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
Concatène des fichiers en un seul fichier.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
Concatène deux fichiers.

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches.

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpServletResponse.

### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf.

### delete {#delete-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpServletResponse.

### delete {#delete-java.lang.String-int:A-java.lang.String-}
Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, enregistre-le comme un nouveau fichier Pdf.

### extract {#extract-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpServletResponse.

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier Pdf.

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf.

### extract {#extract-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpServletResponse.

### extract {#extract-java.lang.String-int:A-java.lang.String-}
Extrait les pages spécifiées par un tableau de numéros, les enregistre comme un nouveau fichier PDF.

### extract {#extract-java.lang.String-int-int-java.lang.String-}
Extrait les pages du fichier d'entrée, les enregistre comme un nouveau fichier Pdf.

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

Obsolète. Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions.

**Returns:**
Valeur booléenne

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

**Returns:**
valeur de chaîne

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Si défini sur true, les flux sont fermés après l'opération.

**Returns:**
valeur booléenne

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true.

**Returns:**
valeur int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtient comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse.

**Returns:**
Élément ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Obtient le journal du processus de conversion.

**Returns:**
valeur de chaîne

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Si true, la structure logique du fichier est copiée lors de la concaténation.

**Returns:**
valeur booléenne

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Si true, les contours seront copiés.

**Returns:**
valeur booléenne

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus.

**Returns:**
Élément ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

Tableau des problèmes rencontrés lors de la concaténation.

**Returns:**
Tableau PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client.

**Returns:**
ConcatenationProgressHandler instance

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation.

**Returns:**
valeur booléenne

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Si true, les actions seront copiées depuis les documents source.

**Returns:**
valeur booléenne

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés.

**Returns:**
valeur booléenne

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Obtient la dernière exception survenue.

**Returns:**
java.lang.Exception objet

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true.

**Returns:**
valeur booléenne

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Si true, les contours dupliqués sont fusionnés.

**Returns:**
valeur booléenne

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtient ou définit le drapeau d'optimisation.

**Returns:**
valeur booléenne

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Obtient le mot de passe du propriétaire si le fichier PDF source d'entrée est chiffré.

**Returns:**
Objet String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé.

**Returns:**
valeur booléenne

### getRemoveSignatures {#getRemoveSignatures--}
```
public boolean getRemoveSignatures()
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Returns:**
valeur booléenne

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse.

**Returns:**
Objet SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtient le format du suffixe ajouté au nom de champ pour le rendre unique lorsque les formulaires sont concaténés.

**Returns:**
Objet String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-javax.servlet.http.HttpServletResponse-}
Insère le document dans un autre document et stocke le résultat dans l'objet réponse.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-javax.servlet.http.HttpServletResponse-}
Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpServletResponse.

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
Insère des pages d'un autre fichier dans le fichier PDF d'entrée.

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
Insère des pages d'un autre fichier dans le fichier PDF à une position donnée.

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres.

**Returns:**
valeur booléenne

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles.

**Returns:**
valeur booléenne

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
Crée un livret à partir de l'InputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
Crée un livret personnalisé à partir du firstInputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
Crée un livret à partir du firstInputStream vers l'outputStream.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crée un livret à partir du fichier source et stocke le résultat dans HttpServletResponse.

### makeBooklet {#makeBooklet-java.io.InputStream-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crée un livret à partir d'un fichier PDF et le stocke dans HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpServletResponse.

### makeBooklet {#makeBooklet-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-javax.servlet.http.HttpServletResponse-}
Crée un livret à partir du fichier source et stocke le résultat dans les objets HttpServletResponse.

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

### makeNUp {#makeNUp-java.io.InputStream-int-int-javax.servlet.http.HttpServletResponse-}
Crée un document N-up et stocke le résultat dans HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crée un document N-up et stocke le résultat dans l'objet HttpServletResponse.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie.

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie.

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
Crée un document N-Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-int-int-javax.servlet.http.HttpServletResponse-}
Crée un document N-up et stocke le résultat dans HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-int-int-com.aspose.pdf.PageSize-javax.servlet.http.HttpServletResponse-}
Crée un document N-up et stocke le résultat dans l'objet HttpServletResponse.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
Crée un document N-Up à partir du firstInputFile vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
Crée un document N-Up à partir du fichier d'entrée vers l'outputFile.

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
Crée un document N-Up à partir de deux fichiers PDF d'entrée vers l'outputFile.

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-com.aspose.ms.System.IO.Stream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-javax.servlet.http.HttpServletResponse-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne le contenu des pages du document.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
Redimensionne le contenu des pages du document.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

Obsolète. Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur booléenne |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

Si défini sur true, les flux sont fermés après l'opération.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpServletResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format du fichier PDF.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Si true, la structure logique du fichier est copiée lors de la concaténation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Si true, les contours seront copiés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Cette propriété définit le comportement lorsqu'un fichier corrompu est rencontré lors de la concaténation du processus.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Si true, les actions seront copiées depuis les documents source.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Si vrai, les noms de champs seront rendus uniques lorsque les formulaires sont concaténés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Si true, les contours dupliqués sont fusionnés.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtient ou définit le drapeau d'optimisation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Définit le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public void setRemoveSignatures(boolean value)
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valeur booléenne |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
Définit le format du suffixe ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés.

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divise le document du début jusqu'à l'emplacement spécifié et stocke le résultat dans l'objet HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie.

### splitFromFirst {#splitFromFirst-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divise le document de la première page jusqu'à l'emplacement et enregistre le résultat dans les objets HttpServletResponse.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier.

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToEnd {#splitToEnd-java.io.InputStream-int-javax.servlet.http.HttpServletResponse-}
Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpServletResponse.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier.

### splitToEnd {#splitToEnd-java.lang.String-int-javax.servlet.http.HttpServletResponse-}
Divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpServletResponse.

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
