---
title: Class ThreadMessageCreateRequest
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.ThreadMessageCreateRequest. Mewakili permintaan untuk membuat pesan dalam sebuah thread
type: docs
weight: 1120
url: /id/net/aspose.pdf.ai/threadmessagecreaterequest/
---
## Kelas ThreadMessageCreateRequest

Mewakili permintaan untuk membuat pesan dalam sebuah thread.

```csharp
public class ThreadMessageCreateRequest
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThreadMessageCreateRequest](threadmessagecreaterequest/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [Attachments](../../aspose.pdf.ai/threadmessagecreaterequest/attachments/) { get; set; } | Mendapatkan atau menetapkan daftar file yang dilampirkan pada pesan. |
| [Content](../../aspose.pdf.ai/threadmessagecreaterequest/content/) { get; set; } | Mendapatkan atau menetapkan konten pesan. Bisa berupa string atau array bagian konten. |
| [Metadata](../../aspose.pdf.ai/threadmessagecreaterequest/metadata/) { get; set; } | Mendapatkan atau menetapkan sekumpulan 16 pasangan kunci-nilai yang dapat dilampirkan pada objek. Ini bisa berguna untuk menyimpan informasi tambahan tentang objek dalam format terstruktur. Kunci dapat memiliki panjang maksimum 64 karakter dan nilai dapat memiliki panjang maksimum 512 karakter. |
| [Role](../../aspose.pdf.ai/threadmessagecreaterequest/role/) { get; set; } | Mendapatkan atau menetapkan peran entitas yang membuat pesan. Nilai yang diizinkan termasuk: "user", "assistant". |

## Metode

| Nama | Deskripsi |
| --- | --- |
| static [FromAssistant](../../aspose.pdf.ai/threadmessagecreaterequest/fromassistant/)() | Membuat `ThreadMessageCreateRequest` baru dengan peran yang diatur ke Assistant. |
| static [FromUser](../../aspose.pdf.ai/threadmessagecreaterequest/fromuser/)() | Membuat `ThreadMessageCreateRequest` baru dengan peran yang diatur ke User. |
| [WithAttachments](../../aspose.pdf.ai/threadmessagecreaterequest/withattachments/)(List&lt;Attachment&gt;) | Mengatur lampiran untuk permintaan pesan thread. |
| [WithContent](../../aspose.pdf.ai/threadmessagecreaterequest/withcontent/)(MessageContentRequest) | Menambahkan konten pesan ke permintaan pesan thread. |
| [WithContents](../../aspose.pdf.ai/threadmessagecreaterequest/withcontents/)(List&lt;MessageContentRequest&gt;) | Mengatur konten pesan untuk permintaan pesan thread. |
| [WithMetadata](../../aspose.pdf.ai/threadmessagecreaterequest/withmetadata/)(Dictionary&lt;string, string&gt;) | Mengatur metadata untuk permintaan pesan thread. |

### Lihat Juga

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)