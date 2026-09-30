---
title: "PdfXmpMetadata Class"
linktitle: "PdfXmpMetadata"
articleTitle: "PdfXmpMetadata"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.PdfXmpMetadata class. Class for manipulation with XMP metadata."
type: docs
weight: 520
url: "/net/aspose.pdf.facades/pdfxmpmetadata/"
keywords: "PdfXmpMetadata, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfXmpMetadata class

Class for manipulation with XMP metadata.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfXmpMetadata](./pdfxmpmetadata/#constructor)() | Constructor for PdfXmpMetadata. |
| [PdfXmpMetadata](./pdfxmpmetadata/#constructor_1)(Document) | Initializes new [`PdfXmpMetadata`](../../aspose.pdf.facades/pdfxmpmetadata/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Count](./count/) { get; } | Gets count if items in the collection. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [ExtensionFields](./extensionfields/) { get; } | Gets the dictionary of extension fields. |
| [IsFixedSize](./isfixedsize/) { get; } | Returns true is collection has fixed size. |
| [IsReadOnly](./isreadonly/) { get; } | Returns true if collection is read-only. |
| [IsSynchronized](./issynchronized/) { get; } | Returns true if collection is synchronized. |
| [Item](./item/) { get; set; } | Gets or sets value by key. (2 indexers) |
| [Keys](./keys/) { get; } | Gets keys from the dictionary. |
| [SyncRoot](./syncroot/) { get; } | Gets synchroniztion object of the collection. |
| [Values](./values/) { get; } | Gets the collection of values in dictionary. |

## Methods

| Name | Description |
| --- | --- |
| [Add](./add/)(KeyValuePair<string, XmpValue>) | Adds pair with key and value into the dictionary. |
| [Add](./add/)(DefaultMetadataProperties, XmpValue) | Adds value to XMP metadata. |
| [Add](./add/)(string, object) | Adds new element to the dictionary object. |
| [Add](./add/)(string, XmpValue) | Adds new element to the dictionary object. |
| [Add](./add/)(XmpPdfAExtensionObject, string, string, string) | Adds extension field into metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| [Clear](./clear/)() | Removes all elements from the object. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [Contains](./contains/)(DefaultMetadataProperties) | Checks if dictionary contains the specified property. |
| [Contains](./contains/)(KeyValuePair<string, XmpValue>) | Checks does specified key-value pair is contained in the dictionary. |
| [Contains](./contains/)(string) | Checks if dictionary contains the specified key. |
| [ContainsKey](./containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](./copyto/)(KeyValuePair<string, XmpValue>[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [GetEnumerator](./getenumerator/)() | Gets enumerator object of the dictionary. |
| [GetNamespaceURIByPrefix](./getnamespaceuribyprefix/)(string) | Gets namespace URI by prefix. |
| [GetPrefixByNamespaceURI](./getprefixbynamespaceuri/)(string) | Gets the prefix by namespace URI. |
| [GetXmpMetadata](./getxmpmetadata/)() | Get the XmpMetadata of the input pdf in a xml format. |
| [GetXmpMetadata](./getxmpmetadata/)(string) | Get a part of the XmpMetadata of the input pdf according to a meta name. |
| [RegisterNamespaceURI](./registernamespaceuri/)(string, string) | Registers the namespace URI. |
| [Remove](./remove/)(DefaultMetadataProperties) | Removes element with specified key. |
| [Remove](./remove/)(KeyValuePair<string, XmpValue>) | Removes key/value pair from the collection. |
| [Remove](./remove/)(string) | Removes key from the dictionary. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |
| [TryGetValue](./trygetvalue/)(string, out XmpValue) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

