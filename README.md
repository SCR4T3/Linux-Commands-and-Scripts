# Linux-Commands-and-Scripts
With this repository you can learn to use the terminal and even make scripts in Linux in a comfortable and organized way
<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>FS</title><style>
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

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
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
	
</style></head><body><article id="6cf3045d-091d-404c-91d4-9396288a426c" class="page sans"><header><h1 class="page-title">FS</h1><p class="page-description"></p></header><div class="page-body"><p id="704ba569-092d-45bb-a6b0-b096cbc347ab" class="">
</p><h2 id="6e743a2f-70c9-4bbc-b267-b31dc7c0014b" class="">Órdenes Básicas</h2><ul id="723780f7-1575-4177-92b6-504a5dbe022e" class="bulleted-list"><li style="list-style-type:disc">Man → Instrucciones sobre cualquier comando. </li></ul><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="18537f6d-37a4-4a04-b96b-2af184502d6e" class="code"><code class="language-Bash">man ls</code></pre><ul id="9fd54054-2b37-4d79-b7a5-e361f9fb2a85" class="bulleted-list"><li style="list-style-type:disc">Ls → Lista el contenido de un directorio.</li></ul><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="6b0d4160-763c-4ce1-8258-5422179f761b" class="code"><code class="language-Bash">ls -l //formato amplio
ls -a //ocultos
ls -c //multicolumna
ls -r //inverso
ls -t //fecha</code></pre><ul id="e2638a96-3d2b-4db8-b611-d1d8cdeb64e1" class="bulleted-list"><li style="list-style-type:disc">Cd → Cambiar de directorio.</li></ul><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="d2050756-f436-407d-b94a-8a24fc43675a" class="code"><code class="language-Bash">cd directorio
cd .. //Volver atrás
cd ../Directorio //Moverte a un directorio del directorio padre
cd ~ //Moverte al home.</code></pre><ul id="ec5f4dcb-4a54-4854-945e-317c8b7558aa" class="bulleted-list"><li style="list-style-type:disc">Pwd → Camino absoluto del directorio actual.</li></ul><ul id="12dd034b-2212-4378-9d0c-bad9a9cf687d" class="bulleted-list"><li style="list-style-type:disc">Mkdir directorio → Crear una carpeta.</li></ul><ul id="eca222c5-27a8-4ea7-ade9-d5f2bedacb59" class="bulleted-list"><li style="list-style-type:disc">Rmdir directorio → Borrar directorio si esta vacio.</li></ul><ul id="b4206b43-4eee-4ed0-8631-b959b86fbed5" class="bulleted-list"><li style="list-style-type:disc">Cat → Muestra el contenido de un archivo o varios, concatena<br/>archivos, copia un archivo, crea un archivo de texto o muestra los caracteres invisibles de control.<br/></li></ul><ul id="11124d48-9428-4456-92e5-40328736acfd" class="bulleted-list"><li style="list-style-type:disc">Cp archivo1 archivo2 → Copia un archivo en el otro y si no existe lo crea.</li></ul><ul id="8dad4d96-255f-4279-aa43-6ef40e5ef3f6" class="bulleted-list"><li style="list-style-type:disc">Mv fuente destino → Para mover archivos o directorios y renombrar.</li></ul><ul id="bdcdd82d-156f-4e4d-8e5d-ae8096bd900a" class="bulleted-list"><li style="list-style-type:disc">File → Tipo de archivo.</li></ul><ul id="00e6e070-1f4a-4425-826e-4b7a9d0267e2" class="bulleted-list"><li style="list-style-type:disc">More → Muestra archivo fraccionado.</li></ul><ul id="f6863b7e-1bdc-407e-b813-4f302ce93e1f" class="bulleted-list"><li style="list-style-type:disc">Rm → Borra archivos y directorios.</li></ul><ul id="925ba758-4210-4968-bd1b-8e59d35d2498" class="bulleted-list"><li style="list-style-type:disc">Touch → Modifica fecha y hora y crea archivos.</li></ul><ul id="7eaedbc8-d199-4ddd-af91-a91078faddb2" class="bulleted-list"><li style="list-style-type:disc">Clear → Limpia terminal.</li></ul><ul id="005b641a-9ec4-4dc6-85db-771204c71a5c" class="bulleted-list"><li style="list-style-type:disc">Head/Tail -lineas archivo → Muestran las n lineas iniciales/finales de un archivo.</li></ul><ul id="5a2be562-1721-4930-af33-ef62e4845f3f" class="bulleted-list"><li style="list-style-type:disc">Sort → Ordena según criterio.</li></ul><ul id="2be46316-88ab-4b89-8e75-6206fcdfd0dc" class="bulleted-list"><li style="list-style-type:disc">Setterm -r → Reestablecer el estado normal de la terminal.</li></ul><h2 id="50a38f4b-de62-44a1-b2ba-98ac670c83b1" class="">Metacaracteres</h2><ul id="c90503a5-f194-447f-a320-dd753da87f40" class="bulleted-list"><li style="list-style-type:disc">* → todo.</li></ul><ul id="db9060d6-9eb1-4e90-9c2f-623b078b97d1" class="bulleted-list"><li style="list-style-type:disc">? → caracter.</li></ul><ul id="215e6338-9633-4a83-a93d-10e222e0791c" class="bulleted-list"><li style="list-style-type:disc">{ → Sustituyen conjuntos de palabras separadas por comas que comparten partes comunes.</li></ul><ul id="35ab6854-126c-42a6-abae-78dc9fd51896" class="bulleted-list"><li style="list-style-type:disc">[ → Designan un carácter o rango de caracteres que representan un carácter simple a través de una lista de caracteres o mediante un rango, en cuyo caso, mostramos el primer y último carácter del rango separados por un guión “-”.</li></ul><h3 id="d8883768-e12b-436f-be3c-01dbb5be4410" class="">De recirección:</h3><figure id="62052a09-b995-4422-8959-0221d9cca5a1" class="image"><a href="Untitled.png"><img style="width:787px" src="Untitled.png"/></a></figure><h3 id="e98752d2-2ea3-4a19-9de1-e3e6bbf22c0b" class="">Sintácticos:</h3><figure id="11ae4d3c-49db-43db-a79e-9b3d3bebeb8e" class="image"><a href="Untitled%201.png"><img style="width:788px" src="Untitled%201.png"/></a></figure><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="a9e3989e-116b-4542-91e9-0a5fee2e3679" class="code"><code class="language-Bash">$ date
Wed oct 6 10:12:04 WET 2010
$ pwd
/home/users/quasimodo
$ pwd ; date | wc
/home/users/quasimodo
1 6 27
$ (pwd ; date) | wc
2 7 48
$ pwd
/home/users/quasimodo
$ ls
listado notas
$ ls -l notas &amp;&amp; pwd
-rw-r-—r-- 1 quasimodo alumnos 3418 Mar 15 2010 notas
/home/users/quasimodo
$ ls -l notas || pwd
-rw-r-—r-- 1 quasimodo alumnos 3418 Mar 15 2010 notas
$ rm notas
$ ls -l notas &amp;&amp; pwd
ls: notas: No existe el archivo o el directorio
$ ls -l notas || pwd
ls: notas: No existe el archivo o el directorio
/home/users/quasimodo</code></pre><ul id="1e305b14-2027-4dfc-9147-91e48dec930b" class="bulleted-list"><li style="list-style-type:disc">r → Lectura.</li></ul><h2 id="6136ea62-5a53-4aa1-bb7b-ef7e01f89569" class="">Permisos</h2><ul id="70af8170-b2bf-4deb-9b8f-d1eec89fd952" class="bulleted-list"><li style="list-style-type:disc">w → Escritura.</li></ul><ul id="249e787c-c86b-4970-95c1-31f90390efed" class="bulleted-list"><li style="list-style-type:disc">x → Ejecución.</li></ul><ul id="5703299e-5977-4fe6-b52d-98c5ec9c3541" class="bulleted-list"><li style="list-style-type:disc">- → No hay permiso.</li></ul><p id="bd62811a-08bb-4081-92fa-2cd1c87b412f" class="">
</p><p id="795b28c5-11ee-4410-9668-060d0e3322ff" class=""><strong>Chmod</strong></p><p id="b9306956-779f-4bf1-9609-3649abbc6332" class="">Si hacemos ls -l vemos el listado de archivos y sus privilegios.</p><p id="79c6e9af-799e-4105-97e3-20d89e01848a" class="">Se nos motrará algo así: rwx r - - r - -</p><p id="cf2876b1-8ed0-49e4-abe5-c0567d64ca50" class="">Podemos definir entre:<div class="indented"><p id="055da724-e1aa-4d38-b844-31d0950e02a2" class="">u → usuario</p><p id="74fc0d9e-b20c-40d1-a0ae-572639d63c4a" class="">g → grupo</p><p id="e658dd5e-a711-4a35-8a40-0d662a20e430" class="">o → otros</p><p id="1dbbb604-9eab-4dc1-879d-25257bf892f2" class="">a → todos</p></div></p><p id="3b8a02d0-b9b6-4eb9-add3-b053f3f74e33" class="">Así podemos definir los permisos:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="14b561d9-8970-4e6f-9ebf-c115c6ff189e" class="code"><code class="language-Bash">chmod (u/g/o/a)(+/-)(w/r/x) nombre_archivo.</code></pre><p id="4777193a-6749-4956-aa0f-8c3f4768e4df" class="">Con números:</p><p id="9fd5aa4f-d09f-4b55-a92b-6ebfe6666c51" class="">Va en binario</p><p id="be514219-d332-4380-a42c-2c69a75b1861" class="">rwx r - - r - -</p><p id="1c76ed54-6a59-4749-adad-064e28300b54" class="">111 100 100</p><p id="9bcd74e6-7b77-4d28-86f3-2987f72b4177" class="">7       4     4</p><p id="44d0e087-4fae-44e8-a539-623a519f26e7" class="">Esto sigue esta regla por ello podemos ejecutar chmod con números: chmod 744 nombre_archivo</p><p id="46852468-a590-4c91-9a1d-0399e5601821" class="">
</p><h2 id="7f23f334-4997-4ce1-a5bc-3577be4a71dc" class="">Echo</h2><p id="1fba53a5-97af-4ac5-a136-ac33342b3fd4" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="aa0876ec-3e9b-4354-baa7-8819d655b453" class="code"><code class="language-Bash">echo “hola”    //Imprime por terminal hola</code></pre><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="97e0cd79-dadc-4009-bb49-ebb37a1adbc9" class="code"><code class="language-Bash">(echo “hola”; ls -l) &gt; nombre_fichero     //Mete dentro de el archivo hola y el ls</code></pre><p id="d8004c93-8ebd-4005-94f4-efb68a3ade84" class="">&gt; escribe dentro de un fichero sustituyendo lo que había.</p><p id="e5823750-0a5c-467b-92e5-149e80fd27c3" class="">&gt;&gt; escribe dentro de un archivo sin sustituir lo que había.</p><p id="38590eb5-967e-4932-a876-5e25325be1f7" class="">&gt;&amp; escribe tambien dentro de el archivo el error por termimal y la orden.</p><p id="de3dd1e4-d1b6-4b02-9b97-f8580c06df95" class="">&gt;2 imprime la orden por terminal y mete en el archivo el error</p><p id="4132a2b2-256c-40c3-a39e-b3592808b894" class="">A &amp;&amp; B → Solo si A se cumple B también.</p><p id="ab633ac1-ebca-4687-b63f-0eef4fc7be6f" class="">A | | B → Si A da error, hace B.</p><p id="c53f75ff-c60c-41f9-952c-e7ad5f1ede7a" class="">
</p><h2 id="f6b36420-6989-4b53-9992-aafd659cd8b3" class="">Wc</h2><p id="f44d6504-953a-49dc-aa34-ab1b7d45acee" class="">
</p><p id="324cd5e2-5a74-41f0-9c72-173c72cc304c" class="">Wc sirve para contar lineas (l), caracteres (c), palabras (w) … .</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="bf013213-20ad-425a-91fd-f03bafc61ade" class="code"><code class="language-Bash">wc -c/-l/-w
$ ls
listado
notas
$ ls notas &amp;&amp; wc notas || echo “no existe el archivo notas”
notas
86 324 5673 notas
$ rm notas
$ ls notas &amp;&amp; wc notas || echo “no existe el archivo notas”
ls: notas: No existe el archivo o el directorio
no existe el archivo notas</code></pre><p id="351a6663-163b-4993-b09c-b1546eef56c4" class="">
</p><h2 id="35819c16-29ec-4ca9-915d-cde5330ef049" class="">Variables</h2><p id="713c26c1-c8c4-4c02-bad9-d3747ac8dc7d" class="">Podemos diferenciar las de entorno (comunes a todos los shells) se pueden mostrar con env o printenv y las locales, visible solo en la shell donde se definen y se pueden mostrar con set. help variables → variables bash. </p><p id="74bf6929-5b51-4c4a-9b99-4b18f9818e54" class="">Podemos crear variables con atributos con declare, numérica (-i), (-p) para ver los atributos.</p><p id="18f7d520-fdb3-4da4-9191-3ed1ea0c34cd" class="">Podemos declarar las variables así:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="f6fa79a3-0fac-4a0d-a719-13ea46ac71d7" class="code"><code class="language-Bash">numero=1
echo &quot;$numero&quot; //Imprime 1
colores=(rojo azul verde)
echo ${colores[0]} //Imprime rojo
$ declare -i IVA=18
$ declare -p IVA
declare -i IVA=”18”
$ declare -i IVA=hola
$ declare -p IVA
declare -i IVA=&quot;0&quot;
//Cuidado: Sin espacios.</code></pre><h3 id="e401950f-335c-4ce0-be16-54e702b2a80e" class="">Variables Especiales</h3><p id="0aad0518-2fe7-436f-8157-100ba7a14329" class="">
</p><figure id="1349183d-fc0a-4fa9-bdda-0811e89654a7" class="image"><a href="Untitled%202.png"><img style="width:789px" src="Untitled%202.png"/></a></figure><p id="0f2c4066-eb56-4380-bce8-76a1a9c7f729" class="">Si reiniciamos la bash podemos perder las variables por eso podemos exportarlas con export variable o export variable=valor.</p><p id="72c2748b-a684-4b67-87bd-c983c0255e44" class=""><span style="border-bottom:0.05em solid">Comillas</span></p><p id="4afb676b-1c18-45d9-834e-360888ad5442" class="">‘ comillas simples para echo.</p><p id="83f82756-1aea-43ad-956e-5fcb223d8a6b" class="">“comillas dobles para echo.</p><p id="8a73568f-cd05-46b0-8f4d-d85159e35b57" class="">`comillas invertidas para ordenes o $(ls -l)</p><p id="9044259d-8524-4778-b9e2-7ae79d9ac4ab" class="">
</p><p id="de9118b5-6204-4ede-aab1-b2fd65e69856" class="">También podemos asignar resultados de ordenes a variables:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="56730d40-04ed-4f79-91c3-1549f332560c" class="code"><code class="language-Bash">variable=`ls .`</code></pre><p id="03cdfc6b-de36-47dc-9473-d194a2abbd76" class="">Si queremos realizar operaciones con varibles podemos hacerlo con expr:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="efa51083-f5a3-4753-937a-bd497b9a8efd" class="code"><code class="language-Bash">numero=`expr $numero + 1`
echo $numero //Imprime numero + 1</code></pre><p id="e9b434e2-27af-4c13-8349-db4770c7a8d4" class="">
</p><h2 id="e3a93016-ee7e-4144-b989-8c3f4c7d4611" class="">Printf</h2><p id="e0816ee5-5d3e-4eb7-874d-dbca983c4053" class="">Se puede escribe:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="f79d5ba2-a30a-4c39-b014-26d09b2d4977" class="code"><code class="language-Bash">printf &quot;mi nombre es %s y mi edad es %d&quot;</code></pre><figure id="1517a86c-e2e3-4369-a3a4-f98fa58ed2d7" class="image"><a href="Untitled%203.png"><img style="width:787px" src="Untitled%203.png"/></a></figure><figure id="a7e57b7e-2ce7-4533-8b45-3d0f12eabc17" class="image"><a href="Untitled%204.png"><img style="width:787px" src="Untitled%204.png"/></a></figure><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="1b49e320-fc25-4ff4-9a2e-5ba293e916d4" class="code"><code class="language-Bash">$ printf “%10d\n” 25
25
$ printf “%-10d %-10d\n” 11 12
11 12
$ printf “%10.3f\n” 15,4
15,400
$ printf “%d %d\n” 010 0xF
8 15
$ printf “0%o 0x%x\n” 8 15
00 0xf
$ printf “El valor actual del IVA es del %d\n” $IVA
El valor actual del IVA es del 18</code></pre><h2 id="03d7870e-ffc6-45f5-87fc-9895514a17fc" class="">Alias</h2><p id="75a988d3-d2bd-48a1-8790-dbf6b0e93853" class="">Los alias se crean con la orden empotrada alias y se borran o eliminan con la orden unalias.</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="6b5a2293-bdcb-4cc9-8899-d7ade53df306" class="code"><code class="language-Bash">$ alias dir=&#x27;ls -l&#x27;
$ dir
$ \ls –l $HOME //Para ignorar un alias se pone la barra \</code></pre><h2 id="dbb37aec-72bc-4ea5-88bd-f50d7d8119f1" class="">Find</h2><p id="f78890d2-d510-4406-b474-76a50a1da9b7" class="">
</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="0e33f10e-e46b-4e1f-814c-64b4834eebcb" class="code"><code class="language-Bash">find &lt;directorio&gt; &lt;opcion&gt; &lt;patron&gt;
$ find / -name &quot;*.c&quot; //nombre del archivo
$ find . -type f //archivos regulares (f), directorios (d)
$ find / ! -user pat //se puede negar cualquier opcion, aqui pat 
para buscar en la raiz los archivos que no pertenezcan al usuario.
$ find . -size 10 -o -atime +2 //-o para concatenar ordenes
$ find . -print
$ find . -atime +100 -exec rm {} \;</code></pre><ul id="9b2d7fa1-d104-4842-ad3a-e9d98f0094eb" class="bulleted-list"><li style="list-style-type:disc">atime 7 busca los archivos a los que se accedió hace 7 días.</li></ul><ul id="348d7f6c-e674-4720-bae3-f74737fa11ff" class="bulleted-list"><li style="list-style-type:disc">atime -2 busca los archivos a los que se accedió hace menos de 2 días.</li></ul><ul id="0c38a2a8-a30e-4af6-ac7e-8354e58510a5" class="bulleted-list"><li style="list-style-type:disc">atime +5 busca los archivos a los que se accedió hace más de 5 días.</li></ul><ul id="72025cd0-85b2-4ea5-b4c5-0047d2dd32b9" class="bulleted-list"><li style="list-style-type:disc">Por su tamaño en bloques: se utiliza la opción -size seguida de un número con o sin signo (+ o -). Si el número va seguido de la letra c el tamaño dado es en bytes. Por ejemplo: -size 100 busca los archivos cuyo tamaño es de 100 bloques.</li></ul><ul id="5ea1ff4e-6967-4dca-9ef9-e712ffe73e43" class="bulleted-list"><li style="list-style-type:disc">-print: visualiza los nombres de camino de cada archivo que se adapta al criterio de búsqueda. Es la opción por defecto.</li></ul><ul id="fc9808dd-7c8d-4cf4-88a8-f6d121908caf" class="bulleted-list"><li style="list-style-type:disc">-exec: permite añadir una orden que se aplicará a los archivos localizados. La orden se situará a continuación de la opción y debe terminarse con un espacio, un carácter \ y a continuación un ;. Se utiliza {} para representar el nombre de archivos localizados.</li></ul><ul id="3e53c25e-351a-4a88-9755-7f577c376272" class="bulleted-list"><li style="list-style-type:disc">-ok: es similar a -exec, con la excepción de que solicita confirmación en cada archivo localizado antes de ejecutar la orden</li></ul><h3 id="1f409677-75b9-415a-8223-b92c35b936ea" class="">Grep</h3><p id="d6f66677-90f0-432b-ad39-696dc0ea1ff3" class="">Permite buscar cadenas en archivos utilizando patrones para especificar dicha cadena.</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="7e6e2c8f-7f93-4f14-8989-1ea6b176eafd" class="code"><code class="language-Bash">grep &lt;opciones&gt; &lt;patron&gt; &lt;archivo&gt;
$ grep mundo *</code></pre><ul id="97e21764-57c2-45de-8f71-7ae374dfadf5" class="bulleted-list"><li style="list-style-type:disc">-x localiza líneas que coincidan totalmente, desde el principio hasta el final de línea, con el patrón especificado.</li></ul><ul id="c5f4253b-a80c-4d70-9fa6-1a9bdbcb2626" class="bulleted-list"><li style="list-style-type:disc">-v selecciona todas las líneas que no contengan el patrón especificado.</li></ul><ul id="ae81be08-be3d-482c-b3df-1c3ef6e1beb8" class="bulleted-list"><li style="list-style-type:disc">-c produce solamente un recuento de las líneas coincidentes.<br/>-i ignora las distinciones entre mayúsculas y minúsculas.<br/>-n añade el número de línea en el archivo fuente a la salida de las coincidencias.<br/></li></ul><ul id="d1e049d2-1077-4f1a-a40b-60db5de9c0f7" class="bulleted-list"><li style="list-style-type:disc">-l selecciona sólo los nombres de aquellos archivos que coincidan con el patrón de búsqueda.</li></ul><ul id="2f24ffc1-c670-40f3-85c9-b71c11f366b2" class="bulleted-list"><li style="list-style-type:disc">-e especial para el uso de múltiples patrones e incluso si el patrón comienza por el carácter (-).</li></ul><p id="bcbbd61f-db33-4c7d-b97b-97b86a27bbd6" class="">La orden fgrep acepta sólo una cadena simple de búsqueda en vez de una expresión regular. La orden egrep permite un conjunto más complejo de operadores en expresiones regulares.</p><h2 id="9db25ccf-655c-4fc2-88ce-da92ad34aa4e" class="">Guiones</h2><p id="36beb317-ceed-4ac8-8ba0-d96bcafb1a91" class="">Para ejecutarlo usamos bash nombrearchivo o ./nombrearchivo</p><p id="40a06980-dd5a-4c2c-8554-51ee4766f916" class="">Creamos imprimevar:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="2250ebf8-b74f-4f50-9005-8d4605488ebb" class="code"><code class="language-Bash">variable=ordenador
printf &quot;Me acabo de comprar un $variable\n&quot;
printf &#x27;Me acabo de comprar un $variable\n&#x27;
printf &quot;Me acabo de comprar un \$variable\n&quot;
Devuelve
$ bash imprimevar
Me acabo de comprar un ordenador
Me acabo de comprar un $variable
Me acabo de comprar un $variable</code></pre><p id="55966d1c-887d-4908-bc85-06411bf723af" class="">Otro ejemplo:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="862d63ce-35bc-40bf-a1ee-152b5635e347" class="code"><code class="language-Bash">#!/bin/bash
printf “El directorio $HOME contiene los siguientes archivos:\n”
ls $HOME</code></pre><p id="5653ba99-a230-48d6-a053-ac8d17d554f2" class="">
</p><p id="1529e4e9-80c4-4f6f-9f95-9d0633b62dd2" class=""><span style="border-bottom:0.05em solid">Variables</span></p><figure id="5c8026db-8fed-4c88-8a28-f2e983f96565" class="image"><a href="Untitled%205.png"><img style="width:784px" src="Untitled%205.png"/></a></figure><p id="b6b422c3-d4c6-423f-af41-13791ef4e0cc" class="">Los argumentos por encima del 9 se suelen ponen entre llaves, por ejemplo, ${12}^2.</p><p id="ac79381d-9559-4747-9d26-ebe4355f9e41" class="">Por ejemplo: </p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="296fd0a2-59ad-4273-baba-8dadfbfa5505" class="code"><code class="language-Bash">#!/bin/bash
printf “El directorio $1 contiene los siguientes archivos:\n”
ls $1</code></pre><p id="d28be7b5-e209-4857-9f3a-0bf3a7c564bf" class="">En este caso justo al poner ./nombrearchivo tenemos que adjuntar el valor de las variable $n.</p><p id="439ec33d-315d-4e11-b652-5989664f1951" class="">Otro ejemplo sencillo de guion bash sería el de realización de una copia en otro directorio de todos los archivos y subdirectorios del directorio home de un usuario. Al igual que antes, se abre el editor con el que más cómodos nos sintamos y escribimos lo siguiente: </p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="15dcb55c-d842-4d1e-b8d5-6ec2f74501bb" class="code"><code class="language-Bash">#!/bin/bash
printf &quot;Haciendo copia de seguridad en $HOME...\n&quot;
cp -r $HOME/* /tmp/backupuser/
printf &quot;Copia realizada\n&quot;</code></pre><p id="688a5ca8-24b5-44e5-8164-ef50f47668b7" class="">Para corregir dichos errores basta con leer el texto del mensaje que nos muestra en el terminal, observar el número de la línea en la que se indica la localización del error y si tras su análisis no se consigue solucionarlo, será necesario realizar una ejecución depurada del mismo. Para ello, podemos ejecutar nuestro guion con la orden bash y empleando una de las siguientes opciones:<br/>-n: Chequea errores sintácticos pero sin ejecutar el guion.<br/>-v: Visualiza cada orden del guion antes de ejecutarla.<br/>-x: Actúa igual que –v sólo que sustituyendo, en su caso, las variables por los valores que tienen en ese instante.<br/></p><p id="056f5a8a-6cab-41b0-9204-4054a74a5bc7" class="">Por ejemplo:</p><figure id="d2d64d3d-54d0-4a92-8915-50935812fb13" class="image"><a href="Untitled%206.png"><img style="width:834px" src="Untitled%206.png"/></a></figure><p id="3d1869ba-b33a-47db-aaad-f8a58428bd64" class="">Para comentar un guion (#), es una buena práctica. Por ejemplo:</p><figure id="240b6dc2-b25f-444f-abb5-4683de8e633f" class="image"><a href="Untitled%207.png"><img style="width:786px" src="Untitled%207.png"/></a></figure><h2 id="c8395457-77a0-436e-87cf-3097d9f798cd" class="">Expresiones con variables</h2><p id="18eb860e-ca97-46f6-b595-a47ce7ef91a5" class="">El shell bash ofrece dos posibles sintaxis para manejar expresiones aritméticas haciendo uso de lo que se denominaexpansión aritmética, o sustitución aritmética, que evalúa una expresión aritmética y sustituye el resultado de la expresión en el lugar donde se utiliza. Ambas posibilidades son:<br/>$(( … ))<br/>$[ … ]<br/></p><p id="56e66f64-829a-42a7-aae4-36235b549cee" class="">Se pueden anidar. Por ejemplo:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="7519c66d-7d76-4227-864d-219ae9926ee5" class="code"><code class="language-Bash">$ echo “Faltan $(( (365 - $(date +%j)) / 7 )) semanas hasta el fin de año”</code></pre><h3 id="0c3a058a-bffb-4abd-b0c7-4d43ece28187" class="">Operadores</h3><figure id="87d87fee-66ce-4b15-a215-429881b98d0c" class="image"><a href="Untitled%208.png"><img style="width:789px" src="Untitled%208.png"/></a></figure><p id="455a035d-d4cd-4799-88b8-061590a1879c" class="">En el resultado del cálculo de expresiones aritméticas, bash solamente trabaja con números enteros, por lo que si se necesitase calcular un resultado con decimales, habría que utilizar una forma alternativa, como puede ser la ofrecida por la orden bc, cuya opción -l, letra “ele”, permite hacer algunos cálculos matemáticos (admite otras posibilidades que pueden verse mediante man).</p><p id="54b304a7-b244-4dd6-afb4-7d4891ba784b" class="">Ejemplo:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="f64f2815-ca17-43b8-9ed1-fdfe2aa09ef6" class="code"><code class="language-Bash">$ echo 6/5|bc -l</code></pre><h3 id="cc04d0f7-bda6-4f61-8bd7-11027fea576d" class="">Operadores Relacionales</h3><figure id="865af02a-1128-4a9a-921c-2d7e7a410ca7" class="image"><a href="Untitled%209.png"><img style="width:788px" src="Untitled%209.png"/></a></figure><h3 id="64f1827f-c093-47a6-9a61-432745809695" class="">Operadores de consulta de archivos</h3><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="cd0ad014-ed57-4200-813f-3d8fe4dca176" class="code"><code class="language-Bash">test &lt;expresion&gt; //true = 0 / false = 1</code></pre><figure id="a231cf63-1ffa-4de2-92cd-2b6a15ef0d11" class="image"><a href="Untitled%2010.png"><img style="width:787px" src="Untitled%2010.png"/></a></figure><p id="a37f92b4-416e-4f73-95b3-d1ffa8f49871" class="">La orden test expresion es equivalente a la orden [ expresion ] (poner espacios entre corchetes).</p><h3 id="087968ef-972d-4012-a7cd-212f58d5fe7c" class="">Asignación y variables aritméticas</h3><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="f313b009-4332-4655-9a69-c92d5c32139b" class="code"><code class="language-Bash">let variableEntera=expresión //Cuidado, sin espacios en blanco
$ let w=3+2
$ let w=&#x27;3 + 2&#x27;
$ let w=&#x27;(4+5)*6&#x27;
$ let “w=4+5*6”
$ let w=4+5*6
$ y=7
$ let w=y%5</code></pre><p id="9b61bee3-fe92-4389-a5c5-2b4d7421fcd0" class="">Las dos primeras asignaciones producen el mismo resultado, a pesar de que en la segunda hay espacios en blanco. Por el contrario, las asignaciones tercera y cuarta no dan el mismo resultado debido al uso o no de paréntesis. Las asignaciones cuarta y quinta son equivalentes, y las dos últimas ponen de manifiesto que en la expresión pueden intervenir otras variables.</p><p id="ec28687c-cc98-4602-9a61-bdf3cde6ce65" class="">Hemos de indicar que (( &lt;expresión&gt; )) equivale a la orden let y presenta ventajas como por ejemplo a la hora de hacer comparaciones numéricas para usarlas en ejecuciones condicionales:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="7181a31a-a4d1-4d03-ba83-898d5eea4792" class="code"><code class="language-Bash">//Ejemplo
$ a=10
$ ((a&lt;10))
$ echo $?
1
$ ((a==10))
$ echo $?
0
$ if let &#x27;a&lt;10&#x27;; then echo “es menor”; else echo “es mayor o igual”; fi
es mayor o igual
//Se puede comprobar si la expresión (8&gt;3)&amp;&amp;(9&lt;5) es falsa, ya que la primera parte de ella es 
//verdadera, pero la segunda es falsa:
$ echo $[$[8&gt;3]&amp;&amp;$[9&lt;5]]
0
$ echo $[8&gt;3] y $[9&lt;5]
1 y 0

// Con operadores de consulta de archivos

$ test -d /bin # comprueba si /bin es un directorio
$ echo $? # nos muestra el estado de la última orden ejecutada, aunque
0 # usado después de test o [ ] da 0 si la evaluación era verdadera
$ [ -w /bin ] # comprueba si tenemos permiso de escritura en /bin
$ echo $? # usado después de test o [ ] da 1 si la evaluación era falsa
1
$ test -f /bin/cat # comprueba si el archivo /bin/cat existe y es plano
$ echo $?
0
$ [ /bin/cat -nt /bin/zz ] # comprueba si /bin/cat es más reciente que /bin/zz
$ echo $?
0 # la evaluación devuelve 1 porque /bin/zz no existe

//Ejemplo

$ cd /bin
$ ls -l cat
-rwxr-xr-x 1 root root 38524 2010-06-11 09:10 cat
$ xacceso=`test -x cat &amp;&amp; echo “true” || echo “false”` # se pueden omitir las “”
$ echo $xacceso
true # indica que sí tenemos permiso de ejecución sobre cat
$ wacceso=`test -w cat &amp;&amp; echo “true” || echo “false”` # se pueden omitir las “”
$ echo $wacceso
false # indica que no tenemos permiso de escritura en cat

//Ejemplo, también podemos combinarlas:

# Si el archivo “ejemplo” no tiene permisos de escritura
$ ls –la ejemplo
-rw-r--r-- 1 usuario usuario 256 29 nov 2016 ejemplo
$ ejemploNOT=`! test –x ejemplo &amp;&amp; echo true || echo false`
$ echo $ejemploNOT
true
# Si es propiedad del usuario que ejecuta la orden y no está vacío
$ ejemploAND=`test –O ejemplo –a –s ejemplo &amp;&amp; echo true || echo false`
$ echo $ejemploAND
true
# Si tiene permisos de lectura o de escritura
$ ejemploOR=`test –r ejemplo –o –w ejemplo &amp;&amp; echo true || echo false`
$ echo $ejemploOR
true</code></pre><h2 id="681734e9-154d-449e-bb99-911d1e6e3a1a" class="">Orden if / else</h2><p id="040f7dbb-bcb5-4708-a6bc-135ea6188496" class=""><div class="indented"><p id="9fcb6831-65eb-4836-a0f4-284016abb501" class="">La sintaxis de la orden condicional if es:<br/><br/></p><figure id="b1bdc52d-1170-46c7-87c2-729bdbc23bf3" class="image"><a href="Untitled%2011.png"><img style="width:281px" src="Untitled%2011.png"/></a></figure><p id="09657f8b-47b4-447b-9a3b-28045597fa0d" class="">El funcionamiento de la orden if es el siguiente: se comienza haciendo la ejecución de la lista de órdenes contenidas en la primera condición; si su estado de salida es 0, entonces se ejecuta la lista de declaraciones que sigue a la palabra then y se termina la ejecución del if; si el estado de salida fuese 1, se comprueba si hay un bloque que comience por elif. En caso de haber varios bloques elif, se evalúa la condición del primero de ellos de forma que si su estado de salida es 0, se hace la parte then correspondiente y termina el if, pero si su estado de salida es 1, se continúa comprobando de manera análoga el siguiente bloque elif, si es que existe. Si el estado de salida de todas las condiciones existentes es 1, se comprueba si hay un bloque else, en cuyo caso se ejecutarían las declaraciones asociadas a él, y termina el if.</p><p id="845c3175-6c4b-4857-a268-ab36640eee24" class="">En el ejemplo siguiente se utiliza la orden if para tener una estructura similar a la que se había planteado anteriormente con test usando “&amp;&amp;” y “||”:</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="1f4e8336-2193-4277-ab77-9b43ce6621b2" class="code"><code class="language-Bash">$ cd /bin
$ ls -l cat
-rwxr-xrx 1 root root 38524 2010-06-11 09:10 cat
$ xacceso=`if test -x cat; then echo “true”; else echo “false”; fi`
$ echo $xacceso
true # indica que sí tenemos permiso de ejecución sobre cat
$ wacceso=`if test -w cat; then echo “true”; else echo “false”; fi`
$ echo $wacceso
false # indica que no tenemos permiso de escritura en cat</code></pre><p id="c3fdbeae-96b2-49cc-bab4-09cc1296654f" class=""><span style="border-bottom:0.05em solid">Comparaciones Aritméticas</span></p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="0d8bc283-0472-47ea-ac7b-b4ec8db50599" class="code"><code class="language-Bash">$ valor=34
$ if [ $valor == &quot;34&quot; ]; then echo sí; else echo no; fi # los huecos en blanco a los
sí # lados de los operadores
$ if [ $valor -eq &quot;34&quot; ]; then echo sí; else echo no; fi# relacionales son
sí # necesarios
$ if [ $valor == &quot;40&quot; ]; then echo sí; else echo no; fi
no</code></pre><p id="ce318867-8160-40d5-ada5-c931e04f646a" class="">¡Cuidado!</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="da4f4caa-20f3-4844-8811-94dba491497e" class="code"><code class="language-Bash">$ if (( $var1 = 234 )); then echo sí; else echo no; fi no
-bash: ((: 234 = 234 : se intentó asignar a algo que no es una variable (el elemento
de error es &quot;= 234 &quot;)
no</code></pre><p id="5defa93e-7e3d-49fb-a5f6-7d49e14b6181" class=""><span style="border-bottom:0.05em solid">Comparaciones entre cadenas de caracteres</span></p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="86a1aa7f-bc30-4a70-ba0b-1259cc8cfad8" class="code"><code class="language-Bash">$ valor=”hola”
$ if [ $valor = &quot;hola&quot; ]; then echo sí; else echo no; fi
sí
$ if [ $valor == &quot;hola&quot; ]; then echo sí; else echo no; fi
sí
$ if [ $valor==&quot;adios&quot; ]; then echo sí; else echo no; fi
si
$ if [ $valor == &quot;adios&quot; ]; then echo sí; else echo no; fi
no
$ if [ $valor != &quot;adiós&quot; ]; then echo sí; else echo no; fi
sí</code></pre><p id="b7e278b4-12f2-4842-b7f8-1dc4aecc74bc" class="">¡Cuidado!</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="9c98fa24-d563-4c99-9850-729c10e20bb4" class="code"><code class="language-Bash">$ valor=”hola amigos”
$ if [ $valor == &quot;hola amigos&quot; ]; then echo sí; else echo no; fi
-bash: [: demasiados argumentos
no
$ if [ “$valor” == &quot;hola amigos&quot; ]; then echo sí; else echo no; fi
sí</code></pre><p id="7494eb21-6e9c-4c6d-b6dd-7245f8cdada4" class=""><span style="border-bottom:0.05em solid">Comparaciones usando órdenes</span></p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="c10c4dae-bded-4270-8281-9e218e99c032" class="code"><code class="language-Bash">$ valor=6
$ if [ valor=3 ]; then echo sí; else echo no; fi
sí # se hace internamente la orden que hay entre corchetes y no
$ echo $valor # da error, pero la supuesta asignación en la condición del
6 # if no tiene efecto sobre la variable que se estaba usando
$ if ls &gt; salida; then echo sí; else echo no; fi
sí # además, el if hace la orden ls sobre el archivo salida
$ cat salida # vemos que la orden ls anterior ha volcado su resultado en
# este archivo, poniendo cada nombre en una línea distinta
# e incluyendo también el nombre “salida”
$ valor=5
$ if valor=3 &amp;&amp; ls ; then echo sí; else echo no; fi
# muestra el resultado de ls y otra línea con sí;
# además, hace la asignación correctamente, tal como podemos ver
$ echo $valor
3 # el if ha cambiado el contenido de la variable valor
$ if rm salida; then echo sí; else echo no; fi 2&gt; sal
# en caso de que el archivo salida exista antes del if, se borra y
# escribe una línea en pantalla poniendo sí;
# en caso de que ese archivo no exista, escribe en pantalla una
# línea con no y pone un mensaje de error en el archivo sal</code></pre><p id="54fc27b2-87b4-499e-bdec-211faad72457" class="">Ejercicios sesion 5</p><p id="69401a1e-3e61-4fa3-bd53-cb02049c44ea" class="">5.1</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="4cf57726-9e4f-48f9-b204-6a6bfaf752d7" class="code"><code class="language-Bash">#!/bin/bash

if [ ! &quot;$#&quot; = 2 ]; then
        echo &quot;Debe de introducir dos parametros&quot;
fi

if [ -d &quot;$1&quot; ]; then
        DIRECTORY=$1
else
        echo &quot;$1 no existe como directorio&quot;
        exit 1
fi

if [ &quot;$2&quot; -gt 0 ]; then
        TAMANIO=$2
else
        echo &quot;El segundo parametro introducido debe ser mayor que 0&quot;
        exit 1
fi

find &quot;$DIRECTORY&quot; -size -&quot;$TAMANIO&quot;&gt;archivosSizN.txt</code></pre><p id="a1e20779-60ce-40da-bf7d-afc0db47ff7f" class="">5.2</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="298cc75f-af75-412d-9a7a-129fca827915" class="code"><code class="language-Bash">#!/bin/bash

if [ -d &quot;$1&quot; ]; then
        DIRECTORY=$1
fi

for archivo in $(ls &quot;$DIRECTORY&quot;)
do
        if [ -d &quot;$archivo&quot; ]; then
                echo &quot;$archivo -&gt; Directorio&quot;
        fi
        if [ -h &quot;$archivo&quot; ]; then
                echo &quot;$archivo -&gt; Enlace&quot;
        fi
        if [ -O &quot;$archivo&quot; ]; then
                echo &quot;$archivo -&gt; Archivo&quot;
        fi
done</code></pre><p id="066e560e-4f98-4f45-8fa0-b779a838096c" class="">5.5</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="91525d43-ee07-4ab2-8c53-2ca0d00fb197" class="code"><code class="language-Bash">#!/bin/bash

process=true

while &quot;$process&quot;;
do
        read -p &quot;Dime un numero: &quot; NUMERO

        if [ &quot;$NUMERO&quot; -gt 1 ] &amp;&amp; [ &quot;$NUMERO&quot; -lt 10 ]; then
                echo &quot;Has proporcionado un numero correcto&quot;
                process=false
        fi
done

printf &quot;\nFin del programa&quot;</code></pre><p id="4c71a863-8534-4c00-aba0-1d3b9e66aa80" class="">5.7</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="06442046-4aa9-42b6-ba81-b940e72bffda" class="code"><code class="language-Bash">!/bin/bash

TERM=$1

encontrado=false

for linea in $(cat /etc/shells)
do
        if [ &quot;$linea&quot; == &quot;$TERM&quot; ]; then
                encontrado=true
                break
         fi
done

if [ &quot;$encontrado&quot; == true ]; then
        for line in $(cat /etc/passwd | cut -d&#x27;:&#x27; --fields=1,7)
        do
                if [ $(echo $line | cut -d&#x27;:&#x27; -f2) == &quot;$TERM&quot; ]; then
                        echo $(echo $line | cut -d&#x27;:&#x27; -f1)
                fi
        done
fi</code></pre><p id="7f4bfd93-de9f-4066-b43e-3f3fa6f88fc2" class="">5.8</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="663c3bc4-4969-403f-9107-e69096dbaa60" class="code"><code class="language-Bash">#!/bin/bash

if [ -e $1 $2 $3 ]; then
        gzip $1 $2 $3
        if [ -d CopiasSeguridad ]; then
                tar -cvf copia$(date +&quot;%y%m%d&quot;).tar.gz *.gz
        else
                mkdir CopiasSeguridad
                tar -cvf CopiasSeguridad/copia$(date +&quot;%y%m%d&quot;).tar.gz *.gz
        fi
fi</code></pre><p id="05bd2813-c0aa-4f36-a9b4-cf01b0aa3807" class="">5.9</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="09b7a16b-3f7c-43e1-aa1a-f1513cd3d008" class="code"><code class="language-Bash">dirname=$1
num_files=$2
basefilename=$3
a=0

if [ ! -d &quot;$dirname&quot; ]; then
    mkdir &quot;$dirname&quot;
    chmod +w &quot;$dirname&quot;
    chmod +r &quot;$dirname&quot;
else
    chmod +w &quot;$dirname&quot;
    chmod +r &quot;$dirname&quot;
fi

if [ &quot;$#&quot; -gt 1 ] &amp;&amp; [ &quot;$num_files&quot; -gt 1 ] &amp;&amp; [ &quot;$num_files&quot; -lt 99 ]; then
    while [ &quot;$a&quot; -lt &quot;$num_files&quot; ]; do
        touch &quot;$dirname/$basefilename$a&quot;
        a=$((a+1))
    done
fi</code></pre><p id="e728d1a3-1f00-4785-aaab-9a9cf3f59505" class="">6.3</p><script src="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/prism.min.js" integrity="sha512-7Z9J3l1+EYfeaPKcGXu3MS/7T+w19WtKQY/n+xzmw4hZhJ9tyYmcUS+4QqAlzhicE5LAfMQSF3iFTK9bQdTxXg==" crossorigin="anonymous" referrerPolicy="no-referrer"></script><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/prism/1.29.0/themes/prism.min.css" integrity="sha512-tN7Ec6zAFaVSG3TpNAKtk4DOHNpSwKHxxrsiw4GHKESGPs5njn/0sMCUMl2svV4wo4BK/rCP7juYz+zx+l6oeQ==" crossorigin="anonymous" referrerPolicy="no-referrer"/><pre id="25a0b88d-3c17-4c54-9b50-4020c881bc3c" class="code"><code class="language-Bash">ps -eo cmd,pmem --sort -pmem | head -2 | tail -1</code></pre><p id="690b2ac0-fcc1-492f-9bf4-a7b8b382de0b" class="">
</p><p id="e8efbc54-2840-4631-a4fd-7e13d3298641" class="">6.4</p><p id="d028aff1-2453-4691-8ded-44ea6e832245" class="">Desde otro terminal con la orden ps -e podemos ver el</p><p id="e336f82f-02d5-41e3-8dd3-48d12779db36" class="">identificador del proceso y con la función kill -SIGSTOP podemos</p><p id="2f4283dd-a308-47ad-9459-82d1a3cf6669" class="">detenerlo, reanudarlo con kill -SIGCONT [PID] y finalizarlo con</p><p id="c7996c02-cd76-4161-8325-d696547990d3" class="">kill -SIGTERM [PID].</p><p id="d52b7c96-414b-4c11-9569-4361a0c72f8f" class="">
</p><p id="b1b58536-c222-4faf-a2a4-005e11fc7902" class="">
</p><figure class="block-color-gray_background callout" style="white-space:pre-wrap;display:flex" id="941225b9-975e-4aab-8337-cb2b6dae5857"><div style="font-size:1.5em"><span class="icon">💡</span></div><div style="width:100%">Hecho por Alejandro Jordán Duran</div></figure><p id="1a1270c5-6aaa-4b8a-a390-cd4314d3408a" class="">
</p></div></p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>
