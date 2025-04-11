---
title: PdfFileEditor.CorruptedItems
second_title: Aspose.PDF for .NET API Reference
description: PdfFileEditor プロパティ。連結が実行されたときに遭遇した問題の配列。Concatenate 関数に渡された各破損したドキュメントに対して新しい CorruptedItem エントリが作成されます。このプロパティは、CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。
type: docs
weight: 90
url: /ja/net/aspose.pdf.facades/pdffileeditor/corrupteditems/
---
## PdfFileEditor.CorruptedItems プロパティ

連結が実行されたときに遭遇した問題の配列。Concatenate() 関数に渡された各破損したドキュメントに対して新しい CorruptedItem エントリが作成されます。このプロパティは、CorruptedFileAction が ConcatenateIgnoringCorrupted の場合にのみ使用できます。

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

### 参照

* クラス [CorruptedItem](../../pdffileeditor.corrupteditem/)
* クラス [PdfFileEditor](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)