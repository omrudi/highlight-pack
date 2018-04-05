# highlight-pack

&lt;!-- ditemplate --&gt;
&lt;style&gt;
pre{
  padding:.5em 1em;
  margin:0;
  white-space:pre;
  word-wrap:normal;
  overflow:auto;
  background-color:#f1f1f1;
  font-size:12px;
  clear:both;
  border-left:15px solid #ccc;
  border-right:1px solid #ccc;
  color:#999
  }
code{
  font-family:Consolas,Monaco,&#039;Andale Mono&#039;,&#039;Courier New&#039;,Courier,Monospace;
  line-height:15px;
  color:#ff3c00;
  font-size:13.5px
  }
pre code{
  display:block;
  padding:0.5em;
  color:#555
  }
#comments pre code{
  padding:0 !mportant;
  color:#555
  }
pre .comment,pre .template_comment,pre .diff .header,pre .doctype,pre .pi,pre .lisp .string,pre .javadoc{
  color:slategray
  }
pre .keyword,pre .winutils,pre .method,pre .addition,pre .css .tag,pre .request,pre .status,pre .nginx .title{
  color:#859900
  }
pre .number,pre .command,pre .string,pre .tag .value,pre .phpdoc,pre .tex .formula,pre .regexp,pre .hexcolor{
  color:#0077aa
  }
pre .title,pre .localvars,pre .chunk,pre .decorator,pre .built_in,pre .identifier,pre .vhdl .literal,pre .id,pre .css .function{
  color:#990055
  }
pre .variable,pre .lisp .body,pre .smalltalk .number,pre .constant,pre .class .title,pre .parent,pre .haskell .type{
  color:#669900
  }
pre .attribute{
  color:#588400
  }
pre .rules .value{
  color:#333
  }
pre .preprocessor,pre .preprocessor .keyword,pre .shebang,pre .symbol,pre .symbol .string,pre .diff .change,pre .special,pre .attr_selector,pre .important,pre .subst,pre .cdata,pre .clojure .title,pre .css .pseudo{
  color:#a0733f
  }
pre .deletion{
  color:#905
  }
pre .tex .formula{
  background:#073642
  }
pre[data-codetype=&quot;HTML&quot;]{
  border-color:#0B7E88;
  color:#08464B
  }
pre[data-codetype=&quot;CSS&quot;]{
  border-color:#7B990C;
  color:#4B5D08
  }
pre[data-codetype=&quot;JavaScript&quot;]{
  border-color:#545448;
  color:#1F2E24
  }
pre[data-codetype=&quot;JQuery&quot;]{
  border-color:#395540;
  color:#2E2E27
  }
pre[data-codetype=&quot;PHP&quot;]{
  border-color:#FF9900;
  color:#865003
  }
pre[data-codetype=&quot;XML&quot;]{
  border-color:#FF0C39;
  color:#790015
  }
pre[data-codetype=&quot;HTML&quot;]:before{
  background-color:#0B7E88
  }
pre[data-codetype=&quot;CSS&quot;]:before{
  background-color:#7B990C
  }
pre[data-codetype=&quot;JavaScript&quot;]:before{
  background-color:#545448
  }
pre[data-codetype=&quot;JQuery&quot;]:before{
  background-color:#395540
  }
pre[data-codetype=&quot;PHP&quot;]:before{
  background-color:#FF9900
  }
pre[data-codetype=&quot;XML&quot;]:before{
  background-color:#FF0C39
  }
&lt;/tyle&gt;

&lt;head&gt;
.....
.....
&lt;script src=&quot;https://cdn.rawgit.com/omrudi/highlight-pack/31e2a6f6/highlight-pack.js&quot; type=&quot;text/javascript&quot;&gt;&lt;/script&gt;&lt;script&gt;hljs.initHighlightingOnLoad();&lt;/script&gt;
&lt;/head&gt;


How to use?
&lt;pre data-codetype=&quot;HTML&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
&lt;pre data-codetype=&quot;CSS&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
&lt;pre data-codetype=&quot;JavaScript&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
&lt;pre data-codetype=&quot;JQuery&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
&lt;pre data-codetype=&quot;PHP&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
&lt;pre data-codetype=&quot;XML&quot;&gt;&lt;code&gt; ... &lt;/code&gt;&lt;/pre&gt;
