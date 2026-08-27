---
title: "AppearanceDictionary"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página."
type: docs
weight: 60
url: /pt/python-net/aspose.pdf.annotations/appearancedictionary/
---

## AppearanceDictionary class

Dicionário de aparência da anotação que especifica como a anotação deve ser apresentada visualmente na página.

O tipo AppearanceDictionary expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_fixed_size | Obtém um valor que indica se o dicionário tem tamanho fixo. |
| keys | Gets keys of the dictionary. If appearance dictionary has subditionaries, then [keys](/pdf/python-net/aspose.pdf.annotations/appearancedictionary/) contains (N | R | Valores de D).state,<br/>            onde N - aparência normal, R - aparência ao passar o mouse, D - aparência pressionada e state - o nome do estado<br/>            (ex.: On, Off para caixas de seleção). |
| valores | Obtém a lista de valores do dicionário. <br/>            A coleção de resultados contém a lista de objetos XForm. |
| is_synchronized | Obtém um valor que indica se o acesso ao dicionário está sincronizado (thread safe). |
| sync_root | Obtém um objeto que pode ser usado para sincronizar o acesso ao dicionário. |
## Métodos
| Nome | Descrição |
| :- | :- |
| add(key, value) | Adiciona um elemento com a chave e o valor fornecidos. |
| add(key, value) | Adiciona X form para a chave especificada. |
| copy_to(array, index) | Copia os elementos do dicionário para um Array, começando em um índice específico do Array. |
| contains_key(key) | Determina se este dicionário contém a chave especificada. |
| remove(key) | Remove chave do dicionário. |
| try_get_value(key, value) | Tenta encontrar a chave no dicionário e recupera o valor se encontrado. |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

