---
title: "page_rotate"
second_title: "Aspose.PDF para Rust via C++"
description: "Gira uma página no documento PDF."
type: docs
url: /pt/rust-cpp/organize/page_rotate/
---

_Gira uma página no documento PDF._

```rust
pub fn page_rotate(&self, num: i32, rotation: Rotation) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **rotation** - rotation angle as enum `Rotation`: `None`, `On90`, `On180`, `On270`, or `On360`

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::{Document, Rotation};

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Girar página
    pdf.page_rotate(1, Rotation::On180)?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_rotate.pdf")?;

    Ok(())
}

```