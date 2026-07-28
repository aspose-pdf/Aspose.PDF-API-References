---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir belgenin nasıl yazdırıldığına dair bilgileri, yazıcı dahil olmak üzere, belirtir."
type: docs
weight: 50
url: /tr/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Bir belgenin nasıl yazdırıldığına dair bilgileri, yazıcı dahil olmak üzere, belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | PrinterSettings sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canDuplex](#canDuplex--) | Yazıcının çift taraflı baskıyı destekleyip desteklemediğini gösteren bir değeri alır. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Graphics2D nesnesini al |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Graphics2D nesnesini al |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Graphics2D nesnesini al |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Graphics2D nesnesini al |
| [deepClone](#deepClone--) | Klonlanmış nesneyi al |
| [getCopies](#getCopies--) | Yazdırılacak belgenin kopya sayısını alır. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Bu yazıcı için varsayılan sayfa ayarlarını alır. |
| [getDuplex](#getDuplex--) | Çift taraflı baskı için yazıcı ayarını alır veya ayarlar. |
| [getFromPage](#getFromPage--) | Yazdırılacak ilk sayfanın sayfa numarasını alır veya ayarlar. |
| [getInstalledPrinters](#getInstalledPrinters--) | Bilgisayara yüklü tüm yazıcıların adlarını alır. |
| [getLandscapeAngle](#getLandscapeAngle--) | Dikey yönlendirmeyi yatay yönlendirmeye dönüştürmek için döndürülen açıyı derece cinsinden alır. |
| [getMaximumCopies](#getMaximumCopies--) | Yazıcının bir seferde kullanıcının yazdırmasına izin verdiği azami kopya sayısını alır. |
| [getMaximumPage](#getMaximumPage--) | PrintDialog içinde seçilebilecek azami FromPage veya ToPage değerini alır veya ayarlar. |
| [getMinimumPage](#getMinimumPage--) | PrintDialog içinde seçilebilecek asgari FromPage veya ToPage değerini alır veya ayarlar. |
| [getPaperSizes](#getPaperSizes--) | Bu yazıcı tarafından desteklenen kağıt boyutlarını alır. |
| [getPaperSources](#getPaperSources--) | Yazıcıda mevcut olan kağıt kaynak tepsilerini alır. |
| [getPrinterName](#getPrinterName--) | Kullanılacak yazıcının adını alır veya ayarlar. |
| [getPrinterResolutions](#getPrinterResolutions--) | Bu yazıcı tarafından desteklenen tüm çözünürlükleri alır. |
| [getPrinterSettings](#getPrinterSettings--) | PrinterSettings nesnesini döndürür |
| [getPrintFileName](#getPrintFileName--) | Dosyaya yazdırılırken dosya adını alır veya ayarlar. |
| [getPrintRange](#getPrintRange--) | Kullanıcının yazdırmak için belirttiği sayfa numaralarını alır veya ayarlar. |
| [getSelectedPages](#getSelectedPages--) | Yazdırılacak seçili sayfa sayısını alır. |
| [getToPage](#getToPage--) | Yazdırılacak son sayfanın numarasını alır veya ayarlar. |
| [isCollate](#isCollate--) | Yazdırılan belgenin birleştirilmiş olup olmadığını gösteren değeri alır veya ayarlar. |
| [isDefaultPrinter](#isDefaultPrinter--) | Kullanıcı PrinterName özelliğini açıkça ayarlamadığında, PrinterName özelliğinin varsayılan yazıcıyı belirleyip belirlemediğini gösteren değeri alır. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Yazıcının Desteklenen Doğrudan Baskı (Supported DirectPrinting) olup olmadığını gösteren değeri alır |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Yazıcının Desteklenen Doğrudan Baskı (Supported DirectPrinting) olup olmadığını gösteren değeri alır |
| [isPlotter](#isPlotter--) | Yazıcının bir plotter olup olmadığını gösteren değeri alır. |
| [isPrintToFile](#isPrintToFile--) | Baskı çıktısının bir bağlantı noktasına yerine dosyaya gönderilip gönderilmediğini gösteren değeri alır. |
| [isSupportsColor](#isSupportsColor--) | Bu yazıcının renkli baskıyı destekleyip desteklemediğini gösteren değeri alır. |
| [isValid](#isValid--) | PrinterName özelliğinin geçerli bir yazıcıyı belirleyip belirlemediğini gösteren değeri alır. |
| [setCollate](#setCollate-boolean-) | Yazdırılan belgenin birleştirilmiş olup olmadığını gösteren değeri alır veya ayarlar. |
| [setCopies](#setCopies-short-) | Yazdırılacak belgenin kopya sayısını ayarlar. |
| [setDuplex](#setDuplex-int-) | Çift taraflı baskı için yazıcı ayarını alır veya ayarlar. |
| [setFromPage](#setFromPage-int-) | Yazdırılacak ilk sayfanın sayfa numarasını alır veya ayarlar. |
| [setMaximumPage](#setMaximumPage-int-) | PrintDialog içinde seçilebilecek azami FromPage veya ToPage değerini alır veya ayarlar. |
| [setMinimumPage](#setMinimumPage-int-) | PrintDialog içinde seçilebilecek asgari FromPage veya ToPage değerini alır veya ayarlar. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Kullanılacak yazıcının adını ayarlar. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Yazdırılacak dosya adını ayarlar. |
| [setPrintRange](#setPrintRange-int-) | Kullanıcının yazdırılmak üzere belirttiği sayfa numaralarını ayarlar. |
| [setPrintToFile](#setPrintToFile-boolean-) | Yazdırma çıktısının bir bağlantı noktasına yerine bir dosyaya gönderilip gönderilmeyeceğini belirten bir değeri ayarlar. |
| [setSelectedPages](#setSelectedPages-int:A-) | Yazdırılacak seçili sayfa sayısını ayarlar. |
| [setToPage](#setToPage-int-) | Yazdırılacak son sayfanın numarasını ayarlar. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

PrinterSettings sınıfının yeni bir örneğini başlatır.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Yazıcının çift taraflı baskıyı destekleyip desteklemediğini gösteren bir değeri alır.

**Returns:**
boolean değer

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Graphics2D nesnesini al

**Returns:**
Graphics2D nesnesi

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Graphics2D nesnesini al

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

**Returns:**
Graphics2D nesnesi

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Graphics2D nesnesini al

**Returns:**
Graphics2D nesnesi

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Graphics2D nesnesini al

**Returns:**
Graphics2D nesnesi

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Klonlanmış nesneyi al

**Returns:**
PdfPrinterSettings nesnesi

### getCopies {#getCopies--}
```
public short getCopies()
```

Yazdırılacak belgenin kopya sayısını alır.

**Returns:**
kopya sayısı

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Bu yazıcı için varsayılan sayfa ayarlarını alır.

**Returns:**
varsayılan sayfa ayarları

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Çift taraflı baskı için yazıcı ayarını alır veya ayarlar.

**Returns:**
int değeri @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Yazdırılacak ilk sayfanın sayfa numarasını alır veya ayarlar.

**Returns:**
int değer

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Bilgisayara yüklü tüm yazıcıların adlarını alır.

**Returns:**
{@code ArrayList<String>} nesnesi

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Dikey yönlendirmeyi yatay yönlendirmeye dönüştürmek için döndürülen açıyı derece cinsinden alır.

**Returns:**
int değer

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Yazıcının bir seferde kullanıcının yazdırmasına izin verdiği azami kopya sayısını alır.

**Returns:**
int değer

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

PrintDialog içinde seçilebilecek azami FromPage veya ToPage değerini alır veya ayarlar.

**Returns:**
int değer

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

PrintDialog içinde seçilebilecek asgari FromPage veya ToPage değerini alır veya ayarlar.

**Returns:**
int değer

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Bu yazıcı tarafından desteklenen kağıt boyutlarını alır.

**Returns:**
{@code ArrayList<PrintPaperSize> } nesnesi

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Yazıcıda mevcut olan kağıt kaynak tepsilerini alır.

**Returns:**
{@code ArrayList<PrintPaperSource> } nesnesi

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Kullanılacak yazıcının adını alır veya ayarlar.

**Returns:**
string nesnesi

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Bu yazıcı tarafından desteklenen tüm çözünürlükleri alır.

**Returns:**
PrinterResolutionCollection nesnesi

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

PrinterSettings nesnesini döndürür

**Returns:**
PrinterSettings nesnesi

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Dosyaya yazdırılırken dosya adını alır veya ayarlar.

**Returns:**
string nesnesi

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Kullanıcının yazdırmak için belirttiği sayfa numaralarını alır veya ayarlar.

**Returns:**
int değeri @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Yazdırılacak seçili sayfa sayısını alır.

**Returns:**
pagesList int dizisi @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Yazdırılacak son sayfanın numarasını alır veya ayarlar.

**Returns:**
int değer

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Yazdırılan belgenin birleştirilmiş olup olmadığını gösteren değeri alır veya ayarlar.

**Returns:**
boolean değer

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Kullanıcı PrinterName özelliğini açıkça ayarlamadığında, PrinterName özelliğinin varsayılan yazıcıyı belirleyip belirlemediğini gösteren değeri alır.

**Returns:**
boolean değer

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Yazıcının Desteklenen Doğrudan Baskı (Supported DirectPrinting) olup olmadığını gösteren değeri alır

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Yazıcının Desteklenen Doğrudan Baskı (Supported DirectPrinting) olup olmadığını gösteren değeri alır

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Yazıcının bir plotter olup olmadığını gösteren değeri alır.

**Returns:**
boolean değer

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Baskı çıktısının bir bağlantı noktasına yerine dosyaya gönderilip gönderilmediğini gösteren değeri alır.

**Returns:**
boolean değer

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Bu yazıcının renkli baskıyı destekleyip desteklemediğini gösteren değeri alır.

**Returns:**
boolean değer

### isValid {#isValid--}
```
public boolean isValid()
```

PrinterName özelliğinin geçerli bir yazıcıyı belirleyip belirlemediğini gösteren değeri alır.

**Returns:**
boolean değer

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Yazdırılan belgenin birleştirilmiş olup olmadığını gösteren değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Yazdırılacak belgenin kopya sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | kopya sayısı |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Çift taraflı baskı için yazıcı ayarını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değeri @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Yazdırılacak ilk sayfanın sayfa numarasını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

PrintDialog içinde seçilebilecek azami FromPage veya ToPage değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

PrintDialog içinde seçilebilecek asgari FromPage veya ToPage değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPrinterName {#setPrinterName-java.lang.String-}
Kullanılacak yazıcının adını ayarlar.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Yazdırılacak dosya adını ayarlar.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Kullanıcının yazdırılmak üzere belirttiği sayfa numaralarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PdfPrintRange öğesi @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Yazdırma çıktısının bir bağlantı noktasına yerine bir dosyaya gönderilip gönderilmeyeceğini belirten bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Yazdırılacak seçili sayfa sayısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pagesList |  | int dizisi @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Yazdırılacak son sayfanın numarasını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | PdfPrintRange öğesi @see PdfPrintRange |
