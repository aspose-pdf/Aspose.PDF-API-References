---
title: "add_text_footer"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona texto no rodapé de um PDF-document."
type: docs
url: /pt/rust-cpp/organize/add_text_footer/
---

_Adiciona texto no rodapé de um PDF-document._

```rust
pub fn add_text_footer(&self, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **footer** - the pages footer

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Adicionar texto no rodapé de um documento PDF
    pdf.add_text_footer("FOOTER")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_add_text_footer.pdf")?;

    Ok(())
}

```