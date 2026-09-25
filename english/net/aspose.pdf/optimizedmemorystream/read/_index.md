---
title: "OptimizedMemoryStream.Read"
linktitle: "Read"
articleTitle: "Read"
second_title: "Aspose.PDF for .NET API Reference"
description: "OptimizedMemoryStream method. When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stre..."
type: docs
weight: 50
url: "/net/aspose.pdf/optimizedmemorystream/read/"
product_version: "26.9.0"
---
## Read(byte[], int, int) {#read}

When overridden in a derived class, reads a sequence of bytes from the current stream and advances the position within the stream by the number of bytes read.

```csharp
public int Read(byte[] buffer, int offset, int count)
```

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | An array of bytes. When this method returns, the buffer contains the specified byte array with the values |
| offset | int | The zero-based byte offset in at which to begin storing the data read from the current stream. |
| count | int | The maximum number of bytes to be read from the current stream. |

### Return Value

int

The total number of bytes read into the buffer. This can be less than the number of bytes requested if that many bytes are not currently available, or zero (0) if the end of the stream has been reached.

### See Also

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

