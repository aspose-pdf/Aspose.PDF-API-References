---
title: Class RunThreadCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.RunThreadCreateRequest. Mewakili permintaan untuk membuat sebuah thread dan menjalankannya dalam satu permintaan
type: docs
weight: 1070
url: /id/net/aspose.pdf.ai/runthreadcreaterequest/
---
## Kelas RunThreadCreateRequest

Mewakili permintaan untuk membuat sebuah thread dan menjalankannya dalam satu permintaan.

```csharp
public class RunThreadCreateRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [RunThreadCreateRequest](runthreadcreaterequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Mendapatkan atau menetapkan ID asisten yang digunakan untuk mengeksekusi run ini. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Mendapatkan atau menetapkan instruksi yang menggantikan instruksi asisten. Ini berguna untuk memodifikasi perilaku berdasarkan setiap run. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token penyelesaian yang dapat digunakan selama run. Run akan berusaha sebaik mungkin untuk hanya menggunakan jumlah token penyelesaian yang ditentukan, di seluruh beberapa giliran run. Jika run melebihi jumlah token penyelesaian yang ditentukan, run akan berakhir dengan status tidak lengkap. Lihat incomplete_details untuk informasi lebih lanjut. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum token prompt yang dapat digunakan selama run. Run akan berusaha sebaik mungkin untuk hanya menggunakan jumlah token prompt yang ditentukan, di seluruh beberapa giliran run. Jika run melebihi jumlah token prompt yang ditentukan, run akan berakhir dengan status tidak lengkap. Lihat incomplete_details untuk informasi lebih lanjut. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Mendapatkan atau menetapkan ID Model yang akan digunakan untuk mengeksekusi run ini. Jika nilai diberikan di sini, itu akan menggantikan model yang terkait dengan asisten. Jika tidak, model yang terkait dengan asisten akan digunakan. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Mendapatkan atau menetapkan format yang harus dihasilkan oleh model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { "type": "json_object" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi yang tidak berujung sampai generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampaknya "terjebak". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason="length", yang menunjukkan bahwa generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Mendapatkan atau menetapkan apakah akan menggunakan streaming. Jika true, mengembalikan aliran peristiwa yang terjadi selama Run sebagai peristiwa yang dikirim server, yang berakhir ketika Run memasuki keadaan terminal dengan pesan data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Mendapatkan atau menetapkan suhu pengambilan sampel yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0.8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0.2 akan membuatnya lebih fokus dan deterministik. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Mendapatkan atau menetapkan permintaan untuk membuat sebuah thread. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Mendapatkan atau menetapkan alat mana (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {"type": "file_search"} atau {"type": "function", "function": {"name": "my_function"}} memaksa model untuk memanggil alat tersebut. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Mendapatkan atau menetapkan sekumpulan sumber daya yang digunakan oleh alat asisten. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Mendapatkan atau menetapkan alat yang menggantikan alat yang dapat digunakan asisten untuk run ini. Ini berguna untuk memodifikasi perilaku berdasarkan setiap run. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Mendapatkan atau menetapkan nilai yang alternatif untuk pengambilan sampel dengan suhu, yang disebut pengambilan sampel nucleus, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0.1 berarti hanya token yang terdiri dari 10% massa probabilitas teratas yang dipertimbangkan. Kami umumnya merekomendasikan untuk mengubah ini atau suhu tetapi tidak keduanya. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Mendapatkan atau menetapkan strategi pemotongan yang mengontrol bagaimana sebuah thread akan dipotong sebelum run. Gunakan ini untuk mengontrol jendela konteks awal dari run. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)