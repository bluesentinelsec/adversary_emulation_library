# CTID Adversary Emulation Library

[TODO: Add a link to the announcement blog post]

## Philosophy 

In collaboration with Center Participants, the MITRE Engenuity Center for Threat-Informed Defense (CTID) has developed these adversary emulation plans to document and distribute red team resources that are based on known-adversary behaviors. This approach empowers defenders to operationalize cyber threat intelligence to better understand and combat real-world adversaries. Rather than focusing on static signatures, these intelligence-driven emulation plans provide a repeatable means to test and tune defensive capabilities and products against the evolving TTPs of threat actors and malware.

## Adversary Emulation Background

Adversary emulation enables organizations to view their security through the eyes of a cyber adversary with the goal of improving defenses across the adversary’s lifecycle. As defenders this expands our attention and focus beyond just the final actions of the adversary achieving their operational objective to rather understand and appreciate every distinct behavior (that could have been detected and/or mitigated) leading up to that point.

Each emulation plan is rooted in intelligence reports and other artifacts that capture and describe breaches and campaigns publicly attributed to a specific named threat actor. To develop each plan, we research and model each threat actor, focusing not only on what they do (ex: gather credentials from victims) but also how (using what specific tools/utilities/commands?) and when (during what stage of a breach?). We then develop emulation content that mimics the underlying behaviors utilized by the threat actor (i.e. not an exact representation, rather capturing the pertinent elements that accurately generate appropriate test telemetry for defenders). This approach results in nuanced emulation plans, each capturing unique scenarios and perspectives that we can leverage as threat-informed defenders. 

## Getting Started

Each emulation plan focuses on a specific named threat actor. The README of each individual plan provides a curated summary of available cyber threat intelligence, composed of an intelligence overview of the actor (describing who they target, how, and why where possible) as well as the scope of their activity (i.e. breadth of techniques and malware used). All presented information is cited back to relevant publicly available cyber threat intelligence and communicated and annotated via [ATT&CK](https://attack.mitre.org/).

Within each emulation plan, the operational flow provides a high-level summary of the captured scenario(s). These scenarios will vary based on the adversary and available intelligence, but typically follow a sequential progression of how the actor breaches then works towards achieving their operational objectives within a victim environment (espionage, data/system destruction, etc.). 

The content to execute the scenario(s) is broken down into step-by-step procedures provided in both human and machine-readable formats. Scenarios can be executed end-to-end or as individual tests. The human-readable formats provide additional relevant background where possible as well as any setup prerequisites, while the machine-readable format is designed to be parsed by an automated agent (ex: [CALDERA](https://github.com/mitre/caldera), though both forms of content can similarly be parsed and run by other C2 and/or breach simulation frameworks). Please see the emulation plan data dictionary for a more detailed breakdown of the fields of the machine-readable format.

## Questions and Feedback

Please submit issues for any technical questions/concerns, or contact ctid@mitre-engenuity.org directly for more general inquiries.


## Liability / Responsible Usage

This content is only to be used with appropriate prior, explicit authorization for the purposes of assessing security posture and/or research.

## Notice

Copyright 2020 MITRE Engenuity. Approved for public release.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

This project makes use of ATT&CK®

[ATT&CK Terms of Use](https://attack.mitre.org/resources/terms-of-use/)
