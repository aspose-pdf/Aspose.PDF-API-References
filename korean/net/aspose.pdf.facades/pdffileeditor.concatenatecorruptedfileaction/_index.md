---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction enum. 손상된 파일이 연결 과정에서 발견되었을 때 수행되는 작업
type: docs
weight: 4470
url: /ko/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction 열거형

손상된 파일이 연결 과정에서 발견되었을 때 수행되는 작업입니다.

```csharp
public enum ConcatenateCorruptedFileAction
```

### 값들

| 이름 | 값 | 설명 |
| --- | --- | --- |
| StopWithError | `0` | 손상된 파일이 발견되면 연결 과정을 중단하고 오류를 반환합니다. |
| ConcatenateIgnoringCorrupted | `1` | 손상된 파일이 발견되면 연결을 중단하지 않고 손상된 파일은 처리하지 않습니다. 손상된 파일 목록은 Failures 속성에서 확인할 수 있습니다. |
| ConcatenateIgnoringCorruptedObjects | `2` | 원본 문서에서 손상된 객체가 발견되면 처리는 중단되지 않고 손상된 객체만 무시됩니다. |

### 참조

* 클래스 [PdfFileEditor](../pdffileeditor/)
* 네임스페이스 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../)