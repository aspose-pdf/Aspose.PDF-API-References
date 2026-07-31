---
title: "PageCollection.Insert"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode PageCollection. Menyisipkan Page kosong ke dalam koleksi pada posisi yang ditentukan. Jika Document sudah berisi pages dengan ukuran yang bervariasi, ukuran page yang paling sering muncul akan dipilih. Jika hanya ada dua pages yang berbeda, ukuran page pertama akan digunakan."
type: docs
weight: 160
url: /id/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Masukkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang berbeda-beda, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Posisi Page baru. |

### Nilai Kembalian

Page yang disisipkan.

### Lihat Juga

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Menyisipkan halaman ke dalam koleksi halaman pada tempat yang ditentukan.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Indeks page yang diperlukan dalam koleksi. |
| entitas | Halaman | Page yang akan disisipkan. |

### Nilai Kembalian

Page yang disisipkan.

### Lihat Juga

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Menyisipkan halaman dari koleksi ke dalam dokumen.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Posisi awal pages baru. |
| halaman | ICollection`1 | Koleksi Pages. |

### Lihat Juga

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Menyisipkan halaman dari array ke dalam dokumen.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Jumlah awal pages baru. |
| halaman | Page[] | Array pages yang akan disisipkan. |

### Lihat Juga

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


