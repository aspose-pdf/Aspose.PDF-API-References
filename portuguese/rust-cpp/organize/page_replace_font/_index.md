---
title: "page_replace_font"
second_title: "Aspose.PDF para Rust via C++"
description: "Substitui fonte na página."
type: docs
url: /pt/rust-cpp/organize/page_replace_font/
---

_Substitui fonte na página._

```rust
pub fn page_replace_font(&self, num: i32, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_font_name** - the font name to search
  * **replace_font_name** - the font name to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Substituir fonte na página
    pdf.page_replace_font(1, "Times-BoldItalic", "Helvetica-Bold")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_replace_font.pdf")?;

    Ok(())
}

```