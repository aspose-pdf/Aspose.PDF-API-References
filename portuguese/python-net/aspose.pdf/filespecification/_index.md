---
title: "FileSpecification"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa arquivo incorporado."
type: docs
weight: 360
url: /pt/python-net/aspose.pdf/filespecification/
---

## FileSpecification class

Classe que representa arquivo incorporado.

O tipo FileSpecification expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| FileSpecification(file) | Inicializa uma nova instância da classe FileSpecification |
| FileSpecification(stream, name) | Inicializa uma nova instância da classe FileSpecification |
| FileSpecification(file, description) | Inicializa uma nova instância da classe FileSpecification |
| FileSpecification(stream, name, description) | Inicializa uma nova instância da classe FileSpecification |
| FileSpecification(file_name, annot) | Inicializa uma nova instância da classe FileSpecification |
| FileSpecification() | Cria uma nova especificação de arquivo vazia. |
## Propriedades
| Nome | Descrição |
| :- | :- |
| codificação | Obtém ou define o formato de codificação.<br/>            Valores possíveis: Zip - o arquivo é compactado com ZIP, <br/>            None - o arquivo não é compactado. |
| include_contents | Se verdadeiro, o conteúdo do arquivo será incluído na especificação de arquivo. |
| encrypted_payload | Obtém a carga útil criptografada. |
| descrição | Obtém ou define o texto associado à especificação do arquivo. |
| af_relationship | Relacionamento de arquivo associado. |
| stream_contents | Obtém o conteúdo do arquivo como fluxo. <br/>            O conteúdo não é carregado na memória, o que permite reduzir o uso de memória.<br/>            Mas esse fluxo não suporta posicionamento nem a propriedade Length. Se precisar desses recursos, use a propriedade Contents em vez disso. |
| conteúdo | Obtém ou define o conteúdo do arquivo. <br/>            Esta propriedade retorna dados carregados na memória, o que pode causar exceção de falta de memória para dados grandes.<br/>            Para reduzir o uso de memória, use StreamContents. |
| params | Obtém os parâmetros do arquivo. |
| mime_type | Obtém o subtipo do arquivo incorporado |
| nome | Obtém ou define o nome da especificação do arquivo. |
| unicode_name | Obtém ou define o nome Unicode da especificação do arquivo. |
| file_system | Obtém ou define o nome do sistema de arquivos. |
## Métodos
| Nome | Descrição |
| :- | :- |
| get_value(key) | Obtém o parâmetro específico da aplicação. |
| set_value(key, value) | Define o parâmetro específico da aplicação. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

