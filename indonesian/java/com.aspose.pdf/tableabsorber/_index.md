---
title: "TableAbsorber"
linktitle: "TableAbsorber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi {@code TableAbsorber.TableList}. </p> <hr> <pre> The.</pre>"
type: docs
weight: 4800
url: /id/java/com.aspose.pdf/tableabsorber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.TableAbsorber

```
public class TableAbsorber extends Object
```

<p> Mewakili objek penyerap elemen tabel. Melakukan pencarian dan menyediakan akses ke hasil pencarian melalui koleksi {@code TableAbsorber.TableList}. </p> <hr> <pre> Contoh ini menunjukkan cara menemukan tabel pada halaman pertama dokumen PDF dan mengganti teks dalam sel tabel. // Buka dokumen Document doc = new Document("D:\\Tests\\input.pdf"); // Buat objek TableAbsorber untuk menemukan tabel TableAbsorber absorber = new TableAbsorber(); // Kunjungi halaman pertama dengan absorber absorber.visit(doc.getPages().get_Item(1)); // Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya TextFragment fragment = absorber.getTableList().get_Item(0).getRowList().get_Item(0).getCellList().get_Item(0) .getTextFragments().get_Item(1); // Ubah teks fragmen teks pertama dalam sel fragment.setText("hi world"); // Simpan dokumen doc.save("D:\\Tests\\output.pdf"); </pre>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [TableAbsorber](#TableAbsorber--) | <p> Menginisialisasi sebuah instance baru dari {@code TableAbsorber}. </p> <hr> Melakukan pencarian tabel dan menyediakan akses ke tabel melalui objek {@code TableList}. |
| [TableAbsorber](#TableAbsorber-com.aspose.pdf.TextSearchOptions-) | <p> Menginisialisasi sebuah instance baru dari {@code TableAbsorber}. </p> <hr> Melakukan pencarian tabel dan menyediakan akses ke tabel melalui objek {@code TableList}. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTableList](#getTableList--) | <p> Mengembalikan IList read‑only yang berisi tabel yang ditemukan </p> |
| [getTextSearchOptions](#getTextSearchOptions--) | <p> Mendapatkan opsi pencarian teks. </p> <hr> Memungkinkan mendefinisikan beberapa opsi yang akan digunakan selama pencarian teks dalam tabel. |
| [isUseFlowEngine](#isUseFlowEngine--) | Aktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas. |
| [remove](#remove-com.aspose.pdf.AbsorbedTable-) | <p> Menghapus {@code AbsorbedTable} dari halaman. </p> <hr> <p> Harap perhatikan bahwa ini mengubah koleksi TableList. Jika menghapus/mengganti tabel dalam loop, gunakan salinan koleksi TableList. </p> |
| [replace](#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-) | <p> Mengganti {@code AbsorbedTable} dengan {@code Table} pada halaman. </p> <hr> <p> Harap perhatikan bahwa ini mengubah koleksi TableList. Jika menghapus/mengganti tabel dalam loop, gunakan salinan koleksi TableList. </p> |
| [setTextSearchOptions](#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-) | <p> Mendapatkan atau mengatur opsi pencarian teks. </p> <hr> Memungkinkan mendefinisikan beberapa opsi yang akan digunakan selama pencarian teks dalam tabel. |
| [setUseFlowEngine](#setUseFlowEngine-boolean-) | Aktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas. |
| [visit](#visit-com.aspose.pdf.IDocument-) | <p> Mengekstrak tabel pada dokumen yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF. // Buka dokumen Document doc = new Document(@"D:\\Tests\\input.pdf"); // Buat objek TableAbsorber untuk menemukan tabel TableAbsorber absorber = new TableAbsorber(); // Kunjungi halaman pertama dengan absorber absorber.visit(pdfDocument); // Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Ubah teks fragmen teks pertama dalam sel fragment.setText ("hi world"); // Simpan dokumen doc.save(@"D:\\Tests\\output.pdf"); </pre> |
| [visit](#visit-com.aspose.pdf.Page-) | <p> Mengekstrak tabel pada halaman yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF. // Buka dokumen Document doc = new Document(@"D:\\Tests\\input.pdf"); // Buat objek TableAbsorber untuk menemukan tabel TableAbsorber absorber = new TableAbsorber(); // Kunjungi halaman pertama dengan absorber absorber.visit(doc.getPages.get_item(1)); // Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Ubah teks fragmen teks pertama dalam sel fragment.setText ("hi world"); // Simpan dokumen doc.save(@"D:\\Tests\\output.pdf"); </pre> |

### TableAbsorber {#TableAbsorber--}
```
public TableAbsorber()
```

<p> Menginisialisasi sebuah instance baru dari {@code TableAbsorber}. </p> <hr> Melakukan pencarian tabel dan menyediakan akses ke tabel melalui objek {@code TableList}.

### TableAbsorber {#TableAbsorber-com.aspose.pdf.TextSearchOptions-}
<p> Menginisialisasi sebuah instance baru dari {@code TableAbsorber}. </p> <hr> Melakukan pencarian tabel dan menyediakan akses ke tabel melalui objek {@code TableList}.

### getTableList {#getTableList--}
```
public List < AbsorbedTable > getTableList()
```

<p> Mengembalikan IList read‑only yang berisi tabel yang ditemukan </p>

**Returns:**
{@code IGenericList<AbsorbedTable> object}

### getTextSearchOptions {#getTextSearchOptions--}
```
public TextSearchOptions getTextSearchOptions()
```

<p> Mendapatkan opsi pencarian teks. </p> <hr> Memungkinkan mendefinisikan beberapa opsi yang akan digunakan selama pencarian teks dalam tabel.

**Returns:**
Objek TextSearchOptions

### isUseFlowEngine {#isUseFlowEngine--}
```
public boolean isUseFlowEngine()
```

Aktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas.

**Returns:**
nilai boolean

### remove {#remove-com.aspose.pdf.AbsorbedTable-}
<p> Menghapus {@code AbsorbedTable} dari halaman. </p> <hr> <p> Harap perhatikan bahwa ini mengubah koleksi TableList. Jika menghapus/mengganti tabel dalam loop, gunakan salinan koleksi TableList. </p>

### replace {#replace-com.aspose.pdf.Page-com.aspose.pdf.AbsorbedTable-com.aspose.pdf.Table-}
<p> Mengganti {@code AbsorbedTable} dengan {@code Table} pada halaman. </p> <hr> <p> Harap perhatikan bahwa ini mengubah koleksi TableList. Jika menghapus/mengganti tabel dalam loop, gunakan salinan koleksi TableList. </p>

### setTextSearchOptions {#setTextSearchOptions-com.aspose.pdf.TextSearchOptions-}
<p> Mendapatkan atau mengatur opsi pencarian teks. </p> <hr> Memungkinkan mendefinisikan beberapa opsi yang akan digunakan selama pencarian teks dalam tabel.

### setUseFlowEngine {#setUseFlowEngine-boolean-}
```
public void setUseFlowEngine(boolean useFlowEngine)
```

Aktifkan mesin pengenalan tabel alternatif yang lebih unggul dalam banyak skenario dan mampu mengenali tabel tanpa batas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| useFlowEngine |  | nilai boolean |

### visit {#visit-com.aspose.pdf.IDocument-}
<p> Mengekstrak tabel pada dokumen yang ditentukan. </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF. // Buka dokumen Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Buat objek TableAbsorber untuk menemukan tabel TableAbsorber absorber = new TableAbsorber(); // Kunjungi halaman pertama dengan absorber absorber.visit(pdfDocument); // Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Ubah teks fragmen teks pertama di sel fragment.setText (\"hi world\"); // Simpan dokumen doc.save(@\"D:\\Tests\\output.pdf\"); </pre>

### visit {#visit-com.aspose.pdf.Page-}
<p> Mengekstrak tabel pada halaman yang ditentukan </p> <hr> <pre> Contoh ini menunjukkan cara mengekstrak tabel pada halaman pertama dokumen PDF. // Buka dokumen Document doc = new Document(@\"D:\\Tests\\input.pdf\"); // Buat objek TableAbsorber untuk menemukan tabel TableAbsorber absorber = new TableAbsorber(); // Kunjungi halaman pertama dengan absorber absorber.visit(doc.getPages.get_item(1)); // Dapatkan akses ke tabel pertama pada halaman, sel pertama mereka, dan fragmen teks di dalamnya TextFragment fragment = absorber.getTableList().get_item(0).getRowList.get_item(0).getCellList().get_item(0) .getTextFragments.get_item(1); // Ubah teks fragmen teks pertama di sel fragment.setText (\"hi world\"); // Simpan dokumen doc.save(@\"D:\\Tests\\output.pdf\"); </pre>
