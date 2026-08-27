---
title: "Kelas OpenAIClient"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.AI.OpenAIClient. Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola vector store file batches"
type: docs
weight: 900
url: /id/net/aspose.pdf.ai/openaiclient/
---
## OpenAIClient class

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola batch file penyimpanan vektor.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola file vector store.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola vector store.

Mewakili klien untuk berinteraksi dengan OpenAI API, memperluas fungsionalitas dasar klien AI.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola run step di dalam thread.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola file.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola pesan thread.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola thread.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola asisten.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam membuat completions.

Menyediakan metode untuk berinteraksi dengan OpenAI API dalam mengelola run di dalam thread.

```csharp
public class OpenAIClient : AIClientBase, IChatClient<OpenAIChatCopilotOptions>, 
    IImageDescriptionClient<OpenAIImageDescriptionCopilotOptions>, 
    IOcrClient<OpenAIOcrCopilotOptions>, IOpenAIClient, ISummaryClient<OpenAISummaryCopilotOptions>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| [BackoffDelaySeconds](../../aspose.pdf.ai/aiclientbase/backoffdelayseconds/) { get; set; } | Mendapatkan atau mengatur penundaan backoff dalam detik. |
| [HttpRequestMaxRetries](../../aspose.pdf.ai/aiclientbase/httprequestmaxretries/) { get; set; } | Mendapatkan atau mengatur jumlah maksimum percobaan ulang permintaan HTTP. |
| [PollingIntervalSeconds](../../aspose.pdf.ai/aiclientbase/pollingintervalseconds/) { get; set; } | Mendapatkan atau mengatur interval polling dalam detik. |
| [PollingTimeoutSeconds](../../aspose.pdf.ai/aiclientbase/pollingtimeoutseconds/) { get; set; } | Mendapatkan atau mengatur batas waktu polling dalam detik. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [CancelRunAsync](../../aspose.pdf.ai/openaiclient/cancelrunasync/)(string, string, CancellationToken?) | Membatalkan run yang ada di dalam thread secara asynchronous. |
| [CancelVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/cancelvectorstorefilebatchasync/)(string, string, CancellationToken?) | Membatalkan batch file vector store tertentu secara asynchronous. |
| [CreateAssistantAsync](../../aspose.pdf.ai/openaiclient/createassistantasync/)(AssistantCreateRequest, CancellationToken?) | Membuat asisten baru secara asynchronous. |
| [CreateCompletionAsync](../../aspose.pdf.ai/openaiclient/createcompletionasync/)(CompletionCreateRequest, CancellationToken?) | Membuat penyelesaian baru secara asinkron. |
| [CreateRunAsync](../../aspose.pdf.ai/openaiclient/createrunasync/)(string, RunCreateRequest, CancellationToken?) | Membuat run dalam thread yang ditentukan secara asinkron. |
| [CreateThreadAndRunAsync](../../aspose.pdf.ai/openaiclient/createthreadandrunasync/)(RunThreadCreateRequest, CancellationToken?) | Membuat thread dan run di dalamnya secara asinkron. |
| [CreateThreadAsync](../../aspose.pdf.ai/openaiclient/createthreadasync/)(ThreadCreateRequest, CancellationToken?) | Membuat thread baru secara asinkron. |
| [CreateThreadMessageAsync](../../aspose.pdf.ai/openaiclient/createthreadmessageasync/)(string, ThreadMessageCreateRequest, CancellationToken?) | Membuat pesan baru dalam thread secara asinkron. |
| [CreateVectorStoreAndWaitToCompleteAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreandwaittocompleteasync/)(VectorStoreCreateRequest, CancellationToken?) | Membuat vector store baru dan menunggu hingga selesai secara asinkron. |
| [CreateVectorStoreAsync](../../aspose.pdf.ai/openaiclient/createvectorstoreasync/)(VectorStoreCreateRequest, CancellationToken?) | Membuat vector store baru secara asinkron. |
| [CreateVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefileasync/)(string, VectorStoreFileCreateRequest, CancellationToken?) | Membuat file vector store baru secara asinkron. |
| [CreateVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/createvectorstorefilebatchasync/)(string, VectorStoreFileBatchCreateRequest, CancellationToken?) | Membuat batch file vector store baru secara asinkron. |
| [DeleteAssistantAsync](../../aspose.pdf.ai/openaiclient/deleteassistantasync/)(string, CancellationToken?) | Menghapus asisten yang ada secara asinkron. |
| [DeleteFileAsync](../../aspose.pdf.ai/openaiclient/deletefileasync/)(string, CancellationToken?) | Menghapus file tertentu secara asinkron. |
| [DeleteThreadAsync](../../aspose.pdf.ai/openaiclient/deletethreadasync/)(string, CancellationToken?) | Menghapus thread yang ada secara asinkron. |
| [DeleteThreadMessageAsync](../../aspose.pdf.ai/openaiclient/deletethreadmessageasync/)(string, string, CancellationToken?) | Menghapus pesan dalam thread secara asinkron. |
| [DeleteVectorStoreAsync](../../aspose.pdf.ai/openaiclient/deletevectorstoreasync/)(string, CancellationToken?) | Menghapus vector store secara asinkron. |
| [DeleteVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/deletevectorstorefileasync/)(string, string, CancellationToken?) | Menghapus file dalam vector store secara asinkron. |
| [Dispose](../../aspose.pdf.ai/aiclientbase/dispose/)() | Membuang sumber daya yang digunakan oleh [`AIClientBase`](../aiclientbase/). |
| [GetAssistantAsync](../../aspose.pdf.ai/openaiclient/getassistantasync/)(string, CancellationToken?) | Mengambil detail asisten tertentu secara asinkron. |
| [GetAssistantsAsync](../../aspose.pdf.ai/openaiclient/getassistantsasync/)(AssistantListQueryParameters, CancellationToken?) | Mengambil daftar asisten secara asinkron. |
| [GetChatCopilot](../../aspose.pdf.ai/openaiclient/getchatcopilot/)(IChatCopilotOptions&lt;OpenAIChatCopilotOptions&gt;) | Mendapatkan instance dari [`IChatCopilot`](../ichatcopilot/) dengan opsi yang ditentukan. |
| [GetFileAsync](../../aspose.pdf.ai/openaiclient/getfileasync/)(string, CancellationToken?) | Mengambil detail file tertentu secara asinkron. |
| [GetFilesAsync](../../aspose.pdf.ai/openaiclient/getfilesasync/)(string, CancellationToken?) | Mengambil daftar file secara asinkron berdasarkan tujuan yang ditentukan. |
| [GetImageDescriptionCopilot](../../aspose.pdf.ai/openaiclient/getimagedescriptioncopilot/)(IImageDescriptionCopilotOptions&lt;OpenAIImageDescriptionCopilotOptions&gt;) | Mendapatkan instance dari [`IImageDescriptionCopilot`](../iimagedescriptioncopilot/) dengan opsi yang ditentukan. |
| [GetOcrCopilot](../../aspose.pdf.ai/openaiclient/getocrcopilot/)(IOcrCopilotOptions&lt;OpenAIOcrCopilotOptions&gt;) | Mendapatkan instance dari [`IOcrCopilot`](../iocrcopilot/) dengan opsi yang ditentukan. |
| [GetRunAsync](../../aspose.pdf.ai/openaiclient/getrunasync/)(string, string, CancellationToken?) | Mengambil detail run tertentu dalam thread secara asinkron. |
| [GetRunsAsync](../../aspose.pdf.ai/openaiclient/getrunsasync/)(string, RunListQueryParameters, CancellationToken?) | Mengambil daftar run untuk thread yang ditentukan secara asinkron. |
| [GetRunStepAsync](../../aspose.pdf.ai/openaiclient/getrunstepasync/)(string, string, string, CancellationToken?) | Mengambil detail langkah tertentu dalam sebuah run secara asynchronous. |
| [GetRunStepsAsync](../../aspose.pdf.ai/openaiclient/getrunstepsasync/)(string, string, RunStepListQueryParameters, CancellationToken?) | Mengambil daftar langkah untuk run tertentu dalam sebuah thread secara asynchronous. |
| [GetSummaryCopilot](../../aspose.pdf.ai/openaiclient/getsummarycopilot/)(ISummaryCopilotOptions&lt;OpenAISummaryCopilotOptions&gt;) | Mendapatkan instance dari [`ISummaryCopilot`](../isummarycopilot/) dengan opsi yang ditentukan. |
| [GetThreadAsync](../../aspose.pdf.ai/openaiclient/getthreadasync/)(string, CancellationToken?) | Mengambil detail thread tertentu secara asynchronous. |
| [GetThreadMessageAsync](../../aspose.pdf.ai/openaiclient/getthreadmessageasync/)(string, string, CancellationToken?) | Mengambil detail pesan tertentu dalam sebuah thread secara asynchronous. |
| [GetThreadMessagesAsync](../../aspose.pdf.ai/openaiclient/getthreadmessagesasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Mengambil daftar pesan untuk thread tertentu secara asynchronous. |
| [GetVectorStoreAsync](../../aspose.pdf.ai/openaiclient/getvectorstoreasync/)(string, CancellationToken?) | Mengambil detail vector store tertentu secara asynchronous. |
| [GetVectorStoreFileAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefileasync/)(string, string, CancellationToken?) | Mengambil detail file tertentu dalam vector store secara asynchronous. |
| [GetVectorStoreFileBatchAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchasync/)(string, string, CancellationToken?) | Mengambil detail batch file vector store tertentu secara asynchronous. |
| [GetVectorStoreFileBatchFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilebatchfilesasync/)(string, string, VectorStoreFileBatchFileListQueryParameters, CancellationToken?) | Mengambil daftar file dalam batch file vector store tertentu secara asynchronous. |
| [GetVectorStoreFilesAsync](../../aspose.pdf.ai/openaiclient/getvectorstorefilesasync/)(string, VectorStoreFileListQueryParameters, CancellationToken?) | Mengambil daftar file dalam vector store tertentu secara asynchronous. |
| [GetVectorStoresAsync](../../aspose.pdf.ai/openaiclient/getvectorstoresasync/)(VectorStoreListQueryParameters, CancellationToken?) | Mengambil daftar vector store secara asynchronous. |
| [ModifyAssistantAsync](../../aspose.pdf.ai/openaiclient/modifyassistantasync/)(string, AssistantModifyRequest, CancellationToken?) | Memodifikasi assistant yang ada secara asynchronous. |
| [ModifyRunAsync](../../aspose.pdf.ai/openaiclient/modifyrunasync/)(string, string, RunModifyRequest, CancellationToken?) | Memodifikasi run yang ada dalam thread secara asynchronous. |
| [ModifyThreadAsync](../../aspose.pdf.ai/openaiclient/modifythreadasync/)(string, ThreadModifyRequest, CancellationToken?) | Memodifikasi thread yang ada secara asynchronous. |
| [ModifyThreadMessageAsync](../../aspose.pdf.ai/openaiclient/modifythreadmessageasync/)(string, string, ThreadMessageModifyRequest, CancellationToken?) | Memodifikasi pesan yang ada dalam thread secara asynchronous. |
| [ModifyVectorStoreAsync](../../aspose.pdf.ai/openaiclient/modifyvectorstoreasync/)(string, VectorStoreModifyRequest, CancellationToken?) | Memodifikasi vector store yang ada secara asynchronous. |
| [RunAndGetAssistantResponseAsync](../../aspose.pdf.ai/openaiclient/runandgetassistantresponseasync/)(string, RunCreateRequest, CancellationToken?) | Menjalankan assistant dengan threadId dan runCreateRequest yang ditentukan, dan secara asynchronous mendapatkan respons assistant. |
| [UploadFileAsync](../../aspose.pdf.ai/openaiclient/uploadfileasync/)(string, string, byte[], CancellationToken?) | Mengunggah file secara asynchronous ke server OpenAI. |
| [WaitForAssistantMessageAsync](../../aspose.pdf.ai/openaiclient/waitforassistantmessageasync/)(string, ThreadMessageListQueryParameters, CancellationToken?) | Menunggu pesan pertama dari assistant dalam thread secara asynchronous. |
| [WaitForRunToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforruntocompleteasync/)(string, string, CancellationToken?) | Menunggu run selesai dalam thread secara asynchronous. |
| [WaitForThreadMessageToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforthreadmessagetocompleteasync/)(string, string, CancellationToken?) | Menunggu pesan thread tertentu selesai secara asynchronous. |
| [WaitForVectorStoreFileToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstorefiletocompleteasync/)(string, string, CancellationToken?) | Menunggu file vector store tertentu selesai secara asynchronous. |
| [WaitForVectorStoreToCompleteAsync](../../aspose.pdf.ai/openaiclient/waitforvectorstoretocompleteasync/)(string, CancellationToken?) | Menunggu vector store tertentu selesai secara asynchronous. |
| static [CreateWithApiKey](../../aspose.pdf.ai/openaiclient/createwithapikey/)(string) | Membuat instance baru dari [`Builder`](../openaiclient.builder/) dengan API key yang diberikan. |

## Anggota Lain

| Nama | Deskripsi |
| --- | --- |
| class [Builder](../../aspose.pdf.ai/openaiclient.builder) | Kelas builder untuk membuat sebuah instance dari `OpenAIClient`. |

### Lihat Juga

* class [AIClientBase](../aiclientbase/)
* interface [IChatClient&lt;TOptions&gt;](../ichatclient-1/)
* class [OpenAIChatCopilotOptions](../openaichatcopilotoptions/)
* interface [IImageDescriptionClient&lt;TOptions&gt;](../iimagedescriptionclient-1/)
* class [OpenAIImageDescriptionCopilotOptions](../openaiimagedescriptioncopilotoptions/)
* interface [IOcrClient&lt;TOptions&gt;](../iocrclient-1/)
* class [OpenAIOcrCopilotOptions](../openaiocrcopilotoptions/)
* interface [IOpenAIClient](../iopenaiclient/)
* interface [ISummaryClient&lt;TOptions&gt;](../isummaryclient-1/)
* class [OpenAISummaryCopilotOptions](../openaisummarycopilotoptions/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


