---
title: Class HtmlFragment
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlFragment sınıfı. Html parçasını temsil eder
type: docs
weight: 5520
url: /tr/net/aspose.pdf/htmlfragment/
---
## HtmlFragment Sınıfı

Html parçasını temsil eder.

```csharp
public sealed class HtmlFragment : FormattedFragment
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [HtmlFragment](htmlfragment/)(string) | HtmlFragment sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| virtual [HorizontalAlignment](../../aspose.pdf/baseparagraph/horizontalalignment/) { get; set; } | Paragrafın yatay hizalamasını alır veya ayarlar |
| [HtmlLoadOptions](../../aspose.pdf/htmlfragment/htmlloadoptions/) { get; set; } | Bu sınıfın örneğine HTML yüklemek (ve render etmek) için kullanılacak HtmlLoadOptions'ı alır veya ayarlar. Bu veya şu örnek için HTML içe aktarmak için belirli bir ayar kullanmak gerektiğinde kullanın (örneğin, bu veya şu örneğin içe aktarılan HTML için belirli bir BasePath kullanması gerektiğinde veya dış kaynakların belirli bir yükleyicisini kullanması gerektiğinde). Parametre varsayılan ise (null), standart HTML yükleme seçenekleri kullanılacaktır. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça hiperlinkini alır veya ayarlar (pdf oluşturucu için). |
| [IsBreakWords](../../aspose.pdf/htmlfragment/isbreakwords/) { get; set; } | Kelimelerin kırılmasını alır veya ayarlar |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsParagraphHasMargin](../../aspose.pdf/htmlfragment/isparagraphhasmargin/) { get; set; } | Paragrafın varsayılan bir kenar boşluğuna sahip olup olmadığını alır veya ayarlar, aksi takdirde kenar boşluğu 0'dır |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Rectangle](../../aspose.pdf/htmlfragment/rectangle/) { get; } | HtmlFragment'in dikdörtgenini alır |
| [TextState](../../aspose.pdf/htmlfragment/textstate/) { get; set; } | Fontu alır veya ayarlar |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Clone](../../aspose.pdf/htmlfragment/clone/)() | Html parçasını kopyalar. |

### Ayrıca Bakınız

* sınıf [FormattedFragment](../formattedfragment/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)