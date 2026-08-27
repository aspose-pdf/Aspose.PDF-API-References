---
title: "RunThreadCreateRequest.ResponseFormat"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti RunThreadCreateRequest. Mendapatkan atau mengatur format yang harus dikeluarkan oleh model. Kompatibel dengan GPT4o, GPT4 Turbo, dan semua model GPT3.5 Turbo sejak gpt3.5turbo1106. Mengatur ke tipe json_object mengaktifkan mode JSON yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting saat menggunakan mode JSON Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini model dapat menghasilkan aliran whitespace yang tak berujung hingga generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak terjebak. Juga perlu dicatat bahwa konten pesan mungkin terpotong sebagian jika finish_reasonlength yang menunjukkan generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum."
type: docs
weight: 80
url: /id/net/aspose.pdf.ai/runthreadcreaterequest/responseformat/
---
## RunThreadCreateRequest.ResponseFormat property

Menentukan atau mengatur format yang harus dikeluarkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi tak berujung hingga generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak \"macet\". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason=\"length\", yang menunjukkan generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum.

```csharp
public ResponseFormat ResponseFormat { get; set; }
```

### Lihat Juga

* class [ResponseFormat](../../responseformat/)
* class [RunThreadCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


