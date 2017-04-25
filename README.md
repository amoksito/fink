<!DOCTYPE html><html><head><meta charset="utf-8"><style>body {
  width: 45em;
  border: 1px solid #ddd;
  outline: 1300px solid #fff;
  margin: 16px auto;
}

body .markdown-body
{
  padding: 30px;
}

@font-face {
  font-family: fontawesome-mini;
  src: url(data:font/woff;charset=utf-8;base64,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) format('woff');
}

@font-face {
  font-family: octicons-anchor;
  src: url(data:font/woff;charset=utf-8;base64,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) format('woff');
}

.markdown-body {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  color: #333333;
  overflow: hidden;
  font-family: "Helvetica Neue", Helvetica, "Segoe UI", Arial, freesans, sans-serif;
  font-size: 16px;
  line-height: 1.6;
  word-wrap: break-word;
}

.markdown-body a {
  background: transparent;
}

.markdown-body a:active,
.markdown-body a:hover {
  outline: 0;
}

.markdown-body b,
.markdown-body strong {
  font-weight: bold;
}

.markdown-body mark {
  background: #ff0;
  color: #000;
  font-style: italic;
  font-weight: bold;
}

.markdown-body sub,
.markdown-body sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
.markdown-body sup {
  top: -0.5em;
}
.markdown-body sub {
  bottom: -0.25em;
}

.markdown-body h1 {
  font-size: 2em;
  margin: 0.67em 0;
}

.markdown-body img {
  border: 0;
}

.markdown-body hr {
  -moz-box-sizing: content-box;
  box-sizing: content-box;
  height: 0;
}

.markdown-body pre {
  overflow: auto;
}

.markdown-body code,
.markdown-body kbd,
.markdown-body pre,
.markdown-body samp {
  font-family: monospace, monospace;
  font-size: 1em;
}

.markdown-body input {
  color: inherit;
  font: inherit;
  margin: 0;
}

.markdown-body html input[disabled] {
  cursor: default;
}

.markdown-body input {
  line-height: normal;
}

.markdown-body input[type="checkbox"] {
  box-sizing: border-box;
  padding: 0;
}

.markdown-body table {
  border-collapse: collapse;
  border-spacing: 0;
}

.markdown-body td,
.markdown-body th {
  padding: 0;
}

.markdown-body .codehilitetable {
  border: 0;
  border-spacing: 0;
}

.markdown-body .codehilitetable tr {
  border: 0;
}

.markdown-body .codehilitetable pre,
.markdown-body .codehilitetable div.codehilite {
  margin: 0;
}

.markdown-body .linenos,
.markdown-body .code,
.markdown-body .codehilitetable td {
  border: 0;
  padding: 0;
}

.markdown-body td:not(.linenos) .linenodiv {
  padding: 0 !important;
}

.markdown-body .code {
  width: 100%;
}

.markdown-body .linenos div pre,
.markdown-body .linenodiv pre,
.markdown-body .linenodiv {
  border: 0;
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
  -webkit-border-top-left-radius: 3px;
  -webkit-border-bottom-left-radius: 3px;
  -moz-border-radius-topleft: 3px;
  -moz-border-radius-bottomleft: 3px;
  border-top-left-radius: 3px;
  border-bottom-left-radius: 3px;
}

.markdown-body .code div pre,
.markdown-body .code div {
  border: 0;
  -webkit-border-radius: 0;
  -moz-border-radius: 0;
  border-radius: 0;
  -webkit-border-top-right-radius: 3px;
  -webkit-border-bottom-right-radius: 3px;
  -moz-border-radius-topright: 3px;
  -moz-border-radius-bottomright: 3px;
  border-top-right-radius: 3px;
  border-bottom-right-radius: 3px;
}

