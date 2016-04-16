

#Semblance - Sensible defaults for the semantic web



roadmap
  - add more default styles for some html5 roles, elements
  - add more common adaptive classes and form/table variants
  - add support for more preprocessors


### element defaults
```
<figcaption>
<figure>
<main>
<mark>
<progress>
<summary>
<time>
<address>
<hr>
<em>
<small>

tables  - <col> <colgroup> <caption>
forms   - <select> <option> <optiongroup>
```
### role default styles
```
banner          - top navbar
navigation      - (w/ .vertical .horizontal classes)
  menu        -
  menubar     - sidenav(left or right)
  toolbar     - component context navigation
heading         - header font styles and bottom margin
presentation    - something like bootstrap's well
separator       - (w/ flex .vertical .horizontal classes)

search
tooltip
alert           - notification message
dialog          - confirm modal

tablist         - <dl>
tab             - <dt>
tabpanel        - <dd>
```
