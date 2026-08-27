---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "PDF belge açıklamaları (yorumlar) ile çalışmak için bir sınıfı temsil eder."
type: docs
weight: 170
url: /tr/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

PDF belge açıklamaları (yorumlar) ile çalışmak için bir sınıfı temsil eder.

PdfAnnotationEditor türü aşağıdaki üyeleri sunar:
## Yapıcılar
| Ad | Açıklama |
| :- | :- |
| PdfAnnotationEditor() | Yeni bir [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) nesnesi başlatır. |
| PdfAnnotationEditor(document) | PdfAnnotationEditor sınıfının yeni bir örneğini başlatır. |
## Özellikler
| Ad | Açıklama |
| :- | :- |
| belge | Çalışılan belge arayüzünü alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| bind_pdf(src_file) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_stream) | PDF belgesini düzenleme için bağlar. |
| bind_pdf(src_doc) | PDF belgesini düzenleme için bağlar. |
| save(dest_file) | PDF belgesini belirtilen dosyaya kaydeder. |
| save(dest_stream) | PDF belgesini belirtilen akışa kaydeder. |
| import_annotations_from_xfdf(xfdf_file) | XFDF dosyasından tüm açıklamaları içe aktarır. |
| import_annotations_from_xfdf(xfdf_stream) | XFDF veri akışından tüm açıklamaları içe aktarır. |
| import_annotation_from_xfdf(xfdf_file) | XFDF dosyasından tüm açıklamaları içe aktarır. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | XFDF dosyasından belirtilen açıklamaları içe aktarır. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | XFDF veri akışından belirtilen açıklamaları içe aktarır. |
| import_annotation_from_xfdf(xfdf_stream) | XFDF veri akışından belirtilen açıklamaları içe aktarır. |
| import_annotations(annot_file, annot_type) | Belirtilen açıklamaları, başka PDF belgelerinin bir dizisinden belgeye içe aktarır. |
| import_annotations(annot_file) | Belirtilen açıklamaları, başka PDF belgelerinin bir dizisinden belgeye içe aktarır. |
| import_annotations(annot_file_stream, annot_type) | Belirtilen ek açıklamaları, başka bir PDF belgesinin akış dizisinden belgeye aktarır. |
| import_annotations(annot_file_stream) | Belirtilen ek açıklamaları, başka bir PDF belgesinin akış dizisinden belgeye aktarır. |
| flattening_annotations() | Belgedeki tüm ek açıklamaları düzleştirir. |
| flattening_annotations(flatten_settings) | Belgedeki tüm ek açıklamaları düzleştirir. |
| flattening_annotations(start, end, annot_type) | Belirtilen türlerin ek açıklamalarını düzleştirir. |
| delete_annotations() | Belgedeki tüm ek açıklamaları siler. |
| delete_annotations(annot_type) | Belgedeki belirtilen türdeki tüm ek açıklamaları siler. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Belirtilen ek açıklama türlerinin içeriğini XFDF'ye aktarır |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Belirtilen ek açıklama türlerinin içeriğini XFDF'ye aktarır |
| extract_annotations(start, end, annot_types) | Belirtilen türlerin ek açıklama listesini alır. |
| extract_annotations(start, end, annot_types) | Belirtilen türlerin ek açıklama listesini alır. |
| close() | Mevcut facade ile ilişkili tüm kaynakları serbest bırakır. |
| modify_annotations_author(start, end, src_author, des_author) | Belirtilen sayfa aralığındaki ek açıklamaların yazarını değiştirir. |
| delete_annotation(annot_name) | Belgedeki belirtilen türdeki tüm ek açıklamaları siler. |
| export_annotations_to_xfdf(xml_output_stream) | Ek açıklamaları akışa aktarır. |
| modify_annotations(start, end, annotation) | Belirtilen sayfa aralığındaki belirtilen türdeki ek açıklamaları değiştirir.<br/>            Aşağıdaki ek açıklama özelliklerini değiştirmeyi destekler: Modified, Title, Contents, Color, Subject ve Open. |
| redact_area(page_index, rect, color) | Belirtilen sayfada alanı gizler. Tüm içerikler kaldırılır. |

### Ayrıca Bakınız

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

