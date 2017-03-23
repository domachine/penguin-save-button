# penguin-save-button

A simple save button for penguin.js.

## Installation

	$ npm i -S penguin-save-button

Then edit your `package.json` file to include the component.

```json
{
  "penguin": {
    "components": {
      "SaveButton": "penguin-save-button"
    }
  }
}
```

## Usage

```html
<button data-component='SaveButton'>
  Save
</button>
```

This component registers an `onclick` handler on the target element and triggers `ctx.save()`.
