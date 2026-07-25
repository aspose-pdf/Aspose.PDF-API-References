---
title: "Aspose.PDF pour Go via C++"
description: "Aspose.PDF pour Go via C++"
keywords:  "Go, Golang, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /fr/go-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Go via C++ allows developers manipulate them PDF files directly in the Go.

# Types

## Document
Le document représente un document PDF.

```go
type Document struct {
}
```

# Functions

## Convert from PDF functions

| Fonction | Description |
| -------- | ----------- |
| [SaveDocX](./convert/savedocx/) | Convertir et enregistrer le PDF-document précédemment ouvert au format DocX-document. |
| [SaveDoc](./convert/savedoc/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Doc-document. |
| [SaveXlsX](./convert/savexlsx/) | Convertir et enregistrer le PDF-document précédemment ouvert au format XlsX-document. |
| [SaveTxt](./convert/savetxt/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Txt-document. |
| [SavePptX](./convert/savepptx/) | Convertir et enregistrer le PDF-document précédemment ouvert au format PptX-document. |
| [SaveXps](./convert/savexps/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Xps-document. |
| [SaveTeX](./convert/savetex/) | Convertir et enregistrer le PDF-document précédemment ouvert au format TeX-document. |
| [SaveEpub](./convert/saveepub/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Epub-document. |
| [SaveBooklet](./convert/savebooklet/) | Convertir et enregistrer le PDF-document précédemment ouvert au format PDF-document livret. |
| [SaveNUp](./convert/savenup/) | Convertir et enregistrer le PDF-document précédemment ouvert au format PDF-document N-Up. |
| [SaveMarkdown](./convert/savemarkdown/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Markdown-document. |
| [SaveTiff](./convert/savetiff/) | Convertir et enregistrer le PDF-document précédemment ouvert au format Tiff-document. |
| [SaveDocXEnhanced](./convert/savedocxenhanced/) | Convertir et enregistrer le PDF-document précédemment ouvert au format DocX-document avec le Mode de Reconnaissance Améliorée (tables et paragraphes entièrement modifiables). |
| [SaveSvgZip](./convert/savesvgzip/) | Convertir et enregistrer le PDF-document précédemment ouvert au format SVG-archive. |
| [ExportFdf](./convert/exportfdf/) | Exporter le PDF-document précédemment ouvert avec AcroForm vers le format FDF-document. |
| [ExportXfdf](./convert/exportxfdf/) | Exporter le PDF-document précédemment ouvert avec AcroForm vers le format XFDF-document. |
| [ExportXml](./convert/exportxml/) | Exporter le PDF-document précédemment ouvert avec AcroForm vers le format XML-document. |
| [PageToJpg](./convert/pagetojpg/) | Convertir et enregistrer la page spécifiée au format Jpg-image. |
| [PageToPng](./convert/pagetopng/) | Convertir et enregistrer la page spécifiée au format Png-image. |
| [PageToBmp](./convert/pagetobmp/) | Convertir et enregistrer la page spécifiée au format Bmp-image. |
| [PageToTiff](./convert/pagetotiff/) | Convertir et enregistrer la page spécifiée au format Tiff-image. |
| [PageToSvg](./convert/pagetosvg/) | Convertir et enregistrer la page spécifiée en tant qu'image Svg-image. |
| [PageToPdf](./convert/pagetopdf/) | Convertir et enregistrer la page spécifiée en tant que Pdf. |
| [PageToDICOM](./convert/pagetodicom/) | Convertir et enregistrer la page spécifiée en tant qu'image DICOM-image. |


## Organize PDF functions

| Fonction | Description |
| -------- | ----------- |
| [Optimize](./organize/optimize/) | Optimiser le contenu du PDF-document. |
| [OptimizeResource](./organize/optimizeresource/) | Optimiser les ressources du PDF-document. |
| [Grayscale](./organize/grayscale/) | Convertir le PDF-document en noir et blanc. |
| [Rotate](./organize/rotate/) | Faire pivoter le PDF-document. |
| [SetBackground](./organize/setbackground/) | Définir la couleur d'arrière-plan du PDF-document. |
| [Repair](./organize/repair/) | Réparer le PDF-document. |
| [ReplaceText](./organize/replacetext/) | Remplacer le texte dans le PDF-document. |
| [AddPageNum](./organize/addpagenum/) | Ajouter le numéro de page à un PDF-document. |
| [AddTextHeader](./organize/addtextheader/) | Ajouter du texte dans l'en-tête d'un PDF-document. |
| [AddTextFooter](./organize/addtextfooter/) | Ajouter du texte dans le pied de page d'un PDF-document. |
| [Flatten](./organize/flatten/) | Aplatir le PDF-document. |
| [RemoveAnnotations](./organize/removeannotations/) | Supprimer les annotations du PDF-document. |
| [RemoveAttachments](./organize/removeattachments/) | Supprimer les pièces jointes du PDF-document. |
| [RemoveBlankPages](./organize/removeblankpages/) | Supprimer les pages vierges du PDF-document. |
| [RemoveBookmarks](./organize/removebookmarks/) | Supprimer les signets du PDF-document. |
| [RemoveHiddenText](./organize/removehiddentext/) | Supprimer le texte caché du PDF-document. |
| [RemoveImages](./organize/removeimages/) | Supprimer les images du PDF-document. |
| [RemoveJavaScripts](./organize/removejavascripts/) | Supprimer les java scripts du PDF-document. |
| [RemoveTables](./organize/removetables/) | Supprimer les tableaux du PDF-document. |
| [RemoveWatermarks](./organize/removewatermarks/) | Supprimer les filigranes du PDF-document. |
| [AddWatermark](./organize/addwatermark/) | Ajouter un filigrane au PDF-document. |
| [EmbedFonts](./organize/embedfonts/) | Incorporer les polices dans un PDF-document. |
| [UnembedFonts](./organize/unembedfonts/) | Désincorporer les polices d'un document PDF. |
| [OptimizeFileSize](./organize/optimizefilesize/) | Optimiser la taille d'un document PDF avec la qualité de compression des images. |
| [RemoveTextHeaders](./organize/removetextheaders/) | Supprimer les en-têtes de texte d'un document PDF. |
| [RemoveTextFooters](./organize/removetextfooters/) | Supprimer les pieds de page de texte d'un document PDF. |
| [Crop](./organize/crop/) | Rogner les pages d'un document PDF. |
| [ReplaceFont](./organize/replacefont/) | Remplacer la police dans un document PDF. |
| [Convert](./organize/convert/) | Convertir un document PDF en un document PDF avec le format PDF spécifié. |
| [Validate](./organize/validate/) | Valider un document PDF pour la conformité au format PDF. |
| [RemovePdfaCompliance](./organize/removepdfacompliance/) | Supprimer la conformité PDF/A d'un document PDF. |
| [RemovePdfUaCompliance](./organize/removepdfuacompliance/) | Supprimer la conformité PDF/UA d'un document PDF. |
| [IsPdfaCompliant](./organize/ispdfacompliant/) | Déterminer si un document PDF est conforme PDF/A. |
| [IsPdfUaCompliant](./organize/ispdfuacompliant/) | Déterminer si un document PDF est conforme PDF/UA. |
| [PageRotate](./organize/pagerotate/) | Faire pivoter la page. |
| [PageSetSize](./organize/pagesetsize/) | Définir la taille de la page. |
| [PageGrayscale](./organize/pagegrayscale/) | Convertir la page en noir et blanc. |
| [PageAddText](./organize/pageaddtext/) | Ajouter du texte sur la page. |
| [PageReplaceText](./organize/pagereplacetext/) | Remplacer le texte sur la page. |
| [PageAddPageNum](./organize/pageaddpagenum/) | Ajouter le numéro de page sur la page. |
| [PageAddTextHeader](./organize/pageaddtextheader/) | Ajouter du texte dans l'en-tête de la page. |
| [PageAddTextFooter](./organize/pageaddtextfooter/) | Ajouter du texte dans le pied de page de la page. |
| [PageRemoveAnnotations](./organize/pageremoveannotations/) | Supprimer les annotations de la page. |
| [PageRemoveHiddenText](./organize/pageremovehiddentext/) | Supprimer le texte caché de la page. |
| [PageRemoveImages](./organize/pageremoveimages/) | Supprimer les images de la page. |
| [PageRemoveTables](./organize/pageremovetables/) | Supprimer les tableaux de la page. |
| [PageRemoveWatermarks](./organize/pageremovewatermarks/) | Supprimer les filigranes de la page. |
| [PageAddWatermark](./organize/pageaddwatermark/) | Ajouter un filigrane sur la page. |
| [PageRemoveTextHeaders](./organize/pageremovetextheaders/) | Supprimer les en-têtes de texte de la page. |
| [PageRemoveTextFooters](./organize/pageremovetextfooters/) | Supprimer les pieds de page de texte de la page. |
| [PageCrop](./organize/pagecrop/) | Rogner la page. |
| [PageReplaceFont](./organize/pagereplacefont/) | Remplacer la police dans la page. |
| [PageMergeLayers](./organize/pagemergelayers/) | Fusionner toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié. |
| [PageLayers](./organize/pagelayers/) | Obtient les noms des couches sur la page. |


## Core PDF functions

| Fonction | Description |
| -------- | ----------- |
| [New](./core/new/) | Créer un nouveau document PDF. |
| [Open](./core/open/) | Ouvrir un document PDF avec le nom de fichier. |
| [Save](./core/save/) | Enregistrer le document PDF précédemment ouvert. |
| [SaveAs](./core/saveas/) | Enregistrer le document PDF précédemment ouvert avec un nouveau nom de fichier. |
| [Close](./core/close/) | Libérer les ressources allouées pour le document PDF. |
| [SetLicense](./core/setlicense/) | Définir la licence avec le nom de fichier. |
| [ExtractText](./core/extracttext/) | Retourner le contenu du document PDF en texte brut. |
| [WordCount](./core/wordcount/) | Retourner le nombre de mots dans le document PDF. |
| [CharacterCount](./core/charactercount/) | Retourner le nombre de caractères dans le document PDF. |
| [Append](./core/append/) | Ajouter des pages d'un autre document PDF. |
| [AppendPages](./core/appendpages/) | Ajouter les pages sélectionnées d'un autre document PDF. |
| [MergeDocuments](./core/mergedocuments/) | Créer un nouveau document PDF en fusionnant les documents PDF fournis. |
| [SplitDocument](./core/splitdocument/) | Créer plusieurs nouveaux documents PDF en extrayant des pages du document PDF source. |
| [Split](./core/split/) | Créer plusieurs nouveaux documents PDF en extrayant des pages du document PDF actuel. |
| [SplitAtPage](./core/splitatpage/) | Diviser le document PDF en deux nouveaux documents PDF. |
| [SplitAt](./core/splitat/) | Diviser le document PDF actuel en deux nouveaux documents PDF. |
| [Bytes](./core/bytes/) | Retourner le contenu du document PDF sous forme de tranche d'octets. |
| [GetMetaInfo](./core/getmetainfo/) | Obtenir la valeur des méta-informations du document PDF.. |
| [SetMetaInfo](./core/setmetainfo/) | Définir la valeur des informations méta du PDF-document.. |
| [ClearMetaInfo](./core/clearmetainfo/) | Effacer toutes les valeurs des informations méta du PDF-document.. |
| [IsLinearized](./core/islinearized/) | Obtenir une valeur indiquant si le document est linéarisé. |
| [PageAdd](./core/pageadd/) | Ajouter une nouvelle page dans le PDF-document. |
| [PageInsert](./core/pageinsert/) | Insérer une nouvelle page à la position spécifiée dans le PDF-document. |
| [PageDelete](./core/pagedelete/) | Supprimer la page spécifiée du PDF-document. |
| [PageCount](./core/pagecount/) | Retourner le nombre de pages du PDF-document. |
| [PageWordCount](./core/pagewordcount/) | Retourner le nombre de mots sur la page spécifiée du PDF-document. |
| [PageCharacterCount](./core/pagecharactercount/) | Retourner le nombre de caractères sur la page spécifiée du PDF-document. |
| [PageIsBlank](./core/pageisblank/) | Retourner si la page est vide dans le PDF-document. |


## Security

| Fonction | Description |
| -------- | ----------- |
| [OpenWithPassword](./security/openwithpassword/) | Ouvrir un PDF-document protégé par mot de passe. |
| [Encrypt](./security/encrypt/) | Crypter le PDF-document. |
| [Decrypt](./security/decrypt/) | Décrypter le PDF-document. |
| [SetPermissions](./security/setpermissions/) | Définir les autorisations pour le PDF-document. |
| [GetPermissions](./security/getpermissions/) | Obtenir les autorisations actuelles du PDF-document. |
| [IsEncrypted](./security/isencrypted/) | Obtenir le statut de chiffrement du PDF-document. |
| [SignPKCS7](./security/signpkcs7/) | Signer un PDF-document en utilisant des signatures numériques PKCS#7. |
| [SignPKCS7Detached](./security/signpkcs7detached/) | Signer un PDF-document en utilisant des signatures numériques PKCS#7 détachées. |
| [IsSigned](./security/issigned/) | Obtenir le statut de signature du PDF-document. |
| [RemoveSigns](./security/removesigns/) | Supprimer les signatures du PDF-document. |


## Miscellaneous

| Fonction | Description |
| -------- | ----------- |
| [About](./miscellaneous/about/) | Retourner les informations de métadonnées sur le Aspose.PDF for Go via C++. |


# Types secondary

## ProductInfo contains metadata about the Aspose.PDF for Go via C++.
```go
type ProductInfo struct {
	Product     string `json:"product"`     // Name
	Family      string `json:"family"`      // Family (e.g., "Aspose.PDF")
	Version     string `json:"version"`     // Version
	ReleaseDate string `json:"releasedate"` // Release date in ISO format (YYYY-MM-DD)
	Producer    string `json:"producer"`    // Producer
	IsLicensed  bool   `json:"islicensed"`  // License status (true if licensed)
}
```


# Constants

## Enumeration of possible rotation values.
```go
const (
    RotationNone  int32 = 0 // Non-rotated.
    RotationOn90  int32 = 1 // Rotated on 90 degrees clockwise.
    RotationOn180 int32 = 2 // Rotated on 180 degrees.
    RotationOn270 int32 = 3 // Rotated on 270 degrees clockwise.
    RotationOn360 int32 = 4 // Rotated on 360 degrees clockwise.
)
```

## Enumeration of possible page size values.
```go
const (
    PageSizeA0         int32 = 0  // A0 size.
    PageSizeA1         int32 = 1  // A1 size.
    PageSizeA2         int32 = 2  // A2 size.
    PageSizeA3         int32 = 3  // A3 size.
    PageSizeA4         int32 = 4  // A4 size.
    PageSizeA5         int32 = 5  // A5 size.
    PageSizeA6         int32 = 6  // A6 size.
    PageSizeB5         int32 = 7  // B5 size.
    PageSizePageLetter int32 = 8  // PageLetter size.
    PageSizePageLegal  int32 = 9  // PageLegal size.
    PageSizePageLedger int32 = 10 // PageLedger size.
    PageSizeP11x17     int32 = 11 // P11x17 size.
)
```

## Enumeration of possible crypto algorithms.
```go
type CryptoAlgorithm int32
const (
	RC4x40  CryptoAlgorithm = 0 // RC4 with key length 40.
	RC4x128 CryptoAlgorithm = 1 // RC4 with key length 128.
	AESx128 CryptoAlgorithm = 2 // AES with key length 128.
	AESx256 CryptoAlgorithm = 3 // AES with key length 256.
)
```

## Enumeration of possible PDF formats.
```go
type PdfFormat int32
const (
	PDF_A_1A      PdfFormat = iota // Pdf/A-1a format.
	PDF_A_1B                       // Pdf/A-1b format.
	PDF_A_2A                       // Pdf/A-2a format.
	PDF_A_3A                       // Pdf/A-3a format.
	PDF_A_2B                       // Pdf/A-2b format.
	PDF_A_2U                       // Pdf/A-2u format.
	PDF_A_3B                       // Pdf/A-3b format.
	PDF_A_3U                       // Pdf/A-3u format.
	V_1_0                          // Adobe version 1.0.
	V_1_1                          // Adobe version 1.1.
	V_1_2                          // Adobe version 1.2.
	V_1_3                          // Adobe version 1.3.
	V_1_4                          // Adobe version 1.4.
	V_1_5                          // Adobe version 1.5.
	V_1_6                          // Adobe version 1.6.
	V_1_7                          // Adobe version 1.7.
	V_2_0                          // ISO Standard PDF 2.0.
	PDF_UA_1                       // PDF/UA-1 format.
	PDF_X_1A_2001                  // PDF/X-1a-2001 format.
	PDF_X_1A                       // PDF/X-1a format.
	PDF_X_3                        // PDF/X-3 format.
	ZUGFeRD                        // ZUGFeRD format.
	PDF_A_4                        // PDF/A-4 format.
	PDF_A_4E                       // PDF/A-4e format.
	PDF_A_4F                       // PDF/A-4f format.
	PDF_X_4                        // PDF/X-4 format.
	PDF_E_1                        // PDF/E-1 (PDF 1.6) format.
)
```

## Enumeration of possible conversion errors action.
```go
type ConvertErrorAction int32
const (
	Delete ConvertErrorAction = iota // Delete convert errors.
	None                             // Do nothing with convert errors.
)
```

## Bitflag set representing PDF permission capabilities.
```go
type Permissions int32
const (
    PrintDocument                  Permissions = 1 << 2  // 4
    ModifyContent                  Permissions = 1 << 3  // 8
    ExtractContent                 Permissions = 1 << 4  // 16
    ModifyTextAnnotations          Permissions = 1 << 5  // 32
    FillForm                       Permissions = 1 << 8  // 256
    ExtractContentWithDisabilities Permissions = 1 << 9  // 512
    AssembleDocument               Permissions = 1 << 10 // 1024
    PrintingQuality                Permissions = 1 << 11 // 2048
)
```
