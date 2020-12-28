[[Space Owl]]
```scss
// space-owl.css

/* Space Owl Theme for [Roam](roamresearch.com)

adapted from [Night Owl by @theianjones](https://github.com/theianjones/roam-research-themes/blob/master/night-owl-ish.css)

I have found that the easiest way to implement new styles in Roam is to add them to Roam. There's a quick two step process.

1. Make a new Roam page called `roam/css`. The name is key. [[roam/css]]
2. Then copy this file's contents into it. When you blur the textarea, the styles should save and take effect.
*/

h1,
h2,
h3,
h4,
h5,
h6,
div {
  font-family: "NotoSerif Nerd Font", serif, system-ui;
}

textarea {
  font-family: "Space Mono for Powerline", "Fantasque Sans Mono", monospace;
}

.roam-block-container {
  max-width: 1000px;
}

.roam-block,
.rm-block-text {
  max-width: 850px;
}

.bp3-button.bp3-minimal {
  color: hsl(340, 84%, 84%);
}

.bp3-button.bp3-minimal:hover {
  color: hsl(340, 84%, 84%);
}

.bp3-elevation-3 {
  background-color: hsl(233, 20%, 50%) !important;
}

.bp3-elevation-3>div:hover {
  background-color: hsl(207, 95%, 8%);
}

.kanban-board {
  background-color: white;
}

.kanban-card {
  background-color: white;
  margin: 8px;
  box-shadow: 0px 1px 2px hsl(203, 21%, 69%);
  padding: 10px;
  border-radius: 2px;
  line-height: 1.3em;
}

.kanban-title {
  text-align: center;
  font-weight: bold;
  padding-top: 6px;
}

.kanban-column {
  background-color: hsl(201, 35%, 92%);
  margin: 0px 4px 0px 4px;
  padding: 4px;
  min-width: 200px;
  border-radius: 3px;
}


.rm-block-ref {
  border-bottom: none;
  font-size: 1em;
  padding: 4px;
  color: hsl(233, 20%, 50%);
}

.rm-block-ref:hover {
  background-color: hsl(233, 20%, 50%);
  color: hsl(207, 95%, 8%);
}

.checkmark {
  background: white;
}

.check-container input:checked~.checkmark {
  background: hsl(197, 84%, 54%);
}

.check-container input:checked~.checkmark:after {
  border-color: white;
}

.rm-level3 {
  color: hsl(223, 23%, 61%);
}

.rm-page-ref-link-color {
  color: hsl(340, 84%, 84%);
}

a {
  color: hsl(233, 84%, 64%) !important;
  transition: 333ms;
}

a:hover,
a:focus {
  color: hsl(203, 84%, 64%) !important;
}

a:visited,
.rm-page-ref {
  color: hsl(253, 84%, 64%) !important;
  transition: 333ms;
}

a:hover:visited,
.rm-page-ref:hover,
.rm-page-ref:focus {
  color: hsl(233, 84%, 64%) !important;
}

.rm-page-ref--tag {
  color: hsl(253, 24%, 54%) !important;
}

.rm-page-ref.rm-page-ref--tag:hover {
  color: hsl(253, 84%, 64%) !important;
}

a:active {
  color: hsl(123, 84%, 64%) !important;
}

.bp3-menu a,
.bp3-menu a:visited,
.bp3-popover-arrow {
  color: white !important;
}

.bp3-menu,
.bp3-popover .bp3-popover-content {
  background-color: hsl(233, 37%, 37%) !important;
}

.bp3-popover .bp3-popover-arrow-fill {
  fill: hsl(233, 37%, 37%) !important;
}

.bp3-overlay div {
  color: white !important;
}

.intercom-app,
.intercom-launcher-frame,
#intercom-container {
  display: none !important;
}

.rm-reference-container {
  margin-bottom: 1em;
}

.rm-reference-item div {
  background-color: hsl(233, 27%, 25%);
}

#right-sidebar div .rm-reference-item div,
.roam-topbar,
.roam-body {
  background-color: #011627;
}

.roam-body-main {
  background-color: #011627;
  color: white;
}

.roam-body .roam-app h1 {
  color: white;
}

#right-sidebar div {
  background-color: hsl(233, 27%, 25%);
  color:hsla(200, 0%, 95%, 0.62);
}

.roam-body .roam-app .roam-sidebar-container {
  background-color: hsl(233, 27%, 25%);
  border-right: 1px hsl(207, 62%, 12%) solid;
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page,
.roam-body .roam-app .roam-sidebar-container>* {
  opacity: 0.92;
  color: white;
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .starred-pages-wrapper .starred-pages .page:hover,
.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button:hover {
  background: hsl(233, 92%, 8%);
  color: white;
  opacity: 0.92;
}

.starred-pages a {
  text-indent: 0.5em;
}

.roam-sidebar-container div,
.bp3-menu div {
  font-family: "NotoSans Nerd Font", system-ui, sans-serif;
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .menu-title {
  color: hsl(206, 15%, 75%);
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .setting {
  background-color: hsla(204, 33%, 34%, 0.5);
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .setting:hover {
  background-color: hsla(204, 33%, 94%, 0.2);
}

.signout {
  color: hsla(200, 0%, 95%, 0.5);
}

.signout:hover {
  color: hsla(200, 0%, 95%, 1);
}

#buffer.tall {
  height: calc(100vh - 50px) !important;
}

.check-container {
  padding-right: 4px;
}

.rm-reference-item {
  background-color: hsl(207, 95%, 8%);
}

.block-highlight-blue,
#roam-right-sidebar-content div .block-highlight-blue div {
  background-color: hsl(196, 65%, 76%);
}

.kanban-board {
  background: hsl(207, 95%, 8%);
  color: white;
}

.kanban-column {
  background-color: hsl(233, 27%, 25%);

}

.kanban-card {
  color: hsl(207, 95%, 8%);
}

/* highlights */

.roam-highlight {
  background-color: hsl(196, 65%, 76%);
}

/* reactions */

.rm-emoji-button {
  background-color: hsl(231, 19%, 50%) !important;
}

/* rows */
.rm-pages-row:first-of-type,
.rm-pages-row-highlight {
  background-color: hsl(233, 27%, 25%) !important;
}



.CodeMirror {
  font-family: 'Space Mono for Powerline' !important;
  height: 300px;
  color: white;
  direction: ltr;
  background: hsl(206, 23%, 12%) !important;
  border-radius: 5px;
}

.CodeMirror-lines {
  padding: 4px 0
}

.CodeMirror pre {
  padding: 0 4px;
  margin-left: 5px;
}

.CodeMirror-scrollbar-filler,
.CodeMirror-gutter-filler {
  background-color: white
}

.CodeMirror-gutters {
  border-right: 0px solid hsl(0, 0%, 87%);
  background-color: hsl(207, 22%, 18%);
  white-space: nowrap;
  width: 30px;
}

.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: hsl(0, 0%, 60%);
  white-space: nowrap;
  font-family: 'Fantasque Sans Mono';
}

.CodeMirror-guttermarker {
  color: black
}

.CodeMirror-guttermarker-subtle {
  color: hsl(0, 0%, 60%)
}

.CodeMirror-cursor {
  border-left: 2px solid hsl(216, 32%, 32%);
  border-right: 0;
  margin-left: 0px;
  width: 0
}

.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver
}

.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: hsl(120, 78%, 70%)
}

.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1
}

.cm-fat-cursor-mark {
  background-color: hsla(120, 100%, 54%, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite
}

.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: hsl(120, 78%, 70%)
}

@-moz-keyframes blink {
  50% {
    background-color: transparent
  }
}

@-webkit-keyframes blink {
  50% {
    background-color: transparent
  }
}

@keyframes blink {
  50% {
    background-color: transparent
  }
}

.cm-tab {
  display: inline-block;
  text-decoration: inherit
}

.CodeMirror-rulers {
  position: absolute;
  left: 0;
  right: 0;
  top: -50px;
  bottom: -20px;
  overflow: hidden
}

.CodeMirror-ruler {
  border-left: 1px solid hsl(0, 0%, 80%);
  top: 0;
  bottom: 0;
  position: absolute
}

.cm-s-default .cm-header {
  color: blue
}

.cm-s-default .cm-quote {
  color: hsl(120, 100%, 30%);
}

.cm-negative {
  color: hsl(360, 69%, 57%);
}

.cm-positive {
  color: hsl(120, 64%, 37%);
}

.cm-header,
.cm-strong {
  font-weight: bold;
}

.cm-em {
  font-style: italic;
}

.cm-link {
  text-decoration: underline;
}

.cm-strikethrough {
  text-decoration: line-through;
}

.cm-s-default .cm-keyword {
  color: hsl(292, 96%, 80%);
}

.cm-s-default .cm-atom {
  color: hsl(307, 82%, 37%);
}

.cm-s-default .cm-number {
  color: hsl(156, 71%, 37%);
}

.cm-s-default .cm-def {
  color: hsl(240, 100%, 50%);
}

.cm-variable {
  color: hsl(217, 34%, 88%);
}

.cm-s-default .cm-variable-2 {
  color: hsl(217, 34%, 88%);
}

.cm-s-default .cm-variable-3,
.cm-s-default .cm-type {
  color: hsl(217, 34%, 88%);
}

.cm-s-default .cm-comment {
  color: hsl(30, 84%, 37%);
}

.cm-s-default .cm-string {
  color: white;
}

.cm-s-default .cm-string-2 {
  color: hsl(20, 84%, 50%);
}

.cm-s-default .cm-meta {
  color: hsl(360, 84%, 86%);
}

.cm-s-default .cm-qualifier {
  color: hsl(0, 0%, 43%);
}

.cm-s-default .cm-builtin {
  color: hsl(199, 84%, 62%);
}

.cm-s-default .cm-bracket {
  color: hsl(60, 17%, 53%);
}

.cm-s-default .cm-tag {
  color: hsl(133, 84%, 47%);
}

.cm-s-default .cm-attribute {
  color: hsl(240, 84%, 60%);
}

.cm-s-default .cm-hr {
  color: hsl(0, 0%, 60%);
}

.cm-s-default .cm-link {
  color: hsl(240, 84%, 60%);
}

.cm-s-default .cm-error {
  color: red;
}

.cm-invalidchar {
  color: red;
}

.CodeMirror-composing {
  border-bottom-width: 2px;
  border-bottom-style: solid;
}

div.CodeMirror span.CodeMirror-matchingbracket {
  color: hsl(120, 84%, 37%);
}

div.CodeMirror span.CodeMirror-nonmatchingbracket {
  color: hsl(360, 67%, 40%);
}

.CodeMirror-matchingtag {
  background: hsla(35, 83%, 50%, 0.3);
}

.CodeMirror-activeline-background {
  background: hsl(207, 22%, 18%);
}

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white
}

.CodeMirror-scroll {
  overflow: scroll !important;
  margin-bottom: -30px;
  margin-right: -30px;
  padding-bottom: 30px;
  height: 100%;
  outline: 0;
  position: relative;
}

.CodeMirror-sizer {
  position: relative;
  border-right: 30px solid transparent;
}

.CodeMirror-vscrollbar,
.CodeMirror-hscrollbar,
.CodeMirror-scrollbar-filler,
.CodeMirror-gutter-filler {
  position: absolute;
  z-index: 6;
  display: none;
}

.CodeMirror-vscrollbar {
  right: 0;
  top: 0;
  overflow-x: hidden;
  overflow-y: scroll;
}

.CodeMirror-hscrollbar {
  bottom: 0;
  left: 0;
  overflow-y: hidden;
  overflow-x: scroll;
}

.CodeMirror-scrollbar-filler {
  right: 0;
  bottom: 0;
}

.CodeMirror-gutter-filler {
  left: 0;
  bottom: 0;
}

.CodeMirror-gutters {
  position: absolute;
  left: 0;
  top: 0;
  min-height: 100%;
  z-index: 3;
}

.CodeMirror-gutter {
  white-space: normal;
  height: 100%;
  display: inline-block;
  vertical-align: top;
  margin-bottom: -30px;
}

.CodeMirror-gutter-wrapper {
  position: absolute;
  z-index: 4;
  background: none !important;
  border: none !important;
}

.CodeMirror-gutter-background {
  position: absolute;
  top: 0;
  bottom: 0;
  z-index: 4;
}

.CodeMirror-gutter-elt {
  position: absolute;
  cursor: default;
  z-index: 4;
}

.CodeMirror-gutter-wrapper ::selection {
  background-color: transparent;
}

.CodeMirror-gutter-wrapper ::-moz-selection {
  background-color: transparent;
}

.CodeMirror-lines {
  cursor: text;
  min-height: 1px;
}

.CodeMirror pre {
  -moz-border-radius: 0;
  -webkit-border-radius: 0;
  border-radius: 0;
  border-width: 0;
  background: transparent;
  font-family: 'Space Mono for Powerline', 'Fantasque Sans Mono', monospace !important;
  font-size: inherit;
  margin: 0;
  white-space: pre;
  word-wrap: normal;
  line-height: inherit;
  color: inherit;
  z-index: 2;
  position: relative;
  overflow: visible;
  -webkit-tap-highlight-color: transparent;
  -webkit-font-variant-ligatures: contextual;
  font-variant-ligatures: contextual;
}

.CodeMirror-wrap pre {
  word-wrap: break-word;
  white-space: pre-wrap;
  word-break: normal;
}

.CodeMirror-linebackground {
  position: absolute;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: 0;
}

.CodeMirror-linewidget {
  position: relative;
  z-index: 2;
  padding: .1px;
}

.CodeMirror-rtl pre {
  direction: rtl;
}

.CodeMirror-code {
  outline: 0;
}

.CodeMirror-scroll,
.CodeMirror-sizer,
.CodeMirror-gutter,
.CodeMirror-gutters,
.CodeMirror-linenumber {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
}

.CodeMirror-measure {
  position: absolute;
  width: 100%;
  height: 0;
  overflow: hidden;
  visibility: hidden;
}

.CodeMirror-cursor {
  position: absolute;
  pointer-events: none;
}

.CodeMirror-measure pre {
  position: static;
}

div.CodeMirror-cursors {
  visibility: hidden;
  position: relative;
  z-index: 3;
}

div.CodeMirror-dragcursors {
  visibility: visible;
}

.CodeMirror-focused div.CodeMirror-cursors {
  visibility: visible;
}

.CodeMirror-selected {
  background: hsla(43, 70%, 95%, 0.9);
}

.CodeMirror-focused .CodeMirror-selected {
  background: hsla(223, 70%, 95%, 0.9);
}

.CodeMirror-crosshair {
  cursor: crosshair
}

.CodeMirror-line::selection,
.CodeMirror-line>span::selection,
.CodeMirror-line>span>span::selection {
  background: hsl(246, 48%, 89%);
}

.CodeMirror-line::-moz-selection,
.CodeMirror-line>span::-moz-selection,
.CodeMirror-line>span>span::-moz-selection {
  background: hsl(246, 48%, 89%);
}

.cm-searching {
  background-color: hsla(60, 87%, 50%, 0.4);
}

.cm-force-border {
  padding-right: .1px
}

@media print {
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

.cm-tab-wrap-hack:after {
  content: '';
}

span.CodeMirror-selectedtext {
  background: 0;
}
```