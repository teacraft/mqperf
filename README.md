### MQ Performance documents

This github repository will be used to publish MQ Performance documents from the MQ Performance Team based in Hursley, England.

For many years the traditional place for Performance reports has been the [IBM SupportPac](http://www-01.ibm.com/support/docview.wss?uid=swg27007150) website. 

For new documents and performance articles, we intend to use this repository as the home for MQ Performance collateral.

### MQ Appliance
#### M2001

The M2001 MQ Appliance was released in June 2016, and the accompanying MQ Appliance Performance Report (MPA1) MQ Appliance HA and DR Performance Report (MPA2) have been updated to show the increased performance on the new Hardware:
- M2001 Performance Report [MPA1-2.0.pdf](./MPA1-2.0.pdf)
- M2001 HA and DR Performance Report [MPA2-2.0.pdf](./MPA2-2.0.pdf)

#### M2000

The M2000 MQ Appliance was the original version of the MQ Appliance and the performance reports that relate to this model are available here:
- M2000 Performance Report [MPA1.pdf](./MPA1.pdf) 
- M2000 HA and DR Performance Report [MPA2.pdf](./MPA2.pdf) 

#### AMS

MQ V9 delivered a new AMS Quality of Protection called ‘Confidentiality’. A performance whitepaper has been produced that illustrates the performance profile this new mode brings by comparing it to existing AMS, TLS and non AMS scenarios. [AMSMQAppliance.pdf](./AMSMQAppliance.pdf)


### MQ Distributed

We intend to publish future versions of the MQ base performance documents.

#### AMS

MQ V9 delivered a new AMS Quality of Protection called ‘Confidentiality’. A performance whitepaper has been produced that illustrates the performance profile this new mode brings by comparing it to existing AMS and non AMS scenarios. [AMS.pdf](./AMS.pdf)

#### Persistent Messaging Performance

A paper describing the best practises for persistent messaging, and illustrating the performance of some different filesytems hosting the MQ transaction log of Linux on x86 has now been released:
[mqio_v1.pdf](./mqio_v1.pdf).

### MQ for z/OS

Performance reports for the latest versions of IBM MQ for z/OS are available here. 
- MQ for z/OS Capacity Planning and Tuning guide [MP16.pdf](./mp16.pdf). This report provides capacity planning and setup/tuning information for IBM MQ for z/OS version 9.0 and earlier releases. It describes how to define performance critical queue manager and channel initiator environment parameters. This version of the report includes z14 and CryptoExpress6S benefits, CFCC level 22, using a common value in MSGID/CORRELID on shared queues, the impact of attempting to open queues that are not defined, the effect of first-open and last-close on shared queue plus links to performance blogs.
- MQ for z/OS version 9.0 performance report [MP1K.pdf](./mp1k.pdf). The report discusses the performance of AMS, including the new AMS 'Confidentiality' Quality of Protection, using IBM MQ classes for JMS in both CICS OSGi JVM Server and IMS environments as well as page set statistics.
- MQ for z/OS version 9.0.1 performance report [V901.pdf](./V901.pdf). The report discusses the performance improvements to AMS as part of the first Continuous Delivery release.

#### MQ for z/OS - General white papers

Performance reports for MQ on z/OS documenting our experiences:

- How does MQ for z/OS perform when moving to z14? Paper [MQ for z/OS on z14](./MQ_for_zOS_on_z14.pdf) discusses the performance expectations and what we achieved when moving from z13 to z14. The paper also discusses some of the new features available on z14 that MQ is able to use such as the Crypto Express 6S feature and the re-location of Storage Class Memory from CF Flash to Virtual Flash Memory.
- Performance of streamed persistent workload from z/OS using shared queue to Linux [QREP_Performance_MQ_zOS_to_Linux.pdf](./QREP_Performance_MQ_zOS_to_Linux.pdf). This paper discusses the shared queue configuration options when sending persistent messages to a Linux partner, illustrating differences in performance when the Linux partner uses client or bindings connections. The configuration used simulates a Queue Replication workload.


### MFT

IBM MQ Managed file transfer performance report contains the charts showing Performance measurements to present the performance characteristics of MQ V9.0.5 for Linux platform and to assist capacity planning. This report shows the messaging rate that can be achieved on Linux systems when transferring messages using different chunk sizes. Anyone designing, implementing or sizing Managed File Transfer solutions using WebSphere MQ for V9.0.5 and above and needs to understand the performance characteristics on Linux platform should review this report.
- MFT 9.0.5 Performance Report[Linux-IBM-MQMFT-9.0.5.0-PerformanceReport.pdf](./Linux-IBM-MQMFT-9.0.5.0-PerformanceReport.pdf)

### Get in touch
You can contact @stmassey and @pharrishur with questions about the MQ Performance content.

