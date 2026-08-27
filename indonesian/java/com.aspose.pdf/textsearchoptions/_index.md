---
title: "TextSearchOptions"
linktitle: "TextSearchOptions"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili opsi pencarian teks"
type: docs
weight: 5290
url: /id/java/com.aspose.pdf/textsearchoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TextOptions com.aspose.pdf.TextSearchOptions, com.aspose.pdf.TextOptions, com.aspose.pdf.TextSearchOptions

```
public final class TextSearchOptions extends TextOptions
```

Mewakili opsi pencarian teks

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TextSearchOptions](#TextSearchOptions-boolean-) | Menginisialisasi instance baru dari objek {@code TextSearchOptions}. Menentukan mode penggunaan ekspresi reguler. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-) | Menginisialisasi instance baru dari objek TextSearchOptions. Menentukan persegi panjang yang membatasi teks yang dicari. |
| [TextSearchOptions](#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-) | Menginisialisasi instance baru dari objek TextSearchOptions. Menentukan persegi panjang yang membatasi teks yang dicari dan mode penggunaan ekspresi reguler. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getExcludeRectangles](#getExcludeRectangles--) | Mendapatkan atau mengatur persegi panjang yang batasnya mengecualikan teks dari pencarian. |
| [getIgnoreResourceFontErrors](#getIgnoreResourceFontErrors--) | Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan tidak adanya font akan diabaikan oleh penyerap teks (fragmen). true - berarti bahwa kesalahan tidak adanya font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false (default) - kesalahan tidak adanya font akan menghentikan pemrosesan dengan melemparkan pengecualian. |
| [getLimitToPageBounds](#getLimitToPageBounds--) | Mendapatkan indikasi bahwa teks dicari dalam batas halaman. |
| [getLogTextExtractionErrors](#getLogTextExtractionErrors--) | Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen). true - berarti bahwa kesalahan ekstraksi teks (dekoding) akan dicatat. Ini dapat menurunkan kinerja. false (default) - tidak ada pencatatan kesalahan. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang yang membatasi teks yang dicari. Properti ini dapat digunakan jika diperlukan untuk membatasi ekstraksi teks atau wilayah penggantian teks. |
| [getSearchForTextRelatedGraphics](#getSearchForTextRelatedGraphics--) | Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks. true - pencarian grafik terkait teks akan dilakukan (nilai default). false - elemen grafis yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika ada masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan. |
| [getStoredGraphicElementsMaxCount](#getStoredGraphicElementsMaxCount--) | Mendapatkan nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada halaman untuk jumlah elemen yang ditentukan. Nilai default adalah 250. Atur nilai lebih kecil jika ada masalah kinerja, coba nilai lebih besar jika beberapa elemen grafis tidak ditemukan. |
| [getUseFontEngineEncoding](#getUseFontEngineEncoding--) | Mendapatkan indikasi bahwa teks akan dicari menggunakan enkoding mesin font. true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen). false - berarti enkoding font dokumen akan digunakan (nilai default). |
| [isDotallMode](#isDotallMode--) | <p> Dalam mode dotall, ekspresi <tt>.</tt> cocok dengan karakter apa pun, termasuk penanda akhir baris. Secara default ekspresi ini tidak cocok dengan penanda akhir baris. |
| [isIgnoreShadowText](#isIgnoreShadowText--) | Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian. true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan). false - berarti teks bayangan akan ditemukan bersama dengan teks normal (nilai default). |
| [isRegularExpressionUsed](#isRegularExpressionUsed--) | Menunjukkan bahwa ekspresi reguler digunakan atau tidak. |
| [isSearchInAnnotations](#isSearchInAnnotations--) | Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Anotasi. true - teks akan dicari dalam Anotasi. false - teks dalam Anotasi tidak akan diproses oleh TextFragmentAbsorber. |
| [setDotallMode](#setDotallMode-boolean-) | Mengaktifkan mode dotall. <p> Dalam mode dotall, ekspresi <tt>.</tt> cocok dengan karakter apa pun, termasuk penanda akhir baris. Secara default ekspresi ini tidak cocok dengan penanda akhir baris. |
| [setExcludeRectangles](#setExcludeRectangles-com.aspose.pdf.Rectangle:A-) | Mendapatkan atau mengatur persegi panjang yang batasnya mengecualikan teks dari pencarian. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan tidak adanya font akan diabaikan oleh penyerap teks (fragmen). true - berarti bahwa kesalahan tidak adanya font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false (default) - kesalahan tidak adanya font akan menghentikan pemrosesan dengan melemparkan pengecualian. |
| [setIgnoreShadowText](#setIgnoreShadowText-boolean-) | Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian. true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan). false - berarti teks bayangan akan ditemukan bersama dengan teks normal (nilai default). |
| [setLimitToPageBounds](#setLimitToPageBounds-boolean-) | Mengatur indikasi bahwa teks dicari dalam batas halaman. |
| [setLogTextExtractionErrors](#setLogTextExtractionErrors-boolean-) | Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen). true - berarti bahwa kesalahan ekstraksi teks (dekoding) akan dicatat. Ini dapat menurunkan kinerja. false (default) - tidak ada pencatatan kesalahan. |
| [setRectangle](#setRectangle-com.aspose.pdf.Rectangle-) | Mengatur persegi panjang yang membatasi teks yang dicari. Properti ini dapat digunakan jika diperlukan untuk membatasi ekstraksi teks atau wilayah penggantian teks. |
| [setRegularExpressionUsed](#setRegularExpressionUsed-boolean-) | Menunjukkan bahwa ekspresi reguler digunakan atau tidak. |
| [setSearchForTextRelatedGraphics](#setSearchForTextRelatedGraphics-boolean-) | Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks. true - pencarian grafik terkait teks akan dilakukan (nilai default). false - elemen grafis yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika ada masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan. |
| [setSearchInAnnotations](#setSearchInAnnotations-boolean-) | Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Anotasi. true - teks akan dicari dalam Anotasi. false - teks dalam Anotasi tidak akan diproses oleh TextFragmentAbsorber. |
| [setStoredGraphicElementsMaxCount](#setStoredGraphicElementsMaxCount-int-) | Mengatur nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada halaman untuk jumlah elemen yang ditentukan. Nilai default adalah 250. Atur nilai lebih kecil jika ada masalah kinerja, coba nilai lebih besar jika beberapa elemen grafis tidak ditemukan. |
| [setUseFontEngineEncoding](#setUseFontEngineEncoding-boolean-) | Mengatur indikasi bahwa teks akan dicari menggunakan enkoding mesin font. true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen). false - berarti enkoding font dokumen akan digunakan (nilai default). |

### TextSearchOptions {#TextSearchOptions-boolean-}
```
public TextSearchOptions(boolean isRegularExpressionUsed)
```

Menginisialisasi instance baru dari objek {@code TextSearchOptions}. Menentukan mode penggunaan ekspresi reguler.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| isRegularExpressionUsed |  | Nilai yang menunjukkan bahwa ekspresi reguler digunakan. |

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-}
Menginisialisasi instance baru dari objek TextSearchOptions. Menentukan persegi panjang yang membatasi teks yang dicari.

### TextSearchOptions {#TextSearchOptions-com.aspose.pdf.Rectangle-boolean-}
Menginisialisasi instance baru dari objek TextSearchOptions. Menentukan persegi panjang yang membatasi teks yang dicari dan mode penggunaan ekspresi reguler.

### getExcludeRectangles {#getExcludeRectangles--}
```
public final Rectangle [] getExcludeRectangles()
```

Mendapatkan atau mengatur persegi panjang yang batasnya mengecualikan teks dari pencarian.

**Returns:**
array dari instance Rectangle

### getIgnoreResourceFontErrors {#getIgnoreResourceFontErrors--}
```
public final boolean getIgnoreResourceFontErrors()
```

Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan tidak adanya font akan diabaikan oleh penyerap teks (fragmen). true - berarti bahwa kesalahan tidak adanya font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false (default) - kesalahan tidak adanya font akan menghentikan pemrosesan dengan melemparkan pengecualian.

**Returns:**
nilai boolean

### getLimitToPageBounds {#getLimitToPageBounds--}
```
public boolean getLimitToPageBounds()
```

Mendapatkan indikasi bahwa teks dicari dalam batas halaman.

**Returns:**
nilai boolean

### getLogTextExtractionErrors {#getLogTextExtractionErrors--}
```
public boolean getLogTextExtractionErrors()
```

Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen). true - berarti bahwa kesalahan ekstraksi teks (dekoding) akan dicatat. Ini dapat menurunkan kinerja. false (default) - tidak ada pencatatan kesalahan.

**Returns:**
nilai boolean

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang yang membatasi teks yang dicari. Properti ini dapat digunakan jika diperlukan untuk membatasi ekstraksi teks atau wilayah penggantian teks.

**Returns:**
Nilai persegi panjang

### getSearchForTextRelatedGraphics {#getSearchForTextRelatedGraphics--}
```
public final boolean getSearchForTextRelatedGraphics()
```

Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks. true - pencarian grafik terkait teks akan dilakukan (nilai default). false - elemen grafis yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika ada masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan.

**Returns:**
nilai boolean

### getStoredGraphicElementsMaxCount {#getStoredGraphicElementsMaxCount--}
```
public final int getStoredGraphicElementsMaxCount()
```

Mendapatkan nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada halaman untuk jumlah elemen yang ditentukan. Nilai default adalah 250. Atur nilai lebih kecil jika ada masalah kinerja, coba nilai lebih besar jika beberapa elemen grafis tidak ditemukan.

**Returns:**
nilai int

### getUseFontEngineEncoding {#getUseFontEngineEncoding--}
```
public boolean getUseFontEngineEncoding()
```

Mendapatkan indikasi bahwa teks akan dicari menggunakan enkoding mesin font. true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen). false - berarti enkoding font dokumen akan digunakan (nilai default).

**Returns:**
nilai boolean

### isDotallMode {#isDotallMode--}
```
public static boolean isDotallMode()
```

<p> Dalam mode dotall, ekspresi <tt>.</tt> cocok dengan karakter apa pun, termasuk penanda akhir baris. Secara default ekspresi ini tidak cocok dengan penanda akhir baris.

**Returns:**
nilai boolean

### isIgnoreShadowText {#isIgnoreShadowText--}
```
public boolean isIgnoreShadowText()
```

Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian. true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan). false - berarti teks bayangan akan ditemukan bersama dengan teks normal (nilai default).

**Returns:**
nilai boolean

### isRegularExpressionUsed {#isRegularExpressionUsed--}
```
public boolean isRegularExpressionUsed()
```

Menunjukkan bahwa ekspresi reguler digunakan atau tidak.

**Returns:**
nilai boolean

### isSearchInAnnotations {#isSearchInAnnotations--}
```
public final boolean isSearchInAnnotations()
```

Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Anotasi. true - teks akan dicari dalam Anotasi. false - teks dalam Anotasi tidak akan diproses oleh TextFragmentAbsorber.

**Returns:**
nilai boolean

### setDotallMode {#setDotallMode-boolean-}
```
public static void setDotallMode(boolean dotallMode)
```

Mengaktifkan mode dotall. <p> Dalam mode dotall, ekspresi <tt>.</tt> cocok dengan karakter apa pun, termasuk penanda akhir baris. Secara default ekspresi ini tidak cocok dengan penanda akhir baris.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dotallMode |  | nilai boolean |

### setExcludeRectangles {#setExcludeRectangles-com.aspose.pdf.Rectangle:A-}
Mendapatkan atau mengatur persegi panjang yang batasnya mengecualikan teks dari pencarian.

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Mendapatkan atau mengatur indikasi bahwa kesalahan yang terkait dengan tidak adanya font akan diabaikan oleh penyerap teks (fragmen). true - berarti bahwa kesalahan tidak adanya font akan diabaikan. Segmen teks yang merujuk ke sumber yang tidak tepat akan dilewati selama pemrosesan. false (default) - kesalahan tidak adanya font akan menghentikan pemrosesan dengan melemparkan pengecualian.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setIgnoreShadowText {#setIgnoreShadowText-boolean-}
```
public void setIgnoreShadowText(boolean value)
```

Mendapatkan atau mengatur indikasi bahwa fragmen teks yang mewakili bayangan teks normal akan diabaikan selama pencarian. true - berarti teks bayangan tidak akan ditemukan (coba ini jika pencarian teks mengembalikan fragmen duplikat pada posisi yang berdekatan). false - berarti teks bayangan akan ditemukan bersama dengan teks normal (nilai default).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLimitToPageBounds {#setLimitToPageBounds-boolean-}
```
public void setLimitToPageBounds(boolean value)
```

Mengatur indikasi bahwa teks dicari dalam batas halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLogTextExtractionErrors {#setLogTextExtractionErrors-boolean-}
```
public void setLogTextExtractionErrors(boolean value)
```

Mendapatkan atau mengatur indikasi bahwa kesalahan ekstraksi teks (dekoding) akan dicatat dalam penyerap teks (fragmen). true - berarti bahwa kesalahan ekstraksi teks (dekoding) akan dicatat. Ini dapat menurunkan kinerja. false (default) - tidak ada pencatatan kesalahan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRectangle {#setRectangle-com.aspose.pdf.Rectangle-}
Mengatur persegi panjang yang membatasi teks yang dicari. Properti ini dapat digunakan jika diperlukan untuk membatasi ekstraksi teks atau wilayah penggantian teks.

### setRegularExpressionUsed {#setRegularExpressionUsed-boolean-}
```
public void setRegularExpressionUsed(boolean value)
```

Menunjukkan bahwa ekspresi reguler digunakan atau tidak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSearchForTextRelatedGraphics {#setSearchForTextRelatedGraphics-boolean-}
```
public final void setSearchForTextRelatedGraphics(boolean value)
```

Mendapatkan atau mengatur nilai yang memungkinkan pencarian grafik terkait teks (garis bawah, latar belakang, dll.) selama pencarian teks. true - pencarian grafik terkait teks akan dilakukan (nilai default). false - elemen grafis yang mungkin ada dalam dokumen sumber akan diabaikan. Atur ini jika ada masalah kinerja atau tidak perlu menangani garis bawah, latar belakang, atau pemotongan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSearchInAnnotations {#setSearchInAnnotations-boolean-}
```
public final void setSearchInAnnotations(boolean value)
```

Mendapatkan atau mengatur nilai yang memungkinkan pencarian teks dalam Anotasi. true - teks akan dicari dalam Anotasi. false - teks dalam Anotasi tidak akan diproses oleh TextFragmentAbsorber.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setStoredGraphicElementsMaxCount {#setStoredGraphicElementsMaxCount-int-}
```
public final void setStoredGraphicElementsMaxCount(int value)
```

Mengatur nilai yang membatasi pencarian grafik terkait teks (garis bawah, latar belakang, dll.) pada halaman untuk jumlah elemen yang ditentukan. Nilai default adalah 250. Atur nilai lebih kecil jika ada masalah kinerja, coba nilai lebih besar jika beberapa elemen grafis tidak ditemukan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setUseFontEngineEncoding {#setUseFontEngineEncoding-boolean-}
```
public void setUseFontEngineEncoding(boolean value)
```

Mengatur indikasi bahwa teks akan dicari menggunakan enkoding mesin font. true - berarti enkoding mesin font akan digunakan (coba ini jika pencarian teks gagal karena enkoding yang tidak sempurna dalam dokumen). false - berarti enkoding font dokumen akan digunakan (nilai default).

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |
