---
title: Class RadioButtonOptionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.RadioButtonOptionField sınıfı. Sınıf, RadioButton alanının bir öğesini temsil eder
type: docs
weight: 5220
url: /tr/net/aspose.pdf.forms/radiobuttonoptionfield/
---
## RadioButtonOptionField sınıfı

Sınıf, RadioButton alanının bir öğesini temsil eder.

```csharp
public sealed class RadioButtonOptionField : Field
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor)() | Yeni bir RadioButtonOptionField örneği oluşturur. |
| [RadioButtonOptionField](radiobuttonoptionfield/#constructor_1)(Sayfa, Dikdörtgen) | Belirtilen sayfadaki belirtilen dikdörtgende radyo düğmesi oluşturur. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Notasyon eylemlerini alır. (2 özellik) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut notasyon görünüm durumunu alır veya ayarlar. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Alanın alternatif adını alır veya ayarlar (Kullanıcı arayüzünde alanın tanımlanacağı yerlerde kullanılacak alternatif bir alan adı). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Bu notasyonun sayfadaki indeksini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Notasyonun türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Caption](../../aspose.pdf.forms/radiobuttonoptionfield/caption/) { get; set; } | Başlığı alır veya ayarlar. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notasyon metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Bu alandaki alt alanların sayısını alır. (Örneğin, radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notasyonun yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Notasyon vurgulama modunu alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Bu alanın terminal olmayan bir alan olup olmadığını belirten boolean değerini alır veya ayarlar, yani alanlar grubudur. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragrafla aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Üretici desteği için özellik. Alan başlık veya alt bilgiye eklendiğinde kullanılır. Eğer true ise, bu alan bir kez oluşturulacak ve görünümü belgenin tüm sayfalarında görünür olacaktır. Eğer false ise, her belge sayfası için ayrı bir alan oluşturulacaktır. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Sözlüğün senkronize olup olmadığını belirten true döner. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Bu alanda bulunan alt alanı alt alanın adıyla alır. (2 indeksleyici) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Belgeden etkileşimli form alanı verilerini dışa aktarırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notasyon adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Notasyon etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| [OptionName](../../aspose.pdf.forms/radiobuttonoptionfield/optionname/) { get; set; } | Seçeneğin adını alır veya ayarlar. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Bu alanı içeren sayfanın indeksini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Notasyonun üst öğesini alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Style](../../aspose.pdf.forms/radiobuttonoptionfield/style/) { get; set; } | Onay kutusunun stilini alır veya ayarlar. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Notasyon için metin hizalamasını alır veya ayarlar. |
| virtual [Value](../../aspose.pdf.forms/field/value/) { get; set; } | Alanın değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(NotasyonSeçici) | Ziyaretçiyi kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matris) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetNotasyonu[], int) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptEylemi) | Alan için belirtilen JavaScript eylemini yürütür. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Akış, DışaAktarmaAlanlarınıJsonSeçenekleri) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu sağlanan akışa yazar. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, DışaAktarmaAlanlarınıJsonSeçenekleri) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu belirtilen dosyaya yazar. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Akış, bool) | Belirtilen alanın içeriğini bir JSON akışına dışa aktarır. Düğme alanı değerleri dışa aktarılmaz. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mevcut durum adlarına göre "kontrol edildi" durumunun adını döner. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | İçerilen alanların enumerator'ünü döner. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notasyonun dikdörtgenini döner. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Akış) | Belirtilen alanlara JSON akışından verileri, alanların tam adlarının tam eşleşmesine dayanarak içe aktarır. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Akış, string) | Belirtilen alana JSON akışından verileri, eşleşme için 'fieldFullNameInJSON' değişkeninde belirtilen tam adı kullanarak içe aktarır. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Form üzerindeki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Nokta) | Alanın konumunu ayarlar. |

### Ayrıca Bakınız

* sınıf [Field](../field/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)