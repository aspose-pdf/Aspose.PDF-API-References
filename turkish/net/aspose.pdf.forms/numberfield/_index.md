---
title: Class NumberField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.NumberField sınıfı. Belirtilen geçerli karakterlere sahip Metin Alanı
type: docs
weight: 5140
url: /tr/net/aspose.pdf.forms/numberfield/
---
## NumberField sınıfı

Belirtilen geçerli karakterlere sahip Metin Alanı

```csharp
public class NumberField : TextBoxField
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [NumberField](numberfield/#constructor)() | `NumberField` sınıfının yeni bir örneğini başlatır. |
| [NumberField](numberfield/#constructor_1)(Document, Rectangle) | `NumberField` sınıfının yeni bir örneğini başlatır. |
| [NumberField](numberfield/#constructor_2)(Page, Rectangle) | `NumberField` sınıfının yeni bir örneğini başlatır. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Notasyon eylemlerini alır. (2 özellik) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut notasyon görünüm durumunu alır veya ayarlar. |
| [AllowedChars](../../aspose.pdf.forms/numberfield/allowedchars/) { get; set; } | İzin verilen karakterleri alır veya ayarlar. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Alanın alternatif adını alır veya ayarlar (Kullanıcı arayüzünde alanın tanımlanacağı yerlerde kullanılacak alternatif alan adı). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Sayfadaki bu notasyonun indeksini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Notasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notasyon metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Bu alandaki alt alanların sayısını alır. (Örneğin, radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notasyonun bayrakları. |
| [ForceCombs](../../aspose.pdf.forms/textboxfield/forcecombs/) { get; set; } | Alanın boş pozisyonlara bölünüp bölünmediğini gösteren bayrağı alır veya ayarlar. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notasyonun yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Notasyon vurgulama modunu alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını gösteren bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Bu alanın terminal olmayan bir alan, yani alanlar grubu olup olmadığını gösteren boolean değerini alır. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını gösteren bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf oluşturma için) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Üretici desteği için özellik. Alan başlık veya altlık olarak eklendiğinde kullanılır. Eğer true ise, bu alan bir kez oluşturulacak ve görünümü belgenin tüm sayfalarında görünür olacaktır. Eğer false ise, her belge sayfası için ayrı bir alan oluşturulacaktır. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Sözlüğün senkronize olup olmadığını gösteren true döner. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Bu alanda bulunan alt alanı alt alanın adıyla alır. (2 indeksleyici) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Belgeden etkileşimli form alanı verilerini dışa aktarırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf oluşturma için) |
| [MaxLen](../../aspose.pdf.forms/textboxfield/maxlen/) { get; set; } | Alan içindeki metnin maksimum uzunluğunu alır veya ayarlar. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notasyonun en son ne zaman değiştirildiğini gösteren tarih ve saati alır veya ayarlar. |
| [Multiline](../../aspose.pdf.forms/textboxfield/multiline/) { get; set; } | Alanın çok satırlı bayrağını alır veya ayarlar. Eğer Multiline true ise, alan birden fazla metin satırı içerebilir. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notasyon adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Notasyon etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Bu alanı içeren sayfanın indeksini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Notasyonun ebeveynini alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| [Scrollable](../../aspose.pdf.forms/textboxfield/scrollable/) { get; set; } | Alanın kaydırılabilir bayrağını alır veya ayarlar. Eğer true ise, alan kaydırılabilir. |
| [SpellCheck](../../aspose.pdf.forms/textboxfield/spellcheck/) { get; set; } | Alan için yazım denetimi bayrağını alır veya ayarlar. Eğer true ise, alan yazım denetimine tabi tutulacaktır. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Notasyon için metin hizalamasını alır veya ayarlar. |
| [TextVerticalAlignment](../../aspose.pdf.forms/textboxfield/textverticalalignment/) { get; set; } | Notasyon için metin dikey hizalamasını alır veya ayarlar. |
| override [Value](../../aspose.pdf.forms/textboxfield/value/) { get; set; } | Alanın değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını gösteren bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Ziyaretçiyi kabul eder. |
| [AddBarcode](../../aspose.pdf.forms/textboxfield/addbarcode/)(string) | Alana 128 barkod ekler. Alan değeri koda değiştirilecek ve alan salt okunur hale gelecektir. |
| [AddImage](../../aspose.pdf.forms/textboxfield/addimage/)(Image) | Alan kaynaklarına resim ekler ve çizer. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği kopyalar. Sanal yöntem. Her zaman null döner. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Alan için belirtilen JavaScript eylemini yürütür. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu sağlanan akışa yazar. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu belirtilen dosyaya yazar. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Belirtilen alanın içeriğini bir JSON akışına dışa aktarır. Düğme alanı değerleri dışa aktarılmaz. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mevcut durum adlarına göre "kontrol edildi" durumunun adını döner. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | İçerilen alanların enumerator'ünü döner. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notasyonun dikdörtgenini döner. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Tam adların tam eşleşmesine dayanarak, belirtilen alanlara JSON akışından veri aktarır. |
| [ImportValueFromJson](../../aspose.pdf/forms/field/importvaluefromjson/)(Stream, string) | 'fieldFullNameInJSON' değişkeninde belirtilen tam adı kullanarak, belirtilen alana JSON akışından veri aktarır. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Form üzerindeki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Alanın konumunu ayarlar. |

### Ayrıca Bakınız

* sınıf [TextBoxField](../textboxfield/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)