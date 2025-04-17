---
title: RunResponse.ToolChoice
second_title: Aspose.PDF for .NET API Reference
description: RunResponse özelliği. Model tarafından çağrılan herhangi bir aracın hangisi olduğunu alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. "type" "file_search" veya "type" "function", "function" "name" "my_function" gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar.
type: docs
weight: 230
url: /tr/net/aspose.pdf.ai/runresponse/toolchoice/
---
## RunResponse.ToolChoice özelliği

Model tarafından çağrılan (varsa) aracın hangisi olduğunu alır veya ayarlar. none, modelin herhangi bir aracı çağırmayacağı ve bunun yerine bir mesaj üreteceği anlamına gelir. auto varsayılan değerdir ve modelin bir mesaj üretmek veya bir veya daha fazla aracı çağırmak arasında seçim yapabileceği anlamına gelir. required, modelin kullanıcıya yanıt vermeden önce bir veya daha fazla aracı çağırması gerektiği anlamına gelir. {"type": "file_search"} veya {"type": "function", "function": {"name": "my_function"}} gibi belirli bir aracı belirtmek, modelin o aracı çağırmasını zorlar.

```csharp
public string ToolChoice { get; set; }
```

### Ayrıca Bakınız

* class [RunResponse](../)
* namespace [Aspose.Pdf.AI](../../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../../)