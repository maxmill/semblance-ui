# Semblance - Sensible defaults for the semantic web

Demo - http://maxmill.github.io/semblance-ui/

## Getting Started
```
bower i semblance-ui (or via npm)
```


### Lean build (6KB minified, 2KB gzipped)
reset, default element styles(forms,lists,tables,typography) generic float/button/text classes
```
minified css: semblance-ui/css/lean.css
```

### UI build (13KB minified, 3KB gzipped)
```
minified css: semblance-ui/css/ui.css
```
utilities/classes
```
grid: .row, .column
padding: .pad-top-sm, .padding-md, etc
margin: .margin-lg, .margin-left-xl, .margin-right-xxl, etc,
menubar: .nav,
input-dropdown: .input-dropdown
top-navbar: nav\[role=navigation\], .nav-title .nav-icon
z-depths: .z-depths-(1 to 5)
```


### Extending

```
@import "path/to/semblance-ui/scss/lean";
```
or
```
@import "path/to/semblance-ui/scss/ui";
```
then
```
@import "your-scss-styles";
```

### Theming

```
@import "path/to/semblance-ui/scss/_core.scss"; // functions, variables, mixins

@import "your-variables";  // use functions to calculate variable values

@import "path/to/semblance-ui/scss/_lean.scss"

@import "path/to/semblance-ui/scss/_ui.scss" sub-components can also be imported individually

@import "your-scss-styles"; override styles, leverage mixins, functions

variables
// sizes- xs,sm,md,lg,xl,xxl
// color- initial,primary,primary-complement,secondary,secondary-complement
// palettes- red,green,purple,yellow,blue,orange with variants for dark, light, bright
```

### todo - more element defaults
```
<figcaption>
<figure>
<summary>
<time>
<address>

tables  - <col> <colgroup> <caption>
forms   - <select> <option> <optiongroup>
```

### todo - role default styles
```
heading         - header font styles and bottom margin
presentation    - something like bootstrap's well

navigation      - (w/ .vertical .horizontal classes)
  toolbar     - component context navigation

separator       - (w/ flex .vertical .horizontal classes)

search
tooltip
alert           - notification message
dialog          - confirm modal

tablist         - <dl>
tab             - <dt>
tabpanel        - <dd>
```
