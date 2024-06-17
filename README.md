<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>배나영 – 백엔드 이력서</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
    margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: rgba(35, 131, 226, .07); }
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-transparentGray { background-color: rgba(227, 226, 224, 0); }
.select-value-color-translucentGray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="e8a2ed84-ddd5-4421-9f8c-ed749beab711" class="page sans"><header><div class="page-header-icon undefined"><img class="icon" src="https://www.notion.so/icons/code_green.svg"/></div><h1 class="page-title">배나영 <em>–</em> 백엔드 이력서</h1><p class="page-description"></p></header><div class="page-body"><h1 id="d14b349d-0e4d-429e-892c-2141063ff77a" class=""><mark class="highlight-teal">Introduce_</mark></h1><p id="4458c0e2-385b-42db-b67b-44882665eadb" class="">자바 Backend 개발자, 배나영 입니다.</p><p id="0c67a915-8ef1-4c9f-911f-dcd9390e9961" class="">신중한 개발을 지향합니다. 테스트 코드로 기능을 검증해가며 개발하는 것을 좋아합니다.</p><p id="17ca6918-a30d-47c0-9744-8b4e36c68719" class="">맞닥뜨린 이슈나 의문점을 개인 블로그 ‘이슈와 해결’에 정리하고 있습니다.</p><p id="92246abf-4d22-40b6-8048-ba319148b7cc" class="">
</p><h2 id="3deb065d-ea85-4937-931f-efeb80664b82" class=""><mark class="highlight-teal">Contact_</mark></h2><ul id="10640ce2-a58e-4440-a945-7ed167363273" class="bulleted-list"><li style="list-style-type:disc">Phone: 010-5532-7662</li></ul><ul id="e26b44b3-dfd5-4b49-8db1-87af81769396" class="bulleted-list"><li style="list-style-type:disc">Email: qoskdud0928@gmail.com</li></ul><ul id="b4f3b95a-81c3-4819-bfcd-a8b0620402e6" class="bulleted-list"><li style="list-style-type:disc">Blog: <a href="https://velog.io/@qoskdud0928/posts">https://velog.io/@qoskdud0928/posts</a></li></ul><p id="b30fdd94-2f2f-4ee7-bf94-dc0ee3ca4164" class="">
</p><hr id="4b2d07a7-a8c4-4301-b8ce-335f328753ee"/><h1 id="b089b194-0f16-44ae-a8f3-fa9a2d3568ed" class=""><mark class="highlight-teal">Work Experience_</mark></h1><div id="fba8b1fb-b452-4b90-a183-6332779134f7" class="column-list"><div id="4f803901-ea32-4988-9a7b-e790140abb9d" style="width:18.75%" class="column"><h3 id="45f57419-8aec-4577-911f-1b25c3d5908a" class=""><a href="http://inzisoft.com/">인지소프트</a></h3><p id="5f01f471-4989-4ffa-85b8-8dac54151ed9" class="block-color-gray"><em>Server Engineer– (2022.12 - 현재)</em></p></div><div id="fa734035-ae85-4807-94e8-4374137e35aa" style="width:81.25%" class="column"><p id="676d12e7-e6e6-4bad-9401-52f6f6886e23" class="">이미지 및 영상 처리, 이미지 보안 솔루션 기업</p><p id="60fdcd3e-c788-4e0d-9275-e5a1931fd06f" class="">연구 1팀(ML 및 컴퓨터 비전을 이용한 이미지 인식 솔루션) 서버 개발자</p><p id="dfc316bb-f7af-4e8c-aff5-077ad9ea6180" class="">
</p><ul id="b750490e-9545-4d13-9908-39c33851bc97" class="bulleted-list"><li style="list-style-type:disc"><strong>서버 ocr 유지보수, 트러블슈팅 (2023.12 ~ 2024.06)</strong><p id="81751c27-10a5-4ce1-b970-537cbafb5c2c" class="">Java/Spring, Tomcat, Linux Shell Script, SVN</p><ol type="1" id="d98c8f25-9c9c-46d4-a14c-ec1a131995a7" class="numbered-list" start="1"><li>업무: 5개의 금융 고객사 서버에 설치된 이미지 솔루션 이슈 대응</li></ol><ol type="1" id="2012b446-ab97-440f-8b8c-d374da786ecd" class="numbered-list" start="2"><li>단순 업무 자동화/효율화: Shell script로 <a href="https://velog.io/@qoskdud0928/%EB%B6%80%ED%95%98-%ED%85%8C%EC%8A%A4%ED%8A%B8">테스트 절차 간소화</a>, <a href="https://velog.io/@qoskdud0928/%ED%86%B0%EC%BA%A3-%EB%A9%80%ED%8B%B0-%EC%9D%B8%EC%8A%A4%ED%84%B4%EC%8A%A4-%ED%99%98%EA%B2%BD-%EA%B5%AC%EC%B6%95">톰캣 멀티 인스턴스</a>를 통해 5개의 금융 고객사 소스 관리, jUnit4를 사용한 단위 테스트 추가</li></ol><p id="4d739f67-8eda-4e00-b242-ae9bc5afd091" class="">
</p></li></ul><ul id="59988608-3e97-42f2-a618-c6ff2a4c09e6" class="bulleted-list"><li style="list-style-type:disc"><strong>AI-OSP 관리자 페이지 개발 (2023.05 ~ 2023.08)</strong><p id="fc5894fb-d016-4d91-a6b0-0d780dfa2d3b" class="">Java/Spring Security, Spring Data JPA, MySQL, SVN</p><ol type="1" id="4eaa71a8-7b9d-4852-a262-1dbf181215f7" class="numbered-list" start="1"><li>Session 기반 인증/인가 구현</li></ol><ol type="1" id="46ddbff0-9c4a-4b76-986c-a4e7110ee2bc" class="numbered-list" start="2"><li>관리자/승인자/사용자의 3가지 사용자의 권한에 따른 페이지/api요청 접근 권한 분리</li></ol><ol type="1" id="3341dee9-8ecf-4f85-9865-211ceb884906" class="numbered-list" start="3"><li>다양한 제약조건 구현: 예외 핸들러를 통해 로그인에 성공해도 비밀번호 오류 횟수/6개월 이상 접속 기록 없는 경우/허용되지 않은 IP 접속인 경우 인증 실패하도록 구현</li></ol><p id="2fbf3dc7-8d49-479f-be33-4854646331fb" class="">
</p></li></ul></div></div><hr id="6bf0b125-84b4-4fee-a0fc-88388601c8b4"/><h1 id="d5f904e5-dc4a-4b67-ad99-d58710a54b6c" class=""><mark class="highlight-teal">Tech Experience_</mark></h1><div id="a8a1b555-a758-4905-9def-b57cbfbee97f" class="column-list"><div id="221b0138-a906-46dc-9d68-6828822ce67e" style="width:18.75%" class="column"><h3 id="9eeb2e2f-f1bd-4c40-bc82-ce4873cbcf09" class="">Spring</h3><p id="cc5f42e2-e132-4903-a767-038627d6b93a" class="block-color-gray">
</p></div><div id="34d67e59-31f2-4682-9eb1-1ecb3eae6e8e" style="width:81.25%" class="column"><ul id="54e027e7-f238-4374-a551-b1782327ecb6" class="bulleted-list"><li style="list-style-type:disc">사용해본 Spring Project: Spring, Spring Boot, Spring Framework, Spring Data JPA, Spring Security</li></ul><ul id="baccac28-758b-4f30-b13f-90c08ff5eb8e" class="bulleted-list"><li style="list-style-type:disc">MVC 기반 Rest Api 구현 경험: 실무 <em>– 2회</em>, 사이드 프로젝트 <em>– 4회</em></li></ul><ul id="b9225071-db6b-49e2-8a1d-97aa4ecabac8" class="bulleted-list"><li style="list-style-type:disc">Spring 기반 실무 프로젝트 트러블슈팅 경험</li></ul><p id="dc80df70-bfe8-4422-9930-4a8d0db0fbb7" class="">
</p></div></div><div id="22b8139c-b67b-4c17-b3e6-5a3fa8836358" class="column-list"><div id="db5662ab-2ca8-4593-957e-4c0a2982e3bb" style="width:18.75%" class="column"><h3 id="79126fcb-76e2-42a3-9a95-1af56e2ecf89" class="">Spring Security</h3><p id="ee14a609-6e05-41b4-ab0d-5697fdacb456" class="block-color-gray">
</p></div><div id="4505f63a-0de0-465f-a83c-4d4fee72794d" style="width:81.25%" class="column"><ul id="b32bc32e-ea7b-4bc7-9211-9b5af095fde8" class="bulleted-list"><li style="list-style-type:disc">Spring Security Framework의 구조를 이해하고 인증 단계에 적합한 인터페이스를 구현할 수 있음</li></ul><ul id="c50b28a0-7cc1-4f33-a391-a3f2c66534aa" class="bulleted-list"><li style="list-style-type:disc">권한에 따른 접근 제어 구현 가능</li></ul><ul id="014f424f-d350-4dad-add5-9951dfa7a6a4" class="bulleted-list"><li style="list-style-type:disc">토큰을 생성하여 인증 기능 구현 경험 <em>– 1회</em></li></ul><ul id="fddbf0dd-2017-4fe6-b898-567d450fb8c7" class="bulleted-list"><li style="list-style-type:disc">Session을 이용한 인증/인가 기능 구현 경험 <em>– 1회</em></li></ul><p id="19c190df-718c-41e1-94c2-a6c09430f67e" class="">
</p></div></div><div id="2c08b77c-2af8-4a6c-bb63-2d4dd0061fa2" class="column-list"><div id="d62044a8-2951-495a-8569-c7faf0aa5cc2" style="width:18.75%" class="column"><h3 id="ef08c13f-c15d-47e1-b55d-f2ec972eb4ee" class="">Others</h3><p id="8345e923-1a85-4dd7-b276-080a3889996f" class="block-color-gray">
</p></div><div id="7cb9a5c6-913a-40f7-80b1-b5d8ebfcdef0" style="width:81.25%" class="column"><ul id="246e0b63-cd77-4350-9c61-8aa2e8e5d6e9" class="bulleted-list"><li style="list-style-type:disc">Spring Data JPA: Crud 기능 구현 경험 <em>– 3회 </em></li></ul><ul id="6f3119c9-d6f2-44f0-8ede-2bd96a8b2672" class="bulleted-list"><li style="list-style-type:disc">CI/CD: Jenkins, Dockerfile, Gitlab, AWS <em>– 1회</em></li></ul><ul id="235221c9-ca4e-43d7-8f50-eb2ee3ac77fb" class="bulleted-list"><li style="list-style-type:disc">Linux: 명령어를 이용하여 실무 프로젝트에 필요한 WAS 세팅 경험 <em>– 5회이상</em> </li></ul><p id="3ba5b3a2-7a81-4f61-a524-5c03cd768a71" class="">
</p></div></div><hr id="8a4fe3d8-d123-4779-9567-cffa09c65c57"/><h1 id="7ce06caf-e08c-4cf0-86e7-883d951d8602" class="block-color-teal">Education_</h1><div id="c74f4228-c845-4a2e-800c-922ef12c6a10" class="column-list"><div id="4b188e42-183a-4108-80ff-c5a834bd99e9" style="width:18.75%" class="column"><h3 id="d7414cc3-a685-4175-963b-fe95e5523833" class=""><a href="https://www.ssafy.com/ksp/jsp/swp/swpMain.jsp">SSAFY</a></h3><p id="56ee7a40-6c11-42ae-9f8a-ea5349de49bc" class="block-color-gray"><em>웹개발 교육– (2022.12 - 현재)</em></p></div><div id="37fc6de3-5910-4749-8bbb-987802f96437" style="width:81.25%" class="column"><p id="c652a390-550f-4bb2-9ff1-275094621615" class="">삼성 청년 소프트웨어 아카데미</p><ul id="fe07ce6f-0f71-4807-b456-cddce52b24df" class="bulleted-list"><li style="list-style-type:disc">Spring 교육: Servlet/JSP, Spring MVC, Spring Boot</li></ul><ul id="fa13f4c2-cb3f-4cd9-a09c-8e3a7d17d89e" class="bulleted-list"><li style="list-style-type:disc">4차례의 웹 프로젝트 기획/설계/개발/배포 경험</li></ul><p id="64c63775-d43d-45d9-8fca-daf34288cd28" class="">
</p></div></div><div id="4b5b3006-2039-4599-a92c-e14bb50d5e8d" class="column-list"><div id="7d6a7305-4883-47a6-bdea-dc6ced387ec8" style="width:18.75%" class="column"><h3 id="a2d7caae-88ed-4187-8b2a-64764e42332f" class=""><a href="https://www.cbnu.ac.kr/www/index.do">충북대학교</a></h3><p id="d54dfa61-5e1f-449f-8f09-75ca13897c22" class="block-color-gray"><em>(2021.08 졸업)</em></p></div><div id="e369d450-370a-42df-891d-1dc859fc731a" style="width:81.25%" class="column"><p id="1599e0aa-477b-4c0b-8898-dc1dec9c1ee9" class="">소프트웨어학과 전공</p><p id="494b9c69-16c5-4bfe-ac3e-7539605eae0a" class="">
</p><p id="2da7e28a-dac3-4fac-923d-91699529b2f6" class="">
</p><p id="e48b0d54-2404-4869-a653-d887a7d8f763" class="">
</p></div></div><hr id="3d860abd-d1d7-4ffd-b272-7228b25b0dc2"/><h1 id="9af6e735-1249-4f22-ac06-d835cb7edb15" class=""><mark class="highlight-teal">Side Project_</mark></h1><div id="998bb14e-7dfd-45a6-a564-fabb1eabb837" class="column-list"><div id="5b286e56-846d-48a6-bb20-c57cd44280de" style="width:18.75%" class="column"><h3 id="2e242e1b-8fd2-44b6-9576-a09ec56e3aa8" class=""><a href="https://github.com/yeong-coding/bring-XXX/tree/main">Bring-XXX</a></h3><p id="ee92db32-7026-45f6-a860-90388ba6e2d1" class="block-color-gray">
</p></div><div id="af8d43d0-56e5-42fe-b91d-d8560b863c1e" style="width:81.25%" class="column"><ul id="0c78b9f3-ad87-48ef-8e11-99cd49b3768d" class="bulleted-list"><li style="list-style-type:disc">사용한 기술을 적용/정리해보기 위하여 시작한 개인 프로젝트</li></ul><ul id="98db4c67-1bea-4d23-881e-6ff4b5e7b008" class="bulleted-list"><li style="list-style-type:disc">바쁜 아침 시간에 그 날 기후 상태에 따라 챙겨야 하는 소지품을 빠르게 확인하기 위하여 <a href="https://github.com/yeong-coding/bring-XXX/tree/design">기획</a></li></ul><ul id="e7d5cb31-02f0-4c09-9077-c6f0713206cd" class="bulleted-list"><li style="list-style-type:disc">현재 <a href="https://github.com/yeong-coding/bring-XXX/tree/security">Spring Security JWT 기반 인증 구현 진행중</a></li></ul><p id="e90438b8-7cc0-43dd-a05c-ae377b38be1d" class="">
</p></div></div><div id="9ab4fb82-eb6b-4a53-8445-3d82e6c7a99c" class="column-list"><div id="5e7791d1-4fe2-4284-9974-2915fd03e7a1" style="width:18.75%" class="column"><h3 id="f55b48bb-34ce-44fd-9bf2-b37dd807d318" class="">Woonana</h3><p id="2ac16d69-60b9-44db-98c9-80ac11a303a3" class="block-color-gray"><em>CI/CD – (2022.04 - 2022.05)</em></p></div><div id="a0c6b792-28c7-4b0e-a367-fd87c3485941" style="width:81.25%" class="column"><ul id="b8f6a9ac-7b32-44a7-92bd-a931d2b6577b" class="bulleted-list"><li style="list-style-type:disc">소규모 운동 모임을 위한 약속 사이트 <ul id="09656b51-2bc9-4dd4-9b83-cb0831cedd1e" class="bulleted-list"><li style="list-style-type:circle">팀 구성 <em>– 6</em></li></ul></li></ul><ul id="a1675c3e-65b1-4279-bf13-19be386233b4" class="bulleted-list"><li style="list-style-type:disc">jenkins, docker, gitlab을 이용하여 git master 브랜치에 push가 발생했을 때 자동으로 서버에 배포되는 시스템을 구축하여 프론트 및 백엔드 담당자가 원하는 때 바로 배포 결과를 확인할 수 있도록 함</li></ul><ul id="564f45e0-ffc0-4a07-b300-5f23b7215cca" class="bulleted-list"><li style="list-style-type:disc">nginx 리버스 프록시 기능을 사용해 채팅 백엔드를 분리하여 채팅 기능이 늦어져도 배포에 지장이 없는 환경을 구축</li></ul><ul id="7fbc90f1-8126-4f92-8261-8300f397d0ad" class="bulleted-list"><li style="list-style-type:disc">백엔드 지원: 평가하기, 운동선호도/운동기록 조회 api 개발</li></ul><p id="c86a779f-5b46-4092-9e60-11e287e3fa92" class="">
</p></div></div><div id="695a0b95-d6f1-4010-b1c0-ebc64e3f276d" class="column-list"><div id="382718de-89bf-4adf-9a97-a8f0e599ec30" style="width:18.75%" class="column"><h3 id="f457e521-6fb4-4ac0-bdd1-ab9c75cc53b6" class="">ROOMMATE</h3><p id="57677256-a2b2-451d-b417-7e0370d1dc4b" class="block-color-gray"><em>Backend – (2021.12 - 2021.12)</em></p></div><div id="b98a757d-22d7-4c86-93f4-dbb3d18b391f" style="width:81.25%" class="column"><ul id="f2cf861d-13c3-4983-8ea2-9ceb712f5ef2" class="bulleted-list"><li style="list-style-type:disc">생활 패턴에 맞는 룸메이트 구하는 것을 돕는 웹사이트 개발<ul id="3806c7ab-1625-48fb-9a22-4b460e2d2436" class="bulleted-list"><li style="list-style-type:circle">팀 구성 <em>– 2</em></li></ul></li></ul><ul id="c273e646-6468-48a6-8ff1-041d15ac1de2" class="bulleted-list"><li style="list-style-type:disc">Spring Boot와 MyBatis를 사용하여 게시글/댓글 CRUD 기능, 룸메이트 검색 기능</li></ul><ul id="fc45dc20-cff6-4dc8-838d-359769ba677d" class="bulleted-list"><li style="list-style-type:disc">카카오 맵 API를 이용한 지도, 위치 검색, 마커 기능 개발</li></ul><p id="ea127635-9513-4d83-bcef-f07c234e1b19" class="">
</p></div></div><hr id="a6670e28-a5f0-4de8-8b77-8c95b2ccf306"/><p id="b6eaea20-cb10-49d7-ba32-4ffb3d07cf33" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>