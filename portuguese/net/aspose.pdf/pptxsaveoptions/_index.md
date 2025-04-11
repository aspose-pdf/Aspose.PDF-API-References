---
title: Class PptxSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PptxSaveOptions. Opções de salvamento para exportação para o formato SVG
type: docs
weight: 9480
url: /pt/net/aspose.pdf/pptxsaveoptions/
---
## Classe PptxSaveOptions

Opções de salvamento para exportação para o formato SVG

```csharp
public class PptxSaveOptions : UnifiedSaveOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PptxSaveOptions](pptxsaveoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto prepara as páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [CustomProgressHandler](../../aspose.pdf/pptxsaveoptions/customprogresshandler/) { get; set; } | Este manipulador pode ser usado para lidar com eventos de progresso da conversão, por exemplo, pode ser usado para mostrar uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, exemplo de código do manipulador que mostra progresso no console é: |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativou a funcionalidade para extrair imagem ou texto para documentos PDF com subcamada OCR. |
| [ImageResolution](../../aspose.pdf/pptxsaveoptions/imageresolution/) { get; set; } | Obtém ou define a resolução da imagem (dpi). O padrão é 192 dpi. |
| [OptimizeTextBoxes](../../aspose.pdf/pptxsaveoptions/optimizetextboxes/) { get; set; } | Alterna o reconhecimento de colunas de texto |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento de dados. |
| [SeparateImages](../../aspose.pdf/pptxsaveoptions/separateimages/) { get; set; } | Se definido como verdadeiro, as imagens são separadas de todos os outros gráficos |
| [SlidesAsImages](../../aspose.pdf/pptxsaveoptions/slidesasimages/) { get; set; } | Se definido como verdadeiro, todo o conteúdo é reconhecido como imagens (uma por página) |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processa páginas em várias threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de tiling iguais colocadas uma ao lado da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém tais limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera essencialmente a conversão, portanto, use esta opção apenas quando realmente necessário. |

## Exemplos

O exemplo a seguir mostra como converter um arquivo PDF para um arquivo PPT ou PPTX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf");

	// The path to your PPT or PPTX File.
	var pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize PptxSaveOptions	
		PptxSaveOptions saveOptions = new PptxSaveOptions();
		
		// Save PPT or PPTX file
		pdfDocument.Save(pptxFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-PPTX.pdf")
    ' The path to your PPT or PPTX File.
    Dim pptxFile = Path.Combine(dataDir, "PDF-to-PPTX.pptx")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize PptxSaveOptions    
        Dim saveOptions As PptxSaveOptions = New PptxSaveOptions()
 
        ' Save PPT or PPTX file
        pdfDocument.Save(pptxFile, saveOptions)
    End Using
```

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)