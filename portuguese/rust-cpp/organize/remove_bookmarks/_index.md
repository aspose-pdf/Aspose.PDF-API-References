---
title: "remove_bookmarks"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove marcadores do PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_bookmarks/
---

_Remove marcadores do PDF-document._

```rust
pub fn remove_bookmarks(&self) -> Result<(), PdfError>
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

    // Remover marcadores do documento PDF
    pdf.remove_bookmarks()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_bookmarks.pdf")?;

    Ok(())
}

```