---
title: "embed_fonts"
second_title: "Aspose.PDF para Rust via C++"
description: "Incorpora fontes em um PDF-document."
type: docs
url: /pt/rust-cpp/organize/embed_fonts/
---

_Incorpora fontes em um PDF-document._

```rust
pub fn embed_fonts(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Incorporar fontes em um PDF-document
    pdf.embed_fonts()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_embed_fonts.pdf")?;

    Ok(())
}

```