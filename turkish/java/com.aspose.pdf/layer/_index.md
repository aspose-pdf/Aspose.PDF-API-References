---
title: "Layer"
linktitle: "Layer"
second_title: "Aspose.PDF for Java API Referansı"
description: "PDF sayfası içinde bir katmanı temsil eder."
type: docs
weight: 2640
url: /tr/java/com.aspose.pdf/layer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Layer

```
public class Layer extends Object
```

PDF sayfası içinde bir katmanı temsil eder.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Layer](#Layer-java.lang.String-java.lang.String-) | {@code Layer} sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [delete](#delete--) | PDF belgesinden geçerli katmanı siler. |
| [flatten](#flatten-boolean-) | Belirtilen katmanı düzleştirir. |
| [getContents](#getContents--) | <p> Katman içeriğini alır. </p> |
| [getDefaultState](#getDefaultState--) | PDF katmanının varsayılan durumunu alır. |
| [getId](#getId--) | Katman kimliğini alır. |
| [getLocked](#getLocked--) | Katmanın kilitli olup olmadığını gösteren bir değeri alır. |
| [getName](#getName--) | Katman adını alır. |
| [lock](#lock--) | Katmanı kilitler. |
| [save](#save-java.io.OutputStream-) | Geçerli katmanı bir PDF belgesine kaydeder. |
| [save](#save-java.lang.String-) | Geçerli katmanı bir PDF belgesine kaydeder. |
| [setDefaultState](#setDefaultState-com.aspose.pdf.DefaultState-) | PDF katmanının varsayılan durumunu ayarlar. |
| [unlock](#unlock--) | Katmanın kilidini açar. |

### Layer {#Layer-java.lang.String-java.lang.String-}
{@code Layer} sınıfının yeni bir örneğini başlatır.

### delete {#delete--}
```
public final void delete()
```

PDF belgesinden geçerli katmanı siler.

### flatten {#flatten-boolean-}
```
public final void flatten(boolean cleanupContentStream)
```

Belirtilen katmanı düzleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cleanupContentStream |  | İçerik akışından isteğe bağlı içerik grubu işaretçilerini kaldırıp kaldırmayacağını belirtir. {@code cleanupContentStream} parametresini false olarak ayarlamak, düzleştirme işlemini hızlandırır. |

### getContents {#getContents--}
```
public List < Operator > getContents()
```

<p> Katman içeriğini alır. </p>

**Returns:**
{@code List<Operator>} nesnesi

### getDefaultState {#getDefaultState--}
```
public final DefaultState getDefaultState()
```

PDF katmanının varsayılan durumunu alır.

**Returns:**
PDF katmanının varsayılan durumu.

### getId {#getId--}
```
public String getId()
```

Katman kimliğini alır.

**Returns:**
String değeri

### getLocked {#getLocked--}
```
public final boolean getLocked()
```

Katmanın kilitli olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean değer

### getName {#getName--}
```
public String getName()
```

Katman adını alır.

**Returns:**
String değeri

### lock {#lock--}
```
public final void lock()
```

Katmanı kilitler.

### save {#save-java.io.OutputStream-}
Geçerli katmanı bir PDF belgesine kaydeder.

### save {#save-java.lang.String-}
Geçerli katmanı bir PDF belgesine kaydeder.

### setDefaultState {#setDefaultState-com.aspose.pdf.DefaultState-}
PDF katmanının varsayılan durumunu ayarlar.

### unlock {#unlock--}
```
public final void unlock()
```

Katmanın kilidini açar.
