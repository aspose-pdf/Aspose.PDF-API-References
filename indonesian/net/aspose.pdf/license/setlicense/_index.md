---
title: "License.SetLicense"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode License. Memberi lisensi pada komponen"
type: docs
weight: 40
url: /id/net/aspose.pdf/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Melisensikan komponen.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| licenseName | String | Dapat berupa nama file lengkap atau pendek atau nama sumber daya tersemat. Gunakan string kosong untuk beralih ke mode evaluasi. |

## Catatan

Mencoba menemukan lisensi di lokasi berikut:

1. Jalur eksplisit.

2. Folder yang berisi assembly komponen Aspose.

3. Folder yang berisi assembly pemanggil klien.

4. Folder yang berisi assembly entri (startup).

5. Sumber daya tersemat di assembly pemanggil klien.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Jalur eksplisit.

2. Sumber daya tersemat di assembly pemanggil klien.

[Java]

2. Folder yang berisi file JAR komponen Aspose.

3. Folder yang berisi file JAR pemanggil klien.

### Lihat Juga

* class [License](../)
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
| stream | Stream | Aliran yang berisi lisensi. |

## Catatan

Gunakan metode ini untuk memuat lisensi dari aliran.

### Lihat Juga

* class [License](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


