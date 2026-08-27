---
title: "PaginationArtifact"
linktitle: "PaginationArtifact"
second_title: "Aspose.PDF for Java API Referansı"
description: "Bir belgede sayfalama öğeleri için soyut temel sınıfı temsil eder."
type: docs
weight: 3460
url: /tr/java/com.aspose.pdf/paginationartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public abstract class PaginationArtifact extends Artifact
```

Bir belgede sayfalama öğeleri için soyut temel sınıfı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getEndPage](#getEndPage--) | Artefakt için son sayfa numarasını alır veya ayarlar. Değer 0'a eşit veya daha büyük olmalıdır. 0'dan küçük bir değer ayarlanırsa, 0 olarak ayarlanır. Varsayılan 0 değeri, son sayfa sınırının olmadığını gösterir. |
| [getStartPage](#getStartPage--) | Artefakt için başlangıç sayfa numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa, 1 olarak ayarlanır. |
| [getSubset](#getSubset--) | Artefaktın uygulanacağı sayfa alt kümesini alır veya ayarlar (ör. tüm sayfalar, çift sayfalar, tek sayfalar). |
| [setEndPage](#setEndPage-int-) | Artefakt için son sayfa numarasını alır veya ayarlar. Değer 0'a eşit veya daha büyük olmalıdır. 0'dan küçük bir değer ayarlanırsa, 0 olarak ayarlanır. Varsayılan 0 değeri, son sayfa sınırının olmadığını gösterir. |
| [setStartPage](#setStartPage-int-) | Artefakt için başlangıç sayfa numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa, 1 olarak ayarlanır. |
| [setSubset](#setSubset-int-) | Artefaktın uygulanacağı sayfa alt kümesini alır veya ayarlar (ör. tüm sayfalar, çift sayfalar, tek sayfalar). |

### getEndPage {#getEndPage--}
```
public final int getEndPage()
```

Artefakt için son sayfa numarasını alır veya ayarlar. Değer 0'a eşit veya daha büyük olmalıdır. 0'dan küçük bir değer ayarlanırsa, 0 olarak ayarlanır. Varsayılan 0 değeri, son sayfa sınırının olmadığını gösterir.

**Returns:**
int değer

### getStartPage {#getStartPage--}
```
public final int getStartPage()
```

Artefakt için başlangıç sayfa numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa, 1 olarak ayarlanır.

**Returns:**
int değer

### getSubset {#getSubset--}
```
public final int getSubset()
```

Artefaktın uygulanacağı sayfa alt kümesini alır veya ayarlar (ör. tüm sayfalar, çift sayfalar, tek sayfalar).

**Returns:**
int değer

### setEndPage {#setEndPage-int-}
```
public final void setEndPage(int value)
```

Artefakt için son sayfa numarasını alır veya ayarlar. Değer 0'a eşit veya daha büyük olmalıdır. 0'dan küçük bir değer ayarlanırsa, 0 olarak ayarlanır. Varsayılan 0 değeri, son sayfa sınırının olmadığını gösterir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setStartPage {#setStartPage-int-}
```
public final void setStartPage(int value)
```

Artefakt için başlangıç sayfa numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa, 1 olarak ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setSubset {#setSubset-int-}
```
public final void setSubset(int value)
```

Artefaktın uygulanacağı sayfa alt kümesini alır veya ayarlar (ör. tüm sayfalar, çift sayfalar, tek sayfalar).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |
