---
title: "Font"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa o objeto de fonte."
type: docs
weight: 100
url: /pt/python-net/aspose.pdf.text/font/
---

## Font class

Representa o objeto de fonte.

O tipo Font expõe os seguintes membros:
## Propriedades
| Nome | Descrição |
| :- | :- |
| font_name | Obtém o nome da fonte do objeto [Font](/pdf/python-net/aspose.pdf.text/font/). |
| decoded_font_name | Às vezes, fontes PDF (geralmente fontes chinesas/japonesas/coreanas) podem ter um nome de fonte específico.<br/>            Esse nome é o valor da propriedade "BaseFont" da fonte PDF e, às vezes, essa propriedade<br/>            pode ser representada em forma hexadecimal. Se ler esse nome diretamente, ele pode aparecer<br/>            em forma não legível. Para obter uma forma legível, é necessário decodificar o nome da fonte<br/>            de acordo com regras específicas para essa fonte. <br/>            Esta propriedade retorna o nome da fonte decodificado, portanto use-a nos casos em que você encontrar <br/>            uma [font_name](/pdf/python-net/aspose.pdf.text/font/) não legível.<br/>            Se a propriedade [font_name](/pdf/python-net/aspose.pdf.text/font/) estiver em forma legível, esta propriedade será a mesma que <br/>            [font_name](/pdf/python-net/aspose.pdf.text/font/), então você pode usar esta propriedade em qualquer caso em que precise<br/>            obter o nome da fonte em forma legível. |
| base_font | Obtém o valor BaseFont do objeto de fonte PDF. Também conhecido como nome PostScript da fonte. |
| is_embedded | Obtém ou define um valor que indica se a fonte está incorporada.<br/>            Fonte baseada em IFont será automaticamente subconjunto e incorporada |
| is_subset | Obtém ou define um valor que indica se a fonte é um subconjunto.<br/>             Fonte baseada em IFont será automaticamente subconjunto e incorporada |
| is_accessible | Obtém indicando se a fonte está presente (instalada) no sistema. |
| font_options | Propriedades úteis para ajustar o comportamento da Fonte |
## Métodos
| Nome | Descrição |
| :- | :- |
| get_last_font_embedding_error() | Um objetivo deste método - retornar a descrição do erro se uma tentativa<br/>            de incorporar a fonte falhar. Se não houver casos de erro, ele retorna uma string vazia. |
| save(stream) | Salva a fonte no stream.<br/>            Observe que a fonte é salva em formato TTF intermediário destinado a ser usado apenas em uma cópia convertida do documento original.<br/>            O arquivo de fonte não se destina a ser usado fora do contexto do documento original. |
| measure_string(str, font_size) | Mede a string. |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

