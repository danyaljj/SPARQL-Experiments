# SPARQL, made easy. 
The following two points made me create this document: 
 - **RDF are everywhere:** a large resources like WikiData and DBPedia, based on refinement of Wikipedia, very useful for NLP research. 
 - **RDF resources are mess:** There are a lot of information about using them spread around the web, which sometimes are erronous. I wanted something simple and handy that I can easily refer to, whenever I need to use it. 

For most this I am using the [SPARQL](https://en.wikipedia.org/wiki/SPARQL) query language. 

## Query tools
There are many online tools to run your queries: 
 - DBPedia's internal SPARQL tool: http://dbpedia.org/sparql
 - WikiData's SAPQL tool: https://query.wikidata.org/

So far [YASGUI](http://yasgui.org)'s been my favorite. 

## Prefixes 
The prefixes help shorten queries. In other words, instead of using full URLs, we define prefixes for them to make the call shorter. All prefix URLs that do not contain hostname are prefixed with the hostname of the generating wiki. 


http://dbpedia.org/sparql?nsdecl
https://www.mediawiki.org/wiki/Wikibase/Indexing/RDF_Dump_Format#Prefixes_used

http://dbpedia.org/sparql?nsdecl


