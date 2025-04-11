---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontSavingModes 열거형. 저장된 PDF에서 참조된 글꼴을 저장하는 데 사용할 수 있는 모드를 열거합니다.
type: docs
weight: 5630
url: /ko/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes 열거형

저장된 PDF에서 참조된 글꼴을 저장하는 데 사용할 수 있는 모드를 열거합니다.

```csharp
public enum FontSavingModes
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | 모든 참조된 글꼴이 WOFF 글꼴로 저장되고 참조됩니다. |
| AlwaysSaveAsTTF | `1` | 모든 참조된 글꼴이 TTF 글꼴로 저장되고 참조됩니다. |
| AlwaysSaveAsEOT | `2` | 모든 참조된 글꼴이 EOT 글꼴로 저장되고 참조됩니다. |
| SaveInAllFormats | `3` | 모든 참조된 글꼴이 3개의 독립 파일(EOT, TTH, WOFF)로 저장되고(CSS에서 참조됨) 저장됩니다. 출력 데이터의 크기가 증가하지만 대다수의 웹 브라우저에 적합한 출력을 만듭니다. |
| DontSave | `4` | 모든 참조된 글꼴이 저장되지 않습니다. |

### 참조

* 클래스 [HtmlSaveOptions](../htmlsaveoptions/)
* 네임스페이스 [Aspose.Pdf](../../aspose.pdf/)
* 어셈블리 [Aspose.PDF](../../)