<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1" />
<meta name="generator" content="pdoc 0.5.1" />
<title>pangaeapy/pandataset API documentation</title>
<meta name="description" content="Created on Tue Aug 21 13:31:30 2018 …" />
<link href='https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.0/normalize.min.css' rel='stylesheet'>
<link href='https://cdnjs.cloudflare.com/ajax/libs/10up-sanitize.css/8.0.0/sanitize.min.css' rel='stylesheet'>
<style>.flex{display:flex !important}body{line-height:1.5em}#content{padding:20px}#sidebar{padding:30px;overflow:hidden}.http-server-breadcrumbs{font-size:130%;margin:0 0 15px 0}#footer{font-size:.75em;padding:5px 30px;border-top:1px solid #ddd;text-align:right}#footer p{margin:0 0 0 1em;display:inline-block}#footer p:last-child{margin-right:30px}h1,h2,h3,h4,h5{font-weight:300}h1{font-size:2.5em;line-height:1.1em}h2{font-size:1.75em;margin:1em 0 .50em 0}h3{font-size:1.4em;margin:25px 0 10px 0}h4{margin:0;font-size:105%}a{color:#058;text-decoration:none;transition:color .3s ease-in-out}a:hover{color:#e82}.title code{font-weight:bold}h2[id=^header-]{margin-top:2em}.ident{color:#900}pre code{background:#f8f8f8;font-size:.8em;line-height:1.4em}code{background:#f2f2f1;padding:1px 4px;overflow-wrap:break-word}h1 code{background:transparent}pre{background:#f8f8f8;border:1px solid #ddd;margin:1em 0 1em 4ch}#http-server-module-list{display:flex;flex-flow:column}#http-server-module-list div{display:flex}#http-server-module-list dt{min-width:10%}#http-server-module-list p{margin-top:0}.toc ul,#index{list-style-type:none;margin:0;padding:0}#index code{background:transparent}#index h3{border-bottom:1px solid #ddd}#index ul{padding:0}#index h4{font-weight:bold}#index h4 + ul{margin-bottom:.6em}#index .two-column{column-count:2}dl{margin-bottom:2em}dl dl:last-child{margin-bottom:4em}dd{margin:0 0 1em 3em}#header-classes + dl > dd{margin-bottom:3em}dd dd{margin-left:2em}dd p{margin:10px 0}.name{background:#eee;font-weight:bold;font-size:.85em;padding:5px 10px;display:inline-block;min-width:40%}.name:hover{background:#e0e0e0}.name > span:first-child{white-space:nowrap}.name.class > span:nth-child(2){margin-left:.4em}.name small{font-weight:normal}.inherited{color:#999;border-left:5px solid #eee;padding-left:1em}.inheritance em{font-style:normal;font-weight:bold}.desc h2{font-weight:400;font-size:1.25em}.desc h3{font-size:1em}.desc dt code{background:inherit}.source summary{background:#ffc;font-weight:400;font-size:.8em;width:11em;text-transform:uppercase;padding:0px 8px;border:1px solid #fd6;border-radius:5px;cursor:pointer}.source summary:hover{background:#fe9 !important}.source[open] summary{background:#fda}.source pre{max-height:500px;overflow-y:scroll;margin-bottom:15px}.hlist{list-syle:none}.hlist li{display:inline}.hlist li:after{content:',\2002'}.hlist li:last-child:after{content:none}.hlist .hlist{display:inline;padding-left:1em}img{max-width:100%}.admonition{padding:.1em .5em}.admonition-title{font-weight:bold}.admonition.note,.admonition.info,.admonition.important{background:#aef}.admonition.todo,.admonition.versionadded,.admonition.tip,.admonition.hint{background:#dfd}.admonition.warning,.admonition.versionchanged,.admonition.deprecated{background:#fd4}.admonition.error,.admonition.danger,.admonition.caution{background:lightpink;]</style>
<style media="screen and (min-width: 700px)">@media screen and (min-width:700px){#sidebar{width:30%}#content{width:70%;max-width:100ch;padding:3em 4em;border-left:1px solid #ddd}pre code{font-size:1em}.item .name{font-size:1em}main{display:flex;flex-direction:row-reverse;justify-content:flex-end}.toc ul ul,#index ul{padding-left:1.5em}.toc > ul > li{margin-top:.5em}}</style>
<style media="print">@media print{#sidebar h1{page-break-before:always}.source{display:none}}@media print{*{background:transparent !important;color:#000 !important;box-shadow:none !important;text-shadow:none !important}a,a:visited{text-decoration:underline}a[href]:after{content:" (" attr(href) ")"}abbr[title]:after{content:" (" attr(title) ")"}.ir a:after,a[href^="javascript:"]:after,a[href^="#"]:after{content:""}pre,blockquote{border:1px solid #999;page-break-inside:avoid}thead{display:table-header-group}tr,img{page-break-inside:avoid}img{max-width:100% !important}@page{margin:0.5cm}p,h2,h3{orphans:3;widows:3}h1,h2,h3,h4,h5,h6{page-break-after:avoid}}</style>
</head>
<body>
<main>
<article id="content">
<header>
<h1 class="title"><code>pangaeapy/pandataset</code> module</h1>
</header>
<section id="section-intro">
<p>Created on Tue Aug 21 13:31:30 2018</p>
<p>@author: Robert Huber
@author: Markus Stocker</p>
</section>
<section>
</section>
<section>
</section>
<section>
</section>
<section>
<h2 class="section-title" id="header-classes">Classes</h2>
<dl>
<dt id="pangaeapy/pandataset.PanAuthor"><code class="flex name class">
<span>class <span class="ident">PanAuthor</span></span>
</code></dt>
<dd>
<section class="desc"><p>PANGAEA Author Class.
A simple helper class to declare 'author' objects which are associated as part of the metadata of a given PANGAEA dataset object</p>
<h2 id="parameters">Parameters</h2>
<dl>
<dt><strong><code>lastname</code></strong> :&ensp;<code>str</code></dt>
<dd>The author's first name</dd>
<dt><strong><code>firstname</code></strong> :&ensp;<code>str</code></dt>
<dd>The authors's last name</dd>
</dl>
<h2 id="attributes">Attributes</h2>
<dl>
<dt><strong><code>lastname</code></strong> :&ensp;<code>str</code></dt>
<dd>The author's first name</dd>
<dt><strong><code>firstname</code></strong> :&ensp;<code>str</code></dt>
<dd>The authors's last name</dd>
<dt><strong><code>fullname</code></strong> :&ensp;<code>str</code></dt>
<dd>Combination of lastname, firstname. This attribute is created by the constructor</dd>
</dl></section>
<h3>Methods</h3>
<dl>
<dt id="pangaeapy/pandataset.PanAuthor.__init__"><code class="name flex">
<span>def <span class="ident">__init__</span></span>(<span>self, lastname, firstname=None)</span>
</code></dt>
<dd>
<section class="desc"><p>Initialize self.
See help(type(self)) for accurate signature.</p></section>
</dd>
</dl>
</dd>
<dt id="pangaeapy/pandataset.PanDataSet"><code class="flex name class">
<span>class <span class="ident">PanDataSet</span></span>
</code></dt>
<dd>
<section class="desc"><p>PANGAEA DataSet
The PANGAEA PanDataSet class enables the creation of objects which hold the necessary information, including data as well as metadata, to analyse a given PANGAEA dataset.</p>
<h2 id="parameters">Parameters</h2>
<dl>
<dt><strong><code>id</code></strong> :&ensp;<code>str</code></dt>
<dd>The identifier of a PANGAEA dataset. An integer number or a DOI is accepted here</dd>
<dt><strong><code>deleteFlag</code></strong> :&ensp;<code>str</code></dt>
<dd>in case quality flags are avialable, this parameter defines a flag for which data should not be included in the data dataFrame.
Possible values are listed here: https://wiki.pangaea.de/wiki/Quality_flag</dd>
</dl>
<h2 id="attributes">Attributes</h2>
<dl>
<dt><strong><code>id</code></strong> :&ensp;<code>str</code></dt>
<dd>The identifier of a PANGAEA dataset. An integer number or a DOI is accepted here</dd>
<dt><strong><code>uri</code></strong> :&ensp;<code>str</code></dt>
<dd>The PANGAEA DOI</dd>
<dt><strong><code>title</code></strong> :&ensp;<code>str</code></dt>
<dd>The title of the dataset</dd>
<dt><strong><code>year</code></strong> :&ensp;<code>int</code></dt>
<dd>The publication year of teh dataset</dd>
<dt><strong><code>authors</code></strong> :&ensp;<code>list</code> of <a title="pangaeapy/pandataset.PanAuthor" href="#pangaeapy/pandataset.PanAuthor"><code>PanAuthor</code></a></dt>
<dd>a list containing the PanAuthot objects (author info) of the dataset</dd>
<dt><strong><code>citation</code></strong> :&ensp;<code>str</code></dt>
<dd>the full citation of the dataset including e.g. author, year, title etc..</dd>
<dt><strong><code>params</code></strong> :&ensp;<code>list</code> of <a title="pangaeapy/pandataset.PanParam" href="#pangaeapy/pandataset.PanParam"><code>PanParam</code></a></dt>
<dd>a list of all PanParam objects (the parameters) used in this dataset</dd>
<dt><strong><code>events</code></strong> :&ensp;<code>list</code> of <a title="pangaeapy/pandataset.PanEvent" href="#pangaeapy/pandataset.PanEvent"><code>PanEvent</code></a></dt>
<dd>a list of all PanEvent objects (the events) used in this dataset</dd>
<dt><strong><code>data</code></strong> :&ensp;<code>pandas.DataFrame</code></dt>
<dd>a pandas dataframe holding all the data</dd>
<dt><strong><code>loginstatus</code></strong> :&ensp;<code>str</code></dt>
<dd>a label which indicates if the data set is protected or not default value: 'unrestricted'</dd>
<dt><strong><code>isParent</code></strong> :&ensp;<code>boolean</code></dt>
<dd>indicates if this dataset is a parent data set within a collection of child data sets</dd>
</dl></section>
<h3>Methods</h3>
<dl>
<dt id="pangaeapy/pandataset.PanDataSet.__init__"><code class="name flex">
<span>def <span class="ident">__init__</span></span>(<span>self, id=None, deleteFlag=&#39;&#39;)</span>
</code></dt>
<dd>
<section class="desc"><p>Initialize self.
See help(type(self)) for accurate signature.</p></section>
</dd>
<dt id="pangaeapy/pandataset.PanDataSet.setData"><code class="name flex">
<span>def <span class="ident">setData</span></span>(<span>self, addEventColumns=True)</span>
</code></dt>
<dd>
<section class="desc"><p>This method populates the data DataFrame with data from a PANGAEA dataset.
In addition to the data given in the tabular ASCII file delivered by PANGAEA.</p>
<h2 id="parameters">Parameters:</h2>
<dl>
<dt><strong><code>addEventColumns</code></strong> :&ensp;<code>boolean</code></dt>
<dd>In case Latitude, Longititude, Elevation, Date/Time and Event are not given in the ASCII matrix, which sometimes is possible in single Event datasets,
the setData could add these columns to the dataframe using the information given in the metadata for Event. Default is 'True'</dd>
</dl></section>
</dd>
<dt id="pangaeapy/pandataset.PanDataSet.setID"><code class="name flex">
<span>def <span class="ident">setID</span></span>(<span>self, id)</span>
</code></dt>
<dd>
<section class="desc"><p>Initialize the ID of a data set in case it was not defined in the constructur
Parameters</p>
<hr>
<dl>
<dt><strong><code>id</code></strong> :&ensp;<code>str</code></dt>
<dd>The identifier of a PANGAEA dataset. An integer number or a DOI is accepted here</dd>
</dl></section>
</dd>
<dt id="pangaeapy/pandataset.PanDataSet.setMetadata"><code class="name flex">
<span>def <span class="ident">setMetadata</span></span>(<span>self)</span>
</code></dt>
<dd>
<section class="desc"><p>The method initializes the metadata of the PanDataSet object using the information of a PANGAEA metadata XML file.</p></section>
</dd>
</dl>
</dd>
<dt id="pangaeapy/pandataset.PanEvent"><code class="flex name class">
<span>class <span class="ident">PanEvent</span></span>
</code></dt>
<dd>
<section class="desc"><p>PANGAEA Event Class.
An Event can be regarded as a named entity which is defined by the usage of a distinct method or device at a distinct location during a given time interval for scientific purposes.
More infos on PANGAEA's Evenmts can be found here: https://wiki.pangaea.de/wiki/Event</p>
<h2 id="parameters">Parameters</h2>
<dl>
<dt><strong><code>label</code></strong> :&ensp;<code>str</code></dt>
<dd>A label which is used to name the event</dd>
<dt><strong><code>latitude</code></strong> :&ensp;<code>float</code></dt>
<dd>The latitude of the event location</dd>
<dt><strong><code>longitude</code></strong> :&ensp;<code>float</code></dt>
<dd>The longitude of the event location</dd>
<dt><strong><code>elevation</code></strong> :&ensp;<code>float</code></dt>
<dd>The elevation (relative to sea level) of the event location</dd>
<dt><strong><code>datetime</code></strong> :&ensp;<code>str</code></dt>
<dd>The date and time of the event in ´%Y/%m/%dT%H:%M:%S´ format</dd>
<dt><strong><code>device</code></strong> :&ensp;<code>str</code></dt>
<dd>The device which was used during the event</dd>
</dl>
<h2 id="attributes">Attributes</h2>
<dl>
<dt><strong><code>label</code></strong> :&ensp;<code>str</code></dt>
<dd>A label which is used to name the event</dd>
<dt><strong><code>latitude</code></strong> :&ensp;<code>float</code></dt>
<dd>The latitude of the event location</dd>
<dt><strong><code>longitude</code></strong> :&ensp;<code>float</code></dt>
<dd>The longitude of the event location</dd>
<dt><strong><code>elevation</code></strong> :&ensp;<code>float</code></dt>
<dd>The elevation (relative to sea level) of the event location</dd>
<dt><strong><code>datetime</code></strong> :&ensp;<code>str</code></dt>
<dd>The date and time of the event in ´%Y/%m/%dT%H:%M:%S´ format</dd>
<dt><strong><code>device</code></strong> :&ensp;<code>str</code></dt>
<dd>The device which was used during the event</dd>
</dl></section>
<h3>Methods</h3>
<dl>
<dt id="pangaeapy/pandataset.PanEvent.__init__"><code class="name flex">
<span>def <span class="ident">__init__</span></span>(<span>self, label, latitude, longitude, elevation=None, datetime=None, device=None)</span>
</code></dt>
<dd>
<section class="desc"><p>Initialize self.
See help(type(self)) for accurate signature.</p></section>
</dd>
</dl>
</dd>
<dt id="pangaeapy/pandataset.PanParam"><code class="flex name class">
<span>class <span class="ident">PanParam</span></span>
</code></dt>
<dd>
<section class="desc"><p>PANGAEA Parameter
Shoud be used to create PANGAEA parameter objects. Parameter is used here to represent 'measured variables'</p>
<h2 id="parameters">Parameters</h2>
<dl>
<dt><strong><code>id</code></strong> :&ensp;<code>int</code></dt>
<dd>the identifier for the parameter</dd>
<dt><strong><code>name</code></strong> :&ensp;<code>str</code></dt>
<dd>A long name or title used for the parameter</dd>
<dt><strong><code>shortName</code></strong> :&ensp;<code>str</code></dt>
<dd>A short name or label to identify the parameter</dd>
<dt><strong><code>param_type</code></strong> :&ensp;<code>str</code></dt>
<dd>indicates the data type of the parameter (string, numeric, datetime etc..)</dd>
<dt><strong><code>source</code></strong> :&ensp;<code>str</code></dt>
<dd>defines the category or source for a parameter (e.g. geocode, data, event)&hellip; very PANGAEA specific ;)</dd>
<dt><strong><code>unit</code></strong> :&ensp;<code>str</code></dt>
<dd>the unit of measurement used with this parameter (e.g. m/s, kg etc..)</dd>
</dl>
<h2 id="attributes">Attributes</h2>
<dl>
<dt><strong><code>id</code></strong> :&ensp;<code>int</code></dt>
<dd>the identifier for the parameter</dd>
<dt><strong><code>name</code></strong> :&ensp;<code>str</code></dt>
<dd>A long name or title used for the parameter</dd>
<dt><strong><code>shortName</code></strong> :&ensp;<code>str</code></dt>
<dd>A short name or label to identify the parameter</dd>
<dt><strong><code>synonym</code></strong> :&ensp;<code>dict</code></dt>
<dd>A diconary of synonyms for the parameter whcih e.g. is used by other archives or communities.
The dict key indicates the namespace (possible values currently are CF and OS)</dd>
<dt><strong><code>type</code></strong> :&ensp;<code>str</code></dt>
<dd>indicates the data type of the parameter (string, numeric, datetime etc..)</dd>
<dt><strong><code>source</code></strong> :&ensp;<code>str</code></dt>
<dd>defines the category or source for a parameter (e.g. geocode, data, event)&hellip; very PANGAEA specific ;)</dd>
<dt><strong><code>unit</code></strong> :&ensp;<code>str</code></dt>
<dd>the unit of measurement used with this parameter (e.g. m/s, kg etc..)</dd>
</dl></section>
<h3>Methods</h3>
<dl>
<dt id="pangaeapy/pandataset.PanParam.__init__"><code class="name flex">
<span>def <span class="ident">__init__</span></span>(<span>self, id, name, shortName, param_type, source, unit=None)</span>
</code></dt>
<dd>
<section class="desc"><p>Initialize self.
See help(type(self)) for accurate signature.</p></section>
</dd>
<dt id="pangaeapy/pandataset.PanParam.addSynonym"><code class="name flex">
<span>def <span class="ident">addSynonym</span></span>(<span>name, ns)</span>
</code></dt>
<dd>
<section class="desc"><p>Creates a new synonym for a parameter which is valid within the given name space. Synonyms are stored in the synonym attribute which is a dictionary</p>
<h2 id="parameters">Parameters</h2>
<dl>
<dt><strong><code>name</code></strong> :&ensp;<code>str</code></dt>
<dd>the name of the synonym</dd>
<dt><strong><code>ns</code></strong> :&ensp;<code>str</code></dt>
<dd>the namespace indicator for the sysnonym</dd>
</dl></section>
</dd>
</dl>
</dd>
</dl>
</section>
</article>
<nav id="sidebar">
<h1>Index</h1>
<div class="toc">
<ul></ul>
</div>
<ul id="index">
<li><h3><a href="#header-classes">Classes</a></h3>
<ul>
<li>
<h4><code><a title="pangaeapy/pandataset.PanAuthor" href="#pangaeapy/pandataset.PanAuthor">PanAuthor</a></code></h4>
<ul class="">
<li><code><a title="pangaeapy/pandataset.PanAuthor.__init__" href="#pangaeapy/pandataset.PanAuthor.__init__">__init__</a></code></li>
</ul>
</li>
<li>
<h4><code><a title="pangaeapy/pandataset.PanDataSet" href="#pangaeapy/pandataset.PanDataSet">PanDataSet</a></code></h4>
<ul class="">
<li><code><a title="pangaeapy/pandataset.PanDataSet.__init__" href="#pangaeapy/pandataset.PanDataSet.__init__">__init__</a></code></li>
<li><code><a title="pangaeapy/pandataset.PanDataSet.setData" href="#pangaeapy/pandataset.PanDataSet.setData">setData</a></code></li>
<li><code><a title="pangaeapy/pandataset.PanDataSet.setID" href="#pangaeapy/pandataset.PanDataSet.setID">setID</a></code></li>
<li><code><a title="pangaeapy/pandataset.PanDataSet.setMetadata" href="#pangaeapy/pandataset.PanDataSet.setMetadata">setMetadata</a></code></li>
</ul>
</li>
<li>
<h4><code><a title="pangaeapy/pandataset.PanEvent" href="#pangaeapy/pandataset.PanEvent">PanEvent</a></code></h4>
<ul class="">
<li><code><a title="pangaeapy/pandataset.PanEvent.__init__" href="#pangaeapy/pandataset.PanEvent.__init__">__init__</a></code></li>
</ul>
</li>
<li>
<h4><code><a title="pangaeapy/pandataset.PanParam" href="#pangaeapy/pandataset.PanParam">PanParam</a></code></h4>
<ul class="">
<li><code><a title="pangaeapy/pandataset.PanParam.__init__" href="#pangaeapy/pandataset.PanParam.__init__">__init__</a></code></li>
<li><code><a title="pangaeapy/pandataset.PanParam.addSynonym" href="#pangaeapy/pandataset.PanParam.addSynonym">addSynonym</a></code></li>
</ul>
</li>
</ul>
</li>
</ul>
</nav>
</main>
<footer id="footer">
<p>Generated by <a href="https://pdoc3.github.io/pdoc"><cite>pdoc</cite> 0.5.1</a>.</p>
</footer>
</body>
</html>