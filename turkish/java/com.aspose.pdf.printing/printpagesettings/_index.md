---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Aspose.PDF for Java API Referansı"
description: "Tek bir yazdırılmış sayfaya uygulanan ayarları belirtir."
type: docs
weight: 90
url: /tr/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Tek bir yazdırılmış sayfaya uygulanan ayarları belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Varsayılan yazıcıyı kullanarak PageSettings sınıfının yeni bir örneğini başlatır. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Varsayılan yazıcıyı kullanarak PageSettings sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds](#getBounds--) | Landscape özelliğiyle belirtilen sayfa yönünü dikkate alarak sayfanın boyutunu alır. |
| [getHardMarginX](#getHardMarginX--) | Sayfanın sol tarafındaki sabit kenar boşluğunun, inçin yüzde birinde x koordinatını alır. |
| [getHardMarginY](#getHardMarginY--) | Sayfanın üst tarafındaki sabit kenar boşluğunun, inçin yüzde birinde y koordinatını alır. |
| [getMargins](#getMargins--) | Bu sayfa için kenar boşluklarını alır. |
| [getPageSettings](#getPageSettings--) | Sayfa Ayarlarını alır |
| [getPaperSize](#getPaperSize--) | Sayfa için kağıt boyutunu alır. |
| [getPaperSource](#getPaperSource--) | Sayfanın kağıt kaynağını alır; örneğin, yazıcının üst tepsisi. |
| [getPrintableArea](#getPrintableArea--) | Yazıcı için sayfanın yazdırılabilir alanının sınırlarını alır. |
| [getPrinterResolution](#getPrinterResolution--) | Sayfa için yazıcı çözünürlüğünü alır. |
| [getPrinterSettings](#getPrinterSettings--) | Sayfa ile ilişkili yazıcı ayarlarını alır. |
| [isColor](#isColor--) | Sayfanın renkli yazdırılıp yazdırılmayacağını belirten bir değeri alır veya ayarlar. |
| [isLandscape](#isLandscape--) | Sayfanın yatay mı yoksa dikey mi yazdırıldığını belirten bir değeri alır veya ayarlar. |
| [setColor](#setColor-boolean-) | Sayfanın renkli yazdırılıp yazdırılmayacağını belirten bir değeri alır veya ayarlar. |
| [setLandscape](#setLandscape-boolean-) | Sayfanın yatay mı yoksa dikey mi yazdırıldığını belirten bir değeri alır veya ayarlar. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Bu sayfa için kenar boşluklarını ayarlar. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Sayfa için kağıt boyutunu ayarlar. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Sayfanın kağıt kaynağını ayarlar; örneğin, yazıcının üst tepsisi. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Sayfa için yazıcı çözünürlüğünü ayarlar. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Sayfayla ilişkili yazıcı ayarlarını belirler. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Varsayılan yazıcıyı kullanarak PageSettings sınıfının yeni bir örneğini başlatır.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Varsayılan yazıcıyı kullanarak PageSettings sınıfının yeni bir örneğini başlatır.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Landscape özelliğiyle belirtilen sayfa yönünü dikkate alarak sayfanın boyutunu alır.

**Returns:**
Rectangle nesnesi

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Sayfanın sol tarafındaki sabit kenar boşluğunun, inçin yüzde birinde x koordinatını alır.

**Returns:**
float değer

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Sayfanın üst tarafındaki sabit kenar boşluğunun, inçin yüzde birinde y koordinatını alır.

**Returns:**
float değer

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Bu sayfa için kenar boşluklarını alır.

**Returns:**
PrinterMargins nesnesi

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Sayfa Ayarlarını alır

**Returns:**
PageSettings nesnesi

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Sayfa için kağıt boyutunu alır.

**Returns:**
PrintPaperSize nesnesi

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Sayfanın kağıt kaynağını alır; örneğin, yazıcının üst tepsisi.

**Returns:**
PrintPaperSource nesnesi

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Yazıcı için sayfanın yazdırılabilir alanının sınırlarını alır.

**Returns:**
Rectangle nesnesi

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Sayfa için yazıcı çözünürlüğünü alır.

**Returns:**
PdfPrinterResolution nesnesi

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Sayfa ile ilişkili yazıcı ayarlarını alır.

**Returns:**
PdfPrinterSettings nesnesi

### isColor {#isColor--}
```
public boolean isColor()
```

Sayfanın renkli yazdırılıp yazdırılmayacağını belirten bir değeri alır veya ayarlar.

**Returns:**
boolean değer

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Sayfanın yatay mı yoksa dikey mi yazdırıldığını belirten bir değeri alır veya ayarlar.

**Returns:**
boolean değer

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Sayfanın renkli yazdırılıp yazdırılmayacağını belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Sayfanın yatay mı yoksa dikey mi yazdırıldığını belirten bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Bu sayfa için kenar boşluklarını ayarlar.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Sayfa için kağıt boyutunu ayarlar.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Sayfanın kağıt kaynağını ayarlar; örneğin, yazıcının üst tepsisi.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Sayfa için yazıcı çözünürlüğünü ayarlar.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Sayfayla ilişkili yazıcı ayarlarını belirler.
