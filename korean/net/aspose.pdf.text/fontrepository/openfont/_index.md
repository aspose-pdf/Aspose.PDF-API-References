---
title: FontRepository.OpenFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository 메서드. 지정된 글꼴 스트림으로 글꼴을 엽니다.
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

지정된 글꼴 스트림으로 글꼴을 엽니다.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontStream | Stream | 글꼴 스트림. |
| fontType | FontTypes | 글꼴 유형 값. |

### 반환 값

글꼴 객체.

## 예제

이 예제는 글꼴을 열고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Open font
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

    // Open document
    Document doc = new Document(@"D:\Tests\input.pdf");

    // Create TextFragmentAbsorber object to find all "hello world" text occurrences
    TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

    // Accept the absorber for first page
    doc.Pages[1].Accept(absorber);

    // Change font of the first text occurrence
    absorber.TextFragments[1].TextState.Font = font;

    // Save document
    doc.Save(@"D:\Tests\output.pdf"); 
}
```

### 참조

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

지정된 글꼴 파일 경로로 글꼴을 엽니다.

```csharp
public static Font OpenFont(string fontFilePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFilePath | String | 글꼴 파일 경로. |

### 반환 값

글꼴 객체.

## 예제

이 예제는 글꼴을 열고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Open font
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string, string) {#openfont_2}

지정된 글꼴 파일 경로와 메트릭스 파일 경로로 글꼴을 엽니다.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFilePath | String | 글꼴 파일 경로. |
| metricsFilePath | String | 글꼴 메트릭스 파일 경로. |

### 반환 값

글꼴 객체.

## 예제

이 예제는 메트릭스와 함께 Type1 글꼴을 열고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Open font
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)