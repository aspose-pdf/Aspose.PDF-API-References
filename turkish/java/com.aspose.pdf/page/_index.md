---
title: "Page"
linktitle: "Page"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesinin sayfasını temsil eden sınıf."
type: docs
weight: 3310
url: /tr/java/com.aspose.pdf/page/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Page

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, com.aspose.pdf.engine.IOperatorContainer, Closeable, AutoCloseable

```
public final class Page extends Object implements com.aspose.ms.System.IDisposable, Closeable , com.aspose.pdf.engine.IOperatorContainer
```

PDF belgesinin sayfasını temsil eden sınıf.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [accept](#accept-com.aspose.pdf.AnnotationSelector-) | {@code AnnotationSelector} ziyaretçi nesnesini kabul eder ve ek açıklamalarla çalışmak için işlevsellik sağlar. |
| [accept](#accept-com.aspose.pdf.ImagePlacementAbsorber-) | Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan {@code ImagePlacementAbsorber} ziyaretçi nesnesini kabul eder. |
| [accept](#accept-com.aspose.pdf.TextAbsorber-) | Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextAbsorber} ziyaretçi nesnesini kabul eder. |
| [accept](#accept-com.aspose.pdf.TextFragmentAbsorber-) | Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextFragmentAbsorber} ziyaretçi nesnesini kabul eder. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Sayfaya grafik ekler. GraphicElement#addOnPage(Page) yöntemiyle öğeleri tek tek eklemekten daha hızlı çalışır. |
| [addGraphics](#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-) | Sayfaya grafik ekler. GraphicElement#addOnPage(Page) yöntemiyle öğeleri tek tek eklemekten daha hızlı çalışır. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-) | Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-) | Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-) | Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-) | Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-) | Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-) | Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-) | Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addImage](#addImage-java.lang.String-com.aspose.pdf.Rectangle-) | Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur. |
| [addStamp](#addStamp-com.aspose.pdf.Stamp-) | Sayfaya damga koyar. Damga sayfa numarası, resim veya basit metin olabilir, ör. bir logo. |
| [asByteArray](#asByteArray-com.aspose.pdf.devices.Resolution-) | Mevcut sayfayı BMP bitmap olarak dönüştürür ve ardından bayt dizisini döndürür. |
| [asXml](#asXml--) | Mevcut sayfayı UTF-8 kodlamalı XML olarak dönüştürür. |
| [calculateContentBBox](#calculateContentBBox--) | bbox değerini hesaplar - içeriği görünür kenar boşlukları olmadan içeren dikdörtgen. |
| [clearContents](#clearContents--) | Yalnızca dahili kullanım için |
| [close](#close--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [convertToPNGMemoryStream](#convertToPNGMemoryStream--) | Sayfayı DSR, OMR, OCR görüntü akışı için PNG'ye dönüştür. |
| [deleteGraphics](#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-) | Sayfadan grafikleri siler. {@link GraphicElement#remove} yöntemiyle öğeleri tek tek silmekten daha hızlı çalışır. |
| [deleteUnusedResources](#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-) |  |
| [dispose](#dispose--) | Belleği serbest bırakır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın. |
| [fillUsedObjectsTable](#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-) |  |
| [findReferences](#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Belirtilen isimdeki kaynağı kullanan operatörlerin listesini döndürür. |
| [findReferences](#findReferences-java.lang.String-) | <p> Referansları bul </p> |
| [flatten](#flatten--) | Sayfada bulunan tüm statik alanları kaldırır ve yerine değerlerini yerleştirir. |
| [freeMemory](#freeMemory--) | Önbelleğe alınmış verileri temizler |
| [getActions](#getActions--) | Sayfa özelliklerinin koleksiyonunu alır. |
| [getAnnotations](#getAnnotations--) | Sayfa ek açıklamalarının koleksiyonunu alır. {@code Annotations} |
| [getArtBox](#getArtBox--) | <p> Sayfanın art kutusunu alır. </p> |
| [getArtifacts](#getArtifacts--) | Sayfadaki artefaktların koleksiyonunu alır. |
| [getBackground](#getBackground--) | Sayfanın arka plan rengini alır. |
| [getBackgroundImage](#getBackgroundImage--) | Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [getBleedBox](#getBleedBox--) | <p> Sayfanın bleed kutusunu alır. </p> |
| [getColorType](#getColorType--) | Sayfaların renk tipini, SetColor operatörlerinden, görüntülerden ve formlardan alınan bilgilere dayanarak alır. |
| [getContents](#getContents--) | <p> Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. {@code OperatorCollection} </p> |
| [getContentsAppender](#getContentsAppender--) | Mevcut içerik ekleyiciyi alır. {@code ContentsAppender} |
| [getCropBox](#getCropBox--) | <p> Sayfanın kırpma kutusunu alır. </p> |
| [getDocument](#getDocument--) | Belgeyi al |
| [getDuration](#getDuration--) | <p> Sayfanın gösterim süresini alır. Bu, sayfanın sunum sırasında saniye cinsinden gösterileceği süredir. Süre tanımlı değilse -1 döndürür. </p> <hr> Örnek, sayfa süresinin nasıl alınacağını gösterir <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p> |
| [getEnginePage](#getEnginePage--) | Yalnızca dahili kullanım için |
| [getFieldsInTabOrder](#getFieldsInTabOrder--) | Bu sayfadaki sekme sırasındaki Field nesnelerinin listesini alır. |
| [getFooter](#getFooter--) | Sayfanın alt bilgisini alır. |
| [getGroup](#getGroup--) | Sayfanın sayfa grubunun özelliklerini belirten bir grup öznitelik sınıfını alır; bu, şeffaf görüntüleme modelinde kullanılmak içindir. |
| [getHeader](#getHeader--) | Sayfanın üst bilgisini alır. |
| [getLayers](#getLayers--) | Katman koleksiyonunu alır. |
| [getMediaBox](#getMediaBox--) | <p> Sayfanın medya kutusunu alır. </p> |
| [getNoteLineStyle](#getNoteLineStyle--) | Notlar için satır stilini alır. (sadece oluşturucu için, belge okunurken doldurulmaz) |
| [getNotifications](#getNotifications--) | Sayfa içeriğiyle ilgili iç işlemler hakkında bildirimleri döndürür. (Şu anda yalnızca metin ekleme senaryolarındaki paragraf olaylarıyla ilgili bildirimler desteklenmektedir.) |
| [getNumber](#getNumber--) | Sayfanın numarasını al. |
| [getOnBeforePageGenerate](#getOnBeforePageGenerate--) | Üst ve alt bilgileri özelleştirmek için olay. |
| [getPageInfo](#getPageInfo--) | Sayfa bilgisini alır. (sadece oluşturucu için, belge okunurken doldurulmaz). |
| [getPageRect](#getPageRect-boolean-) | Sayfanın CropBox'ına (veya CropBox null ise MediaBox'a) göre dikdörtgenini döndürür. |
| [getParagraphs](#getParagraphs--) | Paragrafları alır. |
| [getRect_Rename_Namesake](#getRect_Rename_Namesake--) | <p> Sayfanın CropBox ve MediaBox değerlerine göre dikdörtgenini döndürür; </p> Internal |
| [getRect](#getRect--) | <p> Sayfanın CropBox ve MediaBox değerlerine göre dikdörtgenini döndürür; Alırken: sayfa crop kutusu belirtilmişse o döndürülür, aksi takdirde sayfa media kutusu döndürülür. Ayarlarken: sayfa media kutusu her zaman ayarlanır. </p> |
| [getResources](#getResources--) | Sayfayla ilişkili kaynakları alır. |
| [getResourcesField](#getResourcesField--) | <p> Sayfa kaynaklarını alır. Resources nesnesi görüntüler, formlar ve yazı tiplerinin koleksiyonlarını içerir. {@code Resources} </p> |
| [getRotate](#getRotate--) | <p> Sayfanın dönüşünü alır. </p> |
| [getRotationMatrix](#getRotationMatrix--) | Sayfa için dönüşüm matrisini alır. |
| [getTabOrder](#getTabOrder--) | Sayfanın sekme sırasını alır. Olası değerler: Row, Column. Varsayılan, Manual |
| [getTocInfo](#getTocInfo--) | İçindekiler tablosu bilgilerini alır. |
| [getTrimBox](#getTrimBox--) | <p> Sayfanın kırpma kutusunu alır. </p> |
| [getUserUnit](#getUserUnit--) | UserUnit değerini alır veya ayarlar. 1 / 72 inç'in katları şeklinde, varsayılan kullanıcı uzayı birimlerinin boyutunu veren pozitif bir sayıdır. Varsayılan değer 1'dir. Bu girişin sayfada temizlenmesi için sıfır veya negatif değer ayarlayın. |
| [getWatermark](#getWatermark--) | Sayfanın filigranını alır. |
| [hasVectorGraphics](#hasVectorGraphics--) | Sayfada varsa, vektör grafiklerinin varlığını algılar. |
| [intToRotation](#intToRotation-int-) | Tam sayı değerini karşılık gelen dönüşüm enum üyesine çevirir. |
| [isAddParagraphsAfterLast](#isAddParagraphsAfterLast--) | Sayfanın son paragrafından sonra paragraf eklenmesini alır veya ayarlar. Değer: Değer, paragrafın sayfanın son paragrafından sonra eklenip eklenmeyeceğini gösterir. Değer true ise, paragraf sayfanın son paragrafından sonra eklenecektir. |
| [isBlank](#isBlank-double-) | Sayfanın boş olup olmadığını gösteren bayrağı alır. |
| [isBlank](#isBlank-double-boolean-) | Sayfanın boş olup olmadığını gösteren bayrağı alır. |
| [makeGrayscale](#makeGrayscale--) | Sayfayı gri tonlamaya dönüştürür. |
| [mergeLayers](#mergeLayers-java.lang.String-) | Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmanda birleştirir. |
| [mergeLayers](#mergeLayers-java.lang.String-java.lang.String-) | Sayfadaki tüm katmanları belirtilen yeni katman adı ve isteğe bağlı içerik grup kimliği ile tek bir katmanda birleştirir. |
| [removeObjectReferences](#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-) | Nesne referanslarını kaldır. |
| [removeObjectReferences](#removeObjectReferences-java.lang.String-) | Sayfa içeriklerinden XObject referanslarını kaldır (ör. nesne adını kullanan tüm Do operatörleri). |
| [resize](#resize-com.aspose.pdf.PageSize-) | Sayfanın boyutunu değiştirir. |
| [rotationToInt](#rotationToInt-com.aspose.pdf.Rotation-) | Dönüşüm enum üyesini tam sayı değerine çevirir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-) | Sayfayı verilen sayfa cihazı ile işleme gönderir. |
| [sendTo](#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-) | Sayfayı verilen sayfa cihazı ile işleme gönderir. |
| [setAddParagraphsAfterLast](#setAddParagraphsAfterLast-boolean-) | Sayfanın son paragrafından sonra paragraf eklenmesini alır veya ayarlar. Değer: Değer, paragrafın sayfanın son paragrafından sonra eklenip eklenmeyeceğini gösterir. Değer true ise, paragraf sayfanın son paragrafından sonra eklenecektir. |
| [setArtBox](#setArtBox-com.aspose.pdf.Rectangle-) | Sayfanın art kutusunu ayarlar. |
| [setBackground](#setBackground-java.awt.Color-) | Sayfanın arka plan rengini ayarlar. |
| [setBackground](#setBackground-com.aspose.pdf.Color-) | Sayfanın arka plan rengini ayarlar. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [setBleedBox](#setBleedBox-com.aspose.pdf.Rectangle-) | Sayfanın taşma kutusunu ayarlar. |
| [setCropBox](#setCropBox-com.aspose.pdf.Rectangle-) | <p> Sayfanın kırpma kutusunu ayarlar. </p> <hr> <pre> Örnek, sayfanın kırpma kutusunun nasıl alınacağını gösterir: Document document = new Document(\"sample.pdf\"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre> |
| [setDuration](#setDuration-double-) | Sayfanın görüntülenme süresini ayarlar. Bu, sayfanın sunum sırasında saniye cinsinden gösterileceği süredir. Süre tanımlı değilse -1 döndürür. |
| [setEnginePage](#setEnginePage-com.aspose.pdf.engine.commondata.IPage-) | Yalnızca dahili kullanım için |
| [setFooter](#setFooter-com.aspose.pdf.HeaderFooter-) | Sayfanın altbilgisini ayarlar. |
| [setGroup](#setGroup-com.aspose.pdf.Group-) | Sayfanın sayfa grubunun özelliklerini şeffaf görüntüleme modelinde kullanmak için belirten bir grup öznitelik sınıfını ayarlar. |
| [setHeader](#setHeader-com.aspose.pdf.HeaderFooter-) | Sayfa başlığını ayarlar. |
| [setLayers](#setLayers-java.util.ArrayList-) | Katman koleksiyonunu ayarlar. |
| [setLayersInternal](#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-) | Katman koleksiyonunu ayarlar. |
| [setMediaBox](#setMediaBox-com.aspose.pdf.Rectangle-) | Sayfanın medya kutusunu ayarlar. |
| [setNoteLineStyle](#setNoteLineStyle-com.aspose.pdf.GraphInfo-) | Notlar için satır stilini ayarlar.(yalnızca oluşturucu için, belge okunurken doldurulmaz) |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Sayfa bilgisini ayarlar.(yalnızca oluşturucu için, belge okunurken doldurulmaz). |
| [setPageSize](#setPageSize-double-double-) | Sayfa boyutunu ayarlar. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Paragrafları ayarlar. |
| [setRect](#setRect-com.aspose.pdf.Rectangle-) | Sayfanın dikdörtgenini alır veya ayarlar. Alım için: sayfa kırpma kutusu belirtilmişse döndürülür, aksi takdirde sayfa medya kutusu döndürülür. Ayarlama için: sayfa medya kutusu her zaman ayarlanır. döndürülür. Lütfen bu özelliğin sayfa dönüşünü dikkate almadığını unutmayın. Dönüşü dikkate alarak sayfa dikdörtgenini almak için lütfen ActualRect kullanın. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Sayfanın dönüşünü ayarlar. |
| [setTabOrder](#setTabOrder-int-) | Sayfanın sekme sırasını ayarlar. Olası değerler: Row, Column. Varsayılan, Manual |
| [setTocInfo](#setTocInfo-com.aspose.pdf.TocInfo-) | İçindekiler tablosu bilgisini ayarlar. |
| [setTransition](#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-) | Geçişi ayarlar. |
| [setTrimBox](#setTrimBox-com.aspose.pdf.Rectangle-) | Sayfanın kırpma kutusunu ayarlar. |
| [setUserUnit](#setUserUnit-double-) | UserUnit değerini alır veya ayarlar. 1 / 72 inç'in katları şeklinde, varsayılan kullanıcı uzayı birimlerinin boyutunu veren pozitif bir sayıdır. Varsayılan değer 1'dir. Bu girişin sayfada temizlenmesi için sıfır veya negatif değer ayarlayın. |
| [setWatermark](#setWatermark-com.aspose.pdf.Watermark-) | Sayfanın filigranını ayarlar. |
| [trySaveVectorGraphics](#trySaveVectorGraphics-java.lang.String-) | Sayfada mevcutsa vektör grafikleri kaydetmeye çalışır. Kaydetme formatı SVG'dir. |

### accept {#accept-com.aspose.pdf.AnnotationSelector-}
{@code AnnotationSelector} ziyaretçi nesnesini kabul eder ve ek açıklamalarla çalışmak için işlevsellik sağlar.

### accept {#accept-com.aspose.pdf.ImagePlacementAbsorber-}
Görüntü yerleştirme nesneleriyle çalışmak için işlevsellik sağlayan {@code ImagePlacementAbsorber} ziyaretçi nesnesini kabul eder.

### accept {#accept-com.aspose.pdf.TextAbsorber-}
Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextAbsorber} ziyaretçi nesnesini kabul eder.

### accept {#accept-com.aspose.pdf.TextFragmentAbsorber-}
Metin nesneleriyle çalışmak için işlevsellik sağlayan {@code TextFragmentAbsorber} ziyaretçi nesnesini kabul eder.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Sayfaya grafik ekler. GraphicElement#addOnPage(Page) yöntemiyle öğeleri tek tek eklemekten daha hızlı çalışır.

### addGraphics {#addGraphics-com.aspose.pdf.vector.GraphicElementCollection-com.aspose.pdf.Rectangle-}
Sayfaya grafik ekler. GraphicElement#addOnPage(Page) yöntemiyle öğeleri tek tek eklemekten daha hızlı çalışır.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-}
Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-}
Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-int-int-boolean-com.aspose.pdf.Rectangle-}
Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-}
Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-com.aspose.pdf.CompositingParameters-boolean-}
Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-}
Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.lang.String-java.io.InputStream-com.aspose.pdf.Rectangle-com.aspose.pdf.Rectangle-}
Sayfaya aranabilir bir resim ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addImage {#addImage-java.lang.String-com.aspose.pdf.Rectangle-}
Sayfaya resmi ekler ve belirtilen dikdörtgenin ortasına yerleştirerek resmin oranını korur.

### addStamp {#addStamp-com.aspose.pdf.Stamp-}
Sayfaya damga koyar. Damga sayfa numarası, resim veya basit metin olabilir, ör. bir logo.

### asByteArray {#asByteArray-com.aspose.pdf.devices.Resolution-}
Mevcut sayfayı BMP bitmap olarak dönüştürür ve ardından bayt dizisini döndürür.

### asXml {#asXml--}
```
public String asXml()
```

Mevcut sayfayı UTF-8 kodlamalı XML olarak dönüştürür.

**Returns:**
Dönüştürülmüş xml dizesi.

### calculateContentBBox {#calculateContentBBox--}
```
public Rectangle calculateContentBBox()
```

bbox değerini hesaplar - içeriği görünür kenar boşlukları olmadan içeren dikdörtgen.

**Returns:**
Bbox değeri - görünür kenar boşlukları olmadan içeriği içeren dikdörtgen

### clearContents {#clearContents--}
```
public void clearContents()
```

Yalnızca dahili kullanım için

### close {#close--}
```
public void close()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır.

### convertToPNGMemoryStream {#convertToPNGMemoryStream--}
```
public byte[] convertToPNGMemoryStream()
```

Sayfayı DSR, OMR, OCR görüntü akışı için PNG'ye dönüştür.

**Returns:**
byte[] dizisindeki görüntü akışı.

### deleteGraphics {#deleteGraphics-com.aspose.pdf.vector.GraphicElementCollection-}
Sayfadan grafikleri siler. {@link GraphicElement#remove} yöntemiyle öğeleri tek tek silmekten daha hızlı çalışır.

### deleteUnusedResources {#deleteUnusedResources-com.aspose.ms.System.Collections.Generic.Dictionary-}


### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Belleği serbest bırakır. Bu yöntem artık kullanılmamaktadır, yerine close() kullanın.

### fillUsedObjectsTable {#fillUsedObjectsTable-com.aspose.ms.System.Collections.Generic.Dictionary-com.aspose.pdf.engine.data.IPdfDictionary-}


### findReferences {#findReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Belirtilen isimdeki kaynağı kullanan operatörlerin listesini döndürür.

### findReferences {#findReferences-java.lang.String-}
<p> Referansları bul </p>

### flatten {#flatten--}
```
public void flatten()
```

Sayfada bulunan tüm statik alanları kaldırır ve yerine değerlerini yerleştirir.

### freeMemory {#freeMemory--}
```
public void freeMemory()
```

Önbelleğe alınmış verileri temizler

### getActions {#getActions--}
```
public PageActionCollection getActions()
```

Sayfa özelliklerinin koleksiyonunu alır.

**Returns:**
PageActionCollection değeri

### getAnnotations {#getAnnotations--}
```
public AnnotationCollection getAnnotations()
```

Sayfa ek açıklamalarının koleksiyonunu alır. {@code Annotations}

**Returns:**
AnnotationCollection değeri

### getArtBox {#getArtBox--}
```
public Rectangle getArtBox()
```

<p> Sayfanın art kutusunu alır. </p>

**Returns:**
Dikdörtgen değeri <hr> <pre> Örnek, sayfanın art kutusunun nasıl alınacağını gösterir: Document document = new Document(\"sample.pdf\"); Rectangle artBox = document.getPages().get(1).getArtBox(); </pre>

### getArtifacts {#getArtifacts--}
```
public ArtifactCollection getArtifacts()
```

Sayfadaki artefaktların koleksiyonunu alır.

**Returns:**
ArtifactCollection değeri

### getBackground {#getBackground--}
```
public Color getBackground()
```

Sayfanın arka plan rengini alır.

**Returns:**
Renk değeri

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz).

**Returns:**
Görüntü örneği

### getBleedBox {#getBleedBox--}
```
public Rectangle getBleedBox()
```

<p> Sayfanın bleed kutusunu alır. </p>

**Returns:**
Dikdörtgen değeri <hr> <pre> Örnek, sayfanın bleed kutusunun nasıl alınacağını gösterir: Document document = new Document(\"sample.pdf\"); Rectangle bleedBox = document.getPages().get(1).getBleedBox(); </pre>

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Sayfaların renk tipini, SetColor operatörlerinden, görüntülerden ve formlardan alınan bilgilere dayanarak alır.

**Returns:**
ColorType öğesi @see ColorType

### getContents {#getContents--}
```
public OperatorCollection getContents()
```

<p> Sayfanın içerik akışındaki operatörlerin koleksiyonunu alır. {@code OperatorCollection} </p>

**Returns:**
OperatorCollection nesnesi <hr> <pre> Örnek, sayfanın operatör akışının nasıl taranacağını gösterir. Document document = new Document(\"sample.pdf\"); Operators contents = document.getPages().get_Item(1).getContents(); for(Operator op : {@code (Iterable<Operator>)}contents) { System.out.println(op); } </pre>

### getContentsAppender {#getContentsAppender--}
```
public ContentsAppender getContentsAppender()
```

Mevcut içerik ekleyiciyi alır. {@code ContentsAppender}

**Returns:**
ContentsAppender değeri

### getCropBox {#getCropBox--}
```
public Rectangle getCropBox()
```

<p> Sayfanın kırpma kutusunu alır. </p>

**Returns:**
Rectangle değeri <hr> <pre> Örnek, sayfanın kırpma kutusunu nasıl alacağını gösterir: Document document = new Document("sample.pdf"); Rectangle cropBox = document.getPages().get_Item(1).getCropBox(); </pre>

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

Belgeyi al

**Returns:**
IDocument nesnesi

### getDuration {#getDuration--}
```
public double getDuration()
```

<p> Sayfanın gösterim süresini alır. Bu, sayfanın sunum sırasında saniye cinsinden gösterileceği süredir. Süre tanımlı değilse -1 döndürür. </p> <hr> Örnek, sayfa süresinin nasıl alınacağını gösterir <p> Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); int pageRect = page.getDuration(); </p>

**Returns:**
double değer

### getEnginePage {#getEnginePage--}
```
public com.aspose.pdf.engine.commondata.IPage getEnginePage()
```

Yalnızca dahili kullanım için

**Returns:**
dahili örnek

### getFieldsInTabOrder {#getFieldsInTabOrder--}
```
public List < Field > getFieldsInTabOrder()
```

Bu sayfadaki sekme sırasındaki Field nesnelerinin listesini alır.

**Returns:**
Alan nesnelerinin listesi

### getFooter {#getFooter--}
```
public HeaderFooter getFooter()
```

Sayfanın alt bilgisini alır.

**Returns:**
Sayfa Altbilgisi.

### getGroup {#getGroup--}
```
public Group getGroup()
```

Sayfanın sayfa grubunun özelliklerini belirten bir grup öznitelik sınıfını alır; bu, şeffaf görüntüleme modelinde kullanılmak içindir.

**Returns:**
Grup değeri

### getHeader {#getHeader--}
```
public HeaderFooter getHeader()
```

Sayfanın üst bilgisini alır.

**Returns:**
Sayfa üstbilgisi.

### getLayers {#getLayers--}
```
public List < Layer > getLayers()
```

Katman koleksiyonunu alır.

**Returns:**
Değer: Katmanların koleksiyonu.

### getMediaBox {#getMediaBox--}
```
public Rectangle getMediaBox()
```

<p> Sayfanın medya kutusunu alır. </p>

**Returns:**
Rectangle değeri <hr> <pre> Örnek, sayfanın medya kutusunu nasıl alacağını gösterir: Document document = new Document("sample.pdf"); Rectangle mediaBox = document.getPages().get(1).getMediaBox(); </pre>

### getNoteLineStyle {#getNoteLineStyle--}
```
public GraphInfo getNoteLineStyle()
```

Notlar için satır stilini alır. (sadece oluşturucu için, belge okunurken doldurulmaz)

**Returns:**
GraphInfo değeri

### getNotifications {#getNotifications--}
```
public String getNotifications()
```

Sayfa içeriğiyle ilgili iç işlemler hakkında bildirimleri döndürür. (Şu anda yalnızca metin ekleme senaryolarındaki paragraf olaylarıyla ilgili bildirimler desteklenmektedir.)

**Returns:**
Sayfa içeriğiyle ilgili iç işlemler hakkında bildirimleri temsil eden dize.

### getNumber {#getNumber--}
```
public final int getNumber()
```

Sayfanın numarasını al.

**Returns:**
int değer

### getOnBeforePageGenerate {#getOnBeforePageGenerate--}
```
public PdfEvent < Page.BeforePageGenerate > getOnBeforePageGenerate()
```

Üst ve alt bilgileri özelleştirmek için olay.

**Returns:**
{@code PdfEvent<BeforePageGenerate> instance}

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Sayfa bilgisini alır. (sadece oluşturucu için, belge okunurken doldurulmaz).

**Returns:**
Sayfa bilgisi.

### getPageRect {#getPageRect-boolean-}
```
public Rectangle getPageRect(boolean considerRotation)
```

Sayfanın CropBox'ına (veya CropBox null ise MediaBox'a) göre dikdörtgenini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| considerRotation |  | Doğru ise sayfanın dönüşü, dikdörtgen hesabında dikkate alınacaktır. |

**Returns:**
Sayfanın dikdörtgeni.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Paragrafları alır.

**Returns:**
Paragraflar.

### getRect_Rename_Namesake {#getRect_Rename_Namesake--}
```
public Rectangle getRect_Rename_Namesake()
```

<p> Sayfanın CropBox ve MediaBox değerlerine göre dikdörtgenini döndürür; </p> Internal

**Returns:**
Rectangle değeri <hr> <pre> Örnek, sayfa dikdörtgenini nasıl alacağını gösterir: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getRect {#getRect--}
```
public Rectangle getRect()
```

<p> Sayfanın CropBox ve MediaBox değerlerine göre dikdörtgenini döndürür; Alırken: sayfa crop kutusu belirtilmişse o döndürülür, aksi takdirde sayfa media kutusu döndürülür. Ayarlarken: sayfa media kutusu her zaman ayarlanır. </p>

**Returns:**
Rectangle değeri <hr> <pre> Örnek, sayfa dikdörtgenini nasıl alacağını gösterir: Document document = new Document("sample.pdf"); Page page = document.getPages().get(1); Rectangle pageRect = page.getRect(); </pre>

### getResources {#getResources--}
```
public final Resources getResources()
```

Sayfayla ilişkili kaynakları alır.

**Returns:**
Sayfanın kaynaklarını temsil eden bir {@code Resources}({@link #getResources()}) nesnesi.

### getResourcesField {#getResourcesField--}
```
public Resources getResourcesField()
```

<p> Sayfa kaynaklarını alır. Resources nesnesi görüntüler, formlar ve yazı tiplerinin koleksiyonlarını içerir. {@code Resources} </p>

**Returns:**
Resources değeri <hr> <pre> Örnek, sayfa görüntüleri arasında taramayı gösterir: Document document = new Document("sample.pdf"); DocumentActions actions = document.getActions(); Resources resources = document.getPages().get(1).getResources(); for(XImage image : {@code (Iterable<XImage>)resources}.getImages()) { System.out.println(image.getWidth() + ":" + image.getHeight()); } </pre>

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

<p> Sayfanın dönüşünü alır. </p>

**Returns:**
Dönüş öğesi <hr> <pre> Örnek, sayfa dönüşünü nasıl belirleyeceğini gösterir. Document document = new Document("sample.pdf"); System.out.println(document.getPages().get(1).getRotate()); </pre> @see Rotation

### getRotationMatrix {#getRotationMatrix--}
```
public Matrix getRotationMatrix()
```

Sayfa için dönüşüm matrisini alır.

**Returns:**
Matrix değeri

### getTabOrder {#getTabOrder--}
```
public int getTabOrder()
```

Sayfanın sekme sırasını alır. Olası değerler: Row, Column. Varsayılan, Manual

**Returns:**
TabOrder değeri @see TabOrder

### getTocInfo {#getTocInfo--}
```
public TocInfo getTocInfo()
```

İçindekiler tablosu bilgilerini alır.

**Returns:**
İçindekiler tablosu bilgisi - varsayılan null. Ayarlanırsa bu sayfa içindekiler tablosu içerecektir.

### getTrimBox {#getTrimBox--}
```
public Rectangle getTrimBox()
```

<p> Sayfanın kırpma kutusunu alır. </p>

**Returns:**
Rectangle değeri <hr> <pre> Örnek, sayfanın kırpma kutusunu nasıl alacağını gösterir: Document document = new Document("sample.pdf"); Rectangle trimBox = document.getPages().get(1).getTrimBox(); </pre>

### getUserUnit {#getUserUnit--}
```
public final double getUserUnit()
```

UserUnit değerini alır veya ayarlar. 1 / 72 inç'in katları şeklinde, varsayılan kullanıcı uzayı birimlerinin boyutunu veren pozitif bir sayıdır. Varsayılan değer 1'dir. Bu girişin sayfada temizlenmesi için sıfır veya negatif değer ayarlayın.

**Returns:**
double değer

### getWatermark {#getWatermark--}
```
public Watermark getWatermark()
```

Sayfanın filigranını alır.

**Returns:**
Watermark değeri

### hasVectorGraphics {#hasVectorGraphics--}
```
public final boolean hasVectorGraphics()
```

Sayfada varsa, vektör grafiklerinin varlığını algılar.

**Returns:**
Doğru, sayfa yol oluşturma operatörleri içeriyorsa; aksi takdirde Yanlış.

### intToRotation {#intToRotation-int-}
```
public static Rotation intToRotation(int rotation)
```

Tam sayı değerini karşılık gelen dönüşüm enum üyesine çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dönme |  | Dönüştürülecek tamsayı değeri |

**Returns:**
Rotation enum üyesi @see Rotation

### isAddParagraphsAfterLast {#isAddParagraphsAfterLast--}
```
public final boolean isAddParagraphsAfterLast()
```

Sayfanın son paragrafından sonra paragraf eklenmesini alır veya ayarlar. Değer: Değer, paragrafın sayfanın son paragrafından sonra eklenip eklenmeyeceğini gösterir. Değer true ise, paragraf sayfanın son paragrafından sonra eklenecektir.

**Returns:**
boolean değer

### isBlank {#isBlank-double-}
```
public boolean isBlank(double fillThresholdFactor)
```

Sayfanın boş olup olmadığını gösteren bayrağı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillThresholdFactor |  | Algılama hassasiyetini yöneten doldurma eşik değeri. [0..1) aralığında olmalıdır. Bir sayfanın boş olup olmadığını belirlemek için, doldurulan alanın sayfanın toplam alanına oranı hesaplanır. Bu oran fillThresholdFactor parametresiyle karşılaştırılır ve eğer daha düşükse, sayfa boş olarak kabul edilir. |

**Returns:**
boolean değer True - sayfa boşsa; aksi takdirde false.

### isBlank {#isBlank-double-boolean-}
```
public boolean isBlank(double fillThresholdFactor, boolean parseWhiteContent)
```

Sayfanın boş olup olmadığını gösteren bayrağı alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fillThresholdFactor |  | Algılama hassasiyetini yöneten doldurma eşik değeri. 0.01'den eşit veya büyük olmalıdır. |
| parseWhiteContent |  | Tam sayfa taraması ve beyaz içerik analizi için True, False (varsayılan) - hızlı algoritma, beyaz grafiklerin boş sayfa olarak sayılmadığı. |

**Returns:**
boolean değer True - sayfa boşsa; aksi takdirde false.

### makeGrayscale {#makeGrayscale--}
```
public final void makeGrayscale()
```

Sayfayı gri tonlamaya dönüştürür.

### mergeLayers {#mergeLayers-java.lang.String-}
Sayfadaki tüm katmanları belirtilen yeni katman adıyla tek bir katmanda birleştirir.

### mergeLayers {#mergeLayers-java.lang.String-java.lang.String-}
Sayfadaki tüm katmanları belirtilen yeni katman adı ve isteğe bağlı içerik grup kimliği ile tek bir katmanda birleştirir.

### removeObjectReferences {#removeObjectReferences-com.aspose.pdf.OperatorCollection-java.lang.String-}
Nesne referanslarını kaldır.

### removeObjectReferences {#removeObjectReferences-java.lang.String-}
Sayfa içeriklerinden XObject referanslarını kaldır (ör. nesne adını kullanan tüm Do operatörleri).

### resize {#resize-com.aspose.pdf.PageSize-}
Sayfanın boyutunu değiştirir.

### rotationToInt {#rotationToInt-com.aspose.pdf.Rotation-}
Dönüşüm enum üyesini tam sayı değerine çevirir.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.io.OutputStream-}
Sayfayı verilen sayfa cihazı ile işleme gönderir.

### sendTo {#sendTo-com.aspose.pdf.devices.PageDevice-java.lang.String-}
Sayfayı verilen sayfa cihazı ile işleme gönderir.

### setAddParagraphsAfterLast {#setAddParagraphsAfterLast-boolean-}
```
public final void setAddParagraphsAfterLast(boolean value)
```

Sayfanın son paragrafından sonra paragraf eklenmesini alır veya ayarlar. Değer: Değer, paragrafın sayfanın son paragrafından sonra eklenip eklenmeyeceğini gösterir. Değer true ise, paragraf sayfanın son paragrafından sonra eklenecektir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setArtBox {#setArtBox-com.aspose.pdf.Rectangle-}
Sayfanın art kutusunu ayarlar.

### setBackground {#setBackground-java.awt.Color-}
Sayfanın arka plan rengini ayarlar.

### setBackground {#setBackground-com.aspose.pdf.Color-}
Sayfanın arka plan rengini ayarlar.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Sayfa için arka plan görüntüsünü alır veya ayarlar (yalnızca oluşturucu için, belge okunurken doldurulmaz).

### setBleedBox {#setBleedBox-com.aspose.pdf.Rectangle-}
Sayfanın taşma kutusunu ayarlar.

### setCropBox {#setCropBox-com.aspose.pdf.Rectangle-}
<p> Sayfanın kırpma kutusunu ayarlar. </p> <hr> <pre> Örnek, sayfanın kırpma kutusunun nasıl alınacağını gösterir: Document document = new Document(\"sample.pdf\"); document.getPages().get_Item(1).setCropBox(new Rectangle(0d,0d,100d,100d)); </pre>

### setDuration {#setDuration-double-}
```
public void setDuration(double value)
```

Sayfanın görüntülenme süresini ayarlar. Bu, sayfanın sunum sırasında saniye cinsinden gösterileceği süredir. Süre tanımlı değilse -1 döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | sayfa gösterim süresi. |

### setEnginePage {#setEnginePage-com.aspose.pdf.engine.commondata.IPage-}
Yalnızca dahili kullanım için

### setFooter {#setFooter-com.aspose.pdf.HeaderFooter-}
Sayfanın altbilgisini ayarlar.

### setGroup {#setGroup-com.aspose.pdf.Group-}
Sayfanın sayfa grubunun özelliklerini şeffaf görüntüleme modelinde kullanmak için belirten bir grup öznitelik sınıfını ayarlar.

### setHeader {#setHeader-com.aspose.pdf.HeaderFooter-}
Sayfa başlığını ayarlar.

### setLayers {#setLayers-java.util.ArrayList-}
Katman koleksiyonunu ayarlar.

### setLayersInternal {#setLayersInternal-com.aspose.ms.System.Collections.Generic.List-}
Katman koleksiyonunu ayarlar.

### setMediaBox {#setMediaBox-com.aspose.pdf.Rectangle-}
Sayfanın medya kutusunu ayarlar.

### setNoteLineStyle {#setNoteLineStyle-com.aspose.pdf.GraphInfo-}
Notlar için satır stilini ayarlar.(yalnızca oluşturucu için, belge okunurken doldurulmaz)

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Sayfa bilgisini ayarlar.(yalnızca oluşturucu için, belge okunurken doldurulmaz).

### setPageSize {#setPageSize-double-double-}
```
public void setPageSize(double width, double height)
```

Sayfa boyutunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik |  | Sayfa genişliği. |
| yükseklik |  | Sayfa boyutu. |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Paragrafları ayarlar.

### setRect {#setRect-com.aspose.pdf.Rectangle-}
Sayfanın dikdörtgenini alır veya ayarlar. Alım için: sayfa kırpma kutusu belirtilmişse döndürülür, aksi takdirde sayfa medya kutusu döndürülür. Ayarlama için: sayfa medya kutusu her zaman ayarlanır. döndürülür. Lütfen bu özelliğin sayfa dönüşünü dikkate almadığını unutmayın. Dönüşü dikkate alarak sayfa dikdörtgenini almak için lütfen ActualRect kullanın.

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Sayfanın dönüşünü ayarlar.

### setTabOrder {#setTabOrder-int-}
```
public void setTabOrder(int value)
```

Sayfanın sekme sırasını ayarlar. Olası değerler: Row, Column. Varsayılan, Manual

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | TabOrder nesnesi @see TabOrder |

### setTocInfo {#setTocInfo-com.aspose.pdf.TocInfo-}
İçindekiler tablosu bilgisini ayarlar.

### setTransition {#setTransition-com.aspose.pdf.engine.data.IPdfDictionary-}
Geçişi ayarlar.

### setTrimBox {#setTrimBox-com.aspose.pdf.Rectangle-}
Sayfanın kırpma kutusunu ayarlar.

### setUserUnit {#setUserUnit-double-}
```
public final void setUserUnit(double value)
```

UserUnit değerini alır veya ayarlar. 1 / 72 inç'in katları şeklinde, varsayılan kullanıcı uzayı birimlerinin boyutunu veren pozitif bir sayıdır. Varsayılan değer 1'dir. Bu girişin sayfada temizlenmesi için sıfır veya negatif değer ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | double değer |

### setWatermark {#setWatermark-com.aspose.pdf.Watermark-}
Sayfanın filigranını ayarlar.

### trySaveVectorGraphics {#trySaveVectorGraphics-java.lang.String-}
Sayfada mevcutsa vektör grafikleri kaydetmeye çalışır. Kaydetme formatı SVG'dir.
