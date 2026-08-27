---
title: "com.aspose.pdf.devices"
linktitle: "com.aspose.pdf.devices"
second_title: "Referência da API Aspose.PDF para Java"
description: "O pacote com.aspose.pdf.devices fornece classes que são usadas para representar o documento como imagem(s) ou texto simples."
type: docs
weight: 140
url: /pt/java/com.aspose.pdf.devices/
---
O pacote com.aspose.pdf.devices fornece classes que são usadas para representar o documento como imagem(s) ou texto simples.

## Classes

| Classe | Descrição |
| --- | --- |
| [BmpDevice](./bmpdevice/) | Representa um dispositivo de imagem que ajuda a salvar páginas de documentos pdf em bmp. |
| [Device](./device/) | Classe abstrata para todos os tipos de dispositivos. O dispositivo é usado para representar o documento pdf em algum formato. Por exemplo, a página do documento pode ser representada como imagem ou texto. |
| [DicomDevice](./dicomdevice/) | Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf no formato Dicom. |
| [DocumentDevice](./documentdevice/) | Classe abstrata para todos os dispositivos que são usados para processar todo o documento pdf. |
| [EmfDevice](./emfdevice/) | Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em emf. |
| [FormPresentationMode](./formpresentationmode/) | Usado para especificar o modo de apresentação do formulário ao imprimir ou converter documentos pdf em imagem. |
| [GifDevice](./gifdevice/) | Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em gif. |
| [GraphicsDevice](./graphicsdevice/) | Representa um dispositivo de imagem que ajuda a renderizar as páginas do documento pdf em gráficos. |
| [ImageDevice](./imagedevice/) | Uma classe abstrata para dispositivos de imagem. |
| [InternalHelper](./internalhelper/) |  |
| [JpegDevice](./jpegdevice/) | Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em jpeg. |
| [Margins](./margins/) | Esta classe representa as margens de uma imagem. |
| [PageDevice](./pagedevice/) | Classe abstrata para todos os dispositivos que são usados para processar uma determinada página do documento pdf. |
| [PngDevice](./pngdevice/) | Representa um dispositivo de imagem que ajuda a salvar as páginas do documento pdf em png. |
| [Resolution](./resolution/) | Representa uma classe para armazenar a resolução da imagem. |
| [TextDevice](./textdevice/) | <p> Representa uma classe para converter páginas de documentos pdf em texto. </p> <hr> <pre> O exemplo demonstra como extrair texto na primeira página do documento PDF. Document doc = new Document(inFile); String extractedText; ByteArrayOutputStream ms = new ByteArrayOutputStream(); try { // cria dispositivo de texto TextDevice device = new TextDevice(); // converte a página e salva o texto no fluxo device.process(doc.getPages().get_Item(1), ms); // usa o texto extraído extractedText = Encoding.getUnicode().getString(ms.toByteArray()); ms.close(); } catch (IOException e) { e.printStackTrace(); } </pre> <hr> <p> O objeto {@code TextDevice} é basicamente usado para extrair texto da página pdf. </p> |
| [ThumbnailDevice](./thumbnaildevice/) | Representa um dispositivo de imagem que salva as páginas do documento pdf em imagem em miniatura. |
| [TiffDevice](./tiffdevice/) | Esta classe ajuda a salvar as páginas do documento pdf, uma a uma, em uma única imagem tiff. |
| [TiffSettings](./tiffsettings/) | Esta classe representa as configurações para importar pdf para Tiff. |
| [TiffSettings.IndexedConversionType](./tiffsettings.indexedconversiontype/) | Classe que representa tipos de conversão indexados |
## Enums

| Enum | Descrição |
| --- | --- |
| [ColorDepth](./colordepth/) | Usado para especificar o valor do parâmetro passado para um dispositivo de imagem Tiff. |
| [CompressionType](./compressiontype/) | Usado para especificar o valor do parâmetro passado para um dispositivo de imagem Tiff. |
| [ShapeType](./shapetype/) | Este enum representa o tipo de forma para as imagens extraídas. |
