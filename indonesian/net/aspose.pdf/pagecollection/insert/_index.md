---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Metode PageCollection. Menyisipkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.
type: docs
weight: 160
url: /id/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Menyisipkan halaman kosong ke dalam koleksi pada posisi yang ditentukan. Jika dokumen sudah berisi halaman dengan ukuran yang bervariasi, ukuran halaman yang paling sering muncul akan dipilih. Jika hanya ada dua halaman yang berbeda, ukuran halaman pertama akan digunakan.

```csharp
public Page Insert(int pageNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Posisi halaman baru. |

### Nilai Kembali

Halaman yang disisipkan.

### Lihat Juga

* kelas [Page](../../page/)
* kelas [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Menyisipkan halaman ke dalam koleksi halaman di tempat yang ditentukan.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber | Int32 | Indeks halaman yang diperlukan dalam koleksi. |
| entity | Page | Halaman yang akan disisipkan. |

### Nilai Kembali

Halaman yang disisipkan.

### Lihat Juga

* kelas [Page](../../page/)
* kelas [PageCollection](../)
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
| pageNumber | Int32 | Posisi awal halaman baru. |
| pages | ICollection`1 | Koleksi halaman. |

### Lihat Juga

* kelas [Page](../../page/)
* kelas [PageCollection](../)
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
| pageNumber | Int32 | Nomor awal halaman baru. |
| pages | Page[] | Array halaman yang akan disisipkan. |

### Lihat Juga

* kelas [Page](../../page/)
* kelas [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)