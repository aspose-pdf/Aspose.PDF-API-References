---
title: "is_linearized"
second_title: "Aspose.PDF para Rust via C++"
description: "Obtém um valor que indica se o documento está linearizado."
type: docs
url: /pt/rust-cpp/core/is_linearized/
---

_Obtém um valor que indica se o documento está linearizado._

```rust
pub fn is_linearized(&self) -> Result<bool, PdfError>
```

**Arguments**


**Returns**
  * **Ok(bool)** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Obter um valor que indica se o documento está linearizado
    if pdf.is_linearized()? {
        println!("The PDF-document is linearized.");
    } else {
        println!("The PDF-document is non-linearized.");
    }

    Ok(())
}

```