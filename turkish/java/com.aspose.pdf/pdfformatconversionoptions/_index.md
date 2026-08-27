---
title: "PdfFormatConversionOptions"
linktitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF belgesini dönüştürmek için seçenekler kümesini temsil eder."
type: docs
weight: 3730
url: /tr/java/com.aspose.pdf/pdfformatconversionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfFormatConversionOptions

```
public class PdfFormatConversionOptions extends Object
```

PDF belgesini dönüştürmek için seçenekler kümesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Yapıcı |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-) | Yapıcı |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Yapıcı |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-) | Yapıcı |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-) | Yapıcı |
| [PdfFormatConversionOptions](#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-) | Yapıcı |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addNotAccessibleFont](#addNotAccessibleFont-java.lang.String-) |  |
| [getAlignStrategy](#getAlignStrategy--) | Metni hizalama stratejisi. Bu parametre yalnızca {@code AlignText} bayrağı true olarak ayarlandığında anlam taşır. |
| [getAlignText](#getAlignText--) | Bu bayrak, dönüştürülmüş belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi ikamesi, dönüştürülmüş belgede metin çakışmasına veya ekstra boşluklara neden olur. Bu bayrak ayarlandığında özel hizalama işlemleri gerçekleştirilir. Bu bayrak yalnızca çakışan metin veya ekstra boşluk sorunları olan belgeler için ayarlanmalıdır; çünkü bu bayrağın kullanılması performansı düşürür ve bazı durumlarda metin içeriğini bozabilir. |
| [getAutoTaggingSettings](#getAutoTaggingSettings--) | PDF formatı dönüşümü sırasında otomatik etiketleme ayarlarını alır veya ayarlar. Otomatik etiketleme ayarları, belirli bir PDF formatına dönüşüm sırasında bir PDF belgesinin erişilebilirliğini ve yapısını iyileştirmek için genellikle kullanılan otomatik etiketleme sürecinin davranışını yapılandırmak için kullanılır. |
| [getConvertSoftMaskAction](#getConvertSoftMaskAction--) | Yumuşak maske içeren görüntüler için eylem. |
| [getDefault](#getDefault--) | Varsayılan parametrelerle PdfFormatConversionOptions nesnesini alır |
| [getErrorAction](#getErrorAction--) | Dönüştürülemeyen nesneler için eylem |
| [getExcludeFontsStrategy](#getExcludeFontsStrategy--) | Gereksiz yazı tiplerini dışarıda tutmak ve belge dosya boyutunu azaltmak için strateji(ler). Bu parametre yalnızca {@code OptimizeFileSize} bayrağı true olarak ayarlandığında anlam taşır. Varsayılan olarak {@code SubsetFonts} ve {@code RemoveDuplicatedFonts} stratejilerinin kombinasyonu kullanılır. |
| [getFontEmbeddingOptions](#getFontEmbeddingOptions--) | Bazı yazı tiplerinin PDF belgesine gömülemeyeceği durumlar için seçenekler. |
| [getFormat](#getFormat--) | PDF formatı. |
| [getIccProfileFileName](#getIccProfileFileName--) | ICC profil adının dosya adını alır. Null olması durumunda varsayılan ICC profil kullanılır. |
| [getLogFileName](#getLogFileName--) | Yorumların saklanacağı dosyanın yolu. |
| [getLogStream](#getLogStream--) | Yorumların saklanacağı akış. |
| [getNonSpecificationCases](#getNonSpecificationCases--) | Kaynak belgenin PDF/A spesifikasyonuna uymadığı durumlar için PDF/A dönüşüm sürecini kontrol eden bayrakları tutar. |
| [getNotAccessibleFonts](#getNotAccessibleFonts--) | Bu özellik bir çıkış özelliğidir. Son PDF/A dönüşümünde bilgisayarda bulunamayan tüm yazı tiplerini (yazı tipi adlarını) tutar. |
| [getOptimizeFileSize](#getOptimizeFileSize--) | PDF/A belgesinin dosya boyutunu azaltmak için özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrak alır. Şu anda bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler; gelecekte bu bayrak, grafik gibi diğer veri yapılarını da optimize etmek için kullanılabilir. Bu bayrak ve modun birleşimi dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüşüm performansını da önemli ölçüde düşürebilir. |
| [getOutputIntent](#getOutputIntent--) | PDF formatı dönüşümü için {@link OutputIntent}'i alır veya ayarlar. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) PDF belgesinin hazırlandığı hedef çıktı cihazını veya koşulunu belirtir. Belgedeki renklerin hedef cihazda doğru şekilde işlenmesini sağlamak için kullanılır. |
| [getPuaTextProcessingStrategy](#getPuaTextProcessingStrategy--) | Unicode Özel Kullanım Alanı (PUA) içindeki sembolleri işleme stratejisi. |
| [getSymbolicFontEncodingStrategy](#getSymbolicFontEncodingStrategy--) | Sembolik TrueType yazı tipinin birden fazla kodlama alt tablosu varsa, sembolik yazı tipleri için kodlama verilerini kopyalama stratejisi. |
| [getTransparencyAction](#getTransparencyAction--) | Görüntü maskeli nesneler için eylem |
| [getTransparencyResolution](#getTransparencyResolution--) | Şeffaf görüntülerin dönüştürülmesi sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüşüm hızı o kadar yavaş olur. Varsayılan değer 300'dür. |
| [getUnicodeProcessingRules](#getUnicodeProcessingRules--) | Unicode eşlemesiyle ilgili sorunları çözmek için kurallar. Null olabilir. |
| [isAsyncImageStreamsConversionMode](#isAsyncImageStreamsConversionMode--) | Görüntü akışlarının asenkron modda çalıştırılmasını alır/ayarlar. |
| [isLowMemoryMode](#isLowMemoryMode--) | Düşük bellek dönüşüm modu etkin mi |
| [isPageByPageFontProcess](#isPageByPageFontProcess--) | Yazı tipi analizi sayfa sayfa temelli modda etkin mi Varsayılan değer = false |
| [isTransferInfo](#isTransferInfo--) | PDF 2.0'a dönüştürülürken Bilgi'den MetaVeri'ye veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak true. |
| [isTransparencyIgnore](#isTransparencyIgnore--) | Varsayılan değer FALSE olduğunda şeffaflık rengi belge görünümünü korumak için işlenir. TRUE değeriyle şeffaflık rengi şeffaf olmayan bir renge dönüştürülür, bazı nesneler örtülebilir. |
| [setAlignStrategy](#setAlignStrategy-byte-) | Metni hizalama stratejisi. Bu parametre yalnızca {@code AlignText} bayrağı true olarak ayarlandığında anlam taşır. |
| [setAlignText](#setAlignText-boolean-) | Bu bayrak, dönüştürülmüş belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi ikamesi, dönüştürülmüş belgede metin çakışmasına veya ekstra boşluklara neden olur. Bu bayrak ayarlandığında özel hizalama işlemleri gerçekleştirilir. Bu bayrak yalnızca çakışan metin veya ekstra boşluk sorunları olan belgeler için ayarlanmalıdır; çünkü bu bayrağın kullanılması performansı düşürür ve bazı durumlarda metin içeriğini bozabilir. |
| [setAsyncImageStreamsConversionMode](#setAsyncImageStreamsConversionMode-boolean-) | Görüntü akışlarının asenkron modda çalıştırılmasını alır/ayarlar. |
| [setAutoTaggingSettings](#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-) | PDF formatı dönüşümü sırasında otomatik etiketleme ayarlarını alır veya ayarlar. Otomatik etiketleme ayarları, belirli bir PDF formatına dönüşüm sırasında bir PDF belgesinin erişilebilirliğini ve yapısını iyileştirmek için genellikle kullanılan otomatik etiketleme sürecinin davranışını yapılandırmak için kullanılır. |
| [setConvertSoftMaskAction](#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-) | Yumuşak maske içeren görüntüler için eylem. |
| [setErrorAction](#setErrorAction-com.aspose.pdf.ConvertErrorAction-) | Dönüştürülemeyen nesneler için eylem |
| [setExcludeFontsStrategy](#setExcludeFontsStrategy-byte-) | Gereksiz yazı tiplerini dışarıda tutmak ve belge dosya boyutunu azaltmak için strateji(ler). Bu parametre yalnızca {@code OptimizeFileSize} bayrağı true olarak ayarlandığında anlam taşır. Varsayılan olarak {@code SubsetFonts} ve {@code RemoveDuplicatedFonts} stratejilerinin kombinasyonu kullanılır. |
| [setFormat](#setFormat-com.aspose.pdf.PdfFormat-) | PDF formatı. |
| [setIccProfileFileName](#setIccProfileFileName-java.lang.String-) | ICC profil adının dosya adını ayarlar. Null olması durumunda varsayılan ICC profil kullanılır. |
| [setLogFileName](#setLogFileName-java.lang.String-) | Yorumların saklanacağı dosyanın yolu. |
| [setLogStream](#setLogStream-java.io.OutputStream-) | Yorumların saklanacağı akış. |
| [setLowMemoryMode](#setLowMemoryMode-boolean-) | Düşük bellek dönüşüm modu etkin mi |
| [setOptimizeFileSize](#setOptimizeFileSize-boolean-) | PDF/A belgesinin dosya boyutunu azaltmak için özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrağı ayarlar. Şu anda bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler; gelecekte bu bayrak, grafik gibi diğer veri yapılarını da optimize etmek için kullanılabilir. Bu bayrak ve modun birleşimi dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüşüm performansını da önemli ölçüde düşürebilir. |
| [setOutputIntent](#setOutputIntent-com.aspose.pdf.OutputIntent-) | PDF formatı dönüşümü için {@link OutputIntent}'i alır veya ayarlar. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) PDF belgesinin hazırlandığı hedef çıktı cihazını veya koşulunu belirtir. Belgedeki renklerin hedef cihazda doğru şekilde işlenmesini sağlamak için kullanılır. |
| [setPageByPageFontProcess](#setPageByPageFontProcess-boolean-) | Sayfa sayfa temelli yazı tipi analizi modunu etkinleştir. Varsayılan değer = false |
| [setPuaTextProcessingStrategy](#setPuaTextProcessingStrategy-int-) | Unicode Özel Kullanım Alanı (PUA) içindeki sembolleri işleme stratejisi. |
| [setSymbolicFontEncodingStrategy](#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-) | Sembolik TrueType yazı tipinin birden fazla kodlama alt tablosu varsa, sembolik yazı tipleri için kodlama verilerini kopyalama stratejisi. |
| [setTransferInfo](#setTransferInfo-boolean-) | PDF 2.0'a dönüştürülürken Bilgi'den MetaVeri'ye veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak true. |
| [setTransparencyAction](#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-) | Görüntü maskeli nesneler için eylem |
| [setTransparencyIgnore](#setTransparencyIgnore-boolean-) | Varsayılan değer FALSE olduğunda şeffaflık rengi belge görünümünü korumak için işlenir. TRUE değeriyle şeffaflık rengi şeffaf olmayan bir renge dönüştürülür, bazı nesneler örtülebilir. |
| [setTransparencyResolution](#setTransparencyResolution-int-) | Şeffaf görüntülerin dönüştürülmesi sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüşüm hızı o kadar yavaş olur. Varsayılan değer 300'dür. |
| [setUnicodeProcessingRules](#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-) | Unicode eşlemesiyle ilgili sorunları çözmek için kurallar. Null olabilir. |

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.io.OutputStream-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Yapıcı

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-}
Yapıcı

### PdfFormatConversionOptions {#PdfFormatConversionOptions-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Yapıcı

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-}
Yapıcı

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-}
Yapıcı

### PdfFormatConversionOptions {#PdfFormatConversionOptions-java.lang.String-com.aspose.pdf.PdfFormat-com.aspose.pdf.ConvertErrorAction-com.aspose.pdf.ConvertTransparencyAction-}
Yapıcı

### addNotAccessibleFont {#addNotAccessibleFont-java.lang.String-}


### getAlignStrategy {#getAlignStrategy--}
```
public byte getAlignStrategy()
```

Metni hizalama stratejisi. Bu parametre yalnızca {@code AlignText} bayrağı true olarak ayarlandığında anlam taşır.

**Returns:**
SegmentAlignStrategy öğesi @see SegmentAlignStrategy

### getAlignText {#getAlignText--}
```
public boolean getAlignText()
```

Bu bayrak, dönüştürülmüş belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi ikamesi, dönüştürülmüş belgede metin çakışmasına veya ekstra boşluklara neden olur. Bu bayrak ayarlandığında özel hizalama işlemleri gerçekleştirilir. Bu bayrak yalnızca çakışan metin veya ekstra boşluk sorunları olan belgeler için ayarlanmalıdır; çünkü bu bayrağın kullanılması performansı düşürür ve bazı durumlarda metin içeriğini bozabilir.

**Returns:**
boolean değer

### getAutoTaggingSettings {#getAutoTaggingSettings--}
```
public final AutoTaggingSettings getAutoTaggingSettings()
```

PDF formatı dönüşümü sırasında otomatik etiketleme ayarlarını alır veya ayarlar. Otomatik etiketleme ayarları, belirli bir PDF formatına dönüşüm sırasında bir PDF belgesinin erişilebilirliğini ve yapısını iyileştirmek için genellikle kullanılan otomatik etiketleme sürecinin davranışını yapılandırmak için kullanılır.

**Returns:**
AutoTaggingSettings örneği

### getConvertSoftMaskAction {#getConvertSoftMaskAction--}
```
public final ConvertSoftMaskAction getConvertSoftMaskAction()
```

Yumuşak maske içeren görüntüler için eylem.

**Returns:**
int değer

### getDefault {#getDefault--}
```
public static PdfFormatConversionOptions getDefault()
```

Varsayılan parametrelerle PdfFormatConversionOptions nesnesini alır

**Returns:**
PdfFormatConversionOptions nesnesi

### getErrorAction {#getErrorAction--}
```
public ConvertErrorAction getErrorAction()
```

Dönüştürülemeyen nesneler için eylem

**Returns:**
ConvertErrorAction öğesi @see ConvertErrorAction

### getExcludeFontsStrategy {#getExcludeFontsStrategy--}
```
public byte getExcludeFontsStrategy()
```

Gereksiz yazı tiplerini dışarıda tutmak ve belge dosya boyutunu azaltmak için strateji(ler). Bu parametre yalnızca {@code OptimizeFileSize} bayrağı true olarak ayarlandığında anlam taşır. Varsayılan olarak {@code SubsetFonts} ve {@code RemoveDuplicatedFonts} stratejilerinin kombinasyonu kullanılır.

**Returns:**
byte değeri @see RemoveFontsStrategy

### getFontEmbeddingOptions {#getFontEmbeddingOptions--}
```
public FontEmbeddingOptions getFontEmbeddingOptions()
```

Bazı yazı tiplerinin PDF belgesine gömülemeyeceği durumlar için seçenekler.

**Returns:**
FontEmbeddingOptions nesnesi

### getFormat {#getFormat--}
```
public PdfFormat getFormat()
```

PDF formatı.

**Returns:**
PdfFormat öğesi @see PdfFormat

### getIccProfileFileName {#getIccProfileFileName--}
```
public String getIccProfileFileName()
```

ICC profil adının dosya adını alır. Null olması durumunda varsayılan ICC profil kullanılır.

**Returns:**
Dize nesnesi

### getLogFileName {#getLogFileName--}
```
public String getLogFileName()
```

Yorumların saklanacağı dosyanın yolu.

**Returns:**
Dize nesnesi

### getLogStream {#getLogStream--}
```
public OutputStream getLogStream()
```

Yorumların saklanacağı akış.

**Returns:**
OutputStream nesnesi

### getNonSpecificationCases {#getNonSpecificationCases--}
```
public PdfFormatConversionOptions.PdfANonSpecificationFlags getNonSpecificationCases()
```

Kaynak belgenin PDF/A spesifikasyonuna uymadığı durumlar için PDF/A dönüşüm sürecini kontrol eden bayrakları tutar.

**Returns:**
PdfANonSpecificationFlags nesnesi

### getNotAccessibleFonts {#getNotAccessibleFonts--}
```
public String [] getNotAccessibleFonts()
```

Bu özellik bir çıkış özelliğidir. Son PDF/A dönüşümünde bilgisayarda bulunamayan tüm yazı tiplerini (yazı tipi adlarını) tutar.

**Returns:**
Dizeler dizisi

### getOptimizeFileSize {#getOptimizeFileSize--}
```
public boolean getOptimizeFileSize()
```

PDF/A belgesinin dosya boyutunu azaltmak için özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrak alır. Şu anda bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler; gelecekte bu bayrak, grafik gibi diğer veri yapılarını da optimize etmek için kullanılabilir. Bu bayrak ve modun birleşimi dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüşüm performansını da önemli ölçüde düşürebilir.

**Returns:**
boolean değer

### getOutputIntent {#getOutputIntent--}
```
public final OutputIntent getOutputIntent()
```

PDF formatı dönüşümü için {@link OutputIntent}'i alır veya ayarlar. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) PDF belgesinin hazırlandığı hedef çıktı cihazını veya koşulunu belirtir. Belgedeki renklerin hedef cihazda doğru şekilde işlenmesini sağlamak için kullanılır.

**Returns:**
OutputIntent örneği

### getPuaTextProcessingStrategy {#getPuaTextProcessingStrategy--}
```
public int getPuaTextProcessingStrategy()
```

Unicode Özel Kullanım Alanı (PUA) içindeki sembolleri işleme stratejisi.

**Returns:**
PuaProcessingStrategy öğesi @see PuaProcessingStrategy

### getSymbolicFontEncodingStrategy {#getSymbolicFontEncodingStrategy--}
```
public PdfASymbolicFontEncodingStrategy getSymbolicFontEncodingStrategy()
```

Sembolik TrueType yazı tipinin birden fazla kodlama alt tablosu varsa, sembolik yazı tipleri için kodlama verilerini kopyalama stratejisi.

**Returns:**
PdfASymbolicFontEncodingStrategy nesnesi

### getTransparencyAction {#getTransparencyAction--}
```
public ConvertTransparencyAction getTransparencyAction()
```

Görüntü maskeli nesneler için eylem

**Returns:**
ConvertTransparencyAction öğesi @see ConvertTransparencyAction

### getTransparencyResolution {#getTransparencyResolution--}
```
public int getTransparencyResolution()
```

Şeffaf görüntülerin dönüştürülmesi sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüşüm hızı o kadar yavaş olur. Varsayılan değer 300'dür.

**Returns:**
Çözünürlük değeri

### getUnicodeProcessingRules {#getUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules getUnicodeProcessingRules()
```

Unicode eşlemesiyle ilgili sorunları çözmek için kurallar. Null olabilir.

**Returns:**
ToUnicodeProcessingRules nesnesi

### isAsyncImageStreamsConversionMode {#isAsyncImageStreamsConversionMode--}
```
public final boolean isAsyncImageStreamsConversionMode()
```

Görüntü akışlarının asenkron modda çalıştırılmasını alır/ayarlar.

**Returns:**
boolean değer

### isLowMemoryMode {#isLowMemoryMode--}
```
public final boolean isLowMemoryMode()
```

Düşük bellek dönüşüm modu etkin mi

**Returns:**
boolean değer

### isPageByPageFontProcess {#isPageByPageFontProcess--}
```
public boolean isPageByPageFontProcess()
```

Yazı tipi analizi sayfa sayfa temelli modda etkin mi Varsayılan değer = false

**Returns:**
boolean değer

### isTransferInfo {#isTransferInfo--}
```
public final boolean isTransferInfo()
```

PDF 2.0'a dönüştürülürken Bilgi'den MetaVeri'ye veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak true.

**Returns:**
boolean değer

### isTransparencyIgnore {#isTransparencyIgnore--}
```
public boolean isTransparencyIgnore()
```

Varsayılan değer FALSE olduğunda şeffaflık rengi belge görünümünü korumak için işlenir. TRUE değeriyle şeffaflık rengi şeffaf olmayan bir renge dönüştürülür, bazı nesneler örtülebilir.

**Returns:**
boolean değer

### setAlignStrategy {#setAlignStrategy-byte-}
```
public void setAlignStrategy(byte alignStrategy)
```

Metni hizalama stratejisi. Bu parametre yalnızca {@code AlignText} bayrağı true olarak ayarlandığında anlam taşır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| alignStrategy |  | SegmentAlignStrategy öğesi @see SegmentAlignStrategy |

### setAlignText {#setAlignText-boolean-}
```
public void setAlignText(boolean value)
```

Bu bayrak, dönüştürülmüş belgede metin hizalamasını kontrol eder. Varsayılan olarak belge dönüşümü metin hizalamasını etkilemez ve metni olduğu gibi bırakır. Ancak bazı durumlarda yazı tipi ikamesi, dönüştürülmüş belgede metin çakışmasına veya ekstra boşluklara neden olur. Bu bayrak ayarlandığında özel hizalama işlemleri gerçekleştirilir. Bu bayrak yalnızca çakışan metin veya ekstra boşluk sorunları olan belgeler için ayarlanmalıdır; çünkü bu bayrağın kullanılması performansı düşürür ve bazı durumlarda metin içeriğini bozabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAsyncImageStreamsConversionMode {#setAsyncImageStreamsConversionMode-boolean-}
```
public final void setAsyncImageStreamsConversionMode(boolean value)
```

Görüntü akışlarının asenkron modda çalıştırılmasını alır/ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setAutoTaggingSettings {#setAutoTaggingSettings-com.aspose.pdf.AutoTaggingSettings-}
PDF formatı dönüşümü sırasında otomatik etiketleme ayarlarını alır veya ayarlar. Otomatik etiketleme ayarları, belirli bir PDF formatına dönüşüm sırasında bir PDF belgesinin erişilebilirliğini ve yapısını iyileştirmek için genellikle kullanılan otomatik etiketleme sürecinin davranışını yapılandırmak için kullanılır.

### setConvertSoftMaskAction {#setConvertSoftMaskAction-com.aspose.pdf.ConvertSoftMaskAction-}
Yumuşak maske içeren görüntüler için eylem.

### setErrorAction {#setErrorAction-com.aspose.pdf.ConvertErrorAction-}
Dönüştürülemeyen nesneler için eylem

### setExcludeFontsStrategy {#setExcludeFontsStrategy-byte-}
```
public void setExcludeFontsStrategy(byte value)
```

Gereksiz yazı tiplerini dışarıda tutmak ve belge dosya boyutunu azaltmak için strateji(ler). Bu parametre yalnızca {@code OptimizeFileSize} bayrağı true olarak ayarlandığında anlam taşır. Varsayılan olarak {@code SubsetFonts} ve {@code RemoveDuplicatedFonts} stratejilerinin kombinasyonu kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setFormat {#setFormat-com.aspose.pdf.PdfFormat-}
PDF formatı.

### setIccProfileFileName {#setIccProfileFileName-java.lang.String-}
ICC profil adının dosya adını ayarlar. Null olması durumunda varsayılan ICC profil kullanılır.

### setLogFileName {#setLogFileName-java.lang.String-}
Yorumların saklanacağı dosyanın yolu.

### setLogStream {#setLogStream-java.io.OutputStream-}
Yorumların saklanacağı akış.

### setLowMemoryMode {#setLowMemoryMode-boolean-}
```
public void setLowMemoryMode(boolean value)
```

Düşük bellek dönüşüm modu etkin mi

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOptimizeFileSize {#setOptimizeFileSize-boolean-}
```
public void setOptimizeFileSize(boolean value)
```

PDF/A belgesinin dosya boyutunu azaltmak için özel dönüşüm modunu etkinleştiren/devre dışı bırakan bir bayrağı ayarlar. Şu anda bu bayrak, PDF belgesinde kullanılan yazı tiplerinin optimizasyonunu etkiler; gelecekte bu bayrak, grafik gibi diğer veri yapılarını da optimize etmek için kullanılabilir. Bu bayrak ve modun birleşimi dosya boyutunu önemli ölçüde azaltabilir, ancak aynı zamanda dönüşüm performansını da önemli ölçüde düşürebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setOutputIntent {#setOutputIntent-com.aspose.pdf.OutputIntent-}
PDF formatı dönüşümü için {@link OutputIntent}'i alır veya ayarlar. {@code OutputIntent}({@link #getOutputIntent}/{@link #setOutputIntent(OutputIntent)}) PDF belgesinin hazırlandığı hedef çıktı cihazını veya koşulunu belirtir. Belgedeki renklerin hedef cihazda doğru şekilde işlenmesini sağlamak için kullanılır.

### setPageByPageFontProcess {#setPageByPageFontProcess-boolean-}
```
public void setPageByPageFontProcess(boolean b)
```

Sayfa sayfa temelli yazı tipi analizi modunu etkinleştir. Varsayılan değer = false

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| b |  | boolean değer |

### setPuaTextProcessingStrategy {#setPuaTextProcessingStrategy-int-}
```
public void setPuaTextProcessingStrategy(int value)
```

Unicode Özel Kullanım Alanı (PUA) içindeki sembolleri işleme stratejisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PuaProcessingStrategy öğesi @see PuaProcessingStrategy |

### setSymbolicFontEncodingStrategy {#setSymbolicFontEncodingStrategy-com.aspose.pdf.PdfASymbolicFontEncodingStrategy-}
Sembolik TrueType yazı tipinin birden fazla kodlama alt tablosu varsa, sembolik yazı tipleri için kodlama verilerini kopyalama stratejisi.

### setTransferInfo {#setTransferInfo-boolean-}
```
public final void setTransferInfo(boolean value)
```

PDF 2.0'a dönüştürülürken Bilgi'den MetaVeri'ye veri aktarılıp aktarılmayacağını alır veya ayarlar. Varsayılan olarak true.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTransparencyAction {#setTransparencyAction-com.aspose.pdf.ConvertTransparencyAction-}
Görüntü maskeli nesneler için eylem

### setTransparencyIgnore {#setTransparencyIgnore-boolean-}
```
public void setTransparencyIgnore(boolean value)
```

Varsayılan değer FALSE olduğunda şeffaflık rengi belge görünümünü korumak için işlenir. TRUE değeriyle şeffaflık rengi şeffaf olmayan bir renge dönüştürülür, bazı nesneler örtülebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setTransparencyResolution {#setTransparencyResolution-int-}
```
public void setTransparencyResolution(int dpi)
```

Şeffaf görüntülerin dönüştürülmesi sırasında çözünürlüğü ayarlar. Çözünürlük ne kadar yüksek olursa, dönüşüm hızı o kadar yavaş olur. Varsayılan değer 300'dür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpi |  | Çözünürlük değeri |

### setUnicodeProcessingRules {#setUnicodeProcessingRules-com.aspose.pdf.ToUnicodeProcessingRules-}
Unicode eşlemesiyle ilgili sorunları çözmek için kurallar. Null olabilir.
