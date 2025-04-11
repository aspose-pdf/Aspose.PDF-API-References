---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileEditor. Implémente des opérations avec la concaténation de fichiers PDF, le fractionnement, l'extraction de pages, la création de livrets, etc.
type: docs
weight: 4460
url: /fr/net/aspose.pdf.facades/pdffileeditor/
---
## Classe PdfFileEditor

Implémente des opérations avec des fichiers PDF : concaténation, fractionnement, extraction de pages, création de livrets, etc.

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
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | S'il est défini sur vrai, les flux sont fermés après l'opération. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Nombre de documents concaténés avant qu'une nouvelle mise à jour incrémentielle ne soit effectuée lors de la concaténation lorsque UseDiskBuffer est défini sur vrai. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Obtient le journal du processus de conversion. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré dans le format PDF par défaut sans conversion. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Si vrai, la structure logique du fichier est copiée lors de la concaténation. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Si vrai, les contours seront copiés. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Cette propriété définit le comportement lorsque le processus de concaténation rencontre un fichier corrompu. Les valeurs possibles sont : StopWithError et ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Tableau des problèmes rencontrés lors de la concaténation. Pour chaque document corrompu passé à la fonction Concatenate(), une nouvelle entrée CorruptedItem est créée. Cette propriété ne peut être utilisée que lorsque CorruptedFileAction est ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Si vrai, des mises à jour incrémentielles sont effectuées lors de la concaténation. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Si vrai, les actions seront copiées à partir des documents sources. Valeur par défaut : vrai. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Si vrai, les noms de champs seront rendus uniques lors de la concaténation des formulaires. Des suffixes seront ajoutés aux noms de champs, le modèle de suffixe peut être spécifié dans la propriété UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Obtient la dernière exception survenue. Peut être utilisé pour vérifier la raison de l'échec. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | Le contenu optionnel des documents concaténés avec des noms égaux sera fusionné en une seule couche dans le document résultant si cette propriété est vraie. Sinon, les couches avec des noms égaux seront enregistrées comme différentes couches dans le document résultant. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Si vrai, les contours dupliqués sont fusionnés. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Obtient ou définit le drapeau d'optimisation. Les flux de ressources égaux dans le fichier résultant sont fusionnés en un seul objet PDF si ce drapeau est défini. Cela permet de réduire la taille du fichier résultant mais peut entraîner une exécution plus lente et des exigences de mémoire plus importantes. Valeur par défaut : faux. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Définit le mot de passe du propriétaire si le fichier PDF source est crypté. Cette propriété n'est pas encore implémentée. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Si vrai, les droits d'utilisateur du premier document sont appliqués au document concaténé. Les droits d'utilisateur de tous les autres documents sont ignorés. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Si vrai, toutes les signatures seront supprimées des champs (les champs resteront) ; sinon, vous pouvez obtenir des signatures invalides. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Format du suffixe qui est ajouté au nom de champ pour le rendre unique lors de la concaténation des formulaires. Cette chaîne doit contenir le sous-ensemble %NUM% qui sera remplacé par des chiffres. Par exemple, si UniqueSuffix = "ABC%NUM%", alors pour le champ "fieldName", les noms seront : fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Si cette option est utilisée, le document de destination sera enregistré sur le disque périodiquement et la concaténation ultérieure sera appliquée comme des mises à jour incrémentielles. |

## Méthodes

