---
title: "set_meta_info"
second_title: "Aspose.PDF para Rust via C++"
description: "Define o valor da meta-informação do PDF-document."
type: docs
url: /pt/rust-cpp/core/set_meta_info/
---

_Define o valor da meta-informação do PDF-document._

```rust
pub fn set_meta_info(&self, key: &str, value: &str) -> Result<(), PdfError>
```

**Arguments**
  * **key** - the key whose value to set
  * **value** - the value to be set

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Definir o valor da meta-informação do PDF-document
    pdf.set_meta_info("Author", "Aspose")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_set_meta_info.pdf")?;

    Ok(())
}

```