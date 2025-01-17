# Technical-Support
Repository designed to provide practical knowledge of computer systems, covering fundamentals of hardware and software support. Ideal for building real-world problem-solving skills.

## Artificial intelligence
Artificial intelligence (AI) is the field of computing focused on creating systems capable of performing tasks that would typically require human intelligence. These tasks include reasoning, learning, problem-solving, perception, language understanding, and even the ability to move and manipulate objects.

Machine learning
Machine learning (ML) is a critical domain within artificial intelligence that emphasizes the development of algorithms and statistical models that enable computers to perform specific tasks without explicit instructions. Instead, these systems learn and make predictions or decisions based on data. Here's a more technical breakdown:

1. Types of learning:

Supervised learning: Algorithms learn from labeled training data, aiming to predict outcomes for new inputs.
Unsupervised learning: Algorithms identify patterns in data without needing labeled responses, often used for clustering and association.

Reinforcement learning: Models learn to make sequences of decisions by receiving feedback on the actions' effectiveness.

2. Algorithms and techniques:

Common algorithms include linear regression, decision trees, and neural networks.

Advanced techniques involve deep learning, which uses layered neural networks to analyze various levels of data features.

3. Data handling and processing:

Effective machine learning requires robust data preprocessing, including normalization, handling missing values, and feature selection to improve model accuracy.

4. Performance evaluation:

ML models are evaluated based on metrics such as accuracy, precision, recall, and the area under the receiver operating characteristic (ROC) curve, ensuring that they perform well on unseen data.

5. Application areas:

