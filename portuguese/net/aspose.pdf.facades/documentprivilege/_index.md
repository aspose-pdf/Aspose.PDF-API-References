---
title: Class DocumentPrivilege
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.DocumentPrivilege. Representa os privilégios para acessar arquivos Pdf. Consulte PdfFileSecurity. Existem 4 maneiras de usar esta classe 1. Usando privilégio pré-definido diretamente. 2. Baseado em um privilégio pré-definido e alterando algumas permissões específicas. 3. Baseado em um privilégio pré-definido e alterando algumas combinações específicas de permissões do Adobe Professional. 4. Mistura a maneira 2 e a maneira 3.
type: docs
weight: 4230
url: /pt/net/aspose.pdf.facades/documentprivilege/
---
## Classe DocumentPrivilege

Representa os privilégios para acessar arquivos Pdf. Consulte [`PdfFileSecurity`](../pdffilesecurity/). Existem 4 maneiras de usar esta classe: 1. Usando privilégio pré-definido diretamente. 2. Baseado em um privilégio pré-definido e alterando algumas permissões específicas. 3. Baseado em um privilégio pré-definido e alterando algumas combinações específicas de permissões do Adobe Professional. 4. Mistura a maneira 2 e a maneira 3.

```csharp
public sealed class DocumentPrivilege : IComparable<object>
```

## Propriedades

| Nome | Descrição |
| --- | --- |
| static [AllowAll](../../aspose.pdf.facades/documentprivilege/allowall/) { get; } | Todos permitidos. |
| static [Assembly](../../aspose.pdf.facades/documentprivilege/assembly/) { get; } | Permite a montagem do arquivo. |
| static [Copy](../../aspose.pdf.facades/documentprivilege/copy/) { get; } | Permite copiar o arquivo. |
| static [DegradedPrinting](../../aspose.pdf.facades/documentprivilege/degradedprinting/) { get; } | Permite impressão degradada. |
| static [FillIn](../../aspose.pdf.facades/documentprivilege/fillin/) { get; } | Permite preencher formulários no arquivo. |
| static [ForbidAll](../../aspose.pdf.facades/documentprivilege/forbidall/) { get; } | Todos proibidos. |
| static [ModifyAnnotations](../../aspose.pdf.facades/documentprivilege/modifyannotations/) { get; } | Permite modificar anotações do arquivo. |
| static [ModifyContents](../../aspose.pdf.facades/documentprivilege/modifycontents/) { get; } | Permite modificar o arquivo. |
| static [Print](../../aspose.pdf.facades/documentprivilege/print/) { get; } | Permite imprimir o arquivo. |
| static [ScreenReaders](../../aspose.pdf.facades/documentprivilege/screenreaders/) { get; } | Permite leitura na tela apenas. |
| [AllowAssembly](../../aspose.pdf.facades/documentprivilege/allowassembly/) { get; set; } | Define a permissão que permite montagem ou não. true é permitido e false é proibido. |
| [AllowCopy](../../aspose.pdf.facades/documentprivilege/allowcopy/) { get; set; } | Define a permissão que permite copiar ou não. true é permitido e false é proibido. |
| [AllowDegradedPrinting](../../aspose.pdf.facades/documentprivilege/allowdegradedprinting/) { get; set; } | Define a permissão que permite impressão degradada ou não. true é permitido e false é proibido. |
| [AllowFillIn](../../aspose.pdf.facades/documentprivilege/allowfillin/) { get; set; } | Define a permissão que permite preencher formulários ou não. true é permitido e false é proibido. |
| [AllowModifyAnnotations](../../aspose.pdf.facades/documentprivilege/allowmodifyannotations/) { get; set; } | Define a permissão que permite modificar anotações ou não. true é permitido e false é proibido. |
| [AllowModifyContents](../../aspose.pdf.facades/documentprivilege/allowmodifycontents/) { get; set; } | Define a permissão que permite modificar conteúdos ou não. true é permitido e false é proibido. |
| [AllowPrint](../../aspose.pdf.facades/documentprivilege/allowprint/) { get; set; } | Define a permissão que permite imprimir ou não. true é permitido e false é proibido. |
| [AllowScreenReaders](../../aspose.pdf.facades/documentprivilege/allowscreenreaders/) { get; set; } | Define a permissão que permite leitores de tela ou não. true é permitido e false é proibido. |
| [ChangeAllowLevel](../../aspose.pdf.facades/documentprivilege/changeallowlevel/) { get; set; } | Obtém e define o nível de alteração dos privilégios do documento. Assim como as configurações de Alterações Permitidas do Adobe Professional. 0: Nenhum. 1: Inserir, Deletar e Rotacionar páginas. 2: Preencher campos de formulário e assinar campos de assinatura existentes. 3: Comentar, preencher campos de formulário e assinar campos de assinatura existentes. 4: Qualquer coisa, exceto extrair páginas. |
| [CopyAllowLevel](../../aspose.pdf.facades/documentprivilege/copyallowlevel/) { get; set; } | Obtém e define o nível de cópia dos privilégios do documento. Assim como as configurações de permissão do Adobe Professional. 0: Nenhum. 1: Habilitar acesso ao texto para dispositivos de leitura de tela para deficientes visuais. 2: Habilitar cópia de texto, imagens e outros conteúdos. |
| [PrintAllowLevel](../../aspose.pdf.facades/documentprivilege/printallowlevel/) { get; set; } | Obtém e define o nível de impressão dos privilégios do documento. Assim como as configurações de Impressão Permitida do Adobe Professional. 0: Nenhum. 1: Baixa Resolução (150 dpi). 2: Alta Resolução. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [CompareTo](../../aspose.pdf.facades/documentprivilege/compareto/)(object) | Compara dois objetos `DocumentPrivilege`. O objeto a ser comparado. Um inteiro assinado que indica os valores relativos desta instância e do valor. Menos que zero esta instância é menor que o valor. Zero esta instância é igual ao valor. Maior que zero esta instância é maior que o valor. |

## Exemplos

```csharp
[C#]	
//Way1: Using predefined privilege directly.
DocumentPrivilege privilege = DocumentPrivilege.Print;

//Way2: Based on a predefined privilege and change some specifical permissions.
DocumentPrivilege privilege = DocumentPrivilege.AllowAll;
privilege.AllowPrint = false;
privilege.AllowModifyContents = false;

//Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.PrintAllowLevel = 2;

//Way4: Mixes the way2 and way3
DocumentPrivilege privilege = DocumentPrivilege.ForbidAll;
privilege.ChangeAllowLevel = 1;
privilege.AllowPrint = true;

[Visual Basic]
'Way1: Using predefined privilege directly.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.Print 

'Way2: Based on a predefined privilege and change some specifical permissions.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.AllowAll 
privilege.AllowPrint = False
privilege.AllowModifyContents = False

'Way3: Based on a predefined privilege and change some specifical Adobe Professional permissions combination.
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.PrintAllowLevel = 2

'Way4: Mixes the way2 and way3
Dim privilege As DocumentPrivilege =  DocumentPrivilege.ForbidAll 
privilege.ChangeAllowLevel = 1
privilege.AllowPrint = True
```

### Veja Também

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)