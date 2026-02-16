#  How Quantum Computing Will Revolutionize Cybersecurity and Encryption

Written by Uzair Khan, B.S. Cybersecurity, minor in Computer Science







## I. Introduction

Quantum computing is a revolutionary frontier technology that uses the principles of quantum mechanics to perform computations that current computers cannot compute. In cybersecurity, encryption plays a key role by mathematically mixing data using various functions and discrete logarithms. Encryption at a fundamental level relies on problems that are easy to compute one way but incredibly difficult to reverse engineer by current computers. This means that when quantum computers become powerful enough, they will be able to break widely used public-key methods such as RSA using an algorithm known as Shor's algorithm. This will expose our previously secure data and communications (MIT Technology Review). In this analysis, I will describe quantum computing and its key features, discuss the key cybersecurity challenges it presents, detail potential solutions and countermeasures, and project future scenarios regarding the cybersecurity landscape in a quantum computing era.







## II. Quantum Computing

Quantum computing is exponentially more powerful than modern or classical computers for certain types of problems. The article published by MIT Technology Review explains two concepts responsible for this disparity: superposition and entanglement. Superposition is a quantum computing concept in which a qubit, a unit of quantum computing comparable to a binary, can exist as both a 0 and a 1 simultaneously, which allows it to process many more outcomes. Entanglement is a concept in quantum computing in which two or more qubits become linked so that the state of one qubit instantly affects the state of the other qubit, even if they are physically far apart. This allows quantum computers to work in ways faster and more powerful than classical computers (MIT Technology Review).



Quantum computing works by doing calculations using qubits and entanglement to run algorithms like Shor's that break mathematical functions. It applies quantum algorithms to efficiently compute large numbers and discrete logarithms, which classical computers cannot do.



In the media, quantum computing is hidden behind more mainstream technological evolutions like artificial intelligence (AI), robotics, internet of things (IoT), and virtual reality/augmented reality (VR/AR). Globally, countries are engaging in a lesser-known race by investing in quantum computing. Countries like China, Europe, South Korea, and the United Kingdom are all building multi-city quantum networks using quantum key distribution (QKD), a method in quantum cryptography, and other quantum technologies (Conover, Science News).



