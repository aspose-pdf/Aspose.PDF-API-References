---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
linktitle: "TreatTargetFileNameAsDirectory"
articleTitle: "TreatTargetFileNameAsDirectory"
second_title: "Aspose.PDF for .NET"
description: "This options defines whether will be created target directory (if absent yet) with same name as requested output file instead of requested output file itself..."
type: docs
weight: 30
url: "/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/"
product_version: "26.9.0"
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

This options defines whether will be created target directory
 (if absent yet) with same name as requested output file 
 instead of requested output file itself.
 It so, that directory will contain all output SVG-images of pages (like described below).
 If no, output files of pages other then first one will be created exactly in requested directory
 as main output file, but will contain in file name suffix _[2...n], that
 is defined by page number, f.e. if You define output file "C:\AsposeTests\output.svg"
 and output will contain several svg-files of pages,
 then files of pages will be created also in directory "C:\AsposeTests\" and have names 'output.svg', 'output_2.svg', 'output_3.svg' etc.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### See Also

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

