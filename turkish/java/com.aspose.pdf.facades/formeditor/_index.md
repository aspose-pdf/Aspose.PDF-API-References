---
title: "FormEditor"
linktitle: "FormEditor"
second_title: "Aspose.PDF for Java API Referansı"
description: "Formları düzenlemek için sınıf (alan ekleme/silme vb.)"
type: docs
weight: 200
url: /tr/java/com.aspose.pdf.facades/formeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditor, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditor

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditor extends SaveableFacade implements IFormEditor
```

Formları düzenlemek için sınıf (alan ekleme/silme vb.)

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FormEditor](#FormEditor--) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-com.aspose.pdf.IDocument-java.lang.String-) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.io.InputStream-java.io.OutputStream-) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |
| [FormEditor](#FormEditor-java.lang.String-java.lang.String-) | <p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | <p> Form'a belirtilen türde alan ekle. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre> |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Form'a belirtilen türde alan ekle. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | PushButton alanı için JavaScript ekle. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | <p> Liste kutusuna yeni öğe ekler. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre> |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | <p> Mevcut liste kutusu alanına Export değeriyle yeni bir öğe ekle, yalnızca AcroForm combo kutu alanı için. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre> |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | <p> Form üzerine gönder düğmesi ekle. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre> |
| [close](#close--) | Nesne örneğini kapat |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki her şeyi içerir. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Mevcut bir alanı sayfa numarası ve koordinatlarla belirtilen yeni konuma kopyalar. Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki her şeyi içerir. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Mevcut bir alanı bir PDF belgesinden başka bir belgeye, orijinal sayfa numarası ve koordinatlarıyla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Mevcut bir alanı bir PDF belgesinden başka bir belgeye, belirtilen sayfa numarası ve orijinal koordinatlarla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Mevcut bir alanı bir PDF belgesinden başka bir belgeye, belirtilen sayfa numarası ve koordinatlarla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç). |
| [decorateField](#decorateField--) | <p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | <p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [decorateField](#decorateField-java.lang.String-) | <p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre> |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | <p> Liste alanından öğeyi sil. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre> |
| [dispose](#dispose--) | Nesne örneğini kapat Bu yöntem artık kullanılmıyor, yerine close() kullanın. |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline. |
| [getDestFileName](#getDestFileName--) | Hedef dosya adını alır. |
| [getDestStream](#getDestStream--) | <p> Hedef akışı alır. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [getDocument](#getDocument--) | Alır {@code FormEditor} çalıştığı belgeyi. |
| [getExportItems](#getExportItems--) | <p> Dışa aktarma değerlerine sahip combo kutu seçeneklerini alır. </p> <hr> |
| [getFacade](#getFacade--) | Alanının görsel özniteliklerini alır. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Alan bayraklarını al. |
| [getItems](#getItems--) | Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri al. |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesi boyutunu alır veya ayarlar. FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [getRadioGap](#getRadioGap--) | İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydeden üyeyi al, varsayılan 50'dir. |
| [getRadioHoriz](#getRadioHoriz--) | <p> Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı al, varsayılan değer true'dur. |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak kaydedildiğinde kaydetme seçeneklerini alır. Varsayılan değer: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | Kaynak dosyanın adını alır. |
| [getSrcStream](#getSrcStream--) | Kaynak akışı alır. |
| [getSubmitFlag](#getSubmitFlag--) | Gönder düğmesinin gönderim bayraklarını al |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | <p> Alanın yeni konumunu ayarla. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre> |
| [removeField](#removeField-java.lang.String-) | <p> Formdan alanı kaldır. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre> |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | <p> Alanın gönderme eylemini kaldır. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre> |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Alanın adını değiştir. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre> |
| [resetFacade](#resetFacade--) | Tüm görsel öznitelikleri boş değere sıfırla. |
| [resetInnerFacade](#resetInnerFacade--) | İç facade'in tüm görsel özniteliklerini boş değere sıfırla. |
| [save](#save--) | Değişiklikleri hedef dosyaya kaydeder. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | {@link PdfFormat} PDF dosya biçimini ayarlar. Sonuç dosyası belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF biçiminde kaydedilir. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Hedef dosya adını ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Hedef akışı ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre> |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | <p> Dışa aktarım değerlerine sahip combo kutusu için seçenekleri ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | <p> Alanın görsel özniteliklerini ayarlar. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre> |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | <p> Bir metin alanının hizalama stilini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre> |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | <p> Bir metin alanının dikey hizalama stilini ayarlar. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre> |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | <p> Set field flags </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf"); formEditor.setFieldAppearance("Name", AnnotationFlags.Hidden); formEditor.setFieldAppearance("Phone", AnnotationFlags.NoView \ | AnnotationFlags.Print); </pre> |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | <p> Alanın özniteliklerini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre> |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | <p> Düzenli tek satırlık bir metin alanı için bölme (comb) sayısını ayarlar (alan, combNumber parametresinin değeri kadar eşit aralıklı konuma otomatik olarak bölünür). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre> |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | <p> Metin alanının azami karakter sayısını ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre> |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Bir PushButton alanı için JavaScript ayarlar. Eski JavaScript mevcutsa, yeniyle değiştirilecektir. |
| [setItems](#setItems-java.lang.String:A-) | <p> Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesi boyutunu alır veya ayarlar. FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); |
| [setRadioGap](#setRadioGap-float-) | <p> İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydedecek üye ayarlanır, varsayılan 50'dir. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setRadioHoriz](#setRadioHoriz-boolean-) | <p> Bayrağı ayarlayın; radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini belirtir, varsayılan değer true'dur. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak depolandığında kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | <p> Kaynak dosyanın adını ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre> |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Kaynak akışı ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre> |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | <p> Gönder düğmesinin gönderim bayrağını ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre> |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Gönder düğmesinin gönderim bayraklarını ayarlayın |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | <p> Düğmenin URL'sini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre> |
| [single2Multiple](#single2Multiple-java.lang.String-) | <p> Tek satırlı metin alanını çok satırlı bir alana dönüştürür. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre> |

### FormEditor {#FormEditor--}
```
public FormEditor()
```

<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-}
<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-com.aspose.pdf.IDocument-java.lang.String-}
<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.io.InputStream-java.io.OutputStream-}
<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### FormEditor {#FormEditor-java.lang.String-java.lang.String-}
<p> FormEditor için yapıcı. </p> <hr> <pre> FormEditor formEditor = new FormEditor(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
<p> Form'a belirtilen türde alan ekle. </p> <hr> <pre> FormEditor formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_Text.pdf\"); formEditor.addField(FieldType.Text, \"AddedTextField\", 1, 10, 30, 110, 46); formEditor.save(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Form'a belirtilen türde alan ekle.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
PushButton alanı için JavaScript ekle.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
<p> Liste kutusuna yeni öğe ekler. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", PdfForm_out.pdf\"); formEditor.addListItem(\"listBoxField\", \"Item 4 (New Item)\"); </pre>

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
<p> Mevcut liste kutusu alanına Export değeriyle yeni bir öğe ekle, yalnızca AcroForm combo kutu alanı için. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddListItem2.pdf\"); fe.addListItem(\"listboxField\", new String[] { \"4\", \"Item4(Added)\" }); </pre>

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
<p> Form üzerine gönder düğmesi ekle. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_AddSubmitBtn.pdf\"); formEditor.addSubmitBtn(\"submit\", 1, \"Submit\", \"www.check.com\", 10, 200, 70, 270); </pre>

### close {#close--}
```
public void close()
```

Nesne örneğini kapat

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Mevcut bir alanı belirtilen sayfa numarasındaki aynı konuma kopyalar. Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki her şeyi içerir.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Mevcut bir alanı sayfa numarası ve koordinatlarla belirtilen yeni konuma kopyalar. Yeni bir belge oluşturulur; bu belge, kaynak belgenin tüm içeriğini, yeni kopyalanan alan dışındaki her şeyi içerir.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Mevcut bir alanı bir PDF belgesinden başka bir belgeye, orijinal sayfa numarası ve koordinatlarıyla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Mevcut bir alanı bir PDF belgesinden başka bir belgeye, belirtilen sayfa numarası ve orijinal koordinatlarla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç).

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Mevcut bir alanı bir PDF belgesinden başka bir belgeye, belirtilen sayfa numarası ve koordinatlarla kopyalar. Not: Yalnızca AcroForm alanları için (radyo kutusu hariç).

### decorateField {#decorateField--}
```
public void decorateField()
```

<p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
<p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### decorateField {#decorateField-java.lang.String-}
<p> PDF belgesindeki tüm alanların görsel özelliklerini değiştirir. </p> <hr> <pre> FormEditor fe = new FormEditor(\"PdfForm.pdf\", \"FormEditor_DecorateField.pdf\"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.Green); fe.getFacade().setAlignment(FormFieldFacade.AlignRight); // decorate all fields. fe.decorateField(); </pre>

### delListItem {#delListItem-java.lang.String-java.lang.String-}
<p> Liste alanından öğeyi sil. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_DelListItem.pdf"); formEditor.delListItem("listboxField", "item2"); </pre>

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Nesne örneğini kapat Bu yöntem artık kullanılmıyor, yerine close() kullanın.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
Dize nesnesi

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

İşlemin sonucu HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır. Olası değerler: inline / attachment. Varsayılan: inline.

**Returns:**
ContentDisposition öğesi @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
public String getDestFileName()
```

