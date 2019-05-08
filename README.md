# WAB_Add-More-Data-Grouped-Folder
Staff DART files to add new behavior to grouped add data widgets: 
1. Close all widgets on startup and close all widgets onOpen of Group (Panel.js).

Version 2.12

### INSTRUCTIONS:
* Copy Panel.js to folder \themes\FoldableTheme\panels\FoldablePanel\

```bash
BUG NOTES:
Open/close icon not working since v2.10.  Icon exists in \themes\FoldableTheme\panels\FoldablePanel\images\ folder but is not rendered correctly by ESRI code

Version comparison for html:

2.12
<div class="title-label" data-dojo-attach-point="titleLabelNode" title="Add ESRI Data" style="line-height: 30px;">Add ESRI Data</div>
<div class="btns-container" data-dojo-attach-point="btnsContainer">
	<div class="foldable-btn" role="button" aria-label="Fold window" tabindex="0"></div>
</div>

2.10
<div class="title-label" data-dojo-attach-point="titleLabelNode" title="Add CSV File" style="line-height: 30px;">Add CSV File</div>
<div class="foldable-btn jimu-float-trailing folded"></div>

```


