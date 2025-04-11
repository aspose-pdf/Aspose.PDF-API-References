---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionField 클래스. 이 스키마는 구조화된 유형의 필드를 설명합니다. PDF/A 속성 값 유형 스키마와 매우 유사하지만 속성이 아닌 구조 내의 필드를 정의합니다. 스키마 네임스페이스 URI http//www.aiim.org/pdfa/ns/field 필수 스키마 네임스페이스 접두사 pdfaField
type: docs
weight: 11440
url: /ko/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField 클래스

이 스키마는 구조화된 유형의 필드를 설명합니다. PDF/A 속성 값 유형 스키마와 매우 유사하지만 속성이 아닌 구조 내의 필드를 정의합니다. 스키마 네임스페이스 URI: http://www.aiim.org/pdfa/ns/field# 필수 스키마 네임스페이스 접두사: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 설명을 가져옵니다. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | 필드 이름. 필드 이름은 유효한 XML 요소 이름이어야 합니다. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 값을 가져오거나 설정합니다. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | 필드 값 유형, XMP 사양 2004에서 가져오거나 내장된 PDF/A 값 유형 확장 스키마. 미리 정의된 XMP 유형 이름 또는 사용자 정의 유형의 이름. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | XML 트리에서 필드를 나타내는 XML 요소 목록을 반환합니다. |

### 참조

* 클래스 [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)