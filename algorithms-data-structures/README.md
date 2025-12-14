# Algorithms and Data Structures Enhancement

## Artifact Overview
The artifact selected for the algorithms and data structures category is the **Artemis Financial Security Enhancement Project**, originally developed in CS305. This project focused on identifying security vulnerabilities in a financial web application and applying cryptographic solutions to protect sensitive data. The initial version implemented AES encryption and a basic SHA-256 checksum, which met assignment requirements but did not reflect how encryption and key management are handled in production systems.

For this enhancement, the project was expanded into a more realistic and secure encryption framework that better represents industry practices.

## Why This Artifact Was Selected
This artifact demonstrates my ability to apply algorithmic thinking to real-world security challenges. The enhancement allowed me to work with advanced cryptographic algorithms, key management strategies, and data integrity verification techniques. I chose this project because it highlights how data structures and algorithms directly impact system security, performance, and reliability.

The most significant improvement was the implementation of a **hybrid encryption model**. RSA is used for securely exchanging encryption keys, while AES is used for encrypting application data. This approach removed the insecure hard-coded key from the original design and replaced it with a dynamic and secure key exchange process. I also strengthened data integrity verification by implementing **HMAC-SHA256**, which binds the hash to a secret key and makes tampering much easier to detect.

These changes required working with complex data structures such as `KeyPair`, `PublicKey`, `PrivateKey`, and `SecretKey`, and designing algorithms that balance security, scalability, and performance.

## Skills and Outcomes Demonstrated
This enhancement aligns closely with my planned course outcomes and demonstrates the following skills:

• Designing and evaluating computing solutions using algorithmic principles  
• Applying cryptographic algorithms appropriately based on performance and security trade-offs  
• Managing sensitive data through secure key generation, storage, and exchange  
• Anticipating adversarial exploits and mitigating vulnerabilities through secure design  

The enhanced solution reflects a security-first mindset and demonstrates my ability to improve an existing system by addressing weaknesses rather than simply adding features.

## Reflection on the Enhancement Process
Enhancing this artifact significantly deepened my understanding of how real encryption systems are designed. Implementing hybrid encryption helped clarify why certain algorithms are combined and how they complement each other. RSA provides secure key exchange but is inefficient for large data, while AES offers fast encryption once keys are safely shared. Designing a system that uses both required careful coordination and planning.

I also gained experience working with encoding and decoding processes and ensuring encrypted data remained synchronized throughout encryption and decryption. One of the main challenges was managing key generation and parameter passing correctly across methods. Debugging these issues strengthened my understanding of Java’s security libraries and reinforced the importance of precision when working with cryptographic systems.

Overall, this enhancement improved my confidence in secure software development and gave me hands-on experience applying algorithms and data structures that are critical to protecting real-world financial and enterprise systems.

