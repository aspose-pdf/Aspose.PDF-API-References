---
title: "RunResponse.ToolChoice"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti RunResponse. Mendapatkan atau mengatur alat mana, jika ada, yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan sebaliknya menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti tipe file_search atau tipe function dengan nama fungsi my_function memaksa model untuk memanggil alat tersebut."
type: docs
weight: 230
url: /id/net/aspose.pdf.ai/runresponse/toolchoice/
---
## RunResponse.ToolChoice property

Menentukan atau mengatur alat (jika ada) yang dipanggil oleh model. none berarti model tidak akan memanggil alat apa pun dan malah menghasilkan pesan. auto adalah nilai default dan berarti model dapat memilih antara menghasilkan pesan atau memanggil satu atau lebih alat. required berarti model harus memanggil satu atau lebih alat sebelum merespons pengguna. Menentukan alat tertentu seperti {\"type\": \"file_search\"} atau {\"type\": \"function\", \"function\": {\"name\": \"my_function\"}} memaksa model untuk memanggil alat tersebut.

```csharp
public string ToolChoice { get; set; }
```

### Lihat Juga

* class [RunResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)


