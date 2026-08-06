---
title: "unembed_fonts"
second_title: "Aspose.PDF para Rust via C++"
description: "Desincorpora fontes de um PDF-document."
type: docs
url: /pt/rust-cpp/organize/unembed_fonts/
---

_Desincorpora fontes de um PDF-document._

```rust
pub fn unembed_fonts(&self) -> Result<(), PdfError>
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

    // Desincorpora fontes de um PDF-document
    pdf.unembed_fonts()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_unembed_fonts.pdf")?;

    Ok(())
}

```