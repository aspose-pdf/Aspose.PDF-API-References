---
title: "ToUnicodeProcessingRules"
linktitle: "ToUnicodeProcessingRules"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight \\\"Text cannot be mapped to Unicode\\\"."
type: docs
weight: 5380
url: /id/java/com.aspose.pdf/tounicodeprocessingrules/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ToUnicodeProcessingRules

```
public class ToUnicodeProcessingRules extends Object
```

Kelas ini menjelaskan aturan yang dapat digunakan untuk menyelesaikan kesalahan Adobe Preflight "Text cannot be mapped to Unicode".

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules--) | Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules}. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-) | Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules} dengan opsi yang ditentukan untuk menghapus spasi dari nama CMap. |
| [ToUnicodeProcessingRules](#ToUnicodeProcessingRules-boolean-boolean-) | Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules} dengan opsi yang ditentukan. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getMapNonLinkedSymbolsOnSpace](#getMapNonLinkedSymbolsOnSpace--) | Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Text cannot be mapped to Unicode". Gunakan flag ini untuk memetakan simbol yang tidak terhubung ke unicode "space" (kode 32). |
| [getRemoveSpacesFromCMapNames](#getRemoveSpacesFromCMapNames--) | Beberapa font memiliki peta kode karakter ToUnicode dengan spasi di nama. Spasi ini dapat menyebabkan kesalahan pada pemetaan teks unicode. Flag ini menginstruksikan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Secara default false. |
| [setMapNonLinkedSymbolsOnSpace](#setMapNonLinkedSymbolsOnSpace-boolean-) | Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Text cannot be mapped to Unicode". Gunakan flag ini untuk memetakan simbol yang tidak terhubung ke unicode "space" (kode 32). |
| [setRemoveSpacesFromCMapNames](#setRemoveSpacesFromCMapNames-boolean-) | Beberapa font memiliki peta kode karakter ToUnicode dengan spasi di nama. Spasi ini dapat menyebabkan kesalahan pada pemetaan teks unicode. Flag ini menginstruksikan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Secara default false. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules--}
```
public ToUnicodeProcessingRules()
```

Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules}.

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces)
```

Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules} dengan opsi yang ditentukan untuk menghapus spasi dari nama CMap.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeSpaces |  | Nilai boolean yang menunjukkan apakah spasi harus dihapus dari nama CMap. |

### ToUnicodeProcessingRules {#ToUnicodeProcessingRules-boolean-boolean-}
```
public ToUnicodeProcessingRules(boolean removeSpaces, boolean mapNonLinkedUnicodesOnSpace)
```

Menginisialisasi sebuah instance baru dari kelas {@link ToUnicodeProcessingRules} dengan opsi yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| removeSpaces |  | Menunjukkan apakah spasi harus dihapus dari nama CMap. |
| mapNonLinkedUnicodesOnSpace |  | Menunjukkan apakah simbol Unicode yang tidak terhubung harus dipetakan ke spasi. |

### getMapNonLinkedSymbolsOnSpace {#getMapNonLinkedSymbolsOnSpace--}
```
public boolean getMapNonLinkedSymbolsOnSpace()
```

Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Text cannot be mapped to Unicode". Gunakan flag ini untuk memetakan simbol yang tidak terhubung ke unicode "space" (kode 32).

**Returns:**
nilai boolean

### getRemoveSpacesFromCMapNames {#getRemoveSpacesFromCMapNames--}
```
public boolean getRemoveSpacesFromCMapNames()
```

Beberapa font memiliki peta kode karakter ToUnicode dengan spasi di nama. Spasi ini dapat menyebabkan kesalahan pada pemetaan teks unicode. Flag ini menginstruksikan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Secara default false.

**Returns:**
nilai boolean

### setMapNonLinkedSymbolsOnSpace {#setMapNonLinkedSymbolsOnSpace-boolean-}
```
public void setMapNonLinkedSymbolsOnSpace(boolean value)
```

Beberapa font tidak menyediakan informasi tentang unicode untuk beberapa simbol teks. Kekurangan informasi ini menyebabkan kesalahan "Text cannot be mapped to Unicode". Gunakan flag ini untuk memetakan simbol yang tidak terhubung ke unicode "space" (kode 32).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRemoveSpacesFromCMapNames {#setRemoveSpacesFromCMapNames-boolean-}
```
public void setRemoveSpacesFromCMapNames(boolean value)
```

Beberapa font memiliki peta kode karakter ToUnicode dengan spasi di nama. Spasi ini dapat menyebabkan kesalahan pada pemetaan teks unicode. Flag ini menginstruksikan untuk menghapus spasi dari nama peta kode karakter ToUnicode. Secara default false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
