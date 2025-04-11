---
title: Class OpenAIClient
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.OpenAIClient. Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola batch file penyimpanan vektor
type: docs
weight: 840
url: /id/net/aspose.pdf.ai/openaiclient/
---
## Kelas OpenAIClient

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola batch file penyimpanan vektor.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola file penyimpanan vektor.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola penyimpanan vektor.

Mewakili klien untuk berinteraksi dengan API OpenAI, memperluas fungsionalitas klien AI dasar.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola langkah-langkah eksekusi dalam thread.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola file.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola pesan thread.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola thread.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola asisten.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk membuat penyelesaian.

Menyediakan metode untuk berinteraksi dengan API OpenAI untuk mengelola eksekusi dalam thread.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, IOpenAIClient, 
    ISummaryClient<OpenAISummaryCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Mendapatkan atau menetapkan penundaan backoff dalam detik. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Mendapatkan atau menetapkan jumlah maksimum pengulangan permintaan HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Mendapatkan atau menetapkan interval polling dalam detik. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Mendapatkan atau menetapkan waktu habis polling dalam detik. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Membatalkan eksekusi yang ada dalam thread secara asinkron. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Membatalkan batch file penyimpanan vektor tertentu secara asinkron. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Membuat asisten baru secara asinkron. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Membuat penyelesaian baru secara asinkron. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Membuat eksekusi dalam thread yang ditentukan secara asinkron. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Membuat thread dan eksekusi di dalamnya secara asinkron. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Membuat thread baru secara asinkron. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Membuat pesan baru dalam thread secara asinkron. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Membuat penyimpanan vektor baru dan menunggu penyelesaiannya secara asinkron. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Membuat penyimpanan vektor baru secara asinkron. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Membuat file penyimpanan vektor baru secara asinkron. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Membuat batch file penyimpanan vektor baru secara asinkron. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Menghapus asisten yang ada secara asinkron. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Menghapus file tertentu secara asinkron. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Menghapus thread yang ada secara asinkron. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Menghapus pesan dalam thread secara asinkron. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Menghapus penyimpanan vektor secara asinkron. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string) | Menghapus file dalam penyimpanan vektor secara asinkron. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Menghapus sumber daya yang digunakan oleh [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Mengambil detail asisten tertentu secara asinkron. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Mengambil daftar asisten secara asinkron. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Mendapatkan instance dari [`IChatCopilot`](../ichatcopilot/) dengan opsi yang ditentukan. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Mengambil detail file tertentu secara asinkron. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Mengambil daftar file secara asinkron berdasarkan tujuan yang ditentukan. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Mendapatkan instance dari [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) dengan opsi yang ditentukan. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Mengambil detail eksekusi tertentu dalam thread secara asinkron. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Mengambil daftar eksekusi untuk thread yang ditentukan secara asinkron. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Mengambil detail langkah tertentu dalam eksekusi secara asinkron. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Mengambil daftar langkah untuk eksekusi tertentu dalam thread secara asinkron. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Mendapatkan instance dari [`ISummaryCopilot`](../isummarycopilot/) dengan opsi yang ditentukan. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Mengambil detail thread tertentu secara asinkron. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Mengambil detail pesan tertentu dalam thread secara asinkron. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Mengambil daftar pesan untuk thread tertentu secara asinkron. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Mengambil detail penyimpanan vektor tertentu secara asinkron. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string) | Mengambil detail file tertentu dalam penyimpanan vektor secara asinkron. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Mengambil detail batch file penyimpanan vektor tertentu secara asinkron. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Mengambil daftar file dalam batch file penyimpanan vektor tertentu secara asinkron. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Mengambil daftar file dalam penyimpanan vektor tertentu secara asinkron. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Mengambil daftar penyimpanan vektor secara asinkron. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Memodifikasi asisten yang ada secara asinkron. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Memodifikasi eksekusi yang ada dalam thread secara asinkron. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Memodifikasi thread yang ada secara asinkron. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Memodifikasi pesan yang ada dalam thread secara asinkron. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Memodifikasi penyimpanan vektor yang ada secara asinkron. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Menjalankan asisten dengan threadId dan runCreateRequest yang ditentukan, dan secara asinkron mendapatkan respons asisten. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Mengunggah file secara asinkron ke server OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Menunggu pesan pertama dari asisten dalam thread secara asinkron. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Menunggu eksekusi untuk selesai dalam thread secara asinkron. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string) | Menunggu pesan thread tertentu untuk selesai secara asinkron. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string) | Menunggu file penyimpanan vektor tertentu untuk selesai secara asinkron. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Menunggu penyimpanan vektor tertentu untuk selesai secara asinkron. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Membuat instance baru dari [`Builder`](../openaiclient.builder/) dengan kunci API yang diberikan. |

## Anggota Lainnya

| Nama | Deskripsi |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Kelas Builder untuk membuat instance dari `OpenAIClient`. |

### Lihat Juga

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)