| Nom | Description |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées dans les unités d'espace par défaut. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentages de la taille de la page initiale. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Redimensionne le contenu de la page et ajoute les marges spécifiées. Les marges sont spécifiées en pourcentages de la taille de la page initiale. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Ajoute des sauts de page dans les pages du document. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Ajoute des pages, choisies à partir de portStream dans la plage de startPage à endPage, dans portStream à la fin de firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Ajoute des pages, choisies à partir d'un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Ajoute des pages, choisies à partir de portFile dans la plage de startPage à endPage, dans portFile à la fin de firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Ajoute des pages, choisies à partir de documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Concatène des documents. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Concatène des fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Concatène des fichiers en un seul fichier. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Concatène deux fichiers. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vides. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, page vide, p5, page vide. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vides. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, page vide, p5, page vide. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Supprime les pages spécifiées par le tableau de numéros du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Supprime les pages spécifiées par le tableau de numéros du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extrait les pages spécifiées par le tableau de numéros, enregistre comme un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extrait les pages spécifiées par le tableau de numéros, enregistre comme un nouveau fichier PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extrait des pages du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extrait des pages du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Insère des pages d'un autre fichier dans le fichier Pdf à une position. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Crée un livret à partir de InputStream vers outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Crée un livret à partir de inputFile vers outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Crée un livret personnalisé à partir de firstInputStream vers outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Crée un livret personnalisé à partir de firstInputFile vers outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crée un livret à partir de firstInputStream vers outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé à partir de firstInputFile vers outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Crée un document N-Up à partir des flux PDF d'entrée multiples vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages dans les flux d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page provenant du premier fichier d'entrée et une autre provenant du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Crée un document N-Up à partir des fichiers PDF d'entrée multiples vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Crée un document N-Up à partir de firstInputFile vers outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Crée un document N-Up à partir du fichier d'entrée vers outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Redimensionne les pages du document. Des marges vides sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Redimensionne les pages du document. Des marges vides sont ajoutées autour de la page réduite. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages dans le document. Si la page est réduite, des marges vides sont ajoutées autour de la page. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée en pourcentages. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Divise depuis le début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Divise le fichier Pdf depuis la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à page unique ou multi-pages. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Divise le fichier Pdf en plusieurs documents. Les documents peuvent être à page unique ou multi-pages. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Divise depuis l'emplacement spécifié, et enregistre la partie arrière comme un nouveau flux de fichier. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Divise depuis l'emplacement, et enregistre la partie arrière comme un nouveau fichier. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Divise le fichier Pdf en documents à page unique. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Divise le fichier PDF en documents à page unique. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Divise le fichier Pdf en documents à page unique et les enregistre dans le chemin spécifié. Le chemin est spécifié par le modèle de nom de champ. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Divise le fichier Pdf en documents à page unique et les enregistre dans le chemin spécifié. Le chemin est spécifié par le modèle de nom de champ. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Ajoute des pages, choisies à partir d'un tableau de documents dans portStreams. Le document résultant comprend firstInputFile et toutes les pages des documents portStreams dans la plage startPage à endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Ajoute des pages, choisies à partir de documents portFiles. Le document résultant comprend firstInputFile et toutes les pages des documents portFiles dans la plage startPage à endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Concatène des documents. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Concatène des fichiers. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Concatène des fichiers en un seul fichier. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Concatène deux fichiers. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vides. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, page vide, p5, page vide. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Fusionne deux documents Pdf en un nouveau document Pdf avec des pages de manière alternée et remplit les espaces vides avec des pages vides. par exemple : document1 a 5 pages : p1, p2, p3, p4, p5. document2 a 3 pages : p1', p2', p3'. La fusion des deux documents Pdf produira le document résultant avec les pages : p1, p1', p2, p2', p3, p3', p4, page vide, p5, page vide. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Supprime les pages spécifiées par le tableau de numéros du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Supprime les pages spécifiées par le tableau de numéros du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extrait les pages spécifiées par le tableau de numéros, enregistre comme un nouveau fichier Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extrait les pages spécifiées par le tableau de numéros, enregistre comme un nouveau fichier PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extrait des pages du fichier d'entrée, enregistre comme un nouveau fichier Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Insère des pages d'un autre fichier dans le fichier Pdf d'entrée. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Crée un livret à partir de InputStream vers outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Crée un livret à partir du fichier d'entrée vers le fichier de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Crée un livret à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Crée un livret à partir de inputFile vers outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Crée un livret personnalisé à partir de firstInputStream vers outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Crée un livret personnalisé à partir de firstInputFile vers outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Crée un livret à partir de firstInputStream vers outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Crée un livret personnalisé à partir de firstInputFile vers outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Crée un document N-Up à partir des deux flux PDF d'entrée vers outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Crée un document N-Up à partir des flux PDF d'entrée multiples vers outputStream. Chaque page de outputStream contiendra plusieurs pages, qui sont une combinaison des pages dans les flux d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Crée un document N-Up à partir des deux fichiers PDF d'entrée vers outputFile. Chaque page de outputFile contiendra deux pages, une page provenant du premier fichier d'entrée et une autre provenant du deuxième fichier d'entrée. Les deux pages sont empilées horizontalement. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Crée un document N-Up à partir des fichiers PDF d'entrée multiples vers outputFile. Chaque page de outputFile contiendra plusieurs pages, qui sont une combinaison des pages dans les fichiers d'entrée du même numéro de page. Les pages multiples sont empilées horizontalement si isSidewise est vrai et empilées verticalement si isSidewise est faux. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Crée un document N-Up à partir du flux d'entrée et enregistre le résultat dans le flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Crée un document N-Up à partir de firstInputFile vers outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Crée un document N-Up à partir du premier flux d'entrée vers le flux de sortie. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Crée un document N-Up à partir du fichier d'entrée vers outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensionne le contenu des pages du document. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensionne le contenu des pages dans le document. Si la page est réduite, des marges vides sont ajoutées autour de la page. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Redimensionne le contenu des pages du document. Réduit le contenu de la page et ajoute des marges. La nouvelle taille du contenu est spécifiée dans les unités d'espace par défaut. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Divise depuis le début jusqu'à l'emplacement spécifié, et enregistre la partie avant dans le flux de sortie. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Divise le fichier Pdf depuis la première page jusqu'à l'emplacement spécifié, et enregistre la partie avant comme un nouveau fichier. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Divise depuis l'emplacement spécifié, et enregistre la partie arrière comme un nouveau flux de fichier. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Divise depuis l'emplacement, et enregistre la partie arrière comme un nouveau fichier. |

## Autres Membres

| Nom | Description |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Action effectuée lorsqu'un fichier corrompu a été rencontré dans le processus de concaténation. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Classe pour spécifier les paramètres de redimensionnement de page. Permet de définir les paramètres suivants : Taille de la page résultante (largeur, hauteur) en unités d'espace par défaut ou en pourcentages de la taille des pages initiales ; Marges gauche, supérieure, inférieure et droite en unités d'espace par défaut ou en pourcentages de la taille de la page initiale ; Certaines valeurs peuvent être laissées nulles pour un calcul automatique. Ces valeurs seront calculées à partir du reste de la taille de la page après le calcul des valeurs explicitement spécifiées. Par exemple : si la largeur de la page = 100 et la nouvelle largeur de la page spécifiée est de 60 unités, alors les marges gauche et droite sont automatiquement calculées : (100 - 60) / 2 = 15. Cette classe est utilisée dans la méthode ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Valeur de marge ou de taille de contenu spécifiée en pourcentages des unités d'espace par défaut. Cette classe est utilisée dans ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Classe qui fournit des informations sur les fichiers corrompus au moment de la concaténation. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Données de position de saut de page. |

### Voir aussi

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)