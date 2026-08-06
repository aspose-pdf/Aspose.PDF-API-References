---
title: "Aspose.PDF pour Rust via C++"
description: "Aspose.PDF pour Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /fr/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Structures

## Document
Le document représente un document PDF.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Fonction | Description |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Convertir et enregistrer le document PDF précédemment ouvert en document DocX. |
| [save_doc](./convert/save_doc/) | Convertir et enregistrer le document PDF précédemment ouvert en document Doc. |
| [save_xlsx](./convert/save_xlsx/) | Convertir et enregistrer le document PDF précédemment ouvert en document XlsX. |
| [save_txt](./convert/save_txt/) | Convertir et enregistrer le document PDF précédemment ouvert en document Txt. |
| [save_pptx](./convert/save_pptx/) | Convertir et enregistrer le document PDF précédemment ouvert en document PptX. |
| [save_xps](./convert/save_xps/) | Convertir et enregistrer le document PDF précédemment ouvert en document Xps. |
| [save_tex](./convert/save_tex/) | Convertir et enregistrer le document PDF précédemment ouvert en document TeX. |
| [save_epub](./convert/save_epub/) | Convertir et enregistrer le document PDF précédemment ouvert en document Epub. |
| [save_booklet](./convert/save_booklet/) | Convertir et enregistrer le document PDF précédemment ouvert en document PDF livret. |
| [save_n_up](./convert/save_n_up/) | Convertir et enregistrer le document PDF précédemment ouvert en document PDF N-Up. |
| [save_markdown](./convert/save_markdown/) | Convertir et enregistrer le document PDF précédemment ouvert en document Markdown. |
| [save_tiff](./convert/save_tiff/) | Convertir et enregistrer le document PDF précédemment ouvert en document Tiff. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Convertir et enregistrer le document PDF précédemment ouvert en document DocX avec le mode de reconnaissance avancé (tables et paragraphes entièrement modifiables). |
| [save_svg_zip](./convert/save_svg_zip/) | Convertir et enregistrer le document PDF précédemment ouvert en archive SVG. |
| [export_fdf](./convert/export_fdf/) | Exporter depuis le document PDF précédemment ouvert avec AcroForm vers le document FDF. |
| [export_xfdf](./convert/export_xfdf/) | Exporter depuis le document PDF précédemment ouvert avec AcroForm vers le document XFDF. |
| [export_xml](./convert/export_xml/) | Exporter depuis le document PDF précédemment ouvert avec AcroForm vers le document XML. |
| [page_to_jpg](./convert/page_to_jpg/) | Convertir et enregistrer la page spécifiée en image Jpg. |
| [page_to_png](./convert/page_to_png/) | Convertir et enregistrer la page spécifiée en image Png. |
| [page_to_bmp](./convert/page_to_bmp/) | Convertir et enregistrer la page spécifiée en image Bmp. |
| [page_to_tiff](./convert/page_to_tiff/) | Convertir et enregistrer la page spécifiée en tant qu'image Tiff. |
| [page_to_svg](./convert/page_to_svg/) | Convertir et enregistrer la page spécifiée en tant qu'image Svg. |
| [page_to_pdf](./convert/page_to_pdf/) | Convertir et enregistrer la page spécifiée en tant que document PDF. |
| [page_to_dicom](./convert/page_to_dicom/) | Convertir et enregistrer la page spécifiée en tant qu'image DICOM. |


## Organize PDF functions

