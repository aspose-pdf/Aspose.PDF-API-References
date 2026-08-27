---
title: "OpenAIClient.UploadFileAsync"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OpenAIClient. Mengunggah file secara asynchronous ke server OpenAI."
type: docs
weight: 460
url: /id/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## OpenAIClient.UploadFileAsync method

Mengunggah file secara asynchronous ke server OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| purpose | String | Tujuan unggahan file, biasanya menjelaskan bagaimana file akan digunakan. |
| fileName | String | Nama file yang akan diunggah. |
| fileBytes | Byte[] | Array byte yang berisi data file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembalian

Task yang mewakili operasi asynchronous. Hasil task berisi respons dari unggahan file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika tujuan file bernilai null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilemparkan ketika nama file bernilai null atau kosong. |

### Lihat Juga

* class [FileResponse](../../fileresponse/)
* class [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


