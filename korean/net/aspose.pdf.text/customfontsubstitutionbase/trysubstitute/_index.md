---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: CustomFontSubstitutionBase 메서드. 원본 글꼴을 다른 글꼴로 대체합니다.
type: docs
weight: 20
url: /ko/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute 메서드

원본 글꼴을 다른 글꼴로 대체합니다.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | 원본 글꼴 사양. |
| substitutionFont | Font& | 대체 글꼴. |

### 반환 값

대체가 성공한 경우 true를 반환합니다.

## 비고

CustomFontSubstitutionBase 클래스는 사용자 정의 글꼴 대체 논리를 구현하기 위해 상속되어야 합니다. TrySubstitute 메서드는 적절하게 재정의되어야 합니다: 대체가 필요한 경우 true를 반환해야 합니다. substitutionFont는 유효한 Font 객체로 설정되어야 합니다. 대체가 필요하지 않은 경우 false를 반환해야 합니다. substitutionFont는 null로 설정될 수 있습니다.

### 참조

* 클래스 [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* 클래스 [Font](../../font/)
* 클래스 [CustomFontSubstitutionBase](../)
* 네임스페이스 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* 어셈블리 [Aspose.PDF](../../../)