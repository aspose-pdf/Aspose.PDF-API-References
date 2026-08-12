---
title: "cortar"
second_title: "Aspose.PDF para Rust via C++"
description: "Recorta páginas de um documento PDF."
type: docs
url: /pt/rust-cpp/organize/crop/
---

_Recorta páginas de um documento PDF._

```rust
pub fn crop(&self, margin: f64) -> Result<(), PdfError>
```

**Arguments**
  * **margin** - pages margins

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Recortar páginas de um documento PDF
    pdf.crop(10.5)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_crop.pdf")?;

    Ok(())
}

```