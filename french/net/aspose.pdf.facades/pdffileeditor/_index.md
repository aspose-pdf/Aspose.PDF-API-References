---
title: PdfFileEditor
second_title: Référence de l'API Aspose.PDF pour .NET
description: Met en œuvre des opérations avec un fichier PDF  concaténation fractionnement extraction de pages création de livret etc.
type: docs
weight: 2470
url: /fr/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Met en œuvre des opérations avec un fichier PDF : concaténation, fractionnement, extraction de pages, création de livret, etc.

```csharp
public sealed class PdfFileEditor
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [PdfFileEditor](pdffileeditor)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [AttachmentName](../../aspose.pdf.facades/pdffileeditor/attachmentname) { get; set; } | Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams) { get; set; } | Si la valeur est true, les flux sont fermés après l'opération. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize) { get; set; } | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée lors de la concaténation lorsque UseDiskBuffer est défini sur true. |
| [ContentDisposition](../../aspose.pdf.facades/pdffileeditor/contentdisposition) { get; set; } | Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. Valeur possible : en ligne / pièce jointe. Par défaut : en ligne. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog) { get; } | Obtient le journal du processus de conversion. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto) { set; } | Définit le format de fichier PDF. Le fichier de résultat sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure) { get; set; } | Si vrai, la structure logique du fichier est copiée lors de la concaténation. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines) { get; set; } | Si vrai, les contours seront copiés. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction) { get; set; } | Cette propriété définit le comportement lors de la concaténation d'un processus avec un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems) { get; } | Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu transmis à la fonction Concatenate() , une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates) { get; set; } | Si vrai, les mises à jour incrémentielles sont effectuées lors de la concaténation. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions) { get; set; } | Si vrai, les actions seront copiées à partir des documents source. Valeur par défaut : true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique) { get; set; } | Si vrai, les noms de champ seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champ, un modèle de suffixe peut être spécifié dans la propriété UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception) { get; } | Obtient la dernière exception survenue. Peut être utilisé pour vérifier la raison de l'échec. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers) { get; set; } | Le contenu facultatif des documents concaténés avec des noms égaux sera fusionné en une seule couche dans le document résultant si cette propriété est vraie. Sinon, les calques portant le même nom seront enregistrés en tant que calques différents dans le document résultant. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines) { get; set; } | Si vrai, les contours en double sont fusionnés. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize) { get; set; } | Obtient ou définit l'indicateur d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si cet indicateur est activé. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des besoins en mémoire plus importants. Valeur par défaut : false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword) { get; set; } | Définit le mot de passe du propriétaire si le fichier PDF d'entrée source est crypté. Cette propriété n'est pas encore implémentée. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights) { get; set; } | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. Les droits d'utilisateur de tous les autres documents sont ignorés. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures) { get; set; } | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront); sinon, vous pouvez obtenir des signatures invalides. |
| [SaveOptions](../../aspose.pdf.facades/pdffileeditor/saveoptions) { get; set; } | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix) { get; set; } | Format du suffixe qui est ajouté au nom du champ pour le rendre unique lorsque les formulaires sont concaténés. Cette chaîne doit contenir une sous-chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = "ABC%NUM%" alors pour les noms de champ "fieldName" seront : fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer) { get; set; } | Si cette option est utilisée, le document de destination sera enregistré périodiquement sur le disque et une concaténation supplémentaire lui sera appliquée sous forme de mises à jour incrémentielles. |

## Méthodes

| Nom | La description |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins#addmargins_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentage de la taille de la page initiale. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct#addmarginspct_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentage de la taille de la page initiale. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak)(Document, Document, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_1)(Stream, Stream, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak#addpagebreak_2)(string, string, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append)(Stream, Stream, int, int, Stream) | Ajoute des pages, qui sont choisies dans portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_2)(Stream, Stream[], int, int, HttpResponse) | Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_1)(Stream, Stream[], int, int, Stream) | Ajoute des pages, qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_3)(string, string, int, int, string) | Ajoute les pages, qui sont choisies dans portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_5)(string, string[], int, int, HttpResponse) | Ajoute des documents au document source et enregistre le résultat dans l'objet HttpResponse. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append#append_4)(string, string[], int, int, string) | Ajoute des pages, qui sont choisies parmi les documents portFiles. Le document de résultat inclut firstInputFile et toutes les pages de documents portFiles dans la plage startPage to endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate)(Document[], Document) | Concatène des documents. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_4)(Stream[], HttpResponse) | Concatène les fichiers et stocke le résultat dans l'objet HttpResponse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_3)(Stream[], Stream) | Concatène les fichiers |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_8)(string[], HttpResponse) | Concatène les fichiers et enregistre le résultat dans l'objet HttpResposnse. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_7)(string[], string) | Concatène les fichiers en un seul fichier. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_1)(Stream, Stream, Stream) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_5)(string, string, string) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_2)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate#concatenate_6)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_1)(Stream, int[], HttpResponse) | Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete)(Stream, int[], Stream) | Supprime les pages spécifiées par le tableau de nombres du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_3)(string, int[], HttpResponse) | Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpResponse. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete#delete_2)(string, int[], string) | Supprime les pages spécifiées par le tableau de nombres du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_2)(Stream, int[], HttpResponse) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_1)(Stream, int[], Stream) | Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_5)(string, int[], HttpResponse) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_4)(string, int[], string) | Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract)(Stream, int, int, Stream) | Extrait les pages du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract#extract_3)(string, int, int, string) | Extrait les pages du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_2)(Stream, int, Stream, int[], HttpResponse) | Insère le document dans un autre document et stocke le résultat dans l'objet de réponse. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_1)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_5)(string, int, string, int[], HttpResponse) | Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_4)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert)(Stream, int, Stream, int, int, Stream) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert#insert_3)(string, int, string, int, int, string) | Insère des pages d'un autre fichier dans le fichier PDF à une position. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_2)(Stream, Stream) | Crée un livret du InputStream au outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_8)(string, string) | Crée un livret du fichier d'entrée au fichier de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_1)(Stream, PageSize, HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_3)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_7)(string, PageSize, HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_9)(string, string, PageSize) | Crée un livret du fichier d'entrée au fichier de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_5)(Stream, Stream, int[], int[]) | Crée un livret personnalisé du premier flux d'entrée au flux de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_11)(string, string, int[], int[]) | Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Créer un livret à partir d'un fichier PDF et le stocker dans HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crée un livret du premier flux d'entrée au flux de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet#makebooklet_10)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_4)(Stream, Stream, Stream) | Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_5)(Stream[], Stream, bool) | Crée un document N-Up à partir des flux PDF multi-entrées vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont combinées avec des pages dans les flux d'entrée du même numéro de page. Les multi-pages empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_10)(string, string, string) | Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_11)(string[], string, bool) | Crée un document N-Up à partir des fichiers PDF multi-entrées vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont combinées avec des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_1)(Stream, int, int, HttpResponse) | Crée un document N-up et stocke le résultat dans HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_2)(Stream, Stream, int, int) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_7)(string, int, int, HttpResponse) | Crée un document N-up et stocke le résultat dans HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_8)(string, string, int, int) | Crée un document N-Up du premier fichier d'entrée au fichier de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup)(Stream, int, int, PageSize, HttpResponse) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_3)(Stream, Stream, int, int, PageSize) | Crée un document N-Up du premier flux d'entrée au flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_6)(string, int, int, PageSize, HttpResponse) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup#makenup_9)(string, string, int, int, PageSize) | Crée un document N-Up du fichier d'entrée au fichier de sortie. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_6)(Document, ContentsResizeParameters) | Redimensionne les pages du document. Des marges vierges sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_7)(Document, int[], ContentsResizeParameters) | Redimensionne les pages du document. Des marges vierges sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_4)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_2)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents#resizecontents_5)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct#resizecontentspct_1)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_1)(Stream, int, HttpResponse) | Divise le document du début à l'emplacement spécifié et stocke le résultat dans l'objet HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst)(Stream, int, Stream) | Fractionne du début à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_3)(string, int, HttpResponse) | Divise le document de la première page à l'emplacement et enregistre le résultat dans des objets HttpResponse. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst#splitfromfirst_2)(string, int, string) | Divise le fichier PDF de la première page à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks)(Stream, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks#splittobulks_1)(string, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou de plusieurs pages. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_1)(Stream, int, HttpResponse) | Se divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend)(Stream, int, Stream) | Sépare à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau fichier Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_3)(string, int, HttpResponse) | Se divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend#splittoend_2)(string, int, string) | Sépare de l'emplacement et enregistre la partie arrière dans un nouveau fichier. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages)(Stream) | Divise le fichier PDF en documents d'une seule page. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_1)(string) | Divise le fichier PDF en documents d'une seule page. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_2)(Stream, string) | Divisez le fichier PDF en documents d'une seule page et enregistrez-le dans le chemin spécifié. Le chemin est spécifié par le nom du champ template. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages#splittopages_3)(string, string) | Divisez le fichier PDF en documents d'une seule page et enregistrez-le dans le chemin spécifié. Le chemin est spécifié par le nom du champ template. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_1)(Stream, Stream[], int, int, HttpResponse) | Ajoute des documents au document source et enregistre le résultat dans l'objet de réponse. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend)(Stream, Stream[], int, int, Stream) | Ajoute des pages, qui sont choisies dans un tableau de documents dans portStreams. Le document de résultat inclut firstInputFile et toutes les pages de documents portStreams dans la plage startPage à endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_3)(string, string[], int, int, HttpResponse) | Ajoute des documents au document source et enregistre le résultat dans l'objet HttpResponse. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend#tryappend_2)(string, string[], int, int, string) | Ajoute des pages, qui sont choisies parmi les documents portFiles. Le document de résultat inclut firstInputFile et toutes les pages de documents portFiles dans la plage startPage to endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate)(Document[], Document) | Concatène des documents. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_3)(Stream[], HttpResponse) | Concatène les fichiers et stocke le résultat dans l'objet HttpResponse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_2)(Stream[], Stream) | Concatène les fichiers |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_7)(string[], HttpResponse) | Concatène les fichiers et enregistre le résultat dans l'objet HttpResposnse. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_6)(string[], string) | Concatène les fichiers en un seul fichier. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_4)(string, string, string) | Concatène deux fichiers. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate#tryconcatenate_5)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vierges. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage . |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_1)(Stream, int[], HttpResponse) | Supprime les pages spécifiées du document et enregistre le résultat dans l'objet HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete)(Stream, int[], Stream) | Supprime les pages spécifiées par le tableau de nombres du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_3)(string, int[], HttpResponse) | Supprime les pages spécifiées du document et stocke le résultat dans l'objet HttpResponse. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete#trydelete_2)(string, int[], string) | Supprime les pages spécifiées par le tableau de nombres du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_1)(Stream, int[], HttpResponse) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract)(Stream, int[], Stream) | Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_4)(string, int[], HttpResponse) | Extrait les pages spécifiées du fichier source et stocke le résultat dans l'objet HttpResponse. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_3)(string, int[], string) | Extrait les pages spécifiées par un tableau de nombres, enregistre en tant que nouveau fichier PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract#tryextract_2)(string, int, int, string) | Extrait les pages du fichier d'entrée, enregistre en tant que nouveau fichier Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_1)(Stream, int, Stream, int[], HttpResponse) | Insère le document dans un autre document et stocke le résultat dans l'objet de réponse. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_3)(string, int, string, int[], HttpResponse) | Insère le contenu du fichier dans le fichier source et stocke le résultat dans l'objet HttpResponse. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert#tryinsert_2)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier PDF d'entrée. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_2)(Stream, Stream) | Crée un livret du InputStream au outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_8)(string, string) | Crée un livret du fichier d'entrée au fichier de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_1)(Stream, PageSize, HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_3)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_7)(string, PageSize, HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_9)(string, string, PageSize) | Crée un livret du fichier d'entrée au fichier de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_5)(Stream, Stream, int[], int[]) | Crée un livret personnalisé du premier flux d'entrée au flux de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_11)(string, string, int[], int[]) | Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet)(Stream, PageSize, int[], int[], HttpResponse) | Créer un livret à partir d'un fichier PDF et le stocker dans HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_4)(Stream, Stream, PageSize, int[], int[]) | Crée un livret du premier flux d'entrée au flux de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_6)(string, PageSize, int[], int[], HttpResponse) | Crée un livret à partir du fichier source et stocke le résultat dans des objets HttpResponse. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet#trymakebooklet_10)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé du premier fichier d'entrée au fichier de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_4)(Stream, Stream, Stream) | Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_5)(Stream[], Stream, bool) | Crée un document N-Up à partir des flux PDF multi-entrées vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont combinées avec des pages dans les flux d'entrée du même numéro de page. Les multi-pages empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_10)(string, string, string) | Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page du premier fichier d'entrée et une autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_11)(string[], string, bool) | Crée un document N-Up à partir des fichiers PDF multi-entrées vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont combinées avec des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_1)(Stream, int, int, HttpResponse) | Crée un document N-up et stocke le résultat dans HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_2)(Stream, Stream, int, int) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_7)(string, int, int, HttpResponse) | Crée un document N-up et stocke le résultat dans HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_8)(string, string, int, int) | Crée un document N-Up du premier fichier d'entrée au fichier de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup)(Stream, int, int, PageSize, HttpResponse) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_3)(Stream, Stream, int, int, PageSize) | Crée un document N-Up du premier flux d'entrée au flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_6)(string, int, int, PageSize, HttpResponse) | Crée un document N-up et stocke le résultat dans l'objet HttpResponse. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup#trymakenup_9)(string, string, int, int, PageSize) | Crée un document N-Up du fichier d'entrée au fichier de sortie. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents)(Stream, int[], ContentsResizeParameters, HttpResponse) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_1)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_3)(string, int[], ContentsResizeParameters, HttpResponse) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. Le résultat est stocké dans l'objet HttpResponse. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_4)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges vierges sont ajoutées autour de la page. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents#tryresizecontents_2)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_1)(Stream, int, HttpResponse) | Divise le document du début à l'emplacement spécifié et stocke le résultat dans l'objet HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst)(Stream, int, Stream) | Fractionne du début à l'emplacement spécifié et enregistre la partie avant dans le flux de sortie. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_3)(string, int, HttpResponse) | Divise le document de la première page à l'emplacement et enregistre le résultat dans des objets HttpResponse. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst#trysplitfromfirst_2)(string, int, string) | Divise le fichier PDF de la première page à l'emplacement spécifié et enregistre la partie avant en tant que nouveau fichier. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_1)(Stream, int, HttpResponse) | Se divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend)(Stream, int, Stream) | Sépare à partir de l'emplacement spécifié et enregistre la partie arrière en tant que nouveau fichier Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_3)(string, int, HttpResponse) | Se divise à partir de l'emplacement spécifié et enregistre la partie arrière dans l'objet HttpResponse. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend#trysplittoend_2)(string, int, string) | Sépare de l'emplacement et enregistre la partie arrière dans un nouveau fichier. |

## Autres membres

| Nom | La description |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](pdffileeditor.concatenatecorruptedfileaction) | Action effectuée lorsqu'un fichier corrompu a été rencontré dans le processus de concaténation. |
| class [ContentsResizeParameters](pdffileeditor.contentsresizeparameters) | Classe pour spécifier les paramètres de redimensionnement de la page. Permet de définir les paramètres suivants : Taille de la page de résultat (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille initiale des pages ; Marges de gauche, du haut, du bas et de droite dans les unités d'espace par défaut ou en pourcentage de la taille de page initiale ; Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et la nouvelle largeur de page spécifiée 60 unités, alors les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents. |
| class [ContentsResizeValue](pdffileeditor.contentsresizevalue) | Valeur de la marge ou de la taille du contenu spécifiée en pourcentage des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters. |
| class [CorruptedItem](pdffileeditor.corrupteditem) | Classe qui fournit des informations sur les fichiers corrompus au moment de la concaténation. |
| class [PageBreak](pdffileeditor.pagebreak) | Données de position de saut de page. |

### Voir également

* espace de noms [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