In the United States, the U.S. Department of Energy (DOE), Defense Advanced Research Projects Agency (DARPA, and National Science Foundation (NSF) are investing in quantum research regarding quantum algorithms, simulations, and networking (Palo Alto Networks). Multiple U.S. agencies are realizing the importance and urgency of transitioning to quantum-resistant cryptography reflective of federal mandates to prepare for the post-quantum era.



Locally, Argonne National Laboratory and Fermilab are investing in quantum networks, quantum algorithms, quantum simulations, and overall quantum computing. These local DOE laboratories participate in the Chicago Quantum Exchange, an intellectual hub that connects top universities, national labs, and partners to advance quantum information science, a newer genre of information science. Other organizations are also investing in quantum computing locally, such as IBM, which is creating a new quantum computer in the Chicago South Side. The University of Chicago is partnering with IonQ to install a quantum computer near its research facilities to improve its quantum ecosystem.



## III. Cybersecurity Challenges

### Breaking Public-Key Encryption:



Shor's algorithm allows quantum computers to crack 2048-bit RSA encryptions in hours if there were around 20 million qubits available (MIT Technology Review). Powerful quantum computers are able to break RSA and discrete-logarithm-based encryption. RSA encryption relies on very large prime numbers multiplied together. In this encryption, the public key is the product of two primes, and the private key is the original primes. Classical computers cannot factor extremely large numbers like 2048-bit RSA keys. Even the fastest supercomputers in the world would take millions of years to break one 2048-bit RSA key compared to the hours that quantum computers would need.



### Harvest Now, Decrypt Later Attacks: 



Attackers can collect encrypted data today and decrypt it later once quantum computers reach certain performance metrics. The data that is most at-risk is sensitive government, military, medical, and infrastructure data (Palo Alto Networks).



### Compromised Digital Signatures and Blockchain Integrity:



Digital signatures rely on encryption algorithms like RSA, which would become vulnerable when quantum computers can run Shor's algorithm. In a broader cryptography scale, quantum computers also threaten blockchain technology, as quantum computers can also crack SHA-256 and other hashes used for cryptography.



### Weakened Communication Protocols:



Several communication protocols, such as transport layer security (TLS), secure sockets layer (SSL), virtual private networks (VPNs), and secure email, rely on public-key cryptography, which will become breakable when quantum computers reach a certain performance capability. 



### Threatened Infrastructure:



Critical infrastructure, such as power grids and medical systems, relies on cryptographic authentication, which is susceptible to compromise by quantum computers (Palo Alto Networks). This is a key reason why many U.S. DOE research labs are investing in quantum computing to get ahead of the curve. If these critical systems become compromised or fail, the effects would be incredibly dangerous and far-reaching, involving millions nationwide and billions globally. Internet of Things (IoT) devices also depend on public-key authentication, which means several internet-connected devices, such as smartwatches, smart TVs, home assistants, smart bulbs, camera systems, baby monitors, vehicles, and other IoT devices, are at risk.



### Geopolitical Imbalances:



Like AI and robotics, nations that reach quantum computing for decryption first will gain power and cybersecurity intelligence over others, which would destabilize the global power dynamics. AI, robotics, and quantum computing are all similar to the race for the atomic bomb or the race to the moon.



## IV. Solutions and Countermeasures

### **Quantum-readiness roadmaps and inventory:** 

Organizations should begin to formally migrate to a post-quantum era by identifying and replacing vulnerable cryptography, researching breakthroughs in quantum computing, and partnering with nearby quantum research laboratories. Organizations should create a full inventory of algorithms, protocols, and other cryptographic metrics that RSA uses to improve its security awareness.

### **Elastic Cryptographic Approach:** 

Organizations should design their systems to be able to change algorithms quickly according to the National Institute of Standards and Technology (NIST) post-quantum standards. They should also adopt a hybrid approach similar to hybrid cloud computing in which they can combine classical and post-quantum computing (PQC) systems to preserve their security posture. NIST has created quantum-resistant algorithms that can resist both classical and quantum attacks. Organizations should research ways to include these more resistant algorithms.

### **Quantum-Resistant Key Exchange Strategies:** 

To prepare for Q-day, the point at which quantum computers become powerful enough to break current cryptography standards, organizations can implement a concept called Quantum Key Distribution (QKD). QKD uses physics principles to secure communications. It uses a no-cloning theorem to ensure that any attempt at eavesdropping can be detected right away. This provides a secure method for exchanging cryptographic keys. By integrating QKD into existing networks and systems, organizations can create a multi-layered defense against the cybersecurity threats posed by quantum computers (Science News).

## V. Conclusion

In conclusion, quantum computing introduces critical risks to modern cryptography by mathematically exceeding all classical computers and even supercomputers. It is important for organizations to improve their cybersecurity posture by creating quantum-readiness roadmaps, adopting an elastic cryptographic approach, and applying quantum-resistant key exchange strategies.



In the future, large-scale quantum networks could create a global quantum internet that can accomplish exponentially faster speeds than current limits. Global intelligence, defense, and relations will become reshaped by a nation's quantum capabilities. Quantum technology will enable longer distances and more secure communications, creating an even more digitally connected world.



Quantum computing will revolutionize technology and force us to adapt to its unprecedented capabilities. It will require us to redesign our entire cybersecurity approach, especially with encryption. Quantum computing is incredibly powerful and is coming. As security professionals, it is our job to be prepared for Q-day when it arrives. By taking a proactive approach and conducting comprehensive research, we will be better prepared to use Quantum Computing to enhance cybersecurity. 







## Works Cited

“8 Quantum Computing Cybersecurity Risks \[+ Protection Tips].” Palo Alto Networks, www.paloaltonetworks.com/cyberpedia/what-is-quantum-computings-threat-to-cybersecurity. Accessed 16 Nov. 2025.



Conover, Emily. “How to Stop Quantum Computers from Breaking the Internet’s Encryption.” Science News, 23 Sept. 2024, www.sciencenews.org/article/quantum-computers-break-internet-save.



How a Quantum Computer Could Break 2048-Bit RSA Encryption in 8 Hours, MIT Technology Review, 22 Aug. 2024, www.technologyreview.com/2019/05/30/65724/how-a-quantum-computer-could-break-2048-bit-rsa-encryption-in-8-hours/.



Quantum Computing | Argonne National Laboratory, U.S. Department of Energy, www.anl.gov/mcs/quantum-computing. Accessed 17 Nov. 2025. 



