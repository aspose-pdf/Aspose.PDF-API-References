---
title: Class AssistantResponse
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.AssistantResponse. Mewakili asisten yang dapat memanggil model dan menggunakan alat
type: docs
weight: 140
url: /id/net/aspose.pdf.ai/assistantresponse/
---
## Kelas AssistantResponse

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
| [CreatedAt](../../aspose.pdf.ai/assistantresponse/createdat/) { get; set; } | Mendapatkan atau mengatur timestamp Unix (dalam detik) untuk saat asisten dibuat. |
| [Description](../../aspose.pdf.ai/assistantresponse/description/) { get; set; } | Mendapatkan atau mengatur deskripsi asisten. Panjang maksimum adalah 512 karakter. |
| [Detail](../../aspose.pdf.ai/baseresponse/detail/) { get; set; } | Mendapatkan atau mengatur detail respons. |
| [Error](../../aspose.pdf.ai/baseresponse/error/) { get; set; } | Mendapatkan atau mengatur kesalahan respons HTTP. |
| [ErrorMessage](../../aspose.pdf.ai/baseresponse/errormessage/) { get; } | Mendapatkan atau mengatur informasi kesalahan. |
| [HttpResponseHeaders](../../aspose.pdf.ai/baseresponse/httpresponseheaders/) { get; set; } | Mendapatkan atau mengatur header respons HTTP. |
| [HttpStatusCode](../../aspose.pdf.ai/baseresponse/httpstatuscode/) { get; set; } | Mendapatkan atau mengatur kode status HTTP. |
| [Id](../../aspose.pdf.ai/assistantresponse/id/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi, yang dapat dirujuk dalam endpoint API. |
| [Instructions](../../aspose.pdf.ai/assistantresponse/instructions/) { get; set; } | Mendapatkan atau mengatur instruksi sistem yang digunakan asisten. Panjang maksimum adalah 256.000 karakter. |
| [IsSuccessful](../../aspose.pdf.ai/baseresponse/issuccessful/) { get; } | Menunjukkan apakah respons berhasil. |
| [Metadata](../../aspose.pdf.ai/assistantresponse/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/assistantresponse/model/) { get; set; } | Mendapatkan atau mengatur ID model yang akan digunakan. Anda dapat menggunakan API Daftar model untuk melihat semua model yang tersedia, atau melihat ringkasan Model kami untuk deskripsi mereka. |
| [Name](../../aspose.pdf.ai/assistantresponse/name/) { get; set; } | Mendapatkan atau mengatur nama asisten. Panjang maksimum adalah 256 karakter. |
| [Object](../../aspose.pdf.ai/assistantresponse/object/) { get; set; } | Mendapatkan atau mengatur tipe objek, yang selalu asisten. |
| [ReasonPhrase](../../aspose.pdf.ai/baseresponse/reasonphrase/) { get; } | Mendapatkan frasa alasan kesalahan. |
| [ResponseFormat](../../aspose.pdf.ai/assistantresponse/responseformat/) { get; set; } | Mendapatkan atau mengatur format yang harus dihasilkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { "type": "json_object" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi yang tidak berujung sampai generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampaknya "terjebak". Juga perhatikan bahwa konten pesan mungkin terputus sebagian jika finish_reason="length", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Temperature](../../aspose.pdf.ai/assistantresponse/temperature/) { get; set; } | Mendapatkan atau mengatur suhu pengambilan yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0.8 akan membuat keluaran lebih acak, sementara nilai yang lebih rendah seperti 0.2 akan membuatnya lebih terfokus dan deterministik. |
| [ToolResources](../../aspose.pdf.ai/assistantresponse/toolresources/) { get; set; } | Mendapatkan atau mengatur sekumpulan sumber daya yang digunakan oleh alat asisten. Sumber daya spesifik untuk jenis alat. Misalnya, alat code_interpreter memerlukan daftar ID file, sementara alat file_search memerlukan daftar ID penyimpanan vektor. |
| [Tools](../../aspose.pdf.ai/assistantresponse/tools/) { get; set; } | Mendapatkan atau mengatur daftar alat yang diaktifkan pada asisten. Terdapat maksimum 128 alat per asisten. Alat dapat berupa jenis code_interpreter, file_search, atau function. |
| [TopP](../../aspose.pdf.ai/assistantresponse/topp/) { get; set; } | Mendapatkan atau mengatur alternatif untuk pengambilan dengan suhu, yang disebut pengambilan nucleus, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0.1 berarti hanya token yang terdiri dari 10% massa probabilitas teratas yang dipertimbangkan. Kami umumnya merekomendasikan untuk mengubah ini atau suhu tetapi tidak keduanya. |

### Lihat Juga

* kelas [BaseResponse](../baseresponse/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)