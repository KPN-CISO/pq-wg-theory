# Post-quantum Wireguard (Theory)

PQ-WireGuard is a project initiated by KPN CISO, and a joint work with
Prof. [Peter Schwabe](https://cryptojedi.org/peter/index.shtml) from [Radboud
Universiteit](https://www.ru.nl/english/), and Prof. [Andreas
Hülsing](https://huelsing.net/) and [Florian Weber](https://florianjw.de/) from
[Technische Universiteit Eindhoven](https://www.tue.nl/en/).

The purpose of the project is to create a highly performant and fully
quantum-resistant VPN software, i.e. provides both confidentiality and
authenticity against attackers with sufficiently powerful quantum computers.
The final instantiation of the protocol achieves NIST security level 3
(AES-192-equivalent).

The project consists of four aspects:
1. A new VPN protocol
2. Security proofs (both symbolic and computational)
3. An implementation as a Linux kernel module
4. Performance comparison with other VPN software

This repository hosts the academic paper (2021 IEEE Symposium on Security and
Privacy, to appear) that describes the protocol, its security analysis, and
its performance comparison, as well as the
[Tamarin](https://tamarin-prover.github.io/) model for its symbolic proof.

# Contact
Kai-Chun Ning (kaichun.ning@kpn.com)
