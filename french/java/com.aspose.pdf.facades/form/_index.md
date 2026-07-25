---
title: "Formulaire"
linktitle: "Formulaire"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'objet de formulaire Acro."
type: docs
weight: 170
url: /fr/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Classe représentant l'objet de formulaire Acro.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Form](#Form--) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initialise la façade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initialise la façade. |
| [close](#close--) | Ferme les fichiers ouverts sans aucune modification. |
| [dispose](#dispose--) | Ferme toutes les ressources ouvertes. Cette méthode est obsolète, utilisez close() à la place. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exporte le contenu des champs du PDF vers le flux fdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exporte le contenu des champs du PDF vers le flux xml. La valeur du champ bouton ne sera pas exportée. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exporte le contenu des champs du PDF vers le flux xml. La valeur du champ bouton ne sera pas exportée. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extrait le paquet de données XFA |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Remplit un champ de code-barres selon son nom de champ pleinement qualifié. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Remplit le champ case à cocher avec une valeur booléenne. Remarque : ne s'applique qu'aux cases à cocher. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField" vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Remplit le champ de case à cocher radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, seul le nom du champ doit être connu. La valeur peut être spécifiée par son index. Remarque : Applicable uniquement aux champs Radio Box, Combo Box et List Box. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, les noms de tous les champs et leurs valeurs valides correspondantes doivent être connus. Les noms et les valeurs des champs sont sensibles à la casse. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "TextField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Remplit un champ avec plusieurs sélections. Remarque : uniquement pour le champ List Box d'AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Remplit le champ avec la valeur spécifiée. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Surcharge la fonction FillImageField. L'entrée est un flux d'image. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Aplati tous les champs. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Aplati un champ spécifié avec le nom de champ entièrement qualifié. Tout autre champ restera inchangé. Si le fieldName est invalide, tous les champs resteront inchangés. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Renvoie la valeur actuelle des champs d'option de bouton radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a du sens pour les groupes de boutons radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Obtient les champs d'options de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a un sens pour les groupes de boutons radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Obtient ou définit comment le contenu sera stocké lorsque le résultat de l'opération est enregistré dans l'objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline. |
| [getDestFileName](#getDestFileName--) | Obtient le nom du fichier de destination. |
| [getDestStream](#getDestStream--) | Obtient ou définit le flux de destination. |
| [getField](#getField-java.lang.String-) | <p> Obtient la valeur du champ selon son nom. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Retourne un objet FormFieldFacade contenant tous les attributs d'apparence. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Retourne les indicateurs du champ. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Obtient la limitation du champ texte. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Obtient la liste des noms de champs du formulaire. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Retourne le type du champ. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Obtient tous les noms des boutons de soumission du formulaire. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Obtient le nom complet du champ en fonction de son nom court. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre> |
| [getImportResult](#getImportResult--) | Résultat de la dernière opération d'importation. Tableau d'objets décrivant le résultat de l'importation pour chaque champ. |
| [getRichText](#getRichText-java.lang.String-) | <p> Obtient la valeur d'un champ texte enrichi, y compris les informations de formatage de chaque caractère. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Obtient le nom du fichier source. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre> |
| [getSrcStream](#getSrcStream--) | Obtient le flux source. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Importe le contenu des champs depuis le fichier xfdf (xml) et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. |
| [importXml](#importXml-java.lang.String-) | <p> Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Détermine si le champ est obligatoire ou non. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Renomme un champ. Un champ AcroForm ou XFA convient. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Enregistre la valeur des champs remplis et ferme le document Pdf ouvert. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Définit le nom du fichier de destination. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Obtient le flux de destination. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Définit le nom du fichier source. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Obtient le flux source. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Remplace les données XFA par le paquet de données spécifié. Le paquet de données peut être extrait à l'aide de ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Constructeur de Form sans paramètres. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initialise la façade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initialise la façade.

### close {#close--}
```
public void close()
```

Ferme les fichiers ouverts sans aucune modification.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Ferme toutes les ressources ouvertes. Cette méthode est obsolète, utilisez close() à la place.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exporte le contenu des champs du PDF vers le flux fdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exporte le contenu des champs du PDF vers le flux xml. La valeur du champ bouton ne sera pas exportée. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exporte le contenu des champs du PDF vers le flux xml. La valeur du champ bouton ne sera pas exportée. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extrait le paquet de données XFA

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Remplit un champ de code-barres selon son nom de champ pleinement qualifié. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Remplit le champ case à cocher avec une valeur booléenne. Remarque : ne s'applique qu'aux cases à cocher. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.CheckBoxField" vous devez spécifier le nom complet et non "CheckBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Remplit le champ de case à cocher radio avec une valeur d'index valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, seul le nom du champ doit être connu. La valeur peut être spécifiée par son index. Remarque : Applicable uniquement aux champs Radio Box, Combo Box et List Box. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.ListBoxField", vous devez spécifier le nom complet et non "ListBoxField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Remplit le champ avec une valeur valide selon un nom de champ entièrement qualifié. Avant de remplir les champs, les noms de tous les champs et leurs valeurs valides correspondantes doivent être connus. Les noms et les valeurs des champs sont sensibles à la casse. Veuillez noter que Facades ne prend en charge que les noms de champs complets et ne fonctionne pas avec des noms de champs partiels, contrairement à Aspose.Pdf.Kit ; par exemple, si le champ a le nom complet "Form.Subform.TextField", vous devez spécifier le nom complet et non "TextField". Vous pouvez utiliser la propriété FieldNames pour explorer les noms de champs existants et rechercher le champ requis par son nom partiel. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Remplit un champ avec plusieurs sélections. Remarque : uniquement pour le champ List Box d'AcroForm. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Remplit le champ avec la valeur spécifiée.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Remplit les champs de zone de texte avec des valeurs textuelles et enregistre le document.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Surcharge la fonction FillImageField. L'entrée est un flux d'image. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Colle une image sur le champ bouton existant comme son apparence selon son nom de champ entièrement qualifié. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Aplati tous les champs. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Aplati un champ spécifié avec le nom de champ entièrement qualifié. Tout autre champ restera inchangé. Si le fieldName est invalide, tous les champs resteront inchangés. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

**Returns:**
objet string

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Renvoie la valeur actuelle des champs d'option de bouton radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Obtient les champs d'option de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a du sens pour les groupes de boutons radio. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Obtient les champs d'options de bouton radio et les valeurs associées en fonction du nom du champ. Cette méthode a un sens pour les groupes de boutons radio. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); Hashtable values = form.getButtonOptionValues(\"Color\"); System.out.println(values[\"White\"].toString()); System.out.println(values[\"Black\"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtient ou définit comment le contenu sera stocké lorsque le résultat de l'opération est enregistré dans l'objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline.

**Returns:**
Élément ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Obtient le nom du fichier de destination.

**Returns:**
objet string

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Obtient ou définit le flux de destination.

**Returns:**
Objet OutputStream

### getField {#getField-java.lang.String-}
<p> Obtient la valeur du champ selon son nom. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Field value = \" + form.getField(\"Field1\")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Retourne un objet FormFieldFacade contenant tous les attributs d'apparence. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form(\"form.pdf\")); FormFieldFacade field = form.getFieldFacade(\"field1\"); System.out.println(\"Color of field border: \" + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Retourne les indicateurs du champ. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldFlag(\"textField\") == ProptyFlag.ReadOnly) { System.out.println(\"Field is read-only\"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Obtient la limitation du champ texte. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getFieldLimit(\"textfieldBox\")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Obtient la liste des noms de champs du formulaire. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
objet String[]

### getFieldType {#getFieldType-java.lang.String-}
<p> Retourne le type du champ. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); if (form.getFieldType(\"textField\") == FieldType.Text) { System.out.println(\"Type of field is text\"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Obtient tous les noms des boutons de soumission du formulaire. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
objet String[]

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Obtient le nom complet du champ en fonction de son nom court. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(\"Full field name is : \" + form.getFullFieldName(\"textField\")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Résultat de la dernière opération d'importation. Tableau d'objets décrivant le résultat de l'importation pour chaque champ.

**Returns:**
FormImportResult[] tableau

### getRichText {#getRichText-java.lang.String-}
<p> Obtient la valeur d'un champ texte enrichi, y compris les informations de formatage de chaque caractère. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.getRichText(\"txtDescriptionRTF\")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Obtient le nom du fichier source. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName(\"file.pdf\"); </pre>

**Returns:**
objet string

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Obtient le flux source.

**Returns:**
Objet InputStream

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Retourne les indicateurs de soumission du bouton de soumission </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_imported.pdf\"); form.importFdf(new FileInputStream(\"data.fdf\")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Importe le contenu des champs depuis le fichier xfdf (xml) et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"Form_ImportXfdf.pdf\"); InputStream fs = new FileInputStream(\"export_old.xfdf\"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); InputStream fs = new FileInputStream(\"import.xml\"); form.importXml(fs); form.save(\"Form_Imported.pdf\"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf.

### importXml {#importXml-java.lang.String-}
<p> Importe le contenu des champs depuis le fichier xml et les place dans le nouveau pdf. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.importXml(\"import.xml\"); form.save( \"Form_Imported.pdf\"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Détermine si le champ est obligatoire ou non.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Renomme un champ. Un champ AcroForm ou XFA convient. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

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
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Définit le nom du fichier de destination. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Obtient le flux de destination. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Obtient ou définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Définit le nom du fichier source.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Obtient le flux source. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Remplace les données XFA par le paquet de données spécifié. Le paquet de données peut être extrait à l'aide de ExtractXfaData.
