---
title: "클래스 ToUnicodeProcessingRules"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "Aspose.Pdf.ToUnicodeProcessingRules 클래스. 이 클래스는 Adobe Preflight 오류 \"Text cannot be mapped to Unicode\"를 해결하는 데 사용할 수 있는 규칙을 설명합니다."
type: docs
weight: 11300
url: /ko/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

이 클래스는 Adobe Preflight 오류 "Text cannot be mapped to Unicode"를 해결하는 데 사용할 수 있는 규칙을 설명합니다.

```csharp
public class ToUnicodeProcessingRules
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | 새 `ToUnicodeProcessingRules` 클래스 인스턴스를 초기화합니다. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | CMap 이름에서 공백을 제거하는 지정된 옵션을 사용하여 새 `ToUnicodeProcessingRules` 클래스 인스턴스를 초기화합니다. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 지정된 옵션으로 새 `ToUnicodeProcessingRules` 클래스 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 일부 글꼴은 특정 텍스트 기호에 대한 유니코드 정보를 제공하지 않습니다. 이러한 정보 부족은 "Text cannot be mapped to Unicode" 오류를 발생시킵니다. 이 플래그를 사용하여 연결되지 않은 기호를 유니코드 "space"(코드 32)로 매핑합니다. |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 일부 글꼴은 이름에 공백이 포함된 ToUnicode 문자 코드 맵을 가지고 있습니다. 이러한 공백은 유니코드 텍스트 매핑 오류를 일으킬 수 있습니다. 이 플래그는 ToUnicode 문자 코드 맵 이름에서 공백을 제거하도록 지정합니다. 기본값은 false입니다. |

### 또 보기

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


