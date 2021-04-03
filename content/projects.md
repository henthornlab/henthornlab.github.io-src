+++
title = "Current Projects and Tools"
+++

# Projects and Tools

## Control Systems
Students in our lab have the opportunity to implement modern control system elements including safety instrumented systems, distributed I/O, advanced process control, and soft sensors.

The Unit Operations laboratory at RHIT features three DeltaV distributed control systems provided through an Education Agreement with Emerson. We use them as Test, Development, and Production systems.

We now track over 400 tags and we have worked to implement as many different industrial protocols as practical, including: HART, Wireless HART, Profibus DP, Profibus PA, Modbus TCP, EtherNet/IP, DeviceNet, OPC DA, and OPC UA.
<img src="/instruments.jpg" alt="drawing" width="90%"/>


## Analytics and Data Science
Dark data -- data which is locked away in disparate propietrary systems -- has hindered informed decision making for decades. Our students learn to work with data in modern, usable formats and transform it into actionable intelligence. 


Our cloud historian stack is based on:
* Custom developed OPC UA plugin for Telegraf, [available on our Github.](https://github.com/henthornlab/telegraf) 
* InfluxDB for time series data storage
* Grafana for visualization and dashboarding

In Process Analytics, we teach students to process this data using the Python language and Jupyter notebooks. We use NumPy, scikit-learn, and pandas for analysis. For plotting we use Plotly, Seaborn, and Matplotlib.

<img src="/pairplot.png" alt="drawing" width="90%"/>

## ICS Modernization and Security
We deal extensively with OPC UA programming, using [Open62541](https://open62541.org/) and [GOPCUA](https://github.com/gopcua/opcua).

In addition, we work with modernization of ICS security, focusing on [NIST 800-82R2](https://csrc.nist.gov/publications/detail/sp/800-82/rev-2/final) and [IEC 62443](https://www.iec.ch/cyber-security). 

Students in our lab also get the chance to learn networking and server design. We have projects in:
* Server virualization 
* Containerized workloads and Kubernetes (k3s in particular)
* Setting up firewalls
* Creating VLANs and ACLs
* Emerging network standards such as Ethernet-TSN
* Packet analysis with Wireshark
* Network-based and host intrusion detection (Security Onion, Suricata, Snort, and others)

## Next-Gen Human Machine Interfaces
* Augmented reality HMIs
* On-prem voice assistants
* Virtual assistants for plant safety


