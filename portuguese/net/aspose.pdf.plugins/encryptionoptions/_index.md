---
title: Class EncryptionOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.EncryptionOptions. Representa Opções de Criptografia para o plugin de Segurança
type: docs
weight: 8540
url: /pt/net/aspose.pdf.plugins/encryptionoptions/
---
## Classe EncryptionOptions

Representa Opções de Criptografia para o plugin [`Security`](../security/).

```csharp
public class EncryptionOptions : OrganizerBaseOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [EncryptionOptions](encryptionoptions/)(string, string, DocumentPrivilege, CryptoAlgorithm) | Inicializa uma nova instância do objeto `EncryptionOptions` com opções padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Fecha fluxos de entrada após a operação ser concluída. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Fecha fluxos de saída após a operação ser concluída. |
| [CryptoAlgorithm](../../aspose.pdf.plugins/encryptionoptions/cryptoalgorithm/) { get; set; } | Algoritmo criptográfico, veja [`CryptoAlgorithm`](./cryptoalgorithm/) para detalhes. |
| [DocumentPrivilege](../../aspose.pdf.plugins/encryptionoptions/documentprivilege/) { get; set; } | Permissões do documento, veja [`Permissions`](../../aspose.pdf/permissions/) para detalhes. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Retorna a coleção de dados do plugin OrganizerOptions. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtém a coleção de alvos adicionados para salvar os resultados da operação. |
| [OwnerPassword](../../aspose.pdf.plugins/encryptionoptions/ownerpassword/) { get; set; } | Senha do proprietário. |
| [UserPassword](../../aspose.pdf.plugins/encryptionoptions/userpassword/) { get; set; } | Senha do usuário. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin PdfOrganizer. |

### Veja Também

* classe [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)