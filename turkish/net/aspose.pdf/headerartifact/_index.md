---
title: HeaderArtifact
second_title: Aspose.PDF for .NET API Referansı
description: Sınıf Üstbilgi yapaylığını açıklar. Bu yapı sayfanın başlığını ayarlamak için kullanılabilir.
type: docs
weight: 3340
url: /tr/net/aspose.pdf/headerartifact/
---
## HeaderArtifact class

Sınıf, Üstbilgi yapaylığını açıklar. Bu yapı, sayfanın başlığını ayarlamak için kullanılabilir.

```csharp
public class HeaderArtifact : Artifact
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [HeaderArtifact](headerartifact)() | Header Artifact örneği oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Yapının yatay hizalaması. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Yapının dikey hizalaması. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Yapının alt kenar boşluğu. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Yapay yapı dahili operatörlerinin koleksiyonunu alır. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Yapıt alt türünün adını alır. Yapıt alt türü standart alt tür değilse kullanılabilir. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Yapıt türünün adını alır. Yapıt türü standart değilse kullanılabilir. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Yapının XForm'unu alır (XForm kullanılıyorsa). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Yapının görüntüsünü alır (varsa). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Gerçek Artifact sayfa içeriğinin arkasına yerleştirilmişse. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Yapının sol kenar boşluğu. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Çok satırlı metin yapısı satırları. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Yapının opaklığını alır veya ayarlar. Olası değerler 0..1. aralığındadır |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Artefakt konumunu alır veya ayarlar. Bu özellik belirtilirse, kenar boşlukları ve hizalamalar yoksayılır. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Yapının dikdörtgenini alır. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Yapının sağ kenar boşluğu. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Artefakt döndürme açısını alır veya ayarlar. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Yapıt alt türünü alır. Yapının standart olmayan alt türü varsa, alt türün adı CustomSubtype. aracılığıyla okunabilir. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Yapının metnini alır. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Yapay metin için metin durumu. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Yapının üst kenar boşluğu. Konum açıkça belirtilirse (Konum özelliğinde) bu değer yok sayılır. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Yapıt türünü alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Ertelenen güncellemeleri başlatın. Performansı artırmak için aynı yapı üzerinde birkaç değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle yapıt işleçleri, yapıt özelliği değiştirildiğinde herhangi bir zamanda değiştirilir. Bu, yapıt değiştirildiğinde her zaman content sayfasının değişmesine neden olur. Bu etkiyi önlemek için, tüm yapı güncellemelerini StartUpdates/SaveUpdates çağrıları arasına koyun. Bu, sayfa içeriğinin yalnızca bir kez değiştirilmesine izin verir. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Yapıyı atın. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Yapının özel değerini alır. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Yapıdan özel değeri kaldırın. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | BeginUpdates() çağrısından sonra yapılan tüm güncellemeleri yapaylığa kaydeder. |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Yapının görüntüsünü ayarlar. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Yapının görüntüsünü ayarlar. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Yapının metin ve metin özelliklerini ayarlayın. Birden çok satır belirtmeye izin verir. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Belge sayfasına yapay olarak yerleştirilen PDF sayfasını ayarlar. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Yapının metnini ayarlar. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Yapının metin ve metin özelliklerini ayarlayın. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Yapının özel değerini ayarlar. |

### Ayrıca bakınız

* class [Artifact](../artifact)
* ad alanı [Aspose.Pdf](../../aspose.pdf)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
