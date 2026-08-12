---
title: "page_grayscale"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte uma página para preto e branco."
type: docs
url: /pt/rust-cpp/organize/page_grayscale/
---

_Converte uma página para preto e branco._

```rust
pub fn page_grayscale(&self, num: i32) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter página para preto e branco
    pdf.page_grayscale(1)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_grayscale.pdf")?;

    Ok(())
}

```