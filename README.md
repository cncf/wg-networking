# wg-networking

CNCF Networking WG

## Goals

Explore cloud native networking technology and concepts around container networking interface (CNI).

See this [google doc](https://docs.google.com/document/d/15uuifCseiyUk5kPfnX5Cdj4VNjo79KkmFxm-_HisR3M/edit?usp=sharing) for more information

## Members

* Ken Owens (@kenowens12) [lead]
* Ben Hindman (@benh)
* Alexis Richardson (@monadic)
* Jonathan Boulle (@jonboulle)
* Lee Calcote (@lcalcote)
* Madhu Venugopal
* Jie Yu
* Deepak Bansal
* John Gossman
* Christopher Liljenstolpe
* Bryan Boreham (@bboreham)
* Minhan Xia (@freehan)
* Daniel Nardo (@dnardo)
* Pengfei Ni (@feiskyer)
* John Belamaric (@johnbelamaric)
* Thomas Graf (@tgraf__)
* Jason Venner (@jvmirdel)
* Doug Davis (@duglin)

## Outcomes

* CNI presented to the TOC: https://goo.gl/TeOBzZ
* CNI proposed and accepted as CNCF project: https://github.com/cncf/toc/pull/36

## Meeting Time

The Networking Working Group meets on the 1st and 3rd Tuesday of every month at 8AM PT (USA Pacific):

Join from PC, Mac, Linux, iOS or Android: https://zoom.us/j/175547218

Or iPhone one-tap (US Toll):  +14086380968,,175547218# or +16465588656,,175547218#

Or Telephone:
    Dial: +1 408 638 0968 (US Toll) or +1 646 558 8656 (US Toll)
    +1 855 880 1246 (US Toll Free)
    +1 877 369 0926 (US Toll Free)
    Meeting ID: 175 547 218
    International numbers available: https://zoom.us/zoomconference?m=AnpIc8jE7z2vRW_i71ffOgGCBHWoLDlh
    
NOTE: Please use *6 to mute/un-mute your phone during the call.
    
**Next meeting has been moved to WEDNESDAY July 5th to accomodate for the US Holiday**
    
Here is a public Google calendar so you can add the meetings to your calendar: https://goo.gl/eyutah

Here is a link to a World Time Zone Converter http://www.thetimezoneconverter.com/?t=8:00%20a.m.%20&tz=San%20Francisco&

## Meeting Minutes (or Recordings)

* [2017.04.04](https://docs.google.com/document/d/1rtbk27edum429Q5sEM5IP5FIu2i3qm7naXhZxFFJWs4/edit#) 
* [2017.04.11 ](https://docs.google.com/document/d/1pe5uT_kYJE5zpIMIUE-g9l1ycRF9phOYTq4bcCcSXdw/edit?usp=sharing)
* [2017.04.26](https://docs.google.com/document/d/1g0urMfnlWcDeIqxWtxyEwhMbcjYz4tSvKeAhDCjNT-Q/edit?usp=sharing)
* [2017.06.06](https://docs.google.com/document/d/11oqkQ2OM8120tstCjbwfZ-1RqKyKtVd7c2jCUfiKWfo/edit?usp=sharing)
* [2017.07.05](https://www.youtube.com/watch?v=vc6gYiN69UM&feature=youtu.be)
* [2017.07.18](https://zoom.us/recording/play/tPMy_6EwEcIR8sFY5tvgEhDre--aP7FtqGPUVb-SQD5cTeLb6dZiLYoVnwcK0Gl_)

## Meeting Schedule

* May 1st, 2017 at 4pm CST
  * Topic: _CNCF and CNI Project Overview and proposal_ on [Hangout](https://plus.google.com/hangouts/_/calendar/a2VuY2hyaXN0aW5lb3dlbnNAZ21haWwuY29t.17hnl4inmofpbopu0t7q10k5j8)
* May 10th, 2017 at 11am CST
* June 6th, 2017 at 11am CST
* June 20th, 2017 at 11am CST - Cancelled
* July 5th, 2017 at 11am CDT - Agenda: IPv6 and Weave
* July 18th, 2017 at 11am CDT - Agenda: Project Contiv, CNM Overview
* August 1st, 2017 at 11am CDT - Agenda: Calico, azure-container-networking 

    SDN/network virtualization technologies have been a great enabler and are widely used for the VM based workloads in public and private clouds. With the growing popularity of containers, these technologies are being extended to containers. In this talk, I am going to talk about the challenges that must be addressed to extend SDN technologies to containers. In addition to the much larger scale and much stringent rate of provisioning requirements imposed by container workloads, container SDN must co-exist seamlessly with VM SDN as customers will have both container based and VM based deployments. This means seamless policy language across the container and VM SDN and virtual networks that span across both. I will then describe Azure Virtual Network (VNet) that provides SDN for VMs and is being extended seamlessly to support containers. It provides powerful capabilities such as network isolation, load balancer, internet connectivity, private access to resources and services in Azure, peering networks, on-premise connectivity, traffic filtering, user defined routes, network security policies. azure-container-networking project extends the richness of Azure VNet to container workloads managed by leading orchestrators: Docker, Kubernetes, Mesos DC/OS and Service Fabric. It has a rich API surface and modular architecture to create/manage/connect networks and provision SDN policies. It adopts prevalent network provisioning models (CNM, CNI) to integrate Azure VNet seamlessly with container orchestrators that conform to these standards. Azure container networking provides unified experience and capabilities across Windows and Linux platforms. It also brings the capability of Azure VNet to standalone clusters deployed outside public Azure cloud which provides a unified devops experience and makes transition to public cloud effortless. azure-container-networking is open source project on github that enables dev community to participate in its evolution and help build a rich eco system for container networking with Azure VNet.

* August 15th, 2017 at 11am CDT: Agenda: Fannel, netlink contribution to CNI
