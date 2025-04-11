---
title: CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable
second_title: Aspose.PDF for .NET API Reference
description: Propriedade OriginalFontSpecification. Obtém um valor que indica que a substituição é inevitável
type: docs
weight: 20
url: /pt/net/aspose.pdf.text/customfontsubstitutionbase.originalfontspecification/issubstitutionunavoidable/
---
## Propriedade CustomFontSubstitutionBase.OriginalFontSpecification.IsSubstitutionUnavoidable

Obtém um valor que indica que a substituição é inevitável.

```csharp
public bool IsSubstitutionUnavoidable { get; }
```

## Observações

Retorna verdadeiro caso a substituição tenha sido solicitada devido à ausência da fonte original ou caso a fonte original não possa ser usada no contexto de alguma tarefa. Caso o usuário ignore a flag e não substitua a fonte - o procedimento padrão de substituição de fonte é realizado. Mas isso oferece a oportunidade para o usuário alternar o procedimento padrão de substituição de fonte e definir uma fonte melhor para o sistema. Retorna falso caso a fonte original esteja presente, válida, mas seja permitido ao usuário substituí-la.

### Veja Também

* classe [OriginalFontSpecification](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)