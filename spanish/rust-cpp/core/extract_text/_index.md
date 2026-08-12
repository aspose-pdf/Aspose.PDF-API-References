---
title: "extract_text"
second_title: "Aspose.PDF para Rust vía C++"
description: "Devuelve el contenido del PDF-documento como texto plano."
type: docs
url: /es/rust-cpp/core/extract_text/
---

_Devuelve el contenido del PDF-documento como texto plano._

```rust
pub fn extract_text(&self) -> Result<String, PdfError>
```

**Arguments**


**Returns**
  * **Ok(String)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir un documento PDF con nombre de archivo
    let pdf = Document::open("sample.pdf")?;

    // Devolver el contenido del PDF-documento como texto plano
    let txt = pdf.extract_text()?;

    // Imprimir texto extraído
    println!("Extracted text:\n{}", txt);

    Ok(())
}

```