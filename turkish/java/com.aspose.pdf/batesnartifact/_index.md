---
title: "BatesNArtifact"
linktitle: "BatesNArtifact"
second_title: "Aspose.PDF for Java API Referansı"
description: "Sınıf, Bates Numaralandırma eserini tanımlar."
type: docs
weight: 290
url: /tr/java/com.aspose.pdf/batesnartifact/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Artifact com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.Artifact, com.aspose.pdf.PaginationArtifact com.aspose.pdf.BatesNArtifact, com.aspose.pdf.PaginationArtifact, com.aspose.pdf.BatesNArtifact

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public class BatesNArtifact extends PaginationArtifact
```

Sınıf, Bates Numaralandırma eserini tanımlar.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BatesNArtifact](#BatesNArtifact--) | Yeni bir {@link BatesNArtifact} sınıfı örneği başlatır. Bu yapıcı dahili olup, varsayılan değerlerle bir başlık artefakt örneği oluşturur. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumberOfDigits](#getNumberOfDigits--) | Bates numaralandırması için basamak sayısını alır veya ayarlar. Değer 3 ile 15 arasında (her iki uç dahil) olmalıdır. 3'ten küçük bir değer ayarlanırsa 3'e, 15'ten büyük bir değer ayarlanırsa 15'e ayarlanır. Varsayılan değer 6'dır. |
| [getPrefix](#getPrefix--) | Bates numarasına eklenecek ön eki alır veya ayarlar. |
| [getStartNumber](#getStartNumber--) | Bates numaralandırması için başlangıç numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa 1'e ayarlanır. |
| [getSuffix](#getSuffix--) | Bates numarasına eklenecek son eki alır veya ayarlar. |
| [setNumberOfDigits](#setNumberOfDigits-int-) | Bates numaralandırması için basamak sayısını alır veya ayarlar. Değer 3 ile 15 arasında (her iki uç dahil) olmalıdır. 3'ten küçük bir değer ayarlanırsa 3'e, 15'ten büyük bir değer ayarlanırsa 15'e ayarlanır. Varsayılan değer 6'dır. |
| [setPrefix](#setPrefix-java.lang.String-) | Bates numarasına eklenecek ön eki alır veya ayarlar. |
| [setStartNumber](#setStartNumber-int-) | Bates numaralandırması için başlangıç numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa 1'e ayarlanır. |
| [setSuffix](#setSuffix-java.lang.String-) | Bates numarasına eklenecek son eki alır veya ayarlar. |

### BatesNArtifact {#BatesNArtifact--}
```
public BatesNArtifact()
```

Yeni bir {@link BatesNArtifact} sınıfı örneği başlatır. Bu yapıcı dahili olup, varsayılan değerlerle bir başlık artefakt örneği oluşturur.

### getNumberOfDigits {#getNumberOfDigits--}
```
public final int getNumberOfDigits()
```

Bates numaralandırması için basamak sayısını alır veya ayarlar. Değer 3 ile 15 arasında (her iki uç dahil) olmalıdır. 3'ten küçük bir değer ayarlanırsa 3'e, 15'ten büyük bir değer ayarlanırsa 15'e ayarlanır. Varsayılan değer 6'dır.

**Returns:**
int değer

### getPrefix {#getPrefix--}
```
public final String getPrefix()
```

Bates numarasına eklenecek ön eki alır veya ayarlar.

**Returns:**
String değeri

### getStartNumber {#getStartNumber--}
```
public final int getStartNumber()
```

Bates numaralandırması için başlangıç numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa 1'e ayarlanır.

**Returns:**
int değer

### getSuffix {#getSuffix--}
```
public final String getSuffix()
```

Bates numarasına eklenecek son eki alır veya ayarlar.

**Returns:**
String değeri

### setNumberOfDigits {#setNumberOfDigits-int-}
```
public final void setNumberOfDigits(int value)
```

Bates numaralandırması için basamak sayısını alır veya ayarlar. Değer 3 ile 15 arasında (her iki uç dahil) olmalıdır. 3'ten küçük bir değer ayarlanırsa 3'e, 15'ten büyük bir değer ayarlanırsa 15'e ayarlanır. Varsayılan değer 6'dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setPrefix {#setPrefix-java.lang.String-}
Bates numarasına eklenecek ön eki alır veya ayarlar.

### setStartNumber {#setStartNumber-int-}
```
public final void setStartNumber(int value)
```

Bates numaralandırması için başlangıç numarasını alır veya ayarlar. Değer 1'e eşit veya daha büyük olmalıdır. 1'den küçük bir değer ayarlanırsa 1'e ayarlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer |  | int değer |

### setSuffix {#setSuffix-java.lang.String-}
Bates numarasına eklenecek son eki alır veya ayarlar.
