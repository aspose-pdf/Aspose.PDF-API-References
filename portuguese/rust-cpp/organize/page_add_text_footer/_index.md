---
title: "page_add_text_footer"
second_title: "Aspose.PDF para Rust via C++"
description: "Adiciona texto no rodapé da página."
type: docs
url: /pt/rust-cpp/organize/page_add_text_footer/
---

_Adiciona texto no rodapé da página._

```rust
pub fn page_add_text_footer(&self, num: i32, footer: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
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

    // Adicionar texto no rodapé da página
    pdf.page_add_text_footer(1, "FOOTER")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_add_text_footer.pdf")?;

    Ok(())
}

```