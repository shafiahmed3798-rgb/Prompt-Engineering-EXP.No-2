EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:
CHATGPT

1. Zero-Shot Summary

(Direct summary without examples or guidance)

Blockchain is a decentralized digital ledger that stores data in linked blocks secured by cryptographic hashes. It ensures transparency, security, and immutability by distributing data across multiple nodes instead of relying on a central authority. Blockchain uses consensus mechanisms to validate transactions and supports smart contracts for automation. It is widely used in cryptocurrency, banking, supply chain management, healthcare, and digital identity systems. While blockchain offers benefits such as security, transparency, and efficiency, it also faces challenges like scalability, high energy consumption, and regulatory uncertainty.

2. Few-Shot Summary

(Summary based on examples of concise summarization style)

Example Style: Artificial Intelligence is technology that enables machines to perform tasks requiring human intelligence like learning and decision-making.

Blockchain Summary: Blockchain is a secure digital system for recording and sharing data across many computers. It stores information in connected blocks, making it difficult to alter records once stored. It works without a central authority by using distributed nodes and consensus verification. Blockchain is used in Bitcoin, banking, supply chains, smart contracts, and digital identity management. Its major advantages include security and transparency, while limitations include energy usage and slow adoption.

3. Chain-of-Thought Summary

(Step-by-step reasoning summary)

To understand blockchain:

Step 1: Blockchain is a digital ledger that stores records in blocks. Step 2: Each block contains transaction data, timestamps, and a cryptographic hash linked to the previous block. Step 3: This linking makes tampering easy to detect. Step 4: Data is distributed across multiple nodes, making it decentralized. Step 5: Transactions are verified using consensus mechanisms. Step 6: Smart contracts automate actions when conditions are met. Step 7: Blockchain is used in finance, healthcare, supply chain, voting systems, and digital identity.

Final Summary: Blockchain is a decentralized and secure technology that records data transparently across a distributed network. Its tamper-proof structure and automated processes make it valuable for modern digital applications.

4. Role-Based System Summary

(As if written by an expert educator)

Role: Technology Professor

Blockchain is a foundational distributed ledger technology designed to securely record and verify transactions without requiring intermediaries. It operates through interconnected blocks protected by cryptographic hashes and maintained across a decentralized network of nodes. Through consensus protocols, blockchain ensures trust, transparency, and immutability of records. Its applications extend beyond cryptocurrency to include finance, logistics, healthcare, governance, and smart contract automation. Although blockchain offers transformative potential, issues such as scalability, energy demands, and regulatory concerns remain significant challenges.

CLAUDE

Zero-Shot Prompt "Summarize the following blockchain document." Summary: Blockchain is a decentralized, immutable digital ledger that stores data in cryptographically linked blocks across a network of nodes. It eliminates the need for central authorities by using consensus mechanisms to validate transactions. Originally powering Bitcoin (2008), it evolved through Ethereum (2015) to support smart contracts and decentralized apps. Today it's applied across banking, supply chain, healthcare, travel, and government. Its key strengths are security, transparency, and efficiency — but challenges around scalability, energy use, and regulation remain.

Few-Shot Prompt "Here are examples of how to summarize tech topics in one sentence each... Now summarize blockchain." Summary: Blockchain is a tamper-proof, distributed ledger technology that records transactions across a peer-to-peer network using cryptography and consensus algorithms — removing the need for intermediaries while enabling applications from digital currency to smart contracts, supply chain tracking, and decentralized finance, despite ongoing challenges in scalability, energy consumption, and regulation.

Chain-of-Thought Prompt "Think step by step: What is it? How does it work? Where is it used? What are the pros and cons?" Summary: What is it? Blockchain is a shared, immutable ledger where data is stored in cryptographically chained blocks distributed across many nodes. How does it work? Each transaction is verified by the network via consensus (e.g., Proof of Work), recorded in a block with a unique hash, and linked to the previous block — making tampering detectable. Where is it used? Banking (JP Morgan, Barclays), supply chains (Walmart, Unilever), healthcare (Pfizer, DHL), aviation, and government (Dubai). Pros: Decentralized, secure, transparent, efficient, trust-building. Cons: Hard to scale, energy-intensive, slow adoption, unclear regulation, no unified standards. Conclusion: Blockchain is transformative but still maturing.

Role-Based System Prompt "You are a professor explaining blockchain to first-year computer science students." Summary: Think of blockchain as a Google Doc that no one owns but everyone can see — and once something is written, it can never be erased. Each "page" (block) contains transactions, a timestamp, and a fingerprint (hash) of the previous page, chaining them together. No single server holds this document; instead, thousands of computers around the world each hold an identical copy. If someone tries to cheat by editing a page, their fingerprint won't match everyone else's — so the network rejects it. This is how Bitcoin prevents fraud without a bank, and how Ethereum lets developers build self-running contracts and apps on top of it.

GEMINI

1. Zero-Shot Summary This approach generates a direct summary based entirely on the provided text without any prior examples or step-by-step reasoning.

