---
title: "FormDataConverter"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Verileri bir formattan başka bir formata dönüştürmeyi temsil eden bir sınıf.<br/>            fdf/xml/pdf/xfdf içindeki verileri OLEDB/OdbcDB'ye dönüştürebilir.<br/>            OLEDB/OdbcDB içindeki verileri fdf/xml/xfdf'ye dönüştürebilir.<br/>            fdf'yi \"hard-named\" etiketli xml'e dönüştürebilir."
type: docs
weight: 100
url: /tr/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Verileri bir formattan başka bir formata dönüştürmeyi temsil eden bir sınıf.<br/>            fdf/xml/pdf/xfdf içindeki verileri OLEDB/OdbcDB'ye dönüştürebilir.<br/>            OLEDB/OdbcDB içindeki verileri fdf/xml/xfdf'ye dönüştürebilir.<br/>            fdf'yi "hard-named" etiketli xml'e dönüştürebilir.

FormDataConverter türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| FormDataConverter() | FormDataConverter sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| create_missing_field | ConvertToDataTable, Tablo'da mevcut değilse gerekli alanı oluşturur. |
| replace_existing_table | ImportIntoDatabase, bu özellik true olarak ayarlanmışsa mevcut tabloyu düşürür ve yeni bir tablo oluşturur. |
| clear_table_before_export | ExportFromData, veri dışa aktarımından önce tabloyu temizler. |
| create_missing_table | ImportIntoDatabase, tablo mevcut değilse tabloyu oluşturur. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | XML'i FDF formatına içe/dışa aktarım form veri dosyası olarak dönüştür. |
| convert_fdf_to_xml(source_fdf, dest_xml) | FDF dosyasını XML'e dönüştür. |
| convert_to_data_table(source_streams, source_type) | Akış dosyalarını tabloya dönüştür. |
| import_into_data_base(connect_string, db_type) | Verileri tablo'dan veritabanına aktarır. |
| export_from_data_base(connect_string, db_type) | Verileri veritabanından tabloya aktarır. |
| convert_to_streams(dest_stream, dest_type) | Tablodaki verileri akışlara dönüştür. |
| conver_to_streams(dest_stream, dest_type) | Bu yöntem artık kullanılmamaktadır. Lütfen yerine ConvertToStreams() kullanın. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

