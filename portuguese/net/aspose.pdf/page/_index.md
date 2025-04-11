---
title: Class Page
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Page. Classe que representa a página de um documento PDF
type: docs
weight: 8050
url: /pt/net/aspose.pdf/page/
---
## Classe Página

Classe que representa a página de um documento PDF.

```csharp
public sealed class Page : IDisposable
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Actions](../../aspose.pdf/page/actions/) { get; } | Obtém a coleção de propriedades da página. |
| [Annotations](../../aspose.pdf/page/annotations/) { get; } | Obtém a coleção de anotações da página. [`Annotations`](./annotations/) |
| [ArtBox](../../aspose.pdf/page/artbox/) { get; set; } | Obtém ou define a caixa de arte da página. |
| [Artifacts](../../aspose.pdf/page/artifacts/) { get; } | Obtém a coleção de artefatos na página. |
| [Background](../../aspose.pdf/page/background/) { get; set; } | Obtém ou define a cor de fundo da página. |
| [BackgroundImage](../../aspose.pdf/page/backgroundimage/) { get; set; } | Obtém ou define a imagem de fundo para a página (apenas para gerador, não preenchido ao ler o documento). |
| [BleedBox](../../aspose.pdf/page/bleedbox/) { get; set; } | Obtém ou define a caixa de sangria da página. |
| [ColorType](../../aspose.pdf/page/colortype/) { get; } | Define o tipo de cor das páginas com base nas informações obtidas dos operadores SetColor, imagens e formulários. |
| [Contents](../../aspose.pdf/page/contents/) { get; } | Obtém a coleção de operadores no fluxo de conteúdo da página. [`OperatorCollection`](../operatorcollection/) |
| [CropBox](../../aspose.pdf/page/cropbox/) { get; set; } | Obtém ou define a caixa de corte da página. |
| [Duration](../../aspose.pdf/page/duration/) { get; set; } | Obtém ou define a duração de exibição da página. Este é o tempo em segundos que a página deve ser exibida durante a apresentação. Retorna -1 se a duração não estiver definida. |
| [FieldsInTabOrder](../../aspose.pdf/page/fieldsintaborder/) { get; } | Obtém a lista de objetos Field na ordem de tabulação nesta página. |
| [Footer](../../aspose.pdf/page/footer/) { get; set; } | Obtém ou define o rodapé da página. |
| [Group](../../aspose.pdf/page/group/) { get; set; } | Obtém ou define uma classe de atributos de grupo especificando os atributos do grupo da página para uso no modelo de imagem transparente. |
| [Header](../../aspose.pdf/page/header/) { get; set; } | Obtém ou define o cabeçalho da página. |
| [IsAddParagraphsAfterLast](../../aspose.pdf/page/isaddparagraphsafterlast/) { get; set; } | Obtém ou define a adição de parágrafos após o último parágrafo da página. |
| [Layers](../../aspose.pdf/page/layers/) { get; set; } | Obtém ou define a coleção de camadas. |
| [MediaBox](../../aspose.pdf/page/mediabox/) { get; set; } | Obtém ou define a caixa de mídia da página. |
| [NoteLineStyle](../../aspose.pdf/page/notelinestyle/) { get; set; } | Obtém ou define o estilo da linha para notas. (apenas para gerador, não preenchido ao ler o documento) |
| [Number](../../aspose.pdf/page/number/) { get; } | Obtém o número da página. |
| [PageInfo](../../aspose.pdf/page/pageinfo/) { get; set; } | Obtém ou define as informações da página (apenas para gerador, não preenchido ao ler o documento). |
| [Paragraphs](../../aspose.pdf/page/paragraphs/) { get; set; } | Obtém os parágrafos. |
| [Rect](../../aspose.pdf/page/rect/) { get; set; } | Obtém ou define o retângulo da página. Para obter: a caixa de corte da página é retornada se especificada, caso contrário, a caixa de mídia da página é retornada. Para definir: a caixa de mídia da página sempre é definida. Observe que esta propriedade não considera a rotação da página. Para obter o retângulo da página considerando a rotação, use ActualRect. |
| [Resources](../../aspose.pdf/page/resources/) { get; } | Obtém os recursos da página. O objeto de recursos contém coleções de imagens, formulários e fontes. [`Resources`](./resources/) |
| [Rotate](../../aspose.pdf/page/rotate/) { get; set; } | Obtém ou define a rotação da página. |
| [RotationMatrix](../../aspose.pdf/page/rotationmatrix/) { get; } | Obtém a matriz de transformação para a página. |
| [TabOrder](../../aspose.pdf/page/taborder/) { get; set; } | Obtém ou define a ordem de tabulação da página. Valores possíveis: Linha, Coluna. Padrão, Manual |
| [TocInfo](../../aspose.pdf/page/tocinfo/) { get; set; } | Obtém ou define as informações da tabela de conteúdos. |
| [TrimBox](../../aspose.pdf/page/trimbox/) { get; set; } | Obtém ou define a caixa de corte da página. |
| [UserUnit](../../aspose.pdf/page/userunit/) { get; set; } | Obtém ou define o valor UserUnit. Um número positivo que dá o tamanho das unidades de espaço do usuário padrão, em múltiplos de 1 / 72 polegada. O valor padrão é 1. Defina zero ou um valor negativo para limpar esta entrada na página. |
| [Watermark](../../aspose.pdf/page/watermark/) { get; set; } | Obtém ou define a marca d'água da página. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [Accept](../../aspose.pdf/page/accept/#accept)(AnnotationSelector) | Aceita o objeto visitante [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) que fornece funcionalidade para trabalhar com anotações. |
| [Accept](../../aspose.pdf/page/accept/#accept_1)(ImagePlacementAbsorber) | Aceita o objeto visitante [`ImagePlacementAbsorber`](../imageplacementabsorber/) que fornece funcionalidade para trabalhar com objetos de colocação de imagem. |
| [Accept](../../aspose.pdf/page/accept/#accept_2)(TextAbsorber) | Aceita o objeto visitante [`TextAbsorber`](../../aspose.pdf.text/textabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| [Accept](../../aspose.pdf/page/accept/#accept_3)(TextFragmentAbsorber) | Aceita o objeto visitante [`TextFragmentAbsorber`](../../aspose.pdf.text/textfragmentabsorber/) que fornece funcionalidade para trabalhar com objetos de texto. |
| [AddGraphics](../../aspose.pdf/page/addgraphics/)(GraphicElementCollection, Rectangle) | Adiciona gráficos à página. Funciona mais rápido do que adicionar elementos um por um com o método [`AddOnPage`](../../aspose.pdf.vector/graphicelement/addonpage/). |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_2)(string, Rectangle) | Adiciona uma imagem à página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage)(Stream, Rectangle, Rectangle, bool) | Adiciona uma imagem à página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_3)(string, Stream, Rectangle, Rectangle) | Adiciona uma imagem pesquisável à página e a localiza no meio do retângulo especificado, mantendo a proporção da imagem. |
| [AddImage](../../aspose.pdf/page/addimage/#addimage_1)(Stream, Rectangle, int, int, bool, Rectangle) | Adiciona uma imagem à página e a coloca dependendo da posição do retângulo da imagem. |
| [AddStamp](../../aspose.pdf/page/addstamp/)(Stamp) | Coloca um carimbo na página. O carimbo pode ser um número de página, imagem ou texto simples, por exemplo, um logotipo. |
| [AsByteArray](../../aspose.pdf/page/asbytearray/)(Resolution) | Converte a página atual em bitmap e, em seguida, retorna um array de bytes. |
| [AsXml](../../aspose.pdf/page/asxml/)() | Converte a página atual em xml na codificação utf8. |
| [CalculateContentBBox](../../aspose.pdf/page/calculatecontentbbox/)() | Calcula o valor bbox - retângulo contendo conteúdos sem margens visíveis. |
| [ConvertToPNGMemoryStream](../../aspose.pdf/page/converttopngmemorystream/)() | Converte a página para PNG para fluxo de imagem DSR, OMR, OCR. |
| [DeleteGraphics](../../aspose.pdf/page/deletegraphics/)(GraphicElementCollection) | Exclui gráficos da página. Funciona mais rápido do que excluir elementos um por um com o método [`Remove`](../../aspose.pdf.vector/graphicelement/remove/). |
| [Dispose](../../aspose.pdf/page/dispose/)() | Libera memória |
| [Flatten](../../aspose.pdf/page/flatten/)() | Remove todos os campos localizados na página e coloca seus valores em vez disso. |
| [FreeMemory](../../aspose.pdf/page/freememory/)() | Limpa dados em cache |
| [GetNotifications](../../aspose.pdf/page/getnotifications/)() | Retorna notificações sobre operações internas com o conteúdo da página. (Apenas notificações sobre eventos de parágrafo em cenários de adição de texto são suportadas agora.) |
| [GetPageRect](../../aspose.pdf/page/getpagerect/)(bool) | Retorna o retângulo da página de acordo com sua CropBox (ou MediaBox se CropBox for nulo). |
| [GetResources](../../aspose.pdf/page/getresources/)() | Recupera os recursos associados à página. |
| [HasVectorGraphics](../../aspose.pdf/page/hasvectorgraphics/)() | Detecta a presença de gráficos vetoriais, se estiver presente na página. |
| [IsBlank](../../aspose.pdf/page/isblank/)(double) | Obtém o sinalizador se a página está em branco ou não. |
| [MakeGrayscale](../../aspose.pdf/page/makegrayscale/)() | Converte a página para escala de cinza. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers)(string) | Mescla todas as camadas na página em uma única camada com o nome da nova camada especificada. |
| [MergeLayers](../../aspose.pdf/page/mergelayers/#mergelayers_1)(string, string) | Mescla todas as camadas na página em uma única camada com o nome da nova camada especificada e um Id de grupo de conteúdo opcional. |
| [Resize](../../aspose.pdf/page/resize/)(PageSize) | Redimensiona a página. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto)(PageDevice, Stream) | Envia a página para processar com o dispositivo de página dado. |
| [SendTo](../../aspose.pdf/page/sendto/#sendto_1)(PageDevice, string) | Envia a página para processar com o dispositivo de página dado. |
| [SetPageSize](../../aspose.pdf/page/setpagesize/)(double, double) | Define o tamanho da página. |
| [TrySaveVectorGraphics](../../aspose.pdf/page/trysavevectorgraphics/)(string) | Tenta salvar gráficos vetoriais se estiverem presentes na página. O formato de salvamento é SVG. |
| static [IntToRotation](../../aspose.pdf/page/inttorotation/)(int) | Traduz o valor inteiro em membro de enumeração de rotação correspondente. |
| static [RotationToInt](../../aspose.pdf/page/rotationtoint/)(Rotation) | Traduz o membro de enumeração de rotação em valor inteiro. |

## Eventos

| Nome | Descrição |
| --- | --- |
| event [OnBeforePageGenerate](../../aspose.pdf/page/onbeforepagegenerate/) | Evento para personalizar cabeçalho e rodapé. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| delegate [BeforePageGenerate](../../aspose.pdf/page.beforepagegenerate) | Procedimento para personalizar cabeçalho e rodapé. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)