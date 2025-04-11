---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Permissions. Este enum representa as permissões dos usuários para um pdf
type: docs
weight: 8480
url: /pt/net/aspose.pdf/permissions/
---
## Enumeração de Permissões

Este enum representa as permissões do usuário para um pdf.

```csharp
[Flags]
public enum Permissions
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| PrintDocument | `4` | (Manipuladores de segurança da revisão 2) Imprimir o documento. (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento (possivelmente não na mais alta qualidade, dependendo se PrintingQuality também está definido). |
| ModifyContent | `8` | Modificar o conteúdo do documento por operações diferentes daquelas controladas por ModifyTextAnnotations, FillForm e 11. |
| ExtractContent | `10` | (Manipuladores de segurança da revisão 2) Copiar ou extrair de outra forma texto e gráficos do documento, incluindo a extração de texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins). (Manipuladores de segurança da revisão 3 ou superior) Copiar ou extrair de outra forma texto e gráficos do documento por operações diferentes daquelas controladas por ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Adicionar ou modificar anotações de texto, preencher campos de formulário interativos e, se ModifyContent também estiver definido, criar ou modificar campos de formulário interativos (incluindo campos de assinatura). |
| FillForm | `100` | (Manipuladores de segurança da revisão 3 ou superior) Preencher campos de formulário interativos existentes (incluindo campos de assinatura), mesmo que ModifyTextAnnotations esteja claro. |
| ExtractContentWithDisabilities | `200` | (Manipuladores de segurança da revisão 3 ou superior) Extrair texto e gráficos (em apoio à acessibilidade para usuários com deficiência ou para outros fins). |
| AssembleDocument | `400` | (Manipuladores de segurança da revisão 3 ou superior) Montar o documento (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura), mesmo que ModifyContent esteja claro. |
| PrintingQuality | `800` | (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento para uma representação da qual uma cópia digital fiel do conteúdo PDF poderia ser gerada. Quando este bit está claro (e o bit 3 está definido), a impressão é limitada a uma representação de baixo nível da aparência, possivelmente de qualidade degradada. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)