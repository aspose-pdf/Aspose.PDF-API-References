---
title: "Aspose.PDF para Rust via C++"
description: "Aspose.PDF para Rust via C++"
keywords:  "Rust, PDF, PDF toolkit, pdf, convert, processing"
tags: ['pdf-to-jpg', 'pdf-to-png', 'pdf-convert', 'pdf-tools']
weight: 40
url: /pt/rust-cpp/
type: docs
is_root: true
---

> Aspose.PDF for Rust via C++ allows developers manipulate them PDF files directly in the Rust.

# Estruturas

## Document
Document representa um documento PDF.

```rust
pub struct Document { /* private fields */ }
```

# Implementations

## Convert from PDF functions

| Função | Descrição |
| -------- | ----------- |
| [save_docx](./convert/save_docx/) | Converter e salvar o PDF-documento previamente aberto como documento DocX. |
| [save_doc](./convert/save_doc/) | Converter e salvar o PDF-documento previamente aberto como documento Doc. |
| [save_xlsx](./convert/save_xlsx/) | Converter e salvar o PDF-documento previamente aberto como documento XlsX. |
| [save_txt](./convert/save_txt/) | Converter e salvar o PDF-documento previamente aberto como documento Txt. |
| [save_pptx](./convert/save_pptx/) | Converter e salvar o PDF-documento previamente aberto como documento PptX. |
| [save_xps](./convert/save_xps/) | Converter e salvar o PDF-documento previamente aberto como documento Xps. |
| [save_tex](./convert/save_tex/) | Converter e salvar o PDF-documento previamente aberto como documento TeX. |
| [save_epub](./convert/save_epub/) | Converter e salvar o PDF-documento previamente aberto como documento Epub. |
| [save_booklet](./convert/save_booklet/) | Converter e salvar o PDF-documento previamente aberto como PDF em formato de livreto. |
| [save_n_up](./convert/save_n_up/) | Converter e salvar o PDF-documento previamente aberto como PDF N-Up. |
| [save_markdown](./convert/save_markdown/) | Converter e salvar o PDF-documento previamente aberto como documento Markdown. |
| [save_tiff](./convert/save_tiff/) | Converter e salvar o PDF-documento previamente aberto como documento Tiff. |
| [save_docx_enhanced](./convert/save_docx_enhanced/) | Converter e salvar o PDF-documento previamente aberto como documento DocX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis). |
| [save_svg_zip](./convert/save_svg_zip/) | Converter e salvar o PDF-documento previamente aberto como arquivo SVG. |
| [export_fdf](./convert/export_fdf/) | Exportar do PDF-documento previamente aberto com AcroForm para documento FDF. |
| [export_xfdf](./convert/export_xfdf/) | Exportar do PDF-documento previamente aberto com AcroForm para documento XFDF. |
| [export_xml](./convert/export_xml/) | Exportar do PDF-documento previamente aberto com AcroForm para documento XML. |
| [page_to_jpg](./convert/page_to_jpg/) | Converter e salvar a página especificada como imagem Jpg. |
| [page_to_png](./convert/page_to_png/) | Converter e salvar a página especificada como imagem Png. |
| [page_to_bmp](./convert/page_to_bmp/) | Converter e salvar a página especificada como imagem Bmp. |
| [page_to_tiff](./convert/page_to_tiff/) | Converter e salvar a página especificada como imagem Tiff. |
| [page_to_svg](./convert/page_to_svg/) | Converter e salvar a página especificada como imagem Svg. |
| [page_to_pdf](./convert/page_to_pdf/) | Converter e salvar a página especificada como documento PDF. |
| [page_to_dicom](./convert/page_to_dicom/) | Converter e salvar a página especificada como imagem DICOM. |


## Organize PDF functions

