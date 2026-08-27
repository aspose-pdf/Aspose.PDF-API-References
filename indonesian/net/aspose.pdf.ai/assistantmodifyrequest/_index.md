---
title: "Kelas AssistantModifyRequest"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.AssistantModifyRequest. Objek permintaan untuk memodifikasi asisten"
type: docs
weight: 130
url: /id/net/aspose.pdf.ai/assistantmodifyrequest/
---
## AssistantModifyRequest class

Objek permintaan untuk memodifikasi asisten.

```csharp
public class AssistantModifyRequest : AssistantCreateRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [AssistantModifyRequest](assistantmodifyrequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Description](../../aspose.pdf.ai/assistantcreaterequest/description/) { get; set; } | Mendapatkan atau mengatur deskripsi asisten. Panjang maksimum adalah 512 karakter. |
| [Instructions](../../aspose.pdf.ai/assistantcreaterequest/instructions/) { get; set; } | Mendapatkan atau mengatur instruksi sistem yang digunakan asisten. Panjang maksimum adalah 256.000 karakter. |
| [Metadata](../../aspose.pdf.ai/assistantcreaterequest/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan ke sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/assistantcreaterequest/model/) { get; set; } | Mendapatkan atau mengatur ID model yang akan digunakan. Anda dapat menggunakan API List models untuk melihat semua model yang tersedia, atau melihat ikhtisar Model kami untuk deskripsi masing‑masing. |
| [Name](../../aspose.pdf.ai/assistantcreaterequest/name/) { get; set; } | Mendapatkan atau mengatur nama asisten. Panjang maksimum adalah 256 karakter. |
| [ResponseFormat](../../aspose.pdf.ai/assistantcreaterequest/responseformat/) { get; set; } | Mendapatkan atau mengatur format yang harus dikeluarkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Menetapkan ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi tak berujung sampai generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak \"macet\". Juga perhatikan bahwa konten pesan dapat terpotong sebagian jika finish_reason=\"length\", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Temperature](../../aspose.pdf.ai/assistantcreaterequest/temperature/) { get; set; } | Mendapatkan atau mengatur suhu sampling yang digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0,8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0,2 akan membuatnya lebih terfokus dan deterministik. |
| [ToolResources](../../aspose.pdf.ai/assistantcreaterequest/toolresources/) { get; set; } | Mendapatkan atau mengatur sumber daya yang digunakan oleh alat asisten. Sumber daya bersifat spesifik untuk jenis alat. Misalnya, alat code_interpreter memerlukan daftar ID file, sementara alat file_search memerlukan daftar ID penyimpanan vektor. |
| [Tools](../../aspose.pdf.ai/assistantcreaterequest/tools/) { get; set; } | Mendapatkan atau mengatur daftar alat yang diaktifkan pada asisten. Maksimum 128 alat per asisten. Alat dapat berupa tipe code_interpreter, file_search, atau function. |
| [TopP](../../aspose.pdf.ai/assistantcreaterequest/topp/) { get; set; } | Mendapatkan atau mengatur alternatif sampling dengan suhu, yang disebut nucleus sampling, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0,1 berarti hanya token yang mencakup 10% teratas massa probabilitas yang dipertimbangkan. Kami biasanya merekomendasikan mengubah ini atau suhu, tetapi tidak keduanya. |

### Lihat Juga

* class [AssistantCreateRequest](../assistantcreaterequest/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


