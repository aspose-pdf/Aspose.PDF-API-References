---
title: Class ListBoxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.ListBoxField sınıfı. Sınıf ListBox alanını temsil eder
type: docs
weight: 5130
url: /tr/net/aspose.pdf.forms/listboxfield/
---
## ListBoxField sınıfı

Sınıf ListBox alanını temsil eder.

```csharp
public sealed class ListBoxField : ChoiceField
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [ListBoxField](listboxfield/#constructor)() | Üreticide kullanılacak ListBoxField için yapıcı. |
| [ListBoxField](listboxfield/#constructor_1)(Document, Rectangle) | ListBox alanı için yapıcı. |
| [ListBoxField](listboxfield/#constructor_2)(Page, Rectangle) | Yeni bir ListBox alanı oluşturur. |

## Özellikler

| Ad | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Notasyon eylemlerini alır. (2 özellik) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Mevcut notasyon görünüm durumunu alır veya ayarlar. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Alanın alternatif adını alır veya ayarlar (Kullanıcı arayüzünde alanın tanımlanacağı yerlerde kullanılacak alternatif alan adı). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Bu notasyonun sayfadaki indeksini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Notasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notasyon sınır özelliklerini alır veya ayarlar. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notasyon özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notasyon rengini alır veya ayarlar. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately/) { get; set; } | Seçim değişikliği bayrağını alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notasyon metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Bu alandaki alt alanların sayısını alır. (Örneğin, radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notasyonun yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Notasyon vurgulama modunu alır veya ayarlar. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf üreticisi için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Bu alanın terminal olmayan bir alan olup olmadığını belirten boolean değerini alır veya ayarlar, yani alanlar grubudur. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Üretici desteği için özellik. Alan başlık veya altlık olarak eklendiğinde kullanılır. Eğer true ise, bu alan bir kez oluşturulacak ve görünümü belgenin tüm sayfalarında görünür olacaktır. Eğer false ise, her belge sayfası için ayrı bir alan oluşturulacaktır. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Sözlüğün senkronize olup olmadığını belirten true döner. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Bu alanda bulunan alt alanı alt alanın adıyla alır. (2 indeksleyici) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Belgeden etkileşimli form alanı verilerini dışa aktarırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış marjı alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect/) { get; set; } | Çoklu seçim bayrağını alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notasyon adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Notasyon etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options/) { get; } | Seçenek koleksiyonunu alır. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Bu alanı içeren sayfanın indeksini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Notasyonun üst öğesini alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected/) { set; } | Seçilen öğenin indeksini alır veya ayarlar. Öğeler 1'den numaralandırılır. |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems/) { set; } | Çoklu seçim listesindeki seçilen öğelerin dizisini alır veya ayarlar. Tek seçim listesi için tek bir öğe ile diziyi döner. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Notasyon için metin hizalamasını alır veya ayarlar. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex/) { get; set; } | Listenin en üstteki görünür öğesinin indeksini alır veya ayarlar. |
| override [Value](../../aspose.pdf.forms/choicefield/value/) { get; set; } | Alanın değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Ziyaretçiyi kabul eder. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string) | Belirtilen adla yeni bir seçenek ekler. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption/)(string, string) | Belirtilen dışa aktarma değeri ve adıyla yeni bir seçenek ekler. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Bu örneği klonlar. Sanal yöntem. Her zaman null döner. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption/)(string) | Adına göre seçeneği siler. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Alan için belirtilen JavaScript eylemini yürütür. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu sağlanan akışa yazar. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu belirtilen dosyaya yazar. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Belirtilen alanın içeriğini bir JSON akışına dışa aktarır. Düğme alanı değerleri dışa aktarılmaz. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mevcut durum adlarına göre "kontrol edildi" durumunun adını döner. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | İçerilen alanların enumerator'ünü döner. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notasyonun dikdörtgenini döner. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Alanlara tam adların tam eşleşmesine dayalı olarak JSON akışından veri aktarır. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 'fieldFullNameInJSON' değişkeninde belirtilen tam adı kullanarak JSON akışından belirtilen alana veri aktarır. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Form üzerindeki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Alanın konumunu ayarlar. |

### Ayrıca Bakınız

* sınıf [ChoiceField](../choicefield/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)