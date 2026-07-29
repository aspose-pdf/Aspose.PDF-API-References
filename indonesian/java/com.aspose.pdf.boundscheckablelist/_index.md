---
title: "com.aspose.pdf.boundscheckablelist"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili BoundsCheckableList - pembungkus di sekitar System.Collections.Generic.List."
type: docs
weight: 10
url: /id/java/com.aspose.pdf.boundscheckablelist/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.boundscheckablelist.BoundsCheckableList<T>

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericCollection<T>, com.aspose.ms.System.Collections.Generic.IGenericEnumerable<T>, com.aspose.ms.System.Collections.Generic.IGenericList<T>, com.aspose.ms.System.Collections.IEnumerable<T>, Iterable <T>

```
public class BoundsCheckableList<T extends IBoundsCheckableItem > extends Object implements com.aspose.ms.System.Collections.Generic.IGenericList<T>
```

Mewakili BoundsCheckableList - pembungkus di sekitar System.Collections.Generic.List.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [BoundsCheckableList](#BoundsCheckableList--) | Menginisialisasi instance baru dari kelas BoundsCheckableList. |
| [BoundsCheckableList](#BoundsCheckableList-int-double-double-) | Menginisialisasi instance baru dari kelas BoundsCheckableList. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [addItem](#addItem-T-) | Menambahkan objek ke akhir System.Collections.Generic.List tergantung pada parameter \"boundsCheckMode\". |
| [clear](#clear--) | Menghapus semua elemen dari System.Collections.Generic.List. |
| [containsItem](#containsItem-T-) | Menentukan apakah sebuah elemen berada di System.Collections.Generic.List. |
| [copyToTArray](#copyToTArray-T:A-int-) | Menyalin seluruh System.Collections.Generic.List ke array satu dimensi yang kompatibel, mulai pada indeks yang ditentukan dari array target. |
| [get_Item](#get_Item-int-) | Mendapatkan atau mengatur paragraf dari atau ke koleksi. |
| [indexOfItem](#indexOfItem-T-) | Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama di seluruh System.Collections.Generic.List. |
| [insertItem](#insertItem-int-T-) | Menyisipkan elemen ke dalam System.Collections.Generic.List pada indeks yang ditentukan. |
| [isReadOnly](#isReadOnly--) | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. |
| [iterator](#iterator--) | Mengembalikan enumerator yang mengiterasi melalui System.Collections.Generic.List. |
| [removeAt](#removeAt-int-) | Menghapus elemen pada indeks yang ditentukan dari System.Collections.Generic.List. |
| [removeItem](#removeItem-T-) | Menghapus kemunculan pertama dari objek tertentu dari System.Collections.Generic.List. |
| [set_Item](#set_Item-int-T-) | Mendapatkan atau mengatur paragraf dari atau ke koleksi. |
| [size](#size--) | Mendapatkan jumlah elemen yang terdapat dalam System.Collections.Generic.List. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-) | Memperbarui parameter boundsCheckMode untuk koleksi yang diinisialisasi. |
| [updateBoundsCheckMode](#updateBoundsCheckMode-int-double-double-) | Memperbarui parameter boundsCheckMode untuk koleksi yang diinisialisasi. |

### BoundsCheckableList {#BoundsCheckableList--}
```
public BoundsCheckableList()
```

Menginisialisasi instance baru dari kelas BoundsCheckableList.

### BoundsCheckableList {#BoundsCheckableList-int-double-double-}
```
public BoundsCheckableList(int boundsCheckMode, double containerWidth, double containerHeight)
```

Menginisialisasi instance baru dari kelas BoundsCheckableList.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| boundsCheckMode |  | Mode bounds cCheck. |
| containerWidth |  | Lebar kontainer. |
| containerHeight |  | Tinggi kontainer. |

### addItem {#addItem-T-}
```
public final void addItem( T item)
```

Menambahkan objek ke akhir System.Collections.Generic.List tergantung pada parameter \"boundsCheckMode\".

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item |  | Objek yang akan ditambahkan ke akhir System.Collections.Generic.List. Nilainya dapat berupa "null" untuk tipe referensi. |

### clear {#clear--}
```
public final void clear()
```

Menghapus semua elemen dari System.Collections.Generic.List.

### containsItem {#containsItem-T-}
```
public final boolean containsItem( T item)
```

Menentukan apakah sebuah elemen berada di System.Collections.Generic.List.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item |  | Objek yang akan dicari dalam System.Collections.Generic.List. Nilainya dapat berupa null untuk tipe referensi. |

**Returns:**
true jika itemitem ditemukan dalam System.Collections.Generic.List; jika tidak, false.

### copyToTArray {#copyToTArray-T:A-int-}
```
public final void copyToTArray( T [] array, int arrayIndex)
```

Menyalin seluruh System.Collections.Generic.List ke array satu dimensi yang kompatibel, mulai pada indeks yang ditentukan dari array target.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array |  | System.Array satu dimensi yang menjadi tujuan elemen yang disalin dari System.Collections.Generic.List. System.Array harus memiliki indeks berbasis nol. |
| arrayIndex |  | Indeks berbasis nol dalam array tempat penyalinan dimulai. |

### get_Item {#get_Item-int-}
```
public final T get_Item(int index)
```

Mendapatkan atau mengatur paragraf dari atau ke koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks paragraf. |

**Returns:**
elemen pada indeks yang ditentukan.

### indexOfItem {#indexOfItem-T-}
```
public final int indexOfItem( T item)
```

Mencari objek yang ditentukan dan mengembalikan indeks berbasis nol dari kemunculan pertama di seluruh System.Collections.Generic.List.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item |  | Objek yang akan dicari dalam System.Collections.Generic.List. Nilainya dapat berupa null untuk tipe referensi. |

**Returns:**
Indeks berbasis nol dari kemunculan pertama itemitem dalam seluruh System.Collections.Generic.List, jika ditemukan; jika tidak, –1.

### insertItem {#insertItem-int-T-}
```
public final void insertItem(int index, T item)
```

Menyisipkan elemen ke dalam System.Collections.Generic.List pada indeks yang ditentukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks berbasis nol tempat item harus disisipkan. |
| item |  | Objek yang akan dimasukkan. Nilainya dapat bernilai null untuk tipe referensi. |

### isReadOnly {#isReadOnly--}
```
public final boolean isReadOnly()
```

Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca.

### iterator {#iterator--}
```
public final com.aspose.ms.System.Collections.Generic.IGenericEnumerator< T > iterator()
```

Mengembalikan enumerator yang mengiterasi melalui System.Collections.Generic.List.

**Returns:**
Enumerator untuk System.Collections.Generic.List.

### removeAt {#removeAt-int-}
```
public final void removeAt(int index)
```

Menghapus elemen pada indeks yang ditentukan dari System.Collections.Generic.List.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks berbasis nol dari elemen yang akan dihapus. |

### removeItem {#removeItem-T-}
```
public final boolean removeItem( T item)
```

Menghapus kemunculan pertama dari objek tertentu dari System.Collections.Generic.List.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item |  | Objek yang akan dihapus dari System.Collections.Generic.List. Nilainya dapat bernilai null untuk tipe referensi. |

**Returns:**
true jika itemitem berhasil dihapus; jika tidak, false. Metode ini juga mengembalikan false jika itemitem tidak ditemukan dalam System.Collections.Generic.List.

### set_Item {#set_Item-int-T-}
```
public final void set_Item(int index, T value)
```

Mendapatkan atau mengatur paragraf dari atau ke koleksi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| indeks |  | Indeks paragraf. |

### size {#size--}
```
public final int size()
```

Mendapatkan jumlah elemen yang terdapat dalam System.Collections.Generic.List.

**Returns:**
Jumlah elemen yang terdapat dalam System.Collections.Generic.List.

### updateBoundsCheckMode {#updateBoundsCheckMode-int-}
```
public final void updateBoundsCheckMode(int boundsCheckMode)
```

Memperbarui parameter boundsCheckMode untuk koleksi yang diinisialisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| boundsCheckMode |  | Mode pemeriksaan batas. |

### updateBoundsCheckMode {#updateBoundsCheckMode-int-double-double-}
```
public final void updateBoundsCheckMode(int boundsCheckMode, double containerWidth, double containerHeight)
```

Memperbarui parameter boundsCheckMode untuk koleksi yang diinisialisasi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| boundsCheckMode |  | Mode pemeriksaan batas. |
| containerWidth |  | Lebar kontainer. |
| containerHeight |  | Tinggi kontainer. |
