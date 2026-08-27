---
title: "IFormEditor"
linktitle: "IFormEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour éditer les formulaires (ajout/suppression de champs, etc.)"
type: docs
weight: 260
url: /fr/java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Classe pour éditer les formulaires (ajout/suppression de champs, etc.)

## Méthodes

| Méthode | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Ajouter un champ du type spécifié au formulaire. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Ajouter un champ du type spécifié au formulaire. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Ajoute un nouvel élément à la zone de liste. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Ajoute un nouvel élément avec la valeur Export au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Ajoute un bouton de soumission sur le formulaire. |
| [close](#close--) | Ferme l'objet |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copie un champ existant à la même position dans le numéro de page spécifié. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant à une nouvelle position spécifiée à la fois par le numéro de page et les ordonnées. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page original et les ordonnées. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées originales. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées. |
| [decorateField](#decorateField--) | Modifie les attributs visuels de tous les champs du document PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Modifie les attributs visuels de tous les champs avec le type de champ spécifié. |
| [decorateField](#decorateField-java.lang.String-) | Modifie les attributs visuels du champ spécifié. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Supprime l'élément du champ de liste. |
| [dispose](#dispose--) | Ferme l'objet |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtient le nom du fichier de destination. |
| [getDestStream](#getDestStream--) | Obtient le flux de destination. |
| [getDocument](#getDocument--) | Obtient le document sur lequel FormEditor travaille. |
| [getExportItems](#getExportItems--) | Obtient les options pour la boîte combinée avec des valeurs d'exportation. |
| [getFacade](#getFacade--) | Obtient les attributs visuels du champ. |
| [getItems](#getItems--) | Renvoie le tableau d'éléments |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| [getRadioGap](#getRadioGap--) | Obtenir le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| [getRadioHoriz](#getRadioHoriz--) | Obtenez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie. |
| [getSaveOptions](#getSaveOptions--) | Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtient le nom du fichier source. |
| [getSrcStream](#getSrcStream--) | Obtient le flux source. |
| [getSubmitFlag](#getSubmitFlag--) | Obtenir les indicateurs de soumission du bouton d'envoi |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Définissez la nouvelle position du champ. |
| [removeField](#removeField-java.lang.String-) | Supprimez le champ du formulaire. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Supprimez l'action de soumission du champ. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Modifiez le nom du champ. |
| [resetFacade](#resetFacade--) | Réinitialisez tous les attributs visuels à une valeur vide. |
| [resetInnerFacade](#resetInnerFacade--) | Réinitialisez tous les attributs visuels de la façade interne à une valeur vide. |
| [save](#save--) | Enregistre les modifications dans le fichier de destination. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format de fichier PDF PdfFormat. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Définit le nom du fichier de destination. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Définit le flux de destination. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Définit les options pour la boîte combinée avec des valeurs d'exportation. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Définit les attributs visuels du champ. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Définissez le style d'alignement d'un champ texte. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Définissez le style d'alignement vertical d'un champ texte. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Définissez les drapeaux du champ |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Définissez les attributs du champ. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Définit le nombre de créneaux pour un champ texte à ligne unique régulier (le champ est automatiquement divisé en autant de positions également espacées, ou créneaux, que la valeur du paramètre combNumber). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Définit le nombre maximal de caractères du champ texte. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Définissez le JavaScript pour un champ PushButton. |
| [setItems](#setItems-java.lang.String:A-) | Définit les éléments qui seront ajoutés à la liste déroulante ou à la boîte combinée nouvellement créées. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| [setRadioGap](#setRadioGap-float-) | Définissez le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Définissez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Définit le nom du fichier source. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Définit le flux source. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Définit le drapeau de soumission du bouton. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Définir les drapeaux de soumission du bouton de soumission |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Définit l'URL du bouton. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Convertit un champ de texte à ligne unique en un champ à lignes multiples. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Ajouter un champ du type spécifié au formulaire.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Ajouter un champ du type spécifié au formulaire.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Ajoute un nouvel élément à la zone de liste.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Ajoute un nouvel élément avec la valeur Export au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Ajoute un bouton de soumission sur le formulaire.

### close {#close--}
```
void close()
```

Ferme l'objet

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copie un champ existant à la même position dans le numéro de page spécifié.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copie un champ existant à une nouvelle position spécifiée à la fois par le numéro de page et les ordonnées.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page original et les ordonnées.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées originales.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées.

### decorateField {#decorateField--}
```
void decorateField()
```

Modifie les attributs visuels de tous les champs du document PDF.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Modifie les attributs visuels de tous les champs avec le type de champ spécifié.

### decorateField {#decorateField-java.lang.String-}
Modifie les attributs visuels du champ spécifié.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Supprime l'élément du champ de liste.

### dispose {#dispose--}
```
void dispose()
```

Ferme l'objet

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
Objet String

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

**Returns:**
Élément ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtient le nom du fichier de destination.

**Returns:**
valeur de chaîne

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Obtient le flux de destination.

**Returns:**
Objet OutputStream

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Obtient le document sur lequel FormEditor travaille.

**Returns:**
Objet IDocument

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Obtient les options pour la boîte combinée avec des valeurs d'exportation.

**Returns:**
Objet String[][]

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Obtient les attributs visuels du champ.

**Returns:**
Objet FormFieldFacade

### getItems {#getItems--}
```
String [] getItems()
```

Renvoie le tableau d'éléments

**Returns:**
objet String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté).

**Returns:**
valeur booléenne

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Obtenir le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50.

**Returns:**
Valeur flottante

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Obtenez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie.

**Returns:**
valeur booléenne

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtient le nom du fichier source.

**Returns:**
valeur de chaîne

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Obtient le flux source.

**Returns:**
Objet InputStream

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
```

Obtenir les indicateurs de soumission du bouton d'envoi

**Returns:**
Élément SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
Définissez la nouvelle position du champ.

### removeField {#removeField-java.lang.String-}
Supprimez le champ du formulaire.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Supprimez l'action de soumission du champ.

### renameField {#renameField-java.lang.String-java.lang.String-}
Modifiez le nom du champ.

### resetFacade {#resetFacade--}
```
void resetFacade()
```

Réinitialisez tous les attributs visuels à une valeur vide.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Réinitialisez tous les attributs visuels de la façade interne à une valeur vide.

### save {#save--}
```
void save()
```

Enregistre les modifications dans le fichier de destination.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Définit le nom du fichier de destination.

### setDestStream {#setDestStream-java.io.OutputStream-}
Définit le flux de destination.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Définit les options pour la boîte combinée avec des valeurs d'exportation.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Définit les attributs visuels du champ.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Définissez le style d'alignement d'un champ texte.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Définissez le style d'alignement vertical d'un champ texte.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Définissez les drapeaux du champ

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Définissez les attributs du champ.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Définit le nombre de créneaux pour un champ texte à ligne unique régulier (le champ est automatiquement divisé en autant de positions également espacées, ou créneaux, que la valeur du paramètre combNumber).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Définit le nombre maximal de caractères du champ texte.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Définissez le JavaScript pour un champ PushButton.

### setItems {#setItems-java.lang.String:A-}
Définit les éléments qui seront ajoutés à la liste déroulante ou à la boîte combinée nouvellement créées.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
void setRadioButtonItemSize(double value)
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Définissez le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Définissez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Définit le nom du fichier source.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Définit le flux source.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Définit le drapeau de soumission du bouton.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Définir les drapeaux de soumission du bouton de soumission

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Définit l'URL du bouton.

### single2Multiple {#single2Multiple-java.lang.String-}
Convertit un champ de texte à ligne unique en un champ à lignes multiples.
