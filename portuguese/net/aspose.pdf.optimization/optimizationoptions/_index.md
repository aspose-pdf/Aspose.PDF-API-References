---
title: Class OptimizationOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Optimization.OptimizationOptions. Classe que descreve o algoritmo de otimização de documentos. A instância desta classe pode ser usada como parâmetro do método OptimizeResources.
type: docs
weight: 7980
url: /pt/net/aspose.pdf.optimization/optimizationoptions/
---
## Classe OptimizationOptions

Classe que descreve o algoritmo de otimização de documentos. A instância desta classe pode ser usada como parâmetro do método OptimizeResources().

```csharp
public class OptimizationOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [OptimizationOptions](optimizationoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AllowReusePageContent](../../aspose.pdf.optimization/optimizationoptions/allowreusepagecontent/) { get; set; } | Se verdadeiro, o conteúdo das páginas será reutilizado quando o documento for otimizado para páginas iguais. |
| [CompressObjects](../../aspose.pdf.optimization/optimizationoptions/compressobjects/) { get; set; } | Se esta flag estiver definida como `true`, os objetos Pdf serão compactados em Objet Streams e comprimidos para reduzir o tamanho do arquivo pdf. |
| [ImageCompressionOptions](../../aspose.pdf.optimization/optimizationoptions/imagecompressionoptions/) { get; } | Conjunto de opções que descrevem se as imagens no documento serão comprimidas e os parâmetros da compressão. |
| [ImageEncoding](../../aspose.pdf.optimization/optimizationoptions/imageencoding/) { get; set; } | Codificador de imagem que será utilizado. |
| [LinkDuplicateStreams](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreams/) { get; set; } | Se esta flag estiver definida como verdadeira, os streams de recursos serão analisados. Se streams duplicados forem encontrados (ou seja, se o conteúdo do stream for igual), esses streams serão armazenados como um único objeto. Isso permite diminuir o tamanho do documento em alguns casos (por exemplo, quando o mesmo documento foi concatenado várias vezes). |
| [LinkDuplicateStreamsScanLevel](../../aspose.pdf.optimization/optimizationoptions/linkduplicatestreamsscanlevel/) { get; set; } | Nível de varredura. Varreduras mais profundas (valor mais alto) demoram mais, mas podem produzir arquivos de resultado menores. Valor padrão: 10. |
| [MaxResoultion](../../aspose.pdf.optimization/optimizationoptions/maxresoultion/) { get; set; } | Especifica a resolução máxima das imagens. Se a imagem tiver uma resolução mais alta, ela será escalonada. |
| [RemovePrivateInfo](../../aspose.pdf.optimization/optimizationoptions/removeprivateinfo/) { get; set; } | Remove informações privadas (informações de partes da página). |
| [RemoveUnusedObjects](../../aspose.pdf.optimization/optimizationoptions/removeunusedobjects/) { get; set; } | Se esta flag estiver definida como verdadeira, todos os objetos do documento serão verificados e objetos não utilizados (ou seja, objetos que não têm nenhuma referência) serão removidos do documento. |
| [RemoveUnusedStreams](../../aspose.pdf.optimization/optimizationoptions/removeunusedstreams/) { get; set; } | Se esta flag estiver definida como verdadeira, cada recurso é verificado quanto ao seu uso. Se o recurso nunca for usado, então o recurso é removido. Isso pode diminuir o tamanho do documento, por exemplo, quando páginas foram extraídas do documento. |
| [SubsetFonts](../../aspose.pdf.optimization/optimizationoptions/subsetfonts/) { get; set; } | As fontes serão convertidas em subconjuntos se definido como verdadeiro. |
| [UnembedFonts](../../aspose.pdf.optimization/optimizationoptions/unembedfonts/) { get; set; } | Fazer com que as fontes não sejam incorporadas se definido como verdadeiro. |

## Métodos

| Nome | Descrição |
| --- | --- |
| static [All](../../aspose.pdf.optimization/optimizationoptions/all/)() | Cria uma estratégia de otimização com todas as opções ativadas. Observe que apenas as opções ativadas que não alteram nenhuma funcionalidade do documento. Ou seja, a compressão de imagens e a desincorporação de fontes não serão ativadas (e podem ser incorporadas manualmente). |

### Veja Também

* namespace [Aspose.Pdf.Optimization](../../aspose.pdf.optimization/)
* assembly [Aspose.PDF](../../)