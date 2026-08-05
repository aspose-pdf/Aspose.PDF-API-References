---
title: "FormDataConverter"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para converter dados de um formato para outro.<br/>            Pode converter os dados em fdf/xml/pdf/xfdf para OLEDB/OdbcDB.<br/>            Também pode converter os dados em OLEDB/OdbcDB para dados em fdf/xml/xfdf.<br/>            Pode converter o fdf para xml com a tag \"hard-named\"."
type: docs
weight: 100
url: /pt/python-net/aspose.pdf.facades/formdataconverter/
---

## FormDataConverter class

Representa uma classe para converter dados de um formato para outro.<br/>            Pode converter os dados em fdf/xml/pdf/xfdf para OLEDB/OdbcDB.<br/>            Também pode converter os dados em OLEDB/OdbcDB para dados em fdf/xml/xfdf.<br/>            Pode converter o fdf para xml com a tag "hard-named".

O tipo FormDataConverter expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| FormDataConverter() | Inicializa uma nova instância da classe FormDataConverter |
## Propriedades
| Nome | Descrição |
| :- | :- |
| create_missing_field | ConvertToDataTable criará o campo necessário se ele não existir na Tabela. |
| replace_existing_table | ImportIntoDatabase descartará a tabela existente e criará uma nova tabela se esta propriedade for definida como verdadeira. |
| clear_table_before_export | ExportFromData limpará a tabela antes da exportação de dados. |
| create_missing_table | ImportIntoDatabase criará a tabela se ela não existir. |
## Métodos
| Nome | Descrição |
| :- | :- |
| convert_xml_to_fdf(source_xml, dest_fdf) | Converta o arquivo de dados de formulário XML de importação/exportação para o formato FDF. |
| convert_fdf_to_xml(source_fdf, dest_xml) | Converta o arquivo FDF para XML. |
| convert_to_data_table(source_streams, source_type) | Converta arquivos de streams em tabela. |
| import_into_data_base(connect_string, db_type) | Importa dados da tabela para o banco de dados. |
| export_from_data_base(connect_string, db_type) | Exporta dados do banco de dados para a tabela. |
| convert_to_streams(dest_stream, dest_type) | Converter dados da tabela em fluxos. |
| conver_to_streams(dest_stream, dest_type) | Este método está obsoleto. Por favor, use ConvertToStreams() em vez disso. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

