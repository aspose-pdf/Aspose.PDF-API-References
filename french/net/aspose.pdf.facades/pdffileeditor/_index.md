---
title: "Classe PdfFileEditor"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Facades.PdfFileEditor. Implémente les opérations de concaténation, de division, d'extraction de pages, de création de livret, etc., avec les fichiers PDF."
type: docs
weight: 4580
url: /fr/net/aspose.pdf.facades/pdffileeditor/
---
## PdfFileEditor class

Implémente des opérations sur les fichiers PDF : concaténation, division, extraction de pages, création de livret, etc.

```csharp
public sealed class PdfFileEditor
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Si défini sur true, les flux sont fermés après l'opération. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée pendant la concaténation lorsque UseDiskBuffer est défini sur true. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Obtient le journal du processus de conversion. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Définit le format du fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Si vrai, alors la structure logique du fichier est copiée lors de la concaténation. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Si vrai, alors les contours seront copiés. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate(), une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Si vrai, des mises à jour incrémentielles sont effectuées pendant la concaténation. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Si vrai, les actions seront copiées depuis les documents source. Valeur par défaut : true. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Si vrai, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe pouvant être spécifié dans la propriété UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Obtient la dernière exception survenue. Peut être utilisée pour vérifier la raison de l'échec. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Le contenu optionnel des documents concaténés portant le même nom sera fusionné en une seule couche dans le document résultant si cette propriété est vraie. Sinon, les couches portant le même nom seront enregistrées comme des couches distinctes dans le document résultant. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Si vrai, les contours dupliqués sont fusionnés. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Obtient ou définit le drapeau d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est activé. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences mémoire plus importantes. Valeur par défaut : false. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Définit le mot de passe du propriétaire si le fichier Pdf source est chiffré. Cette propriété n'est pas encore implémentée. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Si vrai, les droits utilisateur du premier document sont appliqués au document concaténé. Les droits utilisateur de tous les autres documents sont ignorés. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Format du suffixe ajouté au nom du champ pour le rendre unique lors de la concaténation des formulaires. Cette chaîne doit contenir la sous‑chaîne %NUM% qui sera remplacée par des nombres. Par exemple, si UniqueSuffix = \"ABC%NUM%\", alors pour le champ \"fieldName\" les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Si cette option est utilisée, le document de destination sera enregistré périodiquement sur le disque et les concaténations ultérieures seront appliquées sous forme de mises à jour incrémentielles. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en unités d'espace par défaut. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en unités d'espace par défaut. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentage de la taille initiale de la page. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu des pages et ajoute les marges spécifiées. Les marges sont exprimées en pourcentage de la taille initiale de la page. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Ajoute les pages, choisies dans portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Ajoute les pages, choisies dans un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage de startPage à endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Ajoute les pages, choisies dans portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Ajoute les pages, choisies dans les documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage de startPage à endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Concatène les documents. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Concatène les fichiers |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Concatène les fichiers en un seul fichier. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Insère des pages d'un autre fichier dans le fichier Pdf à une position donnée. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Crée un livret à partir de l'InputStream vers l'outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Crée un livret à partir de l'inputFile vers l'outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crée un livret à partir du firstInputStream vers l'outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Crée un document N‑Up à partir des deux flux PDF d'entrée vers l'outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Crée un document N‑Up à partir de plusieurs flux PDF d'entrée vers l'outputStream. Chaque page de l'outputStream contiendra plusieurs pages, combinées avec les pages des flux d'entrée portant le même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Crée un document N‑Up à partir des deux fichiers PDF d'entrée vers l'outputFile. Chaque page de l'outputFile contiendra deux pages, une provenant du premier fichier d'entrée et l'autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Crée un document N‑Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile. Chaque page de l'outputFile contiendra plusieurs pages, combinées avec les pages des fichiers d'entrée portant le même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Crée un document N‑Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Crée un document N‑Up à partir du firstInputFile vers l'outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Crée un document N‑Up à partir du premier flux d'entrée vers le flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Crée un document N‑Up à partir du fichier d'entrée vers l'outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Redimensionne les pages du document. Des marges blanches sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Redimensionne les pages du document. Des marges blanches sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges blanches sont ajoutées autour de la page. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentage. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentage. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Divise du début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie Stream. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou multi-pages. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être d'une seule page ou multi-pages. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Divise à partir de l'emplacement spécifié, et enregistre la partie arrière comme un nouveau flux de fichier Stream. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Divise à partir de l'emplacement, et enregistre la partie arrière comme un nouveau fichier. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Divise le fichier Pdf en documents d'une seule page. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Divise le fichier PDF en documents d'une seule page. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Divise le fichier Pdf en documents d'une seule page et l'enregistre dans le chemin spécifié. Le chemin est specifield par le nom de champ temaplate. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Divise le fichier Pdf en documents d'une seule page et l'enregistre dans le chemin spécifié. Le chemin est specifield par le nom de champ temaplate. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Ajoute les pages, choisies dans un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage de startPage à endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Ajoute les pages, choisies dans les documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage de startPage à endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Concatène les documents. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Concatène les fichiers |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Concatène les fichiers en un seul fichier. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Concatène deux fichiers. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec les pages en alternance et remplit les espaces vides avec des pages blanches. par ex. : document1 possède 5 pages : p1, p2, p3, p4, p5. document2 possède 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultat avec les pages : p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Supprime les pages spécifiées par un tableau de numéros du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extrait les pages spécifiées par un tableau de numéros, puis enregistre un nouveau fichier PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extrait les pages du fichier d'entrée, puis enregistre un nouveau fichier Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Crée un livret à partir de l'InputStream vers l'outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Crée un livret à partir de l'inputFile vers l'outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Crée un livret personnalisé à partir du firstInputStream vers l'outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crée un livret à partir du firstInputStream vers l'outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé à partir du firstInputFile vers l'outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Crée un document N‑Up à partir des deux flux PDF d'entrée vers l'outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Crée un document N‑Up à partir de plusieurs flux PDF d'entrée vers l'outputStream. Chaque page de l'outputStream contiendra plusieurs pages, combinées avec les pages des flux d'entrée portant le même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Crée un document N‑Up à partir des deux fichiers PDF d'entrée vers l'outputFile. Chaque page de l'outputFile contiendra deux pages, une provenant du premier fichier d'entrée et l'autre du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Crée un document N‑Up à partir de plusieurs fichiers PDF d'entrée vers l'outputFile. Chaque page de l'outputFile contiendra plusieurs pages, combinées avec les pages des fichiers d'entrée portant le même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Crée un document N‑Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Crée un document N‑Up à partir du firstInputFile vers l'outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Crée un document N‑Up à partir du premier flux d'entrée vers le flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Crée un document N‑Up à partir du fichier d'entrée vers l'outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. Si la page est réduite, des marges blanches sont ajoutées autour de la page. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en unités d'espace par défaut. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Divise du début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie Stream. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Divise le fichier Pdf de la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Divise à partir de l'emplacement spécifié, et enregistre la partie arrière comme un nouveau flux de fichier Stream. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Divise à partir de l'emplacement, et enregistre la partie arrière comme un nouveau fichier. |

## Autres membres

| Nom | Description |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Action effectuée lorsqu'un fichier corrompu est rencontré lors du processus de concaténation. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Classe permettant de spécifier les paramètres de redimensionnement de page. Autorise la définition des paramètres suivants : taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentage de la taille des pages initiales ; marges gauche, haut, bas et droite en unités d'espace par défaut ou en pourcentage de la taille de la page initiale ; certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et que la nouvelle largeur de page spécifiée est 60 unités, les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Valeur de la marge ou de la taille du contenu spécifiée en pourcentages des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Classe qui fournit des informations sur les fichiers corrompus au moment de la concaténation. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Données de la position du saut de page. |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


