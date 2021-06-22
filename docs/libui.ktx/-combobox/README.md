[libui.ktx](../README.md) / [Combobox](README.md)

# Combobox

`class Combobox : `[`Control`](../-control/README.md)`<`[`uiCombobox`](../../libui/ui-combobox.md)`>`

Wrapper class for [uiCombobox](../../libui/ui-combobox.md) - a drop down combo box that allow list selection only.

### Constructors

| Name | Summary |
|---|---|
| [Combobox](-combobox.md) | `Combobox()`<br>Wrapper class for [uiCombobox](../../libui/ui-combobox.md) - a drop down combo box that allow list selection only. |

### Properties

| Name | Summary |
|---|---|
| [value](value.md) | `var value: Int`<br>Return or set the current selected option by index. |

### Inherited properties

| Name | Summary |
|---|---|
| [enabled](../-control/enabled.md) | `var enabled: Boolean`<br>Whether the Control should be enabled or disabled. Defaults to `true`. |
| [parent](../-control/parent.md) | `var parent: `[`Control`](../-control/README.md)`<*>?`<br>Returns parent of the control or `null` for detached. |
| [toplevel](../-control/toplevel.md) | `val toplevel: Boolean`<br>Returns whether the control is a top level one or not. |
| [visible](../-control/visible.md) | `var visible: Boolean`<br>Whether the Control should be visible or hidden. Defaults to `true`. |

### Functions

| Name | Summary |
|---|---|
| [action](action.md) | `fun action(block: `[`Combobox`](README.md)`.() -> Unit)`<br>Function to be run when the user makes a change to the Combobox. Only one function can be registered at a time. |
| [item](item.md) | `fun item(text: String)`<br>Adds the named entry to the end of the combobox. If it is the first entry, it is automatically selected. |

### Inherited functions

| Name | Summary |
|---|---|
| [disable](../-control/disable.md) | `fun disable()`<br>Disables the Control. |
| [dispose](../-control/dispose.md) | `open fun dispose()`<br>Dispose and free all allocated resources. |
| [enable](../-control/enable.md) | `fun enable()`<br>Enables the Control. |
| [getHandle](../-control/get-handle.md) | `fun getHandle(): ULong`<br>Returns the OS-level handle associated with this Control. |
| [hide](../-control/hide.md) | `fun hide()`<br>Hides the Control. Hidden controls do not participate in layout (that is, Box, GridPane, etc. does not reserve space for hidden controls). |
| [isEnabled](../-control/is-enabled.md) | `fun isEnabled(): Boolean`<br>Whether the Control is enabled. |
| [isEnabledToUser](../-control/is-enabled-to-user.md) | `fun isEnabledToUser(): Boolean`<br>Whether the Control and all parents are enabled. |
| [isVisible](../-control/is-visible.md) | `fun isVisible(): Boolean`<br>Whether the Control is visible. |
| [show](../-control/show.md) | `fun show()`<br>Shows the Control. |
