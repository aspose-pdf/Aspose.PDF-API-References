---
title: FontRepository.FindFont
second_title: Aspose.PDF for .NET API Reference
description: FontRepository 메서드. 지정된 글꼴 이름으로 글꼴을 검색하고 반환합니다.
type: docs
weight: 40
url: /ko/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

지정된 글꼴 이름으로 글꼴을 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 글꼴 이름. |

### 반환 값

글꼴 객체.

## 예제

이 예제는 글꼴을 찾고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, bool) {#findfont_3}

지정된 글꼴 이름으로 글꼴을 검색하고 대소문자 구분을 무시하거나 존중합니다.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 글꼴 이름. |
| ignoreCase | Boolean | 대소문자 구분 |

### 반환 값

글꼴 객체.

## 예제

이 예제는 글꼴을 찾고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

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

## FindFont(string, FontStyles) {#findfont_1}

지정된 글꼴 이름과 글꼴 스타일로 글꼴을 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | String | 글꼴 패밀리 이름. |
| stl | FontStyles | 글꼴 스타일 값. |

### 반환 값

검색 요청 매개변수에 해당하는 글꼴 객체.

## 예제

이 예제는 글꼴을 찾고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

지정된 글꼴 이름과 글꼴 스타일로 글꼴을 검색하고 대소문자 구분을 무시하거나 존중합니다.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | String | 글꼴 패밀리 이름. |
| stl | FontStyles | 글꼴 스타일 값. |
| ignoreCase | Boolean | 대소문자 구분 |

### 반환 값

검색 요청 매개변수에 해당하는 글꼴 객체.

## 예제

이 예제는 글꼴을 찾고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### 참조

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)