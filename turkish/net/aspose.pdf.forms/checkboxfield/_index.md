---
title: CheckboxField
second_title: Aspose.PDF for .NET API Referansı
description: Onay kutusunu temsil eden sınıf field
type: docs
weight: 2930
url: /tr/net/aspose.pdf.forms/checkboxfield/
---
## CheckboxField class

Onay kutusunu temsil eden sınıf field

```csharp
public class CheckboxField : Field
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [CheckboxField](checkboxfield#constructor)() | CheckboxField. örneğini oluşturun |
| [CheckboxField](checkboxfield#constructor_1)(Document) | Oluşturucu, Generator ile kullanılacak. |
| [CheckboxField](checkboxfield#constructor_2)(Document, Rectangle) | CheckboxField sınıfı için oluşturucu. |
| [CheckboxField](checkboxfield#constructor_3)(Page, Rectangle) | CheckboxField sınıfı için oluşturucu. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/widgetannotation/actions) { get; } | Açıklama eylemlerini alır. (2 properties) |
| override [ActiveState](../../aspose.pdf.forms/checkboxfield/activestate) { get; set; } | Geçerli ek açıklama görünüm durumunu alır veya ayarlar. |
| [AllowedStates](../../aspose.pdf.forms/checkboxfield/allowedstates) { get; } | İzin verilen durumların listesini döndürür. |
| [AlternateName](../../aspose.pdf.forms/field/alternatename) { get; set; } | Alanın alternatif adını alır veya ayarlar (Alanın kullanıcı arabiriminde tanımlanacağı her yerde gerçek alan adı yerine kullanılacak alternatif bir alan adı). Adobe Acrobat'ta alan araç ipucu olarak alternatif ad kullanılır . |
| [AnnotationIndex](../../aspose.pdf.forms/field/annotationindex) { get; set; } | Sayfadaki bu açıklamanın dizinini alır veya ayarlar. |
| override [AnnotationType](../../aspose.pdf.annotations/widgetannotation/annotationtype) { get; } | Açıklama türünü alır. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Açıklama kenarlığı özelliklerini alır veya ayarlar.[`Border`](../../aspose.pdf.annotations/annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Açıklama özelliklerini alır. |
| [Checked](../../aspose.pdf.forms/checkboxfield/checked) { get; set; } | Onay kutusunun durumunu alır veya ayarlar. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Açıklama rengini alır veya ayarlar. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Ek açıklama metnini alır veya ayarlar. |
| [Count](../../aspose.pdf.forms/field/count) { get; } | Bu alandaki alt alanların sayısını alır veya ayarlar. (Örneğin radyo düğmesi alanındaki öğe sayısı). |
| [DefaultAppearance](../../aspose.pdf.annotations/widgetannotation/defaultappearance) { get; set; } | Alanın varsayılan görünümünü alır veya ayarlar. |
| [Exportable](../../aspose.pdf.annotations/widgetannotation/exportable) { get; set; } | Alanın dışa aktarılabilir bayrağını alır veya ayarlar. |
| [ExportValue](../../aspose.pdf.forms/checkboxfield/exportvalue) { get; set; } | CheckBox alanının dışa aktarma değerini alır veya ayarlar. |
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
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Sayfadaki ek açıklama adını alır veya ayarlar. |
| [OnActivated](../../aspose.pdf.annotations/widgetannotation/onactivated) { get; set; } | Açıklama etkinleştirildiğinde gerçekleştirilecek bir eylem. |
| override [PageIndex](../../aspose.pdf.forms/field/pageindex) { get; } | Bu alanı içeren sayfanın dizinini alır. |
| [Parent](../../aspose.pdf.annotations/widgetannotation/parent) { get; } | Üst açıklamayı alır. |
| [PartialName](../../aspose.pdf.forms/field/partialname) { get; set; } | Alanın kısmi adını alır veya ayarlar. |
| [ReadOnly](../../aspose.pdf.annotations/widgetannotation/readonly) { get; set; } | Alanın salt okunur durumunu alır veya ayarlar. |
| override [Rect](../../aspose.pdf.forms/field/rect) { get; set; } | Alan dikdörtgenini alır veya ayarlar. |
| [Required](../../aspose.pdf.annotations/widgetannotation/required) { get; set; } | Alanın gerekli durumunu alır veya ayarlar. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Açıklamanın görünüm sözlüğünü alır. |
| [Style](../../aspose.pdf.forms/checkboxfield/style) { get; set; } | Onay kutusunun stilini alır veya ayarlar. |
| [SyncRoot](../../aspose.pdf.forms/field/syncroot) { get; } | Senkronizasyon nesnesi. |
| [TabOrder](../../aspose.pdf.forms/field/taborder) { get; set; } | Alanın sekme sırasını alır veya ayarlar. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Açıklama için metin hizalamasını alır veya ayarlar. |
| override [Value](../../aspose.pdf.forms/checkboxfield/value) { get; set; } | Onay kutusu alanının değerini alır veya ayarlar. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | paragrafının dikey hizalamasını alır veya ayarlar |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Açıklamanın genişliğini alır veya ayarlar. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Grafiğin Z sırasını gösteren bir int değeri alır veya ayarlar. Daha büyük ZIndex içeren bir grafik, daha küçük ZIndex içeren grafiğin üzerine yerleştirilecektir. ZIndex negatif olabilir. Negatif ZIndex içeren grafik, sayfadaki metnin arkasına yerleştirilecektir. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/widgetannotation/accept)(AnnotationSelector) | Ziyaretçi kabul eder. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Matris dönüşümüne göre parametreleri ve görünümü güncelleyin. |
| override [Clone](../../aspose.pdf.forms/checkboxfield/clone)() | Onay kutusunu kopyalayın. |
| [CopyTo](../../aspose.pdf.forms/field/copyto)(Field[], int) | Belirtilen dizinden başlayarak bu alanın alt alanlarını diziye kopyalar. |
| override [Flatten](../../aspose.pdf.forms/field/flatten)() | Bu alanı kaldırır ve değerini doğrudan sayfaya yerleştirir. |
| [GetEnumerator](../../aspose.pdf.forms/field/getenumerator)() | İçerdiği alanların numaralandırıcısını döndürür. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Sayfa döndürmeyi dikkate alarak açıklamanın dikdörtgenini döndürür. |
| [Recalculate](../../aspose.pdf.forms/field/recalculate)() | Formdaki tüm hesaplanan alanları yeniden hesaplar. |
| virtual [SetPosition](../../aspose.pdf.forms/field/setposition)(Point) | Alanın konumunu ayarlayın. |

### Ayrıca bakınız

* class [Field](../field)
* ad alanı [Aspose.Pdf.Forms](../../aspose.pdf.forms)
* toplantı [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->