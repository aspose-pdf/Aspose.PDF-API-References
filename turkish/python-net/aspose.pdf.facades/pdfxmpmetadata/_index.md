---
title: "PdfXmpMetadata"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "XMP meta verileriyle manipülasyon için sınıf."
type: docs
weight: 380
url: /tr/python-net/aspose.pdf.facades/pdfxmpmetadata/
---

## PdfXmpMetadata class

XMP meta verileriyle manipülasyon için sınıf.

PdfXmpMetadata türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfXmpMetadata() | PdfXmpMetadata için yapıcı. |
| PdfXmpMetadata(document) | PdfXmpMetadata sınıfının yeni bir örneğini başlatır |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
| anahtarlar | Sözlükten anahtarları alır. |
| değerler | Sözlükteki değerler koleksiyonunu alır. |
| is_fixed_size | Koleksiyon sabit boyutlu ise true döndürür. |
| is_synchronized | Koleksiyon senkronize ise true döndürür. |
| sync_root | Koleksiyonun senkronizasyon nesnesini alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| add(key, value) | Değeri XMP meta verisine ekler. |
| add(xmp_pdf_a_extension_object, namespace_prefix, namespace_uri, schema_description) | Meta veriye uzantı alanı ekler. |
| add(key, value) | Sözlük nesnesine yeni öğe ekler. |
| add(key, value) | Meta veriye uzantı alanı ekler. |
| remove(key) | Belirtilen anahtara sahip öğeyi kaldırır. |
| remove(key) | Anahtarı sözlükten kaldırır. |
| contains(key) | Sözlüğün belirtilen anahtarı içerip içermediğini kontrol eder. |
| contains(property) | Sözlüğün belirtilen özelliği içerip içermediğini kontrol eder. |
| get_xmp_metadata() | Girdi PDF'nin XmpMetadata'sını XML formatında al. |
| get_xmp_metadata(name) | Giriş pdf'in XmpMetadata'ının bir bölümünü meta adına göre al. |
| close() | Mevcut facade ile ilişkili tüm kaynakları serbest bırakır. |
| register_namespace_uri(prefix, namespace_uri) | Namespace URI'sini kaydeder. |
| get_namespace_uri_by_prefix(prefix) | Prefix'e göre namespace URI'sini alır. |
| get_prefix_by_namespace_uri(namespace_uri) | Namespace URI'ye göre prefix'i alır. |
| contains_key(key) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| try_get_value(key, value) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

