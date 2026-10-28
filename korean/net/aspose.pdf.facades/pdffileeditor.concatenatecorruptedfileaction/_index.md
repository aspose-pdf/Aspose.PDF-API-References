---
title: "열거형 PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction 열거형. 병합 과정에서 손상된 파일을 만나면 수행되는 동작"
type: docs
weight: 4590
url: /ko/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

병합 과정에서 손상된 파일을 만나면 수행되는 동작.

```csharp
public enum ConcatenateCorruptedFileAction
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| StopWithError | `0` | 손상된 파일을 만나면, 병합 과정을 중지하고 오류를 반환합니다. |
| ConcatenateIgnoringCorrupted | `1` | 손상된 파일을 만나도 병합을 중지하지 않고 손상된 파일을 처리하지 않습니다. 손상된 파일 목록은 Failures 속성을 통해 접근할 수 있습니다. |
| ConcatenateIgnoringCorruptedObjects | `2` | 원본 *document*에서 손상된 객체를 만나면, 프로세스는 중지되지 않고 손상된 객체만 무시됩니다. |

### 또 보기

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


