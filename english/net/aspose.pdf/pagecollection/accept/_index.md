---
title: PageCollection.Accept
second_title: Aspose.PDF for .NET API Reference
description: PageCollection method. Accepts AnnotationSelector visitor object that provides functionality to work with annotations
type: docs
weight: 60
url: /net/aspose.pdf/pagecollection/accept/
---
## Accept(AnnotationSelector) {#accept}

Accepts [`AnnotationSelector`](../../../aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations.

```csharp
public void Accept(AnnotationSelector visitor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | AnnotationSelector | AnnotationSelector Visitor |

### See Also

* class [AnnotationSelector](../../../aspose.pdf.annotations/annotationselector/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Accept(ImagePlacementAbsorber) {#accept_1}

Accepts [`ImagePlacementAbsorber`](../../imageplacementabsorber/) visitor object that provides functionality to work with image placement objects.

```csharp
public void Accept(ImagePlacementAbsorber visitor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | ImagePlacementAbsorber | Image placement object. |

### See Also

* class [ImagePlacementAbsorber](../../imageplacementabsorber/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Accept(TextFragmentAbsorber) {#accept_4}

Accepts [`TextFragmentAbsorber`](../../../aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects.

```csharp
public void Accept(TextFragmentAbsorber visitor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | TextFragmentAbsorber | Text fragment absorber object. |

### See Also

* class [TextFragmentAbsorber](../../../aspose.pdf.text/textfragmentabsorber/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Accept(TextAbsorber) {#accept_3}

Accepts [`TextAbsorber`](../../../aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects.

```csharp
public void Accept(TextAbsorber visitor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | TextAbsorber | Text absorber object. |

### See Also

* class [TextAbsorber](../../../aspose.pdf.text/textabsorber/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Accept(OcrTextAbsorber) {#accept_2}

Accepts an [`OcrTextAbsorber`](../../../aspose.pdf.ocr/ocrtextabsorber/) that extracts plain text from these pages using OCR.

```csharp
public void Accept(OcrTextAbsorber visitor)
```

| Parameter | Type | Description |
| --- | --- | --- |
| visitor | OcrTextAbsorber | The OCR text absorber to apply to these pages. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Thrown when *visitor* is `null`. |

### See Also

* class [OcrTextAbsorber](../../../aspose.pdf.ocr/ocrtextabsorber/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


