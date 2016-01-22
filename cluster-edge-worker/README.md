# Create an HDInsight Linux Cluster with RedPoint Data Management
This template creates an Azure HDInsight Linux cluster in a virtual network with two other VMs:

* an Ubuntu edge node that is bootstrapped with the cluster's configurations and runs the Data Management server
* a Windows VM that runs the Data Management client

The edge node has the following cluster configurations located locally on the node.<br />
* Hadoop Configs including core-site.xml, hdfs-site.xml, mapred-site.xml, and yarn-site.xml
located at /etc/hadoop/conf <br />
* hive-site.xml located at /etc/hive/conf

**_Note that Data Management must be licensed before use. Azure usage charges will
be assessed as soon as you deploy this stack; consider contacting RedPoint Sales prior to deployment._**

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fredpoint-global%2Fdm4h-hdi-test%2Fcluster-edge-worker%2Fmaster%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
