---
title: "set_license"
second_title: "Aspose.PDF para Rust via C++"
description: "Define a licença usando o nome do arquivo."
type: docs
url: /pt/rust-cpp/core/set_license/
---

_Define a licença usando o nome do arquivo._

```rust
pub fn set_license(&self, filename: &str) -> Result<(), PdfError>
```

**Arguments**
  * **filename** - the path to the license-file

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um documento PDF com nome de arquivo
    let pdf = Document::open("sample.pdf")?;

    // Definir licença com nome do arquivo
    pdf.set_license("Aspose.PDF.RustViaCPP.lic")?;

    // Agora você pode trabalhar com o documento PDF licenciado
    // ...

    Ok(())
}

```