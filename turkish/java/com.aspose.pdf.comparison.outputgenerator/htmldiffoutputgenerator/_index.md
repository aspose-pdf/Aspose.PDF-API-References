---
title: "HtmlDiffOutputGenerator"
linktitle: "HtmlDiffOutputGenerator"
second_title: "Aspose.PDF for Java API Referansı"
description: "Metin farklarının html temsilini üretmek için bir sınıfı temsil eder. Silinen satır sonları - paragraf işareti ile gösterilir."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.comparison.outputgenerator/htmldiffoutputgenerator/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.outputgenerator.HtmlDiffOutputGenerator

**All Implemented Interfaces:**
IFileOutputGenerator, IStringOutputGenerator

```
public class HtmlDiffOutputGenerator extends Object implements IStringOutputGenerator , IFileOutputGenerator
```

Metin farklarının html temsilini üretmek için bir sınıfı temsil eder. Silinen satır sonları - paragraf işareti ile gösterilir.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator--) | Bir {@link HtmlDiffOutputGenerator} sınıfının bir örneğini oluşturur. |
| [HtmlDiffOutputGenerator](#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-) | Bir {@link HtmlDiffOutputGenerator} sınıfının bir örneğini oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [generateOutput](#generateOutput-java.util.List-) | Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [generateOutput](#generateOutput-java.util.List-java.lang.String-) | Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [generateOutput1](#generateOutput1-java.util.List-) | Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [generateOutput1](#generateOutput1-java.util.List-java.lang.String-) | Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder. |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-) |  |
| [generateOutputInternal](#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-) | Dahili yöntem |
| [generateOutputInternal1](#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-) |  |
| [getDeleteStyle](#getDeleteStyle--) | Silme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [getEqualStyle](#getEqualStyle--) | Eşit işlem için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [getInsertStyle](#getInsertStyle--) | Ekleme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [getStrikethroughDeleted](#getStrikethroughDeleted--) | Silme işlemi için text-decoration: line-through stilini alır veya ayarlar. Varsayılan değer {@code False}. |
| [setDeleteStyle](#setDeleteStyle-java.lang.String-) | Silme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [setEqualStyle](#setEqualStyle-java.lang.String-) | Eşit işlem için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [setInsertStyle](#setInsertStyle-java.lang.String-) | Ekleme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66; |
| [setStrikethroughDeleted](#setStrikethroughDeleted-boolean-) | Silme işlemi için text-decoration: line-through stilini alır veya ayarlar. Varsayılan değer {@code False}. |

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator--}
```
public HtmlDiffOutputGenerator()
```

Bir {@link HtmlDiffOutputGenerator} sınıfının bir örneğini oluşturur.

### HtmlDiffOutputGenerator {#HtmlDiffOutputGenerator-com.aspose.pdf.comparison.outputgenerator.OutputTextStyle-}
Bir {@link HtmlDiffOutputGenerator} sınıfının bir örneğini oluşturur.

### generateOutput {#generateOutput-java.util.List-}
Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder.

### generateOutput {#generateOutput-java.util.List-java.lang.String-}
Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder.

### generateOutput1 {#generateOutput1-java.util.List-}
Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder.

### generateOutput1 {#generateOutput1-java.util.List-java.lang.String-}
Metinler arasındaki farklara dayanarak çıktıyı oluşturur ve bir dosyaya kaydeder.

### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-}


### generateOutputInternal {#generateOutputInternal-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-}
Dahili yöntem

### generateOutputInternal1 {#generateOutputInternal1-com.aspose.ms.System.Collections.Generic.List-java.lang.String-}


### getDeleteStyle {#getDeleteStyle--}
```
public final String getDeleteStyle()
```

Silme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

**Returns:**
String değeri

### getEqualStyle {#getEqualStyle--}
```
public final String getEqualStyle()
```

Eşit işlem için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

**Returns:**
String değeri

### getInsertStyle {#getInsertStyle--}
```
public final String getInsertStyle()
```

Ekleme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

**Returns:**
String değeri

### getStrikethroughDeleted {#getStrikethroughDeleted--}
```
public final boolean getStrikethroughDeleted()
```

Silme işlemi için text-decoration: line-through stilini alır veya ayarlar. Varsayılan değer {@code False}.

**Returns:**
boolean değer

### setDeleteStyle {#setDeleteStyle-java.lang.String-}
Silme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

### setEqualStyle {#setEqualStyle-java.lang.String-}
Eşit işlem için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

### setInsertStyle {#setInsertStyle-java.lang.String-}
Ekleme işlemi için CSS stil dizesini alır ve ayarlar. Örnek: color: #003300; background-color: #ccff66;

### setStrikethroughDeleted {#setStrikethroughDeleted-boolean-}
```
public final void setStrikethroughDeleted(boolean value)
```

Silme işlemi için text-decoration: line-through stilini alır veya ayarlar. Varsayılan değer {@code False}.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |
