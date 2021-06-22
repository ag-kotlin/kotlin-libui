[libui.ktx](../README.md) / [Checkbox](README.md)

# Checkbox

`class Checkbox : `[`Control`](../-control/README.md)`<`[`uiCheckbox`](../../libui/ui-checkbox.md)`>`

Wrapper class for [uiCheckbox](../../libui/ui-checkbox.md) - a checkbox widget.

### Constructors

| Name | Summary |
|---|---|
| [Checkbox](-checkbox.md) | `Checkbox(label: String)`<br>Wrapper class for [uiCheckbox](../../libui/ui-checkbox.md) - a checkbox widget. |

### Properties

| Name | Summary |
|---|---|
| [label](label.md) | `var label: String`<br>The static text of the checkbox. |
| [value](value.md) | `var value: Boolean`<br>Whether the checkbox is checked or unchecked. Defaults to `false`. |

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
| [action](action.md) | `fun action(block: `[`Checkbox`](README.md)`.() -> Unit): Unit`<br>Function to be run when the user clicks the Checkbox. Only one function can be registered at a time. |

### Inherited functions

| Name | Summary |
|---|---|
| [disable](../-control/disable.md) | `fun disable(): Unit`<br>Disables the Control. |
| [dispose](../-control/dispose.md) | `open fun dispose(): Unit`<br>Dispose and free all allocated resources. |
| [enable](../-control/enable.md) | `fun enable(): Unit`<br>Enables the Control. |
| [getHandle](../-control/get-handle.md) | `fun getHandle(): ULong`<br>Returns the OS-level handle associated with this Control. |
| [hide](../-control/hide.md) | `fun hide(): Unit`<br>Hides the Control. Hidden controls do not participate in layout (that is, Box, GridPane, etc. does not reserve space for hidden controls). |
| [isEnabled](../-control/is-enabled.md) | `fun isEnabled(): Boolean`<br>Whether the Control is enabled. |
| [isEnabledToUser](../-control/is-enabled-to-user.md) | `fun isEnabledToUser(): Boolean`<br>Whether the Control and all parents are enabled. |
| [isVisible](../-control/is-visible.md) | `fun isVisible(): Boolean`<br>Whether the Control is visible. |
| [show](../-control/show.md) | `fun show(): Unit`<br>Shows the Control. |