| Função | Descrição |
| -------- | ----------- |
| [optimize](./organize/optimize/) | Otimizar o conteúdo do documento PDF. |
| [optimize_resource](./organize/optimize_resource/) | Otimizar os recursos do documento PDF. |
| [grayscale](./organize/grayscale/) | Converter documento PDF para preto e branco. |
| [rotate](./organize/rotate/) | Rotacionar documento PDF. |
| [set_background](./organize/set_background/) | Definir a cor de fundo do documento PDF usando valores RGB. |
| [repair](./organize/repair/) | Reparar documento PDF. |
| [replace_text](./organize/replace_text/) | Substituir texto no documento PDF |
| [add_page_num](./organize/add_page_num/) | Adicionar número de página a um documento PDF |
| [add_text_header](./organize/add_text_header/) | Adicionar texto no cabeçalho de um documento PDF |
| [add_text_footer](./organize/add_text_footer/) | Adicionar texto no rodapé de um documento PDF |
| [flatten](./organize/flatten/) | Aplanar documento PDF |
| [remove_annotations](./organize/remove_annotations/) | Remover anotações do documento PDF |
| [remove_attachments](./organize/remove_attachments/) | Remover anexos do documento PDF |
| [remove_blank_pages](./organize/remove_blank_pages/) | Remover páginas em branco do documento PDF |
| [remove_bookmarks](./organize/remove_bookmarks/) | Remover marcadores do documento PDF |
| [remove_hidden_text](./organize/remove_hidden_text/) | Remover texto oculto do documento PDF |
| [remove_images](./organize/remove_images/) | Remover imagens do documento PDF |
| [remove_javascripts](./organize/remove_javascripts/) | Remover scripts Java do documento PDF |
| [remove_tables](./organize/remove_tables/) | Remover tabelas de um documento PDF. |
| [remove_watermarks](./organize/remove_watermarks/) | Remover marcas d'água do documento PDF. |
| [add_watermark](./organize/add_watermark/) | Adicionar marca d'água ao documento PDF. |
| [embed_fonts](./organize/embed_fonts/) | Incorporar fontes a um documento PDF. |
| [unembed_fonts](./organize/unembed_fonts/) | Desincorporar fontes de um documento PDF. |
| [optimize_file_size](./organize/optimize_file_size/) | Otimizar o tamanho do documento PDF com qualidade de compressão de imagem. |
| [remove_text_headers](./organize/remove_text_headers/) | Remover cabeçalhos de texto de um documento PDF. |
| [remove_text_footers](./organize/remove_text_footers/) | Remover rodapés de texto de um documento PDF. |
| [crop](./organize/crop/) | Cortar páginas de um documento PDF. |
| [replace_font](./organize/replace_font/) | Substituir fonte em um documento PDF. |
| [convert](./organize/convert/) | Converter um documento PDF em um documento PDF com o formato PDF especificado |
| [validate](./organize/validate/) | Validar um documento PDF quanto à conformidade com o formato PDF |
| [remove_pdfa_compliance](./organize/remove_pdfa_compliance/) | Remover a conformidade PDF/A de um documento PDF |
| [remove_pdfua_compliance](./organize/remove_pdfua_compliance/) | Remover a conformidade PDF/UA de um documento PDF |
| [is_pdfa_compliant](./organize/is_pdfa_compliant/) | Obter se um documento PDF está em conformidade PDF/A |
| [is_pdfua_compliant](./organize/is_pdfua_compliant/) | Obter se um documento PDF está em conformidade PDF/UA |
| [page_rotate](./organize/page_rotate/) | Rotacionar uma página no documento PDF. |
| [page_set_size](./organize/page_set_size/) | Definir o tamanho de uma página no documento PDF. |
| [page_grayscale](./organize/page_grayscale/) | Converter página para preto e branco. |
| [page_add_text](./organize/page_add_text/) | Adicionar texto na página. |
| [page_replace_text](./organize/page_replace_text/) | Substituir texto na página |
| [page_add_page_num](./organize/page_add_page_num/) | Adicionar número da página na página |
| [page_add_text_header](./organize/page_add_text_header/) | Adicionar texto no cabeçalho da página |
| [page_add_text_footer](./organize/page_add_text_footer/) | Adicionar texto no rodapé da página |
| [page_remove_annotations](./organize/page_remove_annotations/) | Remover anotações na página. |
| [page_remove_hidden_text](./organize/page_remove_hidden_text/) | Remover texto oculto na página. |
| [page_remove_images](./organize/page_remove_images/) | Remover imagens na página. |
| [page_remove_tables](./organize/page_remove_tables/) | Remover tabelas na página. |
| [page_remove_watermarks](./organize/page_remove_watermarks/) | Remover marcas d'água na página. |
| [page_add_watermark](./organize/page_add_watermark/) | Adicionar marca d'água na página. |
| [page_remove_text_headers](./organize/page_remove_text_headers/) | Remover cabeçalhos de texto na página. |
| [page_remove_text_footers](./organize/page_remove_text_footers/) | Remover rodapés de texto na página. |
| [page_crop](./organize/page_crop/) | Cortar uma página. |
| [page_replace_font](./organize/page_replace_font/) | Substituir fonte na página. |
| [page_merge_layers](./organize/page_merge_layers/) | Mesclar todas as camadas na página em uma única camada com o nome da nova camada especificado. |
| [page_layers](./organize/page_layers/) | Obter nomes das camadas na página. |


## Core PDF functions

