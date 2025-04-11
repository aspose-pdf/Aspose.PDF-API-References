---
title: Class Tool
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.AI.Tool 클래스. 모델에 의해 호출될 수 있는 도구를 나타냅니다.
type: docs
weight: 1190
url: /ko/net/aspose.pdf.ai/tool/
---
## 도구 클래스

모델에 의해 호출될 수 있는 도구를 나타냅니다.

```csharp
public class Tool
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Tool](tool/#constructor)() | `Tool` 클래스의 새 인스턴스를 초기화합니다. |
| [Tool](tool/#constructor_1)(Function) | 지정된 함수로 `Tool` 클래스의 새 인스턴스를 초기화합니다. |
| [Tool](tool/#constructor_2)(string) | 지정된 도구 유형으로 `Tool` 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| static [CodeInterpreter](../../aspose.pdf.ai/tool/codeinterpreter/) { get; } | 코드 인터프리터를 나타내는 도구 인스턴스를 가져옵니다. |
| static [FileSearch](../../aspose.pdf.ai/tool/filesearch/) { get; } | 파일 검색 도구를 나타내는 도구 인스턴스를 가져옵니다. |
| [ToolFunction](../../aspose.pdf.ai/tool/toolfunction/) { get; set; } | 모델이 호출할 수 있는 함수를 가져오거나 설정합니다. |
| [ToolType](../../aspose.pdf.ai/tool/tooltype/) { get; set; } | 도구의 유형을 가져오거나 설정합니다. 현재는 함수만 지원됩니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [Function](../../aspose.pdf.ai/tool/function/)(Function) | 지정된 함수로 새 도구 인스턴스를 생성합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* 어셈블리 [Aspose.PDF](../../)