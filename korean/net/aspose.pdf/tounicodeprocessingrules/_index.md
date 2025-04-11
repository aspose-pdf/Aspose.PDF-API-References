---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.ToUnicodeProcessingRules 클래스. 이 클래스는 Adobe Preflight 오류 "텍스트를 유니코드로 매핑할 수 없습니다"를 해결하는 데 사용할 수 있는 규칙을 설명합니다.
type: docs
weight: 11110
url: /ko/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules 클래스

이 클래스는 Adobe Preflight 오류 "텍스트를 유니코드로 매핑할 수 없습니다"를 해결하는 데 사용할 수 있는 규칙을 설명합니다.

```csharp
public class ToUnicodeProcessingRules
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | `ToUnicodeProcessingRules` 클래스의 새 인스턴스를 초기화합니다. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | CMap 이름에서 공백을 제거하는 옵션을 지정하여 `ToUnicodeProcessingRules` 클래스의 새 인스턴스를 초기화합니다. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | 지정된 옵션으로 `ToUnicodeProcessingRules` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | 일부 글꼴은 일부 텍스트 기호에 대한 유니코드 정보를 제공하지 않습니다. 이 정보의 부족은 "텍스트를 유니코드로 매핑할 수 없습니다"라는 오류를 발생시킵니다. 이 플래그를 사용하여 비연결 기호를 유니코드 "공백"(코드 32)에 매핑합니다. |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | 일부 글꼴은 이름에 공백이 있는 ToUnicode 문자 코드 맵을 가지고 있습니다. 이러한 공백은 유니코드 텍스트 매핑에서 오류를 발생시킬 수 있습니다. 이 플래그는 ToUnicode 문자 코드 맵의 이름에서 공백을 제거하도록 지시합니다. 기본값은 false입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)