| Função | Descrição |
| -------- | ----------- |
| [new](./core/new/) | Criar um novo documento PDF. |
| [open](./core/open/) | Abrir um documento PDF com nome de arquivo. |
| [save](./core/save/) | Salvar o documento PDF aberto anteriormente. |
| [save_as](./core/save_as/) | Salvar o documento PDF aberto anteriormente com novo nome de arquivo. |
| [set_license](./core/set_license/) | Definir licença com nome de arquivo. |
| [extract_text](./core/extract_text/) | Retornar o conteúdo do documento PDF como texto simples. |
| [word_count](./core/word_count/) | Retornar a contagem de palavras no documento PDF. |
| [character_count](./core/character_count/) | Retornar a contagem de caracteres no documento PDF. |
| [append](./core/append/) | Anexar páginas de outro documento PDF. |
| [append_pages](./core/append_pages/) | Anexar páginas selecionadas de outro documento PDF. |
| [merge_documents](./core/merge_documents/) | Criar um novo documento PDF mesclando os documentos PDF fornecidos. |
| [split_document](./core/split_document/) | Criar vários novos documentos PDF extraindo páginas do documento PDF fonte. |
| [split](./core/split/) | Criar vários novos documentos PDF extraindo páginas do documento PDF atual. |
| [split_at_page](./core/split_at_page/) | Dividir o documento PDF em dois novos documentos PDF. |
| [split_at](./core/split_at/) | Dividir o documento PDF atual em dois novos documentos PDF. |
| [bytes](./core/bytes/) | Retornar o conteúdo do documento PDF como um vetor de bytes. |
| [get_meta_info](./core/get_meta_info/) | Obter o valor da informação de metadados do documento PDF. |
| [set_meta_info](./core/set_meta_info/) | Definir valor da informação de metadados do PDF-document. |
| [clear_meta_info](./core/clear_meta_info/) | Limpar todos os valores de informação de metadados do PDF-document. |
| [is_linearized](./core/is_linearized/) | Obter um valor que indica se o documento está linearizado. |
| [page_add](./core/page_add/) | Adicionar nova página no PDF-document. |
| [page_insert](./core/page_insert/) | Inserir nova página na posição especificada no PDF-document. |
| [page_delete](./core/page_delete/) | Excluir página especificada no PDF-document. |
| [page_count](./core/page_count/) | Retornar o número de páginas no PDF-document. |
| [page_word_count](./core/page_word_count/) | Retornar a contagem de palavras na página especificada do PDF-document. |
| [page_character_count](./core/page_character_count/) | Retornar a contagem de caracteres na página especificada do PDF-document. |
| [page_is_blank](./core/page_is_blank/) | Retornar se a página está em branco no PDF-document. |


## Security
| Função | Descrição |
| -------- | ----------- |
| [open_with_password](./security/open_with_password/) | Abrir um PDF-document protegido por senha. |
| [encrypt](./security/encrypt/) | Criptografar PDF-document. |
| [decrypt](./security/decrypt/) | Descriptografar PDF-document. |
| [set_permissions](./security/set_permissions/) | Definir permissões para PDF-document. |
| [get_permissions](./security/get_permissions/) | Obter permissões atuais do PDF-document. |
| [is_encrypted](./security/is_encrypted/) | Obter status de criptografia do PDF-document. |
| [sign_pkcs7](./security/sign_pkcs7/) | Assinar um PDF-document usando assinaturas digitais PKCS#7. |
| [sign_pkcs7_detached](./security/sign_pkcs7_detached/) | Assinar um PDF-document usando assinaturas digitais PKCS#7 Detached. |
| [is_signed](./security/is_signed/) | Obter status de assinatura do PDF-document. |
| [remove_signs](./security/remove_signs/) | Remover assinaturas do PDF-document. |


## Miscellaneous

| Função | Descrição |
| -------- | ----------- |
| [about](./miscellaneous/about/) | Retornar informações de metadados sobre o Aspose.PDF para Rust via C++. |



# Structs secondary

## ProductInfo contains metadata about the Aspose.PDF for Rust via C++.
```rust
#[derive(Debug, Deserialize)]
pub struct ProductInfo {
    #[serde(rename = "product")]
    pub product: String,

    #[serde(rename = "family")]
    pub family: String,

    #[serde(rename = "version")]
    pub version: String,

    #[serde(rename = "releasedate")]
    pub release_date: String,

    #[serde(rename = "producer")]
    pub producer: String,

    #[serde(rename = "islicensed")]
    pub is_licensed: bool,
}
```

