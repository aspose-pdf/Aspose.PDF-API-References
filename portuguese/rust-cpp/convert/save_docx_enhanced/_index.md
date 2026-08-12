---
title: "save_docx_enhanced"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o documento PDF aberto anteriormente como um documento DOCX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis)."
type: docs
url: /pt/rust-cpp/convert/save_docx_enhanced/
---

_Converte e salva o documento PDF aberto anteriormente como um documento DOCX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis)._

```rust
pub fn save_docx_enhanced(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter e salvar o documento PDF aberto anteriormente como documento DocX com Modo de Reconhecimento Avançado (tabelas e parágrafos totalmente editáveis)
    pdf.save_docx_enhanced("sample_enhanced.docx")?;

    Ok(())
}

```