# eZ Platform v1.13 + Solr 6.6 configuration for eZ Platform Cloud (and Platform.sh)

An example configuration for running eZ Platform using the [Solr Search Engine Bundle](https://github.com/ezsystems/ezplatform-solr-search-engine). Used successfully with Solr 6.6 and eZ Platform 1.13 in December 2017.

The Solr configuration will work both with [eZ Platform](http://ezplatform.com) and [eZ Platform EE](https://ez.no/Products/eZ-Platform-Enterprise-Edition). Giving [the Full Stack Symfony CMS](https://symfony-cms.net/ez-platform) powerful search capabilities and scalability to millions of content items using the [Apache Solr](http://lucene.apache.org/solr/) search engine on [eZ Platform Cloud](https://ez.no/Products/eZ-Platform-Cloud), a fully managed Platform as a Service (PaaS).

The configuration is based on the standard configuration files in eZ Platform EE v1.13:
 - https://github.com/ezsystems/ezplatform-ee/blob/1.13/.platform.app.yaml
 - https://github.com/ezsystems/ezplatform-ee/tree/1.13/.platform

Note that you will still need to configure and enable the Solr support as described in the [Solr Bundle documentation](https://doc.ezplatform.com/en/1.13/guide/search/#solr-bundle). Technical documentation for the hosting environment eZ Platform Cloud can be found on the [Platform.sh documentation](https://docs.platform.sh).

No warranty or support. Use as you wish.

