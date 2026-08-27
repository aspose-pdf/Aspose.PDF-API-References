---
title: "PdfFileEditor"
linktitle: "PdfFileEditor"
second_title: "Referência da API Aspose.PDF para Java"
description: "Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc."
type: docs
weight: 410
url: /pt/java/com.aspose.pdf.facades/pdffileeditor/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfFileEditor

**All Implemented Interfaces:**
IPdfFileEditor

```
public final class PdfFileEditor extends Object implements IPdfFileEditor
```

Implementa operações com arquivos PDF: concatenação, divisão, extração de páginas, criação de livrinho, etc.

## Construtores

| Construtor | Descrição |
| --- | --- |
| [PdfFileEditor](#PdfFileEditor--) | Construtor de PdfFileEditor. |

## Métodos

| Método | Descrição |
| --- | --- |
| [addMargins](#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre> |
| [addMargins](#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre> |
| [addMarginsPct](#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-) | <p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagem do tamanho inicial da página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre> |
| [addMarginsPct](#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-) | <p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagem do tamanho inicial da página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre> |
| [addPageBreak](#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [addPageBreak](#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-) | Adiciona quebras de página nas páginas do documento. |
| [append](#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-) | <p> Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos em portStreams no intervalo startPage até endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre> |
| [append](#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage até endPage, em portStream ao final de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre> |
| [append](#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-) | <p> Anexa páginas, que são escolhidas dos documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo startPage até endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre> |
| [append](#append-java.lang.String-java.lang.String-int-int-java.lang.String-) | <p> Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage até endPage, em portFile ao final de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-) | Concatena documentos. |
| [concatenate](#concatenate-java.io.InputStream:A-java.io.OutputStream-) | <p> Concatena arquivos </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. Ex.: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclar os dois documentos Pdf produzirá o documento resultante com as páginas:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre> |
| [concatenate](#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Concatena dois arquivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre> |
| [concatenate](#concatenate-java.lang.String:A-java.lang.String-) | <p> Concatena arquivos em um único arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-) | <p> Concatena dois arquivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre> |
| [concatenate](#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | <p> Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. Ex.: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclar os dois documentos Pdf produzirá o documento resultante com as páginas:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre> |
| [createArrayWithExclusion](#createArrayWithExclusion-int-int-) |  |
| [delete](#delete-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre> |
| [delete](#delete-java.lang.String-int:A-java.lang.String-) | <p> Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre> |
| [extract](#extract-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre> |
| [extract](#extract-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre> |
| [extract](#extract-java.lang.String-int:A-java.lang.String-) | <p> Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre> |
| [extract](#extract-java.lang.String-int-int-java.lang.String-) | <p> Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre> |
| [getAllowConcatenateExceptions](#getAllowConcatenateExceptions--) | <p> Se definido como true, exceções são lançadas se ocorrer um erro. Caso contrário, exceções não são lançadas e os métodos retornam false se falharem. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> |
| [getAttachmentName](#getAttachmentName--) | Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [getCloseConcatenatedStreams](#getCloseConcatenatedStreams--) | Se definido como true, os streams são fechados após a operação. |
| [getConcatenationPacketSize](#getConcatenationPacketSize--) | Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true. |
| [getContentDisposition](#getContentDisposition--) | Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpServletResponse. Valores possíveis: inline / attachment. Padrão: inline. |
| [getConversionLog](#getConversionLog--) | Obtém o registro do processo de conversão. |
| [getCopyLogicalStructure](#getCopyLogicalStructure--) | Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada. |
| [getCopyOutlines](#getCopyOutlines--) | Se true, os contornos serão copiados. |
| [getCorruptedFileAction](#getCorruptedFileAction--) | Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido. Valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted. |
| [getCorruptedItems](#getCorruptedItems--) | <p> Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para a função Concatenate() é criada uma nova entrada CorruptedItem. Esta propriedade pode ser usada somente quando CorruptedFileAction é ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre> |
| [getCustomProgressConcatenationHandler](#getCustomProgressConcatenationHandler--) | Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente. |
| [getIncrementalUpdates](#getIncrementalUpdates--) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [getKeepActions](#getKeepActions--) | Se true, as ações serão copiadas dos documentos de origem. |
| [getKeepFieldsUnique](#getKeepFieldsUnique--) | Se true, os nomes de campo serão tornados únicos quando os formulários forem concatenados. Sufixos serão adicionados aos nomes de campo, e o modelo de sufixo pode ser especificado na propriedade UniqueSuffix. |
| [getLastException](#getLastException--) | Obtém a última exceção ocorrida. |
| [getMergeDuplicateLayers](#getMergeDuplicateLayers--) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [getMergeDuplicateOutlines](#getMergeDuplicateOutlines--) | Se true, contornos duplicados são mesclados. |
| [getOptimizeSize](#getOptimizeSize--) | Obtém ou define a bandeira de otimização. |
| [getOwnerPassword](#getOwnerPassword--) | Obtém a senha do proprietário se o arquivo Pdf de entrada de origem estiver criptografado. Esta propriedade ainda não foi implementada. |
| [getPreserveUserRights](#getPreserveUserRights--) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [getRemoveSignatures](#getRemoveSignatures--) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [getSaveOptions](#getSaveOptions--) | Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. Valor padrão: PdfSaveOptions. |
| [getUniqueSuffix](#getUniqueSuffix--) | Obtenha o formato do sufixo que é adicionado ao nome do campo para torná‑lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = \"ABC%NUM%\" então, para o campo \"fieldName\", os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-) | <p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileoutputStream(\"out.pdf\"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre> |
| [insert](#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-) | <p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-) | <p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre> |
| [insert](#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-) | <p> Insere páginas de outro arquivo no arquivo Pdf em uma posição. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert(\"file1.pdf\", 1, \"file2.pdf\", 2, 6, \"out.pdf\"); </pre> |
| [isTryMergeAdjacentSameBackgroundImages](#isTryMergeAdjacentSameBackgroundImages--) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras. |
| [isUseDiskBuffer](#isUseDiskBuffer--) | Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais. |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-) | <p> Cria um livreto a partir do InputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-) | <p> Cria um livreto personalizado a partir do firstInputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-) | <p> Cria um livreto a partir do input stream e salva o resultado no output stream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Cria um livreto a partir do firstInputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-) | <p> Cria um livreto a partir do arquivo de entrada para o arquivo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-) | <p> Cria um livreto personalizado a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-) | <p> Cria um livreto a partir do inputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre> |
| [makeBooklet](#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-) | <p> Cria um livreto personalizado a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-) | <p> Cria um documento N-Up a partir dos múltiplos fluxos PDF de entrada para outputStream. Cada página de outputStream conterá múltiplas páginas, que são combinações com as páginas nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-) | <p> Cria um documento N-Up a partir dos dois fluxos PDF de entrada para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-) | <p> Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre> |
| [makeNUp](#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-) | <p> Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String:A-java.lang.String-boolean-) | <p> Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página de outputFile conterá múltiplas páginas, que são combinações com as páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-) | <p> Cria um documento N-Up a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-) | <p> Cria um documento N-Up a partir do arquivo de entrada para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre> |
| [makeNUp](#makeNUp-java.lang.String-java.lang.String-java.lang.String-) | <p> Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página de outputFile conterá duas páginas, uma página vem do primeiro arquivo de entrada e outra do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre> |
| [resizeContents](#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContents](#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado nas unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona o conteúdo das páginas do documento. |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre> |
| [resizeContents](#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona o conteúdo das páginas no documento. |
| [resizeContentsPct](#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-) | <p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsPct](#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-) | <p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre> |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [resizeContentsWithNormalization](#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-) | Redimensiona páginas do documento. |
| [setAllowConcatenateExceptions](#setAllowConcatenateExceptions-boolean-) | <p> Se definido como true, exceções são lançadas se ocorrer um erro. Caso contrário, exceções não são lançadas e os métodos retornam false se falharem. </p> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo. |
| [setCloseConcatenatedStreams](#setCloseConcatenatedStreams-boolean-) | <p> Se definido como true, os streams são fechados após a operação. </p> |
| [setConcatenationPacketSize](#setConcatenationPacketSize-int-) | Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpServletResponse. Valor possível: inline / attachment. Padrão: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [setCopyLogicalStructure](#setCopyLogicalStructure-boolean-) | Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada. |
| [setCopyOutlines](#setCopyOutlines-boolean-) | Se true, os contornos serão copiados. |
| [setCorruptedFileAction](#setCorruptedFileAction-int-) | Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido. Valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted. |
| [setCustomProgressConcatenationHandler](#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-) | Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente. |
| [setIncrementalUpdates](#setIncrementalUpdates-boolean-) | Se true, atualizações incrementais são feitas durante a concatenação. |
| [setKeepActions](#setKeepActions-boolean-) | Se true, as ações serão copiadas dos documentos de origem. |
| [setKeepFieldsUnique](#setKeepFieldsUnique-boolean-) | Se true, os nomes de campo serão tornados únicos quando os formulários forem concatenados. Sufixos serão adicionados aos nomes de campo, e o modelo de sufixo pode ser especificado na propriedade UniqueSuffix. |
| [setMergeDuplicateLayers](#setMergeDuplicateLayers-boolean-) | Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true. |
| [setMergeDuplicateOutlines](#setMergeDuplicateOutlines-boolean-) | Se true, contornos duplicados são mesclados. |
| [setOptimizeSize](#setOptimizeSize-boolean-) | Obtém ou define a bandeira de otimização. |
| [setOwnerPassword](#setOwnerPassword-java.lang.String-) | Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado. Esta propriedade ainda não foi implementada. |
| [setPreserveUserRights](#setPreserveUserRights-boolean-) | Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado. |
| [setRemoveSignatures](#setRemoveSignatures-boolean-) | Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. Valor padrão: PdfSaveOptions. |
| [setTryMergeAdjacentSameBackgroundImages](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras. |
| [setUniqueSuffix](#setUniqueSuffix-java.lang.String-) | <p> Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = "ABC%NUM%" então para o campo "fieldName" os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre> |
| [setUseDiskBuffer](#setUseDiskBuffer-boolean-) | Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais. |
| [splitFromFirst](#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide a partir do início até o local especificado e salva a parte frontal no Stream de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Os streams NÃO são fechados após esta operação. |
| [splitFromFirst](#splitFromFirst-java.lang.String-int-java.lang.String-) | <p> Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre> |
| [splitToBulks](#splitToBulks-java.io.InputStream-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToBulks](#splitToBulks-java.lang.String-int:A:A-) | Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas. |
| [splitToEnd](#splitToEnd-java.io.InputStream-int-java.io.OutputStream-) | <p> Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Os streams NÃO são fechados após esta operação, a menos que CloseConcatedStreams seja especificado. |
| [splitToEnd](#splitToEnd-java.lang.String-int-java.lang.String-) | <p> Divide a partir do local e salva a parte traseira como um novo arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre> |
| [splitToPages](#splitToPages-java.io.InputStream-) | Divide o arquivo Pdf em documentos de página única. |
| [splitToPages](#splitToPages-java.io.InputStream-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |
| [splitToPages](#splitToPages-java.lang.String-) | Divide o arquivo PDF em documentos de página única. |
| [splitToPages](#splitToPages-java.lang.String-java.lang.String-) | Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado. |

### PdfFileEditor {#PdfFileEditor--}
```
public PdfFileEditor()
```

Construtor de PdfFileEditor.

### addMargins {#addMargins-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMargins(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); dest.Close(); </pre>

### addMargins {#addMargins-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMargins(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 10 units 10, //right margin is 5 units 5, //top margin is 5 units 5, //bottom margin is 5 units 5); </pre>

### addMarginsPct {#addMarginsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-double-double-}
<p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagem do tamanho inicial da página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InmputStream src = new FileInputStream(\"input.pdf\"); OutputStream dest = new FileInputStream(\"output.pdf\"); fileEditor.addMarginsPct(src, dest, //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); dest.close(); </pre>

### addMarginsPct {#addMarginsPct-java.lang.String-java.lang.String-int:A-double-double-double-double-}
<p> Redimensiona o conteúdo da página e adiciona margens especificadas. As margens são especificadas em porcentagem do tamanho inicial da página. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.addMarginsPct(\"input.pdf\", \"output.pdf\", //process pages 1, 2, 3 new int[] { 1, 2, 3}, //left margin is 15% of page width 15, //right margin is 10% of page width 10, //top margin is 20% of page width 20, //bottom margin is 5% of page width 5); </pre>

### addPageBreak {#addPageBreak-com.aspose.pdf.Document-com.aspose.pdf.Document-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-com.aspose.pdf.IDocument-com.aspose.pdf.IDocument-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### addPageBreak {#addPageBreak-java.lang.String-java.lang.String-com.aspose.pdf.facades.PdfFileEditor.PageBreak:A-}
Adiciona quebras de página nas páginas do documento.

### append {#append-java.io.InputStream-java.io.InputStream:A-int-int-java.io.OutputStream-}
<p> Anexa páginas, que são escolhidas a partir de um array de documentos em portStreams. O documento resultante inclui firstInputFile e todas as páginas dos documentos em portStreams no intervalo startPage até endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OtputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, new InputStream[] { stream1, stream2}, 3, 5, outstream); </pre>

### append {#append-java.io.InputStream-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Anexa páginas, que são escolhidas de portStream dentro do intervalo de startPage até endPage, em portStream ao final de firstInputStream. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream instream = new FileInputStream(\"input.pdf\"); InputStream stream1 = new FileInputStream(\"file1.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.append(instream, stream1, 3, 5, outstream); </pre>

### append {#append-java.lang.String-java.lang.String:A-int-int-java.lang.String-}
<p> Anexa páginas, que são escolhidas dos documentos portFiles. O documento resultante inclui firstInputFile e todas as páginas dos documentos portFiles no intervalo startPage até endPage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", new string[] { \"file1.pdf\", \"file2.pdf\"}, 3, 5, \"outfile.pdf\"); </pre>

### append {#append-java.lang.String-java.lang.String-int-int-java.lang.String-}
<p> Anexa páginas, que são escolhidas de portFile dentro do intervalo de startPage até endPage, em portFile ao final de firstInputFile. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.append(\"input.pdf\", \"file1.pdf\", 3, 5, \"outfile.pdf\"); </pre>

### concatenate {#concatenate-com.aspose.pdf.IDocument:A-com.aspose.pdf.IDocument-}
Concatena documentos.

### concatenate {#concatenate-java.io.InputStream:A-java.io.OutputStream-}
<p> Concatena arquivos </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2 } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. Ex.: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclar os dois documentos Pdf produzirá o documento resultante com as páginas:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); InputStream blank = new FileInputStream(\"blank.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(new Stream[] { stream1, stream2, blank } , outstream); </pre>

### concatenate {#concatenate-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Concatena dois arquivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream stream1 = new FileInputStream(\"file1.pdf\"); InputStream stream2 = new FileInputStream(\"file2.pdf\"); OutputStream outstream = new FileOutputStream(\"outfile.pdf\"); fileEditor.concatenate(stream1, stream2, outstream); </pre>

### concatenate {#concatenate-java.lang.String:A-java.lang.String-}
<p> Concatena arquivos em um único arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(new String[] { \"src1.pdf\", \"src2.pdf\" }, \"dest.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-}
<p> Concatena dois arquivos. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.concatenate(\"file1.pdf\", \"file2.pdf\", \"outfile.pdf\"); </pre>

### concatenate {#concatenate-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
<p> Mescla dois documentos Pdf em um novo documento Pdf com páginas de forma alternada e preenche os espaços vazios com páginas em branco. Ex.: document1 tem 5 páginas: p1, p2, p3, p4, p5. document2 tem 3 páginas: p1', p2', p3'. Mesclar os dois documentos Pdf produzirá o documento resultante com as páginas:p1, p1', p2, p2', p3, p3', p4, blankpage, p5, blankpage. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.concatenate(\"src1.pdf\", \"src2.pdf\", \"blank.pdf\", \"dest.pdf\"); </pre>

### createArrayWithExclusion {#createArrayWithExclusion-int-int-}
```
public static Integer [] createArrayWithExclusion(int n, int y)
```



### delete {#delete-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream intputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileInputStream("output.pdf"); pfe.Delete(inputStream, new int[] { 2, 3 }, outputStream); </pre>

### delete {#delete-java.lang.String-int:A-java.lang.String-}
<p> Exclui páginas especificadas por um array de números do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.delete("input.pdf", new int[] { 2, 3 }, "out.pdf"); </pre>

### extract {#extract-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Extrai páginas especificadas por um array de números, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.extract(sourceStream, new int[] { 3, 5, 8 }, outStream); </pre>

### extract {#extract-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.extract(sourceStream, 1, 3, 6, outStream); </pre>

### extract {#extract-java.lang.String-int:A-java.lang.String-}
<p> Extrai páginas especificadas por um array de números, salva como um novo arquivo PDF. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.extract("input.pdf", new int[] { 3, 5, 7 }, "output.pdf"); </pre>

### extract {#extract-java.lang.String-int-int-java.lang.String-}
<p> Extrai páginas do arquivo de entrada, salva como um novo arquivo Pdf. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.Extract("input.pdf", 3, 7, "output.pdf"); </pre>

### getAllowConcatenateExceptions {#getAllowConcatenateExceptions--}
```
@Deprecated public boolean getAllowConcatenateExceptions()
```

<p> Se definido como true, exceções são lançadas se ocorrer um erro. Caso contrário, exceções não são lançadas e os métodos retornam false se falharem. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre>

**Returns:**
valor booleano @deprecated Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Obtém o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

**Returns:**
valor String

### getCloseConcatenatedStreams {#getCloseConcatenatedStreams--}
```
public boolean getCloseConcatenatedStreams()
```

Se definido como true, os streams são fechados após a operação.

**Returns:**
valor booleano

### getConcatenationPacketSize {#getConcatenationPacketSize--}
```
public final int getConcatenationPacketSize()
```

Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true.

**Returns:**
valor int

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Obtém como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpServletResponse. Valores possíveis: inline / attachment. Padrão: inline.

**Returns:**
Elemento ContentDisposition @see ContentDisposition

### getConversionLog {#getConversionLog--}
```
public String getConversionLog()
```

Obtém o registro do processo de conversão.

**Returns:**
valor de string

### getCopyLogicalStructure {#getCopyLogicalStructure--}
```
public boolean getCopyLogicalStructure()
```

Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada.

**Returns:**
valor booleano

### getCopyOutlines {#getCopyOutlines--}
```
public boolean getCopyOutlines()
```

Se true, os contornos serão copiados.

**Returns:**
valor booleano

### getCorruptedFileAction {#getCorruptedFileAction--}
```
public int getCorruptedFileAction()
```

Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido. Valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted.

**Returns:**
Elemento ConcatenateCorruptedFileAction @see ConcatenateCorruptedFileAction

### getCorruptedItems {#getCorruptedItems--}
```
public PdfFileEditor.CorruptedItem [] getCorruptedItems()
```

<p> Array de problemas encontrados quando a concatenação foi realizada. Para cada documento corrompido passado para a função Concatenate() é criada uma nova entrada CorruptedItem. Esta propriedade pode ser usada somente quando CorruptedFileAction é ConcatenateIgnoringCorrupted. </p> <hr> <pre> //concatenate documents and show information about corrupted documents PdfFileEditor pfe = new PdfFileEditor(); pfe.setCorruptedFileAction(PdfFileEditor.ConcatenateCorruptedFileAction.ConcatenateIgnoringCorrupted); {@code if (pfe.getCorruptedItems().length >0)} { for(PdfFileEditor.CorruptedItem item : pfe.getCorruptedItems()) { System.out.println(item.getIndex()+ " reason: " + item.getException()); } } </pre>

**Returns:**
array de PdfFileEditor.CorruptedItem

### getCustomProgressConcatenationHandler {#getCustomProgressConcatenationHandler--}
```
public PdfFileEditor.ConcatenationProgressHandler getCustomProgressConcatenationHandler()
```

Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente.

**Returns:**
ConcatenationProgressHandler instância

### getIncrementalUpdates {#getIncrementalUpdates--}
```
public boolean getIncrementalUpdates()
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Returns:**
valor booleano

### getKeepActions {#getKeepActions--}
```
public final boolean getKeepActions()
```

Se true, as ações serão copiadas dos documentos de origem.

**Returns:**
valor booleano

### getKeepFieldsUnique {#getKeepFieldsUnique--}
```
public boolean getKeepFieldsUnique()
```

Se true, os nomes de campo serão tornados únicos quando os formulários forem concatenados. Sufixos serão adicionados aos nomes de campo, e o modelo de sufixo pode ser especificado na propriedade UniqueSuffix.

**Returns:**
valor booleano

### getLastException {#getLastException--}
```
public final RuntimeException getLastException()
```

Obtém a última exceção ocorrida.

**Returns:**
java.lang.Exception objeto

### getMergeDuplicateLayers {#getMergeDuplicateLayers--}
```
public boolean getMergeDuplicateLayers()
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Returns:**
valor booleano

### getMergeDuplicateOutlines {#getMergeDuplicateOutlines--}
```
public boolean getMergeDuplicateOutlines()
```

Se true, contornos duplicados são mesclados.

**Returns:**
valor booleano

### getOptimizeSize {#getOptimizeSize--}
```
public boolean getOptimizeSize()
```

Obtém ou define a bandeira de otimização.

**Returns:**
valor booleano

### getOwnerPassword {#getOwnerPassword--}
```
public String getOwnerPassword()
```

Obtém a senha do proprietário se o arquivo Pdf de entrada de origem estiver criptografado. Esta propriedade ainda não foi implementada.

**Returns:**
valor String

### getPreserveUserRights {#getPreserveUserRights--}
```
public boolean getPreserveUserRights()
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Returns:**
valor booleano

### getRemoveSignatures {#getRemoveSignatures--}
```
public final boolean getRemoveSignatures()
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Returns:**
valor booleano

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Obtém ou define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. Valor padrão: PdfSaveOptions.

**Returns:**
Objeto SaveOptions

### getUniqueSuffix {#getUniqueSuffix--}
```
public String getUniqueSuffix()
```

Obtenha o formato do sufixo que é adicionado ao nome do campo para torná‑lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = \"ABC%NUM%\" então, para o campo \"fieldName\", os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc.

**Returns:**
valor String

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int:A-java.io.OutputStream-}
<p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileoutputStream(\"out.pdf\"); pfe.Insert(sourceStream, 1, insertedStream, new int[] { 3, 4, 5}, outStream); </pre>

### insert {#insert-java.io.InputStream-int-java.io.InputStream-int-int-java.io.OutputStream-}
<p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileOutputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int:A-java.lang.String-}
<p> Insere páginas de outro arquivo no arquivo Pdf de entrada. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); outstream sourceStream = new FileInputStream(\"file1.pdf\"); outstream insertedStream = new FileInputStream(\"file2.pdf\"); OutputStream outStream = new FileInputStream(\"out.pdf\"); pfe.insert(sourceStream, 1, insertedStream, 2, 6, outStream); </pre>

### insert {#insert-java.lang.String-int-java.lang.String-int-int-java.lang.String-}
<p> Insere páginas de outro arquivo no arquivo Pdf em uma posição. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.insert(\"file1.pdf\", 1, \"file2.pdf\", 2, 6, \"out.pdf\"); </pre>

### isTryMergeAdjacentSameBackgroundImages {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.

**Returns:**
valor booleano

### isUseDiskBuffer {#isUseDiskBuffer--}
```
public final boolean isUseDiskBuffer()
```

Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais.

**Returns:**
valor booleano

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-}
<p> Cria um livreto a partir do InputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-int:A-int:A-}
<p> Cria um livreto personalizado a partir do firstInputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-}
<p> Cria um livreto a partir do input stream e salva o resultado no output stream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileInputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.io.InputStream-java.io.OutputStream-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Cria um livreto a partir do firstInputStream para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream(\"input.pdf\"); OutputStream outputStream = new FileOutputStream(\"output.pdf\"); pfe.makeBooklet(inputStream, outputStream, PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-}
<p> Cria um livreto a partir do arquivo de entrada para o arquivo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\"); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-int:A-int:A-}
<p> Cria um livreto personalizado a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet(\"input.pdf\", \"output.pdf\", new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-}
<p> Cria um livreto a partir do inputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4); </pre>

### makeBooklet {#makeBooklet-java.lang.String-java.lang.String-com.aspose.pdf.PageSize-int:A-int:A-}
<p> Cria um livreto personalizado a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeBooklet("input.pdf", "output.pdf", PageSize.A4, new int[] { 2, 4, 6 }, new int[] 1, 3, 5, 7 }); </pre>

### makeNUp {#makeNUp-java.io.InputStream:A-java.io.OutputStream-boolean-}
<p> Cria um documento N-Up a partir dos múltiplos fluxos PDF de entrada para outputStream. Cada página de outputStream conterá múltiplas páginas, que são combinações com as páginas nos fluxos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream stream1 = new FileInputStream("input1.pdf"); InputStream stream2 = new FileInputStream("input2.pdf"); InputStream stream3 = new FileInputStream("input3.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(new InputStream[] { stream1, stream2, stream3 }, output, false); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.InputStream-java.io.OutputStream-}
<p> Cria um documento N-Up a partir dos dois fluxos PDF de entrada para outputStream. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream input1 = new FileInputStream("input1.pdf"); InputStream input2 = new FileInputStream("input2.pdf"); OutputStream output = new FileOutputStream("output.pdf"); pfe.makeNUp(input1, input2, output); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-}
<p> Cria um documento N-Up a partir do fluxo de entrada e salva o resultado no fluxo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.makeNUp(inputStream, outputStream, 3, 3); </pre>

### makeNUp {#makeNUp-java.io.InputStream-java.io.OutputStream-int-int-com.aspose.pdf.PageSize-}
<p> Cria um documento N-Up a partir do primeiro fluxo de entrada para o fluxo de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream inputStream = new FileInputStream("input.pdf"); OutputStream outputStream = new FileOutputStream("output.pdf"); pfe.MakeNUp(inputStream, outputStream, 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String:A-java.lang.String-boolean-}
<p> Cria um documento N-Up a partir dos múltiplos arquivos PDF de entrada para outputFile. Cada página de outputFile conterá múltiplas páginas, que são combinações com as páginas nos arquivos de entrada do mesmo número de página. As múltiplas páginas são empilhadas horizontalmente se isSidewise for true e empilhadas verticalmente se isSidewise for false. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp(new String[] { "input1.pdf", "input2.pdf", "input3.pdf" }, "output.pdf", false); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-}
<p> Cria um documento N-Up a partir do firstInputFile para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-int-int-com.aspose.pdf.PageSize-}
<p> Cria um documento N-Up a partir do arquivo de entrada para outputFile. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input.pdf", "output.pdf", 3, 3, PageSize.A4); </pre>

### makeNUp {#makeNUp-java.lang.String-java.lang.String-java.lang.String-}
<p> Cria um documento N-Up a partir dos dois arquivos PDF de entrada para outputFile. Cada página de outputFile conterá duas páginas, uma página vem do primeiro arquivo de entrada e outra do segundo arquivo de entrada. As duas páginas são empilhadas horizontalmente. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.makeNUp("input1.pdf", "input2.pdf", "output.pdf"); </pre>

### resizeContents {#resizeContents-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContents {#resizeContents-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensiona o conteúdo das páginas do documento. Reduz o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado nas unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizeContents(src, dest, //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.io.InputStream-java.io.OutputStream-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona o conteúdo das páginas do documento.

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em unidades de espaço padrão. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizeContents("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 200 200, //new contents height = 300 300); // rest area of page will be empty </pre>

### resizeContents {#resizeContents-java.lang.String-java.lang.String-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona o conteúdo das páginas no documento.

### resizeContentsPct {#resizeContentsPct-java.io.InputStream-java.io.OutputStream-int:A-double-double-}
<p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); InputStream src = new FileInputStream("input.pdf"); OutputStream dest = new FileOutputStream("output.pdf"); fileEditor.resizePct(src, dest, //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsPct {#resizeContentsPct-java.lang.String-java.lang.String-int:A-double-double-}
<p> Redimensiona o conteúdo das páginas do documento. Encolhe o conteúdo da página e adiciona margens. O novo tamanho do conteúdo é especificado em porcentagens. </p> <hr> <pre> PdfFileEditor fileEditor = new PdfFileEditor(); fileEditor.resizePct("input.pdf", "output.pdf", //resize all pages of document null, //new contents width = 60% of initial size 60, //new contents height = 60% of initial size 60); // Rest area of page will be empty (page margins). Size of left and right margins is (100% - 60%) / 2 = 20% // The same for top and bottom margins. </pre>

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.Document-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### resizeContentsWithNormalization {#resizeContentsWithNormalization-com.aspose.pdf.IDocument-int:A-com.aspose.pdf.facades.IPdfFileEditor.ContentsResizeParameters-}
Redimensiona páginas do documento.

### setAllowConcatenateExceptions {#setAllowConcatenateExceptions-boolean-}
```
@Deprecated public void setAllowConcatenateExceptions(boolean value)
```

<p> Se definido como true, exceções são lançadas se ocorrer um erro. Caso contrário, exceções não são lançadas e os métodos retornam false se falharem. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setAllowConcatenatedException (true); </pre> @deprecated Esta propriedade está obsoleta e não pode ser usada para permitir lançar exceções. |

### setAttachmentName {#setAttachmentName-java.lang.String-}
Define o nome do anexo quando o resultado da operação é armazenado em objetos HttpServletResponse como anexo.

### setCloseConcatenatedStreams {#setCloseConcatenatedStreams-boolean-}
```
public void setCloseConcatenatedStreams(boolean value)
```

<p> Se definido como true, os streams são fechados após a operação. </p>

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.setCloseConcatenatedStreams (true); </pre> |

### setConcatenationPacketSize {#setConcatenationPacketSize-int-}
```
public final void setConcatenationPacketSize(int value)
```

Número de documentos concatenados antes de uma nova atualização incremental ser feita durante a concatenação quando UseDiskBuffer está definido como true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int |

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Define como o conteúdo será armazenado quando o resultado da operação for armazenado em um objeto HttpServletResponse. Valor possível: inline / attachment. Padrão: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão.

### setCopyLogicalStructure {#setCopyLogicalStructure-boolean-}
```
public void setCopyLogicalStructure(boolean value)
```

Se true, a estrutura lógica do arquivo é copiada quando a concatenação é realizada.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCopyOutlines {#setCopyOutlines-boolean-}
```
public void setCopyOutlines(boolean value)
```

Se true, os contornos serão copiados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCorruptedFileAction {#setCorruptedFileAction-int-}
```
public void setCorruptedFileAction(int value)
```

Esta propriedade define o comportamento quando o processo de concatenação encontra um arquivo corrompido. Valores possíveis são: StopWithError e ConcatenateIgnoringCorrupted.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @see ConcatenateCorruptedFileAction |

### setCustomProgressConcatenationHandler {#setCustomProgressConcatenationHandler-com.aspose.pdf.facades.PdfFileEditor.ConcatenationProgressHandler-}
Representação do processador interno de eventos de progresso que funciona durante a concatenação e traduz eventos de concatenação das etapas internas de concatenação para o código externo do cliente.

### setIncrementalUpdates {#setIncrementalUpdates-boolean-}
```
public void setIncrementalUpdates(boolean value)
```

Se true, atualizações incrementais são feitas durante a concatenação.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepActions {#setKeepActions-boolean-}
```
public final void setKeepActions(boolean value)
```

Se true, as ações serão copiadas dos documentos de origem.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setKeepFieldsUnique {#setKeepFieldsUnique-boolean-}
```
public void setKeepFieldsUnique(boolean value)
```

Se true, os nomes de campo serão tornados únicos quando os formulários forem concatenados. Sufixos serão adicionados aos nomes de campo, e o modelo de sufixo pode ser especificado na propriedade UniqueSuffix.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateLayers {#setMergeDuplicateLayers-boolean-}
```
public void setMergeDuplicateLayers(boolean value)
```

Conteúdos opcionais de documentos concatenados com nomes iguais serão mesclados em uma única camada no documento resultante se esta propriedade for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setMergeDuplicateOutlines {#setMergeDuplicateOutlines-boolean-}
```
public void setMergeDuplicateOutlines(boolean value)
```

Se true, contornos duplicados são mesclados.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOptimizeSize {#setOptimizeSize-boolean-}
```
public void setOptimizeSize(boolean value)
```

Obtém ou define a bandeira de otimização.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setOwnerPassword {#setOwnerPassword-java.lang.String-}
Define a senha do proprietário se o arquivo Pdf de entrada estiver criptografado. Esta propriedade ainda não foi implementada.

### setPreserveUserRights {#setPreserveUserRights-boolean-}
```
public void setPreserveUserRights(boolean value)
```

Se verdadeiro, os direitos de usuário do primeiro documento são aplicados ao documento concatenado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRemoveSignatures {#setRemoveSignatures-boolean-}
```
public final void setRemoveSignatures(boolean value)
```

Se verdadeiro, todas as assinaturas serão removidas dos campos (os campos permanecerão); caso contrário, você pode obter assinaturas inválidas.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Define as opções de salvamento quando o resultado é armazenado como HttpServletResponse. Valor padrão: PdfSaveOptions.

### setTryMergeAdjacentSameBackgroundImages {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```

Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo em mosaico iguais colocadas próximas umas das outras.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages |  | valor booleano |

### setUniqueSuffix {#setUniqueSuffix-java.lang.String-}
<p> Define o formato do sufixo que é adicionado ao nome do campo para torná-lo único quando os formulários são concatenados. Esta string deve conter a substring %NUM% que será substituída por números. Por exemplo, se UniqueSuffix = "ABC%NUM%" então para o campo "fieldName" os nomes serão: fieldNameABC1, fieldNameABC2, fieldNameABC3 etc. </p> <hr> <pre> PdfFileEditor ed = new PdfFileEditor(); ed.setUniqueSuffix ( "_%NUM%"); </pre>

### setUseDiskBuffer {#setUseDiskBuffer-boolean-}
```
public final void setUseDiskBuffer(boolean value)
```

Se esta opção for usada, o documento de destino será salvo no disco periodicamente e concatenações subsequentes serão aplicadas a ele como atualizações incrementais.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### splitFromFirst {#splitFromFirst-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide a partir do início até o local especificado e salva a parte frontal no Stream de saída. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileOutputStream("out.pdf"); pfe.splitFromFirst(sourceStream, 5, outStream); </pre> <hr> Os streams NÃO são fechados após esta operação.

### splitFromFirst {#splitFromFirst-java.lang.String-int-java.lang.String-}
<p> Divide o arquivo Pdf da primeira página até o local especificado e salva a parte frontal como um novo arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitFromFirst("input.pdf", 5, "out.pdf"); </pre>

### splitToBulks {#splitToBulks-java.io.InputStream-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToBulks {#splitToBulks-java.lang.String-int:A:A-}
Divide o arquivo Pdf em vários documentos. Os documentos podem ser de página única ou de múltiplas páginas.

### splitToEnd {#splitToEnd-java.io.InputStream-int-java.io.OutputStream-}
<p> Divide a partir do local especificado e salva a parte traseira como um novo Stream de arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); InputStream sourceStream = new FileInputStream("file1.pdf"); OutputStream outStream = new FileInputStream("out.pdf"); pfe.splitToEnd(sourceStream, 5, outStream); </pre> <hr> Os streams NÃO são fechados após esta operação, a menos que CloseConcatedStreams seja especificado.

### splitToEnd {#splitToEnd-java.lang.String-int-java.lang.String-}
<p> Divide a partir do local e salva a parte traseira como um novo arquivo. </p> <hr> <pre> PdfFileEditor pfe = new PdfFileEditor(); pfe.splitToEnd("input.pdf", 5, "out.pdf"); </pre>

### splitToPages {#splitToPages-java.io.InputStream-}
Divide o arquivo Pdf em documentos de página única.

### splitToPages {#splitToPages-java.io.InputStream-java.lang.String-}
Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado.

### splitToPages {#splitToPages-java.lang.String-}
Divide o arquivo PDF em documentos de página única.

### splitToPages {#splitToPages-java.lang.String-java.lang.String-}
Divida o arquivo Pdf em documentos de página única e salve-o no caminho especificado.
