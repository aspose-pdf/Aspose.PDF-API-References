---
title: "rotate"
second_title: "Aspose.PDF para Rust via C++"
description: "Gira o PDF-document."
type: docs
url: /pt/rust-cpp/organize/rotate/
---

_Gira o PDF-document._

```rust
pub fn rotate(&self, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Girar PDF-document
    pdf.rotate(Rotation::On270)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_rotate.pdf")?;

    Ok(())
}

```