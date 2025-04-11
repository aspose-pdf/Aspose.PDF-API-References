---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.SaveOptions 클래스. SaveOptions 유형은 개별 저장 옵션에 대한 추상화 수준을 보유합니다.
type: docs
weight: 9870
url: /ko/net/aspose.pdf/saveoptions/
---
## SaveOptions 클래스

SaveOptions 유형은 개별 저장 옵션에 대한 추상화 수준을 보유합니다.

```csharp
public abstract class SaveOptions
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | 글꼴 글리프가 aps 페이지를 준비하는 동안 캐시될지를 나타내는 부울 값을 가져오거나 설정합니다. PDF를 다른 형식으로 변환할 때 성능을 향상시키지만 메모리 소비를 증가시킵니다. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | 문서가 응답에 저장된 후 Response 객체가 닫힐지를 나타내는 부울 값을 가져오거나 설정합니다. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | 데이터 저장 형식. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | 생성된 경고를 처리하기 위한 콜백입니다. WarningHandler는 Continue 또는 Abort를 지정하는 ReturnAction 열거형 항목을 반환합니다. Continue는 기본 동작이며 Save 작업이 계속되지만, 사용자는 Abort를 반환할 수도 있으며, 이 경우 Save 작업은 중단되어야 합니다. |

### 참조

* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)