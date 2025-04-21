---
title: RunCreateRequest.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: Properti RunCreateRequest. Mendapatkan atau mengatur alat mana yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti "type" "file_search" atau "type" "function", "function" "name" "my_function" memaksa model untuk memanggil alat tersebut.
type: docs
weight: 130
url: /id/net/aspose.pdf.ai/runcreaterequest/toolchoice/
---
## Properti RunCreateRequest.ToolChoice

Mendapatkan atau mengatur alat mana (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {"type": "file_search"} atau {"type": "function", "function": {"name": "my_function"}} memaksa model untuk memanggil alat tersebut.

```csharp
public string ToolChoice { get; set; }
```

### Lihat Juga

* kelas [RunCreateRequest](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)