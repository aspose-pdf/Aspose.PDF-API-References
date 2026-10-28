---
title: "PdfPageEditor.Save"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfPageEditor 메서드. 변경된 문서를 파일에 저장합니다."
type: docs
weight: 180
url: /ko/net/aspose.pdf.facades/pdfpageeditor/save/
---
## Save(string) {#save_1}

변경된 문서를 파일에 저장합니다.

```csharp
public override void Save(string outputFile)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputFile | String | 문서가 저장될 파일 경로. |

## 예제

다음 샘플은 변경된 PDF 문서를 저장하는 방법을 보여줍니다

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 또 보기

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## Save(Stream) {#save}

변경된 문서를 스트림에 저장합니다.

```csharp
public override void Save(Stream outputStream)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| outputStream | Stream | 변경된 PDF 문서가 저장될 스트림. |

## 예제

다음 샘플은 변경된 PDF 문서를 스트림에 저장하는 방법을 보여줍니다.

```csharp
PdfPageEditor editor = new PdfPageEditor();
editor.BindPdf("sample.pdf");
editor.Zoom = 0.5f;
editor.Save("newdocument.pdf");
```

### 또 보기

* class [PdfPageEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


