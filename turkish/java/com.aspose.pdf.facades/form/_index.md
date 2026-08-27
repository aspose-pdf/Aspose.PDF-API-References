---
title: "Form"
linktitle: "Form"
second_title: "Aspose.PDF for Java API Referansı"
description: "Acro form nesnesini temsil eden sınıf."
type: docs
weight: 170
url: /tr/java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Acro form nesnesini temsil eden sınıf.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Form](#Form--) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre> |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Facade'i başlatır. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Facade'i başlatır. |
| [close](#close--) | Açılan dosyaları herhangi bir değişiklik yapmadan kapatır. |
| [dispose](#dispose--) | Tüm açılmış kaynakları kapatır. Bu yöntem artık kullanılmıyor, yerine close() kullanın. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> PDF alanlarının içeriğini fdf akışına aktarır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> PDF alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri aktarılmaz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> PDF alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri aktarılmaz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | XFA veri paketini çıkarır. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Tam nitelikli alan adına göre bir barkod alanını doldurur. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Onay kutusu alanını bir boolean değerle doldurur. Not: Yalnızca Check Box için uygulanabilir. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.CheckBoxField\" ise tam adı belirtmelisiniz, \"CheckBoxField\" yerine. Mevcut alan adlarını keşfetmek ve gereken alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Tam nitelikli alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur. Alanları doldurmadan önce yalnızca alanın adı bilinmelidir. Değer indeks ile belirtilebilir. Not: Yalnızca Radio Box, Combo Box ve List Box alanlarına uygulanır. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.ListBoxField\" ise tam adı belirtmelisiniz, \"ListBoxField\" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Tam nitelikli alan adına göre geçerli bir değerle alanı doldurur. Alanları doldurmadan önce her alanın adı ve ilgili geçerli değerleri bilinmelidir. Hem alan adları hem de değerler büyük/küçük harfe duyarlıdır. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.TextField\" ise tam adı belirtmelisiniz, \"TextField\" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Bir alanı birden çok seçimle doldurur. Not: yalnızca AcroForm List Box alanı için geçerlidir. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Belirtilen değerle alanı doldurur. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> FillImageField işlevinin aşırı yüklemesini sağlar. Girdi bir görüntü akışıdır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak üzerine bir görüntü yapıştırır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Tüm alanları düzleştirir. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Tam nitelikli alan adıyla belirtilen bir alanı düzleştirir. Diğer tüm alanlar değiştirilemez kalır. fieldName geçersiz ise, tüm alanlar değiştirilemez kalır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre> |
| [getAttachmentName](#getAttachmentName--) | İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Radyo düğmesi seçenek alanları için geçerli değeri döndürür. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Alan adına göre radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu yöntem radyo düğmesi grupları için anlam taşır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Alan adını temel alarak radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu yöntem radyo düğmesi grupları için anlam taşır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | İşlemin sonucunun HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır veya ayarlar. Olası değer: inline / attachment. Varsayılan: inline. |
| [getDestFileName](#getDestFileName--) | Hedef dosya adını alır. |
| [getDestStream](#getDestStream--) | Hedef akışı alır veya ayarlar. |
| [getField](#getField-java.lang.String-) | <p> Alan adını temel alarak alanın değerini alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Tüm görünüm özelliklerini içeren FormFieldFacade nesnesini döndürür. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Alanın bayraklarını döndürür. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Metin alanının sınırlamasını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Formdaki alan adlarının listesini alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Alanın tipini döndürür. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Tüm form gönderme düğmesi adlarını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Kısa alan adına göre tam alan adını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Son içe aktarma işleminin sonucu. Her alan için içe aktarma sonucunu tanımlayan nesneler dizisi. |
| [getRichText](#getRichText-java.lang.String-) | <p> Zengin Metin alanının değerini, her karakterin biçimlendirme bilgileri dahil olmak üzere alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Kaynak dosya adını alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Kaynak akışı alır. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \ | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. |
| [importXml](#importXml-java.lang.String-) | <p> Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Alanının gerekli olup olmadığını belirler. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Bir alanın adını değiştirir. AcroForm alanı ya da XFA alanı olabilir. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre> |
| [save](#save--) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Hedef dosya adını ayarlar. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Hedef akışı alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Kaynak dosya adını ayarlar. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Kaynak akışı alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | XFA verilerini belirtilen veri paketiyle değiştirir. Veri paketi, ExtractXfaData kullanılarak çıkarılabilir. |

### Form {#Form--}
```
public Form()
```

<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Form'un parametresiz yapıcısı. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( \"file.pdf\"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Facade'i başlatır.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Facade'i başlatır.

### close {#close--}
```
public void close()
```

Açılan dosyaları herhangi bir değişiklik yapmadan kapatır.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Tüm açılmış kaynakları kapatır. Bu yöntem artık kullanılmıyor, yerine close() kullanın.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> PDF alanlarının içeriğini fdf akışına aktarır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); OutputStream stream = new FileOutputStream(\"export.fdf\"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> PDF alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri aktarılmaz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); FileInputStream fs = new FileInputStream(\"export.xfdf\", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> PDF alanlarının içeriğini xml akışına aktarır. Düğme alanının değeri aktarılmaz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\")); OutputStream fs = new FileOutputStream(\"export.xml\"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
XFA veri paketini çıkarır.

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Tam nitelikli alan adına göre bir barkod alanını doldurur. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillBarcodeField(\"textField\", \"42207252\"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Onay kutusu alanını bir boolean değerle doldurur. Not: Yalnızca Check Box için uygulanabilir. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.CheckBoxField\" ise tam adı belirtmelisiniz, \"CheckBoxField\" yerine. Mevcut alan adlarını keşfetmek ve gereken alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"checkboxField\", true); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"CheckBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Tam nitelikli alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur. Alanları doldurmadan önce yalnızca alanın adı bilinmelidir. Değer indeks ile belirtilebilir. Not: Yalnızca Radio Box, Combo Box ve List Box alanlarına uygulanır. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.ListBoxField\" ise tam adı belirtmelisiniz, \"ListBoxField\" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> //1 Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"listboxField\", 2); form.fillField(\"comboboxField\", 2); form.fillField(\"radiobuttonField\", 2); //2 //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"ListBoxField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Tam nitelikli alan adına göre geçerli bir değerle alanı doldurur. Alanları doldurmadan önce her alanın adı ve ilgili geçerli değerleri bilinmelidir. Hem alan adları hem de değerler büyük/küçük harfe duyarlıdır. Lütfen Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi alan adlarıyla çalışmadığını unutmayın; Örneğin alanın tam adı \"Form.Subform.TextField\" ise tam adı belirtmelisiniz, \"TextField\" değil. Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.fillField(\"FirstName\", \"John\"); form.fillField(\"LastName\", \"Smith\"); //how to search field by its partial name: Form form = new Form(\"input.pdf\", \"output.pdf\"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith(\"TextField\")) { System.out.println(\"Full name is: \" + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Bir alanı birden çok seçimle doldurur. Not: yalnızca AcroForm List Box alanı için geçerlidir. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(\"PdfForm.pdf\", \"Form_Updated.pdf\"); form.fillField(\"ListBox1\", new String[] { \"Three\", \"One\" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Belirtilen değerle alanı doldurur.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> FillImageField işlevinin aşırı yüklemesini sağlar. Girdi bir görüntü akışıdır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", new FileInputStream(\"file.jpg\", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Tam nitelikli alan adına göre mevcut düğme alanının görünümü olarak üzerine bir görüntü yapıştırır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_filled.pdf\"); form.fillImageField(\"fieldName\", \"file.jpg\"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Tüm alanları düzleştirir. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Tam nitelikli alan adıyla belirtilen bir alanı düzleştirir. Diğer tüm alanlar değiştirilemez kalır. fieldName geçersiz ise, tüm alanlar değiştirilemez kalır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); form.flattenField(\"textField\"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

İşlemin sonucu HttpResponse nesnelerine ek olarak kaydedildiğinde ekin adını alır.

**Returns:**
string nesnesi

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Radyo düğmesi seçenek alanları için geçerli değeri döndürür. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println(form.GetButtonOptionCurrentValue(\"btnField\")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Alan adına göre radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu yöntem radyo düğmesi grupları için anlam taşır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); java.util.Map values = form.getButtonOptionValues(\"Color\"); System.out.println(values.get(\"White\").toString()); System.out.println(values.get(\"Black\").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Alan adını temel alarak radyo düğmesi seçenek alanlarını ve ilgili değerleri alır. Bu yöntem radyo düğmesi grupları için anlam taşır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

İşlemin sonucunun HttpResponse nesnesine kaydedildiğinde içeriğin nasıl saklanacağını alır veya ayarlar. Olası değer: inline / attachment. Varsayılan: inline.

**Returns:**
ContentDisposition öğesi @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Hedef dosya adını alır.

**Returns:**
string nesnesi

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Hedef akışı alır veya ayarlar.

**Returns:**
OutputStream nesnesi

### getField {#getField-java.lang.String-}
<p> Alan adını temel alarak alanın değerini alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Tüm görünüm özelliklerini içeren FormFieldFacade nesnesini döndürür. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Alanın bayraklarını döndürür. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Metin alanının sınırlamasını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Formdaki alan adlarının listesini alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] nesnesi

### getFieldType {#getFieldType-java.lang.String-}
<p> Alanın tipini döndürür. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Tüm form gönderme düğmesi adlarını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] nesnesi

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Kısa alan adına göre tam alan adını alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Son içe aktarma işleminin sonucu. Her alan için içe aktarma sonucunu tanımlayan nesneler dizisi.

**Returns:**
FormImportResult[] dizisi

### getRichText {#getRichText-java.lang.String-}
<p> Zengin Metin alanının değerini, her karakterin biçimlendirme bilgileri dahil olmak üzere alır. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions.

**Returns:**
SaveOptions nesnesi

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Kaynak dosya adını alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
string nesnesi

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Kaynak akışı alır.

**Returns:**
InputStream nesnesi

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Gönder düğmesinin gönderim bayraklarını döndürür </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\"); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Xfdf != 0) ? \" XFDF\" : \" \" ); /// System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Fdf != 0) ? \" FDF\" : \" \" ); System.out.println( ( form.getSubmitFlags(\"btnSubmit\") | SubmitFormFlag.Pdf != 0) ? \" PDF\" : \" \" ); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Alanların içeriğini fdf dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir.

### importXml {#importXml-java.lang.String-}
<p> Alanların içeriğini xml dosyasından içe aktarır ve yeni pdf'ye yerleştirir. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Alanının gerekli olup olmadığını belirler.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Bir alanın adını değiştirir. AcroForm alanı ya da XFA alanı olabilir. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfFormUpdated.pdf\"); form.renameField(\"field\", \"field1\"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. </p> <hr> <pre> Form form = new Form(\"PdfForm.pdf\", \"PdfForm_Changed.pdf\"); form.fillField(\"textField\", \"new value\"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
İşlemin sonucu HttpResponse nesnelerine ek olarak depolandığında ekin adını ayarlar.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
İşlemin sonucu HttpResponse nesnesine depolandığında içeriğin nasıl saklanacağını ayarlar. Olası değerler: inline / attachment. Varsayılan: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
PDF dosya formatını ayarlar. Sonuç dosyası belirtilen dosya formatında kaydedilecektir. Bu özellik belirtilmezse dosya, dönüşüm olmadan varsayılan PDF formatında kaydedilir.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Hedef dosya adını ayarlar. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName(\"file.pdf\"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Hedef akışı alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream(\"file.pdf\")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sonuç HttpResponse olarak saklandığında kaydetme seçeneklerini alır veya ayarlar. Varsayılan değer: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Kaynak dosya adını ayarlar.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Kaynak akışı alır. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream(\"source.pdf\"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
XFA verilerini belirtilen veri paketiyle değiştirir. Veri paketi, ExtractXfaData kullanılarak çıkarılabilir.
