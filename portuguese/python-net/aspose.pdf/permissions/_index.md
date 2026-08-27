---
title: "Permissões"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Este enum representa as permissões do usuário para um PDF."
type: docs
weight: 6560
url: /pt/python-net/aspose.pdf/permissions/
---

## Permissions enumeration

Este enum representa as permissões do usuário para um PDF.

## Members
| Nome do membro | Descrição |
| :- | :- |
| PRINT_DOCUMENT | (Manipuladores de segurança da revisão 2) Imprimir o documento.<br/>            (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento <br/>            (possivelmente não no nível de qualidade mais alto, <br/>            dependendo se [PRINTING_QUALITY](/pdf/python-net/aspose.pdf/permissions/) também está definido). |
| MODIFY_CONTENT | Modificar o conteúdo do documento por operações diferentes <br/>            daquelas controladas por  [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/), <br/>            [FILL_FORM](/pdf/python-net/aspose.pdf/permissions/), e 11. |
| EXTRACT_CONTENT | (Manipuladores de segurança da revisão 2) Copiar ou de outra forma extrair <br/>            texto e gráficos do documento, incluindo a extração <br/>            de texto e gráficos (em apoio à acessibilidade para usuários <br/>            com deficiências ou para outros fins).<br/>            (Manipuladores de segurança da revisão 3 ou superior) Copiar ou de outra forma <br/>            extrair texto e gráficos do documento por operações <br/>            diferentes daquelas controladas por [EXTRACT_CONTENT_WITH_DISABILITIES](/pdf/python-net/aspose.pdf/permissions/). |
| MODIFY_TEXT_ANNOTATIONS | Adicionar ou modificar anotações de texto, preencher campos de formulário interativos, <br/>            e, se [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) também estiver definido, criar ou modificar campos de formulário interativos <br/>            (incluindo campos de assinatura). |
| FILL_FORM | (Manipuladores de segurança da revisão 3 ou superior) Preencher campos de formulário interativos existentes <br/>            (incluindo campos de assinatura), mesmo se <br/>            [MODIFY_TEXT_ANNOTATIONS](/pdf/python-net/aspose.pdf/permissions/) estiver desmarcado. |
| EXTRACT_CONTENT_WITH_DISABILITIES | (Manipuladores de segurança da revisão 3 ou superior) Extrair texto e <br/>            gráficos (em apoio à acessibilidade para usuários com deficiências <br/>            ou para outros fins). |
| ASSEMBLE_DOCUMENT | (Manipuladores de segurança da revisão 3 ou superior) Montar o documento <br/>            (inserir, girar ou excluir páginas e criar marcadores ou imagens em miniatura <br/>            ), mesmo se [MODIFY_CONTENT](/pdf/python-net/aspose.pdf/permissions/) estiver desmarcado. |
| PRINTING_QUALITY | (Manipuladores de segurança da revisão 3 ou superior) Imprimir o documento para <br/>            uma representação a partir da qual uma cópia digital fiel do conteúdo PDF <br/>            poderia ser gerada. Quando este bit está desmarcado (e o bit 3 está definido), <br/>            a impressão é limitada a uma representação de baixo nível da aparência, <br/>            possivelmente com qualidade degradada. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

