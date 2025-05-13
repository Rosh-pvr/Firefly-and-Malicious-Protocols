# Firefly-and-Malicious-Protocols

You will find comparisons between DL, SEIR-F, and EFF-FAODV Protocols

# EXPLANATION

# 1. DL
Full Form: Deep Learning
Explanation:

    A subset of machine learning that uses neural networks to detect malware or optimize routing in WSNs.

    In the study, DL is used as a baseline method for malware detection but suffers from high computational overhead and lower efficiency compared to EFF-FAODV.

# 2. SEIR-F
Full Form: Susceptible-Exposed-Infectious-Recovered with Failure (SEIR-F) Model
Explanation:

An epidemiological model adapted for WSNs to simulate malware propagation.

            S (Susceptible): Nodes vulnerable to malware.

            E (Exposed): Infected but not yet spreading malware.

            I (Infectious): Actively spreading malware.

            R (Recovered): Nodes that have removed malware.

            F (Failed): Nodes dead due to malware/energy drain.

Used in your study to model malware dynamics but lacks real-time optimization.

# 3. EFF-FAODV
Full Form: Enhanced Firefly-Fault-Tolerant Ad-hoc On-Demand Distance Vector (EFF-FAODV)
Explanation:

EFF (Enhanced Firefly Algorithm):

Optimizes Cluster Head (CH) selection using bio-inspired firefly behavior.

Maximizes energy efficiency and minimizes delay via fitness functions (Eq. 9–10 in the manuscript).

# FAODV (Fault-Tolerant AODV):

An improved AODV routing protocol with fault tolerance.

Detects malware nodes (S/I/E states) and switches to backup paths (Algorithm 2 in the study).

Combined Benefit: Achieves 91% efficiency (highest PDR, lowest energy use) in IoT-WSNs.

# Key Differences
          Metric	DL	SEIR-F	EFF-FAODV
          Approach	Deep Learning	Epidemiological Model	Bio-inspired + Fault-Tolerant Routing
          Strengths	Pattern recognition	Malware modeling	Energy efficiency, real-time adaptation
          Weaknesses	High latency	Reactive detection	Slightly complex implementation
          Performance	Lowest PDR (45–65%)	Moderate (55–75%)	Best (75–92%)
