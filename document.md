<div id="adobe-dc-view" style="width: 800px;"></div>
<script src="https://documentcloud.adobe.com/view-sdk/main.js"></script>
<script type="text/javascript">
	document.addEventListener("adobe_dc_view_sdk.ready", function(){ 
		var adobeDCView = new AdobeDC.View({clientId: "<YOUR_CLIENT_ID>", divId: "adobe-dc-view"});
		adobeDCView.previewFile({
			content:{location: {url: "https://acrobat.adobe.com/link/review?uri=urn:aaid:scds:US:278679a4-985c-4c5d-8151-81e817e1490a)"}},
			metaData:{fileName: "Reference Data"}
		}, {embedMode: "IN_LINE"});
	});
</script>