Summary: Blockchain is a decentralized, distributed digital ledger that organizes data into cryptographically secured, immutable blocks across a peer-to-peer network of nodes. By eliminating central authorities (like traditional banks), it builds trust through transparency, consensus mechanisms, security, and smart contracts. While it vastly improves traditional systems by cutting transaction waiting times, reducing middleman fees, and enhancing supply chain traceability, it faces challenges such as scalability limits, high energy consumption, regulatory uncertainty, and slow adoption. Major global industries—spanning finance, healthcare, aviation, and tech—are heavily investing in blockchain, paving the way for future applications in Decentralized Finance (DeFi), secure digital identities, and the Internet of Things (IoT).

2. Few-Shot Summary This approach mimics a specific template style by learning from a couple of quick format examples.

Example 1 (Bitcoin): A digital cryptocurrency using peer-to-peer networks to bypass banks, utilizing digital signatures to secure transactions. Example 2 (Smart Contracts): Automated, self-executing digital scripts embedded in a blockchain that trigger actions when specific pre-set conditions are met.

Summary (Blockchain Technology): A tamper-proof, decentralized database synchronized across global nodes that records transactions permanently without a central server. It eliminates expensive intermediaries, enhances data integrity through cryptographic hashing, and is actively transforming global sectors like banking, logistics, and retail despite facing current hurdles in energy consumption and regulatory frameworks.

3. Chain-of-Thought (CoT) Summary This approach breaks down the text logically step-by-step to arrive at a comprehensive conclusion.

Step 1: Identify the core definition. Blockchain is a shared, decentralized ledger where data is bundled into blocks and chained together using cryptographic hashes, making it immutable.

Step 2: Contrast with current systems. Traditional systems suffer from central points of failure (e.g., bank server hacks), high third-party fees, and long processing times. Blockchain solves this by distributing data across millions of nodes.

Step 3: Pinpoint the key components. The system relies on a peer-to-peer network, consensus mechanisms (to agree on data validity), cryptography, and automated smart contracts.

Step 4: Analyze real-world impact and adoption. Major corporations (like Walmart, Visa, and Pfizer) are already using it to secure supply chains, track inventory, and streamline payments.

Step 5: Weight the pros against the cons. While it brings unparalleled security, trust, and transparency, it is bottlenecked by scalability issues, high mining energy consumption, and a lack of standardized regulations.

Conclusion/Summary: Therefore, blockchain is a foundational, trust-less architecture poised to revolutionize future digital infrastructure (via DeFi, IoT, and Digital IDs) once its current technical and regulatory constraints are resolved.

4. Role-Based System Summary This summary is written from the perspective of a specific persona: A Venture Capitalist Tech Analyst evaluating the technology for future investment.

Executive Summary Report: From an investment and market-disruption standpoint, Blockchain represents a paradigm shift from centralized trust to algorithmic trust. By utilizing a distributed architecture secured by cryptography, it effectively de-risks operations by eliminating single points of failure and cutting out high-fee intermediaries (saving industries 18–22% in overhead costs).

The enterprise validation is already clear: tier-one firms across finance (JP Morgan, Goldman Sachs), logistics (DHL, Walmart), and tech (Google, Microsoft) are actively deploying it. While current infrastructure bottlenecks—specifically scalability and high energy overhead—present short-term friction, the long-term addressable market in DeFi, automated legal frameworks (Smart Contracts), and IoT security makes this a foundational technology for the next generation of global digital trade. Recommendation: Highly viable for long-term strategic deployment.

COPILOT

Zero-shot (direct summary without examples)

Advantages: Decentralization, security, transparency, efficiency, trust.

Disadvantages: Scalability issues, high energy consumption, slow adoption, regulatory uncertainty, lack of standards.

Few-shot (summary with examples for clarity)

Advantages:

Decentralization: Removes intermediaries, lowering costs.

Security: Cryptography makes transactions resistant to hacking.

Transparency: Shared ledger reduces disputes.

Efficiency: Faster, cheaper transactions.

Trust: Built through openness and security.

Disadvantages:

Scalability: Hard to handle large-scale applications.

Energy: Mining consumes massive power.

Adoption: Slow due to complexity.

Regulation: Unclear frameworks create risk.

Standards: Lack of uniform protocols hinders integration.

Chain-of-thought (step-by-step reasoning)

Blockchain eliminates intermediaries → lowers costs → increases transparency.

Cryptography secures transactions → reduces fraud → builds trust.

Shared ledger → everyone sees the same data → disputes minimized.

However, decentralization → harder to scale → performance bottlenecks.

Mining → requires huge computing power → energy/environmental concerns.

Adoption → slowed by technical complexity → businesses hesitant.

Regulation → still evolving → uncertainty for investors.

Standards → missing → integration challenges.

Role-based system (explained from different perspectives)

Business Leader: Blockchain reduces costs and builds trust, but regulatory uncertainty makes investment risky.

Technologist: Strong cryptography ensures security, yet scalability and energy use remain major technical hurdles.

Policy Maker: Transparency is valuable, but lack of standards and regulation complicates governance.

Environmentalist: Efficiency is appealing, but mining’s energy consumption raises sustainability concerns.

<img width="1044" height="494" alt="image" src="https://github.com/user-attachments/assets/61781909-3bc8-460b-9b63-66668692fdaf" />


RESULT:
The best overall combination is FEW-SHOT PROMPT + Chatgpt based on the evaluation metrics including accuracy, simplicity, speed, and user experience.
