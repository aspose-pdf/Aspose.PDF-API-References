---
title: Class PdfXmpMetadata
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfXmpMetadata class. Class for manipulation with XMP metadata
type: docs
weight: 3100
url: /net/aspose.pdf.facades/pdfxmpmetadata/
---
## PdfXmpMetadata class

Class for manipulation with XMP metadata.

```csharp
public sealed class PdfXmpMetadata : SaveableFacade, IDictionary<string, XmpValue>
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor)() | Constructor for PdfXmpMetadata. |
| [PdfXmpMetadata](pdfxmpmetadata/#constructor_1)(Document) | Initializes new `PdfXmpMetadata` object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [Count](../../aspose.pdf.facades/pdfxmpmetadata/count/) { get; } | Gets count if items in the collection. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [ExtensionFields](../../aspose.pdf.facades/pdfxmpmetadata/extensionfields/) { get; } | Gets the dictionary of extension fields. |
| [IsFixedSize](../../aspose.pdf.facades/pdfxmpmetadata/isfixedsize/) { get; } | Returns true is collection has fixed size. |
| [IsReadOnly](../../aspose.pdf.facades/pdfxmpmetadata/isreadonly/) { get; } | Returns true if collection is read-only. |
| [IsSynchronized](../../aspose.pdf.facades/pdfxmpmetadata/issynchronized/) { get; } | Returns true if collection is synchronized. |
| [Item](../../aspose.pdf.facades/pdfxmpmetadata/item/) { get; set; } | Gets or sets value by key. (2 indexers) |
| [Keys](../../aspose.pdf.facades/pdfxmpmetadata/keys/) { get; } | Gets keys from the dictionary. |
| [SyncRoot](../../aspose.pdf.facades/pdfxmpmetadata/syncroot/) { get; } | Gets synchroniztion object of the collection. |
| [Values](../../aspose.pdf.facades/pdfxmpmetadata/values/) { get; } | Gets the collection of values in dictionary. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_2)(KeyValuePair&lt;string, XmpValue&gt;) | Adds pair with key and value into the dictionary. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add)(DefaultMetadataProperties, XmpValue) | Adds value to XMP metadata. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_4)(string, object) | Adds new element to the dictionary object. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_3)(string, XmpValue) | Adds new element to the dictionary object. |
| [Add](../../aspose.pdf.facades/pdfxmpmetadata/add/#add_1)(XmpPdfAExtensionObject, string, string, string) | Adds extension field into metadata. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| [Clear](../../aspose.pdf.facades/pdfxmpmetadata/clear/)() | Removes all elements from the object. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Disposes Aspose.Pdf.Document bound with a facade. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains)(DefaultMetadataProperties) | Checks if dictionary contains the specified property. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_1)(KeyValuePair&lt;string, XmpValue&gt;) | Checks does specified key-value pair is contained in the dictionary. |
| [Contains](../../aspose.pdf.facades/pdfxmpmetadata/contains/#contains_2)(string) | Checks if dictionary contains the specified key. |
| [ContainsKey](../../aspose.pdf.facades/pdfxmpmetadata/containskey/)(string) | Determines does this dictionary contasins specified key. |
| [CopyTo](../../aspose.pdf.facades/pdfxmpmetadata/copyto/)(KeyValuePair&lt;string, XmpValue&gt;[], int) |  |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [GetEnumerator](../../aspose.pdf.facades/pdfxmpmetadata/getenumerator/)() | Gets enumerator object of the dictionary. |
| [GetNamespaceURIByPrefix](../../aspose.pdf.facades/pdfxmpmetadata/getnamespaceuribyprefix/)(string) | Gets namespace URI by prefix. |
| [GetPrefixByNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/getprefixbynamespaceuri/)(string) | Gets the prefix by namespace URI. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata)() | Get the XmpMetadata of the input pdf in a xml format. |
| [GetXmpMetadata](../../aspose.pdf.facades/pdfxmpmetadata/getxmpmetadata/#getxmpmetadata_1)(string) | Get a part of the XmpMetadata of the input pdf according to a meta name. |
| [RegisterNamespaceURI](../../aspose.pdf.facades/pdfxmpmetadata/registernamespaceuri/)(string, string) | Registers the namespace URI. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_2)(DefaultMetadataProperties) | Removes element with specified key. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove)(KeyValuePair&lt;string, XmpValue&gt;) | Removes key/value pair from the collection. |
| [Remove](../../aspose.pdf.facades/pdfxmpmetadata/remove/#remove_1)(string) | Removes key from the dictionary. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Saves the PDF document to the specified stream. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Saves the PDF document to the specified file. |
| [TryGetValue](../../aspose.pdf.facades/pdfxmpmetadata/trygetvalue/)(string, out XmpValue) | Tries to find key in the dictionary and retreives value if found. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* class [XmpValue](../../aspose.pdf/xmpvalue/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


