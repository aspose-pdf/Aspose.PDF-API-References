---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: 문서 속성. 문서 작업을 가져옵니다. 이 속성은 BeforClosing, BeforSaving 등의 작업을 가져오고 설정할 수 있는 DocumentActions 클래스의 인스턴스입니다.
type: docs
weight: 30
url: /ko/net/aspose.pdf/document/actions/
---
## Document.Actions 속성

문서 작업을 가져옵니다. 이 속성은 BeforClosing, BeforSaving 등의 작업을 가져오고 설정할 수 있는 DocumentActions 클래스의 인스턴스입니다.

```csharp
public DocumentActionCollection Actions { get; }
```

## 예제

이 예제는 문서의 열기 후 작업을 얻는 방법을 보여줍니다:

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### 참조

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)