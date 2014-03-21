A New Look at Dual-Hop Relaying
==================

This is a code package is related to the follow scientific article:

Emil Björnson, Michail Matthaiou, Mérouane Debbah, “[A New Look at Dual-Hop Relaying: Performance Limits with Hardware Impairments](http://arxiv.org/pdf/1311.2634),” IEEE Transactions on Communications, vol. 61, no. 11, pp. 4512-4525, November 2013.

The package contains a simulation environment, based on Matlab, that reproduces all the numerical results and figures in the article. *We encourage you to also perform reproducible research!*


##Abstract of Article

Physical transceivers have hardware impairments that create distortions which degrade the performance of communication systems. The vast majority of technical contributions in the area of relaying neglect hardware impairments and, thus, assumes ideal hardware. Such approximations make sense in low-rate systems, but can lead to very misleading results when analyzing future high-rate systems. This paper quantifies the impact of hardware impairments on dual-hop relaying, for both amplify-and-forward and decode-and-forward protocols. The outage probability (OP) in these practical scenarios is a function of the effective end-to-end signal-to-noise-and-distortion ratio (SNDR). This paper derives new closed-form expressions for the exact and asymptotic OPs, accounting for hardware impairments at the source, relay, and destination. A similar analysis for the ergodic capacity is also pursued, resulting in new upper bounds. We assume that both hops are subject to independent but non-identically distributed Nakagami-m fading. This paper validates that the performance loss is small at low rates, but otherwise can be very substantial. In particular, it is proved that for high signal-to-noise ratio (SNR), the end-to-end SNDR converges to a deterministic constant, coined the SNDR ceiling, which is inversely proportional to the level of impairments. This stands in contrast to the ideal hardware case in which the end-to-end SNDR grows without bound in the high-SNR regime. Finally, we provide fundamental design guidelines for selecting hardware that satisfies the requirements of a practical relaying system.


##Content of Code Package

The article contains 7 simulation figures, numbered from 2 to 8. These are generated by the Matlab scripts simulationFigure2and3.m, simulationFigure4.m, ..., simulationFigure8.m. The package contains an additional Matlab function, functionOutageFormula.m, which is called by the other scripts.

See each file for further documentation. 


##Acknowledgements

E. Björnson is funded by the International Postdoc Grant 2012-228 from The Swedish Research Council. This research has been supported by the ERC Starting Grant 305123 MORE (Advanced Mathematical Tools for Complex Network Engineering). The work of M. Matthaiou has been supported in part by the Swedish Governmental Agency for Innovation Systems (VINNOVA) within the VINN Excellence Center Chase.


##License and Referencing

This code package is licensed under the GPLv2 license. If you in any way use this code for research that results in publications, please cite our original article listed above.