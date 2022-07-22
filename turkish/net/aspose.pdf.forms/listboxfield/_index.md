---
title: ListBoxField
second_title: Aspose.PDF for .NET API Referansı
description: Sınıf ListBox alanını temsil eder.
type: docs
weight: 3080
url: /tr/net/aspose.pdf.forms/listboxfield/
---
## ListBoxField class

Sınıf, ListBox alanını temsil eder.

```csharp
public sealed class ListBoxField : ChoiceField
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [ListBoxField](listboxfield#constructor)() | Generator'da kullanılacak ListBoxField için yapıcı. |
| [ListBoxField](listboxfield#constructor_1)(Document, Rectangle) | ListBox alanı için oluşturucu. |
| [ListBoxField](listboxfield#constructor_2)(Page, Rectangle) | Yeni Liste Kutusu alanı oluşturur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Açıklama eylemlerini alır. (2 properties) |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Alanın alternatif adını alır veya ayarlar (Alanın kullanıcı arabiriminde tanımlanacağı her yerde gerçek alan adı yerine kullanılacak alternatif bir alan adı). Adobe Acrobat'ta alan araç ipucu olarak alternatif ad kullanılır . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Sayfadaki bu açıklamanın dizinini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [CommitImmediately](../../aspose.pdf.forms/choicefield/commitimmediately) { get; set; } | Seçim değişikliği bayrağına bağlılığı alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Bu alandaki alt alanların sayısını alır veya ayarlar. (Örneğin radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Ek açıklamanın bayrakları. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Açıklamanın tam nitelikli adını alır. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Açıklamanın yüksekliğini alır veya ayarlar. |
| [Highlighting](../../aspose.pdf.annotations/widgetannotation/highlighting) { get; set; } | Açıklama vurgulama modu. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Parça köprüsünü alır veya ayarlar (pdf oluşturucu için). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Bu paragrafın sonraki sütunda olup olmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsGroup](../../aspose.pdf.forms/field/isgroup) { get; } | Bu alanın terminal olmayan alan, yani alanlar grubu olduğunu gösteren boole değerini alır veya ayarlar. |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Satır içi bir paragraf alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Bu paragrafı yeni sayfada oluşturmaya zorlayan bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Geçerli paragrafın sonraki paragrafla birlikte aynı sayfada kalıp kalmayacağını belirten bir bool değeri alır veya ayarlar. Varsayılan yanlıştır.(pdf oluşturma için) |
| [IsSharedField](../../aspose.pdf.forms/field/issharedfield) { get; set; } | Jeneratör desteği için Özellik. Üstbilgiye veya altbilgiye alan eklendiğinde kullanılır. True ise, bu alan bir kez oluşturulacak ve görünümü belgenin tüm sayfalarında görünecektir. Yanlış ise, her belge sayfası için ayrılmış alan oluşturulur. |
| [IsSynchronized](../../aspose.pdf.forms/field/issynchronized) { get; } | Sözlük senkronize edilmişse true değerini döndürür. |
| [Item](../../aspose.pdf.forms/field/item) { get; } | Bu alanda bulunan alt alanı alt alan adına göre alır. (2 indexers) |
| [MappingName](../../aspose.pdf.forms/field/mappingname) { get; set; } | Etkileşimli form alanı verilerini belgeden dışa aktarırken kullanılacak alanın eşleme adını alır veya ayarlar. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Paragraf için bir dış kenar boşluğu alır veya ayarlar (pdf oluşturma için) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Açıklamanın yakın zamanda değiştirildiği tarih ve saati alır veya ayarlar. |
| [MultiSelect](../../aspose.pdf.forms/choicefield/multiselect) { get; set; } | Çoklu seçim bayrağını alır veya ayarlar. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Sayfadaki ek açıklama adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Açıklama etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| virtual [Options](../../aspose.pdf.forms/choicefield/options) { get; } | Seçim seçenekleri koleksiyonunu alır. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Bu alanı içeren sayfanın dizinini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Üst açıklamayı alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| override [Selected](../../aspose.pdf.forms/listboxfield/selected) { set; } | Seçili öğenin dizinini alır veya ayarlar. Öğeler 1. ile numaralandırılmıştır |
| override [SelectedItems](../../aspose.pdf.forms/listboxfield/selecteditems) { set; } | Çoklu seçim listesindeki seçili öğelerin dizisini alır veya ayarlar. Tek seçimli liste için tek öğeli dizi döndürür. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Açıklama için metin hizalamasını alır veya ayarlar. |
| [TopIndex](../../aspose.pdf.forms/listboxfield/topindex) { get; set; } | Listenin en üstteki görünen öğesinin dizinini alır veya ayarlar. |
| override [Value](../../aspose.pdf.forms/choicefield/value) { get; set; } | Alanın değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Ziyaretçi kabul eder. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string) | Belirtilen adla yeni seçenek ekler. |
| virtual [AddOption](../../aspose.pdf.forms/choicefield/addoption)(string, string) | Belirtilen dışa aktarma değeri ve adıyla yeni seçenek ekler. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü güncelleyin. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Bu örneği klonlar. Sanal yöntem. Her zaman null. döndür |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Belirtilen dizinden başlayarak bu alanın alt alanlarını diziye kopyalar. |
| virtual [DeleteOption](../../aspose.pdf.forms/choicefield/deleteoption)(string) | Seçeneği adıyla siler. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | İçerdiği alanların numaralandırıcısını döndürür. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Formdaki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Alanın konumunu ayarlayın. |

### Ayrıca bakınız

* class [ChoiceField](../choicefield)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
