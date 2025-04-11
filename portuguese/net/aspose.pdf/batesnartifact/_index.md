---
title: Class BatesNArtifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.BatesNArtifact. A classe descreve o artefato de numeração Bates
type: docs
weight: 2850
url: /pt/net/aspose.pdf/batesnartifact/
---
## Classe BatesNArtifact

A classe descreve o artefato de numeração Bates.

```csharp
public class BatesNArtifact : PaginationArtifact
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [BatesNArtifact](batesnartifact/)() | Inicializa uma nova instância da classe `BatesNArtifact`. Este construtor é interno e cria uma instância de artefato de cabeçalho com valores padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alinhamento horizontal do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alinhamento vertical do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margem inferior do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtém a coleção de operadores internos do artefato. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtém o nome do subtipo do artefato. Pode ser usado se o subtipo do artefato não for um subtipo padrão. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtém o nome do tipo do artefato. Pode ser usado se o tipo do artefato não for padrão. |
| [EndPage](../../aspose.pdf/paginationartifact/endpage/) { get; set; } | Obtém ou define o número da página final para o artefato. O valor deve ser maior ou igual a 0. Se um valor menor que 0 for definido, ele será ajustado para 0. O valor padrão de 0 significa que não há limites de página final. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtém o XForm do artefato (se o XForm for usado). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtém a imagem do artefato (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Se verdadeiro, o artefato é colocado atrás do conteúdo da página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linhas do artefato de texto multilinha. |
| [NumberOfDigits](../../aspose.pdf/batesnartifact/numberofdigits/) { get; set; } | Obtém ou define o número de dígitos para a numeração Bates. O valor deve estar entre 3 e 15, inclusive. Se um valor menor que 3 for definido, ele será ajustado para 3. Se um valor maior que 15 for definido, ele será ajustado para 15. O valor padrão é 6. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtém ou define a opacidade do artefato. Os valores possíveis estão na faixa de 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtém ou define a posição do artefato. Se esta propriedade for especificada, então margens e alinhamentos são ignorados. |
| [Prefix](../../aspose.pdf/batesnartifact/prefix/) { get; set; } | Obtém ou define o prefixo a ser adicionado ao número Bates. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtém o retângulo do artefato. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margem direita do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtém ou define o ângulo de rotação do artefato. |
| [StartNumber](../../aspose.pdf/batesnartifact/startnumber/) { get; set; } | Obtém ou define o número inicial para a numeração Bates. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1. |
| [StartPage](../../aspose.pdf/paginationartifact/startpage/) { get; set; } | Obtém ou define o número da página inicial para o artefato. O valor deve ser maior ou igual a 1. Se um valor menor que 1 for definido, ele será ajustado para 1. |
| [Subset](../../aspose.pdf/paginationartifact/subset/) { get; set; } | Obtém ou define o subconjunto de páginas ao qual o artefato se aplica (por exemplo, todas as páginas, páginas pares, páginas ímpares). |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtém o subtipo do artefato. Se o artefato tiver um subtipo não padrão, o nome do subtipo pode ser lido através de CustomSubtype. |
| [Suffix](../../aspose.pdf/batesnartifact/suffix/) { get; set; } | Obtém ou define o sufixo a ser adicionado ao número Bates. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtém o texto do artefato. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Estado do texto para o texto do artefato. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margem superior do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtém o tipo do artefato. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inicia atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores do artefato são alterados sempre que uma propriedade do artefato é alterada. Isso causa a alteração do conteúdo da página toda vez que o artefato é alterado. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite alterar o conteúdo da página apenas uma vez. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Descartar o artefato. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtém o valor personalizado do artefato. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Remove o valor personalizado do artefato. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Salva todas as atualizações no artefato que foram feitas após a chamada BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Define a imagem do artefato. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Define a imagem do artefato. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Define o texto e as propriedades de texto do artefato. Permite especificar várias linhas. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Define qual string será substituída pelo número da página. O valor padrão é #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Define a página PDF que é colocada na página do documento como artefato. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Define o texto do artefato. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Define o texto e as propriedades de texto do artefato. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Define o valor personalizado do artefato. |

### Veja Também

* classe [PaginationArtifact](../paginationartifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)