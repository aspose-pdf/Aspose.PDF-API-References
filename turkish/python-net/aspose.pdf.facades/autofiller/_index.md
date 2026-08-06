---
title: "AutoFiller"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Veritabanı veya diğer veri kaynağından veri almayı temsil eden bir sınıf, bu verileri şablon pdf'nin tasarlanmış alanlarına doldurur ve sonunda yeni pdf dosyası veya akışı oluşturur.<br/>             İki şablon dosya giriş moduna sahiptir: akış olarak giriş veya pdf dosyası.<br/>             Dört çıkış modu türü vardır: birleştirilmiş tek akış, birleştirilmiş tek dosya, birçok küçük akış, birçok küçük dosya.<br/>             System.Data.DataTable içinde bulunan literal verileri alabilir."
type: docs
weight: 20
url: /tr/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Veritabanı veya diğer veri kaynağından veri almayı temsil eden bir sınıf, bu verileri şablon pdf'nin tasarlanmış alanlarına doldurur ve sonunda yeni pdf dosyası veya akışı oluşturur.<br/>             İki şablon dosya giriş moduna sahiptir: akış olarak giriş veya pdf dosyası.<br/>             Dört çıkış modu türü vardır: birleştirilmiş tek akış, birleştirilmiş tek dosya, birçok küçük akış, birçok küçük dosya.<br/>             System.Data.DataTable içinde bulunan literal verileri alabilir.

AutoFiller türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| AutoFiller() | AutoFiller sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| output_stream | OutputStream'i alır veya ayarlar. Dört çıkış modundan biri. Klasik kullanım durumu Response.OutputStream'dir.<br/>            Lütfen çevrimiçi demoya bakın. |
| output_streams | Birçok Output Stream'i alır veya ayarlar. Dört çıkış modundan biri. |
| input_stream | Giriş şablon akışını alır veya ayarlar. İki giriş modundan biri. |
| input_file_name | Giriş şablon dosyasını alır veya ayarlar. İki giriş modundan biri. |
| output_file_name | Tek büyük birleştirilmiş çıkış dosyasını alır veya ayarlar. Dört çıkış modundan biri. |
| generating_path | Birçok küçük PDF dosyası oluşturulacaksa, küçük PDF dosyalarının Oluşturma Yolunu alır veya ayarlar. Başka bir özellik olan [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName ile çalışır.<br/>            Dört çıkış modundan biri. |
| basic_file_name | Birçok küçük dosya oluşturulacaksa temel dosya adını alır veya ayarlar. Oluşturulan dosya "BasicFileName0","BasicFileName1",... şeklinde olacaktır.<br/>            Başka bir özellik olan [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath ile çalışır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| save() | Tüm PDF'leri kaydeder. |
| save(dest_file) | Tüm PDF'leri kaydeder. |
| save(dest_stream) | Tüm PDF'leri kaydeder. |
| bind_pdf(src_file) | Bir PDF dosyasını bağlar. |
| bind_pdf(src_stream) | Bir PDF dosyasını bağlar. |
| bind_pdf(src_doc) | Bir PDF belgesini bağlar. |
| close() | Nesneyi ve çıkış akışlarını kapatır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

