---
title: "IForm"
linktitle: "IForm"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'objet de formulaire Acro."
type: docs
weight: 250
url: /fr/java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Classe représentant l'objet de formulaire Acro.

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Ferme les fichiers ouverts sans aucune modification. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux fdf. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux xml. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exporte le contenu des champs du pdf vers le flux xml. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Remplit un champ de code-barres selon son nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-boolean-) | Remplit le champ case à cocher avec une valeur booléenne. |
| [fillField](#fillField-java.lang.String-int-) | Remplit le champ bouton radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Remplit un champ avec plusieurs sélections. Note : uniquement pour le champ liste AcroForm. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Surcharge la fonction FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié. |
| [flattenAllFields](#flattenAllFields--) | Aplatisse tous les champs. |
| [flattenField](#flattenField-java.lang.String-) | Aplatisse un champ spécifié avec le nom de champ entièrement qualifié. |
| [getAttachmentName](#getAttachmentName--) | Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Renvoie la valeur actuelle des champs d'option de bouton radio. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. |
| [getContentDisposition](#getContentDisposition--) | Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. |
| [getDestFileName](#getDestFileName--) | Obtient le nom du fichier de destination. |
| [getDestStream](#getDestStream--) | Obtient le flux de destination. |
| [getDocument](#getDocument--) | Obtient le formulaire du document sur lequel travaille. |
| [getField](#getField-java.lang.String-) | Obtient la valeur du champ selon son nom. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Renvoie l'objet FrohmFieldFacade contenant tous les attributs d'apparence. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Renvoie les indicateurs du champ. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Obtenez la limitation du champ texte. |
| [getFieldNames](#getFieldNames--) | Obtient la liste des noms de champs du formulaire. |
| [getFieldType](#getFieldType-java.lang.String-) | Renvoie le type du champ. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Obtient tous les noms des boutons de soumission du formulaire. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Obtient le nom complet du champ selon son nom court. |
| [getRichText](#getRichText-java.lang.String-) | Obtient la valeur d'un champ Rich Text, y compris les informations de formatage de chaque caractère. |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Obtient le nom du fichier source. |
| [getSrcStream](#getSrcStream--) | Obtient le flux source. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Renvoie les indicateurs de soumission du bouton d'envoi |
| [importFdf](#importFdf-java.io.InputStream-) | Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Importe le contenu des champs depuis le fichier xfdf(xml) et les place dans le nouveau pdf. |
| [importXml](#importXml-java.io.InputStream-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renomme un champ. |
| [save](#save--) | Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format du fichier PDF. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Définit le nom du fichier de destination. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Obtient le flux de destination. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Définit le nom du fichier source. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Obtient le flux source. |

### close {#close--}
```
void close()
```

Ferme les fichiers ouverts sans aucune modification.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux fdf.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux xml.

### exportXml {#exportXml-java.io.OutputStream-}
Exporte le contenu des champs du pdf vers le flux xml.

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Surcharge la fonction FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Aplatisse tous les champs.

### flattenField {#flattenField-java.lang.String-}
Aplatisse un champ spécifié avec le nom de champ entièrement qualifié.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Obtient ou définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

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
ContentDisposition getContentDisposition()
```

Obtient ou définit la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse.

**Returns:**
Élément ContentDisposition

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Obtient le nom du fichier de destination.

**Returns:**
Objet String

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

Obtient le formulaire du document sur lequel travaille.

**Returns:**
Objet IDocument

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
String [] getFieldNames()
```

Obtient la liste des noms de champs du formulaire.

**Returns:**
objet String[]

### getFieldType {#getFieldType-java.lang.String-}
Renvoie le type du champ.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Obtient tous les noms des boutons de soumission du formulaire.

**Returns:**
objet String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
Obtient le nom complet du champ selon son nom court.

### getRichText {#getRichText-java.lang.String-}
Obtient la valeur d'un champ Rich Text, y compris les informations de formatage de chaque caractère.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Obtient le nom du fichier source.

**Returns:**
Objet String

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
Renomme un champ.

### save {#save--}
```
void save()
```

Enregistre la valeur des champs remplis et ferme le document Pdf ouvert.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans l'objet HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format du fichier PDF.

### setDestFileName {#setDestFileName-java.lang.String-}
Définit le nom du fichier de destination.

### setDestStream {#setDestStream-java.io.OutputStream-}
Obtient le flux de destination.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Définit le nom du fichier source.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Obtient le flux source.
