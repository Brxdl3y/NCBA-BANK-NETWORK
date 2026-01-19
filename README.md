**NCBA Bank — Enterprise Network** 

🔹I built this lab the way I believe networks should be built in real life: with restraint, intention, and a quiet respect for failure.

Not the loud kind of complexity, the kind of complexity that disappears when everything is working and only shows itself when something breaks.

🔹This is a simulated **NCBA Bank** campus network, but the thinking behind it is real-world, production‑minded, and shaped by how enterprise networks behave under pressure.

📌**Why This Network Exists**

In banking environments, the network is never the product it’s the foundation. If it fails, everything above it collapses.

That mindset shaped every decision here.


📌**The Mental Model**

I don’t see networking as commands on a screen. I see it as controlled chaos.

Links fail. Switches reboot. Someone plugs in something they shouldn’t. Traffic spikes when you least expect it.

A good network absorbs all of that — quietly.

This lab reflects how I think:

-Predictable paths beat clever tricks

-**Redundancy** only matters if it’s intentional

-Security should feel boring — because it’s always there

-Documentation is part of the design, not an afterthought


**Architecture, With Purpose**

The topology follows a classic enterprise hierarchy, not because it’s textbook, but because it works.

📌**Core Layer** 

The core is clean and disciplined.

Dynamic routing with **OSPF**

**Loopback interfaces** for stable identities

MD5 authentication to establish routing trust

Nothing extra. Nothing fragile. Just fast, resilient forwarding.


📌**Distribution Layer**

This is where intelligence lives:

Layer 3 switches performing inter‑VLAN routing via SVIs

HSRP providing uninterrupted default‑gateway availability for every department

Routing and switching meet here — cleanly, deliberately

If one distribution switch disappears, users don’t panic. Traffic reroutes. The network keeps its composure.


**Access Layer**

The access layer is intentionally boring.

VLANs strictly aligned to business functions

STP controlling Layer 2 behavior

Edge ports protected with PortFast and BPDU Guard

End devices connect. They do not influence the topology. Ever.


**Segmentation That Reflects Reality**

Departments are separated not for practice, but for realism:

🔹Customer Service

🔹Finance & Fraud

🔹Human Resources

🔹System Administration

🔹Loans & Savings

🔹Digital Marketing

🔹Telecommunications

This structure reduces broadcast noise, limits failure domains, and mirrors how financial institutions think about internal boundaries.


**Routing That Respects the Network**

OSPF is configured with restraint:

Passive interfaces wherever adjacency isn’t required

Explicit router IDs using loopbacks

Authentication enabled by default

The goal isn’t to show OSPF knowledge — it’s to show routing hygiene.

High Availability That Isn’t Cosmetic

HSRP isn’t just turned on. It’s thought through.

🔹Every VLAN has a resilient default gateway. Roles are defined. Preemption is controlled. Failure scenarios were considered before the first command was typed.

Redundancy here isn’t for show — it’s for continuity.


**Security as a Baseline**

Even in a lab, I refuse to normalize insecurity.

This network includes:

VEncrypted routing authentication

VPassword encryption and device hardening

VSSH‑only remote access

VStorm‑control and edge protections

None of this is exotic. That’s the point.


**What This Lab Actually Demonstrates**

This project isn’t trying to prove that I can configure protocols. It proves that I:

Think in systems, not features

Design with failure in mind

Value clarity over cleverness

Take infrastructure seriously

If you handed me this network in production, I wouldn’t feel nervous. I’d feel oriented.

That’s the standard I’m working toward.

**Final Thought**

I’m pursuing networking because I enjoy building things that don’t demand attention — because they work.


Quietly resilient. Intentionally designed. Ready to grow.


Author - **Bradley Giovanni**

|  Network Engineer   | Network Administrator    |  NOC Engineer


GMAIL - giovanniibradley@gmail.com


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/bradley-giovanniii293)

