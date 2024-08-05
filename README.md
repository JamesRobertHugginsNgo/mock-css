# mock-css

v1.0.0

## button

Button style.

### Variables

Variable | Description
-- | --
--button--background-color | Background color.
--button--background-color--hover | Background color on hover.
--button--color | Text color.
--button--color--hover | Text color on hover.

### Modifiers

Class | Description
-- | --
button--link | For applying style on anchor elements (\<a>).

## flex-stack

Generic flex layout styles.

### Modifiers

Class | Description
-- | --
flex-stack--center | Adds align-items with `center`. Helpful for icons beside text.
flex-stack--compact | Overrides gulp with `0.5rem`. Allows for closer columns.
flex-stack--equal | Adds flex with `1` to child elements. Helpful for evenly distributed layout.
flex-stack--list | For applying the style to a list element.
flex-stack--space | Adds justify-content with `space-between`. Helpful for creating left and right columns, used for header and footer layout.
flex-stack--vertical | Adds flex-direction with `column`. Helpful for vertical layouts.
flex-stack--very-compact | Overrides gulp with `0.25rem`. Allows for much closer columns.

## flex-stack-field

Form field layout. Same as having `class="flex-stack flex-stack--vertical flex-stack--very-compact"`. Adds a small gap between the label, input and help-text.

## flex-stack-icon

Icon with text layout. Same as having `class="flex-stack flex-stack--center flex-stack--compact"`.

## flex-stack-layout

Header-footer layout. Same as having `class="flex-stack flex-stack--space"`.

## flex-stack-pills

Pills layout. Tabs layout. Same as having `class="flex-stack flex-stack--center flex-stack--middle"` with an additional border-bottom.

## flex-stack-row

Form row layout. Same as having `class="flex-stack flex-stack--equal"` with an additional margin-bottom and margin-top of `1rem`. Allows for multi-column forms.

## flex-stack-tabs

Tabs layout. Same as having `class="flex-stack flex-stack--equal"` with an additional border-bottom.

### Variables

Variable | Description
-- | --
--flex-stack-tabs--border-color | Border color.

## help-text

Form help text style. Should be used inside flex-stack-field.

## label

Form label style. Should be used inside flex-stack-field. Use an inner span element to display optional label.

## page-width

Centers content on the page with a maximum width.

## panel

"Card" style with a header and body.

### Elements

Class | Description
-- | --
panel__body | Body.
panel__header | Optional header.

## pill

Represents the individual pill. Should be used inside flex-stack-pills.

### Variables

Variable | Description
-- | --
--pill--background-color | Background color.
--pill--background-color--active | Background color when active.
--pill--color | Text color.
--pill--color--active | Text color when active.

## tab

Represents the individual tab. Should be used inside flex-stack-tabs.

### Variables

Variable | Description
-- | --
--tab--border-color | Border color for active tab. Default of --flex-stack-tabs--border-color value.

### Modifiers

Class | Description
-- | --
tab--active | Renders the tab as an active tab.

## text-box

Form text box style.

### Modifiers

Class | Description
-- | --
text-box--select | For applying style on select elements (\<select>) replacing the native style.
