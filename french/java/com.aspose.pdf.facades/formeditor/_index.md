---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe pour éditer les formulaires (ajout/suppression de champs, etc.)"
type: docs
weight: 200
url: /fr/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Classe pour éditer les formulaires (ajout/suppression de champs, etc.)

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Ajouter un champ du type spécifié au formulaire. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Ajouter un champ du type spécifié au formulaire. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Ajouter du JavaScript pour un champ PushButton. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Ajoute un nouvel élément à la zone de liste. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Ajouter un nouvel élément avec valeur d'exportation au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Ajouter un bouton de soumission au formulaire. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Fermer l'instance d'objet |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera créé, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant vers une nouvelle position spécifiée à la fois par le numéro de page et les coordonnées. Un nouveau document sera créé, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les cases radio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les cases radio). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées spécifiés. Remarque : uniquement pour les champs AcroForm (excluant les cases radio). |
| [decorateField](#decorateField--) | <p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Supprimer l'élément du champ de liste. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | Fermer l'instance d'objet Cette méthode est obsolète, utilisez close() à la place. |
| [getAttachmentName](#getAttachmentName--) | Obtient le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [getContentDisposition](#getContentDisposition--) | Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline. |
| [getDestFileName](#getDestFileName--) | Obtient le nom du fichier de destination. |
| [getDestStream](#getDestStream--) | <p> Obtient le flux de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | Obtient le document {@code FormEditor} sur lequel il travaille. |
| [getExportItems](#getExportItems--) | <p> Obtient les options pour la zone combinée avec des valeurs d'exportation. </p> <hr> |
| [getFacade](#getFacade--) | Obtient les attributs visuels du champ. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Obtenir les indicateurs du champ. |
| [getItems](#getItems--) | Obtenir les éléments qui seront ajoutés à la nouvelle boîte de liste ou zone combinée. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Obtenir le membre qui enregistre l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Obtenir le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est true. |
| [getSaveOptions](#getSaveOptions--) | Obtient les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Obtient le nom du fichier source. |
| [getSrcStream](#getSrcStream--) | Obtient le flux source. |
| [getSubmitFlag](#getSubmitFlag--) | Obtenir les indicateurs de soumission du bouton d'envoi |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Définir la nouvelle position du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Supprimer le champ du formulaire. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Supprimer l'action d'envoi du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Modifier le nom du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | Réinitialiser tous les attributs visuels à une valeur vide. |
| [resetInnerFacade](#resetInnerFacade--) | Réinitialiser tous les attributs visuels de la façade interne à une valeur vide. |
| [save](#save--) | Enregistre les modifications dans le fichier de destination. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Définit le format de fichier PDF {@link PdfFormat}. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Définit le nom du fichier de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Définit le flux de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Définit les options pour la boîte combinée avec des valeurs d'exportation. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Définit les attributs visuels du champ. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Définit le style d'alignement d'un champ texte. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Définit le style d'alignement vertical d'un champ texte. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Définit les attributs du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Définit le nombre de créneaux pour un champ texte à ligne unique standard (le champ est automatiquement divisé en autant de positions également espacées, ou créneaux, que la valeur du paramètre combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Définit le nombre maximal de caractères du champ texte. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Définit le JavaScript pour un champ PushButton. Si un ancien JavaScript existait, il sera remplacé par le nouveau. |
| [setItems](#setItems-java.lang.String:A-) | <p> Définit les éléments qui seront ajoutés à la liste ou à la boîte combinée nouvellement créées. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Définit le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Définissez le drapeau pour indiquer si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Définit le nom du fichier source. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Définit le flux source. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Définit le drapeau de soumission du bouton de soumission. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Définir les drapeaux de soumission du bouton de soumission |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Définit l'URL du bouton. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Convertit un champ texte à ligne unique en un champ texte à plusieurs lignes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Constructeur pour FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Ajouter un champ du type spécifié au formulaire. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Ajouter un champ du type spécifié au formulaire.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Ajouter du JavaScript pour un champ PushButton.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Ajoute un nouvel élément à la zone de liste. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Ajouter un nouvel élément avec valeur d'exportation au champ de zone de liste existant, uniquement pour le champ de zone de liste déroulante AcroForm. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Ajouter un bouton de soumission au formulaire. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Fermer l'instance d'objet

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copie un champ existant à la même position dans le numéro de page spécifié. Un nouveau document sera créé, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copie un champ existant vers une nouvelle position spécifiée à la fois par le numéro de page et les coordonnées. Un nouveau document sera créé, contenant tout ce que le document source possède, à l'exception du champ nouvellement copié.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les cases radio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page spécifié et les coordonnées d'origine. Remarque : uniquement pour les champs AcroForm (excluant les cases radio).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copie un champ existant d'un document PDF à un autre document avec le numéro de page et les coordonnées spécifiés. Remarque : uniquement pour les champs AcroForm (excluant les cases radio).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Modifie les attributs visuels de tous les champs du document PDF. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Supprimer l'élément du champ de liste. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Fermer l'instance d'objet Cette méthode est obsolète, utilisez close() à la place.

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

Obtient la façon dont le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Valeur par défaut : inline.

**Returns:**
Élément ContentDisposition @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Obtient le nom du fichier de destination.

**Returns:**
objet string

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Obtient le flux de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
Objet OutputStream

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Obtient le document {@code FormEditor} sur lequel il travaille.

**Returns:**
Objet IDocument

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Obtient les options pour la zone combinée avec des valeurs d'exportation. </p> <hr>

**Returns:**
Objet String[][]

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

Obtenir les éléments qui seront ajoutés à la nouvelle boîte de liste ou zone combinée.

**Returns:**
objet String[]

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

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

<p> Obtenir le drapeau indiquant si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est true.

**Returns:**
valeur booléenne

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtient les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

**Returns:**
Objet SaveOptions

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Obtient le nom du fichier source.

**Returns:**
objet string

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
Élément SubmitFormFlag @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Définir la nouvelle position du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Supprimer le champ du formulaire. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Supprimer l'action d'envoi du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Modifier le nom du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Réinitialiser tous les attributs visuels à une valeur vide.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Réinitialiser tous les attributs visuels de la façade interne à une valeur vide.

### save {#save--}
```
@Deprecated public void save()
```

Enregistre les modifications dans le fichier de destination.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Définit le nom de la pièce jointe lorsque le résultat de l'opération est stocké dans des objets HttpResponse en tant que pièce jointe.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Définit comment le contenu sera stocké lorsque le résultat de l'opération est stocké dans un objet HttpResponse. Valeur possible : inline / attachment. Par défaut : inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Définit le format de fichier PDF {@link PdfFormat}. Le fichier résultant sera enregistré dans le format de fichier spécifié. Si cette propriété n'est pas spécifiée, le fichier sera enregistré au format PDF par défaut sans conversion.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Définit le nom du fichier de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName(\"OutFile.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Définit le flux de destination. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Définit les options pour la boîte combinée avec des valeurs d'exportation. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_Updated.pdf\")); formEditor.setExportItems ( new String[][] { new String[] { \"1\", \"Firs\" }, new String[] { \"2\", \"Second\" }, new String[] { \"3\", \"Third\" } }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Définit les attributs visuels du champ. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"PdfForm_DecorateField_text.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField(\"textField\"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Définit le style d'alignement d'un champ texte. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_updated.pdf\")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Définit le style d'alignement vertical d'un champ texte. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfStaticForm.pdf\", \"VerticalAlign.pdf\"); fe.setFieldAlignmentV(\"form1[0].TextField[0]\", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Définit les drapeaux du champ </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Définit les attributs du champ. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_SetFieldAttribute.pdf\"); formEditor.setFieldAttribute(\"listboxField\", PropertyFlag.ReadOnly); formEditor.setFieldAttribute(\"textField\", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Définit le nombre de créneaux pour un champ texte à ligne unique standard (le champ est automatiquement divisé en autant de positions également espacées, ou créneaux, que la valeur du paramètre combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfWithAcroForm.pdf\", \"FormEditor_SetFieldComb.pdf\")); formEditor.setFieldCombNumber(\"textCombField\", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Définit le nombre maximal de caractères du champ texte. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetFieldLimit.pdf\"); formEditor.setFieldLimit(\"textField\", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Définit le JavaScript pour un champ PushButton. Si un ancien JavaScript existait, il sera remplacé par le nouveau.

### setItems {#setItems-java.lang.String:A-}
<p> Définit les éléments qui seront ajoutés à la liste ou à la boîte combinée nouvellement créées. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Obtient ou définit la taille de l'élément du bouton radio (lorsqu'un nouveau champ de bouton radio est ajouté). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Définit le membre pour enregistrer l'écart entre deux boutons radio voisins en pixels, la valeur par défaut est 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Définissez le drapeau pour indiquer si les boutons radio sont disposés horizontalement ou verticalement, la valeur par défaut est true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Définit les options d'enregistrement lorsque le résultat est stocké en tant que HttpResponse. Valeur par défaut : PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Définit le nom du fichier source. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName("InputFile.pdf"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Définit le flux source. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream("InFile.pdf")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Définit le drapeau de soumission du bouton de soumission. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf"); formEditor.setSubmitFlag("btnSubmit", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Définir les drapeaux de soumission du bouton de soumission

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Définit l'URL du bouton. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf"); formEditor.setSubmitUrl("btnSubmit", "www.mysite.com"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Convertit un champ texte à ligne unique en un champ texte à plusieurs lignes. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.single2Multiple("textField"); </pre>
