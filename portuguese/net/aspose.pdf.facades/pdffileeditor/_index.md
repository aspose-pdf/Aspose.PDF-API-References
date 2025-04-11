---
title: Class PdfFileEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileEditor. Implementa operações com concatenação de arquivos PDF, divisão, extração de páginas, criação de livreto, etc.
type: docs
weight: 4460
url: /pt/net/aspose.pdf.facades/pdffileeditor/
---
## Classe PdfFileEditor

Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livreto, etc.

```csharp
public sealed class PdfFileEditor
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileEditor](pdffileeditor/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CloseConcatenatedStreams](../../aspose.pdf.facades/pdffileeditor/closeconcatenatedstreams/) { get; set; } | Se definido como verdadeiro, os fluxos são fechados após a operação. |
| [ConcatenationPacketSize](../../aspose.pdf.facades/pdffileeditor/concatenationpacketsize/) { get; set; } | Número de documentos concatenados antes que uma nova atualização incremental seja feita durante a concatenação quando UseDiskBuffer está definido como verdadeiro. |
| [ConversionLog](../../aspose.pdf.facades/pdffileeditor/conversionlog/) { get; } | Obtém o log do processo de conversão. |
| [ConvertTo](../../aspose.pdf.facades/pdffileeditor/convertto/) { set; } | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [CopyLogicalStructure](../../aspose.pdf.facades/pdffileeditor/copylogicalstructure/) { get; set; } | Se verdadeiro, a estrutura lógica do arquivo é copiada quando a concatenação é realizada. |
| [CopyOutlines](../../aspose.pdf.facades/pdffileeditor/copyoutlines/) { get; set; } | Se verdadeiro, os contornos serão copiados. |
| [CorruptedFileAction](../../aspose.pdf.facades/pdffileeditor/corruptedfileaction/) { get; set; } | Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido. Os valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted. |
| [CorruptedItems](../../aspose.pdf.facades/pdffileeditor/corrupteditems/) { get; } | Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para a função Concatenate(), uma nova entrada CorruptedItem é criada. Esta propriedade pode ser usada apenas quando CorruptedFileAction é ConcatenateIgnoringCorrupted. |
| [IncrementalUpdates](../../aspose.pdf.facades/pdffileeditor/incrementalupdates/) { get; set; } | Se verdadeiro, atualizações incrementais são feitas durante a concatenação. |
| [KeepActions](../../aspose.pdf.facades/pdffileeditor/keepactions/) { get; set; } | Se verdadeiro, as ações serão copiadas dos documentos de origem. Valor padrão: verdadeiro. |
| [KeepFieldsUnique](../../aspose.pdf.facades/pdffileeditor/keepfieldsunique/) { get; set; } | Se verdadeiro, os nomes dos campos serão tornados únicos quando os formulários forem concatenados. Sufixos serão adicionados aos nomes dos campos, o modelo de sufixo pode ser especificado na propriedade UniqueSuffix. |
| [LastException](../../aspose.pdf.facades/pdffileeditor/lastexception/) { get; } | Obtém a última exceção ocorrida. Pode ser usado para verificar a razão da falha. |
| [MergeDuplicateLayers](../../aspose.pdf.facades/pdffileeditor/mergeduplicatelayers/) { get; set; } | O conteúdo opcional dos documentos concatenados com nomes iguais será mesclado em uma camada no documento resultante se esta propriedade for verdadeira. Caso contrário, camadas com nomes iguais serão salvas como camadas diferentes no documento resultante. |
| [MergeDuplicateOutlines](../../aspose.pdf.facades/pdffileeditor/mergeduplicateoutlines/) { get; set; } | Se verdadeiro, contornos duplicados são mesclados. |
| [OptimizeSize](../../aspose.pdf.facades/pdffileeditor/optimizesize/) { get; set; } | Obtém ou define a flag de otimização. Fluxos de recursos iguais no arquivo resultante são mesclados em um objeto PDF se esta flag estiver definida. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória. Valor padrão: falso. |
| [OwnerPassword](../../aspose.pdf.facades/pdffileeditor/ownerpassword/) { get; set; } | Define a senha do proprietário se o arquivo PDF de entrada fonte estiver criptografado. Esta propriedade ainda não foi implementada. |
| [PreserveUserRights](../../aspose.pdf.facades/pdffileeditor/preserveuserrights/) { get; set; } | Se verdadeiro, os direitos do usuário do primeiro documento são aplicados ao documento concatenado. Os direitos do usuário de todos os outros documentos são ignorados. |
| [RemoveSignatures](../../aspose.pdf.facades/pdffileeditor/removesignatures/) { get; set; } | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [UniqueSuffix](../../aspose.pdf.facades/pdffileeditor/uniquesuffix/) { get; set; } | Formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = "ABC%NUM%", então para o campo "fieldName" os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3, etc. |
| [UseDiskBuffer](../../aspose.pdf.facades/pdffileeditor/usediskbuffer/) { get; set; } | Se esta opção for usada, o documento de destino será salvo no disco periodicamente e a concatenação posterior será aplicada a ele como atualizações incrementais. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins)(Stream, Stream, int[], double, double, double, double) | Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. |
| [AddMargins](../../aspose.pdf.facades/pdffileeditor/addmargins/#addmargins_1)(string, string, int[], double, double, double, double) | Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct)(Stream, Stream, int[], double, double, double, double) | Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagens do tamanho inicial da página. |
| [AddMarginsPct](../../aspose.pdf.facades/pdffileeditor/addmarginspct/#addmarginspct_1)(string, string, int[], double, double, double, double) | Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagens do tamanho inicial da página. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak)(Document, Document, PageBreak[]) | Adiciona quebras de página nas páginas do documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_1)(Stream, Stream, PageBreak[]) | Adiciona quebras de página nas páginas do documento. |
| [AddPageBreak](../../aspose.pdf.facades/pdffileeditor/addpagebreak/#addpagebreak_2)(string, string, PageBreak[]) | Adiciona quebras de página nas páginas do documento. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append)(Stream, Stream, int, int, Stream) | Anexa páginas, que são escolhidas do portStream dentro do intervalo de startPage a endPage, no portStream no final do firstInputStream. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_1)(Stream, Stream[], int, int, Stream) | Anexa páginas, que são escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_2)(string, string, int, int, string) | Anexa páginas, que são escolhidas do portFile dentro do intervalo de startPage a endPage, no portFile no final do firstInputFile. |
| [Append](../../aspose.pdf.facades/pdffileeditor/append/#append_3)(string, string[], int, int, string) | Anexa páginas, que são escolhidas de documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo de startPage a endPage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate)(Document[], Document) | Concatena documentos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_3)(Stream[], Stream) | Concatena arquivos |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_6)(string[], string) | Concatena arquivos em um arquivo. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_1)(Stream, Stream, Stream) | Concatena dois arquivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_4)(string, string, string) | Concatena dois arquivos. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_2)(Stream, Stream, Stream, Stream) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Concatenate](../../aspose.pdf.facades/pdffileeditor/concatenate/#concatenate_5)(string, string, string, string) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete)(Stream, int[], Stream) | Exclui páginas especificadas por array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [Delete](../../aspose.pdf.facades/pdffileeditor/delete/#delete_1)(string, int[], string) | Exclui páginas especificadas por array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_1)(Stream, int[], Stream) | Extrai páginas especificadas por array de números, salva como um novo arquivo Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_3)(string, int[], string) | Extrai páginas especificadas por array de números, salva como um novo arquivo PDF. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract)(Stream, int, int, Stream) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [Extract](../../aspose.pdf.facades/pdffileeditor/extract/#extract_2)(string, int, int, string) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_1)(Stream, int, Stream, int[], Stream) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_3)(string, int, string, int[], string) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert)(Stream, int, Stream, int, int, Stream) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| [Insert](../../aspose.pdf.facades/pdffileeditor/insert/#insert_2)(string, int, string, int, int, string) | Insere páginas de outro arquivo no arquivo Pdf em uma posição. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet)(Stream, Stream) | Cria um livreto do InputStream para outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_4)(string, string) | Cria um livreto do arquivo de entrada para o arquivo de saída. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_1)(Stream, Stream, PageSize) | Cria um livreto do fluxo de entrada e salva o resultado no fluxo de saída. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_5)(string, string, PageSize) | Cria um livreto do inputFile para outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_3)(Stream, Stream, int[], int[]) | Cria um livreto personalizado do firstInputStream para outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_7)(string, string, int[], int[]) | Cria um livreto personalizado do firstInputFile para outputFile. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Cria um livreto do firstInputStream para outputStream. |
| [MakeBooklet](../../aspose.pdf.facades/pdffileeditor/makebooklet/#makebooklet_6)(string, string, PageSize, int[], int[]) | Cria um livreto personalizado do firstInputFile para outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_2)(Stream, Stream, Stream) | Cria um documento N-Up a partir dos dois fluxos PDF de entrada para outputStream. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_3)(Stream[], Stream, bool) | Cria um documento N-Up a partir dos múltiplos fluxos PDF de entrada para outputStream. Cada página do outputStream conterá várias páginas, que são combinações com páginas nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_6)(string, string, string) | Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página do outputFile conterá duas páginas, uma página é do primeiro arquivo de entrada e outra é do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_7)(string[], string, bool) | Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página do outputFile conterá várias páginas, que são combinações com páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup)(Stream, Stream, int, int) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_4)(string, string, int, int) | Cria um documento N-Up do firstInputFile para outputFile. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_1)(Stream, Stream, int, int, PageSize) | Cria um documento N-Up do primeiro fluxo de entrada para o fluxo de saída. |
| [MakeNUp](../../aspose.pdf.facades/pdffileeditor/makenup/#makenup_5)(string, string, int, int, PageSize) | Cria um documento N-Up do arquivo de entrada para outputFile. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_4)(Document, ContentsResizeParameters) | Redimensiona páginas do documento. Margens em branco são adicionadas ao redor da página reduzida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_5)(Document, int[], ContentsResizeParameters) | Redimensiona páginas do documento. Margens em branco são adicionadas ao redor da página reduzida. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensiona o conteúdo das páginas do documento. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_1)(Stream, Stream, int[], double, double) | Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão. |
| [ResizeContents](../../aspose.pdf.facades/pdffileeditor/resizecontents/#resizecontents_3)(string, string, int[], double, double) | Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct)(Stream, Stream, int[], double, double) | Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. |
| [ResizeContentsPct](../../aspose.pdf.facades/pdffileeditor/resizecontentspct/#resizecontentspct_1)(string, string, int[], double, double) | Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst)(Stream, int, Stream) | Divide do início até a localização especificada e salva a parte da frente no fluxo de saída. |
| [SplitFromFirst](../../aspose.pdf.facades/pdffileeditor/splitfromfirst/#splitfromfirst_1)(string, int, string) | Divide o arquivo Pdf da primeira página até a localização especificada e salva a parte da frente como um novo arquivo. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks)(Stream, int[][]) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de uma única página ou várias páginas. |
| [SplitToBulks](../../aspose.pdf.facades/pdffileeditor/splittobulks/#splittobulks_1)(string, int[][]) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de uma única página ou várias páginas. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend)(Stream, int, Stream) | Divide da localização especificada e salva a parte traseira como um novo fluxo de arquivo. |
| [SplitToEnd](../../aspose.pdf.facades/pdffileeditor/splittoend/#splittoend_1)(string, int, string) | Divide da localização e salva a parte traseira como um novo arquivo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages)(Stream) | Divide o arquivo Pdf em documentos de uma única página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_1)(string) | Divide o arquivo PDF em documentos de uma única página. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_2)(Stream, string) | Divide o arquivo Pdf em documentos de uma única página e salva no caminho especificado. O caminho é especificado pelo modelo de nome de campo. |
| [SplitToPages](../../aspose.pdf.facades/pdffileeditor/splittopages/#splittopages_3)(string, string) | Divide o arquivo Pdf em documentos de uma única página e salva no caminho especificado. O caminho é especificado pelo modelo de nome de campo. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend)(Stream, Stream[], int, int, Stream) | Anexa páginas, que são escolhidas de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos portStreams no intervalo de startPage a endPage. |
| [TryAppend](../../aspose.pdf.facades/pdffileeditor/tryappend/#tryappend_1)(string, string[], int, int, string) | Anexa páginas, que são escolhidas de documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo de startPage a endPage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate)(Document[], Document) | Concatena documentos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_2)(Stream[], Stream) | Concatena arquivos |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_5)(string[], string) | Concatena arquivos em um arquivo. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_3)(string, string, string) | Concatena dois arquivos. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_1)(Stream, Stream, Stream, Stream) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryConcatenate](../../aspose.pdf.facades/pdffileeditor/tryconcatenate/#tryconcatenate_4)(string, string, string, string) | Mescla dois documentos Pdf em um novo documento Pdf com páginas de maneiras alternadas e preenche os espaços em branco com páginas em branco. por exemplo: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclando os dois documentos Pdf produzirá o documento resultante com páginas: p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete)(Stream, int[], Stream) | Exclui páginas especificadas por array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [TryDelete](../../aspose.pdf.facades/pdffileeditor/trydelete/#trydelete_1)(string, int[], string) | Exclui páginas especificadas por array de números do arquivo de entrada, salva como um novo arquivo Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract)(Stream, int[], Stream) | Extrai páginas especificadas por array de números, salva como um novo arquivo Pdf. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_2)(string, int[], string) | Extrai páginas especificadas por array de números, salva como um novo arquivo PDF. |
| [TryExtract](../../aspose.pdf.facades/pdffileeditor/tryextract/#tryextract_1)(string, int, int, string) | Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert)(Stream, int, Stream, int[], Stream) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| [TryInsert](../../aspose.pdf.facades/pdffileeditor/tryinsert/#tryinsert_1)(string, int, string, int[], string) | Insere páginas de outro arquivo no arquivo Pdf de entrada. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet)(Stream, Stream) | Cria um livreto do InputStream para outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_4)(string, string) | Cria um livreto do arquivo de entrada para o arquivo de saída. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_1)(Stream, Stream, PageSize) | Cria um livreto do fluxo de entrada e salva o resultado no fluxo de saída. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_5)(string, string, PageSize) | Cria um livreto do inputFile para outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_3)(Stream, Stream, int[], int[]) | Cria um livreto personalizado do firstInputStream para outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_7)(string, string, int[], int[]) | Cria um livreto personalizado do firstInputFile para outputFile. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_2)(Stream, Stream, PageSize, int[], int[]) | Cria um livreto do firstInputStream para outputStream. |
| [TryMakeBooklet](../../aspose.pdf.facades/pdffileeditor/trymakebooklet/#trymakebooklet_6)(string, string, PageSize, int[], int[]) | Cria um livreto personalizado do firstInputFile para outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_2)(Stream, Stream, Stream) | Cria um documento N-Up a partir dos dois fluxos PDF de entrada para outputStream. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_3)(Stream[], Stream, bool) | Cria um documento N-Up a partir dos múltiplos fluxos PDF de entrada para outputStream. Cada página do outputStream conterá várias páginas, que são combinações com páginas nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_6)(string, string, string) | Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página do outputFile conterá duas páginas, uma página é do primeiro arquivo de entrada e outra é do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_7)(string[], string, bool) | Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página do outputFile conterá várias páginas, que são combinações com páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for verdadeiro e empilhadas verticalmente se isSidewise for falso. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup)(Stream, Stream, int, int) | Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_4)(string, string, int, int) | Cria um documento N-Up do firstInputFile para outputFile. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_1)(Stream, Stream, int, int, PageSize) | Cria um documento N-Up do primeiro fluxo de entrada para o fluxo de saída. |
| [TryMakeNUp](../../aspose.pdf.facades/pdffileeditor/trymakenup/#trymakenup_5)(string, string, int, int, PageSize) | Cria um documento N-Up do arquivo de entrada para outputFile. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents)(Stream, Stream, int[], ContentsResizeParameters) | Redimensiona o conteúdo das páginas do documento. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_2)(string, string, int[], ContentsResizeParameters) | Redimensiona o conteúdo das páginas no documento. Se a página for reduzida, margens em branco são adicionadas ao redor da página. |
| [TryResizeContents](../../aspose.pdf.facades/pdffileeditor/tryresizecontents/#tryresizecontents_1)(Stream, Stream, int[], double, double) | Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst)(Stream, int, Stream) | Divide do início até a localização especificada e salva a parte da frente no fluxo de saída. |
| [TrySplitFromFirst](../../aspose.pdf.facades/pdffileeditor/trysplitfromfirst/#trysplitfromfirst_1)(string, int, string) | Divide o arquivo Pdf da primeira página até a localização especificada e salva a parte da frente como um novo arquivo. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend)(Stream, int, Stream) | Divide da localização especificada e salva a parte traseira como um novo fluxo de arquivo. |
| [TrySplitToEnd](../../aspose.pdf.facades/pdffileeditor/trysplittoend/#trysplittoend_1)(string, int, string) | Divide da localização e salva a parte traseira como um novo arquivo. |

## Outros Membros

| Nome | Descrição |
| --- | --- |
| enum [ConcatenateCorruptedFileAction](../../aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction) | Ação realizada quando um arquivo corrompido é encontrado no processo de concatenação. |
| class [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters) | Classe para especificar parâmetros de redimensionamento de página. Permite definir os seguintes parâmetros: Tamanho da página resultante (largura, altura) em unidades de espaço padrão ou em porcentagens do tamanho das páginas iniciais; Margens esquerda, superior, inferior e direita em unidades de espaço padrão ou em porcentagens do tamanho da página inicial; Alguns valores podem ser deixados nulos para cálculo automático. Esses valores serão calculados a partir do restante do tamanho da página após o cálculo dos valores explicitamente especificados. Por exemplo: se a largura da página = 100 e a nova largura da página especificada for 60 unidades, então as margens esquerda e direita são calculadas automaticamente: (100 - 60) / 2 = 15. Esta classe é usada no método ResizeContents. |
| class [ContentsResizeValue](../../aspose.pdf.facades/pdffileeditor.contentsresizevalue) | Valor da margem ou tamanho do conteúdo especificado em porcentagens de unidades de espaço padrão. Esta classe é usada em ContentsResizeParameters. |
| class [CorruptedItem](../../aspose.pdf.facades/pdffileeditor.corrupteditem) | Classe que fornece informações sobre arquivos corrompidos durante a concatenação. |
| class [PageBreak](../../aspose.pdf.facades/pdffileeditor.pagebreak) | Dados da posição da quebra de página. |

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)