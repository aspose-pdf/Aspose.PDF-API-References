---
title: "page_replace_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Substitui texto na página."
type: docs
url: /pt/rust-cpp/organize/page_replace_text/
---

_Substitui texto na página._

```rust
pub fn page_replace_text(&self, num: i32, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **find_text** - the text fragment to search
  * **replace_text** - the text fragment to replace

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Substituir texto na página
    pdf.page_replace_text(1, "PDF", "TXT")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_replace_text.pdf")?;

    Ok(())
}

```