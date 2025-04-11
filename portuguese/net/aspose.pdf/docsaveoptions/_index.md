---
title: Class DocSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.DocSaveOptions. Opções de salvamento para exportação para o formato Doc
type: docs
weight: 3750
url: /pt/net/aspose.pdf/docsaveoptions/
---
## Classe DocSaveOptions

Opções de salvamento para exportação para o formato Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend/) { get; set; } | Usar quebras de parágrafo ou de linha |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize/) { get; set; } | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto prepara as páginas aps. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [ConvertType3Fonts](../../aspose.pdf/docsaveoptions/converttype3fonts/) { get; set; } | Obtém ou define a conversão para fontes Type3. Nas fontes Type 3, os glifos devem ser definidos por fluxos de operadores gráficos. Isso significa que na saída DOC/DOCX vemos imagens em vez de texto. Defina esta flag como verdadeira para converter fontes Type3 em TTF e obter texto no arquivo resultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativa a funcionalidade para extrair imagem ou texto de documentos PDF com subcamada OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format/) { get; set; } | Formato de saída |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx/) { get; set; } | Resolução X das imagens convertidas. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony/) { get; set; } | Resolução Y das imagens convertidas. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines/) { get; set; } | Este parâmetro é usado para agrupar linhas de texto em parágrafos. Determina quão distantes podem estar duas linhas de texto relativas. Especificado em centenas de porcento da altura das linhas de texto. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath/) { get; set; } | Define o caminho (nome do arquivo ou nome do diretório) para armazenar dados temporários ao converter no modo de salvamento em memória. |
| [Mode](../../aspose.pdf/docsaveoptions/mode/) { get; set; } | Modo de reconhecimento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets/) { get; set; } | Ativar o reconhecimento de marcadores |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity/) { get; set; } | Em PDFs, as palavras podem ser representadas internamente com operadores que imprimem palavras imprimindo independentemente suas letras ou sílabas. Assim, para detectar palavras, às vezes precisamos detectar grupos de caracteres independentes que são, de fato, palavras. Esta configuração define a largura do espaço entre elementos de texto (letras, sílabas) que devem ser tratados como distância entre palavras durante o reconhecimento de palavras no PDF de origem. (a presença de espaço vazio com pelo menos essa largura entre letras significa que os elementos textuais pertencem a palavras diferentes). É normalizado para o tamanho da fonte - 1.0 significa 100% do tamanho da fonte suposta da palavra. ATENÇÃO! É usado apenas em casos em que o PDF de origem contém fontes raramente usadas para as quais o valor ótimo não pode ser calculado a partir da fonte. Portanto, na grande maioria dos casos, este parâmetro não altera nada no documento resultante. |
| [ReSaveFonts](../../aspose.pdf/docsaveoptions/resavefonts/) { get; set; } | Obtém ou define o procedimento para re-salvar fontes. Se definido como verdadeiro, recarregamos fontes em cada página para evitar a influência das propriedades de fonte anteriores e carregar a nova fonte criada do zero. Defina esta opção como falsa se você quiser melhorar o desempenho. O valor padrão é verdadeiro; |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento de dados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler/) | Este manipulador pode ser usado para lidar com eventos de progresso da conversão, por exemplo, pode ser usado para mostrar uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, exemplo do código do manipulador que mostra progresso no console é: |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processar páginas em várias threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma ao lado da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém tais limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera essencialmente a conversão, então, por favor, use esta opção apenas quando realmente necessário. |

### Exemplos

O seguinte exemplo mostra como converter um arquivo PDF para um arquivo DOC ou DOCX

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf");

	// The path to output DOC or DOCX File.
	var docFile = Path.Combine(dataDir, "PDF-to-DOC.doc");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		DocSaveOptions saveOptions = new DocSaveOptions
		{
			Format = DocSaveOptions.DocFormat.Doc,
			// Set the recognition mode as Flow
			Mode = DocSaveOptions.RecognitionMode.Flow,
			// Set the Horizontal proximity as 2.5
			RelativeHorizontalProximity = 2.5f,
			// Enable the value to recognize bullets during conversion process
			RecognizeBullets = true
		};
		pdfDocument.Save(docFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-DOC.pdf")
    
	' The path to output DOC or DOCX File.
    Dim docFile = Path.Combine(dataDir, "PDF-to-DOC.doc")
 
    Using pdfDocument As Document = New Document(pdfFile)
        Dim saveOptions As DocSaveOptions = New DocSaveOptions With {
          .Format = DocSaveOptions.DocFormat.Doc,
            ' Set the recognition mode as Flow
            .Mode = DocSaveOptions.RecognitionMode.Flow,
            ' Set the Horizontal proximity as 2.5
            .RelativeHorizontalProximity = 2.5,
            ' Enable the value to recognize bullets during conversion process
            .RecognizeBullets = True
        }
        pdfDocument.Save(docFile, saveOptions)
    End Using
```

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)