---
title: Class Artifact
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Artifact. Classe representa objeto Artifact PDF
type: docs
weight: 2770
url: /pt/net/aspose.pdf/artifact/
---
## Classe Artifact

Classe representa objeto Artifact PDF.

```csharp
public class Artifact : IDisposable
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [Artifact](artifact/#constructor)(ArtifactType, ArtifactSubtype) | Construtor de artifact com tipo e subtipo especificados |
| [Artifact](artifact/#constructor_1)(string, string) | Construtor de artifact com tipo e subtipo especificados |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Alinhamento horizontal do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Alinhamento vertical do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Margem inferior do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Obtém coleção de operadores internos do artifact. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Obtém o nome do subtipo do artifact. Pode ser usado se o subtipo do artifact não for um subtipo padrão. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Obtém o nome do tipo do artifact. Pode ser usado se o tipo do artifact não for padrão. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Obtém XForm do artifact (se XForm for usado). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Obtém imagem do artifact (se presente). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Se verdadeiro, o Artifact é colocado atrás do conteúdo da página. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Margem esquerda do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linhas do artifact de texto multilinha. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Obtém ou define a opacidade do artifact. Os valores possíveis estão na faixa de 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Obtém ou define a posição do artifact. Se esta propriedade for especificada, então margens e alinhamentos são ignorados. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Obtém o retângulo do artifact. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Margem direita do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Obtém ou define o ângulo de rotação do artifact. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Obtém o subtipo do artifact. Se o artifact tiver um subtipo não padrão, o nome do subtipo pode ser lido através de CustomSubtype. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Obtém o texto do artifact. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Estado do texto para o texto do artifact. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Margem superior do artifact. Se a posição for especificada explicitamente (na propriedade Position), este valor é ignorado. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Obtém o tipo do artifact. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Inicia atualizações atrasadas. Use este recurso se precisar fazer várias alterações no mesmo artifact para melhorar o desempenho. Normalmente, os operadores do artifact são alterados sempre que uma propriedade do artifact é alterada. Isso causa a alteração do conteúdo da página toda vez que o artifact é alterado. Para evitar esse efeito, coloque todas as atualizações do artifact entre as chamadas StartUpdates/SaveUpdates. Isso permite alterar o conteúdo da página apenas uma vez. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Descartar o artifact. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Obtém valor personalizado do artifact. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Remove valor personalizado do artifact. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Salva todas as atualizações no artifact que foram feitas após a chamada BeginUpdates(). |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage)(Stream) | Define a imagem do artifact. |
| [SetImage](../../aspose.pdf/artifact/setimage/#setimage_1)(string) | Define a imagem do artifact. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Define texto e propriedades de texto do artifact. Permite especificar várias linhas. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Define qual string será substituída pelo número da página. O valor padrão é #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Define a página PDF que é colocada na página do documento como artifact. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Define o texto do artifact. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Define texto e propriedades de texto do artifact. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Define valor personalizado do artifact. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| enum [ArtifactSubtype](../../aspose.pdf/artifact.artifactsubtype) | Enumeração de possíveis subtipos de artifacts. |
| enum [ArtifactType](../../aspose.pdf/artifact.artifacttype) | Enumeração de possíveis tipos de artifacts. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)