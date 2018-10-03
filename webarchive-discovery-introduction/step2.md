Now Solr is running, you should be able to see Solr's built-in interface via the _Solr UI_ tab, or by visiting [this link](https://[[HOST_SUBDOMAIN]]-8983-[[KATACODA_HOST]].environments.katacoda.com/)

Once there:

* Solr can hold multiple databases (known as 'cores') -- select the one called `discovery`.
* On the menu that appears, select the `Query` item, after which the built-in query UI should appear.
* Press `Execute Query` and the default query will run, which matches all records in the database. However, as the database is empty there is nothing to see yet.

When you're done, it should look like this:

![Empty Solr Screenshot](https://raw.githubusercontent.com/ukwa/katacoda-scenarios/master/webarchive-discovery-introduction/images/solr-ui-query-empty.png "Empty Solr Screenshot")
