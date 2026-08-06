---
title: "replace_font"
second_title: "Aspose.PDF para Rust via C++"
description: "Substitui a fonte em um PDF-document."
type: docs
url: /pt/rust-cpp/organize/replace_font/
---

_Substitui a fonte em um PDF-document._

```rust
pub fn replace_font(&self, find_font_name: &str, replace_font_name: &str) -> Result<(), PdfError>
```

**Arguments**
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

    // Substituir fonte em um documento PDF.
    pdf.replace_font("Helvetica", "Courier")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_replace_font.pdf")?;

    Ok(())
}

```