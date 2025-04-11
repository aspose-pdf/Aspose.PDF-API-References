---
title: Class AssistantCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.AssistantCreateRequest. Objek permintaan untuk membuat asisten
type: docs
weight: 100
url: /id/net/aspose.pdf.ai/assistantcreaterequest/
---
## Kelas AssistantCreateRequest

Objek permintaan untuk membuat asisten.

```csharp
public class AssistantCreateRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AssistantCreateRequest](assistantcreaterequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Mendapatkan atau menetapkan deskripsi asisten. Panjang maksimum adalah 512 karakter. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Mendapatkan atau menetapkan instruksi sistem yang digunakan oleh asisten. Panjang maksimum adalah 256.000 karakter. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Mendapatkan atau menetapkan ID model yang akan digunakan. Anda dapat menggunakan API Daftar model untuk melihat semua model yang tersedia, atau melihat ringkasan Model kami untuk deskripsi tentang mereka. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Mendapatkan atau menetapkan nama asisten. Panjang maksimum adalah 256 karakter. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Mendapatkan atau menetapkan format yang harus dihasilkan oleh model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { "type": "json_object" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi yang tidak berujung sampai generasi mencapai batas token, yang mengakibatkan permintaan yang berjalan lama dan tampaknya "terjebak". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason="length", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Mendapatkan atau menetapkan suhu pengambilan yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0.8 akan membuat keluaran lebih acak, sementara nilai yang lebih rendah seperti 0.2 akan membuatnya lebih fokus dan deterministik. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Mendapatkan atau menetapkan sumber daya yang digunakan oleh alat asisten. Sumber daya spesifik untuk jenis alat. Misalnya, alat code_interpreter memerlukan daftar ID file, sementara alat file_search memerlukan daftar ID penyimpanan vektor. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Mendapatkan atau menetapkan daftar alat yang diaktifkan pada asisten. Terdapat maksimum 128 alat per asisten. Alat dapat berupa jenis code_interpreter, file_search, atau function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Mendapatkan atau menetapkan alternatif untuk pengambilan dengan suhu, yang disebut pengambilan nucleus, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0.1 berarti hanya token yang terdiri dari 10% massa probabilitas teratas yang dipertimbangkan. Kami umumnya merekomendasikan untuk mengubah ini atau suhu tetapi tidak keduanya. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)