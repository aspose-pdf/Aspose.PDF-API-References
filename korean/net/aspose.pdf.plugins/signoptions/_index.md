---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Plugins.SignOptions 클래스. 서명 플러그인을 위한 서명 옵션을 나타냅니다.
type: docs
weight: 9250
url: /ko/net/aspose.pdf.plugins/signoptions/
---
## SignOptions 클래스

[`Signature`](../signature/) 플러그인을 위한 서명 옵션을 나타냅니다.

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | 기본 옵션으로 `SignOptions` 객체의 새 인스턴스를 초기화합니다. |
| [SignOptions](signoptions/#constructor_1)(string, string) | 기본 옵션으로 `SignOptions` 객체의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | 작업이 완료된 후 입력 스트림을 닫습니다. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | 작업이 완료된 후 출력 스트림을 닫습니다. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | 서명의 연락처입니다. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | OrganizerOptions 플러그인 데이터 컬렉션을 반환합니다. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | 서명의 위치입니다. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | 기존 서명 필드의 이름입니다. 새 필드를 만들려면 Null로 설정합니다. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | 저장 작업 결과를 위한 추가 대상의 컬렉션을 가져옵니다. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | 서명이 이루어진 페이지 번호입니다. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | 서명의 이유입니다. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | 서명의 사각형입니다. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | 서명의 가시성입니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | PdfOrganizer 플러그인 데이터 컬렉션에 새 데이터 소스를 추가합니다. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | PdfOrganizer 플러그인 데이터 컬렉션에 새 데이터 소스를 추가합니다. |

### 참조

* 클래스 [OrganizerBaseOptions](../organizerbaseoptions/)
* 네임스페이스 [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* 어셈블리 [Aspose.PDF](../../)