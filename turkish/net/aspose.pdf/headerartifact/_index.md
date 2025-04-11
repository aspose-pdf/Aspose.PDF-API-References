---
title: Class HeaderArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HeaderArtifact sınıfı. Sınıf, Header artefaktını tanımlar. Bu artefakt, sayfanın başlığını ayarlamak için kullanılabilir.
type: docs
weight: 5420
url: /tr/net/aspose.pdf/headerartifact/
---
## HeaderArtifact sınıfı

Sınıf, Header artefaktını tanımlar. Bu artefakt, sayfanın başlığını ayarlamak için kullanılabilir.

```csharp
public class HeaderArtifact : Artifact
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [HeaderArtifact](headerartifact/)() | Header Artefaktı örneği oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Artefaktın yatay hizalaması. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Artefaktın dikey hizalaması. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Artefaktın alt marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Artefaktın içsel operatörlerinin koleksiyonunu alır. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Artefakt alt türünün adını alır. Artefakt alt türü standart alt tür değilse kullanılabilir. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Artefakt türünün adını alır. Artefakt türü standart dışıysa kullanılabilir. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Artefaktın XForm'unu alır (eğer XForm kullanılıyorsa). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Artefaktın resmini alır (varsa). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Eğer true ise, Artefakt sayfa içeriğinin arkasına yerleştirilir. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Artefaktın sol marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Çok satırlı metin artefaktının satırları. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Artefaktın opaklığını alır veya ayarlar. Olası değerler 0..1 aralığındadır. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Artefaktın konumunu alır veya ayarlar. Bu özellik belirtilirse, marjlar ve hizalamalar göz ardı edilir. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Artefaktın dikdörtgenini alır. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Artefaktın sağ marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Artefaktın döndürme açısını alır veya ayarlar. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Artefakt alt türünü alır. Eğer artefaktın standart dışı bir alt türü varsa, alt türün adı CustomSubtype üzerinden okunabilir. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Artefaktın metnini alır. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Artefakt metni için metin durumu. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Artefaktın üst marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Artefakt türünü alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Gecikmeli güncellemeleri başlatır. Performansı artırmak için aynı artefakta birkaç değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, artefakt değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında koyun. Bu, sayfa içeriğini yalnızca bir kez değiştirmeyi sağlar. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Artefaktı yok eder. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Artefaktın özel değerini alır. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Artefaktan özel değeri kaldırır. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() çağrısından sonra yapılan tüm güncellemeleri artefakta kaydeder. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Artefaktın resmini ayarlar. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Artefaktın resmini ayarlar. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Artefaktın metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye olanak tanır. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Sayfa numarası ile değiştirilecek dizeyi ayarlar. Varsayılan değer #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Artefakt olarak belge sayfasında yer alan PDF sayfasını ayarlar. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Artefaktın metnini ayarlar. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Artefaktın metnini ve metin özelliklerini ayarlar. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Artefaktın özel değerini ayarlar. |

### Ayrıca Bakınız

* sınıf [Artifact](../artifact/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)