---
title: "PdfFileEditor.CorruptedItems"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfFileEditor 속성. 연결이 수행될 때 발생한 문제들의 배열입니다. Concatenate 함수에 전달된 각 손상된 문서마다 새로운 CorruptedItem 항목이 생성됩니다. 이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted인 경우에만 사용할 수 있습니다."
type: docs
weight: 90
url: /ko/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems property

연결이 수행될 때 발생한 문제들의 배열입니다. Concatenate() 함수에 전달된 각 손상된 문서마다 새로운 CorruptedItem 항목이 생성됩니다. 이 속성은 CorruptedFileAction이 ConcatenateIgnoringCorrupted인 경우에만 사용할 수 있습니다.

```csharp
//문서를 연결하고 손상된 문서에 대한 정보를 표시합니다.
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

### 또 보기

* class [CorruptedItem](../../pdffileeditor.corrupteditem/)
* class [PdfFileEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


