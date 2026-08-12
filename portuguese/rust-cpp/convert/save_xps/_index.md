---
title: "save_xps"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o documento PDF aberto anteriormente como um documento XPS."
type: docs
url: /pt/rust-cpp/convert/save_xps/
---

_Converte e salva o documento PDF aberto anteriormente como um documento XPS._

```rust
pub fn save_xps(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the output file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Converter e salvar o documento PDF aberto anteriormente como documento XPS
    pdf.save_xps("sample.xps")?;

    Ok(())
}

```