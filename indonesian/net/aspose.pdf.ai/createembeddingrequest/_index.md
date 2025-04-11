---
title: Class CreateEmbeddingRequest
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.CreateEmbeddingRequest. Mewakili permintaan untuk endpoint Create Embeddings
type: docs
weight: 260
url: /id/net/aspose.pdf.ai/createembeddingrequest/
---
## Kelas CreateEmbeddingRequest

Mewakili permintaan untuk endpoint Create Embeddings.

```csharp
public class CreateEmbeddingRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CreateEmbeddingRequest](createembeddingrequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Mendapatkan atau menetapkan jumlah dimensi yang harus dimiliki embedding output yang dihasilkan. Hanya didukung dalam model text-embedding-3 dan yang lebih baru. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Mendapatkan atau menetapkan format untuk mengembalikan embedding. Bisa berupa float atau base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Mendapatkan atau menetapkan teks input untuk disematkan, yang dikodekan sebagai string atau array token. Untuk menyematkan beberapa input dalam satu permintaan, kirimkan array string atau array dari array token. Input tidak boleh melebihi jumlah token input maksimum untuk model (8192 token untuk text-embedding-ada-002), tidak boleh berupa string kosong, dan setiap array harus memiliki 2048 dimensi atau kurang. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Mendapatkan atau menetapkan model untuk menghasilkan embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Mendapatkan atau menetapkan pengidentifikasi unik yang mewakili pengguna akhir Anda, yang dapat membantu OpenAI untuk memantau dan mendeteksi penyalahgunaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)