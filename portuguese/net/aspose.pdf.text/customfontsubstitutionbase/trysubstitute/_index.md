---
title: CustomFontSubstitutionBase.TrySubstitute
second_title: Aspose.PDF for .NET API Reference
description: Método CustomFontSubstitutionBase. Substitui a fonte original por outra fonte
type: docs
weight: 20
url: /pt/net/aspose.pdf.text/customfontsubstitutionbase/trysubstitute/
---
## Método CustomFontSubstitutionBase.TrySubstitute

Substitui a fonte original por outra fonte.

```csharp
public virtual bool TrySubstitute(OriginalFontSpecification originalFontSpecification, 
    out Font substitutionFont)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| originalFontSpecification | OriginalFontSpecification | Especificação da fonte original. |
| substitutionFont | Font& | Fonte de substituição. |

### Valor de Retorno

Verdadeiro caso a substituição tenha sido bem-sucedida.

## Observações

A classe CustomFontSubstitutionBase deve ser herdada para implementar a lógica de substituição de fonte personalizada. O método TrySubstitute deve ser sobrescrito corretamente: deve retornar verdadeiro caso a substituição seja necessária. substitutionFont deve ser definido como um objeto Font válido. Deve retornar falso caso nenhuma substituição seja necessária. substitutionFont pode ser definido como nulo.

### Veja Também

* classe [OriginalFontSpecification](../../customfontsubstitutionbase.originalfontspecification/)
* classe [Font](../../font/)
* classe [CustomFontSubstitutionBase](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)