---
title: OpenAIClient.UploadFileAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode OpenAIClient. Mengunggah file secara asinkron ke server OpenAI
type: docs
weight: 450
url: /id/net/aspose.pdf.ai/openaiclient/uploadfileasync/
---
## Metode OpenAIClient.UploadFileAsync

Mengunggah file secara asinkron ke server OpenAI.

```csharp
public Task<FileResponse> UploadFileAsync(string purpose, string fileName, byte[] fileBytes, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| purpose | String | Tujuan pengunggahan file, biasanya menggambarkan bagaimana file akan digunakan. |
| fileName | String | Nama file yang akan diunggah. |
| fileBytes | Byte[] | Array byte yang berisi data file. |
| cancellationToken | Nullable`1 | Token untuk membatalkan operasi. |

### Nilai Kembali

Sebuah tugas yang mewakili operasi asinkron. Hasil tugas berisi respons dari pengunggahan file.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| [AIClientException](../../aiclientexception/) | Dilempar ketika tujuan file adalah null atau kosong. |
| [AIClientException](../../aiclientexception/) | Dilempar ketika nama file adalah null atau kosong. |

### Lihat Juga

* kelas [FileResponse](../../fileresponse/)
* kelas [OpenAIClient](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)