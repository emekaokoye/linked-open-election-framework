# Situation Analysis
In most part of the world, there is hardly any freely available database of political election results in existence. This is because the data required to compile it is located in different websites or documents. The information is presented in many different formats and many different ways, and the only way the information can be compiled for re-use is by manual methods.

The Linked Open Election Framework is supporting the publication of election results as <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/HTML"><a href="http://en.wikipedia.org/wiki/HTML" itemprop="url"><span itemprop="name">HTML</span></a></span> (the language used to write web pages) embed <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/Machine-readable_data"><a href="http://en.wikipedia.org/wiki/Machine-readable_data" itemprop="url"><span itemprop="name">machine-readable data</span></a></span> (called "Metadata") in the source code. Though invisible to normal users, publishing the information in this way gives it structure and meaning, and allowing machines to understand its meaning.

# What is the Linked Open Election Framework?
<p>The main point of <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/Open_data"><a href="http://en.wikipedia.org/wiki/Open_data" itemprop="url"><span itemprop="name">Open Data</span></a></span> is to aid accountability and transparency and this framework supports the publication and public access to Election results on websites as <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/Linked_open_data"><a href="http://en.wikipedia.org/wiki/Linked_open_data" itemprop="url"><span itemprop="name">Linked Open data</span></a></span> – data that is published under an open licence that allows unrestricted reuse, and that is marked up to identify the structure and meaning, making possible its automated collection for re-publishing and mashing up with other data.</p>

# How does it work?
<p>Rather than publishing using not-so open formats or standards like PDF, HTML, Plain Text, etc, we embed machine-readable metadata in the HTML source code of web pages. These metadata is derived from information defined from the Election data. Entities or "things" that make up the Election data are defined as items and described in an HTML page. Each item is made up of one or more key-value pairs: a property and a value. The Microdata syntax is completely made up of HTML attributes. These attributes can be used on any valid HTML element. This gives the information structure and meaning, with a licence to allow collection, collation and reuse by anyone at no cost.</p>

		<p>This structured information or "Structured Data" is a broad term that encompasses various standards and encoding mechanisms but, at the end of the day, refers to information provided to data consumers specifically for machine consumption. This machine-readable code is closely-allied to, but separate from, the presentation layer that us humans consume when we read a web page, providing a way for dumb machines to better understand the entities and connections between entities present in a piece of content.</p>

		<p>Although this additional code does not directly impact the user's experience of the page, it makes a big difference to machines (including Bots, Smart Agents, Search Engines, etc), helping them to "understand" that (for example) this webpage:
		<ul>
		<li> Is a News Article </li>
		<li> Has the headline "Election Results for Ekiti Governorship Election 2014" </li>
		<li> Has information on a "Poll" event held on June 21, 2014 </li>
		</ul>
		</p>

<p>To make this metadata available we have used a vocabulary (or <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/Ontology"><a href="http://en.wikipedia.org/wiki/Ontology" itemprop="url"><span itemprop="name">Ontology</span></a></span>) called <a href="http://linkedopendatang.com/schemas/election/">Linked Open Election</a>. This vocabulary provides a simple way of expressing Election data and information in Linked Data formats. Additionally, we used <span itemscope itemtype="http://schema.org/Thing" itemid="http://dbpedia.org/resource/Schema.org"><a href="http://schema.org" itemprop="url"><span itemprop="name">Schema.org</span></a></span> vocabulary proposed by Google, Bing, Yahoo and others</p>

		<p>This metadata comprises of real-world entities refered by Uniform Resource Identifiers (URIs).</p>
		
		# Benefits
		<p>An immediate benefit of this work will be that search engines will be better able to display links to these News articles, helping users to find relevant stories and to determine from a search engine's listings the relevance of the article to the story that they are searching for and ultimately help to open up references to the data contained in those stories. </p>

		<p>It will create an open database of election results. </p>
		
		# Why is it important?
		<p>The use of Linked Open Data provides a clear signal to every organizations and governments the imminence of the "web of data" or Web 3.0. Every Web Site has to evolve into a Linked Data Space: a location on the Web that provides granular access to discrete data items in line with the core principles of the Linked Data meme.</p>

		<p>Remember, the essence of the <a href="http://kidehen.typepad.com/kingsley_idehens_typepad/2009/04/what-is-linked-data-meme-about.html">Linked Data meme</a> is simply this: you reference data items and access their metadata, in variety of formats via a single HTTP based URI. This approach to Web data publishing is compatible with any HTTP aware user agent (e.g., your Web Browser or tools & applications that provide abstracted access to HTTP).</p>
		
		
		# Do you need a special software to do this?
		<p>No, just the same way to mark up HTML. This also works in Content Management and Blogging system.</p>
		
		

