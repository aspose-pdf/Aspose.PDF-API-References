---
title: CompletionCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Properti CompletionCreateRequest. Mendapatkan atau mengatur objek yang mengontrol alat mana yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat. Menentukan alat tertentu melalui "type": "function", "function": "name": "my_function" memaksa model untuk memanggil alat tersebut. none adalah default ketika tidak ada alat yang ada. auto adalah default jika alat ada.
type: docs
weight: 150
url: /id/net/aspose.pdf.ai/completioncreaterequest/toolchoice/
---
## Properti CompletionCreateRequest.ToolChoice

Mendapatkan atau mengatur objek yang mengontrol alat mana (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat. Menentukan alat tertentu melalui {"type": "function", "function": {"name": "my_function"}} memaksa model untuk memanggil alat tersebut. none adalah default ketika tidak ada alat yang ada. auto adalah default jika alat ada.

```csharp
public ToolChoice ToolChoice { get; set; }
```

### Lihat Juga

* kelas [ToolChoice](../../toolchoice/)
* kelas [CompletionCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)