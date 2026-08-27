---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass för att redigera formulär (lägga till/ta bort fält etc)"
type: docs
weight: 200
url: /sv/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Klass för att redigera formulär (lägga till/ta bort fält etc)

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Lägg till fält av angiven typ i formuläret. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Lägg till fält av angiven typ i formuläret. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Lägg till JavaScript för ett PushButton‑fält. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Lägger till ett nytt objekt i listrutan. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Lägg till ett nytt objekt med Export‑värde till det befintliga listrutfältet, endast för AcroForm‑kombinationsruta. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Lägg till en skicka‑knapp i formuläret. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Stäng objektinstans |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar). |
| [decorateField](#decorateField--) | <p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Ta bort objekt från listfältet. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre> |
| [dispose](#dispose--) | Stäng objektinstansen Denna metod är föråldrad, använd close() istället. |
| [getAttachmentName](#getAttachmentName--) | Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [getContentDisposition](#getContentDisposition--) | Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline. |
| [getDestFileName](#getDestFileName--) | Hämtar destinationsfilens namn. |
| [getDestStream](#getDestStream--) | <p> Hämtar destinationsström. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre> |
| [getDocument](#getDocument--) | Hämtar dokumentet {@code FormEditor} arbetar med. |
| [getExportItems](#getExportItems--) | <p> Hämtar alternativ för kombinationsruta med exportvärden. </p> <hr> |
| [getFacade](#getFacade--) | Hämtar visuella attribut för fältet. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Hämta fältflaggor. |
| [getItems](#getItems--) | Hämta objekt som kommer att läggas till i den nyskapade listrutan eller kombinationsrutan. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Hämtar eller anger storleken på radioknappens objektstorlek (när ett nytt radioknappsfält läggs till). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true. |
| [getSaveOptions](#getSaveOptions--) | Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Hämtar namn på källfilen. |
| [getSrcStream](#getSrcStream--) | Hämtar källström. |
| [getSubmitFlag](#getSubmitFlag--) | Hämta skicka-knappens inskickningsflaggor |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Ställ in ny position för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Ta bort fält från formuläret. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Ta bort skickaåtgärden för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Ändra namn på fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre> |
| [resetFacade](#resetFacade--) | Återställ alla visuella attribut till tomt värde. |
| [resetInnerFacade](#resetInnerFacade--) | Återställ alla visuella attribut för den inre facaden till tomt värde. |
| [save](#save--) | Sparar ändringar i destinationsfilen. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Ställer in {@link PdfFormat} PDF-filformat. Resultatfilen sparas i det angivna filformatet. Om denna egenskap inte specificeras sparas filen i standard PDF-format utan konvertering. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Ställer in destinationsfilens namn. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Ställer in destinationsström. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Ställer in alternativ för kombinationsruta med exportvärden. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Ställer in visuella attribut för fältet. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Ställ in justeringsstil för ett textfält. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Ställ in vertikal justeringsstil för ett textfält. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Ställ in attribut för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Ställer in antal kombinationer för ett vanligt enkelradigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller kombinationer, som värdet på parametern combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Ställer in maximalt teckenantal för textfältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Ställ in JavaScript för ett PushButton-fält. Om tidigare JavaScript fanns, ersätts det med den nya. |
| [setItems](#setItems-java.lang.String:A-) | <p> Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Hämtar eller anger storleken på radioknappens objektstorlek (när ett nytt radioknappsfält läggs till). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> Ställ in medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Ställ in flaggan för att ange om radioknapparna är ordnade horisontellt eller vertikalt, standardvärdet är true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Ställer in namn på källfilen. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Ställer in källströmmen. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Ställ in inskickningsflagga för inskickningsknappen. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Ställ in inskickningsknappens inskickningsflaggor |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Ställer in URL för knappen. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Ändra ett enradigt textfält till ett flerradigt. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> Konstruktor för FormEditor. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Lägg till fält av angiven typ i formuläret. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Lägg till fält av angiven typ i formuläret.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Lägg till JavaScript för ett PushButton‑fält.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Lägger till ett nytt objekt i listrutan. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Lägg till ett nytt objekt med Export‑värde till det befintliga listrutfältet, endast för AcroForm‑kombinationsruta. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Lägg till en skicka‑knapp i formuläret. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Stäng objektinstans

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Kopierar ett befintligt fält till samma position på angivet sidnummer. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Kopierar ett befintligt fält till en ny position som specificeras av både sidnummer och koordinater. Ett nytt dokument kommer att skapas, som innehåller allt som källdokumentet har förutom det nykopierade fältet.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med originalt sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och originalkoordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Kopierar ett befintligt fält från ett PDF‑dokument till ett annat dokument med angivet sidnummer och koordinater. Observera: Endast för AcroForm‑fält (exklusive radioknappar).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> Ändrar visuella attribut för alla fält i PDF-dokumentet. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Ta bort objekt från listfältet. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_DelListItem.pdf\"); formEditor.delListItem(\"listboxField\", \"item2\"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Stäng objektinstansen Denna metod är föråldrad, använd close() istället.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Hämtar namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

**Returns:**
String-objekt

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Hämtar hur innehållet kommer att lagras när resultatet av operationen lagras i HttpResponse-objektet. Möjligt värde: inline / attachment. Standard: inline.

**Returns:**
ContentDisposition-element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Hämtar destinationsfilens namn.

**Returns:**
string‑objekt

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Hämtar destinationsström. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream(\"OutFile.pdf\")); </pre>

**Returns:**
OutputStream objekt

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Hämtar dokumentet {@code FormEditor} arbetar med.

**Returns:**
IDocument-objekt

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Hämtar alternativ för kombinationsruta med exportvärden. </p> <hr>

**Returns:**
String[][]-objekt

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Hämtar visuella attribut för fältet.

**Returns:**
FormFieldFacade-objekt

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Hämta fältflaggor.

### getItems {#getItems--}
```
public String [] getItems()
```

Hämta objekt som kommer att läggas till i den nyskapade listrutan eller kombinationsrutan.

**Returns:**
String[] objekt

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Hämtar eller anger storleken på radioknappens objektstorlek (när ett nytt radioknappsfält läggs till). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
double-värde

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Hämta medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50.

**Returns:**
flyttalsvärde

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> Hämta flaggan som indikerar om radioknapparna är placerade horisontellt eller vertikalt, standardvärdet är true.

**Returns:**
booleskt värde

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Hämtar sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

**Returns:**
SaveOptions-objekt

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Hämtar namn på källfilen.

**Returns:**
string‑objekt

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Hämtar källström.

**Returns:**
InputStream-objekt

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Hämta skicka-knappens inskickningsflaggor

**Returns:**
SubmitFormFlag-element @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Ställ in ny position för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_MoveField.pdf\"); formEditor.moveField(\"textField\", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Ta bort fält från formuläret. </p> <hr> <pre> FormEditr formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveField.pdf\"); formEditor.removeField(\"listboxField\"); formEditor.removeField(\"textField\"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Ta bort skickaåtgärden för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_RemoveFieldAction.pdf\"); formEditor.removeFieldAction(\"btnSubmit\"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Ändra namn på fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.renameField(\"textField\", \"textField_Renamed\"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Återställ alla visuella attribut till tomt värde.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Återställ alla visuella attribut för den inre facaden till tomt värde.

### save {#save--}
```
@Deprecated public void save()
```

Sparar ändringar i destinationsfilen.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Ställer in namn på bilagan när resultatet av operationen lagras i HttpResponse-objekt som bilaga.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Ställer in hur innehållet ska lagras när resultatet av operationen lagras i ett HttpResponse-objekt. Möjligt värde: inline / attachment. Standard: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Ställer in {@link PdfFormat} PDF-filformat. Resultatfilen sparas i det angivna filformatet. Om denna egenskap inte specificeras sparas filen i standard PDF-format utan konvertering.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Ställer in destinationsfilens namn. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Ställer in destinationsström. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Ställer in alternativ för kombinationsruta med exportvärden. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Ställer in visuella attribut för fältet. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Ställ in justeringsstil för ett textfält. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Ställ in vertikal justeringsstil för ett textfält. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Ställ in fältflaggor </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm1.pdf\", \"FormEditor_SetFieldAppearance.pdf\"); formEditor.setFieldAppearance(\"Name\", AnnotationFlags.Hidden); formEditor.setFieldAppearance(\"Phone\", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Ställ in attribut för fältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Ställer in antal kombinationer för ett vanligt enkelradigt textfält (fältet delas automatiskt upp i lika många jämnt fördelade positioner, eller kombinationer, som värdet på parametern combNumber). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Ställer in maximalt teckenantal för textfältet. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Ställ in JavaScript för ett PushButton-fält. Om tidigare JavaScript fanns, ersätts det med den nya.

### setItems {#setItems-java.lang.String:A-}
<p> Ställer in objekt som kommer att läggas till i en ny skapad listbox eller kombinationsruta. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor(\"input.pdf\", \"output.pdf\"); formEditor.setItems(new String[] { \"AAA\", \"BBB\", \"CCC\" }); formEditor.addField(FieldType.ListBox, \"AddedListBoxField\", \"BBB\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Hämtar eller anger storleken på radioknappens objektstorlek (när ett nytt radioknappsfält läggs till). FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | double-värde |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> Ställ in medlemmen för att registrera avståndet mellan två intilliggande radioknappar i pixlar, standard är 50. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | flyttalsvärde |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Ställ in flaggan för att ange om radioknapparna är ordnade horisontellt eller vertikalt, standardvärdet är true. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Ställer in sparalternativ när resultatet lagras som HttpResponse. Standardvärde: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Ställer in namn på källfilen. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Ställer in källströmmen. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Ställ in inskickningsflagga för inskickningsknappen. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Ställ in inskickningsknappens inskickningsflaggor

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Ställer in URL för knappen. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Ändra ett enradigt textfält till ett flerradigt. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre>
