# Lucene search test

This code try to use different
[`Analyzer`](https://lucene.apache.org/core/8_11_1/core/org/apache/lucene/analysis/Analyzer.html)
for text fields which will override 
the default one setup on `IndexWriter`

Start with [Indexer configuration](https://github.com/rhubner/search-test/blob/master/src/main/java/cz/evolvedbinary/search/SearchTest.java#L48)
Then continue with [Custom Field creation](https://github.com/rhubner/search-test/blob/master/src/main/java/cz/evolvedbinary/search/SearchTest.java#L135)