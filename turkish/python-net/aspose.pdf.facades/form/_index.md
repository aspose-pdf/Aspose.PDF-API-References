---
title: "Form"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Acro form nesnesini temsil eden sınıf."
type: docs
weight: 80
url: /tr/python-net/aspose.pdf.facades/form/
---

## Form class

Acro form nesnesini temsil eden sınıf.

Form türü aşağıdaki üyeleri ortaya çıkar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| Form(src_stream, dest_stream) | Form sınıfının yeni bir örneğini başlatır. |
| Form() | Parametresiz Form yapıcı. |
| Form(src_file_name) | Form sınıfının yeni bir örneğini başlatır. |
| Form(src_stream) | Form sınıfının yeni bir örneğini başlatır. |
| Form(src_file_name, dest_file_name) | Form sınıfının yeni bir örneğini başlatır. |
| Form(src_file_name, dest_stream) | Form sınıfının yeni bir örneğini başlatır. |
| Form(src_stream, dest_file_name) | Form sınıfının yeni bir örneğini başlatır. |
| Form(document) | Form sınıfının yeni bir örneğini başlatır. |
| Form(document, dest_file_name) | Form sınıfının yeni bir örneğini başlatır. |
| Form(document, dest_stream) | Form sınıfının yeni bir örneğini başlatır. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| import_result | Son içe aktarma işleminin sonucu. Her alan için içe aktarma sonucunu tanımlayan nesneler dizisi. |
| src_file_name | Kaynak dosya adını alır veya ayarlar. |
| dest_file_name | Hedef dosya adını alır veya ayarlar. |
| src_stream | Kaynak akışı alır veya ayarlar. |
| dest_stream | Hedef akışı alır veya ayarlar. |
| field_names | Formdaki alan adlarının listesini alır. |
| form_submit_button_names | Tüm form gönderme düğmesi adlarını alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save() | Doldurulmuş alanların değerini kaydeder ve açılmış PDF belgesini kapatır. |
| save(dest_file) | Belgeyi belirtilen dosyaya kaydeder. |
| save(dest_stream) | Belgeyi belirtilen akışa kaydeder. |
| fill_field(field_name, field_value) | Alanı tam nitelikli bir alan adına göre geçerli bir değerle doldurur.<br/>            Alanları doldurmadan önce, her alanın adı ve karşılık gelen geçerli değerler bilinmelidir.<br/>            Hem alan adları hem de değerler büyük/küçük harfe duyarlıdır.<br/>            Lütfen Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi <br/>            alan adlarıyla çalışmadığını unutmayın;<br/>            Örneğin, alanın tam adı "Form.Subform.TextField" ise tam adı belirtmeli ve "TextField" kullanmamalısınız. <br/>            Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| fill_field(field_name, index) | Alanı tam nitelikli bir alan adına göre geçerli bir indeks değeriyle radyo kutusu alanını doldurur.<br/>            Alanları doldurmadan önce yalnızca alanın adı bilinmelidir. Değer ise indeks ile belirtilebilir.<br/>            Not: Yalnızca Radio Box, Combo Box ve List Box alanlarına uygulanır.<br/>            Lütfen Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi <br/>            alan adlarıyla çalışmadığını unutmayın;<br/>            Örneğin, alanın tam adı "Form.Subform.ListBoxField" ise tam adı belirtmeli ve "ListBoxField" kullanmamalısınız. <br/>            Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| fill_field(field_name, be_checked) | Alanı bir boolean değerle işaret kutusu alanını doldurur.<br/>            Not: Yalnızca Check Box için uygulanır.<br/>            Lütfen Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi <br/>            alan adlarıyla çalışmadığını unutmayın;<br/>            Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise tam adı belirtmeli ve "CheckBoxField" kullanmamalısınız. <br/>            Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| fill_field(field_name, field_values) | Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder.<br/>            İmzalı belgeler için geçerlidir.<br/>            Not: Yalnızca Text Box için uygulanır.<br/>            Hem alan adları hem de değerler büyük/küçük harfe duyarlıdır. |
| fill_field(field_name, value, fit_font_size) | Alanı bir boolean değerle işaret kutusu alanını doldurur.<br/>            Not: Yalnızca Check Box için uygulanır.<br/>            Lütfen Aspose.Pdf.Facades'in yalnızca tam alan adlarını desteklediğini ve Aspose.Pdf.Kit'in aksine kısmi <br/>            alan adlarıyla çalışmadığını unutmayın;<br/>            Örneğin, alanın tam adı "Form.Subform.CheckBoxField" ise tam adı belirtmeli ve "CheckBoxField" kullanmamalısınız. <br/>            Mevcut alan adlarını keşfetmek ve gerekli alanı kısmi adıyla aramak için FieldNames özelliğini kullanabilirsiniz. |
| import_xml(input_xml_stream) | XML dosyasından alanların içeriğini içe aktarır ve yeni PDF'e yerleştirir. |
| import_xml(input_xml_stream, ignore_form_template_changes) | XML dosyasından alanların içeriğini içe aktarır ve yeni PDF'e yerleştirir. |
| fill_image_field(field_name, image_file_name) | Mevcut düğme alanına, tam nitelikli alan adına göre <br/>            bir görüntü yapıştırarak görünümünü ayarlar. |
| fill_image_field(field_name, image_stream) | FillImageField işlevinin aşırı yüklemeleri.<br/>            Girdi bir görüntü akışıdır. |
| close() | Açılan dosyaları herhangi bir değişiklik yapmadan kapatır. |
| get_field_facade(field_name) | Tüm görünüm özelliklerini içeren FrofmFieldFacade nesnesini döndürür. |
| fill_fields(field_names, field_values, output) | Metin kutusu alanlarını metin değerleriyle doldurur ve belgeyi kaydeder.<br/>            İmzalı belgeler için geçerlidir.<br/>            Not: Yalnızca Text Box için uygulanır.<br/>            Hem alan adları hem de değerler büyük/küçük harfe duyarlıdır. |
| get_button_option_current_value(field_name) | Radyo düğmesi seçenek alanları için geçerli değeri döndürür. |
| get_field(field_name) | Tüm görünüm özelliklerini içeren FrofmFieldFacade nesnesini döndürür. |
| get_full_field_name(field_name) | Kısa alan adına göre tam alan adını alır. |
| get_field_limit(field_name) | Metin alanının sınırlamasını al. |
| flatten_all_fields() | Tüm alanları düzleştirir. |
| flatten_field(field_name) | Tam nitelikli alan adıyla belirtilen bir alanı düzleştirir.<br/>            Diğer tüm alanlar değiştirilemez kalır. Eğer fieldName geçersizse, <br/>            tüm alanlar değiştirilemez kalır. |
| fill_barcode_field(field_name, data) | Tam nitelikli alan adına göre bir barkod alanını doldurur. |
| import_fdf(input_fdf_stream) | Fdf dosyasından alanların içeriğini içe aktarır ve yeni pdf'e yerleştirir. |
| export_fdf(output_fdf_stream) | Pdf'in alan içeriğini fdf akışına dışa aktarır. |
| export_xml(output_xml_stream) | Pdf'in alan içeriğini xml akışına dışa aktarır.<br/>            Düğme alanının değeri dışa aktarılmayacak. |
| extract_xfa_data(output_xml_stream) | XFA veri paketini çıkarır |
| set_xfa_data(input_xml_stream) | XFA verisini belirtilen veri paketiyle değiştirir. Veri paketi, ExtractXfaData kullanılarak çıkarılabilir. |
| import_xfdf(input_xfdf_stream) | Alanların içeriğini xfdf(xml) dosyasından içe aktarır ve yeni PDF'e yerleştirir. |
| export_xfdf(output_xfdf_stream) | Pdf'in alan içeriğini xml akışına dışa aktarır.<br/>            Düğme alanının değeri dışa aktarılmayacak. |
| rename_field(field_name, new_field_name) | Bir alanın adını değiştirir. AcroForm alanı ya da XFA alanı olabilir. |
| get_rich_text(field_name) | Zengin Metin alanının değerini alır, her karakterin biçimlendirme bilgilerini dahil eder. |
| get_submit_flags(field_name) | Gönder düğmesinin gönderim bayraklarını döndürür |
| get_field_type(field_name) | Alan tipini döndürür. |
| is_required_field(field_name) | Alanının gerekli olup olmadığını belirler. |
| get_field_flag(field_name) | Alan bayraklarını döndürür. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

