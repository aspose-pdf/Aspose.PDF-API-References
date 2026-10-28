---
title: "FontRepository.OpenFont"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "FontRepository 메서드. 지정된 폰트 스트림으로 폰트를 엽니다"
type: docs
weight: 60
url: /ko/net/aspose.pdf.text/fontrepository/openfont/
---
## OpenFont(Stream, FontTypes) {#openfont}

지정된 폰트 스트림으로 폰트를 엽니다.

```csharp
public static Font OpenFont(Stream fontStream, FontTypes fontType)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontStream | Stream | 폰트 스트림. |
| fontType | FontTypes | 폰트 유형 값. |

### 반환 값

폰트 객체.

## 예제

예제는 폰트를 열고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 열기
using (FileStream fontStream = File.OpenRead(@"C:\WINDOWS\Fonts\arial.ttf"))
{
    Font font = FontRepository.OpenFont(fontStream, , FontTypes.TTF);

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
}
```

### 또 보기

* class [Font](../../font/)
* enum [FontTypes](../../fonttypes/)
* class [FontRepository](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## OpenFont(string) {#openfont_1}

지정된 폰트 파일 경로로 폰트를 엽니다.

```csharp
public static Font OpenFont(string fontFilePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFilePath | String | 폰트 파일 경로. |

### 반환 값

폰트 객체.

## 예제

예제는 폰트를 열고 첫 페이지 텍스트의 폰트를 교체하는 방법을 보여줍니다.

```csharp
// 폰트 열기
Font font = FontRepository.OpenFont(@"C:\WINDOWS\Fonts\arial.ttf");

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

## OpenFont(string, string) {#openfont_2}

지정된 폰트 파일 경로와 메트릭스 파일 경로로 폰트를 엽니다.

```csharp
public static Font OpenFont(string fontFilePath, string metricsFilePath)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| fontFilePath | String | 폰트 파일 경로. |
| metricsFilePath | String | 폰트 메트릭 파일 경로. |

### 반환 값

폰트 객체.

## 예제

이 예제는 메트릭이 포함된 Type1 글꼴을 열고 첫 페이지의 텍스트 글꼴을 교체하는 방법을 보여줍니다.

```csharp
// 폰트 열기
Font font = FontRepository.OpenFont("courier.pfb", "courier.afm");

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


