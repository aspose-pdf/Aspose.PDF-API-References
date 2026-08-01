---
title: "XslFoLoadOptions.XsltArgumentList"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "XslFoLoadOptions プロパティ。既存の xls パラメータに値を挿入するための XsltArgumentList。XLS ファイルに値が設定されていない animal パラメータがあり、XsltArgumentList args = new XsltArgumentList(); args.AddParamanimal  cat とすると、コンバータは XLS ファイルに animal パラメータが値 cat で存在するとみなします。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/
---
## XslFoLoadOptions.XsltArgumentList property

既存の XLS パラメータに値を挿入するための XsltArgumentList。XLS ファイルに値のない 'animal' パラメータがある場合：XsltArgumentList args = new XsltArgumentList(); args.AddParam("animal", "", "cat"); これにより、コンバータは XLS ファイルに値 'cat' の 'animal' パラメータがあるとみなします。

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

### 関連項目

* class [XslFoLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


