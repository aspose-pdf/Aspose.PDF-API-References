---
title: "Kelas RunThreadCreateRequest"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.RunThreadCreateRequest. Mewakili permintaan untuk membuat thread dan menjalankannya dalam satu permintaan."
type: docs
weight: 1150
url: /id/net/aspose.pdf.ai/runthreadcreaterequest/
---
## RunThreadCreateRequest class

Mewakili permintaan untuk membuat thread dan menjalankannya dalam satu permintaan.

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
| [AssistantId](../../aspose.pdf.ai/runthreadcreaterequest/assistantid/) { get; set; } | Mendapatkan atau mengatur ID asisten yang akan digunakan untuk mengeksekusi run ini. |
| [Instructions](../../aspose.pdf.ai/runthreadcreaterequest/instructions/) { get; set; } | Mendapatkan atau mengatur instruksi yang menggantikan instruksi asisten. Ini berguna untuk memodifikasi perilaku pada tiap run. |
| [MaxCompletionTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxcompletiontokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token penyelesaian yang dapat digunakan selama run. Run akan berusaha sebaik mungkin hanya menggunakan jumlah token penyelesaian yang ditentukan, melintasi beberapa putaran run. Jika run melebihi jumlah token penyelesaian yang ditentukan, run akan berakhir dengan status incomplete. Lihat incomplete_details untuk info lebih lanjut. |
| [MaxPromptTokens](../../aspose.pdf.ai/runthreadcreaterequest/maxprompttokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token prompt yang dapat digunakan selama run. Run akan berusaha sebaik mungkin hanya menggunakan jumlah token prompt yang ditentukan, melintasi beberapa putaran run. Jika run melebihi jumlah token prompt yang ditentukan, run akan berakhir dengan status incomplete. Lihat incomplete_details untuk info lebih lanjut. |
| [Metadata](../../aspose.pdf.ai/runthreadcreaterequest/metadata/) { get; set; } | Mendapatkan atau mengatur sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan ke sebuah objek. Ini dapat berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Model](../../aspose.pdf.ai/runthreadcreaterequest/model/) { get; set; } | Mendapatkan atau mengatur ID Model yang akan digunakan untuk mengeksekusi run ini. Jika nilai diberikan di sini, itu akan menggantikan model yang terkait dengan asisten. Jika tidak, model yang terkait dengan asisten akan digunakan. |
| [ResponseFormat](../../aspose.pdf.ai/runthreadcreaterequest/responseformat/) { get; set; } | Menentukan atau mengatur format yang harus dikeluarkan model. Kompatibel dengan GPT-4o, GPT-4 Turbo, dan semua model GPT-3.5 Turbo sejak gpt-3.5-turbo-1106. Mengatur ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. Penting: saat menggunakan mode JSON, Anda juga harus menginstruksikan model untuk menghasilkan JSON sendiri melalui pesan sistem atau pengguna. Tanpa ini, model dapat menghasilkan aliran spasi tak berujung hingga generasi mencapai batas token, menghasilkan permintaan yang berjalan lama dan tampak \"macet\". Juga perhatikan bahwa konten pesan mungkin terpotong sebagian jika finish_reason=\"length\", yang menunjukkan generasi melebihi max_tokens atau percakapan melebihi panjang konteks maksimum. |
| [Stream](../../aspose.pdf.ai/runthreadcreaterequest/stream/) { get; set; } | Mendapatkan atau mengatur apakah akan menggunakan streaming. Jika true, mengembalikan aliran peristiwa yang terjadi selama Run sebagai server-sent events, berakhir ketika Run memasuki status terminal dengan pesan data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/runthreadcreaterequest/temperature/) { get; set; } | Mendapatkan atau mengatur suhu sampling yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0,8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0,2 akan membuatnya lebih terfokus dan deterministik. |
| [Thread](../../aspose.pdf.ai/runthreadcreaterequest/thread/) { get; set; } | Mendapatkan atau mengatur permintaan untuk membuat thread. |
| [ToolChoice](../../aspose.pdf.ai/runthreadcreaterequest/toolchoice/) { get; set; } | Menentukan atau mengatur alat (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan malah menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {\"type\": \"file_search\"} atau {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} memaksa model untuk memanggil alat tersebut. |
| [ToolResources](../../aspose.pdf.ai/runthreadcreaterequest/toolresources/) { get; set; } | Mendapatkan atau mengatur sekumpulan sumber daya yang digunakan oleh alat asisten. |
| [Tools](../../aspose.pdf.ai/runthreadcreaterequest/tools/) { get; set; } | Mendapatkan atau mengatur alat yang menggantikan alat yang dapat digunakan asisten untuk run ini. Ini berguna untuk memodifikasi perilaku pada tiap run. |
| [TopP](../../aspose.pdf.ai/runthreadcreaterequest/topp/) { get; set; } | Mendapatkan atau mengatur nilai yang menjadi alternatif sampling dengan temperature, disebut nucleus sampling, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0.1 berarti hanya token yang mencakup 10% teratas massa probabilitas yang dipertimbangkan. Kami biasanya menyarankan mengubah ini atau temperature, tetapi tidak keduanya. |
| [TruncationStrategy](../../aspose.pdf.ai/runthreadcreaterequest/truncationstrategy/) { get; set; } | Mendapatkan atau mengatur strategi pemotongan yang mengontrol bagaimana thread akan dipotong sebelum run. Gunakan ini untuk mengontrol jendela konteks awal run. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


