---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc."
type: docs
weight: 410
url: /fr/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implémente les opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | Constructeur PdfFileEditor. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentages de la taille initiale de la page. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentages de la taille initiale de la page. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Ajoute des sauts de page dans les pages du document. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Ajoute des pages, qui sont choisies à partir d'un tableau de documents dans portStreams. Le document résultant inclut firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Ajoute des pages, qui sont choisies à partir des documents portFiles. Le document résultant inclut firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatène les documents. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Concatène les fichiers </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les emplacements vides avec des pages blanches. par ex. : le document1 possède 5 pages : p1, p2, p3, p4, p5. le document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, pagevide, p5, pagevide. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Concatène deux fichiers. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Concatène les fichiers en un seul fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Concatène deux fichiers. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les emplacements vides avec des pages blanches. par ex. : le document1 possède 5 pages : p1, p2, p3, p4, p5. le document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, pagevide, p5, pagevide. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Extrait les pages spécifiées par un tableau de numéros, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Extrait les pages du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Extrait les pages spécifiées par un tableau de numéros, puis les enregistre dans un nouveau fichier PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Extrait les pages du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Si défini sur true, des exceptions sont levées en cas d'erreur. Sinon, les exceptions ne sont pas levées et les méthodes renvoient false en cas d'échec. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Si défini sur true, les flux sont fermés après l'opération. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpServletResponse. Valeur possible : inline / attachment. Valeur par défaut : inline. |
| [getConversionLog](#getConversionLog--) | Obtient le journal du processus de conversion. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Si true, la structure logique du fichier est copiée lors de la concaténation. |
| [getCopyOutlines](#getCopyOutlines--) | Si true, les contours seront copiés. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate(), une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [getKeepActions](#getKeepActions--) | Si true, les actions seront copiées depuis les documents source. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Si true, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe pouvant être spécifié dans la propriété UniqueSuffix. |
| [getLastException](#getLastException--) | Obtient la dernière exception survenue. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Si true, les contours dupliqués sont fusionnés. |
| [getOptimizeSize](#getOptimizeSize--) | Obtient ou définit le drapeau d'optimisation. |
| [getOwnerPassword](#getOwnerPassword--) | Obtient le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré. Cette propriété n'est pas encore implémentée. |
| [getPreserveUserRights](#getPreserveUserRights--) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [getRemoveSignatures](#getRemoveSignatures--) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. Valeur par défaut : PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtenez le format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileoutputStream(\"out.pdf\"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Insère des pages d'un autre fichier dans le fichier Pdf à une position. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert(\"file1.pdf\", 1, \"file2.pdf\", 2, 6, \"out.pdf\"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Crée un livret à partir de l'InputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crée un livret à partir du firstInputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Crée un livret à partir du fichier d'entrée vers le fichier de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Crée un livret à partir du inputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Crée un livret personnalisé à partir du firstInputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Crée un document N‑Up à partir des flux PDF multi‑entrée vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages des flux d’entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Crée un document N‑Up à partir des deux flux PDF d’entrée vers outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Crée un document N‑Up à partir du flux d’entrée et enregistre le résultat dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Crée un document N‑Up à partir du premier flux d’entrée vers le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Crée un document N‑Up à partir des fichiers PDF multi‑entrée vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages des fichiers d’entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Crée un document N‑Up à partir du firstInputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Crée un document N‑Up à partir du fichier d’entrée vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Crée un document N‑Up à partir des deux fichiers PDF d’entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une provenant du premier fichier d’entrée et une autre du deuxième fichier d’entrée. Les deux pages sont empilées horizontalement. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d’espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne le contenu des pages du document. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 200 200, //nouvelle hauteur du contenu = 300 300); // la zone restante de la page sera vide </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne le contenu des pages du document. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 60% of initial size 60, //nouvelle hauteur du contenu = 60% of initial size 60); // La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20% // Idem pour les marges supérieures et inférieures. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 60% of initial size 60, //nouvelle hauteur du contenu = 60% of initial size 60); // La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20% // Idem pour les marges supérieures et inférieures. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensionne les pages du document. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Si défini sur true, des exceptions sont levées en cas d'erreur. Sinon les exceptions ne sont pas levées et les méthodes renvoient false en cas d'échec. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Si défini sur true, les flux sont fermés après l'opération. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpServletResponse. Valeur possible : inline / attachment. Par défaut : inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Si true, la structure logique du fichier est copiée lors de la concaténation. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Si true, les contours seront copiés. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Représentation du processeur interne d'événements de progression qui fonctionne pendant la concaténation et traduit les événements de concaténation des étapes internes en code externe du client. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Si true, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [setKeepActions](#setKeepActions-boolean-) | Si true, les actions seront copiées depuis les documents source. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Si true, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe pouvant être spécifié dans la propriété UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Si true, les contours dupliqués sont fusionnés. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtient ou définit le drapeau d'optimisation. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Définit le mot de passe du propriétaire si le fichier PDF d'entrée source est chiffré. Cette propriété n'est pas encore implémentée. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. Valeur par défaut : PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Parfois, les PDF contiennent des images d'arrière‑plan (de pages ou de cellules de tableau) construites à partir de plusieurs images d'arrière‑plan en mosaïque identiques placées les unes à côté des autres. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Définit le format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Les flux ne sont PAS fermés après cette opération. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Divise le fichier PDF de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Les flux ne sont PAS fermés après cette opération sauf si CloseConcatedStreams est spécifié. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |
| [splitToPages](#splitToPages-java.lang.String-) | Divise le fichier PDF en documents d'une seule page. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

Constructeur PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont spécifiées en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentages de la taille initiale de la page. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentages de la taille initiale de la page. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Ajoute des sauts de page dans les pages du document.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Ajoute des pages, qui sont choisies à partir d'un tableau de documents dans portStreams. Le document résultant inclut firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Ajoute des pages, qui sont choisies depuis portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Ajoute des pages, qui sont choisies à partir des documents portFiles. Le document résultant inclut firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Ajoute des pages, qui sont choisies depuis portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatène les documents.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Concatène les fichiers </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les emplacements vides avec des pages blanches. par ex. : le document1 possède 5 pages : p1, p2, p3, p4, p5. le document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, pagevide, p5, pagevide. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Concatène deux fichiers. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Concatène les fichiers en un seul fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Concatène deux fichiers. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les emplacements vides avec des pages blanches. par ex. : le document1 possède 5 pages : p1, p2, p3, p4, p5. le document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, pagevide, p5, pagevide. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Extrait les pages spécifiées par un tableau de numéros, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Extrait les pages du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Extrait les pages spécifiées par un tableau de numéros, puis les enregistre dans un nouveau fichier PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Extrait les pages du fichier d'entrée, puis les enregistre dans un nouveau fichier Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Si défini sur true, des exceptions sont levées en cas d'erreur. Sinon, les exceptions ne sont pas levées et les méthodes renvoient false en cas d'échec. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
valeur booléenne @deprecated Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

**Returns:**
valeur String

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

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpServletResponse. Valeur possible : inline / attachment. Valeur par défaut : inline.

**Returns:**
Élément ContentDisposition @see ContentDisposition

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

Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted.

**Returns:**
ConcatenateCorruptedFileAction élément @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate(), une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
tableau de PdfFileEditor.CorruptedItem

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

Si true, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe pouvant être spécifié dans la propriété UniqueSuffix.

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

Obtient le mot de passe du propriétaire si le fichier Pdf source d'entrée est chiffré. Cette propriété n'est pas encore implémentée.

**Returns:**
valeur String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé.

**Returns:**
valeur booléenne

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Returns:**
valeur booléenne

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. Valeur par défaut : PdfSaveOptions.

**Returns:**
Objet SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtenez le format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc.

**Returns:**
valeur String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileoutputStream(\"out.pdf\"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Insère des pages d'un autre fichier dans le fichier Pdf à une position. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert(\"file1.pdf\", 1, \"file2.pdf\", 2, 6, \"out.pdf\"); </pre>

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
<p> Crée un livret à partir de l'InputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crée un livret à partir du firstInputStream vers l'outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Crée un livret à partir du fichier d'entrée vers le fichier de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Crée un livret à partir du inputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Crée un livret personnalisé à partir du firstInputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Crée un document N‑Up à partir des flux PDF multi‑entrée vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages des flux d’entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"input1.pdf\"); InputStream stream2 = new FileInputStream(\"input2.pdf\"); InputStream stream3 = new FileInputStream(\"input3.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Crée un document N‑Up à partir des deux flux PDF d’entrée vers outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream(\"input1.pdf\"); InputStream input2 = new FileInputStream(\"input2.pdf\"); OutputStream output = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Crée un document N‑Up à partir du flux d’entrée et enregistre le résultat dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Crée un document N‑Up à partir du premier flux d’entrée vers le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Crée un document N‑Up à partir des fichiers PDF multi‑entrée vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages des fichiers d’entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { \"input1.pdf\", \"input2.pdf\", \"input3.pdf\" }, \"output.pdf\", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Crée un document N‑Up à partir du firstInputFile vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Crée un document N‑Up à partir du fichier d’entrée vers outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input.pdf\", \"output.pdf\", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Crée un document N‑Up à partir des deux fichiers PDF d’entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une provenant du premier fichier d’entrée et une autre du deuxième fichier d’entrée. Les deux pages sont empilées horizontalement. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(\"input1.pdf\", \"input2.pdf\", \"output.pdf\"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d’espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileOutputStream(\"output.pdf\"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne le contenu des pages du document.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 200 200, //nouvelle hauteur du contenu = 300 300); // la zone restante de la page sera vide </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne le contenu des pages du document.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 60% of initial size 60, //nouvelle hauteur du contenu = 60% of initial size 60); // La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20% // Idem pour les marges supérieures et inférieures. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //redimensionner toutes les pages du document null, //nouvelle largeur du contenu = 60% of initial size 60, //nouvelle hauteur du contenu = 60% of initial size 60); // La zone restante de la page sera vide (marges de la page). La taille des marges gauche et droite est (100% - 60%) / 2 = 20% // Idem pour les marges supérieures et inférieures. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensionne les pages du document.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Si défini sur true, des exceptions sont levées en cas d'erreur. Sinon les exceptions ne sont pas levées et les méthodes renvoient false en cas d'échec. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Cette propriété est obsolète et ne peut pas être utilisée pour autoriser le lancement d'exceptions. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpServletResponse en tant que pièce jointe.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Si défini sur true, les flux sont fermés après l'opération. </p>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

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
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpServletResponse. Valeur possible : inline / attachment. Par défaut : inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion.

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

Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @see ConcatenateCorruptedFileAction |

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

Si true, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe pouvant être spécifié dans la propriété UniqueSuffix.

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
Définit le mot de passe du propriétaire si le fichier PDF d'entrée source est chiffré. Cette propriété n'est pas encore implémentée.

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
public final void setRemoveSignatures(boolean value)
```

Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpServletResponse. Valeur par défaut : PdfSaveOptions.

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
<p> Définit le format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour le champ "fieldName" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Divise du début jusqu'à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Les flux ne sont PAS fermés après cette opération.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Divise le fichier PDF de la première page jusqu'à l'emplacement spécifié et enregistre la partie avant comme un nouveau fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divise le fichier PDF en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Divise à partir de l'emplacement spécifié et enregistre la partie arrière comme un nouveau flux de fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Les flux ne sont PAS fermés après cette opération sauf si CloseConcatedStreams est spécifié.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Divise à partir de l'emplacement et enregistre la partie arrière comme un nouveau fichier. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Divise le fichier PDF en documents d'une seule page.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié.

### splitToPages {#splitToPages-java.lang.String-}
Divise le fichier PDF en documents d'une seule page.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divisez le fichier Pdf en documents d'une seule page et enregistrez-le dans le chemin spécifié.
