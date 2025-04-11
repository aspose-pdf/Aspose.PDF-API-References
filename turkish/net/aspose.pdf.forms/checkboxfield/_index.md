---
title: Class CheckboxField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Forms.CheckboxField sınıfı. Checkbox alanını temsil eden sınıf
type: docs
weight: 4980
url: /tr/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField sınıfı

Checkbox alanını temsil eden sınıf

```csharp
public class CheckboxField : Field
```

## Yapıcılar

| İsim | Açıklama |
| --- | --- |
| [CheckboxField](checkboxfield/#constructor_1)(Document) | Üretici ile kullanılacak yapıcı. |
| [CheckboxField](checkboxfield/#constructor_2)(Document, Rectangle) | CheckboxField sınıfı için yapıcı. |
| [CheckboxField](checkboxfield/#constructor_3)(Page, Rectangle) | CheckboxField sınıfı için yapıcı. |

## Özellikler

| İsim | Açıklama |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions/) { get; } | Notasyon eylemlerini alır. (2 özellik) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate/) { get; set; } | Mevcut notasyon görünüm durumunu alır veya ayarlar. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates/) { get; } | İzin verilen durumların listesini döndürür. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename/) { get; set; } | Alanın alternatif adını alır veya ayarlar (Kullanıcı arayüzünde alanın tanımlanacağı yerlerde kullanılacak alternatif alan adı). Alternatif ad, Adobe Acrobat'ta alan ipucu olarak kullanılır. |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex/) { get; set; } | Bu notasyonun sayfadaki indeksini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype/) { get; } | Notasyon türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Notasyon kenarlık özelliklerini alır veya ayarlar. [`Border`](../../aspose.pdf.annotations/annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Notasyon özelliklerini alır. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked/) { get; set; } | Onay kutusunun durumunu alır veya ayarlar. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Notasyon rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Notasyon metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count/) { get; } | Bu alandaki alt alanların sayısını alır. (Örneğin, radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance/) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable/) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue/) { get; set; } | Checkbox alanının dışa aktarım değerini alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Notasyonun bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Notasyonun tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Notasyonun yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting/) { get; set; } | Notasyon vurgulama modu. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf üreticisi için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Bu paragrafın bir sonraki sütunda olup olmadığını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup/) { get; } | Bu alanın terminal olmayan bir alan yani alanlar grubu olup olmadığını belirten boolean değerini alır veya ayarlar. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Bir paragrafın satır içi olup olmadığını alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Bu paragrafın yeni bir sayfada oluşturulmasını zorlayan bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Mevcut paragrafın bir sonraki paragraf ile aynı sayfada kalıp kalmayacağını belirten bir bool değerini alır veya ayarlar. Varsayılan false'dur. (pdf üretimi için) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield/) { get; set; } | Üretici desteği için özellik. Alan başlık veya altlık olarak eklendiğinde kullanılır. Eğer true ise, bu alan bir kez oluşturulacak ve görünümü belgenin tüm sayfalarında görünür olacaktır. Eğer false ise, her belge sayfası için ayrı bir alan oluşturulacaktır. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized/) { get; } | Sözlüğün senkronize olup olmadığını belirten true döndürür. |
| [Item](../../aspose.pdf.forms/field/item/) { get; } | Bu alanda bulunan alt alanı alt alanın adıyla alır. (2 indeksleyici) |
| [MappingName](../../aspose.pdf.forms/field/mappingname/) { get; set; } | Belgeden etkileşimli form alanı verilerini dışa aktarırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Paragraf için dış kenar boşluğunu alır veya ayarlar (pdf üretimi için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Notasyonun en son ne zaman değiştirildiğini belirten tarih ve saati alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Sayfadaki notasyon adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated/) { get; set; } | Notasyon etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex/) { get; } | Bu alanı içeren sayfanın indeksini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent/) { get; } | Notasyonun üst öğesini alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname/) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly/) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect/) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required/) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Notasyonun görünüm sözlüğünü alır. |
| [Style](../../aspose.pdf.forms/checkboxfield/style/) { get; set; } | Onay kutusunun stilini alır veya ayarlar. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot/) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder/) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Notasyon için metin hizalamasını alır veya ayarlar. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value/) { get; set; } | Onay kutusu alanının değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Paragrafın dikey hizalamasını alır veya ayarlar. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Notasyonun genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Grafiğin Z-sırasını belirten bir int değerini alır veya ayarlar. Daha büyük ZIndex'e sahip bir grafik, daha küçük ZIndex'e sahip grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex'e sahip grafik, sayfadaki metnin arkasında yer alacaktır. |

