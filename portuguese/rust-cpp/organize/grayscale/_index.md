---
title: "grayscale"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte o PDF-documento para preto e branco."
type: docs
url: /pt/rust-cpp/organize/grayscale/
---

_Converte o PDF-documento para preto e branco._

```rust
pub fn grayscale(&self) -> Result<(), PdfError>
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

    // Converter PDF-documento para preto e branco
    pdf.grayscale()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_grayscale.pdf")?;

    Ok(())
}

```