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

**md1** to **md12**, **md-offset1** to **md-offset12**, **md-pull1** to **md-pull12**, **md-push1** to **md-push12**  
**sm1** to **sm12**, **sm-offset1** to **sm-offset12**, **sm-pull1** to **sm-pull12**, **sm-push1** to **sm-push12**   
**xs1** to **xs12**, **xs-offset1** to **xs-offset12**, **xs-pull1** to **xs-pull12**, **xs-push1** to **xs-push12**

**Example**
```
<row>
  <cell lg3 sm6>Left content</cell>
  <cell lg5 sm4>Middle content</cell>
  <cell lg4 sm2>Right content</cell>
</row>
```
this is equivalent to
```
<div class="row">
  <div class="col-lg-3 col-sm-6">Left content</div>
  <div class="col-lg-5 col-sm-4">Middle content</div>
  <div class="col-lg-4 col-sm-2">Right content</div>
</div>
```
## Lists
**dl horizontal** - `<dl-horizontal><dt>...</dt><dd>...</dd></dl-horizontal>`  
**list inline** - `<list-inline><li>...</li></list-inline>`  
**list unstyled** - `<list-unstyled><li>...</li></list-unstyled>` 

## Pagination 
**pagination** - `<pagination><li><a href="#">1</a></li></pagination>`  
**pager** - `<pager><li><a href="#">Previous</a></li><li><a href="#">Next</a></li></pager>` 

## Panels

In the simplest form: `<panel>This content will be placed in the body of the panel</panel>`  
Add header title and/or footer: `<panel header="Your title" footer="{{footerText}}">Content</panel>`

Available panels:  
**panel default** - `<panel>...</panel>`  
**panel primary** - `<panel-primary>...</panel-primary>`  
**panel success** - `<panel-success>...</panel-success>`  
**panel info** - `<panel-info>...</panel-info>`  
**panel warning** - `<panel-warning>...</panel-warning>`   
**panel danger** - `<panel-danger>...</panel-danger>`  

## Progress bar
In the simplest form: `<progress valuenow="50"></progress>` 

**Available attributes (with example values)**  
**valuemin="10"** - set custom min value, set to 0 by default.  
**valuemax="3450"** - set custom max value, set to 100 by default.     
**label="true"** - show the current value as a number, which is not visible by default.  
**striped="true"** - show stripes.    
**active="true"** - animate stripes when **striped** is set to **true**  

**Available progress bars**   
**progress default** - `<progress></progress>`  
**progress success** - `<progress-success></progress-success>`  
**progress info** - `<progress-info></progress-info>`  
**progress warning** - `<progress-warning></progress-warning>`   
**progress danger** - `<progress-danger></progress-danger>`  

## Text elements 


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

