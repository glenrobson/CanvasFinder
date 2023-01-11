# CanvasFinder
Tool to find a canvas from a manifest

<script src="canvas_finder.js">
</script>

# Canvas Finder

This tool allows you to paste a IIIF Manifest URL into the box below and it will show you all of the Canvases which are present in that manifest. 

<script src="https://kit.fontawesome.com/0060d53ddc.js" crossorigin="anonymous"></script>
<div id="canvas_finder" style="border: 1px solid black; padding: 5px;">
<div id="manifest_enter" style="padding: 5px;">
<form>
<label for="exampleInputEmail1"><b>Manifest URL:</b></label>
<input type="text" id="manifest_uri" style="width:70%"/>
<button onclick=loadManifest(event)>Load</button>
<button onclick=clearManifest(event)>Clear</button>
</form>
</div>
<div id="manifest_content">
</div>
</div>
