# angular-layout

Directives for common layout components in Twitter bootstrap. 
Fast and beautiful template building and great for prototyping.

## Alerts
**alert success** - `<alert-success>Way to go!</alert-success>`   
**alert info** - `<alert-info>{{data.info}}</alert-info>`  
**alert warning** - `<alert-warning>hey, this is not good!</alert-warning>`  
**alert danger** - `<alert-danger>danger zone!</alert-danger>` 

## Form elements
**form group** - `<form-group>...</form-group>`    
**form horizontal** - `<form-horizontal>...</form-horizontal>`  
**form inline** - `<form-inline>...</form-inline>`  
**input group** - `<input-group>...</input-group>`  
**input group addon** - `<input-group-addon>$<input-group-addon>`  

## Grid elements
**row** - `<row>...</row>`  
**cell** - `<cell>...</cell>`

### Cell sizing and positioning

**lg1** to **lg12** is equivalent to classes **col-lg-1** to **col-lg-12.**   
Can be used either as an attribute `<cell lg1>` or as a class `<cell class="lg12">`

**lg-offset1** to **lg-offset12** is equivalent to classes **col-lg-offset-1** to **col-lg-offset-12.**  
As an attribute `<cell lg-offset1>` or as a class `<cell class="lg-offset12">`

**lg-pull1** to **lg-pull12** is equivalent to classes **col-lg-pull-1** to **col-lg-pull-12.**  
As an attribute `<cell lg-pull1>` or as a class `<cell class="lg-pull12">`

**lg-push1** to **lg-push12** is equivalent to classes **col-lg-push-1** to **col-lg-push-12.**  
As an attribute `<cell lg-push1>` or as a class `<cell class="lg-push12">`

**md1-md12, md**

## Misc
**badge** - `<badge>{{count}}</badge>`  
**blockquote reverse** - `<blockquote-reverse>text...</blockquote-reverse>`  
**breadcrumb** - `<breadcrumb><li>...</li></breadcrumb>`  
**caret** - `<caret></caret>`  
**container** - `<container></container>`  
**container fluid** - `<container-fluid></container-fluid>`  
**jumbotron** - `<jumbotron>...content...</jumbotron>`  
**page header** - `<page-header>Page title</page-header>`  
**well** - `<well>...content...</well>`  
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

**Default button** - `<btn-default>Normal</btn-default>`

Add ``-lg``, ``-sm`` or ``-xs`` at the end of the tag for different sizing, this applies to all button types.

**Info button** - `<btn-info>Normal</btn-info>`  
**Primary button**- `<btn-primary>Normal</btn-primary>`  
**Warning button** - `<btn-warning>Normal</btn-warning>`  
**Button group** - `<btn-group>...</btn-group>`  

**Button group vertical** - `<btn-group-vertical>...</btn-group-vertical>`  
**Button toolbar** - `<btn-toolbar>...</btn-toolbar>`     

