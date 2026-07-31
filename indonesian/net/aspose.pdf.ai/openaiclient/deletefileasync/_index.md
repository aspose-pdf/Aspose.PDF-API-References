---
title: "OpenAIClient.DeleteFileAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Menghapus file tertentu secara asinkron."
type: docs
weight: 140
url: /id/net/aspose.pdf.ai/openaiclient/deletefileasync/
---
## OpenAIClient.DeleteFileAsync method

Menghapus file tertentu secara asinkron.

```csharp
public Task<DeleteStatusResponse> DeleteFileAsync(string fileId, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fileId | String | ID file yang akan dihapus. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Tugas yang mewakili operasi asinkron. Hasil tugas berisi status operasi penghapusan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika Id file null atau kosong. |

### Lihat Juga

* class [DeleteStatusResponse](../../deletestatusresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


