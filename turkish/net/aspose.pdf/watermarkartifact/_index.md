---
title: Class WatermarkArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.WatermarkArtifact sınıfı. Sınıf, filigran nesnesini tanımlar. Bu, kullanılabilir
type: docs
weight: 11310
url: /tr/net/aspose.pdf/watermarkartifact/
---
## WatermarkArtifact sınıfı

Sınıf, filigran nesnesini tanımlar. Bu, kullanılabilir

```csharp
public class WatermarkArtifact : Artifact
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [WatermarkArtifact](watermarkartifact/)() | Filigran nesnesinin örneğini oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Nesnenin yatay hizalaması. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Nesnenin dikey hizalaması. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Nesnenin alt marjı. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Nesnenin iç operatörlerinin koleksiyonunu alır. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Nesne alt türünün adını alır. Standart alt tür değilse kullanılabilir. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Nesne türünün adını alır. Nesne türü standart değilse kullanılabilir. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Nesnenin XForm'unu alır (eğer XForm kullanılıyorsa). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Nesnenin resmini alır (varsa). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Eğer doğruysa, nesne sayfa içeriğinin arkasına yerleştirilir. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Nesnenin sol marjı. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Çok satırlı metin nesnesinin satırları. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Nesnenin opaklığını alır veya ayarlar. Olası değerler 0..1 aralığındadır. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Nesne pozisyonunu alır veya ayarlar. Bu özellik belirtilirse, marjlar ve hizalamalar göz ardı edilir. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Nesnenin dikdörtgenini alır. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Nesnenin sağ marjı. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Nesnenin döndürme açısını alır veya ayarlar. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Nesne alt türünü alır. Eğer nesne standart dışı bir alt türe sahipse, alt türün adı CustomSubtype üzerinden okunabilir. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Nesnenin metnini alır. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Nesne metni için metin durumu. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Nesnenin üst marjı. Pozisyon açıkça belirtilmişse (Pozisyon özelliğinde) bu değer göz ardı edilir. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Nesne türünü alır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Gecikmeli güncellemeleri başlatır. Performansı artırmak için aynı nesne üzerinde birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle nesne operatörleri, nesne özelliği değiştiğinde her zaman değiştirilir. Bu, nesne değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm nesne güncellemelerini StartUpdates/SaveUpdates çağrıları arasında koyun. Bu, sayfa içeriğini yalnızca bir kez değiştirmeyi sağlar. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Nesneyi yok eder. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Nesnenin özel değerini alır. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Nesneden özel değeri kaldırır. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() çağrısından sonra yapılan tüm güncellemeleri nesnede kaydeder. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Nesnenin resmini ayarlar. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Nesnenin resmini ayarlar. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Nesnenin metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye olanak tanır. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Sayfa numarası ile değiştirilecek dizeyi ayarlar. Varsayılan değer #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Belge sayfasında nesne olarak yer alan PDF sayfasını ayarlar. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Nesnenin metnini ayarlar. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Nesnenin metnini ve metin özelliklerini ayarlar. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Nesnenin özel değerini ayarlar. |

### Ayrıca Bakınız

* sınıf [Artifact](../artifact/)
* ad alanı [Aspose.Pdf](../../aspose.pdf/)
* derleme [Aspose.PDF](../../)