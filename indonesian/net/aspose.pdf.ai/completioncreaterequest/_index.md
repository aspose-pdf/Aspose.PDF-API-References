---
title: Class CompletionCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.CompletionCreateRequest. Mewakili permintaan untuk endpoint Create Chat Completion
type: docs
weight: 220
url: /id/net/aspose.pdf.ai/completioncreaterequest/
---
## Kelas CompletionCreateRequest

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
| [FrequencyPenalty](../../aspose.pdf.ai/completioncreaterequest/frequencypenalty/) { get; set; } | Mendapatkan atau mengatur angka antara -2.0 dan 2.0. Nilai positif menghukum token baru berdasarkan frekuensi yang ada dalam teks sejauh ini, mengurangi kemungkinan model untuk mengulangi baris yang sama secara verbatim. |
| [LogitBias](../../aspose.pdf.ai/completioncreaterequest/logitbias/) { get; set; } | Mendapatkan atau mengatur kemungkinan token tertentu muncul dalam penyelesaian. Menerima objek JSON yang memetakan token (ditentukan oleh ID token mereka dalam tokenizer) ke nilai bias terkait dari -100 hingga 100. |
| [Logprobs](../../aspose.pdf.ai/completioncreaterequest/logprobs/) { get; set; } | Mendapatkan atau mengatur apakah akan mengembalikan probabilitas log dari token output atau tidak. Jika true, mengembalikan probabilitas log dari setiap token output yang dikembalikan dalam konten pesan. |
| [MaxTokens](../../aspose.pdf.ai/completioncreaterequest/maxtokens/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum token yang akan dihasilkan dalam penyelesaian. |
| [Messages](../../aspose.pdf.ai/completioncreaterequest/messages/) { get; set; } | Mendapatkan atau mengatur daftar pesan yang terdiri dari percakapan sejauh ini. |
| [Model](../../aspose.pdf.ai/completioncreaterequest/model/) { get; set; } | Mendapatkan atau mengatur ID model yang akan digunakan. |
| [NumberOfChoices](../../aspose.pdf.ai/completioncreaterequest/numberofchoices/) { get; set; } | Mendapatkan atau mengatur berapa banyak pilihan penyelesaian chat yang akan dihasilkan untuk setiap pesan input. Perhatikan bahwa Anda akan dikenakan biaya berdasarkan jumlah token yang dihasilkan di semua pilihan. Pertahankan n sebagai 1 untuk meminimalkan biaya. |
| [PresencePenalty](../../aspose.pdf.ai/completioncreaterequest/presencepenalty/) { get; set; } | Mendapatkan atau mengatur angka antara -2.0 dan 2.0. Nilai positif menghukum token baru berdasarkan apakah mereka muncul dalam teks sejauh ini, meningkatkan kemungkinan model untuk membahas topik baru. |
| [ResponseFormat](../../aspose.pdf.ai/completioncreaterequest/responseformat/) { get; set; } | Mendapatkan atau mengatur objek yang menentukan format yang harus dihasilkan oleh model. Kompatibel dengan GPT-4 Turbo dan semua model GPT-3.5 Turbo yang lebih baru dari gpt-3.5-turbo-1106. Mengatur ke { "type": "json_object" } mengaktifkan mode JSON, yang menjamin pesan yang dihasilkan model adalah JSON yang valid. |
| [Seed](../../aspose.pdf.ai/completioncreaterequest/seed/) { get; set; } | Mendapatkan atau mengatur nilai Seed. Fitur ini dalam Beta. Jika ditentukan, sistem kami akan berusaha sebaik mungkin untuk mengambil sampel secara deterministik, sehingga permintaan berulang dengan seed dan parameter yang sama harus mengembalikan hasil yang sama. Determinisme tidak dijamin, dan Anda harus merujuk pada parameter respons system_fingerprint untuk memantau perubahan di backend. |
| [Stop](../../aspose.pdf.ai/completioncreaterequest/stop/) { get; set; } | Mendapatkan atau mengatur hingga 4 urutan di mana API akan berhenti menghasilkan token lebih lanjut. |
| [Stream](../../aspose.pdf.ai/completioncreaterequest/stream/) { get; set; } | Mendapatkan atau mengatur apakah akan menggunakan streaming. Jika diatur, delta pesan parsial akan dikirim, seperti di ChatGPT. Token akan dikirim sebagai data-only server-sent events saat tersedia, dengan stream diakhiri oleh pesan data: [DONE]. |
| [Temperature](../../aspose.pdf.ai/completioncreaterequest/temperature/) { get; set; } | Mendapatkan atau mengatur suhu pengambilan sampel yang akan digunakan, antara 0 dan 2. Nilai yang lebih tinggi seperti 0.8 akan membuat output lebih acak, sementara nilai yang lebih rendah seperti 0.2 akan membuatnya lebih fokus dan deterministik. |
| [ToolChoice](../../aspose.pdf.ai/completioncreaterequest/toolchoice/) { get; set; } | Mendapatkan atau mengatur objek yang mengontrol alat mana (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat. Menentukan alat tertentu melalui {"type": "function", "function": {"name": "my_function"}} memaksa model untuk memanggil alat tersebut. none adalah default ketika tidak ada alat yang ada. auto adalah default jika alat ada. |
| [Tools](../../aspose.pdf.ai/completioncreaterequest/tools/) { get; set; } | Mendapatkan atau mengatur daftar alat yang mungkin dipanggil model. Saat ini, hanya fungsi yang didukung sebagai alat. Gunakan ini untuk memberikan daftar fungsi yang mungkin dihasilkan model untuk input JSON. Maksimal 128 fungsi didukung. |
| [TopP](../../aspose.pdf.ai/completioncreaterequest/topp/) { get; set; } | Mendapatkan atau mengatur alternatif untuk pengambilan sampel dengan suhu, yang disebut pengambilan sampel nucleus, di mana model mempertimbangkan hasil token dengan massa probabilitas top_p. Jadi 0.1 berarti hanya token yang terdiri dari 10% massa probabilitas teratas yang dipertimbangkan. |
| [User](../../aspose.pdf.ai/completioncreaterequest/user/) { get; set; } | Mendapatkan atau mengatur pengidentifikasi unik yang mewakili pengguna akhir Anda, yang dapat membantu OpenAI untuk memantau dan mendeteksi penyalahgunaan. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)