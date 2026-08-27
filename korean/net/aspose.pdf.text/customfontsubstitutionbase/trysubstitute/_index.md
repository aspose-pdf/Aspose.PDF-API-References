---
title: "CustomFontSubstitutionBase.TrySubstitute"
second_title: "Aspose.PDF 용 .NET API 참조"
description: "CustomFontSubstitutionBase 메서드. 원본 글꼴을 다른 글꼴로 대체합니다."
type: docs
weight: 20
url: /ko/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## CustomFontSubstitutionBase.TrySubstitute method

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

대체가 성공한 경우 true.

## 비고

CustomFontSubstitutionBase 클래스는 사용자 정의 글꼴 대체 로직을 구현하기 위해 상속되어야 합니다. TrySubstitute 메서드는 적절히 오버라이드되어야 합니다: 대체가 필요할 경우 true를 반환해야 합니다. substitutionFont는 유효한 Font 객체로 설정되어야 합니다. 대체가 필요하지 않을 경우 false를 반환해야 합니다. substitutionFont는 null로 설정될 수 있습니다.

### 또 보기

* class [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* class [Font](../../font/)
* class [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


