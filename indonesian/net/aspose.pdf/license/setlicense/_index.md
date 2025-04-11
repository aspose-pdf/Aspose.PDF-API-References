---
title: License.SetLicense
second_title: Aspose.PDF for .NET API Reference
description: Metode lisensi. Melisensikan komponen
type: docs
weight: 20
url: /id/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Melisensikan komponen.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | String | Dapat berupa nama file lengkap atau pendek atau nama sumber daya yang disematkan. Gunakan string kosong untuk beralih ke mode evaluasi. |

## Keterangan

Mencoba untuk menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi assembly komponen Aspose.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entri (startup).

5. Sumber daya yang disematkan dalam assembly pemanggil klien.

**Catatan:** Pada .NET Compact Framework, mencoba untuk menemukan lisensi hanya di lokasi-lokasi ini:

1. Jalur eksplisit.

2. Sumber daya yang disematkan dalam assembly pemanggil klien.

[Java]

2. Folder yang berisi file JAR komponen Aspose.

3. Folder yang berisi file JAR pemanggil klien.

### Lihat Juga

* kelas [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## SetLicense(Stream) {#setlicense}

Melisensikan komponen.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | Stream | Sebuah stream yang berisi lisensi. |

## Keterangan

Gunakan metode ini untuk memuat lisensi dari sebuah stream.

### Lihat Juga

* kelas [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)