# Add a RedPoint Data Management (RPDM) Server to an HDInsight Linux Cluster
This template adds the RedPoint Data Management Server Edgenode to your existing HDInsight Linux Cluster.
This script adds a virtual machine, configures it to be an edgenode on your cluster and downloads
and sets up the RPDM server software on that newly added node. 
You will also need an RP Data Management Client installation in order to run Data Management on your cluster.

The edge node has the following cluster configurations located locally on the node.<br />
* Hadoop Configs including core-site.xml, hdfs-site.xml, mapred-site.xml, and yarn-site.xml
located at /etc/hadoop/conf <br />
* hive-site.xml located at /etc/hive/conf

**_Note that Data Management must be licensed before use. Azure usage charges will
be assessed as soon as you deploy this stack; consider contacting RedPoint Sales prior to deployment._**

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fredpoint-global%2Fdm4h-hdi-test%2Fmaster%2Fedgenode-only%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>

<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fredpoint-global%2Fdm4h-hdi-test%2Fmaster%2Fedgenode-only%2Fazuredeploy.json" target="_blank">
      <img src="http://armviz.io/visualizebutton.png"/>
</a>
