<!-- ========= Abstract ========= -->
\pagenumbering{Roman}
\thispagestyle{empty}
\quad\vspace{1in}\quad 
\abstract{
\qquad
\begin{center}
\begin{minipage}{0.8\textwidth}
\setlength{\parskip}{0.5em}% restore the value

Today's trend of migrating radio devices from hardware to software provides 
potential to create flexible applications for both commercial and military use. 
However, this raises security concerns, as malicious attackers can also be 
generated easily to break legitimate communications. In this research work, our goal is 
to design a robust anti-jamming radio framework. We 
particularly investigate three different aspects of jamming threats: high-power 
jammers, link attacks on rate adaptation, and jamming in 
multicarrier systems.

The threats of high-power jamming to wireless communications today are 
realistic due to the ease of access to powerful jamming sources such as the 
availability of commercial GPS/WiFi/cellular devices on the market, or RF guns 
built from microwave ovens' magnetron. To counter high-power jamming attacks, 
we develop \jamcancel which is a hybrid system capable of resisting jammers of 
up to 100,000 times higher power than legitimate communication nodes. The 
system robustness relies on our own antenna structure specially designed for 
anti-jamming purpose. We develop an efficient algorithm for auto-configuring 
the antenna adaptively to dynamic environments. We also devise a software-based 
jamming cancellation technique for appropriately extracting original signals, 
which is more robust than traditional MIMO approaches, as pilot signals are not 
required in \jamcancel.

In spite of the robustness of \jamcancel, our design is more appropriate for malicious environments with powerful jammers, where mechanical steering is feasible, e.g., military applications. Residential and commercial wireless communication systems are still vulnerable to even limited-power jamming, as in today's standard wireless protocols, rate information is 
exposed 
to adversaries. Rate-based attacks have been demonstrated to severely degrade 
the networks at very low cost. To mitigate rate-based attacks, we 
develop \ratehiding, 
a system capable of hiding rate and -- at the same time -- increasing 
resiliency against jammers up to seven times higher than regular systems, where 
rate is exposed. We achieve the resiliency boost by generalizing Trellis Coded Modulation to allow non-uniform codeword mapping. We develop an efficient 
algorithm for finding good non-uniform codes for all modulations in \{BPSK, QPSK, 8-PSK, 16-QAM, 64-QAM\}. To conceal rate information, we devise an 
efficient method for generating cryptographic interleaving functions.

In recently deployed communication networks such as WiFi and LTE systems, MIMO and OFDM are the two main techniques for increasing bandwidth 
efficiency. While MIMO increases the channel capacity by spatial processing on multiple received signals, OFDM mitigates impacts of dynamic variations in wide-band channels and allows frequency reuse with overlapping carriers.
Synchronization is a key for high-throughput performance in MIMO and OFDM systems. In this work, we study impacts of jamming attacks 
specifically targeting to control channels in WiFi and LTE 
networks. Our study focuses on efficient techniques for both jamming and 
anti-jamming in multicarrier systems.

Research work in this proposal is developed based on our own radio system 
which is a multicarrier framework with adaptive sensing and support of a 
large set of modulation and coding schemes. Our base system achieved the 
Winning award of Cooperative Tournament and Third prize of Competitive 
Tournament in Preliminary Round of DARPA Spectrum Challenge 2013.
\end{minipage}
\end{center}}

\newpage