| Fonction | Description |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Optimiser le contenu du document PDF. |
| [optimize_resource](./organize/optimize_resource/) | Optimiser les ressources du document PDF. |
| [grayscale](./organize/grayscale/) | Convertir le document PDF en noir et blanc. |
| [rotate](./organize/rotate/) | Faire pivoter le document PDF. |
| [set_background](./organize/set_background/) | Définir la couleur d'arrière-plan du document PDF en utilisant les valeurs RVB. |
| [repair](./organize/repair/) | Réparer le document PDF. |
| [replace_text](./organize/replace_text/) | Remplacer le texte dans le document PDF |
| [add_page_num](./organize/add_page_num/) | Ajouter le numéro de page à un document PDF |
| [add_text_header](./organize/add_text_header/) | Ajouter du texte dans l'en-tête d'un document PDF |
| [add_text_footer](./organize/add_text_footer/) | Ajouter du texte dans le pied de page d'un document PDF |
| [flatten](./organize/flatten/) | Aplatir le document PDF |
| [remove_annotations](./organize/remove_annotations/) | Supprimer les annotations du document PDF |
| [remove_attachments](./organize/remove_attachments/) | Supprimer les pièces jointes du document PDF |
| [remove_blank_pages](./organize/remove_blank_pages/) | Supprimer les pages blanches du document PDF |
| [remove_bookmarks](./organize/remove_bookmarks/) | Supprimer les signets du document PDF |
| [remove_hidden_text](./organize/remove_hidden_text/) | Supprimer le texte masqué du document PDF |
| [remove_images](./organize/remove_images/) | Supprimer les images du document PDF |
| [remove_javascripts](./organize/remove_javascripts/) | Supprimer les scripts Java du document PDF |
| [remove_tables](./organize/remove_tables/) | Supprimer les tableaux d'un document PDF. |
| [remove_watermarks](./organize/remove_watermarks/) | Supprimer les filigranes du document PDF. |
| [add_watermark](./organize/add_watermark/) | Ajouter un filigrane au document PDF. |
| [embed_fonts](./organize/embed_fonts/) | Intégrer les polices dans un PDF-document. |
| [unembed_fonts](./organize/unembed_fonts/) | Désintégrer les polices d'un PDF-document. |
| [optimize_file_size](./organize/optimize_file_size/) | Optimiser la taille d'un PDF-document avec la qualité de compression d'image. |
| [remove_text_headers](./organize/remove_text_headers/) | Supprimer les en-têtes de texte du PDF-document. |
| [remove_text_footers](./organize/remove_text_footers/) | Supprimer les pieds de page de texte du PDF-document. |
| [crop](./organize/crop/) | Recadrer les pages d'un PDF-document. |
| [replace_font](./organize/replace_font/) | Remplacer la police dans un PDF-document. |
| [convert](./organize/convert/) | Convertir un PDF-document en un PDF-document avec le format PDF spécifié |
| [validate](./organize/validate/) | Valider un PDF-document pour la conformité au format PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Supprimer la conformité PDF/A d'un PDF-document |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Supprimer la conformité PDF/UA d'un PDF-document |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Déterminer si un PDF-document est conforme PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Déterminer si un PDF-document est conforme PDF/UA |
| [page_rotate](./organize/page_rotate/) | Faire pivoter une page dans le PDF-document. |
| [page_set_size](./organize/page_set_size/) | Définir la taille d'une page dans le PDF-document. |
| [page_grayscale](./organize/page_grayscale/) | Convertir la page en noir et blanc. |
| [page_add_text](./organize/page_add_text/) | Ajouter du texte sur la page. |
| [page_replace_text](./organize/page_replace_text/) | Remplacer le texte sur la page |
| [page_add_page_num](./organize/page_add_page_num/) | Ajouter le numéro de page sur la page |
| [page_add_text_header](./organize/page_add_text_header/) | Ajouter du texte dans l'en-tête de la page |
| [page_add_text_footer](./organize/page_add_text_footer/) | Ajouter du texte dans le pied de page de la page |
| [page_remove_annotations](./organize/page_remove_annotations/) | Supprimer les annotations dans la page. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Supprimer le texte caché dans la page. |
| [page_remove_images](./organize/page_remove_images/) | Supprimer les images dans la page. |
| [page_remove_tables](./organize/page_remove_tables/) | Supprimer les tableaux dans la page. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Supprimer les filigranes dans la page. |
| [page_add_watermark](./organize/page_add_watermark/) | Ajouter un filigrane sur la page. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Supprimer les en-têtes de texte dans la page. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Supprimer les pieds de page de texte dans la page. |
| [page_crop](./organize/page_crop/) | Rogner une page. |
| [page_replace_font](./organize/page_replace_font/) | Remplacer la police dans la page. |
| [page_merge_layers](./organize/page_merge_layers/) | Fusionner toutes les couches de la page en une seule couche avec le nom de nouvelle couche spécifié. |
| [page_layers](./organize/page_layers/) | Obtenir les noms des couches sur la page. |


