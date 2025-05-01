# Who Relies More on World Knowledge and Bias for Syntactic Ambiguity Resolution: Humans or LLMs?

Paper link: https://aclanthology.org/2025.naacl-long.177/

1. The doctor met the son of the man who had a beard.   Oh wait, who had a beard? the son or the man?
2. The doctor met the son of the woman who had a beard.  How about now? the woman or the son?

English normally prefers to "attach" the relative clause to the closest noun. We call this low attachment. Spanish and Korean, on the other hand,  prefer to attach to the farther noun -- they have "high attachment". Do LLMs reflect the same "attachment preference" as human lanugage-users? This is the "syntactic bias" we investigate in our paper.

In Sentence 2, we introduce another, semantic bias, based on world knowledge, since it is more common for men to grow beards than women. In this sentence it works **against** the syntactic bias. How do humans respond to these conflicting biases? How do LLMs resolve the relative clause attachment ambiguity? 

We constructed a 6-language dataset to investigate this phenomenon. Read our paper to find out the answers!

Paper link: https://aclanthology.org/2025.naacl-long.177/

ABSTRACT
This study explores how recent large language models (LLMs) navigate relative clause attachment {ambiguity} and use world knowledge biases for disambiguation in six typologically diverse languages: English, Chinese, Japanese, Korean, Russian, and Spanish. We describe the process of creating a novel dataset -- MultiWho -- for fine-grained evaluation of relative clause attachment preferences in ambiguous and unambiguous contexts. Our experiments with three LLMs indicate that, contrary to humans, LLMs consistently exhibit a preference for local attachment, displaying limited responsiveness to syntactic variations or language-specific attachment patterns. Although LLMs performed well in unambiguous cases, they rigidly prioritized world knowledge biases, lacking the flexibility of human language processing. These findings highlight the need for more diverse, pragmatically nuanced multilingual training to improve LLMs' handling of complex structures and human-like comprehension.
