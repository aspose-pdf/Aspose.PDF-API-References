---
title: "FormWeb"
linktitle: "FormWeb"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représentation de l'interface du formulaire Acro."
type: docs
weight: 230
url: /fr/java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Représentation de l'interface du formulaire Acro.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialise la façade. |
| [close](#close--) | Ferme toutes les ressources ouvertes utilisées par ce document. |
| [dispose](#dispose--) | Obsolète. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux xml. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrait le paquet de données XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Remplit un champ de code-barres selon son nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-boolean-) | Remplit le champ case à cocher avec une valeur booléenne. |
| [fillField](#fillField-java.lang.String-int-) | Remplit le champ bouton radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Remplit un champ avec plusieurs sélections. Note : uniquement pour le champ liste AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Remplit le champ avec la valeur spécifiée. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Surcharge la fonction FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié. |
| [flattenAllFields](#flattenAllFields--) | Aplatisse tous les champs. |
| [flattenField](#flattenField-java.lang.String-) | Aplatisse un champ spécifié avec le nom de champ entièrement qualifié. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Renvoie la valeur actuelle des champs d'option de bouton radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. |
| [getContentDisposition](#getContentDisposition--) | Le contenu Getshow sera stocké lorsque le résultat de l'opération sera stocké dans l'objet HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obsolète. |
| [getDestStream](#getDestStream--) | Obsolète. |
| [getField](#getField-java.lang.String-) | Obtient la valeur du champ selon son nom. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Renvoie l'objet FrohmFieldFacade contenant tous les attributs d'apparence. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Renvoie les indicateurs du champ. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtenez la limitation du champ texte. |
| [getFieldNames](#getFieldNames--) | Obtient la liste des noms de champs du formulaire. |
| [getFieldType](#getFieldType-java.lang.String-) | Renvoie le type du champ. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtient tous les noms des boutons de soumission du formulaire. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtient le nom complet du champ selon son nom court. |
| [getImportResult](#getImportResult--) | Résultat de la dernière opération d'importation. |
| [getResponse](#getResponse--) | Obtient ou définit l'objet Response où le résultat de l'opération sera stocké. |
| [getRichText](#getRichText-java.lang.String-) | Obtient la valeur d'un champ Rich Text, y compris les informations de formatage de chaque caractère. |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obsolète. |
| [getSrcStream](#getSrcStream--) | Obtient le flux source. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Renvoie les indicateurs de soumission du bouton d'envoi |
| [importFdf](#importFdf-java.io.InputStream-) | Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importe le contenu des champs depuis le fichier xfdf(xml) et les place dans le nouveau pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [importXml](#importXml-java.lang.String-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Détermine si le champ est obligatoire ou non. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renomme un champ. |
| [save](#save--) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format du fichier PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Obsolète. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obsolète. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Obtient ou définit l'objet Response où le résultat de l'opération sera stocké. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Obsolète. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtient le flux source. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Remplace les données XFA par le paquet de données spécifié. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Constructeur de FormWeb sans paramètres. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName(\"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialise la façade.

### close {#close--}
```
public void close()
```

Ferme toutes les ressources ouvertes utilisées par ce document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Obsolète.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux xml.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrait le paquet de données XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Remplit un champ de code-barres selon son nom de champ entièrement qualifié.

### fillField {#fillField-java.lang.String-boolean-}
Remplit le champ case à cocher avec une valeur booléenne.

### fillField {#fillField-java.lang.String-int-}
Remplit le champ bouton radio avec une valeur d'index valide selon un nom de champ entièrement qualifié.

### fillField {#fillField-java.lang.String-java.lang.String-}
Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Remplit un champ avec plusieurs sélections. Note : uniquement pour le champ liste AcroForm.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Remplit le champ avec la valeur spécifiée.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Surcharge la fonction FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Aplatisse tous les champs.

### flattenField {#flattenField-java.lang.String-}
Aplatisse un champ spécifié avec le nom de champ entièrement qualifié.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
objet string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Renvoie la valeur actuelle des champs d'option de bouton radio.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ.

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Le contenu Getshow sera stocké lorsque le résultat de l'opération sera stocké dans l'objet HttpResponse.

**Returns:**
Élément ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obsolète.

**Returns:**
Objet String

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obsolète.

**Returns:**
Objet OutputStream

### getField {#getField-java.lang.String-}
Obtient la valeur du champ selon son nom.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Renvoie l'objet FrohmFieldFacade contenant tous les attributs d'apparence.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Renvoie les indicateurs du champ.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Obtenez la limitation du champ texte.

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Obtient la liste des noms de champs du formulaire.

**Returns:**
objet String[]

### getFieldType {#getFieldType-java.lang.String-}
Renvoie le type du champ.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Obtient tous les noms des boutons de soumission du formulaire.

**Returns:**
objet String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtient le nom complet du champ selon son nom court.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Résultat de la dernière opération d'importation.

**Returns:**
FormImportResult[] tableau

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Obtient ou définit l'objet Response où le résultat de l'opération sera stocké.

**Returns:**
Objet HttpServletResponse

### getRichText {#getRichText-java.lang.String-}
Obtient la valeur d'un champ Rich Text, y compris les informations de formatage de chaque caractère.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Obsolète.

**Returns:**
Objet String

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtient le flux source.

**Returns:**
Objet InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Renvoie les indicateurs de soumission du bouton d'envoi

### importFdf {#importFdf-java.io.InputStream-}
Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf.

### importXfdf {#importXfdf-java.io.InputStream-}
Importe le contenu des champs depuis le fichier xfdf(xml) et les place dans le nouveau pdf.

### importXml {#importXml-java.io.InputStream-}
Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf.

### importXml {#importXml-java.io.InputStream-boolean-}
Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf.

### importXml {#importXml-java.lang.String-}
Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf.

### isRequiredField {#isRequiredField-java.lang.String-}
Détermine si le champ est obligatoire ou non.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renomme un champ.

### save {#save--}
```
public void save()
```

<p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format du fichier PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Obsolète.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obsolète.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Obtient ou définit l'objet Response où le résultat de l'opération sera stocké.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Obsolète.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtient le flux source.

### setXfaData {#setXfaData-java.io.InputStream-}
Remplace les données XFA par le paquet de données spécifié.
