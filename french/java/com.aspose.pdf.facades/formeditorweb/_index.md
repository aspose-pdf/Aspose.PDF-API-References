---
title: "FormEditorWeb"
linktitle: "FormEditorWeb"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour l'édition des formulaires (ajout/suppression de champs, etc.)"
type: docs
weight: 210
url: /fr/java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Classe pour l'édition des formulaires (ajout/suppression de champs, etc.)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Ajouter un champ du type spécifié au formulaire. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Ajouter un champ du type spécifié au formulaire. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Ajouter du JavaScript pour un champ PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Ajoute un nouvel élément à la zone de liste. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Ajoute un nouvel élément avec la valeur Export au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Ajoute un bouton de soumission sur le formulaire. |
| [close](#close--) | Ferme toutes les ressources utilisées par ce document. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copie un champ existant à la même position dans le numéro de page spécifié. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant à une nouvelle position spécifiée à la fois par le numéro de page et les ordonnées. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page original et les ordonnées. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées originales. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les ordonnées. |
| [decorateField](#decorateField--) | Modifie les attributs visuels de tous les champs du document PDF. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Modifie les attributs visuels de tous les champs avec le type de champ spécifié. |
| [decorateField](#decorateField-java.lang.String-) | Modifie les attributs visuels du champ spécifié. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Supprime l'élément du champ de liste. |
| [dispose](#dispose--) | Obsolète. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsolète. |
| [getDestStream](#getDestStream--) | Obtient le flux de destination. |
| [getExportItems](#getExportItems--) | Obtient les options pour la boîte combinée avec des valeurs d'exportation. |
| [getFacade](#getFacade--) | Obtient les attributs visuels du champ. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Obtenir les indicateurs du champ. |
| [getItems](#getItems--) | Renvoie le tableau d'éléments |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). |
| [getRadioGap](#getRadioGap--) | Obtenir le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| [getRadioHoriz](#getRadioHoriz--) | Obtenez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie. |
| [getResponse](#getResponse--) | Obtient l'objet Response où le résultat de l'opération sera stocké. |
| [getSaveOptions](#getSaveOptions--) | Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsolète. |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsolète. |
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
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Définit l'objet Response où le résultat de l'opération sera stocké. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsolète. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Définit le flux source. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Définit le drapeau de soumission du bouton. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Définir les drapeaux de soumission du bouton de soumission |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Définit l'URL du bouton. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Convertit un champ de texte à ligne unique en un champ à lignes multiples. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Constructeur pour FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Ajouter un champ du type spécifié au formulaire.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Ajouter un champ du type spécifié au formulaire.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Ajouter du JavaScript pour un champ PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Ajoute un nouvel élément à la zone de liste.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Ajoute un nouvel élément avec la valeur Export au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Ajoute un bouton de soumission sur le formulaire.

### close {#close--}
```
public void close()
```

Ferme toutes les ressources utilisées par ce document.

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
public void decorateField()
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
@Deprecated public void dispose()
```

Obsolète.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
Objet String

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

**Returns:**
Élément ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsolète.

**Returns:**
valeur de chaîne

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Obtient le flux de destination.

**Returns:**
Objet OutputStream

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Obtient les options pour la boîte combinée avec des valeurs d'exportation.

**Returns:**
Tableau String[][]

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Obtient les attributs visuels du champ.

**Returns:**
Objet FormFieldFacade

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Obtenir les indicateurs du champ.

### getItems {#getItems--}
```
public String [] getItems()
```

Renvoie le tableau d'éléments

**Returns:**
objet String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté).

**Returns:**
valeur double

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Obtenir le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50.

**Returns:**
Valeur flottante

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

Obtenez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie.

**Returns:**
valeur booléenne

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtient l'objet Response où le résultat de l'opération sera stocké.

**Returns:**
Objet HttpServletResponse

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsolète.

**Returns:**
valeur de chaîne

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtient le flux source.

**Returns:**
Objet InputStream

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
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
public void resetFacade()
```

Réinitialisez tous les attributs visuels à une valeur vide.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Réinitialisez tous les attributs visuels de la façade interne à une valeur vide.

### save {#save--}
```
public void save()
```

Enregistre les modifications dans le fichier de destination.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF PdfFormat.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsolète.

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
public void setRadioButtonItemSize(double value)
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Définissez le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Définissez le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est vraie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Définit l'objet Response où le résultat de l'opération sera stocké.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké sous forme de HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsolète.

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
