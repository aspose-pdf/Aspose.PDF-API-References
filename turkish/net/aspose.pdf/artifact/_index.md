---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Artifact sınıfı. Sınıf PDF Artifact nesnesini temsil eder
type: docs
weight: 2770
url: /tr/net/aspose.pdf/artifact/
---
## Artifact sınıfı

Sınıf PDF Artifact nesnesini temsil eder.

```csharp
public class Artifact : IDisposable
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Belirtilen tür ve alt tür ile artifact yapıcısı |
| [Artifact](artifact/#constructor_1)(string, string) | Belirtilen tür ve alt tür ile artifact yapıcısı |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Artifact'ın yatay hizalaması. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Artifact'ın dikey hizalaması. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Artifact'ın alt marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Artifact içindeki operatörlerin koleksiyonunu alır. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Artifact alt türünün adını alır. Artifact alt türü standart alt tür değilse kullanılabilir. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Artifact türünün adını alır. Artifact türü standart dışıysa kullanılabilir. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Artifact'ın XForm'unu alır (eğer XForm kullanılıyorsa). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Artifact'ın resmini alır (varsa). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Eğer true ise Artifact sayfa içeriğinin arkasına yerleştirilir. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Artifact'ın sol marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Çok satırlı metin artifact'ının satırları. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Artifact'ın opaklığını alır veya ayarlar. Olası değerler 0..1 aralığındadır. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Artifact pozisyonunu alır veya ayarlar. Bu özellik belirtilirse, marjlar ve hizalamalar göz ardı edilir. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Artifact'ın dikdörtgenini alır. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Artifact'ın sağ marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Artifact'ın döndürme açısını alır veya ayarlar. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Artifact alt türünü alır. Eğer artifact standart dışı bir alt türe sahipse, alt türün adı CustomSubtype üzerinden okunabilir. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Artifact'ın metnini alır. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Artifact metni için metin durumu. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Artifact'ın üst marjı. Pozisyon açıkça belirtilmişse (Position özelliğinde) bu değer göz ardı edilir. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Artifact türünü alır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Gecikmeli güncellemeleri başlatır. Performansı artırmak için aynı artifact üzerinde birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artifact operatörleri, artifact özelliği değiştiğinde her zaman değiştirilir. Bu, artifact değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artifact güncellemelerini StartUpdates/SaveUpdates çağrıları arasında koyun. Bu, sayfa içeriğini yalnızca bir kez değiştirmeyi sağlar. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Artifact'ı yok eder. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Artifact'ın özel değerini alır. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Artifact'tan özel değeri kaldırır. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | BeginUpdates() çağrısından sonra yapılan tüm güncellemeleri artifact'ta kaydeder. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Artifact'ın resmini ayarlar. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Artifact'ın resmini ayarlar. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Artifact'ın metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye olanak tanır. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Sayfa numarası ile hangi dize değiştirileceğini ayarlar. Varsayılan değer #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Belge sayfasında artifact olarak yer alan PDF sayfasını ayarlar. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Artifact'ın metnini ayarlar. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Artifact'ın metnini ve metin özelliklerini ayarlar. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Artifact'ın özel değerini ayarlar. |

## Diğer Üyeler

| Ad | Açıklama |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Olası artifact alt türlerinin enumerasyonu. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Olası artifact türlerinin enumerasyonu. |

### Ayrıca Bakınız

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)