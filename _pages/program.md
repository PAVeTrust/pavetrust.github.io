---
title: "Program"
permalink: /program/
---

* **9:00-9:05** Welcome and opening remarks by PAVeTrust organisers

* **9:05-10:00** Invited talk 1: **Remote Attestation and Formal Methods - the bigger picture** by **Ian Oliver** (University of Oulu, Finland)
  * Abstract: Remote Attestation, its concepts, protocols, services etc do not exist alone as individual entities - everything exists as part of a larger infrastructure or system. This places some very interesting demands on how we think about and construct specifications and proofs of these components. Much has been talked about composability of specifications, but it is relatively rare that these composable specifications are actually composed and put into the context of a system. Further, even if these specifications do sit alone, then their implications must be taken into consideration properly for any part of the system that has to integrate with that component.
    In this talk we will present our experiences of developing an attestation engine, its place in some wider architectures, eg: medical, 5G, 6G etc,  how it interacts and abstracts with attestation protocols, and finally emphasize the role of formal specification in larger systems and the implication to a "complete" attestation solution.
* **10:00-10:30** Paper 1: **Towards Comprehensive Formal Specification of Attestation Frameworks for Confidential Computing** by Muhammad Usama Sardar, Thomas Fossati, Hannes Tschofenig and Simon Frost
  * Abstract: Confidential computing has recently garnered significant industry attention, and it is increasingly used in artificial intelligence (AI) applications to make critical decisions. To evaluate the trustworthiness of such AI systems' decisions, formal methods can play a crucial role. However, existing works focus on the formal verification of either network protocols or system architecture. In this paper, we propose a systematic approach for holistic specification of both by considering the strong interlink between them. We show the application of our approach to a popular production-grade solution, namely SCONE. Specifically, we highlight the challenges in the formal specification of such complex systems and provide a list of missing specifications that are critical for a formal analysis. Even without complete specifications, we not only invalidate some of the security claims of SCONE but also discover design and security flaws.

* **10:30-11:00** Coffee Break

* **11:00-12:00** Invited talk 2: **Beyond the Surface: Validation Challenges and Opportunities for Confidential Computing** by **Jo Van Bulck** (KU Leuven, Belgium)
  * Abstract: Confidential Computing is an emerging paradigm that is rapidly transforming the computing landscape, ranging from mainstream cloud infrastructures to low-end IoT devices. By creating isolated "enclaves" where code and data remain secure, even during CPU processing, these architectures offer robust protection against powerful, root-level adversaries. However, Confidential Computing cannot protect against vulnerabilities within the enclave software or the underlying CPU hardware.
    This talk overviews our efforts on developing validation strategies for enclave software and side-channel resistant hardware. We will outline pitfalls for formal-verification approaches and introduce a symbolic-execution framework aimed at enabling principled validation of enclave software on both low-end and high-end devices.

* **12:00-12:20** Extended abstract 1: **Exceptions Prove the Rule: Investigating and Resolving Residual Side Channels in Provably Secure Interrupt Handling** by Matteo Busi, Pierpaolo Degano, Riccardo Focardi, Letterio Galletta, Flaminia Luccio, Frank Piessens and Jo Van Bulck
  * Abstract: The ongoing surge in side-channel attacks on trusted execution environments has prompted the application of formal methods to eliminate these
vulnerabilities definitively. Recently, research has focused on mitigating interrupt-driven side channels on small microcontrollers, resulting in a
provably secure mechanism to maintain enclave isolation in the presence of arbitrary timer interrupts.
This paper uncovers a subtle flaw in the formal model’s handling of illegal memory-access exceptions, showing how this oversight can compromise contextual equivalence through a strategic combination of interrupts and exceptions. We propose a minimal adjustment to rectify the model and reinstate formal assurances. Our study underscores the importance of precisely modeling interrupts and exceptions, drawing remarkable parallels with controlled-channel and single-stepping attacks on higher-end processors.

* **12:20-14:00** Lunch Break

* **14:00-15:00** Invited talk 3: TBA by **Hannes Tschofenig** (University of Applied Sciences Bonn-Rhein-Sieg/Siemens, Germany)
* **15:00-15:20** Extended abstract 2: **Build the next-generation bridge with on- and off-chain synergy** by Qian Ren

* **15:20-16:00** Coffee Break

* **16:00-17:00** Invited talk 4: **Formal verification of the Realm Management Monitor (RMM)** by **Eleni Vafeiadi Bila** (Arm)
  * Abstract: The Realm Management Monitor (RMM) is an important (security-critical) software component of Arm Confidential Computing Architecture (Arm CCA); a technology comprising a reference software architecture and an architectural extension for the Armv9-A profile. We have been actively engaged in the formal verification of the RMM specification and its implementation. A key component of this verification effort is a formalization of the RMM specification using the HOL4 interactive theorem prover.
The HOL4 specification comprises approximately 4000 lines of definitions that mirror the published RMM specification. The theorem prover facilitates exploring and validating the correctness of RMM flows, as well as verifying that the specification preserves important invariant properties and confidentiality/integrity guarantees.
In this talk, we will present the methodology adopted for formalizing the RMM specification within the HOL4 theorem prover and provide an overview of the aspects of the RMM that have been verified. Additionally, we will shed light on the recent additions to the RMM specification and their impact on the verification work. Finally, we will address the challenges we have encountered in maintaining the verification and keeping it up to date.
* **17:00-17:30** Wrap-up discussion and concluding remarks
