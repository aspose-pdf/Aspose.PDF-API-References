---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Aspose.PDF for Java API Referansı"
description: "BoundsCheckableList'i temsil eder - System.Collections.Generic.List etrafında bir sarmalayıcı."
type: docs
weight: 10
url: /tr/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

BoundsCheckableList'i temsil eder - System.Collections.Generic.List etrafında bir sarmalayıcı.

## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | BoundsCheckableList sınıfının yeni bir örneğini başlatır. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | BoundsCheckableList sınıfının yeni bir örneğini başlatır. |

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addItem](#addItem-T-) | \"boundsCheckMode\" parametresine bağlı olarak bir nesneyi System.Collections.Generic.List'in sonuna ekler. |
| [clear](#clear--) | System.Collections.Generic.List'ten tüm öğeleri kaldırır. |
| [containsItem](#containsItem-T-) | Bir öğenin System.Collections.Generic.List içinde olup olmadığını belirler. |
| [copyToTArray](#copyToTArray-T:A-int-) | Tüm System.Collections.Generic.List'i hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar. |
| [get_Item](#get_Item-int-) | Paragrafı koleksiyondan alır veya koleksiyona ayarlar. |
| [indexOfItem](#indexOfItem-T-) | Belirtilen nesneyi arar ve tüm System.Collections.Generic.List içinde ilk oluşumun sıfır tabanlı indeksini döndürür. |
| [insertItem](#insertItem-int-T-) | Belirtilen indekste bir öğeyi System.Collections.Generic.List'e ekler. |
| [isReadOnly](#isReadOnly--) | Koleksiyonun yalnızca okunur olup olmadığını gösteren değeri alır. |
| [iterator](#iterator--) | System.Collections.Generic.List üzerinde yineleme yapan bir enumerator döndürür. |
| [removeAt](#removeAt-int-) | System.Collections.Generic.List'in belirtilen dizindeki öğeyi kaldırır. |
| [removeItem](#removeItem-T-) | System.Collections.Generic.List'ten belirli bir nesnenin ilk oluşumunu kaldırır. |
| [set_Item](#set_Item-int-T-) | Paragrafı koleksiyondan alır veya koleksiyona ayarlar. |
| [size](#size--) | System.Collections.Generic.List içinde bulunan öğe sayısını alır. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Başlatılmış koleksiyon için boundsCheckMode parametresini günceller. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Başlatılmış koleksiyon için boundsCheckMode parametresini günceller. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

BoundsCheckableList sınıfının yeni bir örneğini başlatır.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

BoundsCheckableList sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boundsCheckMode |  | Sınır cCheck modu. |
| containerWidth |  | Konteyner genişliği. |
| containerHeight |  | Konteyner yüksekliği. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

\"boundsCheckMode\" parametresine bağlı olarak bir nesneyi System.Collections.Generic.List'in sonuna ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item |  | System.Collections.Generic.List'in sonuna eklenecek nesne. Referans tipleri için değer "null" olabilir. |

### clear {#clear--}
```
public final void clear()
```

System.Collections.Generic.List'ten tüm öğeleri kaldırır.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Bir öğenin System.Collections.Generic.List içinde olup olmadığını belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item |  | System.Collections.Generic.List içinde bulunacak nesne. Referans tipleri için değer null olabilir. |

**Returns:**
System.Collections.Generic.List içinde itemitem bulunursa true; aksi takdirde false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Tüm System.Collections.Generic.List'i hedef dizinin belirtilen indeksinden başlayarak uyumlu tek boyutlu bir diziye kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array |  | System.Collections.Generic.List'ten kopyalanan öğelerin hedefi olan tek boyutlu System.Array. System.Array sıfır tabanlı indekslemeye sahip olmalıdır. |
| arrayIndex |  | Kopyalamanın başladığı array içindeki sıfır tabanlı indeks. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Paragrafı koleksiyondan alır veya koleksiyona ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Paragraf indeksi. |

**Returns:**
belirtilen dizindeki öğe.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Belirtilen nesneyi arar ve tüm System.Collections.Generic.List içinde ilk oluşumun sıfır tabanlı indeksini döndürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item |  | System.Collections.Generic.List içinde bulunacak nesne. Referans tipleri için değer null olabilir. |

**Returns:**
Bulunursa, System.Collections.Generic.List içinde itemitem'in ilk oluşumunun sıfır tabanlı indeksi; aksi takdirde –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Belirtilen indekste bir öğeyi System.Collections.Generic.List'e ekler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Item'in eklenmesi gereken sıfır tabanlı indeks. |
| item |  | Eklenecek nesne. Değer, referans tipleri için null olabilir. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Koleksiyonun yalnızca okunur olup olmadığını gösteren değeri alır.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

System.Collections.Generic.List üzerinde yineleme yapan bir enumerator döndürür.

**Returns:**
System.Collections.Generic.List için bir Enumerator.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

System.Collections.Generic.List'in belirtilen dizindeki öğeyi kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Kaldırılacak öğenin sıfır tabanlı indeksi. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

System.Collections.Generic.List'ten belirli bir nesnenin ilk oluşumunu kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item |  | System.Collections.Generic.List'ten kaldırılacak nesne. Değer, referans tipleri için null olabilir. |

**Returns:**
itemitem başarıyla kaldırıldıysa true; aksi takdirde false. Bu yöntem, itemitem System.Collections.Generic.List içinde bulunamazsa da false döndürür.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Paragrafı koleksiyondan alır veya koleksiyona ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index |  | Paragraf indeksi. |

### size {#size--}
```
public final int size()
```

System.Collections.Generic.List içinde bulunan öğe sayısını alır.

**Returns:**
System.Collections.Generic.List içinde bulunan öğe sayısı.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Başlatılmış koleksiyon için boundsCheckMode parametresini günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boundsCheckMode |  | Sınır kontrol modu. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Başlatılmış koleksiyon için boundsCheckMode parametresini günceller.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| boundsCheckMode |  | Sınır kontrol modu. |
| containerWidth |  | Konteyner genişliği. |
| containerHeight |  | Konteyner yüksekliği. |
