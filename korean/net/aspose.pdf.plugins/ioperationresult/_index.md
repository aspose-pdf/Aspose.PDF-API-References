---
title: Interface IOperationResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.IOperationResult 인터페이스. 구체적인 플러그인 작업 결과가 구현해야 하는 공통 메서드를 정의하는 일반 작업 결과 인터페이스
type: docs
weight: 8850
url: /ko/net/aspose.pdf.plugins/ioperationresult/
---
## IOperationResult 인터페이스

구체적인 플러그인 작업 결과가 구현해야 하는 공통 메서드를 정의하는 일반 작업 결과 인터페이스입니다.

```csharp
public interface IOperationResult
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [Data](../../aspose.pdf.plugins/ioperationresult/data/) { get; } | 원시 데이터를 가져옵니다. |
| [IsFile](../../aspose.pdf.plugins/ioperationresult/isfile/) { get; } | 결과가 출력 파일에 대한 경로인지 여부를 나타냅니다. |
| [IsStream](../../aspose.pdf.plugins/ioperationresult/isstream/) { get; } | 결과가 출력 스트림인지 여부를 나타냅니다. |
| [IsString](../../aspose.pdf.plugins/ioperationresult/isstring/) { get; } | 결과가 텍스트 문자열인지 여부를 나타냅니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [ToFile](../../aspose.pdf.plugins/ioperationresult/tofile/)() | 결과를 파일로 변환하려고 시도합니다. |
| [ToStream](../../aspose.pdf.plugins/ioperationresult/tostream/)() | 결과를 스트림 객체로 변환하려고 시도합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)