---
title: "IChatCopilot.SaveResponseAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode IChatCopilot. Secara asinkron menyimpan respons untuk pesan yang diberikan ke file PDF."
type: docs
weight: 40
url: /id/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Menyimpan respons untuk pesan yang diberikan secara asinkron ke file PDF.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | String | Pesan input yang responsnya disimpan. |
| outputFileName | String | Nama file PDF output untuk menyimpan respons. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron.

### Lihat Juga

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Menyimpan respons untuk pesan yang diberikan secara asinkron ke file dengan format yang ditentukan.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | String | Pesan input yang responsnya disimpan. |
| outputFileName | String | Nama file output untuk menyimpan respons. |
| saveFormat | SaveFormat | Format untuk menyimpan respons (PDF jika tidak ditentukan). |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron.

### Lihat Juga

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Menyimpan respons untuk daftar pesan yang diberikan secara asinkron ke file PDF.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | List`1 | Daftar pesan input yang responsnya disimpan. |
| outputFileName | String | Nama file PDF output untuk menyimpan respons. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron.

### Lihat Juga

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Menyimpan respons untuk daftar pesan yang diberikan secara asinkron ke file dengan format yang ditentukan.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pesan | List`1 | Daftar pesan input yang responsnya disimpan. |
| outputFileName | String | Nama file output untuk menyimpan respons. |
| saveFormat | SaveFormat | Format untuk menyimpan respons (PDF jika tidak ditentukan). |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron.

### Lihat Juga

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


