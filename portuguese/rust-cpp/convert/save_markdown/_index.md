---
title: "save_markdown"
second_title: "Aspose.PDF para Rust via C++"
description: "Converte e salva o documento PDF previamente aberto como documento Markdown."
type: docs
url: /pt/rust-cpp/convert/save_markdown/
---

_Converte e salva o documento PDF previamente aberto como documento Markdown._

```rust
pub fn save_markdown(&self, filename: &str) -> Result<(), PdfError>
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

    // Converter e salvar o documento PDF previamente aberto como documento Markdown
    pdf.save_markdown("sample.md")?;

    Ok(())
}
```