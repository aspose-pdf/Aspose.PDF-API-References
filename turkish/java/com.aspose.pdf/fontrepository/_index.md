---
title: "FontRepository"
linktitle: "FontRepository"
second_title: "Aspose.PDF for Java API Referansı"
description: "<p> Yazı tipi araması gerçekleştirir. Sistem yüklü yazı tiplerinde ve standart Pdf yazı tiplerinde arama yapar. Ayrıca özel yazı tiplerini açma işlevi sağlar. </p> <hr> <pre> Örnek gösterir."
type: docs
weight: 1690
url: /tr/java/com.aspose.pdf/fontrepository/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontRepository

```
public final class FontRepository extends Object
```

<p> Yazı tipi araması gerçekleştirir. Sistem yüklü yazı tiplerinde ve standart Pdf yazı tiplerinde arama yapar. Ayrıca özel yazı tiplerini açma işlevi sağlar. </p> <hr> <pre> Örnek, bir yazı tipini bulmayı ve ilk sayfanın metin yazı tipini değiştirmeyi gösterir. // Find font Font font = FontRepository.findFont("Arial"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre> @see TextFragmentAbsorber @see IDocument

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FontRepository](#FontRepository--) |  |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addLocalFontPath](#addLocalFontPath-java.lang.String-) | Yazı tiplerine bir yol daha ekle. |
| [addSystemFont](#addSystemFont-com.aspose.pdf.Font-) | <p> Belirtilen yazı tipiyle sistem yazı tipini ekle. </p> <hr> <pre> Örnek, sistem yazı tipini nasıl ekleyeceğini gösterir. InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre> |
| [clear](#clear--) |  |
| [findFont](#findFont-java.lang.String-) | <p> Belirtilen yazı tipi adıyla yazı tipini arar ve döndürür. </p> <hr> <pre> Örnek, yazı tipini bulmayı ve ilk sayfanın metninin yazı tipini değiştirmeyi gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\"); // Belgeyi aç Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-boolean-) | <p> Belirtilen yazı tipi adıyla, büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak yazı tipini arar ve döndürür. </p> <hr> <pre> Örnek, yazı tipini bulmayı ve ilk sayfanın metninin yazı tipini değiştirmeyi gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Belgeyi aç Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-) | <p> Belirtilen yazı tipi adı ve yazı tipi stiliyle yazı tipini arar ve döndürür. </p> <hr> <pre> Örnek, yazı tipini bulmayı ve ilk sayfanın metninin yazı tipini değiştirmeyi gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Belgeyi aç Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [findFont](#findFont-java.lang.String-int-boolean-) | <p> Belirtilen yazı tipi adı ve yazı tipi stiliyle, büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak yazı tipini arar ve döndürür. </p> <hr> <pre> Örnek, yazı tipini bulmayı ve ilk sayfanın metninin yazı tipini değiştirmeyi gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Belgeyi aç Document doc = new Document(\"D:\\\\\\\\Tests\\\\\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\\\\\Tests\\\\\\\\output.pdf\"); </pre> |
| [getLocalFontPaths](#getLocalFontPaths--) | Gerçek yazı tipi dizinlerini içeren listenin kopyası. |
| [getSources](#getSources--) | Yazı tipi kaynakları koleksiyonunu alır. |
| [getSubstitutions](#getSubstitutions--) | Yazı tipi ikame stratejileri koleksiyonunu alır. |
| [isReplaceNotFoundFonts](#isReplaceNotFoundFonts--) | Bulunamayan yazı tipleri standart yazı tipiyle değiştirilecektir. |
| [isThreadStaticConfigEnabled](#isThreadStaticConfigEnabled--) | <p> Font Kaynakları depolama yapılandırmasının durumunu döndürür. <br> true ise ThreadStatic kullanılır ve her iş parçacığının kendi Font Kaynakları vardır. <br> false ise tüm iş parçacıkları için global statik yapılandırma kullanılır. </p> <hr> Varsayılan değer True'dur. |
| [loadFonts](#loadFonts--) | Sistem yüklü yazı tiplerini ve standart Pdf yazı tiplerini yükler. Bu yöntem, yazı tipi yükleme sürecini hızlandırmak için tasarlanmıştır. Varsayılan olarak yazı tipleri herhangi bir yazı tipi için ilk istek üzerine yüklenir. Bu yöntemin kullanılması, herhangi bir Pdf belgesi açılmadan önce sistem ve standart Pdf yazı tiplerini hemen yükler. |
| [openFont](#openFont-java.io.InputStream-int-) | <p> Belirtilen font akışıyla fontu açar. </p> <hr> <pre> Bu örnek, fontu nasıl açacağınızı ve ilk sayfanın metninin fontunu nasıl değiştireceğinizi gösterir. // Fontu aç InputStream fontStream = new FileInputStream("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Belgeyi aç Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun fontunu değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save("D:\\\\Tests\\\\output.pdf"); } </pre> |
| [openFont](#openFont-java.lang.String-) | <p> Belirtilen font dosya yolu ile fontu açar. </p> <hr> <pre> Bu örnek, fontu nasıl açacağınızı ve ilk sayfanın metninin fontunu nasıl değiştireceğinizi gösterir. // Fontu aç Font font = FontRepository.openFont("C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf"); // Belgeyi aç Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun fontunu değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [openFont](#openFont-java.lang.String-java.lang.String-) | <p> Belirtilen font dosya yolu ve ölçüm dosyası yolu ile fontu açar. </p> <hr> <pre> Bu örnek, ölçümlerle Type1 fontunu nasıl açacağınızı ve ilk sayfanın metninin fontunu nasıl değiştireceğinizi gösterir. // Fontu aç Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Belgeyi aç Document doc = new Document("D:\\\\Tests\\\\input.pdf"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun fontunu değiştir absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Belgeyi kaydet doc.save("D:\\\\Tests\\\\output.pdf"); </pre> |
| [reloadFonts](#reloadFonts--) | {@code Sources} özelliğiyle belirtilen tüm fontları yeniden yükler ({@link #getSources}) |
| [restoreLocalFontPath](#restoreLocalFontPath--) | Varsayılan olarak standart font dizinleri için listeyi geri yükler. |
| [setLocalFontPaths](#setLocalFontPaths-java.util.List-) | Kullanıcı listesini font yolları ile ayarlar |
| [setReplaceNotFoundFonts](#setReplaceNotFoundFonts-boolean-) | Bulunamayan fontları varsayılan fontla değiştirmek gerekiyorsa TRUE ayarlayın. Varsayılan değer false'tur. |
| [setThreadStaticConfigEnabled](#setThreadStaticConfigEnabled-boolean-) | Font Sources depolama yapılandırmasını ayarlama seçeneği. TRUE ise ThreadStatic kullanılır ve her iş parçacığının kendi Font Sources'ı olur. FALSE ise tüm iş parçacıkları için global statik yapılandırma kullanılır. |

### FontRepository {#FontRepository--}
```
public FontRepository()
```



### addLocalFontPath {#addLocalFontPath-java.lang.String-}
Yazı tiplerine bir yol daha ekle.

### addSystemFont {#addSystemFont-com.aspose.pdf.Font-}
<p> Belirtilen font ile sistem fontu ekler. </p> <hr> <pre> Bu örnek, sistem fontunun nasıl ekleneceğini gösterir. InputStream fontStream = new FileInputStream("C:\\WINDOWS\\Fonts\\arial.ttf")) Font font = FontRepository.openFont(fontStream, FontTypes.TTF); FontRepository.addSystemFont(font); </pre>

### clear {#clear--}
```
public static void clear()
```



### findFont {#findFont-java.lang.String-}
<p> Belirtilen font adıyla fontu arar ve döndürür. </p> <hr> <pre> Bu örnek, fontun nasıl bulunacağını ve ilk sayfanın metninin fontunun nasıl değiştirileceğini gösterir. // Fontu bul Font font = FontRepository.findFont("Arial"); // Belgeyi aç Document doc = new Document("D:\\Tests\\input.pdf"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun fontunu değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save("D:\\Tests\\output.pdf"); </pre>

### findFont {#findFont-java.lang.String-boolean-}
<p> Belirtilen yazı tipi adıyla eşleşen yazı tipini büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak arar ve döndürür. </p> <hr> <pre> Bu örnek, yazı tipinin nasıl bulunacağını ve ilk sayfadaki metnin yazı tipinin nasıl değiştirileceğini gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Belgeyi aç Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-}
<p> Belirtilen yazı tipi adı ve yazı tipi stiliyle eşleşen yazı tipini arar ve döndürür. </p> <hr> <pre> Bu örnek, yazı tipinin nasıl bulunacağını ve ilk sayfadaki metnin yazı tipinin nasıl değiştirileceğini gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic); // Belgeyi aç Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### findFont {#findFont-java.lang.String-int-boolean-}
<p> Belirtilen yazı tipi adı ve stiliyle eşleşen yazı tipini büyük/küçük harf duyarlılığını göz ardı ederek veya dikkate alarak arar ve döndürür. </p> <hr> <pre> Bu örnek, yazı tipinin nasıl bulunacağını ve ilk sayfadaki metnin yazı tipinin nasıl değiştirileceğini gösterir. // Yazı tipini bul Font font = FontRepository.findFont(\"Arial\", FontStyles.Italic, true); // Belgeyi aç Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont(font); // Belgeyi kaydet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### getLocalFontPaths {#getLocalFontPaths--}
```
public static List < String > getLocalFontPaths()
```

Gerçek yazı tipi dizinlerini içeren listenin kopyası.

**Returns:**
String listesi

### getSources {#getSources--}
```
public static FontSourceCollection getSources()
```

Yazı tipi kaynakları koleksiyonunu alır.

**Returns:**
FontSourceCollection nesnesi

### getSubstitutions {#getSubstitutions--}
```
public static FontSubstitutionCollection getSubstitutions()
```

Yazı tipi ikame stratejileri koleksiyonunu alır.

**Returns:**
FontSubstitutionCollection nesnesi

### isReplaceNotFoundFonts {#isReplaceNotFoundFonts--}
```
public static boolean isReplaceNotFoundFonts()
```

Bulunamayan yazı tipleri standart yazı tipiyle değiştirilecektir.

**Returns:**
boolean değer

### isThreadStaticConfigEnabled {#isThreadStaticConfigEnabled--}
```
public static boolean isThreadStaticConfigEnabled()
```

<p> Font Kaynakları depolama yapılandırmasının durumunu döndürür. <br> true ise ThreadStatic kullanılır ve her iş parçacığının kendi Font Kaynakları vardır. <br> false ise tüm iş parçacıkları için global statik yapılandırma kullanılır. </p> <hr> Varsayılan değer True'dur.

**Returns:**
boolean değer

### loadFonts {#loadFonts--}
```
public static void loadFonts()
```

Sistem yüklü yazı tiplerini ve standart Pdf yazı tiplerini yükler. Bu yöntem, yazı tipi yükleme sürecini hızlandırmak için tasarlanmıştır. Varsayılan olarak yazı tipleri herhangi bir yazı tipi için ilk istek üzerine yüklenir. Bu yöntemin kullanılması, herhangi bir Pdf belgesi açılmadan önce sistem ve standart Pdf yazı tiplerini hemen yükler.

### openFont {#openFont-java.io.InputStream-int-}
<p> Belirtilen yazı tipi akışıyla yazı tipini açar. </p> <hr> <pre> Bu örnek, yazı tipinin nasıl açılacağını ve ilk sayfadaki metnin yazı tipinin nasıl değiştirileceğini gösterir. // Yazı tipini aç InputStream fontStream = new FileInputStream(\"C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf\")) { Font font = FontRepository.openFont(fontStream, , FontTypes.TTF); // Belgeyi aç Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save(\"D:\\\\Tests\\\\output.pdf\"); } </pre>

### openFont {#openFont-java.lang.String-}
<p> Belirtilen yazı tipi dosya yolu ile yazı tipini açar. </p> <hr> <pre> Bu örnek, yazı tipinin nasıl açılacağını ve ilk sayfadaki metnin yazı tipinin nasıl değiştirileceğini gösterir. // Yazı tipini aç Font font = FontRepository.openFont(\"C:\\\\WINDOWS\\\\Fonts\\\\arial.ttf\"); // Belgeyi aç Document doc = new Document(\"D:\\\\Tests\\\\input.pdf\"); // Tüm \"hello world\" metin oluşumlarını bulmak için TextFragmentAbsorber nesnesi oluştur TextFragmentAbsorber absorber = new TextFragmentAbsorber(\"hello world\"); // İlk sayfa için absorber'ı kabul et doc.getPages().get_Item(1).accept(absorber); // İlk metin oluşumunun yazı tipini değiştir absorber.getTextFragments().get_Item(1).getTextState().setFont ( font); // Belgeyi kaydet doc.save(\"D:\\\\Tests\\\\output.pdf\"); </pre>

### openFont {#openFont-java.lang.String-java.lang.String-}
<p> Belirtilen yazı tipi dosyası yolu ve ölçüm dosyası yolu ile yazı tipini açar. </p> <hr> <pre> Örnek, Type1 yazı tipini ölçümlerle nasıl açacağını ve ilk sayfanın metin yazı tipini nasıl değiştireceğini gösterir. // Open font Font font = FontRepository.openFont("courier.pfb", "courier.afm"); // Open document Document doc = new Document("D:\\Tests\\input.pdf"); // Create TextFragmentAbsorber object to find all "hello world" text occurrences TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world"); // Accept the absorber for first page doc.getPages().get_Item(1).accept(absorber); // Change font of the first text occurrence absorber.getTextFragments().get_Item(1).sgetTextState().setFont(font); // Save document doc.save("D:\\Tests\\output.pdf"); </pre>

### reloadFonts {#reloadFonts--}
```
public static void reloadFonts()
```

{@code Sources} özelliğiyle belirtilen tüm fontları yeniden yükler ({@link #getSources})

### restoreLocalFontPath {#restoreLocalFontPath--}
```
public static void restoreLocalFontPath()
```

Varsayılan olarak standart font dizinleri için listeyi geri yükler.

### setLocalFontPaths {#setLocalFontPaths-java.util.List-}
Kullanıcı listesini font yolları ile ayarlar

### setReplaceNotFoundFonts {#setReplaceNotFoundFonts-boolean-}
```
public static void setReplaceNotFoundFonts(boolean value)
```

Bulunamayan fontları varsayılan fontla değiştirmek gerekiyorsa TRUE ayarlayın. Varsayılan değer false'tur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean |

### setThreadStaticConfigEnabled {#setThreadStaticConfigEnabled-boolean-}
```
public static void setThreadStaticConfigEnabled(boolean isTheadLocal)
```

Font Sources depolama yapılandırmasını ayarlama seçeneği. TRUE ise ThreadStatic kullanılır ve her iş parçacığının kendi Font Sources'ı olur. FALSE ise tüm iş parçacıkları için global statik yapılandırma kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isTheadLocal |  | boolean değer |
