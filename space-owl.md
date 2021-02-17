[[Space Owl]]

```scss
/* Space Owl Theme for [Roam](roamresearch.com)

adapted from [Night Owl by @theianjones](https://github.com/theianjones/roam-research-themes/blob/master/night-owl-ish.css)

I have found that the easiest way to implement new styles in Roam is to add them to Roam. There's a quick two step process.

1. Make a new Roam page called `roam/css`. The name is key. [[roam/css]]
2. Then copy this file's contents into it. When you blur the textarea, the styles should save and take effect.
*/

:root {
  --heading-color: hsl(33, 63%, 73%) !important;
  --secondary-color: hsl(63, 63%, 73%) !important;
  --tertiary-color: hsl(153, 53%, 73%) !important;
  --s1: 12px !important;
  --background-color: hsl(233, 92%, 8%) !important;
  --monospaces: "Space Mono for Powerline", monospace !important;
  --serifs: "Aleo", serif, system-ui !important;
  --sanses: "Open Sans", sans-serif !important;
  --shade: hsla(233, 92%, 8%, 0.75) !important;
  --dusk: hsl(233, 27%, 25%);
  --hilit: hsl(233, 92%, 72%);
}

.roam-body {
  --bg: var(--background-color);
}

div {
  font-family: var(--sanses) !important;
}

textarea {
  font-family: var(--serifs) !important;
}

h1,
h2,
h3,
.rm-heading-level-1 > .rm-block__self .rm-block__input,
.rm-heading-level-2 > .rm-block__self .rm-block__input,
.rm-heading-level-3 > .rm-block__self .rm-block__input {
  font-family: var(--sanses) !important;
}

.rm-heading-level-1 > .rm-block__self textarea.rm-block__input,
.rm-heading-level-2 > .rm-block__self textarea.rm-block__input,
.rm-heading-level-3 > .rm-block__self textarea.rm-block__input {
  font-family: var(--serifs) !important;
}

h1,
.rm-heading-level-1 > .rm-block__self .rm-block__input {
  color: var(--heading-color) !important;
}

h2,
.rm-heading-level-2 > .rm-block__self .rm-block__input {
  color: var(--secondary-color) !important;
}

h3,
.rm-heading-level-3 > .rm-block__self .rm-block__input {
  color: var(--tertiary-color) !important;
}

textarea:focus {
  background-image: hsla(233, 30%, 83%, 0.2);
}

.roam-sidebar-container div,
.bp3-menu div {
  font-family: var(--sanses);
}

.roam-block-container {
  max-width: 1000px;
}

.roam-block,
.rm-block-text {
  max-width: 850px;
}

.bp3-button.bp3-minimal {
  color: hsl(233, 64%, 84%) !important;
}

.bp3-button.bp3-minimal:hover {
  color: hsl(233, 84%, 84%) !important;
}

.bp3-elevation-3 {
  background-color: hsl(233, 20%, 50%) !important;
}

.bp3-elevation-3 > div:hover {
  background-color: var(--bg);
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
  background-color: hsl(203, 33%, 92%);
  margin: 0px 4px 0px 4px;
  padding: 4px;
  min-width: 203px;
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
  color: var(--bg);
}

.checkmark {
  background: white;
}

.check-container input:checked ~ .checkmark {
  background: hsl(203, 84%, 54%);
}

.check-container input:checked ~ .checkmark:after {
  border-color: white;
}

.rm-level3 {
  color: hsl(233, 23%, 61%);
}

.rm-page-ref-link-color {
  color: hsl(333, 84%, 84%);
}

a {
  color: hsl(233, 94%, 77%) !important;
  transition: 333ms;
}

a:hover,
a:focus {
  color: hsl(203, 94%, 77%) !important;
}

a:visited,
.rm-page-ref {
  color: hsl(253, 94%, 77%) !important;
  transition: 333ms;
}

a:hover:visited,
.rm-page-ref:hover,
.rm-page-ref:focus {
  color: hsl(233, 94%, 77%) !important;
}

.rm-page-ref--tag {
  color: hsl(253, 24%, 54%) !important;
}

.rm-page-ref.rm-page-ref--tag:hover {
  color: hsl(253, 94%, 77%) !important;
}

a:active {
  color: hsl(133, 94%, 77%) !important;
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
  /* background-color: var(--dusk); */
}

#right-sidebar div .rm-reference-item div,
.roam-topbar,
.roam-body {
  background-color: var(--bg);
}

.roam-body-main {
  background-color: var(--bg);
  color: white;
}

.roam-body .roam-app h1 {
  color: var(--heading-color);
}

#right-sidebar div {
  background-color: var(--dusk);
  color: hsla(203, 0%, 95%, 0.62);
}

.roam-body .roam-app .roam-sidebar-container {
  background-color: var(--dusk);
  border-right: 1px solid hsl(233, 62%, 12%);
}

.roam-body .roam-app .roam-sidebar-container .roam-sidebar-content .log-button,
.roam-body
  .roam-app
  .roam-sidebar-container
  .roam-sidebar-content
  .starred-pages-wrapper,
.roam-body
  .roam-app
  .roam-sidebar-container
  .roam-sidebar-content
  .starred-pages-wrapper
  .starred-pages
  .page,
.roam-body .roam-app .roam-sidebar-container > * {
  opacity: 0.92;
  color: white;
}

.roam-body
  .roam-app
  .roam-sidebar-container
  .roam-sidebar-content
  .starred-pages-wrapper
  .starred-pages
  .page:hover,
.roam-body
  .roam-app
  .roam-sidebar-container
  .roam-sidebar-content
  .log-button:hover {
  background: var(--bg);
  color: white;
  opacity: 0.92;
}

.starred-pages a {
  text-indent: 0.5em;
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .menu-title {
  color: hsl(203, 15%, 75%);
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .setting {
  background-color: hsla(203, 33%, 33%, 0.5);
}

.roam-body .roam-app .roam-sidebar-container .rm-graph-dropdown .setting:hover {
  background-color: hsla(203, 33%, 94%, 0.2);
}

.signout {
  color: hsla(203, 0%, 95%, 0.5);
}

.signout:hover {
  color: hsla(203, 0%, 95%, 1);
}

#buffer.tall {
  height: calc(100vh - 50px) !important;
}

.check-container {
  padding-right: 4px;
}

.rm-reference-item {
  background-color: var(--bg);
}

.block-highlight-blue,
#roam-right-sidebar-content div .block-highlight-blue div {
  background-color: hsl(183, 65%, 76%);
}

.kanban-board {
  background: var(--bg);
  color: white;
}

.kanban-column {
  background-color: var(--dusk);
}

.kanban-card {
  color: var(--bg);
}

/* highlights */

.roam-highlight {
  background-color: hsl(183, 65%, 76%);
}

/* reactions */

.rm-emoji-button {
  background-color: hsl(233, 19%, 50%) !important;
}

/* rows */
.rm-pages-row:first-of-type,
.rm-pages-row-highlight {
  background-color: hsl(233, 27%, 25%) !important;
}

.CodeMirror {
  font-family: var(--monospaces);
  height: 300px;
  color: white;
  direction: ltr;
  background: hsl(203, 23%, 12%) !important;
  border-radius: 5px;
}

.CodeMirror-lines {
  padding: 4px 0;
}

.CodeMirror pre {
  padding: 0 4px;
  margin-left: 5px;
}

.CodeMirror-scrollbar-filler,
.CodeMirror-gutter-filler {
  background-color: white;
}

.CodeMirror-gutters {
  border-right: 0px solid hsl(0, 0%, 87%);
  background-color: hsl(233, 22%, 18%);
  white-space: nowrap;
  width: 30px;
}

.CodeMirror-linenumber {
  padding: 0 3px 0 5px;
  min-width: 20px;
  text-align: right;
  color: hsl(0, 0%, 60%);
  white-space: nowrap;
  font-family: var(--monospaces);
}

.CodeMirror-guttermarker {
  color: black;
}

.CodeMirror-guttermarker-subtle {
  color: hsl(0, 0%, 60%);
}

.CodeMirror-cursor {
  border-left: 2px solid hsl(233, 32%, 32%);
  border-right: 0;
  margin-left: 0px;
  width: 0;
}

.CodeMirror div.CodeMirror-secondarycursor {
  border-left: 1px solid silver;
}

.cm-fat-cursor .CodeMirror-cursor {
  width: auto;
  border: 0 !important;
  background: hsl(133, 80%, 70%);
}

.cm-fat-cursor div.CodeMirror-cursors {
  z-index: 1;
}

.cm-fat-cursor-mark {
  background-color: hsla(133, 92%, 54%, 0.5);
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
}

.cm-animate-fat-cursor {
  width: auto;
  border: 0;
  -webkit-animation: blink 1.06s steps(1) infinite;
  -moz-animation: blink 1.06s steps(1) infinite;
  animation: blink 1.06s steps(1) infinite;
  background-color: hsl(133, 80%, 70%);
}

@-moz-keyframes blink {
  50% {
    background-color: transparent;
  }
}

@-webkit-keyframes blink {
  50% {
    background-color: transparent;
  }
}

@keyframes blink {
  50% {
    background-color: transparent;
  }
}

.cm-tab {
  display: inline-block;
  text-decoration: inherit;
}

.CodeMirror-rulers {
  position: absolute;
  left: 0;
  right: 0;
  top: -50px;
  bottom: -20px;
  overflow: hidden;
}

.CodeMirror-ruler {
  border-left: 1px solid hsl(0, 0%, 80%);
  top: 0;
  bottom: 0;
  position: absolute;
}

.cm-s-default .cm-header {
  color: blue;
}

.cm-s-default .cm-quote {
  color: hsl(133, 92%, 33%);
}

.cm-negative {
  color: hsl(363, 63%, 56%);
}

.cm-positive {
  color: hsl(133, 63%, 33%);
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
  color: hsl(293, 96%, 80%);
}

.cm-s-default .cm-atom {
  color: hsl(303, 82%, 37%);
}

.cm-s-default .cm-number {
  color: hsl(153, 71%, 37%);
}

.cm-s-default .cm-def {
  color: hsl(233, 92%, 54%);
}

.cm-variable {
  color: hsl(233, 33%, 88%);
}

.cm-s-default .cm-variable-2 {
  color: hsl(233, 33%, 88%);
}

.cm-s-default .cm-variable-3,
.cm-s-default .cm-type {
  color: hsl(233, 33%, 88%);
}

.cm-s-default .cm-comment {
  color: hsl(33, 84%, 37%);
}

.cm-s-default .cm-string {
  color: white;
}

.cm-s-default .cm-string-2 {
  color: hsl(23, 84%, 50%);
}

.cm-s-default .cm-meta {
  color: hsl(363, 84%, 86%);
}

.cm-s-default .cm-qualifier {
  color: hsl(3, 0%, 43%);
}

.cm-s-default .cm-builtin {
  color: hsl(203, 84%, 62%);
}

.cm-s-default .cm-bracket {
  color: hsl(63, 17%, 53%);
}

.cm-s-default .cm-tag {
  color: hsl(133, 84%, 47%);
}

.cm-s-default .cm-attribute {
  color: hsl(243, 84%, 60%);
}

.cm-s-default .cm-hr {
  color: hsl(3, 0%, 60%);
}

.cm-s-default .cm-link {
  color: hsl(243, 84%, 60%);
}

.cm-s-default .cm-error {
  color: hsl(3, 96%, 56%);
}

.cm-invalidchar {
  color: hsl(3, 96%, 56%);
}

.CodeMirror {
  height: auto;
}

.CodeMirror-composing {
  border-bottom-width: 2px;
  border-bottom-style: solid;
}

div.CodeMirror span.CodeMirror-matchingbracket {
  color: hsl(133, 84%, 37%);
}

div.CodeMirror span.CodeMirror-nonmatchingbracket {
  color: hsl(363, 67%, 40%);
}

.CodeMirror-matchingtag {
  background: hsla(33, 83%, 50%, 0.3);
}

.CodeMirror-activeline-background {
  background: hsl(233, 22%, 18%);
}

.CodeMirror {
  position: relative;
  overflow: hidden;
  background: white;
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
  font-family: var(--monospaces);
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
  padding: 0.1px;
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
  background: hsla(233, 70%, 95%, 0.9);
}

.CodeMirror-crosshair {
  cursor: crosshair;
}

.CodeMirror-line::selection,
.CodeMirror-line > span::selection,
.CodeMirror-line > span > span::selection {
  background: hsl(243, 48%, 89%);
}

.CodeMirror-line::-moz-selection,
.CodeMirror-line > span::-moz-selection,
.CodeMirror-line > span > span::-moz-selection {
  background: hsl(243, 48%, 89%);
}

.cm-searching {
  background-color: hsla(63, 87%, 50%, 0.4);
}

.cm-force-border {
  padding-right: 0.1px;
}

@media print {
  .CodeMirror div.CodeMirror-cursors {
    visibility: hidden;
  }
}

.cm-tab-wrap-hack:after {
  content: "";
}

span.CodeMirror-selectedtext {
  background: 0;
}

.bp3-datepicker,
.bp3-datepicker * {
  background-color: inherit !important;
}

.bp3-datepicker,
.bp3-html-select select,
.bp3-select select,
.bp3-html-select .bp3-icon,
.bp3-button .bp3-icon {
  color: inherit !important;
}

.bp3-html-select .bp3-icon,
.bp3-button .bp3-icon {
  opacity: 0.6;
}

.rm-find-or-create-wrapper .rm-menu-item .rm-search-title {
  color: var(--secondary-color) !important;
}

.rm-mentions .rm-ref-page-view .rm-title-arrow-wrapper {
  margin-top: 2em;
}

.roam-body select {
  background-color: inherit !important;
  border-color: inherit !important;
  appearance: none !important;
  border-radius: 0.25em;
  color: inherit !important;
}

.roam-body .rm-zoom .rm-zoom-item {
  color: white !important;
}

.rm-embed-container--block {
  background-color: hsla(233, 30%, 12%, 0.7) !important;
}
.block-highlight-yellow {
  color: yellow !important;
  background-color: hsl(233, 30%, 20%) !important;
}

.rm-autocomplete-result {
  color: hsl(299, 75%, 75%) !important;
}
.bp3-dialog {
  background-color: var(--background-color) !important;
}
.level3 {
  color: var(--heading-color);
}
.rm-inline-references {
  background-color: var(--shade);
}
.rm-user-settings .rm-display-name-settings__input {
  background-color: var(--dusk);
}
.rm-user-settings .rm-display-name-settings__input:focus {
  border-color: var(--hilit);
  background-color: var(--dusk);
}

.flex-v-box textarea,
.flex-v-box textarea:focus {
  background-color: var(--dusk);
  padding: 0.25em !important;
  border-radius: 0.25em;
}
```
