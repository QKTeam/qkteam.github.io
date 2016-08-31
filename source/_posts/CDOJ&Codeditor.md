---
title: CDOJ & Codeditor 盛大发布，献礼UESTC 60周年
date: 2016-08-31 22:54:07
tags: [iOS, CDOJ, UESTCACM]
---

<style>
img {
	max-width: 100%;
}
.badge {
	position: absolute;
	display: none;
}
</style>

<div style="position: relative;">
	<img id="pic" src="/resources/CDOJ&Codeditor_noBadge.png">
	<a class="badge" id="cdoj" href="https://itunes.apple.com/app/cdoj/id1147018708" target="_blank">
		<img src="/resources/AppStoreBadge.png">
	</a>
	<a class="badge" id="codeditor" href="https://itunes.apple.com/app/codeditor/id1147022827" target="_blank">
		<img src="/resources/AppStoreBadge.png">
	</a>
</div>
<script>
function A() {
	var width = $('#pic').width() * 0.1593;
	var top = $('#pic').height() * 0.55;
	var left = ($('#pic').width() * 0.5 - width) * 0.5;
	$('#cdoj').css('top', top + 'px');
	$('#cdoj').css('left', left + 'px');
	$('#cdoj').css('width', width + 'px');

	left = $('#pic').width() - left - width;
	$('#codeditor').css('top', top + 'px');
	$('#codeditor').css('left', left + 'px');
	$('#codeditor').css('width', width + 'px');

	$('.badge').css('display', 'block');
}
window.onresize = function () { A(); }
window.onload = function () { A(); }
$('#pic').load(function() { A(); });
</script>

<!--more-->
Android版正在开发中，敬请期待……

