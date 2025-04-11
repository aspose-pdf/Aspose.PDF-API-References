---
title: Class FooterArtifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.FooterArtifact. Descreve o artefato de rodapé. Isso pode ser usado para definir o rodapé da página
type: docs
weight: 4930
url: /pt/net/aspose.pdf/footerartifact/
---
## Classe FooterArtifact

Descreve o artefato de rodapé. Isso pode ser usado para definir o rodapé da página.

```csharp
public class FooterArtifact : Artifact
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [FooterArtifact](footerartifact/)() | Cria uma instância do artefato de rodapé. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alinhamento horizontal do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alinhamento vertical do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margem inferior do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtém a coleção de operadores internos do artefato. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtém o nome do subtipo do artefato. Pode ser usado se o subtipo do artefato não for um subtipo padrão. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtém o nome do tipo do artefato. Pode ser usado se o tipo do artefato não for padrão. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtém o XForm do artefato (se o XForm for usado). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtém a imagem do artefato (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Se verdadeiro, o artefato é colocado atrás do conteúdo da página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margem esquerda do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linhas do artefato de texto multilinha. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtém ou define a opacidade do artefato. Os valores possíveis estão na faixa de 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtém ou define a posição do artefato. Se esta propriedade for especificada, então as margens e alinhamentos são ignorados. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtém o retângulo do artefato. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margem direita do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtém ou define o ângulo de rotação do artefato. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtém o subtipo do artefato. Se o artefato tiver um subtipo não padrão, o nome do subtipo pode ser lido através de CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtém o texto do artefato. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Estado do texto para o texto do artefato. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margem superior do artefato. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtém o tipo do artefato. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inicia atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artefato para melhorar o desempenho. Normalmente, os operadores do artefato são alterados sempre que a propriedade do artefato é alterada. Isso causa a alteração do conteúdo da página toda vez que o artefato é alterado. Para evitar esse efeito, coloque todas as atualizações do artefato entre as chamadas StartUpdates/SaveUpdates. Isso permite alterar o conteúdo da página apenas uma vez. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Descarte o artefato. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtém o valor personalizado do artefato. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Remove o valor personalizado do artefato. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Salva todas as atualizações no artefato que foram feitas após a chamada de BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Define a imagem do artefato. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Define a imagem do artefato. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Define o texto e as propriedades de texto do artefato. Permite especificar várias linhas. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Define qual string será substituída pelo número da página. O valor padrão é #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Define a página PDF que é colocada na página do documento como artefato. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Define o texto do artefato. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Define o texto e as propriedades de texto do artefato. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Define o valor personalizado do artefato. |

### Veja Também

* classe [Artifact](../artifact/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)