ML is applied in various fields such as finance for algorithmic trading, healthcare for predictive diagnostics, and autonomous vehicles for navigation systems.
![Screenshot (4)](https://github.com/user-attachments/assets/415247d7-7f99-4b0f-aa5d-883331769fa1)
## Deep learning
Deep learning (DL) is an advanced branch of ML that uses artificial neural networks with multiple layers, known as deep neural networks. These networks are capable of learning from large amounts of unstructured data. DL models automatically extract and learn features at multiple levels of abstraction, enabling the system to learn complex patterns in large datasets. The learning process can be:

Supervised - where the model is trained with labeled data

Semi-supervised - which uses a mix of labeled and unlabeled data

Unsupervised - which relies solely on unlabeled data 

This technique is particularly effective in areas such as image recognition, natural language processing (NLP), and speech recognition, where conventional machine-learning techniques may fall short due to the data structures' complexity. DL has propelled advancements in generative AI, enabling the creation of sophisticated models like generative adversarial networks (GANs) that can generate new data instances that mimic real data.

## Neural networks
Neural networks (NN) are a cornerstone of AI. They are particularly effective in pattern recognition and data interpretation tasks, which they achieve through a structure inspired by the human brain. Comprising layers of interconnected nodes, or neurons, each with its weights and biases, NN processes input data through these nodes. The connections between nodes represent synapses and are weighted according to their importance. As data passes through each layer, the network adjusts the weights, which is how learning occurs. This structure enables neural networks to learn from vast amounts of data to make decisions, classify data, or predict outcomes with high accuracy. NN are particularly crucial in fields such as computer vision, speech recognition, and NLP where they can recognize complex patterns and nuances better than traditional algorithms. The training process involves techniques such as backpropagation, where the model learns to minimize errors by adjusting weights to produce the most accurate outputs possible.

## Generative adversarial networks (GAN)
GANs are a sophisticated class of AI algorithms used in ML, characterized by their unique structure of two competing NNs: the generator and the discriminator. The generator is tasked with creating data that is indistinguishable from genuine data, while the discriminator evaluates whether the generated data is real or fake. This adversarial process, much like a teacher-student dynamic, continuously improves the accuracy of the generated outputs. The training involves the discriminator learning to better distinguish between real and generated data, while the generator strives to produce increasingly convincing data, enhancing its ability to deceive the discriminator. This setup not only helps in generating new data samples but is also useful in unsupervised learning, semi-supervised learning, and reinforcement learning. GANs are particularly renowned for their applications in image generation, video creation, and voice synthesis, where they can produce highly realistic outputs.

## Natural language processing (NLP)
NLP is an advanced area of AI that focuses on the interaction between computers and humans through natural language. The goal of NLP is to read, decipher, understand, and make sense of human languages in a manner that is valuable. It involves several disciplines, including computer science and computational linguistics, in an effort to bridge the gap between human communication and computer understanding. Key techniques in NLP include syntax tree parsing, entity recognition, and sentiment analysis, among others. These techniques help computers to process and analyze large amounts of natural language data. NLP is used in a variety of applications, such as automated chatbots, translation services, email filtering, and voice-activated global position systems (GPS). Each application requires the computer to understand the input provided by humans, process that data in a meaningful way, and if necessary, respond in a language that humans understand.

## Transformers 
Transformers represent a significant advancement in deep learning, particularly in the field of NLP. Introduced by Google researchers in the seminal 2017 paper "Attention is All You Need", transformers use a mechanism known as self-attention to weigh the importance of each word in a sentence, regardless of its position. Unlike previous models that processed data sequentially, transformers process all words or tokens in parallel, which significantly increases efficiency and performance on tasks that require understanding context over long distances within text. This architecture avoids recurrence and convolutions entirely, relying instead on stacked self-attention and point-wise, fully connected layers for both the encoder and the decoder components. This design allows for more scalable learning and has been fundamental in developing models that achieve state-of-the-art results on a variety of NLP tasks, including machine translation, text summarization, and sentiment analysis. The transformer's ability to handle sequential data extends beyond text, making it versatile in other domains like image processing and even music generation.

## Generative pre-trained transformers
Generative pre-trained transformers (GPT) are state-of-the-art language models developed by OpenAI that use DL techniques, specifically the transformer architecture, for natural language understanding and generation. These models are first pre-trained on a diverse range of internet text to develop a broad understanding of language structure and context. The pre-training involves unsupervised learning, where the model predicts the next word in a sentence without human-labeled corrections. This allows GPT models to generate coherent and contextually appropriate text sequences based on the prompts they are given. Once pre-trained, GPT models can be fine-tuned on specific tasks such as translation, question-answering, and summarization, enhancing their applicability across various domains. Their ability to generate human-like text and perform language-based tasks has implications across fields such as AI-assisted writing, conversational agents, and automated content creation. Each successive version of GPT has been larger and more complex, with GPT-4, the latest iteration, containing 175 billion parameters, which significantly advances its learning and generative capabilities.

## Tokenization, Word2vec, and BERT
Tokenization in NLP involves splitting text into smaller units known as tokens, which can be words, characters, or subwords. This step is crucial for preparing text for processing with various NLP models, as it standardizes the initial input into manageable pieces for algorithms to process. Word2vec, developed by researchers at Google, is a technique that embeds words into numerical vectors using shallow, two-layer NNs. The models are trained to reconstruct the linguistic contexts of words, thereby capturing the relationships and multiple degrees of similarity among them. Meanwhile, Bidirectional Encoder Representations from Transformers (BERT) represents a significant advancement in pre-training language representations. Developed also by Google, BERT incorporates a transformer architecture that processes words in relation to all the other words in a sentence, rather than one-by-one in order. This allows BERT to capture the full context of a word based on all its surroundings, leading to a deeper understanding of language nuances. BERT's ability to handle context from both directions makes it exceptionally powerful for tasks where context is crucial, such as question answering and sentiment analysis.

## Neural Network
A Neural Network is a type of machine learning algorithm inspired by the structure and functioning of the human brain. It is composed of layers of interconnected nodes (also called neurons), which process data and learn patterns to make predictions or decisions. Neural networks are the foundation of many artificial intelligence (AI) systems.

Applications-
Image recognition and processing (e.g., facial recognition).
Natural language processing (e.g., chatbots, translation tools).
Finance (e.g., fraud detection, stock price predictions).

## Threat stats
Trojan Attacks
A user inadvertently introduces malicious code into the organization and triggers it behind the defensive walls. The best defense against trojan attacks is to practice vigilant internet usage. Some guidelines are to never click on an unsolicited email with unexpected attachments, and always examine domain names and links before clicking on them. Be particularly vigilant with misspellings, such as zeroes that have been replaced with O’s, a trick used to lure an unwary user into bringing the horse behind the gate. Below you’ll find an example of a potentially malicious email, along with a list of general warning signs to be aware of.
This is an umbrella term that covers several attack types, including the following:

-- Exploit Trojans 

-- Downloader Trojans 

-- Ransom Trojans 

-- Backdoor Trojans 

## Ransomware Attacks

Recall that ransomware is an approach to cybercrime that is designed to cause disruption to services. This approach is featured frequently in the news due to the scope of impact. It is not uncommon for these attacks to occur on a national scale, with infrastructure and vital services being the target. Recent examples include:
-- Ireland’s Health Service’s Executive (HSE) in 2021.

-- Critical Ukraine infrastructure in 2022. 

The methodology behind these types of attacks is to gain access to a system and lock out the legitimate owner until a demand has been met. One approach to best mitigate against this type of attack is to ensure that no external actors gain access to your system. Best practices for achieving this include the following:

-- Use strong passwords. A strong password is one that is difficult to guess and typically would include a mix of characters, numbers, and symbols. 

-- Keep your system up-to-date with the latest security patches.

-- Ensure that only people with authorization for a system can use its system. 

## Botnet Attacks
A bot can be defined as an online software program that performs automated and repetitive tasks. They are a means of creating a Denial of Service to an organization. If a Trojan attack is a subtle attempt to circumnavigate an application’s defenses, a bot attack could be described as a full scaling of the walls.

These attacks are orchestrated so that a system is plagued with innumerable requests for information and services. These requests can come from any capable devices on the Internet of Things (IoT) that have an IP address. The IoT relates to devices online and will be covered in more detail later. 

This type of attack can be coupled with the trojan attack, when some of the code maliciously embedded in a system is used to make the request of another system. In this way, an attacker makes use of someone else's digital resources to negate the resources of a targeted victim. One defensive approach to mitigate against these types of attacks is to monitor network traffic for suspicious activity. If a particular source is identified as making repeated calls that impact the operations of a system, then this address can be blocked. However, more sophisticated approaches must be employed when a variety of compromised systems are used. 


## Explaining the threat landscape
Threat number One: Poor password protection  
Vulnerability: Poor password

Passwords are the first step in protecting a business, as they offer a legitimate way for an authorized user to gain access to a system. Using an oversimplified password poses a severe risk to an organization. 

Risk: Brute force attack 

A brute force attack involves running through a list of common passwords in an effort to see whether a password can be guessed to gain access to a system.

Attack: Ransomware

Once an external party has gained access to a system, it is possible for them to make internal changes that could have very harmful side effects for a business. One potential danger might be locking the account owner from the system until such a ransom is paid. 

Mitigation: Choose strong passwords, and never use the same passwords for different applications. 

Threat Number Two: Malware 
Vulnerability: Poor cyber hygiene 

Cyber hygiene is the practice of maintaining the health and security of a system and includes such habits as regularly updating software and scanning for malware and other unwanted elements. Poor cyber hygiene opens the door for malware, which is one of the oldest forms of carrying out a cyberattack. It involves getting a legitimate user within a system to trigger some code from within the system that is designed to alter the system in some unintended way. Malware often requires a user within a system to click on a link. This is often achieved by sending an email with a link or an attachment and directions to click on it to claim a reward.

Risk: Trojans 

A trojan is an umbrella term for several attacks that can be executed by unsuspectingly clicking on a link containing malware.

Attack: Malware 

Malware can be designed to perform any number of ill effects on a system once executed. It is a blanket term that can encompass theft of information, disruption of services, or application of ransomware. Injecting it into a system by unsuspectingly clicking on a link can be very harmful. 

Mitigation: 

Generally, practicing good cyber hygiene can mitigate against malware. Be careful when clicking on external links, and always check email addresses to ensure that they originate from a trusted source. Watch the language used in emails, which is often an indicator of a dubious source and can be identified through poor grammar and spelling. The image below provides an example of a potentially malicious email:

Warning signs of a potentially malicious email.
Threat Number Three: Virus 
Vulnerability: Outdated Software

When software is first released it is prone to bugs or flaws in it that were not identified previously. Once these bugs are discovered, a patch to close or fix them will typically be released in the form of an update. This is why it is so important to always keep your software updated. 

Risk: Virus  

Outdated software builds up an increasing risk of viruses as more and more bugs are found with the application.

Attack: Exploiting software bug 

Outdated software can leave an opening in your firewall that a malicious actor can exploit. Depending on the flaw any number of attacks may be released. 

Mitigation: 

Enable automatic updates on your software if available or check for updates and install them on a regular basis.





