---
title: "Kelas CreateEmbeddingRequest"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.CreateEmbeddingRequest. Mewakili permintaan untuk endpoint Create Embeddings"
type: docs
weight: 270
url: /id/net/aspose.pdf.ai/createembeddingrequest/
---
## CreateEmbeddingRequest class

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
| [Dimensions](../../aspose.pdf.ai/createembeddingrequest/dimensions/) { get; set; } | Mendapatkan atau mengatur jumlah dimensi yang harus dimiliki embedding output yang dihasilkan. Hanya didukung dalam model text-embedding-3 dan yang lebih baru. |
| [EncodingFormat](../../aspose.pdf.ai/createembeddingrequest/encodingformat/) { get; set; } | Mendapatkan atau mengatur format untuk mengembalikan embedding. Dapat berupa float atau base64. |
| [Input](../../aspose.pdf.ai/createembeddingrequest/input/) { get; set; } | Mendapatkan atau mengatur teks input untuk di-embed, dienkode sebagai string atau array token. Untuk meng-embed beberapa input dalam satu permintaan, berikan array string atau array array token. Input tidak boleh melebihi token maksimum untuk model (8192 token untuk text-embedding-ada-002), tidak boleh berupa string kosong, dan setiap array harus berukuran 2048 dimensi atau kurang. |
| [Model](../../aspose.pdf.ai/createembeddingrequest/model/) { get; set; } | Mendapatkan atau mengatur model untuk menghasilkan embedding. |
| [User](../../aspose.pdf.ai/createembeddingrequest/user/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik yang mewakili pengguna akhir Anda, yang dapat membantu OpenAI memantau dan mendeteksi penyalahgunaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


