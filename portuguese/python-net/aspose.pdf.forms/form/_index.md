---
title: "Form"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa o objeto de formulário."
type: docs
weight: 110
url: /pt/python-net/aspose.pdf.forms/form/
---

## Form class

Classe que representa o objeto de formulário.

O tipo Form expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_synchronized | Retorna true se o objeto for thread-safe. |
| sync_root | Retorna o objeto de sincronização. |
| auto_recalculate | Se definido, todos os campos do formulário serão recalculados quando qualquer campo for alterado. O valor padrão é true. Defina como false para aumentar o desempenho ao preencher o formulário com grande quantidade de campos calculados. |
| auto_restore_form | Se definido, campos de formulário ausentes serão criados automaticamente se estiverem presentes nas anotações. |
| default_resources | Obtém os recursos padrão colocados neste formulário. |
| default_appearance | Obtém ou define a aparência padrão do formulário (objeto que descreve a fonte padrão, tamanho do texto e cor para os campos no formulário). |
| xfa | Obtém os dados XFA do formulário (se houver). |
| ignore_needs_rendering | Se esta propriedade for verdadeira, o valor da chave NeedsRendering será ignorado durante a conversão <br/>            do formulário XFA para o formulário padrão. O padrão é falso. |
| remove_permission | Se esta propriedade for verdadeira, o dicionário "Perms" será removido do documento PDF após a conversão <br/>            de documentos dinâmicos para padrão. O dicionário "Perms" pode conter regras que atrapalham a exibição da seleção de <br/>            campos obrigatórios no leitor Adobe Acrobat.<br/>            O padrão é falso. |
| emulate_requierd_groups | Se esta propriedade for verdadeira, retângulos vermelhos adicionais serão desenhados ao redor dos contêineres de elementos Xfa exclGroup obrigatórios<br/>            Esta propriedade foi introduzida devido à ausência de equivalentes para o exclGroup durante a conversão da representação Xfa de formulários <br/>            para o padrão.<br/>            O padrão é falso. |
| type | Obtém o tipo do formulário. Valores possíveis são: Standard, Static, Dynamic. |
| fields | Obtém a lista de todos os campos no nível mais baixo do formulário hierárquico. |
| signatures_exist | Se definido, o documento contém pelo menos um campo de assinatura. |
| signatures_append_only | Se definido, o documento contém assinaturas que podem ser invalidadas se o arquivo for salvo (escrito) de forma que altere seu conteúdo anterior, <br/>            ao contrário de uma atualização incremental. |
| sign_dependent_elements_rendering_mode_when_converted | Os formulários podem conter informações de assinatura, ou seja, podem ser assinados ou não assinados.<br/>              E a visualização do formulário às vezes deve depender de o formulário estar assinado ou não.<br/>              Esta propriedade informa ao conversor de formulários (por exemplo, durante a conversão de formulário XFA para formulário padrão)<br/>              se o formulário resultante deve ser renderizado como assinado ou como não assinado. |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o campo do formulário pelo índice do campo. |
## Métodos
| Nome | Descrição |
| :- | :- |
| delete(field) | Exclui o campo do formulário. |
| delete(field_name) | Exclui o campo do formulário pelo seu nome. |
| add(field, page_number) | Adiciona um campo ao formulário. |
| add(field) | Adiciona um campo ao formulário. |
| add(field, partial_name, page_number) | Adiciona um novo campo ao formulário; se este campo já estiver colocado em outro ou neste formulário, uma cópia do campo é criada. |
| has_field(field) | Verifique se o formulário já possui o campo especificado. |
| has_field(field_name) | Determina se o campo com o nome especificado já foi adicionado ao Formulário. |
| copy_to(array, index) | Copia os campos colocados no formulário para um array. |
| flatten() | Remove todos os campos do formulário e coloca seus valores diretamente na página. |
| add_field_appearance(field, page_number, rect) | Adiciona uma aparência adicional do campo à página especificada do documento na localização especificada. |
| get_fields_in_rect(rect) | Retorna os campos dentro do retângulo especificado. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

