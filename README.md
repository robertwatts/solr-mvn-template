Solr gradle template
===================

This sample gradle script provides a simple way to develop a Solr server and then
deploy it to a servlet container.

Development
-----------

To quickly set up a solr server, run

    gradle runSolr

Access the solr server at http://localhost:8082

Solr configuration is in the `solr/` directory.

Add custom Solr components to `src/main/java` as you would in any other
maven project. These will be compiled into the war file.

Credits and License
-------------------
Orginally forked from https://github.com/alastair/solr-mvn-template and Gradle script copied
from https://github.com/fhopf/solr-facet-example


