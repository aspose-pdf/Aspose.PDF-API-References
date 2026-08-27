---
title: "Kelas AssistantResponse"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.AssistantResponse. Mewakili asisten yang dapat memanggil model dan menggunakan alat."
type: docs
weight: 140
url: /id/net/aspose.pdf.ai/assistantresponse/
---
## AssistantResponse class

Mewakili asisten yang dapat memanggil model dan menggunakan alat.

```csharp
public class AssistantResponse : BaseResponse
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AssistantResponse](assistantresponse/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Mendapatkan atau mengatur stempel waktu Unix (dalam detik) saat asisten dibuat. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Mendapatkan atau mengatur deskripsi asisten. Panjang maksimum adalah 512 karakter. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi, yang dapat direferensikan dalam endpoint API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Mendapatkan atau mengatur instruksi sistem yang digunakan asisten. Panjang maksimum adalah 256.000 karakter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan ke sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Mendapatkan atau mengatur ID model yang akan digunakan. Anda dapat menggunakan API List models untuk melihat semua model yang tersedia, atau melihat ikhtisar Model kami untuk deskripsi masing‑masing. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Mendapatkan atau mengatur nama asisten. Panjang maksimum adalah 256 karakter. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu assistant. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Mendapatkan atau mengatur format yang harus dikeluarkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Menetapkan ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi tak berujung sampai generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak \"macet\". Juga perhatikan bahwa konten pesan dapat terpotong sebagian jika finish_reason=\"length\", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Mendapatkan atau mengatur suhu sampling yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0,8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0,2 akan membuatnya lebih terfokus dan deterministik. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Mendapatkan atau mengatur sekumpulan sumber daya yang digunakan oleh alat asisten. Sumber daya tersebut spesifik untuk jenis alat. Misalnya, alat code_interpreter memerlukan daftar ID file, sementara alat file_search memerlukan daftar ID vector store. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Mendapatkan atau mengatur daftar alat yang diaktifkan pada asisten. Maksimum 128 alat per asisten. Alat dapat berupa tipe code_interpreter, file_search, atau function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Mendapatkan atau mengatur alternatif sampling dengan suhu, yang disebut nucleus sampling, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0,1 berarti hanya token yang mencakup 10% teratas massa probabilitas yang dipertimbangkan. Kami biasanya merekomendasikan mengubah ini atau suhu, tetapi tidak keduanya. |

### Lihat Juga

* class [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


