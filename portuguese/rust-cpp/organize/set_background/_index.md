---
title: "set_background"
second_title: "Aspose.PDF para Rust via C++"
description: "Define a cor de fundo do documento PDF usando valores RGB."
type: docs
url: /pt/rust-cpp/organize/set_background/
---

_Define a cor de fundo do documento PDF usando valores RGB._

```rust
pub fn set_background(&self, r: i32, g: i32, b: i32) -> Result<(), PdfError>
```

**Arguments**
  * **r** - red component (0-255)
  * **g** - green component (0-255)
  * **b** - blue component (0-255)

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Definir a cor de fundo do documento PDF usando valores RGB
    pdf.set_background(200, 100, 101)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_set_background.pdf")?;

    Ok(())
}

```