## Bitflag set representing PDF permission capabilities.
```rust
bitflags! {
    /// Conjunto de bitflags que representa as capacidades de permissão de PDF.
    #[derive(Copy, Clone, PartialEq, Eq)]
    pub struct Permissions: i32 {
        const PRINT_DOCUMENT                    = 1 << 2;  // 4
        const MODIFY_CONTENT                    = 1 << 3;  // 8
        const EXTRACT_CONTENT                   = 1 << 4;  // 16
        const MODIFY_TEXT_ANNOTATIONS           = 1 << 5;  // 32
        const FILL_FORM                         = 1 << 8;  // 256
        const EXTRACT_CONTENT_WITH_DISABILITIES = 1 << 9;  // 512
        const ASSEMBLE_DOCUMENT                 = 1 << 10; // 1024
        const PRINTING_QUALITY                  = 1 << 11; // 2048
    }
}
```

# Enums

## Enumeration of possible page size values.
```rust
pub enum PageSize {
    /// Tamanho A0.
    A0 = 0,
    /// Tamanho A1.
    A1 = 1,
    /// Tamanho A2.
    A2 = 2,
    /// tamanho A3.
    A3 = 3,
    /// tamanho A4.
    A4 = 4,
    /// tamanho A5.
    A5 = 5,
    /// tamanho A6.
    A6 = 6,
    /// tamanho B5.
    B5 = 7,
    /// tamanho PageLetter.
    PageLetter = 8,
    /// tamanho PageLegal.
    PageLegal = 9,
    /// tamanho PageLedger.
    PageLedger = 10,
    /// tamanho P11x17.
    P11x17 = 11,
}
```

## Enumeration of possible rotation values.
```rust
pub enum Rotation {
    /// Não rotacionado.
    None = 0,
    /// Rotacionado em 90 graus no sentido horário.
    On90 = 1,
    /// Rotacionado em 180 graus.
    On180 = 2,
    /// Rotacionado em 270 graus no sentido horário.
    On270 = 3,
    /// Rotacionado em 360 graus no sentido horário.
    On360 = 4,
}
```

## An enumeration of possible crypto algorithms.
```rust
pub enum CryptoAlgorithm {
    /// RC4 com comprimento de chave 40.
    RC4x40 = 0,
    /// RC4 com comprimento de chave 128.
    RC4x128 = 1,
    /// AES com comprimento de chave 128.
    AESx128 = 2,
    /// AES com comprimento de chave 256.
    AESx256 = 3,
}
```

## An enumeration of possible PDF format standards.
```rust
pub enum PdfFormat {
    /// formato PDF/A-1a.
    PDF_A_1A = 0,
    /// formato PDF/A-1b.
    PDF_A_1B = 1,
    /// formato PDF/A-2a.
    PDF_A_2A = 2,
    /// formato PDF/A-3a.
    PDF_A_3A = 3,
    /// formato PDF/A-2b.
    PDF_A_2B = 4,
    /// formato PDF/A-2u.
    PDF_A_2U = 5,
    /// formato PDF/A-3b.
    PDF_A_3B = 6,
    /// formato PDF/A-3u.
    PDF_A_3U = 7,
    /// versão Adobe 1.0.
    V_1_0 = 8,
    /// versão Adobe 1.1.
    V_1_1 = 9,
    /// versão Adobe 1.2.
    V_1_2 = 10,
    /// versão Adobe 1.3.
    V_1_3 = 11,
    /// versão Adobe 1.4.
    V_1_4 = 12,
    /// versão Adobe 1.5.
    V_1_5 = 13,
    /// versão Adobe 1.6.
    V_1_6 = 14,
    /// versão Adobe 1.7.
    V_1_7 = 15,
    /// Padrão ISO PDF 2.0.
    V_2_0 = 16,
    /// formato PDF/UA-1.
    PDF_UA_1 = 17,
    /// formato PDF/X-1a:2001.
    PDF_X_1A_2001 = 18,
    /// formato PDF/X-1a.
    PDF_X_1A = 19,
    /// formato PDF/X-3.
    PDF_X_3 = 20,
    /// formato ZUGFeRD.
    ZUGFeRD = 21,
    /// formato PDF/A-4.
    PDF_A_4 = 22,
    /// formato PDF/A-4e.
    PDF_A_4E = 23,
    /// formato PDF/A-4f.
    PDF_A_4F = 24,
    /// formato PDF/X-4.
    PDF_X_4 = 25,
    /// formato PDF/E-1 (PDF 1.6).
    PDF_E_1 = 26,
}
```

## An enumeration of actions to take when a conversion error occurs.
```rust
pub enum ConvertErrorAction {
    /// Excluir elementos não conformes.
    Delete = 0,
    /// Não fazer nada, manter elementos não conformes.
    None = 1,
}
```

