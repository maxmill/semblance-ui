# Semblance - Sensible defaults for the semantic web

Demo - http://maxmill.github.io/semblance/

## get started
```
    npm i semblance
    bower i semblance
```
## roadmap

  - add more common adaptive classes and form/table/navigation variants
  - add support for more preprocessors

### element defaults
```
<figcaption>
<figure>
<summary>
<time>
<address>

tables  - <col> <colgroup> <caption>
forms   - <select> <option> <optiongroup>
```
### role default styles
```
banner          - top navbar
heading         - header font styles and bottom margin
presentation    - something like bootstrap's well

navigation      - (w/ .vertical .horizontal classes)
  menu        -
  menubar     - sidenav(left or right)
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
