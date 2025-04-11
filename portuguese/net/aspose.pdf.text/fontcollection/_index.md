---
title: Class FontCollection
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontCollection. Representa coleção de fontes
type: docs
weight: 10530
url: /pt/net/aspose.pdf.text/fontcollection/
---
## Classe FontCollection

Representa coleção de fontes.

```csharp
public sealed class FontCollection : ICollection<Font>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Count](../../aspose.pdf.text/fontcollection/count/) { get; } | Obtém o número de elementos do objeto [`Font`](../font/) realmente contidos na coleção. |
| [IsReadOnly](../../aspose.pdf.text/fontcollection/isreadonly/) { get; } | Obtém um valor que indica se a coleção é somente leitura |
| [IsSynchronized](../../aspose.pdf.text/fontcollection/issynchronized/) { get; } | Obtém um valor que indica se o acesso à coleção é sincronizado (seguro para threads). |
| [Item](../../aspose.pdf.text/fontcollection/item/) { get; } | Obtém o elemento de fonte no índice especificado. (2 indexadores) |
| [SyncRoot](../../aspose.pdf.text/fontcollection/syncroot/) { get; } | Obtém um objeto que pode ser usado para sincronizar o acesso à coleção. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Add](../../aspose.pdf.text/fontcollection/add/)(Font, out string) | Adiciona nova fonte aos recursos de fonte e retorna o nome automaticamente atribuído do recurso de fonte. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains)(Font) | Determina se a coleção contém um valor específico. |
| [Contains](../../aspose.pdf.text/fontcollection/contains/#contains_1)(string) | Verifica se a fonte existe na coleção de fontes. |
| [CopyTo](../../aspose.pdf.text/fontcollection/copyto/)(Font[], int) | Copia toda a coleção para um Array unidimensional compatível, começando no índice especificado do array de destino |
| [GetEnumerator](../../aspose.pdf.text/fontcollection/getenumerator/)() | Retorna um enumerador para toda a coleção. |
| [Remove](../../aspose.pdf.text/fontcollection/remove/)(Font) | Exclui o item especificado da coleção. |

## Observações

As coleções de fontes representadas pela classe `FontCollection` são usadas em vários cenários. Por exemplo, em recursos com a propriedade [`Fonts`](../../aspose.pdf/resources/fonts/).

## Exemplos

O exemplo demonstra como tornar todas as fontes declaradas na página como incorporadas.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// ensure all fonts declared on page resources are embedded
// note that if fonts are declared on form resources they are not accessible from page resources
foreach(Aspose.Pdf.Txt.Font font in doc.Pages[1].Resources.Fonts)
{
    if(!font.IsEmbedded)
        font.IsEmbedded = true;
}

doc.Save(@"D:\Tests\input.pdf");
```

### Veja Também

* classe [Font](../font/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)