---
title: "PdfContentEditor.GetViewerPreference"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 보기 기본 설정을 반환합니다"
type: docs
weight: 390
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/getviewerpreference/
---
## PdfContentEditor.GetViewerPreference method

뷰 기본 설정을 반환합니다.

```csharp
public int GetViewerPreference()
```

### 반환 값

ViewerPrefernece 플래그 집합을 반환합니다

## 예제

```csharp
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf("example.pdf");
int prefValue = editor.GetViewerPreference();
if ((prefValue & ViewerPreference.PageModeUseOutline) != 0)
{ // ... }
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


