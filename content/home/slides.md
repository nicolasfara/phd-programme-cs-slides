+++
weight = 1
+++

# Context

{{% shrink %}}

- Modern **CPS** are characterized by a _high heterogeneity_ in terms of devices, communication technologies, and infrastructure
- The _edge-cloud continuum_ is a promising solution to address the _scalability_ and _dynamicity_
- Complexity of the system is increasing, and the _engineering_ of such systems is becoming a challenge
- Many approaches are proposed in the literature: **pulverisation** is one of them in the context of _Collective Adaptive Systems_

{{% /shrink %}}

---

# State of the Art

<!-- Many different _approches_ are proposed in the literature to tackle the complexity of **cloud-edge** systems. -->

{{% multicol %}}

{{< col >}}
<h3>Collective Adaptive Systems</h3>

- Several entities that _interact_ with each other to achieve a _common goal_
- _Coordination_[^1] as an effective way to achieve global goal in a distributed system
    - **Message passing**[^11]
    - **Tuple space models**[^2]
    - **Stigmergy models**[^3]
- _Aggregate Computing_[^4] paradigm as an approach to _engineer_ Collective Adaptive Systems (frameworks like _ScaFi_[^5] and _Protelis_[^6])
{{< /col >}}

{{< col >}}
<h3>Edge-Cloud continuum</h3>

- _Osmotic Computing_[^7] approach focused on microservices architectures which aims to maintain an osmotic equilibrium
- _Multi-tier programming_[^8] as a way to write application that span across multiple tiers into a single compilation unit
- _Component-based_[^9] a way to decompose the system into _components_ that can be independently deployed and reconfigured
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
[^11]: [Kohei Honda et al. "Multiparty Asynchronous Session Types"](https://doi.org/10.1145/2827695)

---

# Project description

---

# Extends the Pulverisation approach

<!-- **Pulverisation** approach for engineering collective systems by neatly separate the _business logic_ from _deployment aspects_.   -->
<!-- **Pulverization**: a (logical) _device_ is decomposed into **five** components that can be _independently_ deployed in the infrastructure. -->

{{% multicol %}}

{{% col %}}

<!-- Extensions meant to be pursued in the project: -->

### Rule-based reconfiguration

- Define reconfiguration rules that can _move_ components into different infrastructure nodes.
- Suitable for a priori defined rules based on _well-known patterns_ and _specific conditions_.

### AI-based reconfiguration

- _Dynamic reconfiguration_ based on _AI_ techniques (e.g., _reinforcement learning_).
- _Distributed intelligence_ from two differen perspective: **Application** and **Infrastructural**
- Suitable for scenarios where the context is _dynamic_ and _unpredictable_ but **QoS** metrics are known

{{% /col %}}

{{% col class="center-content" %}}

{{< figure src="images/pulverization-model.svg" width="70%" >}}

{{% multicol %}}
{{% col class="center-content" %}}
{{< figure src="images/cloud.svg" width="60%" caption="<b>Edge-cloud</b> deployment" >}}
{{% /col %}}
{{% col class="center-content" %}}
{{< figure src="images/peer-to-peer.svg" width="63%" caption="<b>Peer-to-peer</b> deployment" >}}
{{% /col %}}
{{% /multicol %}}

{{% /col %}}

{{% /multicol %}}

**Dynamic reconfiguration** is a key aspect for _energy efficiency_, _carbon footprint_ reduction, and _QoS_ improvement.

---

# Bridge the gap between simulation and real world

{{% multicol %}}
{{% col %}}

- Prototype a framework supporting the _pulverisation_ approach
- Integration of the framework with _simulators_ to allow to simulate the system before its deployment
- Provide a _methodology_ and _techniques_ for a full-stack solution to engineer CAS effectively

In many applicative scenarios like _smart cities_, _ambient intelligence_, _building automation_ and so on,
the unpredictable nature of the environment makes it difficult to _predict_ the behavior of the system.

<!-- For this reason, having a full-stack solution that enable to _simulate_ the system before its deployment could be strategic. -->

{{% /col %}}

{{% col class="center-content" %}}
{{< figure src="images/phd-proposal.drawio.png" width="80%" >}}
{{% /col %}}
{{% /multicol %}}

---

# Engineering data stream on the continuum

{{% multicol %}}

{{% col %}}
- _IoT_ devices generate a huge amount of **data** from many different sources
- The _efficient_ and _effective_ management of data streams is an open issue, especially in _edge-cloud_ environments
- Engineer the _data stream_ on the continuum to provide more effective control of distributed actuators, and also improved cloud-edge data storage/analysis
{{% /col %}}

{{% col class="center-content" %}}

{{< figure src="images/data-stream.drawio.png" >}}

{{% /col %}}
{{% /multicol %}}

---

# Expected results

{{% shrink %}}

- Design and prototype a **framework** for the pulverisation approach to be _modular_, _extensible_ and support different targets
- Extends the pulverization approach to support **dynamic reconfiguration** of the system, then implement it in the framework
- Extends the _reconfiguration_ model to support **AI-based** reconfiguration at runtime to adapt to dynamic changing scenarios
- Integrate the framework with **AC frameworks** like _ScaFi_ and _Protelis_ to provide a full-stack solution for CAS engineering
- **Data stream engineering** on the continuum to support the computation of actuators from sensors stream on the framework

{{% /shrink %}}

---

# Long term contribution

{{% shrink %}}

- Provide new _approaches_ and _solutions_ to challenges in the research community (focus on CAS)
- Understand the role of **CAS** in modern scenarios like _smart cities_ and _large-scale IoT systems_
- Provide reference implementations of the proposed approaches
- Groundwork for creating systems in the _edge-cloud continuum_ with a focus on **dynamicity** and **self-adaptation**.

{{% /shrink %}}
