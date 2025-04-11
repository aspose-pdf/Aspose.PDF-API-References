---
title: Class TeXFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.TeXFragment sınıfı. TeX parçasını temsil eder
type: docs
weight: 10360
url: /tr/net/aspose.pdf/texfragment/
---
## TeXFragment sınıfı

TeX parçasını temsil eder.

```csharp
public class TeXFragment : FormattedFragment
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [TeXFragment](texfragment/#constructor)(string) | HtmlFragment sınıfının yeni bir örneğini başlatır. |
| [TeXFragment](texfragment/#constructor_1)(string, bool) | HtmlFragment sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça bağlantısını alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış marjı alır veya ayarlar (pdf oluşturma için) |
| [TeXLoadOptionsOfInstance](../../aspose.pdf/texfragment/texloadoptionsofinstance/) { get; set; } | Bu sınıfın örneğine LaTeX yüklemek (ve işlemek) için kullanılacak TeXLoadOptions'ı alır veya ayarlar. Bu veya şu örnek için LaTeX'in içe aktarımı için belirli bir ayar kullanılması gerektiğinde kullanın (örneğin, bu veya şu örneğin içe aktarılan LaTeX için belirli bir BasePath kullanması gerektiğinde veya dış kaynakların belirli bir yükleyicisini kullanması gerektiğinde). Parametre varsayılan (null) ise, standart LaTeX yükleme seçenekleri kullanılacaktır. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf/texfragment/clone/)() | Parçayı kopyalar. |

### Ayrıca Bakınız

* sınıf [FormattedFragment](../formattedfragment/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)