---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions property. With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1based numbers. I.e. valid numbers of pages must be taken from range 1...NumberOfPagesInConvertedDocument Order of appearing of pages in this list does not affect their order in result HTML pages  in result pages allways will go in order in which they are present in source PDF. If this list is null as it is by default all pages will be converted. If any page number of this list will go out of range of present pages1amountOfPagesInDocument exception will be thrown
type: docs
weight: 70
url: /net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### See Also

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


