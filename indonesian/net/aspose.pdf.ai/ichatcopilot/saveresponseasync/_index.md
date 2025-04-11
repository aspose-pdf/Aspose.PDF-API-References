---
title: IChatCopilot.SaveResponseAsync
second_title: Aspose.PDF for .NET API Reference
description: Metode IChatCopilot. Menyimpan respons untuk pesan yang diberikan ke file PDF secara asinkron
type: docs
weight: 40
url: /id/net/aspose.pdf.ai/ichatcopilot/saveresponseasync/
---
## SaveResponseAsync(string, string, CancellationToken?) {#saveresponseasync_3}

Menyimpan respons untuk pesan yang diberikan ke file PDF secara asinkron.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | String | Pesan input untuk mana respons disimpan. |
| outputFileName | String | Nama file PDF keluaran untuk menyimpan respons. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(string, string, SaveFormat, CancellationToken?) {#saveresponseasync_2}

Menyimpan respons untuk pesan yang diberikan ke file dengan format yang ditentukan secara asinkron.

```csharp
public Task SaveResponseAsync(string message, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| message | String | Pesan input untuk mana respons disimpan. |
| outputFileName | String | Nama file keluaran untuk menyimpan respons. |
| saveFormat | SaveFormat | Format di mana respons disimpan (PDF jika tidak ditentukan). |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, CancellationToken?) {#saveresponseasync_1}

Menyimpan respons untuk daftar pesan yang diberikan ke file PDF secara asinkron.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| messages | List`1 | Daftar pesan input untuk mana respons disimpan. |
| outputFileName | String | Nama file PDF keluaran untuk menyimpan respons. |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron.

### See Also

* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)

---

## SaveResponseAsync(List&lt;string&gt;, string, SaveFormat, CancellationToken?) {#saveresponseasync}

Menyimpan respons untuk daftar pesan yang diberikan ke file dengan format yang ditentukan secara asinkron.

```csharp
public Task SaveResponseAsync(List<string> messages, string outputFileName, SaveFormat saveFormat, 
    CancellationToken? cancellationToken = default)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| messages | List`1 | Daftar pesan input untuk mana respons disimpan. |
| outputFileName | String | Nama file keluaran untuk menyimpan respons. |
| saveFormat | SaveFormat | Format di mana respons disimpan (PDF jika tidak ditentukan). |
| cancellationToken | Nullable`1 | Token pembatalan (opsional). |

### Return Value

Sebuah tugas yang mewakili operasi asinkron.

### See Also

* enum [SaveFormat](../../../aspose.pdf/saveformat/)
* interface [IChatCopilot](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)