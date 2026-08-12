---
title: "remove_tables"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove tabelas do PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_tables/
---

_Remove tabelas do PDF-document._

```rust
pub fn remove_tables(&self) -> Result<(), PdfError>
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

    // Remover tabelas do PDF-document
    pdf.remove_tables()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_tables.pdf")?;

    Ok(())
}

```