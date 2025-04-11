---
title: PdfContentEditor.ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: PdfContentEditor 메서드. 지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. 교체된 텍스트에 대해 TextState 객체의 글꼴 패밀리 색상을 지정할 수 있습니다.
type: docs
weight: 450
url: /ko/net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

지정된 페이지의 PDF 파일에서 텍스트를 교체합니다. [`TextState`](../../../aspose.pdf.text/textstate/) 객체(글꼴 패밀리, 색상)를 교체된 텍스트에 대해 지정할 수 있습니다.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체할 문자열입니다. |
| thePage | Int32 | 페이지 번호(0은 "모든 페이지"를 의미합니다). |
| destString | String | 교체된 문자열입니다. |
| textState | TextState | 텍스트 상태(텍스트 색상, 글꼴 등). |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 PDF 문서의 첫 페이지에서 텍스트를 교체하고 새로운 텍스트에 대한 [`TextState`](../../../aspose.pdf.text/textstate/) 텍스트 속성을 설정하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### 참조

* 클래스 [TextState](../../../aspose.pdf.text/textstate/)
* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

PDF 파일에서 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체할 문자열입니다. |
| destString | String | 교체 문자열입니다. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 PDF 문서에서 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

지정된 페이지의 PDF 파일에서 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체할 문자열입니다. |
| thePage | Int32 | 페이지 번호(모든 페이지는 0입니다) |
| destString | String | 교체 문자열입니다. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 지정된 페이지에서 PDF 문서의 텍스트를 교체하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

지정된 [`TextState`](../../../aspose.pdf.text/textstate/) 객체를 사용하여 PDF 파일에서 텍스트를 교체합니다.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체할 문자열입니다. |
| destString | String | 교체 문자열입니다. |
| textState | TextState | 텍스트 상태(텍스트 색상, 글꼴 등). |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 텍스트를 교체하고 새로운 텍스트에 대한 [`TextState`](../../../aspose.pdf.text/textstate/) 텍스트 속성을 설정하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### 참조

* 클래스 [TextState](../../../aspose.pdf.text/textstate/)
* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

PDF 파일에서 텍스트를 교체하고 글꼴 크기를 설정합니다.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| srcString | String | 교체할 문자열입니다. |
| destString | String | 교체 문자열입니다. |
| fontSize | Int32 | 글꼴 크기입니다. |

### 반환 값

교체가 이루어지면 true를 반환합니다.

## 예제

이 예제는 텍스트를 교체하고 새로운 텍스트에 대한 글꼴 크기를 설정하는 방법을 보여줍니다.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### 참조

* 클래스 [PdfContentEditor](../)
* 네임스페이스 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 어셈블리 [Aspose.PDF](../../../)