## Core PDF functions

| Fonction | Description |
| -------- | ----------- |
| [new](./core/new/) | Créer un nouveau document PDF. |
| [open](./core/open/) | Ouvrir un document PDF avec le nom de fichier. |
| [save](./core/save/) | Enregistrer le document PDF précédemment ouvert. |
| [save_as](./core/save_as/) | Enregistrer le document PDF précédemment ouvert avec un nouveau nom de fichier. |
| [set_license](./core/set_license/) | Définir la licence avec le nom de fichier. |
| [extract_text](./core/extract_text/) | Retourner le contenu du document PDF en texte brut. |
| [word_count](./core/word_count/) | Retourner le nombre de mots dans le document PDF. |
| [character_count](./core/character_count/) | Retourner le nombre de caractères dans le document PDF. |
| [append](./core/append/) | Ajouter des pages d'un autre document PDF. |
| [append_pages](./core/append_pages/) | Ajouter les pages sélectionnées d'un autre document PDF. |
| [merge_documents](./core/merge_documents/) | Créer un nouveau document PDF en fusionnant les documents PDF fournis. |
| [split_document](./core/split_document/) | Créer plusieurs nouveaux documents PDF en extrayant des pages du document PDF source. |
| [split](./core/split/) | Créer plusieurs nouveaux documents PDF en extrayant des pages du document PDF actuel. |
| [split_at_page](./core/split_at_page/) | Diviser le document PDF en deux nouveaux documents PDF. |
| [split_at](./core/split_at/) | Diviser le document PDF actuel en deux nouveaux documents PDF. |
| [bytes](./core/bytes/) | Retourner le contenu du document PDF sous forme de vecteur d'octets. |
| [get_meta_info](./core/get_meta_info/) | Obtenir la valeur des métadonnées du document PDF. |
| [set_meta_info](./core/set_meta_info/) | Définir la valeur des métadonnées du PDF-document. |
| [clear_meta_info](./core/clear_meta_info/) | Effacer toutes les valeurs des métadonnées du PDF-document. |
| [is_linearized](./core/is_linearized/) | Obtenir une valeur indiquant si le document est linéarisé. |
| [page_add](./core/page_add/) | Ajouter une nouvelle page dans le PDF-document. |
| [page_insert](./core/page_insert/) | Insérer une nouvelle page à la position spécifiée dans le PDF-document. |
| [page_delete](./core/page_delete/) | Supprimer la page spécifiée du PDF-document. |
| [page_count](./core/page_count/) | Retourner le nombre de pages du PDF-document. |
| [page_word_count](./core/page_word_count/) | Retourner le nombre de mots sur la page spécifiée du PDF-document. |
| [page_character_count](./core/page_character_count/) | Retourner le nombre de caractères sur la page spécifiée du PDF-document. |
| [page_is_blank](./core/page_is_blank/) | Retourner si la page est blanche dans le PDF-document. |


## Security
| Fonction | Description |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Ouvrir un PDF-document protégé par mot de passe. |
| [encrypt](./security/encrypt/) | Chiffrer le PDF-document. |
| [decrypt](./security/decrypt/) | Déchiffrer le PDF-document. |
| [set_permissions](./security/set_permissions/) | Définir les autorisations pour le PDF-document. |
| [get_permissions](./security/get_permissions/) | Obtenir les autorisations actuelles du PDF-document. |
| [is_encrypted](./security/is_encrypted/) | Obtenir le statut de chiffrement du PDF-document. |
| [sign_pkcs7](./security/sign_pkcs7/) | Signer un PDF-document en utilisant des signatures numériques PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Signer un PDF-document en utilisant des signatures numériques PKCS#7 détachées. |
| [is_signed](./security/is_signed/) | Obtenir le statut de signature du PDF-document. |
| [remove_signs](./security/remove_signs/) | Supprimer les signatures du PDF-document. |


## Miscellaneous

| Fonction | Description |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Retourner les informations de métadonnées sur Aspose.PDF pour Rust via C++. |



# Structs secondary