Hedef dosya adını alır.

**Returns:**
string nesnesi

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

<p> Hedef akışı alır. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

**Returns:**
OutputStream nesnesi

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Alır {@code FormEditor} çalıştığı belgeyi.

**Returns:**
IDocument nesnesi

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

<p> Dışa aktarma değerlerine sahip combo kutu seçeneklerini alır. </p> <hr>

**Returns:**
String[][] nesnesi

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Alanının görsel özniteliklerini alır.

**Returns:**
FormFieldFacade nesnesi

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Alan bayraklarını al.

### getItems {#getItems--}
```
public String [] getItems()
```

Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri al.

**Returns:**
String[] nesnesi

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesi boyutunu alır veya ayarlar. FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Returns:**
double değer

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydeden üyeyi al, varsayılan 50'dir.

**Returns:**
float değer

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

<p> Radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini gösteren bayrağı al, varsayılan değer true'dur.

**Returns:**
boolean değer

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak kaydedildiğinde kaydetme seçeneklerini alır. Varsayılan değer: PdfSaveOptions.

**Returns:**
SaveOptions nesnesi

### getSrcFileName {#getSrcFileName--}
```
public String getSrcFileName()
```

Kaynak dosyanın adını alır.

**Returns:**
string nesnesi

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Kaynak akışı alır.

