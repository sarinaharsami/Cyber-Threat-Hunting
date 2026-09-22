# Chapter 01: Introducing Threat Hunting

## 1. Chapter Overview

This chapter introduces threat hunting as a proactive, human-driven security practice focused on identifying threats that may have evaded existing detection mechanisms. It explains the role of hypotheses, evidence, and structured hunting processes in uncovering suspicious activity and improving an organization's security posture.


## 2. Key Concepts

### 2.1 Threat Hunting

* Definition: A proactive, human-driven process of searching for threats that have not been detected by existing security controls.

* Proactive vs. Reactive Security: Reactive security responds to known or detected incidents, while threat hunting actively searches for potential threats before they are confirmed.

* Threat Hunting Objectives:

  * Identify threats missed by existing detection mechanisms.

  * Reduce attacker dwell time.

  * Discover suspicious behaviors and previously unknown attack activity.

  * Improve detection capabilities and support incident response.

### 2.2 Threat Hunting Hypothesis

A hypothesis is a testable assumption that guides the hunting process.

* Hypotheses may be based on threat intelligence, attacker TTPs, environmental knowledge, or previous incidents.

* A hypothesis provides direction and focus for the hunt.

* Hunters collect and analyze evidence to validate or disprove the hypothesis.

* A hunt may result in a confirmed finding, a disproven hypothesis, or an inconclusive outcome.

### 2.3 Threat Hunting Process

A structured hunt typically follows these activities:

1. Develop a hypothesis.

2. Search available telemetry for supporting or contradicting evidence.

3. Optimize queries and pivot based on findings.

4. Expand the investigation to related activities, systems, or behaviors.

5. Document the outcome and identify follow-up actions.

### 2.4 Threat Hunting Outcomes

* Confirmed: Evidence supports the hypothesis and may require incident response.

* Disproved: Evidence does not support the hypothesis.

* Inconclusive: Available evidence is insufficient to reach a conclusion.

A hunt can still provide value even when no threat is confirmed.

## 3. Important Notes

|Concept|Description|
| --- | --- |
|Threat Hunting|Proactive, human-driven search for threats that evade detection|
|Hypothesis|A testable assumption that guides hunting|
|Telemetry|Data collected from systems and security sources|
|Dwell Time|Time an attacker remains in an environment before detection or containment|
|Pivoting|Using a finding to guide further searches|
|Evidence|Data used to support or disprove a hypothesis|
|Hunting Play|A structured procedure for conducting a hunt|
|Detection vs. Hunting|Detection identifies activity using established mechanisms; hunting actively investigates potential threats|
|Hunt Outcome|A hypothesis may be confirmed, disproved, or inconclusive|

## 4. My Takeaways

* Threat hunting is not random searching; it is a hypothesis-driven and evidence-based process.

* The absence of an alert does not mean the absence of a threat.

* A disproven hypothesis or inconclusive hunt is not necessarily a failed hunt.

* Hunting findings can lead to incident response, improved detection rules, and better threat intelligence.

* In real-world hunting, I can use EDR telemetry to investigate suspicious behaviors, correlate related events, and pivot from initial findings to uncover activity that existing alerts may have missed.

