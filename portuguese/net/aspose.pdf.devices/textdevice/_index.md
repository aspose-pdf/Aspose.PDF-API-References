---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TextDevice. Representa a classe para converter páginas de documentos pdf em texto
type: docs
weight: 3680
url: /pt/net/aspose.pdf.devices/textdevice/
---
## Classe TextDevice

Representa a classe para converter páginas de documentos pdf em texto.

```csharp
public sealed class TextDevice : PageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Inicializa uma nova instância de `TextDevice` com o modo de formatação de texto bruto e codificação de texto Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Inicializa uma nova instância de `TextDevice` para a codificação especificada. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Inicializa uma nova instância de `TextDevice` com opções de extração de texto. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Inicializa uma nova instância de `TextDevice` para a codificação especificada com opções de extração de texto. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Obtém ou define a codificação do texto extraído. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Obtém ou define as opções de extração de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Converte a página e a salva como um fluxo de texto. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

## Observações

O objeto `TextDevice` é basicamente usado para extrair texto de uma página pdf.

## Exemplos

O exemplo demonstra como extrair texto na primeira página do documento PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Veja Também

* classe [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)