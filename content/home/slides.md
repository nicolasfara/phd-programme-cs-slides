+++
weight = 1
+++

# Context

---

{{% section %}}

# Project description

---

# Extends the Pulverisation approach

**Pulverisation** approach for engineering collective systems by neatly separate the _business logic_ from _deployment aspects_.

A (logical) _device_ is decomposed into **five** components that can be _independently_ deployed in the infrastructure.

{{% multicol %}}

{{% col %}}

Extensions meant to be pursued in the project:

- Support _Dynamic renfiguration_ of the system:
    * **Rules-based**: a priori defined rules based on well-known patterns
    * **AI-based**: policy learned during the system execution to adapt the system to specific _QoS_ requirements
- Support _openness_: allow the system to adapt to the add of new devices and infrastructure nodes
{{% /col %}}

{{% col %}}

{{< figure src="images/pulverization-model.svg" width="60%" >}}

{{% multicol %}}
{{% col %}}
{{< figure src="images/cloud.svg" width="50%" caption="<b>Edge-cloud</b> deployment" >}}
{{% /col %}}
{{% col %}}
{{< figure src="images/peer-to-peer.svg" width="50%" caption="<b>Peer-to-peer</b> deployment" >}}
{{% /col %}}
{{% /multicol %}}

{{% /col %}}

{{% /multicol %}}

---

## Bridge the gap between simulation and real world

{{% multicol %}}
{{% col %}}

- **Pulverisation framework**: concretize the pulverisation approach via a dedicated framework
- Framework _integration_ with simulator(s): allow to simulate the system before its deployment
- _Methodology_ and _techniques_: provide a full-stack solution to engineer CAS effectively
- _Relevant scenarios_: identify and study relevant scenarios and case studies where the approach can be applied (wearable devices, smart cities, etc.)
{{% /col %}}

{{% col %}}
{{< figure src="images/phd-proposal.drawio.png" width="80%" >}}
{{% /col %}}
{{% /multicol %}}

---

## Engineering data stream on the continuum

{{% multicol %}}

{{% col %}}
- _IoT_ devices generate a huge amount of **data** from many different sources
- The _efficient_ and _effective_ management of data streams is an open issue, especially in _edge-cloud_ environments
- Engineer the _data stream_ on the continuum to enable external data analysis (i.e. with big-data techniques)
{{% /col %}}

{{% col %}}

{{< figure src="images/data-stream.drawio.png" >}}

{{% /col %}}
{{% /multicol %}}

{{% /section %}}

---

# Expected results

- **Pulverisation framework**: concretize the pulverisation approach via a dedicated _framework_
- **Rule-based** and **AI-based** dynamic _reconfiguration_ of the system
- **Data stream engineering** on the continuum
- **Integration with CAS frameworks** with a main focus on the _AC_ paradigm

---

# Long term contribution

- Provide new _approaches_ and _solutions_ to challenges in the research community (focus on CAS)
- Understand the role of **CAS** in modern scenarios like _smart cities_ and _large-scale IoT systems_
- Provide reference implementations of the proposed approaches
- Groundwork for creating systems in the _edge-cloud continuum_ with a focus on **dynamicity** and **self-adaptation**.
