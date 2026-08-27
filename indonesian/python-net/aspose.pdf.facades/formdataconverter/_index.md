---
title: "FormDataConverter"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Mewakili kelas untuk mengonversi data dari satu format ke format lain.<br/>            Dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB.<br/>            Juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf.<br/>            Dapat mengonversi fdf ke xml dengan tag \"hard-named\"."
type: docs
weight: 100
url: /id/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Mewakili kelas untuk mengonversi data dari satu format ke format lain.<br/>            Dapat mengonversi data dalam fdf/xml/pdf/xfdf ke OLEDB/OdbcDB.<br/>            Juga dapat mengonversi data dalam OLEDB/OdbcDB ke data dalam fdf/xml/xfdf.<br/>            Dapat mengonversi fdf ke xml dengan tag "hard-named".

Tipe FormDataConverter menampilkan anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| FormDataConverter() | Menginisialisasi instance baru dari kelas FormDataConverter |
## Properti
| Nama | Deskripsi |
| :- | :- |
| create_missing_field | ConvertToDataTable akan membuat bidang yang diperlukan jika tidak ada di Tabel. |
| replace_existing_table | ImportIntoDatabase akan menghapus tabel yang ada dan membuat tabel baru jika properti ini disetel ke true. |
| clear_table_before_export | ExportFromData akan mengosongkan tabel sebelum ekspor data. |
| create_missing_table | ImportIntoDatabase akan membuat tabel jika tidak ada. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Konversi file data formulir XML impor/ekspor ke format FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Konversi file FDF ke XML. |
| convert_to_data_table(source_streams, source_type) | Konversi file aliran menjadi tabel. |
| import_into_data_base(connect_string, db_type) | Mengimpor data dari tabel ke basis data. |
| export_from_data_base(connect_string, db_type) | Mengekspor data dari basis data ke tabel. |
| convert_to_streams(dest_stream, dest_type) | Konversi data dalam tabel menjadi aliran. |
| conver_to_streams(dest_stream, dest_type) | Metode ini sudah usang. Silakan gunakan ConvertToStreams() sebagai gantinya. |

### Lihat Juga

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

