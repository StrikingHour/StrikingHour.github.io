---
title: "QSAC: Quantum-assisted Secure Audio Communication using quantum entanglement, audio steganography, and classical encryption"
collection: publications
category: manuscripts
permalink: /publication/2025-08-22-qsac-quantum-audio
excerpt: "This paper proposes QSAC, a novel framework for secure audio communication that integrates quantum key distribution (QKD) using the E91 protocol, classical encryption (ChaCha20-Poly1305), and audio steganography (LSB). The system generates a quantum-secured key, hashes it with SHA-3 for high entropy, hides the secret audio within a cover signal, and then encrypts it. Rigorous experiments demonstrated the method's robustness against classical and quantum attacks, showing high randomness in the encrypted output (avg. entropy ~16) and successfully using the CHSH inequality to detect eavesdroppers."
date: 2025-08-22
venue: 'Published in Engineering Science and Technology.'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2215098625002228'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: '@article{RIFAT2025102167,
title = {QSAC: Quantum-assisted Secure Audio Communication using quantum entanglement, audio steganography, and classical encryption},
journal = {Engineering Science and Technology, an International Journal},
volume = {70},
pages = {102167},
year = {2025},
issn = {2215-0986},
doi = {https://doi.org/10.1016/j.jestch.2025.102167},
url = {https://www.sciencedirect.com/science/article/pii/S2215098625002228},
author = {Md. Raisul Islam Rifat and Md. Mizanur Rahman and Md. Abdul Kader Nayon and Md Shawmoon Azad and M.R.C. Mahdy},
keywords = {Quantum Key Distribution (QKD), E91 protocol, Entanglement, CHSH inequality, Steganography, ChaCha20-Poly1305, Secure Hash Algorithm (SHA)},
}'
---
The emergence of quantum computing poses a significant security threat to the current classical cryptography system since it has the potential to outperform the current classical computer in some specific tasks due to its unique principle of operation. This necessitates finding a method that is resistant to quantum computers to securely transfer information. This research addresses these challenges by proposing a novel method combining quantum key distribution (QKD), specifically the E91 protocol, with the classical encryption-authentication protocol ChaCha20-Poly1305, and concealing information within another message through steganography to securely transfer audio messages. A shared secret key is created between the communicating parties using E91 QKD, which exploits the stellar protection of quantum entanglement against eavesdropping. The shared key is hashed through the SHA–3 hash function to generate a fixed-length, high-entropy symmetric key. The audio message is hidden inside another audio signal through steganography. The steganographic signal is encrypted using ChaCha20-Poly1305 AEAD in order to provide another layer of obfuscation as well as a means to verify integrity. Through rigorous experiments, we validated the robustness of the proposed methodology in both classical and quantum attacks. The processing of secret audio signals of varying duration (00:01:32 to 00:01:36) exhibits consistent encryption results. The encrypted stego audios show high randomness, with an average entropy of 15.9984, an average correlation of 1.4627 × 10<sup>-5</sup>, an average UACI of 49.9977%, and an average NSCR of 99.9985%. We demonstrated the safety of the shared key using the CHSH inequality test, where in the presence of an eavesdropper, the CHSH value is much less than 2 &radic;2. In addition, the integrity of the secret audio is also validated through the verification of the authenticator tag generated during the encryption process. Our research offers a novel framework for secure audio transmission, combining classical encryption and authentication methods with QKD to enhance confidentiality, integrity, and resilience against eavesdropping and tampering, ensuring robust end-to-end security.
