---
title: "Metadata"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "XMP meta veri akışına erişim sağlar."
type: docs
weight: 930
url: /tr/python-net/aspose.pdf/metadata/
---

## Metadata class

XMP meta veri akışına erişim sağlar.

Metadata türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_fixed_size | Koleksiyonun sabit boyuta sahip olup olmadığını kontrol eder. |
| anahtarlar | Meta veri anahtarlarının koleksiyonunu alır. |
| değerler | Meta verideki değerleri alır. |
| is_synchronized | Koleksiyonun senkronize edilip edilmediğini kontrol eder. |
| sync_root | Koleksiyon senkronizasyon nesnesini alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| register_namespace_uri(prefix, namespace_uri) | Ad alanı URI'sını kaydeder. |
| register_namespace_uri(prefix, namespace_uri, schema_description) | Ad alanı URI'sını kaydeder. |
| add(key, value) | Meta veriye değer ekler. |
| add(key, value) | Meta veriye değer ekler. |
| add(prefix, value) | Meta veriye pdf uzantısı ekler. |
| get_namespace_uri_by_prefix(prefix) | Önek ile namespace URI'sını döndürür. |
| get_prefix_by_namespace_uri(namespace_uri) | Namespace URI ile önek'i döndürür. |
| contains(key) | Anahtarın meta veride bulunup bulunmadığını kontrol eder. |
| remove(key) | Meta veriden girişi kaldırır. |
| contains_key(key) | Bu sözlüğün belirtilen anahtarı içerip içermediğini belirler. |
| try_get_value(key, value) | Sözlükte anahtarı bulmaya çalışır ve bulunursa değeri getirir. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