.markdown-body * {
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

.markdown-body input {
  font: 13px Helvetica, arial, freesans, clean, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol";
  line-height: 1.4;
}

.markdown-body a {
  color: #4183c4;
  text-decoration: none;
}

.markdown-body a:hover,
.markdown-body a:focus,
.markdown-body a:active {
  text-decoration: underline;
}

.markdown-body hr {
  height: 0;
  margin: 15px 0;
  overflow: hidden;
  background: transparent;
  border: 0;
  border-bottom: 1px solid #ddd;
}

.markdown-body hr:before,
.markdown-body hr:after {
  display: table;
  content: " ";
}

.markdown-body hr:after {
  clear: both;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  margin-top: 15px;
  margin-bottom: 15px;
  line-height: 1.1;
}

.markdown-body h1 {
  font-size: 30px;
}

.markdown-body h2 {
  font-size: 21px;
}

.markdown-body h3 {
  font-size: 16px;
}

.markdown-body h4 {
  font-size: 14px;
}

.markdown-body h5 {
  font-size: 12px;
}

.markdown-body h6 {
  font-size: 11px;
}

.markdown-body blockquote {
  margin: 0;
}

.markdown-body ul,
.markdown-body ol {
  padding: 0;
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body ol ol,
.markdown-body ul ol {
  list-style-type: lower-roman;
}

.markdown-body ul ul ol,
.markdown-body ul ol ol,
.markdown-body ol ul ol,
.markdown-body ol ol ol {
  list-style-type: lower-alpha;
}

.markdown-body dd {
  margin-left: 0;
}

.markdown-body code,
.markdown-body pre,
.markdown-body samp {
  font-family: Consolas, "Liberation Mono", Menlo, Courier, monospace;
  font-size: 12px;
}

.markdown-body pre {
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body kbd {
  background-color: #e7e7e7;
  background-image: -moz-linear-gradient(#fefefe, #e7e7e7);
  background-image: -webkit-linear-gradient(#fefefe, #e7e7e7);
  background-image: linear-gradient(#fefefe, #e7e7e7);
  background-repeat: repeat-x;
  border-radius: 2px;
  border: 1px solid #cfcfcf;
  color: #000;
  padding: 3px 5px;
  line-height: 10px;
  font: 11px Consolas, "Liberation Mono", Menlo, Courier, monospace;
  display: inline-block;
}

.markdown-body>*:first-child {
  margin-top: 0 !important;
}

.markdown-body>*:last-child {
  margin-bottom: 0 !important;
}

.markdown-body .headeranchor-link {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  display: block;
  padding-right: 6px;
  padding-left: 30px;
  margin-left: -30px;
}

.markdown-body .headeranchor-link:focus {
  outline: none;
}

.markdown-body h1,
.markdown-body h2,
.markdown-body h3,
.markdown-body h4,
.markdown-body h5,
.markdown-body h6 {
  position: relative;
  margin-top: 1em;
  margin-bottom: 16px;
  font-weight: bold;
  line-height: 1.4;
}

.markdown-body h1 .headeranchor,
.markdown-body h2 .headeranchor,
.markdown-body h3 .headeranchor,
.markdown-body h4 .headeranchor,
.markdown-body h5 .headeranchor,
.markdown-body h6 .headeranchor {
  display: none;
  color: #000;
  vertical-align: middle;
}

.markdown-body h1:hover .headeranchor-link,
.markdown-body h2:hover .headeranchor-link,
.markdown-body h3:hover .headeranchor-link,
.markdown-body h4:hover .headeranchor-link,
.markdown-body h5:hover .headeranchor-link,
.markdown-body h6:hover .headeranchor-link {
  height: 1em;
  padding-left: 8px;
  margin-left: -30px;
  line-height: 1;
  text-decoration: none;
}

.markdown-body h1:hover .headeranchor-link .headeranchor,
.markdown-body h2:hover .headeranchor-link .headeranchor,
.markdown-body h3:hover .headeranchor-link .headeranchor,
.markdown-body h4:hover .headeranchor-link .headeranchor,
.markdown-body h5:hover .headeranchor-link .headeranchor,
.markdown-body h6:hover .headeranchor-link .headeranchor {
  display: inline-block;
}

.markdown-body h1 {
  padding-bottom: 0.3em;
  font-size: 2.25em;
  line-height: 1.2;
  border-bottom: 1px solid #eee;
}

.markdown-body h2 {
  padding-bottom: 0.3em;
  font-size: 1.75em;
  line-height: 1.225;
  border-bottom: 1px solid #eee;
}

.markdown-body h3 {
  font-size: 1.5em;
  line-height: 1.43;
}

.markdown-body h4 {
  font-size: 1.25em;
}

.markdown-body h5 {
  font-size: 1em;
}

.markdown-body h6 {
  font-size: 1em;
  color: #777;
}

.markdown-body p,
.markdown-body blockquote,
.markdown-body ul,
.markdown-body ol,
.markdown-body dl,
.markdown-body table,
.markdown-body pre,
.markdown-body .admonition {
  margin-top: 0;
  margin-bottom: 16px;
}

.markdown-body hr {
  height: 4px;
  padding: 0;
  margin: 16px 0;
  background-color: #e7e7e7;
  border: 0 none;
}

.markdown-body ul,
.markdown-body ol {
  padding-left: 2em;
}

.markdown-body ul ul,
.markdown-body ul ol,
.markdown-body ol ol,
.markdown-body ol ul {
  margin-top: 0;
  margin-bottom: 0;
}

.markdown-body li>p {
  margin-top: 16px;
}

.markdown-body dl {
  padding: 0;
}

.markdown-body dl dt {
  padding: 0;
  margin-top: 16px;
  font-size: 1em;
  font-style: italic;
  font-weight: bold;
}

.markdown-body dl dd {
  padding: 0 16px;
  margin-bottom: 16px;
}

.markdown-body blockquote {
  padding: 0 15px;
  color: #777;
  border-left: 4px solid #ddd;
}

.markdown-body blockquote>:first-child {
  margin-top: 0;
}

.markdown-body blockquote>:last-child {
  margin-bottom: 0;
}

.markdown-body table {
  display: block;
  width: 100%;
  overflow: auto;
  word-break: normal;
  word-break: keep-all;
}

.markdown-body table th {
  font-weight: bold;
}

.markdown-body table th,
.markdown-body table td {
  padding: 6px 13px;
  border: 1px solid #ddd;
}

.markdown-body table tr {
  background-color: #fff;
  border-top: 1px solid #ccc;
}

.markdown-body table tr:nth-child(2n) {
  background-color: #f8f8f8;
}

.markdown-body img {
  max-width: 100%;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}

.markdown-body code,
.markdown-body samp {
  padding: 0;
  padding-top: 0.2em;
  padding-bottom: 0.2em;
  margin: 0;
  font-size: 85%;
  background-color: rgba(0,0,0,0.04);
  border-radius: 3px;
}

.markdown-body code:before,
.markdown-body code:after {
  letter-spacing: -0.2em;
  content: "\00a0";
}

.markdown-body pre>code {
  padding: 0;
  margin: 0;
  font-size: 100%;
  word-break: normal;
  white-space: pre;
  background: transparent;
  border: 0;
}

.markdown-body .codehilite {
  margin-bottom: 16px;
}

.markdown-body .codehilite pre,
.markdown-body pre {
  padding: 16px;
  overflow: auto;
  font-size: 85%;
  line-height: 1.45;
  background-color: #f7f7f7;
  border-radius: 3px;
}

.markdown-body .codehilite pre {
  margin-bottom: 0;
  word-break: normal;
}

.markdown-body pre {
  word-wrap: normal;
}

.markdown-body pre code {
  display: inline;
  max-width: initial;
  padding: 0;
  margin: 0;
  overflow: initial;
  line-height: inherit;
  word-wrap: normal;
  background-color: transparent;
  border: 0;
}

.markdown-body pre code:before,
.markdown-body pre code:after {
  content: normal;
}

/* Admonition */
.markdown-body .admonition {
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  position: relative;
  border-radius: 3px;
  border: 1px solid #e0e0e0;
  border-left: 6px solid #333;
  padding: 10px 10px 10px 30px;
}

.markdown-body .admonition table {
  color: #333;
}

.markdown-body .admonition p {
  padding: 0;
}

.markdown-body .admonition-title {
  font-weight: bold;
  margin: 0;
}

.markdown-body .admonition>.admonition-title {
  color: #333;
}

.markdown-body .attention>.admonition-title {
  color: #a6d796;
}

.markdown-body .caution>.admonition-title {
  color: #d7a796;
}

.markdown-body .hint>.admonition-title {
  color: #96c6d7;
}

.markdown-body .danger>.admonition-title {
  color: #c25f77;
}

.markdown-body .question>.admonition-title {
  color: #96a6d7;
}

.markdown-body .note>.admonition-title {
  color: #d7c896;
}

.markdown-body .admonition:before,
.markdown-body .attention:before,
.markdown-body .caution:before,
.markdown-body .hint:before,
.markdown-body .danger:before,
.markdown-body .question:before,
.markdown-body .note:before {
  font: normal normal 16px fontawesome-mini;
  -moz-osx-font-smoothing: grayscale;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  line-height: 1.5;
  color: #333;
  position: absolute;
  left: 0;
  top: 0;
  padding-top: 10px;
  padding-left: 10px;
}

.markdown-body .admonition:before {
  content: "\f056\00a0";
  color: 333;
}

.markdown-body .attention:before {
  content: "\f058\00a0";
  color: #a6d796;
}

.markdown-body .caution:before {
  content: "\f06a\00a0";
  color: #d7a796;
}

.markdown-body .hint:before {
  content: "\f05a\00a0";
  color: #96c6d7;
}

.markdown-body .danger:before {
  content: "\f057\00a0";
  color: #c25f77;
}

.markdown-body .question:before {
  content: "\f059\00a0";
  color: #96a6d7;
}

.markdown-body .note:before {
  content: "\f040\00a0";
  color: #d7c896;
}

.markdown-body .admonition::after {
  content: normal;
}

.markdown-body .attention {
  border-left: 6px solid #a6d796;
}

.markdown-body .caution {
  border-left: 6px solid #d7a796;
}

.markdown-body .hint {
  border-left: 6px solid #96c6d7;
}

.markdown-body .danger {
  border-left: 6px solid #c25f77;
}

.markdown-body .question {
  border-left: 6px solid #96a6d7;
}

.markdown-body .note {
  border-left: 6px solid #d7c896;
}

.markdown-body .admonition>*:first-child {
  margin-top: 0 !important;
}

.markdown-body .admonition>*:last-child {
  margin-bottom: 0 !important;
}

/* progress bar*/
.markdown-body .progress {
  display: block;
  width: 300px;
  margin: 10px 0;
  height: 24px;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  background-color: #ededed;
  position: relative;
  box-shadow: inset -1px 1px 3px rgba(0, 0, 0, .1);
}

.markdown-body .progress-label {
  position: absolute;
  text-align: center;
  font-weight: bold;
  width: 100%; margin: 0;
  line-height: 24px;
  color: #333;
  text-shadow: 1px 1px 0 #fefefe, -1px -1px 0 #fefefe, -1px 1px 0 #fefefe, 1px -1px 0 #fefefe, 0 1px 0 #fefefe, 0 -1px 0 #fefefe, 1px 0 0 #fefefe, -1px 0 0 #fefefe, 1px 1px 2px #000;
  -webkit-font-smoothing: antialiased !important;
  white-space: nowrap;
  overflow: hidden;
}

.markdown-body .progress-bar {
  height: 24px;
  float: left;
  -webkit-border-radius: 3px;
  -moz-border-radius: 3px;
  border-radius: 3px;
  background-color: #96c6d7;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, .5), inset 0 -1px 0 rgba(0, 0, 0, .1);
  background-size: 30px 30px;
  background-image: -webkit-linear-gradient(
    135deg, rgba(255, 255, 255, .4) 27%,
    transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%,
    transparent 77%, transparent
  );
  background-image: -moz-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: -ms-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: -o-linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
  background-image: linear-gradient(
    135deg,
    rgba(255, 255, 255, .4) 27%, transparent 27%,
    transparent 52%, rgba(255, 255, 255, .4) 52%,
    rgba(255, 255, 255, .4) 77%, transparent 77%,
    transparent
  );
}

.markdown-body .progress-100plus .progress-bar {
  background-color: #a6d796;
}

.markdown-body .progress-80plus .progress-bar {
  background-color: #c6d796;
}

.markdown-body .progress-60plus .progress-bar {
  background-color: #d7c896;
}

.markdown-body .progress-40plus .progress-bar {
  background-color: #d7a796;
}

.markdown-body .progress-20plus .progress-bar {
  background-color: #d796a6;
}

.markdown-body .progress-0plus .progress-bar {
  background-color: #c25f77;
}

.markdown-body .candystripe-animate .progress-bar{
  -webkit-animation: animate-stripes 3s linear infinite;
  -moz-animation: animate-stripes 3s linear infinite;
  animation: animate-stripes 3s linear infinite;
}

@-webkit-keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

@-moz-keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

@keyframes animate-stripes {
  0% {
    background-position: 0 0;
  }

  100% {
    background-position: 60px 0;
  }
}

.markdown-body .gloss .progress-bar {
  box-shadow:
    inset 0 4px 12px rgba(255, 255, 255, .7),
    inset 0 -12px 0 rgba(0, 0, 0, .05);
}

/* Multimarkdown Critic Blocks */
.markdown-body .critic_mark {
  background: #ff0;
}

.markdown-body .critic_delete {
  color: #c82829;
  text-decoration: line-through;
}

.markdown-body .critic_insert {
  color: #718c00 ;
  text-decoration: underline;
}

.markdown-body .critic_comment {
  color: #8e908c;
  font-style: italic;
}

.markdown-body .headeranchor {
  font: normal normal 16px octicons-anchor;
  line-height: 1;
  display: inline-block;
  text-decoration: none;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}

.headeranchor:before {
  content: '\f05c';
}

.markdown-body .task-list-item {
  list-style-type: none;
}

.markdown-body .task-list-item+.task-list-item {
  margin-top: 3px;
}

.markdown-body .task-list-item input {
  margin: 0 4px 0.25em -20px;
  vertical-align: middle;
}

/* Media */
@media only screen and (min-width: 480px) {
  .markdown-body {
    font-size:14px;
  }
}

@media only screen and (min-width: 768px) {
  .markdown-body {
    font-size:16px;
  }
}

@media print {
  .markdown-body * {
    background: transparent !important;
    color: black !important;
    filter:none !important;
    -ms-filter: none !important;
  }

  .markdown-body {
    font-size:12pt;
    max-width:100%;
    outline:none;
    border: 0;
  }

  .markdown-body a,
  .markdown-body a:visited {
    text-decoration: underline;
  }

  .markdown-body .headeranchor-link {
    display: none;
  }

  .markdown-body a[href]:after {
    content: " (" attr(href) ")";
  }

  .markdown-body abbr[title]:after {
    content: " (" attr(title) ")";
  }

  .markdown-body .ir a:after,
  .markdown-body a[href^="javascript:"]:after,
  .markdown-body a[href^="#"]:after {
    content: "";
  }

  .markdown-body pre {
    white-space: pre;
    white-space: pre-wrap;
    word-wrap: break-word;
  }

  .markdown-body pre,
  .markdown-body blockquote {
    border: 1px solid #999;
    padding-right: 1em;
    page-break-inside: avoid;
  }

  .markdown-body .progress,
  .markdown-body .progress-bar {
    -moz-box-shadow: none;
    -webkit-box-shadow: none;
    box-shadow: none;
  }

  .markdown-body .progress {
    border: 1px solid #ddd;
  }

  .markdown-body .progress-bar {
    height: 22px;
    border-right: 1px solid #ddd;
  }

  .markdown-body tr,
  .markdown-body img {
    page-break-inside: avoid;
  }

  .markdown-body img {
    max-width: 100% !important;
  }

  .markdown-body p,
  .markdown-body h2,
  .markdown-body h3 {
    orphans: 3;
    widows: 3;
  }

  .markdown-body h2,
  .markdown-body h3 {
    page-break-after: avoid;
  }
}
</style><title>Freud y Husserl</title></head><body><article class="markdown-body"><h1 id="freud-y-husserl"><a name="user-content-freud-y-husserl" href="#freud-y-husserl" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>Freud y Husserl</h1>
<p>Por si me sigue leyendo en vez de escribir sus páginas, 3 advertencias preliminares: estoy sumamente incómodo con la parte en la que hablo de los &ldquo;sujetos&rdquo; fenomenológicos (pensando en el yo trsacendental, el yo-empírico, el yo-mónada, etc.), corríjame y mándeme a leer si es tan amable. Ya sé que tengo que leer CM, estoy en camino, ya llegando.</p>
<p>2) Me pasé con Freud al alemán, q se deja leer mucho más fácil de lo q temía, porque mire, posta:</p>
<blockquote>
<p>&ldquo;Bewußt sein ist zunächst ein rein deskriptiver Terminus, der sich auf die unmittelbarste und sicherste Wahrnehmung beruft&rdquo; dice Freud.</p>
</blockquote>
<p>&ldquo;«Ser conciente&gt; es, en primer lugar, una expresión puramente descriptiva, que invoca la percepción más inmediata y segura&rdquo;, traduce muchacho, lo cual no está <em>mal</em>, pero yo diría que F. dice en realidad: &ldquo;ser conciente es, en primer lugar, un término puramente descriptivo, que se refiere a la percepción más immediata y segura.&rdquo; No sé cuán grave es, pero posta que no me parece lo mismo, ud. juzgará. </p>
<p>Y dps, más puntualmente, <em>Verdrängung</em> como &lsquo;represión&rsquo;, me empieza a parecer que es una metáfora que se venga, agrego algo más abajo cuando es relevante.<br />
<em>vorbewusst</em> como &ldquo;precc&rdquo; es directametne <em>misleading</em>, cuando por vorbewusst F. quiere entender <em>latent</em>, como él mismo dice y en lo que posta, parecería, aunque fuera accidentalmente, ser en el sentido fenomenológico: lo que ahora no es temáticamente cc, pero puede volverse realizando los actos correspondientes.</p>
<p>3) Todo lo que sigue es altamente especulativo, al punto en el q empieza a significar &lsquo;poco riguroso&rsquo;, pero no me disculpo.</p>
<h2 id="cc-e-icc-traducido-a-fenomenologico"><a name="user-content-cc-e-icc-traducido-a-fenomenologico" href="#cc-e-icc-traducido-a-fenomenologico" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>CC e Icc traducido a fenomenológico</h2>
<p>Leyendo primeras páginas Das Ich und das Es.</p>
<blockquote>
<p>&ldquo;Die Psychoanalyse kann das Wesen des Psychischen nicht ins Bewußtsein verlegen, sondern muß das Bewußtsein als eine Qualität des Psychischen ansehen, die zu anderen Qualitäten hinzukommen oder wegbleiben mag&rdquo;.</p>
</blockquote>
<p>Tienta la metáfora del rayo atencional y ver algo en el orden de lo temático y lo marginal. Cc= temático; Icc = no-temático. Pero parecería que enseguida hay que agregar una restricción, Icc no es meramente no-tematico, sino más bien &lsquo;intematizable&rsquo; (no en una imposibildad absoulta, sino una que requiere de múltiples mediatizaciones y medio que sólo tenemos el método del psicoanálisis como para intentar llegar, que descansa principalmente en la asociación, que es medio una cagada para el filósofo que quiere hacer epojé y descubrir verdades usando sus superpoderes). Hay que ver, entonces, cómo traducir esa intematizabilidad exigida por Freud a algo fenomenológico coherente. Freud mismo dice: &ldquo;Der Hinweis auf eine Deutlichkeitsskala der Bewußtheit hat nichts Verbindliches und nicht mehr Beweiskraft als etwa die analogen Sätze: »Es gibt so viel Abstufungen der Beleuchtung vom grellsten, blendenden Licht bis zum matten Lichtschimmer, folglich gibt es überhaupt keine Dunkelheit&rdquo;</p>
<p>Hablé en otro lado de constituciones espurias y noemas rotos (Cf. el otro archivito, qué capo que soy, me empiezo a parecer a E.=). Podríamos ahora preguntarnos &lsquo;quién&rsquo; lleva a cabo esos actos. F: &ldquo;Wir haben uns die Vorstellung von einer zusammenhängenden Organisation der seelischen Vorgänge in einer Person gebildet und heißen diese das Ich derselben&rdquo;, pero quiénes son &ldquo;wir&rdquo;?? ¿Cuál de todos los sujetos constituye espuriamente? Quizás ninguno de los de H. Quizás podemos pensar el Icc freudiano (o el ello, capaz en un rato tenga más claro lo relevante de la diferencia) como una &lsquo;parte&rsquo; del yo-empírico, el ello-empírico, con sus propios horizontes, con su propia biografía, con sus propias constituciones y un momento de unidad en eterno equilibrio inestable. Este sujeto, además, sería (en comienzo) inaccesible en cualquier actitud de las conocidas; en otras palabras, para poder comprender el ello-empírico necesitamos entrar en una actitud particular, para poder constituirlo en su verdad (y dejar así de constituir el resto del mundo bajo su influencia, ponele). Quiero decir, el ello-empírico sería diferente del yo-trascendental (este último completamente independiente de aquel), diferente del yo empírico, pero &lsquo;aparecería&rsquo; (si es que lo q&rsquo; hace el yo empírico, en algún sentido, sea aparecer, no en sentido temporal, sino lógico) &lsquo;después&rsquo; (malditas metáforas mal hechas, mal M.), &lsquo;más arriba&rsquo; incluso que el yo-empírico. En actitud natural, las vivencias del ello-empírico se dan a la cc bajo las formas de la neurosis, los sustitutos, las diferentes manifestaciones del icc, incluso si este hecho mismo no es cc para la cc e incluso aunque sí lo sea. </p>
<p>En actitud fenomenológica, epojé, reducción, querríamos suponer, y en gran parte tendríamos razón, que el Icc no aparece para nada, que hicimos epojé de él tmb. Habría que ver cuánto nos sigue apareciendo como parte del ejercicio mismo de hacer epojé.</p>
<p>Jugando con los conceptos a la filosofía especulativa: el ello es el límite entre el cuerpo y la cc (como un todo). Es el &lsquo;resultado&rsquo; de la encarnación del sujeto trascendental. Nacemos siendo puro ello, dice F. El ST todavía es una mónada dormida, necesita que el cerebrito madure y el yo empírico termine de formarse en su maldito devenir ontogénetico. Lamentablemente, para el momento en que el ST está en pleno poder de sus funciones constitutivas, el ello-empírico pasó de ser nuestro deseo corporal desenfrenado, vivido siempre de manera cc, hasta que las primeras operaciones constitutivas de la cc se vieron obligadas a neutralizar componentes afectivos (el deseo puro del ello) por las exigencias del mundo de la vida y el a priori histórico. Cuando a nuestro proto-yo le enseñaron a constituir, le enseñaron pa&rsquo;l orto. Le enseñaron constituciones espurias y noemas rotos. Para tolerar este sinsentido, el proto-yo infante tenía dos opciones. Matar a su padre, diciéndole, ¡no! ¡No solo me cojo a mami, sino que voy a constituir el mundo como corresponde, puto! No como burgués egoista y malo, ni como positivista alienado, lo voy a constituir como es! ¡Bello y lleno de amor! Pero, lamentablemente, ese ese mismo poder inherente al ser humano como tal, porque Dios lo hizo con amor, de constituir el mundo tal y como es, el que le hizo darse cuenta de que no podía matar a papi y el único camino era la sumisión. Inevitablemente, ese auto-ultraje originario sólo puede ser reprimido, para que el mundo cobre sentido, aunque ya se lo hayamos quitado. Que se vuelva ese mundito del apriori historico que nos toca, con sus reglas y sus metas y sus no-verdades. Cuando llega la pubertad, el ello se volvio autónomo e icc al yo, aunque con algo así como &lsquo;eficacia causal&rsquo;, ya que estamos en el orden del o empírico, incluso a ese yo maduro que tiene todos los poderes del ST y constituye mundo como debería, en su formalidad. </p>
<p>Quizás siempre haya un ello para la cc humana, como resultado de la encarnación y de la penosa union del alma trascendental y el cuerpo material. Quizás siempre algo de ese ello se autonomice y vuelva icc, como resultado de las penas y dolores propios de la existencia humana en general. Diríamos que la neurosis es la forma propia que ese ello adquiere en la familia patriarcal, en la civilización occidental, en el capitalismo, lo que fuere. </p>
<p>La resistencia podría ser un &lsquo;componente&rsquo; (descriptivo) de la actitud natural. La represión es más complicada. Decía que podía ser una metáfora q se venga. Si traducimos Verdrängung por &lsquo;expulsión&rsquo;, por ejemplo, podemos dejar de pensar en términos de una &lsquo;fuerza&rsquo; que no sabemos de dónde viene y empezar a pensar en una operación de la cc constituyente que consiste en tornar inaccesibles/icc ciertos noemata, recuerdos, sedimentaciones, horizontes&hellip;</p>
<hr />
<h2 id="el-problema-de-los-actos-objetivantes-y-freud"><a name="user-content-el-problema-de-los-actos-objetivantes-y-freud" href="#el-problema-de-los-actos-objetivantes-y-freud" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>El problema de los actos objetivantes y Freud.</h2>
<p>Algunos interpretes de Husserl, como Steinbock, sostienen que los <strong>actos objetivantes</strong> son fundamento para los <strong>actos no objetivantes</strong> que, de todas formas, construyen sentido. Es decir: los actos no objetivantes tienen la misma estructura <strong>correlación/significado</strong> (tomando significado en su sentido más amplio) que los actos objetivantes. Sin embargo, están fundados. En efecto, actos <em>deseo</em>, <em>valoración</em> y <em>actos afectivos</em> dependen de la construcción/constitución primera del objeto que se desea, valora, o que nos afecta afectivamente; mediante algún otro tipo de acto. </p>
<p>¿Qué pasa cuando tenes un afecto dirigido hacia una objetividad, y todo este mambo es no consciente? Quizá acá está la cuestión más interesante con Freud. Porque, digamoslo así, hay dos posibilidades:</p>
<ol>
<li>Que lo que es ICC sea el correlato del acto-no-objetivante. </li>
<li>Que lo ICC sea la suma de los dos: un objeto ICC, cargado libidinalmente.</li>
</ol>
<p>Obviamente, diría Steinbock/Husserl, un objeto ICC cargado libidinalmente implica que la carga libidinal también va a ser ICC. No podría ser de otra manera, pues solo podemos ser CC de objetos &ldquo;objetivados&rdquo;. Ahora bien, dice Freud, el aparato psíquico tiene maneras de hacernos saber que hay una representación ICC con una carga libidinal &ldquo;frustrada&rdquo;. ¿Cómo lo hace? Mediante desplazamientos de divero tipo: actos fallidos, chistes, estructuras-neuróticas varias, etc., etc. En efecto, si conocemos la teoría psicoanalítica, podemos &ldquo;volvernos conscientes&rdquo; en primera instancia, de que hay un <em>acto no-objetivante</em>, un acto afectivo, valorativo o de deseo, dirigido hacia una objetividad que no logramos ubicar. Así, el acto-no-objetivante puede volverse CC, en cierta medida (y habrá, evidentemente, que objetivarlo, en la reflexión o en donde sea para poder llegar a este resultado) aún cuando la representación o el objeto que está así investido libidinalmente permanezca ICC.</p>
<p>¿Qué es, entonces, lo que <em>se reprime</em>? Antes de responder eso podemos considerar las condiciones trascendentales. Evidentemente, diría Freud si supiera Husserl, se reprime el correlato de un acto intencional. Dicho acto intencional puede haber sido un acto-objetivante, y entonces se reprimira una objetividad-constituida, con todas las cargas propias de otros actos-no-objetivantes que también hayamos dirigido hacia él, o quizá, lo que se reprimen son simplemente los correlatos de estos actos-no-objetivantes: afectos, deseos, valoraciones.</p>
<p>Ahora bien, tomemos el segundo caso. Para que el afecto, deseo, valoración, whatever, <em>desaparezca</em> de la conciencia, no solo tiene que desaparecer el correlato del acto en-sí-mismo. Tiene que desaparecer, también, en cierto sentido, el acto-no-objetivante, que se desarrollo en algún momento preciso del flujo de la conciencia temporal. En efecto, para poder reprimir el afecto, deseo, valoración, whatever, tiene que desaparecer de la cc también la constitución-no-objetivante: esto es, tiene que desaparecer el recuerdo de tal constitución. Y así, junto con el deseo, el afecto, la valoración; se debe reprimir EL EPISODIO en el cual tal constitución fue realizada. </p>
<p>Si logramos traer a la conciencia tal EPISODIO, entonces podremos, a la vez, cambiar el sentido de tal acto-no-objetivante. Por así decirlo, estaremos en condiciones, tendremos la libertad, de cambiar la <strong>posición tética</strong> de tal acto-no-objetivante. </p>
<p>(Comentario desplazado: para Kant solo podre tener una experiencia objetiva como correlato de un acto objetivamente, cuando le adscriba a la intuición empírica -mediante un juicio- el concepto de <em>objeto-en-general</em>. Todo acto objetivante es, así, en Kant, papá-trascendental, un juicio. En Husserl esto cambia para bien, pero no en todos los interpretes).</p>
<p>Pero hay que notar lo siguiente: el trabajo psicoanalitico te lleva hasta un <em>espacio de libertad ampliado</em> por así decirlo. No te garantiza que luego vayas a tomar la desición &ldquo;correcta&rdquo; de cambiar la posición tética del acto en cuestión. Así, dar vuelta la represión no es garantia de curación, tal slo de que tenes la posibilidad de curarte. Y hasta ahí llega la cosa.</p>
<h3 id="el-espacio-de-libertad-ampliado-y-el-sentido-de-la-terapia-psicoanalitica"><a name="user-content-el-espacio-de-libertad-ampliado-y-el-sentido-de-la-terapia-psicoanalitica" href="#el-espacio-de-libertad-ampliado-y-el-sentido-de-la-terapia-psicoanalitica" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>El espacio de libertad ampliado y el sentido de la terapia psicoanalítica</h3>
<p>Justo había pensado algo en esa línea, que no llegué a comentarles el otro día y no sé si lo anoté en algún lado, lo hago antes de olvidarlo.</p>
<p>Quizás habría que decir que al traer el episodio a la consciencia, más que &ldquo;cambiar el sentido de tal acto-no-objetivante&rdquo; lo que ocurre es que lo desarticulamos. Se nos abre entonces el espacio de libertad ampliado y debemos decidir cómo reconstituir, qué nuevo sentido adjudicarle a nuestras vivencias en general, hacia dónde dirigir la líbido que fue liberada del síntoma. Y, se me ocurre, en ese momento hay tres posibilidades:</p>
<ol>
<li>La venganza del icc o la victoria de la neurosis. Uno se deshace del síntoma, pero vuelve a constituir pa&rsquo;l orto, por así decir, sea por motivaciones internas o situaciones externas (nuevas frustraciones o vivencias traumáticas). Los síntomas reaparecen bajo otras formas.</li>
<li>Cura contrarrevolucionaria o insertarse en la serie. Como usted ya dijo tantas veces, la concepción de &lsquo;cura&rsquo; y &lsquo;normalidad&rsquo; freudianas son, en definitiva contrarrevolucionarias, en tanto que apuntan a una adaptación al mundo capitalista, conformidad, alienación, etc. Sin embargo, sería una cura posta respecto de 1 aunque fuera solo por la desaparición de síntomas molestos y una forma más &lsquo;sana&rsquo; de vivir el placer. También podría ser que 1. fuera una suerte de &lsquo;no resignarse&rsquo; a ser contrarrevolucionario y ser más neurótico, pero más revolucionario ¿?</li>
<li>Cura revolucionaria. Sin embargo, parecería que algún tipo de reflexión psicaoanalítica (si no fuera la terapia) es <em>necesaria</em> para vencer las trabas neuróticas-alienadas que el capitalismo nos impuso bajo la forma de la familia patriarcal, etc. Es el camino que nos queda para desarticular nuestras constituciones espurias y constituir bien la comunidad intermonádica del amor.</li>
</ol>
<h2 id="fenomenologia-psicoanalisis-fundamentacion"><a name="user-content-fenomenologia-psicoanalisis-fundamentacion" href="#fenomenologia-psicoanalisis-fundamentacion" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>Fenomenología, Psicoanálisis, Fundamentación.</h2>
<p>El punto es que todo Freud necesita de una fundamentación fenomenológica como dice Mati. No se trata tanto, quizá, de &ldquo;mezclar&rdquo; psicoanálisis y fenomenología, cuanto de fundamentar fenomenológicamente el psicoanálisis. En cierto punto Lacan intenta esto, pero solo hasta cierto punto. Podemos ver el problema especificamente en las fuentes de Lacan: utiliza más a Heidegger que a Husserl. Y ahí la cuestión es siempre la misma: ¿Hasta que punto lo que Heidegger hace es fenomenología? <strong>Crowell</strong>, en su texto <strong>Space of Meaning</strong>, afirma que Heidegger siempre estuvo interesado por algo así como una Lógica Trascendental, dadas las influencias primero neokantianas (de <em>Baden</em>: Rickert, Lask) y luego fenomenológicas (Husserl). Encontrar una suerte de <strong>espacio trascendental de significado</strong> fue siempre, para este interprete, la meta de Heidegger. Y uno puede estar de acuerdo con tal interpretación, ponele. Pero también es cierto que probablemente esa no es la interpretación de Lacan, y por ello falla en intentar darle un rigor fenomenológico al psicoanálisis. </p>
<p>Uno de los puntos centrales de la diferencia entre Freud y Lacan parece ser en la consideración ontológica sobre el tipo de actos que se reprimen. Y esto, ya, debería quedar como un resultado provisorio pero bastante fundamental: </p>
<ul>
<li>Lo que se reprimen son ACTOS (y el recuerdo del acto) junto con sus CORRELATOS. </li>
</ul>
<p>El punto es: ¿reprimimos actos pre-predicativos o actos predicativos? ¿Qué son, por ejemplo, las valoraciones? ¿No son, en cierto sentido, todos los actos-no-objetivantes una suerte de predicación?</p>
<p>Ahí hay algo para explorar. Me pinta que Freud sería más del orden &ldquo;Se reprimen experiencias ante-predicativas&rdquo; y Lacan tipo &ldquo;Se reprime el Lenguaje, se reprimen actos predicativos&rdquo;. Pero evidentemente nada de esto está puesto así explicitamente, en ninguno de los dos. Otra manera de verlo, que es la misma si se quiere, es ponerlo no en terminos de experiencia pre-predicativa y exp. predicativa; sino en términos de experiencia sensible (<em>sichlicke Erfahrung</em>) y exp. categorial. </p>
<p>Ahora, si tenemos en cuenta que Freud fue alumno de Brentano, seguramente algo del orden de la <em>lógica trascendental</em> (si presto atención en las clases) se le jugaba, y posta que pareciera que fuera así.</p>
<p>Se ve, como sea, que Freud está más lejos de &ldquo;la magia&rdquo; incluso que Husserl. No hay una &ldquo;experiencia intuitiva&rdquo; (Wesenschau) o lo que sea en él. No se trata de guiarnos hacia una experiencia mágica, sino tan solo de guiarnos a través del hilo-conductor de un correlato de un acto-no-objetivante, hasta el momento primigenio de tal constitución, para permitirnos la libertad de deshacer la posición tética del mismo. Cuando Rickert le pega, en 1920, a Husserl por ser parte de las corrientes de pensamiento de &ldquo;la filosofía de la vida&rdquo; (<em>Lebensphilosophie</em>), debido justamente a este énfasis de Husserl en la &ldquo;intuición&rdquo;, tiene quizá un punto, que no tendría, si lo hubiera intentado, contra Freud . . .  por mucho que parezca, <em>a priori</em>, lo contrario.</p>
<blockquote>
<p>What matters here is obviously not the articulation of the logical vis-à-vis the psychological: this, in fact, can only lead to a refusal of a philosophy of mere life. Rather, what matters is the doctrine of the &ldquo;vision of essence [ Wesensschau ]&rdquo; which Husserl intends to appoint as fundamental science for all philosophy and which granted him followers. Albeit with a conscious one-sidedness and to this extent unfairly, we try to interpret this doctrine too as a contemporary trend connected to the inclinations towards Erlebnis, considering that phenomenology means the doctrine of a newly discovered kind of intuitive and immediate &ldquo;phenomena [ Erscheinungen ].&rdquo;</p>
</blockquote>
<p>Hay que volver, entonces, a pensar en la articulación de los <strong>niveles de constitución</strong>. Y en dos sentidos: </p>
<ol>
<li>Actos no-objetivantes fundamentados en actos-objetivantes.</li>
<li>Actos predicativos/categoriales fundamentados en actos prepredicativos.</li>
</ol>
<p>Esto es parte de la problemática fenomenológica, pero también de la neokantiana. Sobre todo en LASK, que es uno de los primeros en ver la conexión 2. en <em>Die Logik der Philosophie und die Kategorienlehre</em>. Hasta entonces, la filosofía considera una cierta independencia del nivel lógico, que Lask es el primero en poner en cuestión. Luego, la recepción de su lectura es Ideen, MÉDITATIONS CARTÉSIENNES, etc, etc. Gurwitsch, como &ldquo;mero interprete&rdquo; de Husserl también lo ve claro: </p>
<blockquote>
<p>In his last three books, Formale und transzendental Logik, Erfahrung und Urteil, and Die Krisis der europiischen Wissenschaften und die transzendentale Phånomenologie, Husserl pointed out the rootedness of the predicative sphere in the pre-predicative one and formulated the idea and the program of a genealogy of the predicative sphere. </p>
</blockquote>
<p>Y también:</p>
<blockquote>
<p>In the mentioned books, Husserl has taken important steps in that direction and presented some decisive results. Still, the task is far from being completed. Its completion amounts to nothing less that providing a solution to the problem of the relation between reality and logic or -which is the same from another point of viewthe elaboration of a phenomenological theory of the sciences: the formal ones like logic (in the narrower and technical sense) and mathematics as well as those concerned with reality, that is to say both the natural and human sciences or, to use a German expression, &ldquo;Geisteswissenschaften.&rdquo; It is this task with which, it seems to me, Husserlian phenomenology finds itself confronted at the present stage of its development. Toward that end, it necessary to set forth, first, proto-logical structures and then the operations of consciousness by means of which the transition to the predicative sphere or logic in the wider sense is accomplished. In this respect the notion of thematization may prove a valuable theoretical instrument.</p>
</blockquote>
<p>Lo mismo falta en Freud. </p>
<p>Recordemos lo siguiente sin embargo: el correlato de una experiencia categorial es un <em>Sachverhalt</em> en Husserl, un <em>estado de cosas</em>. Al menos así lo presenta en LU, y eso parece . . .  pobre. La experiencia predicativa debería incluir, como correlatos constitutivos, no solo Sachverhalt (<strong>% ¿qué cosas??</strong>). O eso me pinta en este instante. Además, prosiguiendo esto hasta sus límites, la experiencia predicativa debería dar cuenta también de la articulación inmanente para la vida misma de la totalidad de la vida consicente predicativa, e incluir cosas como las metáforas (la paloma es la paz, el lobo es la caza, la depredación, etc.), las metonímias, etc., etc. (Habría que mirar algunas vez las Urteilstheorie, las <em>Lecciones sobre el Juicio</em> que Husserl imparte en 1905, publicadas por Schuhmann como HUA Materialen V). </p>
<p>Pero, ¿Por qué no encarar el problema entre Freud y Husserl desde el que pareciera es el motivo más obvio? Esto es, la idea de una Fenomenología Deconstructiva (<strong>Abbau</strong>), de una arqueología fenomenológica que intenta excavar en los edificios constitutivos que están a la base de toda constitución de orden superior. </p>
<p>No niego esta posibilidad, pero me parece más bien <em>complementaria</em>. Para analizar la <em>estructura neurótica</em> algo como una cierta <strong>apercepción afectiva</strong> debería ser teorizado, evidentemente. </p>
<ul>
<li>Alta idea: APERCEPCIONES AFECTIVAS.</li>
</ul>
<p>Lo dije ayer en otro lado pero el problema de la <strong>reflexión</strong>, como acto capaz de tematizar un acto que no es objetivante, pero, mediante tal tematización, volverlo objetivante, me parece cada vez más fundamental. Acá, sin embargo, llegamos a uno de esos límites raros del pensamiento: el acto reflexivo es, a su vez, posible de ser objetivado -mediante un nuevo acto de reflexión-, etc, etc. Sin embargo, notese también lo siguiente: si todos tenemos una experiencia &lsquo;cotidiana&rsquo; de esta posibilidad, aunque sea icc o pre-cc, tenemos allí uno de los principios de la lógica: la <strong>iteración</strong>. </p>
<h2 id="horizontes-y-psicoanalisis"><a name="user-content-horizontes-y-psicoanalisis" href="#horizontes-y-psicoanalisis" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>Horizontes y Psicoanálisis.</h2>
<p>A todo esto, tampoco tenemos que olvidarnos de lo que brinda el horizonte al momento presente de cada constitución, en cada uno de las esferas ontológicas o de los reinos del ser u ordenes de existencia en lo que nos encontremos. </p>
<p>Probablemente lo único bueno que hizo Merleau-Ponty fue advertir esta problemática en el orden de lo sensible, de la primera experiencia pre-predicativa. Por ejemplo, con las <strong>constancias cromáticas</strong>: un color solo aparece como tal en relación a los colores que lo rodeen, pero también en relación a otros aspectos visuales &lsquo;no-cromáticos&rsquo; de la cosa: forma, iluminación, etc. A su vez, lo visual (cromático y no-cromático) aparece como tal en relación a otros aspectos sensibles, como los táctiles, etc. Y, en definitiva, esto equivale a que hay percepción sobre un fondo de impercepción. </p>
<p>Lo mismo luego tiene que decirse de la esfera predicativa (tipicos ejemplos de Gurwitsch respecto al <em>campo temático</em> en las esferas conceptuales), al mundo como unidad (tipicos ejemplos de Husserl respecto al mundo como el horizonte de todos los horizontes), etc, etc. </p>
<p>Así, las APERCEPCIONES AFECTIVAS, digamos con Mati, las apercepciones-afectivas-espurias del neurótico, tienen múltiples fuentes probablemente. Se puede excavar en la biografía del individuo en busca de alguna de ellas. Otras dependen del <em>Lebenswelt</em>, y a esas no hay con que darles (o sí: con la Revolución). </p>
<h3 id="m"><a name="user-content-m" href="#m" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>M</h3>
<p>Usted decía más arriba q lo q se reprime son actos y sus correlatos, pero tmb dijo que era el EPISODIO en el que esa constitución había sido realizada, que incluye tmb el correlato. Y parece que un poco el punto es, justamente, que esa constitución (el episodio) ocurrió &lsquo;al interior&rsquo; de determinados horizontes, por eso el &lsquo;sentido&rsquo; de las vivencias (que es en definitiva lo que se desplaza a los síntomas y manifestaciones icc) sólo es tal al interior de esos horizontes. Por eso no podemos hacer generalizaciones empíricas en psicoanálisis y es necesario conocer la biografía del individuo. Y, en definitiva, por eso es tan difícil llegar a ese episodio, porque uno ya no vive en esos horizontes. Si bien no están reprimidos como el episodio y sus componentes, ya no son los horizontes que &lsquo;habita&rsquo; el yo. Y de eso va la terapia PA, intenta reponer esos horizontes para llegar al episodio y al momento de la constitución espuria. Lo hace mediante asociaciones, transferencia, interpretación de otras manifestaciones icc, ¿etc?</p>
<h2 id="valores-y-psicoanalisis"><a name="user-content-valores-y-psicoanalisis" href="#valores-y-psicoanalisis" class="headeranchor-link" aria-hidden="true"><span class="headeranchor"></span></a>Valores y Psicoanálisis.</h2>
<p>Siguiendo con el tema de los horizontes, para Freud toda valoración implica una cierta carga libidinal. Toda constitución-no-objetivante es de ese orden. En efecto, tenemos acá la importancia del horizonte bajo el cuál se realizan estas <em>apercepciones valorativas</em> que vamos a llamarlas. </p>
<p>Husserl elabora conceptualmente varios tipos de Historicidad (mal no haber puesto esto en el trabajo para la Academia). La primera es, valga la tautología, la <strong>historicidad primaria</strong>: se trata de la simple Historia efectiva. Propone metas que sobreviven a la caducidad de las generaciones. Pero no son, todavía, metas infinitas. El problema con el Capitalismo (o el neocapitalismo quizá) es que es un retroceso hacia una Historicidad primaria por así decirlo: las metas infinitas se han cancelado en su operatividad social. No nos proponemos una sociedad mejor, sino ir resolviendo las dificultades que surgen con el mismo devenir de los acontecimientos sociales. Eso es todo. </p>
<p>Y desde ese horizonte de significatividad valorativa última, constituimos valores. Pero estamos negando la verdadera esencia de nuestro ser occidental, y encima la vivimos constantemente. Todos sabemos &ldquo;que hubo otro tiempo mejor&rdquo;. No como la mera perogrullada de &ldquo;todo tiempo pasado fue mejor&rdquo;, sino en un sentido radical. Lo vemos en el arte, en la historia, en la política, en el saber que la URSS fue, etc., etc. Por lo tanto: hay que REPRIMIR diría Freud. O volvemos a una sociedad de metas infinitas, en todo el espectro en que &ldquo;metas infinitas&rdquo; pueden entenderse, o reprimiremos forever, o hasta que desaparezcamos como especie.</p></article></body></html>
