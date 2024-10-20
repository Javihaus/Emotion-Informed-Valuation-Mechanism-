This repository contains the experiments explained in this post: https://cleverai.ghost.io/emotion-informed-valuation-mechanism/
## Description
This work introduces a novel emotion-informed valuation mechanism for large language models (LLMs), designed to enhance their emotional intelligence and contextual understanding. Drawing inspiration from V.J. Wukmir's psychological theory of emotion (orectic theory), we propose a multidimensional valuation space that incorporates emotional context into the attention mechanism of transformer-based models. We consider emotions as rapid, holistic evaluations that organisms use to assess stimuli. Our approach treats emotions as inputs to the valuation process, rather than outputs. We define a three-dimensional valuation space comprising valence, arousal, and relevance. The proposed mechanism generates emotion embeddings alongside traditional token embeddings, which are then combined and processed through a valuation function. The resulting emotion-informed valuations modify the standard attention weights, allowing the model to simultaneously consider semantic relationships and emotional/contextual significance. This approach aims to create more nuanced and contextually appropriate responses by enabling LLMs to process not just what is being said (semantics) but also how it's being said (emotional context). Potential applications span various domains, including improved human-AI interaction, more empathetic conversational agents, and enhanced content analysis.
![Diagram2-02](https://github.com/user-attachments/assets/91963f98-71e5-4873-b20d-0709e1df57e7)


