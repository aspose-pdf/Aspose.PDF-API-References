---
title: "OperatorCollection"
second_title: "Aspose.PDF Python için .NET API Referansı"
description: "Sınıf, operatör koleksiyonunu temsil eder"
type: docs
weight: 1010
url: /tr/python-net/aspose.pdf/operatorcollection/
---

## OperatorCollection class

Sınıf, operatör koleksiyonunu temsil eder

OperatorCollection türü aşağıdaki üyeleri sunar:
## Özellikler
| Ad | Açıklama |
| :- | :- |
| is_fast_text_extraction_mode | Koleksiyonun hızlı metin çıkarımına sınırlı olup olmadığını gösterir |
## Indexer
| Ad | Açıklama |
| :- | :- |
| [index] | Operatörü indeksine göre alır. |
## Yöntemler
| Ad | Açıklama |
| :- | :- |
| insert(index, op) | Operatörü koleksiyona ekler. |
| insert(at, ops) | Operatörleri verilen konuma ekler. |
| insert(at, ops) | Operatörü koleksiyona ekler. |
| delete(index) | Operatörü koleksiyondan siler. |
| delete(ops) | Operatörleri koleksiyondan siler. |
| delete(list) | Yok |
| add(ops) | Operatörleri içerik operatörlerinin sonuna ekler. |
| add(ops) | Yeni bir operatörü koleksiyona ekler. |
| suppress_update() | İçerik verilerinin güncellenmesini engeller.<br/>            İçerik akışı, ResumeUpdate çağrılana kadar güncellenmez. |
| resume_update() | Belge güncellemeyi yeniden başlatır.<br/>            Bekleyen değişiklikler varsa içerik akışını günceller. |
| cancel_update() | Son güncellemeyi iptal eder.<br/>            Bu yöntem, değişikliğin içerik güncellemesi tetiklememesi gerektiğinde çağrılabilir. |
| accept(visitor) | Operatörleri işlemek için IOperatorSelector ziyaretçi nesnesini kabul eder. |
| replace(operators) | Koleksiyondaki operatörleri diğer operatörlerle değiştirin. |

### Ayrıca Bakınız

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

