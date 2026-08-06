---
title: "page_merge_layers"
second_title: "Aspose.PDF para Rust vía C++"
description: "Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado."
type: docs
url: /es/rust-cpp/organize/page_merge_layers/
---

_Fusiona todas las capas de la página en una sola capa con el nombre de capa nuevo especificado._

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
    // Abrir un PDF-documento desde un archivo
    let pdf = Document::open("sample.pdf")?;

    // Fusionar todas las capas de la página en una sola capa con el nombre de capa nuevo especificado
    pdf.page_merge_layers(1, "New Layer Name")?;

    // Guardar el PDF-documento previamente abierto con un nuevo nombre de archivo
    pdf.save_as("sample_page1_merge_layers.pdf")?;

    Ok(())
}

```