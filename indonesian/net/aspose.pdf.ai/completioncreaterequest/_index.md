---
title: "Kelas CompletionCreateRequest"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.AI.CompletionCreateRequest kelas. Mewakili permintaan untuk endpoint Create Chat Completion"
type: docs
weight: 230
url: /id/net/aspose.pdf.ai/completioncreaterequest/
---
## CompletionCreateRequest class

Mewakili permintaan untuk endpoint Create Chat Completion.

```csharp
public class CompletionCreateRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [CompletionCreateRequest](completioncreaterequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Mendapatkan atau mengatur angka antara -2.0 dan 2.0. Nilai positif menghukum token baru berdasarkan frekuensi mereka yang sudah ada dalam teks sejauh ini, mengurangi kemungkinan model mengulang baris yang sama secara verbatim. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Mendapatkan atau mengatur kemungkinan token tertentu muncul dalam penyelesaian. Menerima objek JSON yang memetakan token (ditentukan oleh ID token mereka dalam tokenizer) ke nilai bias terkait dari -100 hingga 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Mendapatkan atau mengatur apakah mengembalikan probabilitas log token output atau tidak. Jika true, mengembalikan probabilitas log setiap token output yang dikembalikan dalam konten pesan. |
| [MaxCompletionTokens](../../aspose.pdf.ai/completioncreaterequest/maxcompletiontokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token yang dihasilkan dalam penyelesaian. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Mendapatkan atau mengatur daftar pesan yang terdiri dari percakapan sejauh ini. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Mendapatkan atau mengatur ID model yang akan digunakan. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Mendapatkan atau mengatur berapa banyak pilihan penyelesaian obrolan yang dihasilkan untuk setiap pesan masuk. Perhatikan bahwa Anda akan dikenakan biaya berdasarkan jumlah token yang dihasilkan di semua pilihan. Tetapkan n menjadi 1 untuk meminimalkan biaya. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Mendapatkan atau mengatur angka antara -2.0 dan 2.0. Nilai positif memberi penalti pada token baru berdasarkan apakah mereka muncul dalam teks sejauh ini, meningkatkan kemungkinan model untuk membicarakan topik baru. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Mendapatkan atau mengatur objek yang menentukan format yang harus dikeluarkan oleh model. Kompatibel dengan GPT-4 Turbo dan semua model GPT-3.5 Turbo yang lebih baru dari gpt-3.5-turbo-1106. Menetapkan ke { \"type\": \"json_object\" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Mendapatkan atau mengatur nilai Seed. Fitur ini berada dalam Beta. Jika ditentukan, sistem kami akan berusaha sebaik mungkin untuk melakukan sampling secara deterministik, sehingga permintaan berulang dengan seed dan parameter yang sama harus mengembalikan hasil yang sama. Determinisme tidak dijamin, dan Anda harus merujuk ke parameter respons system_fingerprint untuk memantau perubahan di backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Mendapatkan atau mengatur hingga 4 urutan di mana API akan berhenti menghasilkan token lebih lanjut. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Mendapatkan atau mengatur apakah menggunakan streaming. Jika diatur, delta pesan parsial akan dikirim, seperti di ChatGPT. Token akan dikirim sebagai event server-sent hanya data saat tersedia, dengan aliran dihentikan oleh pesan data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Mendapatkan atau mengatur suhu sampling yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0,8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0,2 akan membuatnya lebih terfokus dan deterministik. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Mendapatkan atau mengatur objek yang mengontrol alat (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat. Menentukan alat tertentu melalui {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} memaksa model memanggil alat tersebut. none adalah default ketika tidak ada alat. auto adalah default jika ada alat. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Mendapatkan atau mengatur daftar alat yang dapat dipanggil model. Saat ini, hanya fungsi yang didukung sebagai alat. Gunakan ini untuk menyediakan daftar fungsi yang dapat model menghasilkan masukan JSON untuknya. Maksimum 128 fungsi didukung. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Mendapatkan atau mengatur alternatif sampling dengan suhu, disebut nucleus sampling, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0,1 berarti hanya token yang mencakup 10% teratas massa probabilitas yang dipertimbangkan. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik yang mewakili pengguna akhir Anda, yang dapat membantu OpenAI memantau dan mendeteksi penyalahgunaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