## Yöntemler

| İsim | Açıklama |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept/)(AnnotationSelector) | Ziyaretçiyi kabul eder. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption)(string) | En fazla bir onay kutusunun işaretlenebileceği bir onay kutusu grubuna yeni bir onay kutusu ekler. Yeni onay kutusu grubun altına eklenir. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_1)(string, Rectangle) | En fazla bir onay kutusunun işaretlenebileceği bir onay kutusu grubuna yeni bir onay kutusu ekler. |
| [AddOption](../../aspose.pdf.forms/checkboxfield/addoption/#addoption_2)(string, int, Rectangle) | En fazla bir onay kutusunun işaretlenebileceği bir onay kutusu grubuna yeni bir onay kutusu ekler. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü günceller. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone/)() | Onay kutusunu klonlar. |
| [CopyTo](../../aspose.pdf.forms/field/copyto/)(WidgetAnnotation[], int) | Bu alanın alt alanlarını belirtilen indeksten başlayarak diziye kopyalar. |
| [ExecuteFieldJavaScript](../../aspose.pdf.forms/field/executefieldjavascript/)(JavascriptAction) | Alan için belirtilen JavaScript eylemini yürütür. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(Stream, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu sağlanan akışa yazar. |
| [ExportToJson](../../aspose.pdf.annotations/widgetannotation/exporttojson/)(string, ExportFieldsToJsonOptions) | Belirtilen PDF form alanını JSON formatına dışa aktarır ve sonucu belirtilen dosyaya yazar. |
| [ExportValueToJson](../../aspose.pdf.forms/field/exportvaluetojson/)(Stream, bool) | Belirtilen alanın içeriğini bir JSON akışına dışa aktarır. Düğme alanı değerleri dışa aktarılmaz. |
| override [Flatten](../../aspose.pdf.forms/field/flatten/)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetCheckedStateName](../../aspose.pdf.annotations/widgetannotation/getcheckedstatename/)() | Mevcut durum adlarına göre "işaretli" durumunun adını döndürür. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator/)() | İçerilen alanların enumerator'ünü döndürür. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Sayfa döndürmesini dikkate alarak notasyonun dikdörtgenini döndürür. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream) | Alanların tam adlarının tam eşleşmesine dayanarak belirtilen alanlara JSON akışından veri aktarır. |
| [ImportValueFromJson](../../aspose.pdf.forms/field/importvaluefromjson/)(Stream, string) | 'fieldFullNameInJSON' değişkeninde belirtilen tam adı kullanarak belirtilen alana JSON akışından veri aktarır. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate/)() | Form üzerindeki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition/)(Point) | Alanın konumunu ayarlar. |

## Örnekler

Örnek, çok değerli bir onay kutusu alanı oluşturmanın nasıl yapılacağını gösterir.

```csharp
using (var document = new Document())
{
var page = document.Pages.Add();

var checkbox = new CheckboxField(page, new Rectangle(50, 50, 70, 70));

// Set the first checkbox group option value
checkbox.ExportValue = "option 1";

// Add new option right under existing ones
checkbox.AddOption("option 2");

// Add new option at the given rectangle
checkbox.AddOption("option 3", new Rectangle(100, 100, 120, 120));

document.Form.Add(checkbox);

// Select the added checkbox
checkbox.Value = "option 2";
document.Save("checkbox_group.pdf");
}
```

### Ayrıca Bakınız

* sınıf [Field](../field/)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms/)
* derleme [Aspose.PDF](../../)