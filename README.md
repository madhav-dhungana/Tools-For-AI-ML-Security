# Tools for AI/ML Security
The hacker's Toolbox: Tools for AI/ML Pentesting
A carefully curated collection of top AI security frameworks, tools, attacks, and research papers, inspired by the awesome-machine-learning repository.




As Artificial Intelligence (AI) and Machine Learning (ML) systems become integral to numerous applications, their security against adversarial threats has become a pressing concern. Incidents such as adversarial attacks on self-driving cars and bypassing AI-driven authentication systems highlight the critical need for robust security testing. Attackers are constantly finding new ways to exploit vulnerabilities in AI models, making comprehensive testing and evaluation indispensable.

To address these challenges, several tools have been developed to identify weaknesses, test defenses, and improve the resilience of AI models. Below is a curated list of essential tools for AI/ML penetration testing, emphasizing their key functionalities and practical applications.

---

## Tools for AI/ML Penetration Testing

### 1. **Adversarial Robustness Toolbox (ART)**
- **Source**: IBM Research  
- **GitHub**: [ART Repository](https://github.com/IBM/adversarial-robustness-toolbox)  
- **Description**: ART is a comprehensive library designed to test and enhance the security of machine learning models. It supports a wide range of adversarial attacks (e.g., FGSM, PGD) and defenses across different ML frameworks like TensorFlow, PyTorch, and Scikit-learn.  
- **Best for**: Testing classification, regression, and clustering models against adversarial threats.

### 2. **CleverHans**
- **Source**: OpenAI and Google Brain  
- **GitHub**: [CleverHans Repository](https://github.com/cleverhans-lab/cleverhans)  
- **Description**: A benchmark library for assessing vulnerabilities in ML models to adversarial examples. It provides tools for evaluating model robustness.  
- **Best for**: Researchers looking to benchmark adversarial robustness.

### 3. **Foolbox**
- **Source**: University of Tübingen  
- **GitHub**: [Foolbox Repository](https://github.com/bethgelab/foolbox)  
- **Description**: A versatile library supporting various adversarial attacks and defenses. It allows users to test models for weaknesses and analyze mitigation strategies.  
- **Best for**: Evaluating deep learning model robustness in academic and enterprise research.

### 4. **PyRIT**
- **Source**: Microsoft  
- **GitHub**: [PyRIT Repository](https://github.com/microsoft/pyrit)  
- **Description**: PyRIT evaluates privacy and robustness in AI systems, focusing on data poisoning, adversarial examples, and model inversion attacks.  
- **Best for**: Identifying AI security flaws related to data manipulation.

### 5. **Garak**
- **Source**: NVIDIA  
- **GitHub**: [Garak Repository](https://github.com/NVIDIA/garak)  
- **Description**: A tool specializing in scanning vulnerabilities in large language models (LLMs), helping identify risks associated with unintended AI behaviors.  
- **Best for**: Enhancing LLM security and integrating with NVIDIA’s NeMo Guardrails.

### 6. **Prompt Fuzzer**
- **Source**: Prompt Security  
- **GitHub**: [Prompt Fuzzer Repository](https://github.com/prompt-security/prompt-fuzzer)  
- **Description**: Evaluates the robustness of language models against prompt injection attacks. A crucial tool for ensuring LLM safety in real-world applications.  
- **Best for**: Testing chatbot security and automated assistant models.

### 7. **Akto**
- **Source**: Akto  
- **GitHub**: [Akto Repository](https://github.com/akto-api/akto)  
- **Description**: An API security tool designed to test the robustness of APIs integrated with AI systems. It helps detect vulnerabilities compromising data integrity.  
- **Best for**: Securing AI-driven API interactions.

### 8. **DeepEval**
- **Source**: Confident AI  
- **GitHub**: [DeepEval Repository](https://github.com/confident-ai/deepeval)  
- **Description**: A red-teaming tool for LLMs, analyzing security flaws and improving robustness against adversarial threats.  
- **Best for**: Stress-testing LLMs for adversarial weaknesses.

---
