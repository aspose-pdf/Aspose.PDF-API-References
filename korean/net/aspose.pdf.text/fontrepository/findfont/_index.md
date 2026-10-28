---
title: "FontRepository.FindFont"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FontRepository 메서드. 지정된 폰트 이름으로 폰트를 검색하고 반환합니다"
type: docs
weight: 40
url: /ko/net/aspose.pdf.text/fontrepository/findfont/
---
## FindFont(string) {#findfont}

지정된 폰트 이름으로 폰트를 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontName)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 폰트 이름. |

### 반환 값

폰트 객체.

## 예제

이 예제는 폰트를 찾고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 찾기
Font font = FontRepository.FindFont("Arial");

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, bool) {#findfont_3}

대소문자 구분을 무시하거나 존중하여 지정된 폰트 이름으로 폰트를 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontName, bool ignoreCase)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontName | String | 폰트 이름. |
| ignoreCase | Boolean | 대소문자 구분 |

### 반환 값

폰트 객체.

## 예제

이 예제는 폰트를 찾고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 찾기
Font font = FontRepository.FindFont("Arial");

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// \"hello world\" 텍스트 발생을 모두 찾기 위해 TextFragmentAbsorber 객체를 생성합니다.
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [Font](../../font/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles) {#findfont_1}

지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | String | 폰트 패밀리 이름. |
| stl | FontStyles | 폰트 스타일 값. |

### 반환 값

검색 요청 매개변수에 해당하는 폰트 객체.

## 예제

이 예제는 폰트를 찾고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 찾기
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 모든 "hello world" 텍스트 발생을 찾기 위해 TextFragmentAbsorber 객체를 생성합니다
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## FindFont(string, FontStyles, bool) {#findfont_2}

대소문자 구분을 무시하거나 존중하여 지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다.

```csharp
public static Font FindFont(string fontFamilyName, FontStyles stl, bool ignoreCase)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFamilyName | String | 폰트 패밀리 이름. |
| stl | FontStyles | 폰트 스타일 값. |
| ignoreCase | Boolean | 대소문자 구분 |

### 반환 값

검색 요청 매개변수에 해당하는 폰트 객체.

## 예제

이 예제는 폰트를 찾고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 찾기
Font font = FontRepository.FindFont("Arial", FontStyle.Italic);

// 문서 열기
Document doc = new Document(@"D:\Tests\input.pdf");

// 모든 "hello world" 텍스트 발생을 찾기 위해 TextFragmentAbsorber 객체를 생성합니다
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// 첫 번째 페이지에 대해 흡수기를 적용합니다.
doc.Pages[1].Accept(absorber);

// 첫 번째 텍스트 발생의 폰트를 변경합니다
absorber.TextFragments[1].TextState.Font = font;

// 문서 저장
doc.Save(@"D:\Tests\output.pdf"); 
```

### 또 보기

* class [Font](../../font/)
* enum [FontStyles](../../fontstyles/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


