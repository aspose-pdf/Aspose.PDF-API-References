---
title: "Artefakt"
linktitle: "Artefakt"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, PDF Artifact nesnesini temsil eder."
type: docs
weight: 190
url: /tr/java/com.aspose.pdf/artifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class Artifact extends Object implements com.aspose.ms.System.IDisposable, Closeable
```

Sınıf, PDF Artifact nesnesini temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Artifact](#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-) | Belirtilen tip ve alt tip ile artefaktın yapıcı metodu |
| [Artifact](#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-) | Bu yapıcı, artefakt sayfadan okunduğunda kullanılır. |
| [Artifact](#Artifact-java.lang.String-java.lang.String-) | Belirtilen tip ve alt tip ile artefaktın yapıcı metodu |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [beginUpdates](#beginUpdates--) | Silinen güncellemeleri başlat. Performansı artırmak için aynı artefakt üzerinde birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, artefakt değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında yapın. Bu, sayfa içeriğinin yalnızca bir kez değiştirilmesini sağlar. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates(); |
| [close](#close--) | Bu belge tarafından kullanılan tüm kaynakları kapatır. |
| [dispose](#dispose--) | Artefakti serbest bırakın. Bu yöntem artık kullanılmıyor, yerine close() kullanın. |
| [getArtifactHorizontalAlignment](#getArtifactHorizontalAlignment--) | Artefaktın yatay hizalamasını alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır. |
| [getArtifactVerticalAlignment](#getArtifactVerticalAlignment--) | Artefaktın dikey hizalamasını alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır. |
| [getBottomMargin](#getBottomMargin--) | Artefaktın alt kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır. |
| [getContents](#getContents--) | Artefaktın iç operatör koleksiyonunu alır. |
| [getCustomSubtype](#getCustomSubtype--) | Artefakt alt tipinin adını alır. Artefakt alt tipi standart bir alt tip değilse kullanılabilir. |
| [getCustomType](#getCustomType--) | Artefakt tipinin adını alır. Artefakt tipi standart değilse kullanılabilir. |
| [getForm](#getForm--) | Artefaktın XFormunu alır (XForm kullanılıyorsa). |
| [getImage](#getImage--) | Artefaktın görüntüsünü alır (varsa). |
| [getLeftMargin](#getLeftMargin--) | Artefaktın sol kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır. |
| [getLines](#getLines--) | Çok satırlı metin artefaktının satırları. |
| [getOpacity](#getOpacity--) | Artefaktın opaklığını alır. Olası değerler 0..1 aralığındadır. |
| [getPosition](#getPosition--) | Artefakt konumunu alır. Bu özellik belirtilmişse, kenar boşlukları ve hizalamalar yoksayılır. |
| [getRectangle](#getRectangle--) | Artefaktın dikdörtgenini alır. |
| [getRightMargin](#getRightMargin--) | Artefaktın sağ kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır. |
| [getRotation](#getRotation--) | Artefaktın döndürme açısını alır. |
| [getSubtype](#getSubtype--) | Artefakt alt tipini alır. Artefaktın standart olmayan bir alt tipi varsa, alt tipin adı CustomSubtype aracılığıyla okunabilir. |
| [getText](#getText--) | Artefaktın metnini alır. |
| [getTextState](#getTextState--) | Artefakt metni için metin durumu. |
| [getTopMargin](#getTopMargin--) | Artefaktın üst kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yok sayılır. |
| [getType](#getType--) | Artefakt tipini alır. |
| [getValue](#getValue-java.lang.String-) | Artefaktın özel değerini alır. |
| [isBackground](#isBackground--) | Doğruysa, Artefakt sayfa içeriğinin arkasına yerleştirilir. |
| [removeValue](#removeValue-java.lang.String-) | Artefaktan özel değeri kaldır. |
| [saveUpdates](#saveUpdates--) | BeginUpdates() çağrısından sonra yapılan artefakt üzerindeki tüm güncellemeleri kaydeder. |
| [setArtifactHorizontalAlignment](#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Artefaktın yatay hizalamasını alır. |
| [setArtifactVerticalAlignment](#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Artefaktın dikey hizalamasını ayarlar. |
| [setBackground](#setBackground-boolean-) | Doğruysa, Artefakt sayfa içeriğinin arkasına yerleştirilir. |
| [setBottomMargin](#setBottomMargin-double-) | Artefaktın alt kenar boşluğunu ayarlar. |
| [setCustomSubtype](#setCustomSubtype-java.lang.String-) |  |
| [setCustomType](#setCustomType-java.lang.String-) | Artefakt tipinin adını ayarlar. Artefakt tipi standart dışı ise kullanılabilir. |
| [setImage](#setImage-java.io.InputStream-) | Artefaktın görüntüsünü ayarlar. |
| [setImage](#setImage-java.lang.String-) | Artefaktın görüntüsünü ayarlar. |
| [setLeftMargin](#setLeftMargin-double-) | Artefaktın sol kenar boşluğunu ayarlar. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yok sayılır. |
| [setLinesAndState](#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-) | Artefaktın metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye izin verir. |
| [setOpacity](#setOpacity-double-) | Artefaktın opaklığını ayarlar. Olası değerler 0..1 aralığındadır. |
| [setPageNumberReplacementString](#setPageNumberReplacementString-java.lang.String-) | Sayfa numarasıyla değiştirilecek dizeyi ayarlar. Varsayılan değer #dır. |
| [setPdfPage](#setPdfPage-com.aspose.pdf.Page-) | Belge sayfasına artefakt olarak yerleştirilen PDF sayfasını ayarlar. |
| [setPosition](#setPosition-com.aspose.pdf.Point-) | Artefakt konumunu ayarlar. |
| [setRightMargin](#setRightMargin-double-) | Artefaktın sağ kenar boşluğunu ayarlar. |
| [setRotation](#setRotation-double-) | Artefaktın döndürme açısını ayarlar. |
| [setSubtype](#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-) | Artefakt alt türünü ayarlar. |
| [setText](#setText-com.aspose.pdf.facades.FormattedText-) | Artefaktın metnini ayarlar. |
| [setText](#setText-java.lang.String-) | Artefaktın metnini ayarlar. |
| [setTextAndState](#setTextAndState-java.lang.String-com.aspose.pdf.TextState-) | Artefaktın metnini ve metin özelliklerini ayarlar. |
| [setTextState](#setTextState-com.aspose.pdf.TextState-) | Artefakt metni için metin durumu. |
| [setTopMargin](#setTopMargin-double-) | Artefaktın üst kenar boşluğunu ayarlar. |
| [setType](#setType-com.aspose.pdf.Artifact.ArtifactType-) | Artefakt tipini ayarlar. |
| [setValue](#setValue-java.lang.String-java.lang.String-) | Artefaktın özel değerini ayarlar. |

### Artifact {#Artifact-com.aspose.pdf.Artifact.ArtifactType-com.aspose.pdf.Artifact.ArtifactSubtype-}
Belirtilen tip ve alt tip ile artefaktın yapıcı metodu

### Artifact {#Artifact-com.aspose.pdf.ArtifactCollection-com.aspose.pdf.Artifact.ArtifactContext-com.aspose.ms.System.Collections.Generic.List-com.aspose.pdf.engine.data.IPdfDictionary-}
Bu yapıcı, artefakt sayfadan okunduğunda kullanılır.

### Artifact {#Artifact-java.lang.String-java.lang.String-}
Belirtilen tip ve alt tip ile artefaktın yapıcı metodu

### beginUpdates {#beginUpdates--}
```
public void beginUpdates()
```

Silinen güncellemeleri başlat. Performansı artırmak için aynı artefakt üzerinde birden fazla değişiklik yapmanız gerekiyorsa bu özelliği kullanın. Genellikle artefakt operatörleri, artefakt özelliği değiştiğinde her zaman değiştirilir. Bu, artefakt değiştiğinde sayfa içeriğinin her seferinde değişmesine neden olur. Bu etkiyi önlemek için tüm artefakt güncellemelerini StartUpdates/SaveUpdates çağrıları arasında yapın. Bu, sayfa içeriğinin yalnızca bir kez değiştirilmesini sağlar. Artifact art = doc.getPages().get_Item(1).getArtifacts().get_Item(1); art.beginUpdates(); art.setOpacity ( 0.3f); art.setPosition ( new Point(10,10)); art.setRotation (30); art.saveUpdates();

### close {#close--}
```
public void close()
```

Bu belge tarafından kullanılan tüm kaynakları kapatır.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Artefakti serbest bırakın. Bu yöntem artık kullanılmıyor, yerine close() kullanın.

### getArtifactHorizontalAlignment {#getArtifactHorizontalAlignment--}
```
public HorizontalAlignment getArtifactHorizontalAlignment()
```

Artefaktın yatay hizalamasını alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır.

**Returns:**
HorizontalAlignment değeri @see HorizontalAlignment

### getArtifactVerticalAlignment {#getArtifactVerticalAlignment--}
```
public VerticalAlignment getArtifactVerticalAlignment()
```

Artefaktın dikey hizalamasını alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır.

**Returns:**
VerticalAlignment değeri. @see VerticalAlignment

### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Artefaktın alt kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır.

**Returns:**
alt kenar boşluğu.

### getContents {#getContents--}
```
public List < Operator > getContents()
```

Artefaktın iç operatör koleksiyonunu alır.

**Returns:**
artefakt iç operatörlerini listeler.

### getCustomSubtype {#getCustomSubtype--}
```
public String getCustomSubtype()
```

Artefakt alt tipinin adını alır. Artefakt alt tipi standart bir alt tip değilse kullanılabilir.

**Returns:**
String değeri

### getCustomType {#getCustomType--}
```
public String getCustomType()
```

Artefakt tipinin adını alır. Artefakt tipi standart değilse kullanılabilir.

**Returns:**
String artefakt adı

### getForm {#getForm--}
```
public XForm getForm()
```

Artefaktın XFormunu alır (XForm kullanılıyorsa).

**Returns:**
XForm nesnesi

### getImage {#getImage--}
```
public XImage getImage()
```

Artefaktın görüntüsünü alır (varsa).

**Returns:**
XImage nesnesi

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Artefaktın sol kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır.

**Returns:**
artefaktın sol kenar boşluğu.

### getLines {#getLines--}
```
public final List < String > getLines()
```

Çok satırlı metin artefaktının satırları.

**Returns:**
String listesi

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Artefaktın opaklığını alır. Olası değerler 0..1 aralığındadır.

**Returns:**
artefaktın opaklığı.

### getPosition {#getPosition--}
```
public Point getPosition()
```

Artefakt konumunu alır. Bu özellik belirtilmişse, kenar boşlukları ve hizalamalar yoksayılır.

**Returns:**
artefakt konumu.

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Artefaktın dikdörtgenini alır.

**Returns:**
Rectangle nesnesi

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Artefaktın sağ kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yoksayılır.

**Returns:**
artefaktın sağ kenar boşluğu.

### getRotation {#getRotation--}
```
public double getRotation()
```

Artefaktın döndürme açısını alır.

**Returns:**
artefakt dönüş açısı.

### getSubtype {#getSubtype--}
```
public Artifact.ArtifactSubtype getSubtype()
```

Artefakt alt tipini alır. Artefaktın standart olmayan bir alt tipi varsa, alt tipin adı CustomSubtype aracılığıyla okunabilir.

**Returns:**
artefakt alt türü. @see ArtifactSubtype

### getText {#getText--}
```
public String getText()
```

Artefaktın metnini alır.

**Returns:**
String değeri

### getTextState {#getTextState--}
```
public final TextState getTextState()
```

Artefakt metni için metin durumu.

**Returns:**
TextState örneği

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Artefaktın üst kenar boşluğunu alır. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yok sayılır.

**Returns:**
artefaktın üst kenar boşluğu.

### getType {#getType--}
```
public Artifact.ArtifactType getType()
```

Artefakt tipini alır.

**Returns:**
artefakt tür değeri. @see ArtifactType

### getValue {#getValue-java.lang.String-}
Artefaktın özel değerini alır.

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Doğruysa, Artefakt sayfa içeriğinin arkasına yerleştirilir.

**Returns:**
boolean değer

### removeValue {#removeValue-java.lang.String-}
Artefaktan özel değeri kaldır.

### saveUpdates {#saveUpdates--}
```
public void saveUpdates()
```

BeginUpdates() çağrısından sonra yapılan artefakt üzerindeki tüm güncellemeleri kaydeder.

### setArtifactHorizontalAlignment {#setArtifactHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Artefaktın yatay hizalamasını alır.

### setArtifactVerticalAlignment {#setArtifactVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Artefaktın dikey hizalamasını ayarlar.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Doğruysa, Artefakt sayfa içeriğinin arkasına yerleştirilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | boolean değer |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Artefaktın alt kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | alt kenar boşluğu. |

### setCustomSubtype {#setCustomSubtype-java.lang.String-}


### setCustomType {#setCustomType-java.lang.String-}
Artefakt tipinin adını ayarlar. Artefakt tipi standart dışı ise kullanılabilir.

### setImage {#setImage-java.io.InputStream-}
Artefaktın görüntüsünü ayarlar.

### setImage {#setImage-java.lang.String-}
Artefaktın görüntüsünü ayarlar.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Artefaktın sol kenar boşluğunu ayarlar. Konum açıkça (Position özelliğinde) belirtilmişse bu değer yok sayılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | artefaktın sol kenar boşluğu. |

### setLinesAndState {#setLinesAndState-java.lang.String:A-com.aspose.pdf.TextState-}
Artefaktın metnini ve metin özelliklerini ayarlar. Birden fazla satır belirtmeye izin verir.

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Artefaktın opaklığını ayarlar. Olası değerler 0..1 aralığındadır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | artefaktın opaklığı. |

### setPageNumberReplacementString {#setPageNumberReplacementString-java.lang.String-}
Sayfa numarasıyla değiştirilecek dizeyi ayarlar. Varsayılan değer #dır.

### setPdfPage {#setPdfPage-com.aspose.pdf.Page-}
Belge sayfasına artefakt olarak yerleştirilen PDF sayfasını ayarlar.

### setPosition {#setPosition-com.aspose.pdf.Point-}
Artefakt konumunu ayarlar.

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Artefaktın sağ kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | artefaktın sağ kenar boşluğu. |

### setRotation {#setRotation-double-}
```
public void setRotation(double value)
```

Artefaktın döndürme açısını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | artefakt dönüş açısı. |

### setSubtype {#setSubtype-com.aspose.pdf.Artifact.ArtifactSubtype-}
Artefakt alt türünü ayarlar.

### setText {#setText-com.aspose.pdf.facades.FormattedText-}
Artefaktın metnini ayarlar.

### setText {#setText-java.lang.String-}
Artefaktın metnini ayarlar.

### setTextAndState {#setTextAndState-java.lang.String-com.aspose.pdf.TextState-}
Artefaktın metnini ve metin özelliklerini ayarlar.

### setTextState {#setTextState-com.aspose.pdf.TextState-}
Artefakt metni için metin durumu.

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Artefaktın üst kenar boşluğunu ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | artefaktın üst kenar boşluğu. |

### setType {#setType-com.aspose.pdf.Artifact.ArtifactType-}
Artefakt tipini ayarlar.

### setValue {#setValue-java.lang.String-java.lang.String-}
Artefaktın özel değerini ayarlar.
