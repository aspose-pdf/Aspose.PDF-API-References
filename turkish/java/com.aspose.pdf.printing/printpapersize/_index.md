---
title: "PrintPaperSize"
linktitle: "PrintPaperSize"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir kağıt parçasının boyutunu belirtir."
type: docs
weight: 100
url: /tr/java/com.aspose.pdf.printing/printpapersize/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPaperSize

```
public class PrintPaperSize extends Object
```

Bir kağıt parçasının boyutunu belirtir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PrintPaperSize](#PrintPaperSize--) | PaperSize sınıfının yeni bir örneğini başlatır. |
| [PrintPaperSize](#PrintPaperSize-int-java.lang.String-int-int-) | PaperSize sınıfının yeni bir örneğini başlatır. |
| [PrintPaperSize](#PrintPaperSize-java.lang.String-int-int-) | PaperSize sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeight](#getHeight--) | Kağıdın yüksekliğini alır veya ayarlar, inçin yüzde birimlerinde. |
| [getKind](#getKind--) | Kağıdın türünü alır. |
| [getPaperName](#getPaperName--) | Kağıdın türünün adını alır veya ayarlar. |
| [getRawKind](#getRawKind--) | PaperSize değerlerinden birini veya özel bir değeri temsil eden bir tam sayıyı alır veya ayarlar. |
| [getWidth](#getWidth--) | Kağıdın genişliğini, inçin yüzde bir biriminde alır veya ayarlar. |
| [setHeight](#setHeight-int-) | Kağıdın yüksekliğini alır veya ayarlar, inçin yüzde birimlerinde. |
| [setPaperName](#setPaperName-java.lang.String-) | Kağıdın türünün adını alır. |
| [setWidth](#setWidth-int-) | Kağıdın genişliğini, inçin yüzde bir biriminde ayarlar. |
| [toNativePaperSize](#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Dönüştürür {@link PaperSize} öğesini Windows'a özgü System.Drawing.Printing.PaperSize'a. |
| [toString](#toString--) | Bu örneğin adını alır. |

### PrintPaperSize {#PrintPaperSize--}
```
public PrintPaperSize()
```

PaperSize sınıfının yeni bir örneğini başlatır.

### PrintPaperSize {#PrintPaperSize-int-java.lang.String-int-int-}
PaperSize sınıfının yeni bir örneğini başlatır.

### PrintPaperSize {#PrintPaperSize-java.lang.String-int-int-}
PaperSize sınıfının yeni bir örneğini başlatır.

### getHeight {#getHeight--}
```
public int getHeight()
```

Kağıdın yüksekliğini alır veya ayarlar, inçin yüzde birimlerinde.

**Returns:**
int değer

### getKind {#getKind--}
```
public int getKind()
```

Kağıdın türünü alır.

**Returns:**
int değer @see PrinterPaperKind

### getPaperName {#getPaperName--}
```
public String getPaperName()
```

Kağıdın türünün adını alır veya ayarlar.

**Returns:**
String değeri

### getRawKind {#getRawKind--}
```
public int getRawKind()
```

PaperSize değerlerinden birini veya özel bir değeri temsil eden bir tam sayıyı alır veya ayarlar.

**Returns:**
int değer

### getWidth {#getWidth--}
```
public int getWidth()
```

Kağıdın genişliğini, inçin yüzde bir biriminde alır veya ayarlar.

**Returns:**
int değer

### setHeight {#setHeight-int-}
```
public void setHeight(int value)
```

Kağıdın yüksekliğini alır veya ayarlar, inçin yüzde birimlerinde.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPaperName {#setPaperName-java.lang.String-}
Kağıdın türünün adını alır.

### setWidth {#setWidth-int-}
```
public void setWidth(int value)
```

Kağıdın genişliğini, inçin yüzde bir biriminde ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### toNativePaperSize {#toNativePaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Dönüştürür {@link PaperSize} öğesini Windows'a özgü System.Drawing.Printing.PaperSize'a.

### toString {#toString--}
```
public String toString()
```

Bu örneğin adını alır.

**Returns:**
String değeri
