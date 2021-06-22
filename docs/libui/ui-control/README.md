[libui](../README.md) / [uiControl](README.md)

# uiControl

`class uiControl : CStructVar`

### Types

| Name | Summary |
|---|---|
| [Companion](-companion.md) | `companion object Companion : Type` |

### Constructors

| Name | Summary |
|---|---|
| [uiControl](ui-control.md) | `uiControl(rawPtr: NativePtr)` |

### Properties

| Name | Summary |
|---|---|
| [Destroy](-destroy.md) | `var Destroy: CPointer<CFunction<(CPointer<uiControl>?) -> Unit>>?` |
| [Disable](-disable.md) | `var Disable: CPointer<CFunction<(CPointer<uiControl>?) -> Unit>>?` |
| [Enable](-enable.md) | `var Enable: CPointer<CFunction<(CPointer<uiControl>?) -> Unit>>?` |
| [Enabled](-enabled.md) | `var Enabled: CPointer<CFunction<(CPointer<uiControl>?) -> Int>>?` |
| [Handle](-handle.md) | `var Handle: CPointer<CFunction<(CPointer<uiControl>?) -> uintptr_t>>?` |
| [Hide](-hide.md) | `var Hide: CPointer<CFunction<(CPointer<uiControl>?) -> Unit>>?` |
| [OSSignature](-o-s-signature.md) | `var OSSignature: uint32_t` |
| [Parent](-parent.md) | `var Parent: CPointer<CFunction<(CPointer<uiControl>?) -> CPointer<uiControl>?>>?` |
| [SetParent](-set-parent.md) | `var SetParent: CPointer<CFunction<(CPointer<uiControl>?, CPointer<uiControl>?) -> Unit>>?` |
| [Show](-show.md) | `var Show: CPointer<CFunction<(CPointer<uiControl>?) -> Unit>>?` |
| [Signature](-signature.md) | `var Signature: uint32_t` |
| [Toplevel](-toplevel.md) | `var Toplevel: CPointer<CFunction<(CPointer<uiControl>?) -> Int>>?` |
| [TypeSignature](-type-signature.md) | `var TypeSignature: uint32_t` |
| [Visible](-visible.md) | `var Visible: CPointer<CFunction<(CPointer<uiControl>?) -> Int>>?` |

### Extension functions

| Name | Summary |
|---|---|
| [fill](../../libui.ktx.draw/fill.md) | `fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.fill(mode: `[`uiDrawFillMode`](../ui-draw-fill-mode.md)`, brush: `[`Brush`](../../libui.ktx.draw/-brush/README.md)`, block: `[`Path`](../../libui.ktx.draw/-path/README.md)`.() -> Unit)`<br>`fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.fill(brush: `[`Brush`](../../libui.ktx.draw/-brush/README.md)`, block: `[`Path`](../../libui.ktx.draw/-path/README.md)`.() -> Unit)`<br>Draw a path filled with a color. |
| [stroke](../../libui.ktx.draw/stroke.md) | `fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.stroke(mode: `[`uiDrawFillMode`](../ui-draw-fill-mode.md)`, brush: `[`Brush`](../../libui.ktx.draw/-brush/README.md)`, stroke: `[`Stroke`](../../libui.ktx.draw/-stroke/README.md)`, block: `[`Path`](../../libui.ktx.draw/-path/README.md)`.() -> Unit)`<br>`fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.stroke(brush: `[`Brush`](../../libui.ktx.draw/-brush/README.md)`, stroke: `[`Stroke`](../../libui.ktx.draw/-stroke/README.md)`, block: `[`Path`](../../libui.ktx.draw/-path/README.md)`.() -> Unit)`<br>Draw a path in the context. |
| [text](../../libui.ktx.draw/text.md) | `fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.text(string: `[`AttributedString`](../../libui.ktx.draw/-attributed-string/README.md)`, defaultFont: `[`Font`](../../libui.ktx.draw/-font/README.md)`, width: Double, align: `[`uiDrawTextAlign`](../ui-draw-text-align.md)`, x: Double, y: Double)`<br>draws formatted text with the top-left point at (`x`, `y`). |
| [transform](../../libui.ktx.draw/transform.md) | `fun `[`DrawContext`](../../libui.ktx/-draw-context.md)`.transform(block: `[`Matrix`](../../libui.ktx.draw/-matrix/README.md)`.() -> Unit)`<br>Apply a different transform matrix to the context. |
