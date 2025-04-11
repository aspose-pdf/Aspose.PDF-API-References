---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator sınıfı. Metin farklılıklarının html temsilini oluşturmak için bir sınıfı temsil eder. Silinen satır sonları paragraf işareti ile belirtilir.
type: docs
weight: 3200
url: /tr/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator Sınıfı

Metin farklılıklarının html temsilini oluşturmak için bir sınıfı temsil eder. Silinen satır sonları paragraf işareti ile belirtilir.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | `HtmlDiffOutputGenerator` sınıfının bir örneğini oluşturur. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | `HtmlDiffOutputGenerator` sınıfının bir örneğini oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Silme işlemi için CSS-stil dizesini alır ve ayarlar. Örnek: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Eşitlik işlemi için CSS-stil dizesini alır ve ayarlar. Örnek: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Ekleme işlemi için CSS-stil dizesini alır ve ayarlar. Örnek: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Silme işlemi için text-decoration: line-through stilini alır veya ayarlar. Varsayılan değer `False`'dır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Metinler arasındaki farklılıklara dayalı çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Metinler arasındaki farklılıklara dayalı çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Metinler arasındaki farklılıklara dayalı çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Metinler arasındaki farklılıklara dayalı çıktıyı oluşturur ve bir dosyaya kaydeder. |

### Ayrıca Bakınız

* arayüz [IFileOutputGenerator](../ifileoutputgenerator/)
* arayüz [IStringOutputGenerator](../istringoutputgenerator/)
* ad alanı [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* derleme [Aspose.PDF](../../)