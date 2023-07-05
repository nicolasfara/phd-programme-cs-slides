+++
weight = 1
+++

# Context

- Modern **CPS** are characterized by a _high heterogeneity_ in terms of devices, communication technologies, and infrastructure
- The _edge-cloud continuum_ is a promising solution to address the _scalability_ and _dynamicity_
- Complexity of the system is increasing, and the _engineering_ of such systems is becoming a challenge
- Many approaches are proposed in the literature: **pulverisation** is one of them in the context of _Collective Adaptive Systems_

---

# State of the Art

<!-- Many different _approches_ are proposed in the literature to tackle the complexity of **cloud-edge** systems. -->

{{% multicol %}}

{{< col >}}
<h3>Collective Adaptive Systems</h3>

- Several entities that _interact_ with each other to achieve a _common goal_
- _Coordination_[^1] as an effective way to achieve global goal in a distributed system
    - **Message passing** 
    - **Tuple space models**[^2]
    - **Stigmergy models**[^3]
- _Aggregate Computing_[^4] paradigm as an approach to _engineer_ Collective Adaptive Systems (frameworks like _ScaFi_[^5] and _Protelis_[^6])
{{< /col >}}

{{< col >}}
<h3>Edge-Cloud continuum</h3>

- _Osmotic Computing_[^7] general approach main focused on microservices architectures which aims to maintain an osmotic equilibrium
- _Multi-tier programming_[^8] as a way to write application that span across multiple tiers into a single compilation unit
- _Component-based_[^9] distributed software as a way to decompose the system into _components_ that can be independently deployed and reconfigured
- _Pulverization_[^10] as an approach to neatly separate the _business logic_ from _deployment aspects_ by decomposing a (logical) _device_ into **five** components

{{< /col >}}

{{% /multicol %}}

[^1]: [Paolo Ciancarini. "Coordination Models and Languages as Software Integrators"](https://doi.org/10.1145/234528.234732)
[^2]: [Davide Rossi, Giacomo Cabri, and Enrico Denti. "Tuple-based Technologies for Coordination"]()
[^3]: [Francis Heylighen. "Stigmergy as a universal coordination mechanism: Definition and components"](https://doi.org/10.1016/j.cogsys.2015.12.002)
[^4]: [Jacob Beal, Danilo Pianini, and Mirko Viroli. "Aggregate Programming for the Internet of Things"](https://doi.org/10.1109/MC.2015.261)
[^5]: [Roberto Casadei et al. "ScaFi: A Scala DSL and Toolkit for Aggregate Programming"](https://doi.org/10.1016/j.softx.2022.101248)
[^6]: [Danilo Pianini, Mirko Viroli, and Jacob Beal. "Protelis: practical aggregate programming"](https://doi.org/10.1145/2695664.2695913)
[^7]: [Benazir Neha et al. "A Systematic Review on Osmotic Computing"](https://doi.org/10.1145/3488247)
[^8]: [Pascal Weisenburger, Johannes Wirth, and Guido Salvaneschi. "A Survey of Multitier Programming"](https://doi.org/10.1145/3397495)
[^9]: [Hélène Coullon et al. "Component-Based Distributed Software Reconfiguration: A Verification-Oriented Survey"](https://doi.org/10.1145/3595376)
[^10]: [Roberto Casadei et al. "Pulverization in Cyber-Physical Systems: Engineering the Self-Organizing Logic Separated from Deployment"](https://doi.org/10.3390/fi12110203)

---

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

# Bridge the gap between simulation and real world

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

# Engineering data stream on the continuum

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
