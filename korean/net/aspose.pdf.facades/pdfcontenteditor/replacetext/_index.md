---
title: "PdfContentEditor.ReplaceText"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "PdfContentEditor 메서드. 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. TextState 객체의 글꼴 패밀리와 색상을 지정하여 교체할 텍스트를 설정할 수 있습니다."
type: docs
weight: 450
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [`TextState`](../../../aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 지정하여 교체할 텍스트를 설정할 수 있습니다.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체될 문자열입니다. |
| thePage | Int32 | 페이지 번호 (0은 "전체 페이지"를 의미합니다). |
| destString | String | 대체된 문자열. |
| textState | TextState | 텍스트 상태 (텍스트 색상, 글꼴 등). |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 PDF 문서의 첫 번째 페이지에서 텍스트를 교체하고 새 텍스트에 대해 [`TextState`](../../../aspose.pdf.text/textstate/) 텍스트 속성을 설정하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 글꼴을 생성하고 포함하도록 표시합니다.
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 텍스트를 편집하기 위해 PdfContentEditor 객체를 생성합니다.
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState 객체를 생성합니다.
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// 지정된 글꼴로 텍스트를 변경합니다.
editor.ReplaceText("hello world", 1, "hi world", textState);

// 문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDF 파일의 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체될 문자열입니다. |
| destString | String | 문자열을 교체합니다. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 PDF 문서에서 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 편집하기 위해 PdfContentEditor 객체를 생성합니다.
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 텍스트를 변경 
editor.ReplaceText("hello world", "hi world");

// 문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

지정된 페이지의 PDF 파일에서 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체될 문자열. |
| thePage | Int32 | 페이지 번호 (전체 페이지는 0) |
| destString | String | 문자열을 교체합니다. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 지정된 페이지에서 PDF 문서의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 텍스트를 편집하기 위해 PdfContentEditor 객체를 생성합니다.
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 텍스트를 변경 
editor.ReplaceText("hello world", 1, "hi world");

// 문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

지정된 [`TextState`](../../../aspose.pdf.text/textstate/) 객체를 사용하여 PDF 파일의 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체될 문자열 |
| destString | String | 문자열 교체 |
| textState | TextState | 텍스트 상태 (텍스트 색상, 글꼴 등) |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 텍스트를 교체하고 새 텍스트에 대해 [`TextState`](../../../aspose.pdf.text/textstate/) 텍스트 속성을 설정하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 글꼴을 생성하고 포함하도록 표시합니다.
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 텍스트를 편집하기 위해 PdfContentEditor 객체를 생성합니다.
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// textState 객체를 생성합니다.
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// 지정된 글꼴로 텍스트를 변경합니다.
editor.ReplaceText("hello world", "hi world", textState);

// 문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [TextState](../../../aspose.pdf.text/textstate/)
* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF 파일의 텍스트를 교체하고 글꼴 크기를 설정합니다.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체될 문자열. |
| destString | String | 문자열을 교체합니다. |
| fontSize | Int32 | 글꼴 크기. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 텍스트를 교체하고 새 텍스트에 대한 글꼴 크기를 설정하는 방법을 보여줍니다.

```csharp
// 문서 열기
Document doc = new Document(inFile);

// 글꼴을 생성하고 포함하도록 표시합니다.
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// 텍스트를 편집하기 위해 PdfContentEditor 객체를 생성합니다.
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// 지정된 글꼴로 텍스트를 변경합니다.
editor.ReplaceText("hello world", "hi world", 14);

// 문서를 저장합니다.
doc.Save(outFile);
```

### 또 보기

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


