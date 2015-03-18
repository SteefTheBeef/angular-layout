# angular-layout

Directives for common layout components in Twitter bootstrap. 
Fast and beautiful template building and great for prototyping.

## Buttons

Buttons are available in four sizes lg, normal, sm and xs

#### Danger button
```
<btn-danger-lg>Large</btn-danger-lg>
<btn-danger>Normal</btn-danger>
<btn-danger-sm>Small</btn-danger-sm>
<btn-danger-xs>Extra small</btn-danger-xs>
```
Instead of this
```
<button type="button" class="btn btn-danger btn-lg">Large</button>
```
and so forth...
#### Default button
``<btn-default>Normal</btn-default>``

Add ``-lg``, ``-sm`` or ``-xs`` at the end of the tag for different sizing, this applies to all button types.

#### Info button
``<btn-info>Normal</btn-info>``

#### Primary button
``<btn-primary>Normal</btn-primary>``

#### Warning button
``<btn-warning>Normal</btn-warning>``

**Button group** - `<btn-group>...</btn-group>`

versus 

``<div class="btn-group" role="group" aria-label="button group">...</div>``

#### Button group vertical
``<btn-group-vertical>...</btn-group-vertical>`` 

versus 

``<div class="btn-group-vertical" role="group" aria-label="vertical button group">...</div>``

#### Button toolbar
``<btn-toolbar>...</btn-toolbar>`` 

versus 

``<div class="btn-toolbar" role="group" aria-label="button toolbar"></div>``
