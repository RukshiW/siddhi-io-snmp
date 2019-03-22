siddhi-io-snmp
======================================


The **siddhi-io-snmp extension** is an extension to <a target="_blank" href="https://wso2.github.io/siddhi">Siddhi</a> that allows you to receive and publish events via snmp. This extension works with WSO2 Stream Processor and with standalone Siddhi.

Find some useful links below:

* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp">Source code</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp/releases">Releases</a>
* <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp/issues">Issue tracker</a>

## Latest API Docs 


## How to use 


**Using the extension in <a target="_blank" href="https://github.com/wso2/product-sp">WSO2 Stream Processor</a>**

* You can use this extension in the latest <a target="_blank" href="https://github.com/wso2/product-sp/releases">WSO2 Stream Processor</a> that is a part of <a target="_blank" href="http://wso2.com/analytics?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">WSO2 Analytics</a> offering, with editor, debugger and simulation support.

* This extension is shipped by default with WSO2 Stream Processor, if you wish to use an alternative version of this extension you can replace the component <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp/releases">jar</a> that can be found in the `<STREAM_PROCESSOR_HOME>/lib` directory.

**Using the extension as a <a target="_blank" href="https://wso2.github.io/siddhi/documentation/running-as-a-java-library">java library</a>**

* This extension can be added as a maven dependency along with other Siddhi dependencies to your project.

```
     <dependency>
        <groupId>org.wso2.extension.siddhi.io.snmp</groupId>
        <artifactId>siddhi-io-snmp</artifactId>
        <version>x.x.x</version>
     </dependency>
```

## Jenkins Build Status

---

|  Branch | Build Status |
| :------ |:------------ | 
| master  | [![Build Status](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-io-snmp/badge/icon)](https://wso2.org/jenkins/view/All%20Builds/job/siddhi/job/siddhi-io-snmp/)|

---

## Features

**<a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-snmp/api/latest/#sink">snmp</a><a target="_blank" href="https://siddhi-io.github.io/siddhi/documentation/siddhi-4.0/">(Sink)</a>**

The snmp sink publishes the snmp set request messages using SNMP protocol.


**<a target="_blank" href="https://wso2-extensions.github.io/siddhi-io-snmp/api/latest/#source">snmp</a><a target="_blank" href="https://siddhi-io.github.io/siddhi/documentation/siddhi-4.0/">(Source)</a>**

The snmp source consumes the SNMP response of the SNMP get request messages using SNMP protocol.

## How to Contribute
 
  * Report issues at <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp/issues">GitHub Issue Tracker</a>.
  
  * Send your contributions as pull requests to the <a target="_blank" href="https://github.com/wso2-extensions/siddhi-io-snmp/tree/master">master branch</a>. 
 
## Contact us 

 * Post your questions with the <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">"Siddhi"</a> tag in <a target="_blank" href="http://stackoverflow.com/search?q=siddhi">Stackoverflow</a>. 
 
 * Siddhi developers can be contacted via the following mailing lists:
 
    Developers List   : [dev@wso2.org](mailto:dev@wso2.org)
    
    Architecture List : [architecture@wso2.org](mailto:architecture@wso2.org)
 
## Support 

* We are committed to provide support for this extension in production. Our unique approach ensures that all support 
leverages our open development methodology, and is provided by the very same engineers who build the technology. 

* For more details and to take advantage of this unique opportunity contact us via <a target="_blank" href="http://wso2
.com/support?utm_source=gitanalytics&utm_campaign=gitanalytics_Jul17">http://wso2.com/support/</a>. 

