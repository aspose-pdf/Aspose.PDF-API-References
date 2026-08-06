---
title: "flatten"
second_title: "Aspose.PDF para Rust vía C++"
description: "Aplana el documento PDF."
type: docs
url: /es/rust-cpp/organize/flatten/
---

_Aplana el documento PDF._

```rust
pub fn flatten(&self) -> Result<(), PdfError>
```

**Arguments**


**Returns**
  * **Ok(())** - if the operation succeeds
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