**Returns:**
InputStream nesnesi

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Gönder düğmesinin gönderim bayraklarını al

**Returns:**
SubmitFormFlag öğesi @see SubmitFormFlag

### moveField {#moveField-java.lang.String-float-float-float-float-}
<p> Alanın yeni konumunu ayarla. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf"); formEditor.moveField("textField", 20.5f, 20.3f, 120.6f, 40.8f); </pre>

### removeField {#removeField-java.lang.String-}
<p> Formdan alanı kaldır. </p> <hr> <pre> FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf"); formEditor.removeField("listboxField"); formEditor.removeField("textField"); </pre>

### removeFieldAction {#removeFieldAction-java.lang.String-}
<p> Alanın gönderme eylemini kaldır. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf"); formEditor.removeFieldAction("btnSubmit"); </pre>

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Alanın adını değiştir. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf"); formEditor.renameField("textField", "textField_Renamed"); </pre>

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Tüm görsel öznitelikleri boş değere sıfırla.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

İç facade'in tüm görsel özniteliklerini boş değere sıfırla.

### save {#save--}
```
@Deprecated public void save()
```

Değişiklikleri hedef dosyaya kaydeder.

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
{@link PdfFormat} PDF dosya biçimini ayarlar. Sonuç dosyası belirtilen dosya biçiminde kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF biçiminde kaydedilir.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Hedef dosya adını ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestFileName("OutFile.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Hedef akışı ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setDestStream(new FileInputStream("OutFile.pdf")); </pre>

### setExportItems {#setExportItems-java.lang.String:A:A-}
<p> Dışa aktarım değerlerine sahip combo kutusu için seçenekleri ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_Updated.pdf")); formEditor.setExportItems ( new String[][] { new String[] { "1", "Firs" }, new String[] { "2", "Second" }, new String[] { "3", "Third" } }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
<p> Alanın görsel özniteliklerini ayarlar. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfForm.pdf", "PdfForm_DecorateField_text.pdf"); fe.setFacade(new FormFieldFacade()); fe.getFacade().setBackgroundColor(Color.red); fe.getFacade().setTextColor(Color.blue); fe.getFacade().setBorderColor(Color.green); fe.getFacade().setAlignment(FormFieldFacade.AlignCenter); fe.setDecorateField("textField"); fe.save(); </pre>

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
<p> Bir metin alanının hizalama stilini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_updated.pdf")); formEditor.setFieldAlignment(fieldName, FormFieldFacade.AlignCenter); </pre>

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
<p> Bir metin alanının dikey hizalama stilini ayarlar. </p> <hr> <pre> FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf"); fe.setFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom); </pre>

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
<p> Alan bayraklarını ayarlar </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm1.pdf\", \"FormEditor_SetFieldAppearance.pdf\"); formEditor.setFieldAppearance(\"Name\", AnnotationFlags.Hidden); formEditor.setFieldAppearance(\"Phone\", AnnotationFlags.NoView | AnnotationFlags.Print); </pre>

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
<p> Alanın özniteliklerini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_SetFieldAttribute.pdf"); formEditor.setFieldAttribute("listboxField", PropertyFlag.ReadOnly); formEditor.setFieldAttribute("textField", PropertyFlag.NoExport); </pre>

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
<p> Düzenli tek satırlık bir metin alanı için bölme (comb) sayısını ayarlar (alan, combNumber parametresinin değeri kadar eşit aralıklı konuma otomatik olarak bölünür). </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf")); formEditor.setFieldCombNumber("textCombField", 5); </pre>

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
<p> Metin alanının azami karakter sayısını ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf"); formEditor.setFieldLimit("textField", 15); </pre>

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Bir PushButton alanı için JavaScript ayarlar. Eski JavaScript mevcutsa, yeniyle değiştirilecektir.

### setItems {#setItems-java.lang.String:A-}
<p> Yeni oluşturulan liste kutusuna veya combo kutusuna eklenecek öğeleri ayarlar. </p> <hr> <pre> formEditor = new com.aspose.pdf.facadesFormEditor("input.pdf", "output.pdf"); formEditor.setItems(new String[] { "AAA", "BBB", "CCC" }); formEditor.addField(FieldType.ListBox, "AddedListBoxField", "BBB", 1, 10, 30, 110, 130); formEditor.save(); </pre>

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Yeni radyo düğmesi alanı eklendiğinde radyo düğmesi öğesi boyutunu alır veya ayarlar. FormEditor formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setRadioButtonItemSize(20); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(com.aspose.pdf.facades.FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save();

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

<p> İki komşu radyo düğmesi arasındaki boşluğu piksel cinsinden kaydedecek üye ayarlanır, varsayılan 50'dir. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor("PdfForm.pdf", "FormEditor_AddField_RadioButton.pdf"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { "First", "Second", "Third" }); formEditor.addField(FieldType.Radio, "AddedRadioButtonField", "Second", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | float değer |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

<p> Bayrağı ayarlayın; radyo düğmelerinin yatay mı yoksa dikey mi düzenlendiğini belirtir, varsayılan değer true'dur. </p> <hr> <pre> formEditor = new com.aspose.pdf.facades.FormEditor(\"PdfForm.pdf\", \"FormEditor_AddField_RadioButton.pdf\"); formEditor.setRadioGap(4); formEditor.setRadioHoriz(false); formEditor.setItems(new String[] { \"First\", \"Second\", \"Third\" }); formEditor.addField(FieldType.Radio, \"AddedRadioButtonField\", \"Second\", 1, 10, 30, 110, 130); formEditor.save(); </pre>

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak depolandığında kaydetme seçeneklerini ayarlar. Varsayılan değer: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
<p> Kaynak dosyanın adını ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcFileName(\"InputFile.pdf\"); </pre>

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Kaynak akışı ayarlar. </p> <hr> <pre> FormEditor editor = new FormEditor(); editor.setSrcStream(new FileInputStream(\"InFile.pdf\")); </pre>

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
<p> Gönder düğmesinin gönderim bayrağını ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitFlag.pdf\"); formEditor.setSubmitFlag(\"btnSubmit\", SubmitFormFlag.Fdf); </pre>

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Gönder düğmesinin gönderim bayraklarını ayarlayın

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
<p> Düğmenin URL'sini ayarlar. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"FormEditor_SetSubmitUrl.pdf\"); formEditor.setSubmitUrl(\"btnSubmit\", \"www.mysite.com\"); </pre>

### single2Multiple {#single2Multiple-java.lang.String-}
<p> Tek satırlı metin alanını çok satırlı bir alana dönüştürür. </p> <hr> <pre> FormEditor formEditor = new FormEditor(\"PdfForm.pdf\", \"PdfForm_updated.pdf\"); formEditor.single2Multiple(\"textField\"); </pre>
