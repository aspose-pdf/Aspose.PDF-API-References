---
title: Document.ConvertToSearchablePdf
second_title: Aspose.PDF for .NET API Reference
description: Document method. Adds a searchable OCR text layer using the default recognition options
type: docs
weight: 620
url: /net/aspose.pdf/document/converttosearchablepdf/
---
## ConvertToSearchablePdf() {#converttosearchablepdf}

Adds a searchable OCR text layer using the default recognition options.

```csharp
public bool ConvertToSearchablePdf()
```

### Return Value

The operation result. If there are no images in the document returns `false`

### Exceptions

| exception | condition |
| --- | --- |
| [MissingOptionalDependencyException](../../missingoptionaldependencyexception/) | Thrown when Aspose.OCR or one of its required runtime dependencies is unavailable. |

## Remarks

English is used as the recognition language and image flattening is disabled.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## ConvertToSearchablePdf(OcrSearchablePdfOptions) {#converttosearchablepdf_1}

Adds a searchable OCR text layer.

```csharp
public bool ConvertToSearchablePdf(OcrSearchablePdfOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | OcrSearchablePdfOptions | The options that specify the recognition language and whether images are flattened. |

### Return Value

The operation result. If there are no images in the document returns `false`

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *options* is `null`. |
| [MissingOptionalDependencyException](../../missingoptionaldependencyexception/) | Thrown when Aspose.OCR or one of its required runtime dependencies is unavailable. |
| ArgumentOutOfRangeException | Thrown when [`Language`](../../../aspose.pdf.ocr/ocrsearchablepdfoptions/language/) contains an undefined value. |

### See Also

* class [OcrSearchablePdfOptions](../../../aspose.pdf.ocr/ocrsearchablepdfoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