## ProductInfo contains metadata about the Aspose.PDF for Rust via C++.
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

## Bitflag set representing PDF permission capabilities.
```rust
bitflags! {
    /// Ensemble de bits représentant les capacités d'autorisation PDF.
    #[derive(Copy, Clone, PartialEq, Eq)]
    pub struct Permissions: i32 {
        const PRINT_DOCUMENT                    = 1 << 2;  // 4
        const MODIFY_CONTENT                    = 1 << 3;  // 8
        const EXTRACT_CONTENT                   = 1 << 4;  // 16
        const MODIFY_TEXT_ANNOTATIONS           = 1 << 5;  // 32
        const FILL_FORM                         = 1 << 8;  // 256
        const EXTRACT_CONTENT_WITH_DISABILITIES = 1 << 9;  // 512
        const ASSEMBLE_DOCUMENT                 = 1 << 10; // 1024
        const PRINTING_QUALITY                  = 1 << 11; // 2048
    }
}
```

# Enums

## Enumeration of possible page size values.
```rust
pub enum PageSize {
    /// Taille A0.
    A0 = 0,
    /// Taille A1.
    A1 = 1,
    /// Taille A2.
    A2 = 2,
    /// taille A3.
    A3 = 3,
    /// taille A4.
    A4 = 4,
    /// taille A5.
    A5 = 5,
    /// taille A6.
    A6 = 6,
    /// taille B5.
    B5 = 7,
    /// taille PageLetter.
    PageLetter = 8,
    /// taille PageLegal.
    PageLegal = 9,
    /// taille PageLedger.
    PageLedger = 10,
    /// taille P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Non pivoté.
    None = 0,
    /// Pivoté de 90 degrés dans le sens des aiguilles d'une montre.
    On90 = 1,
    /// Pivoté de 180 degrés.
    On180 = 2,
    /// Pivoté de 270 degrés dans le sens des aiguilles d'une montre.
    On270 = 3,
    /// Pivoté de 360 degrés dans le sens des aiguilles d'une montre.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 avec une longueur de clé de 40.
    RC4x40 = 0,
    /// RC4 avec une longueur de clé de 128.
    RC4x128 = 1,
    /// AES avec une longueur de clé de 128.
    AESx128 = 2,
    /// AES avec une longueur de clé de 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// format PDF/A-1a.
    PDF_A_1A = 0,
    /// format PDF/A-1b.
    PDF_A_1B = 1,
    /// format PDF/A-2a.
    PDF_A_2A = 2,
    /// format PDF/A-3a.
    PDF_A_3A = 3,
    /// format PDF/A-2b.
    PDF_A_2B = 4,
    /// format PDF/A-2u.
    PDF_A_2U = 5,
    /// format PDF/A-3b.
    PDF_A_3B = 6,
    /// format PDF/A-3u.
    PDF_A_3U = 7,
    /// version Adobe 1.0.
    V_1_0 = 8,
    /// version Adobe 1.1.
    V_1_1 = 9,
    /// version Adobe 1.2.
    V_1_2 = 10,
    /// version Adobe 1.3.
    V_1_3 = 11,
    /// version Adobe 1.4.
    V_1_4 = 12,
    /// version Adobe 1.5.
    V_1_5 = 13,
    /// version Adobe 1.6.
    V_1_6 = 14,
    /// version Adobe 1.7.
    V_1_7 = 15,
    /// norme ISO PDF 2.0.
    V_2_0 = 16,
    /// format PDF/UA-1.
    PDF_UA_1 = 17,
    /// format PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// format PDF/X-1a.
    PDF_X_1A = 19,
    /// format PDF/X-3.
    PDF_X_3 = 20,
    /// format ZUGFeRD.
    ZUGFeRD = 21,
    /// format PDF/A-4.
    PDF_A_4 = 22,
    /// format PDF/A-4e.
    PDF_A_4E = 23,
    /// format PDF/A-4f.
    PDF_A_4F = 24,
    /// format PDF/X-4.
    PDF_X_4 = 25,
    /// format PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Supprimer les éléments non conformes.
    Delete = 0,
    /// Ne rien faire, conserver les éléments non conformes.
    None = 1,
}
```

