---
title: "page_merge_layers"
second_title: "Aspose.PDF para Rust via C++"
description: "Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado."
type: docs
url: /pt/rust-cpp/organize/page_merge_layers/
---

_Mescla todas as camadas da página em uma única camada com o nome da nova camada especificado._

```rust
pub fn page_merge_layers(&self, num: i32, new_layer_name: &str) -> Result<(), PdfError>
```

**Arguments**
  * **num** - the page number (1-based)
  * **new_layer_name** - the name of the new layer after merging

**Returns**
  * **Ok(())** - if the operation succeeds
  * **Err(PdfError)** - if the operation fails

**Example**

```rust
use asposepdf::Document;

fn main() -> Result<(), Box<dyn std::error::Error>> {
    // Abrir um PDF-document a partir de um arquivo
    let pdf = Document::open("sample.pdf")?;

    // Mesclar todas as camadas da página em uma única camada com o nome da nova camada especificado
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Salvar o documento PDF aberto anteriormente com um novo nome de arquivo
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```