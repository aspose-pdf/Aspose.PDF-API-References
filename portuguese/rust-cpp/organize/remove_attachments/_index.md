---
title: "remove_attachments"
second_title: "Aspose.PDF para Rust via C++"
description: "Remove anexos de PDF-document."
type: docs
url: /pt/rust-cpp/organize/remove_attachments/
---

_Remove anexos de PDF-document._

```rust
pub fn remove_attachments(&self) -> Result<(), PdfError>
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

    // Remover anexos do documento PDF
    pdf.remove_attachments()?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_remove_attachments.pdf")?;

    Ok(())
}

```