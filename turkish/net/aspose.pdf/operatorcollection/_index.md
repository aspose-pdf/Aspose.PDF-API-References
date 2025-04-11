---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OperatorCollection sınıfı. Sınıf, operatörlerin koleksiyonunu temsil eder
type: docs
weight: 7080
url: /tr/net/aspose.pdf/operatorcollection/
---
## OperatorCollection sınıfı

Sınıf, operatörlerin koleksiyonunu temsil eder

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Özellikler

| İsim | Açıklama |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Koleksiyondaki operatörlerin sayısını alır. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Koleksiyonun hızlı metin çıkarımı ile sınırlı olup olmadığını gösterir. |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Koleksiyonun salt okunur olup olmadığını belirten bir değer alır. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Operatörü indeksine göre alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Operatörleri işlemek için IOperatorSelector ziyaretçi nesnesini kabul eder. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Diğer koleksiyondaki tüm operatörleri koleksiyona ekler. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Koleksiyona yeni bir operatör ekler. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Operatörleri içerik operatörlerinin sonuna ekler. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Son güncellemeyi iptal eder. Bu yöntem, değişikliğin içerik güncellemesi gerektirmediğinde çağrılabilir. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Listeden tüm operatörleri kaldırır. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Koleksiyonun verilen operatörü içerip içermediğini kontrol eder. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Operatörleri operatörler listesine kopyalar. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Koleksiyondan operatörleri siler. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Koleksiyondan operatörü siler. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Koleksiyondan operatörleri siler. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Yönetilmeyen kaynakları serbest bırakma, boşaltma veya sıfırlama ile ilgili uygulama tanımlı görevleri yerine getirir. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Koleksiyon için enumeratör döner |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Operatörleri belirtilen konuma ekler. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Operatörü koleksiyona ekler. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Operatörleri belirtilen konuma ekler. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Operatörü koleksiyondan kaldırır. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Koleksiyondaki operatörleri diğer operatörlerle değiştirir. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Belge güncellemesini devam ettirir. Bekleyen değişiklikler varsa içerik akışını günceller. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Belge güncellemesini devam ettirir. Bekleyen değişiklikler varsa içerik akışını günceller. Geçersiz kılma parametresi true ise tüm operatörleri "değiştirildi" olarak işaretler. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | İçerik verilerini güncellemeyi bastırır. ResumeUpdate çağrılana kadar içerik akışı güncellenmez. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Operatörün metin temsilini döner. |

### Ayrıca Bakınız

* sınıf [BaseOperatorCollection](../baseoperatorcollection/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)