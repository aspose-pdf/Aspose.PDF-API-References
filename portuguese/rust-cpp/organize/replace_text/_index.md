---
title: "replace_text"
second_title: "Aspose.PDF para Rust via C++"
description: "Substitui texto."
type: docs
url: /pt/rust-cpp/organize/replace_text/
---

_Substitui texto._

```rust
pub fn replace_text(&self, find_text: &str, replace_text: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Substituir texto no documento PDF
    pdf.replace_text("PDF", "TXT")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_replace_text.pdf")?;

    Ok(())
}

```