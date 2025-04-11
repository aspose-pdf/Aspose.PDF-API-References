---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor 속성. 연결이 수행될 때 발생한 문제의 배열. Concatenate 함수에 전달된 각 손상된 문서에 대해 새로운 CorruptedItem 항목이 생성됩니다. 이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted일 때만 사용할 수 있습니다.
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems 속성

연결이 수행될 때 발생한 문제의 배열. Concatenate() 함수에 전달된 각 손상된 문서에 대해 새로운 CorruptedItem 항목이 생성됩니다. 이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted일 때만 사용할 수 있습니다.

```csharp
//concatenate documents and show information about corrupted documents
PdfFileEditor pfe = new PdfFileEditor();
pfe.CorruptedFileAction = PdfFileEditor.ConcatenateCorruptedFileActions.ConcatenateIgnoringCorrupted;
if (pfe.CorruptedItems.Length >0)
{
  foreach(PdfFileEditor.CorruptedItem item in pfe.CorruptedItems)
  {
     Console.WriteLine(item.Index + " reason: " + item.Exception);
  }
}
```

```csharp
public CorruptedItem[] CorruptedItems { get; }
```

### 참조

* 클래스 [CorruptedItem](../../pdffileeditor.corrupteditem/)
* 클래스 [PdfFileEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)