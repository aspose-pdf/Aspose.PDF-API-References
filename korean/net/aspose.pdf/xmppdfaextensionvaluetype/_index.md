---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XmpPdfAExtensionValueType 클래스. PDF/A ValueType 스키마는 XMP 2004 사양에 정의되지 않은 모든 속성 값 유형에 필요합니다. 즉, 다음 목록에 없는 값 유형에 대해 필요합니다 - 배열 유형（이들은 하나 이상의 필드를 포함할 수 있는 컨테이너 유형입니다） Alt, Bag, Seq - 기본 값 유형 Boolean, （열림 및 닫힘） Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - 미디어 관리 값 유형 AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - 기본 작업/워크플로우 값 유형 Job - EXIF 스키마 값 유형 Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational 스키마 네임스페이스 URI http//www.aiim.org/pdfa/ns/type# 필수 스키마 네임스페이스 접두사 pdfaType
type: docs
weight: 11490
url: /ko/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType 클래스

PDF/A ValueType 스키마는 XMP 2004 사양에 정의되지 않은 모든 속성 값 유형에 필요합니다. 즉, 다음 목록에 없는 값 유형에 대해 필요합니다: - 배열 유형(이들은 하나 이상의 필드를 포함할 수 있는 컨테이너 유형입니다): Alt, Bag, Seq - 기본 값 유형: Boolean, (열림 및 닫힘) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - 미디어 관리 값 유형: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - 기본 작업/워크플로우 값 유형: Job - EXIF 스키마 값 유형: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational 스키마 네임스페이스 URI: http://www.aiim.org/pdfa/ns/type# 필수 스키마 네임스페이스 접두사: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | 새 객체를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | 설명을 가져옵니다. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | 필드 목록을 가져옵니다. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | 네임스페이스 URI를 가져옵니다. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | 접두사를 가져옵니다. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | 값 유형을 가져옵니다. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | 값을 가져오거나 설정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | 새 필드를 추가합니다. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | 필드 범위를 추가합니다. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | 모든 필드를 지웁니다. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | XML 트리에서 값 유형을 나타내는 XML 요소 목록을 반환합니다. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | 필드 목록에서 필드를 제거합니다. |

### 참조

* 클래스 [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)