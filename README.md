# Human-AI-Generated Text Corpus
The dataset contains human-generated, _AI-generated_ and _AI-rephrased_ texts from the _educational domain_ in English, French, German, and Spanish and English texts
from the _news domain_.

## Texts from the Educational Domain
The educational human-generated texts consist of 100 Wikipedia texts from the following categories:
- Biology
- Chemistry
- Geography
- History
- IT
- Music
- Politics
- Religion
- Sports
- Visual arts

## Text from the News Domain
The news human-generated texts consist of 100 news articles from the following categories:
- Crime
- Entertainment
- Politics
- Science
- Sports

For the generation of the AI-written texts, GPT-3.5 was used. For each human-generated text, 4 AI-written texts were generated using the following prompts:

### Basic AI-generated
Generate a text on the following topic: <Title>

### Advanced AI-generated
Generate a text on the following topic in a way a human would do it: <Title>

### Basic AI-rephrased
Rephrase a text on the following topic: <Text>

### Advanced AI-rephrased
Generate a text on the following topic in a way a human would do it: <Text>

For the other languages, the prompts were translated.


## References

Please cite the following publications when using the data from this repo.

Schaaff, K., Schlippe, T., Mindner, L. (2024). Classification of human- and AI-generated texts for different languages and domains. In: International Journal of Speech Technology. https://doi.org/10.1007/s10772-024-10143-3

Mindner, L., Schlippe, T., Schaaff, K. (2023). Classification of Human- and AI-Generated Texts: Investigating Features for ChatGPT. In: Schlippe, T., Cheng, E.C.K., Wang, T. (eds) Artificial Intelligence in Education Technologies: New Development and Innovative Practices. AIET 2023. Lecture Notes on Data Engineering and Communications Technologies, vol 190. Springer, Singapore. https://doi.org/10.1007/978-981-99-7947-9_12

Schaaff, K., Schlippe, T., Mindner, L. (2023). Classification of Human- and AI-Generated Texts for English, French, German, and Spanish. In: The 6th International Conference on Natural Language and Speech Processing (ICNLSP 2023), Virtual, 16-17 December 2023. Available at: https://aclanthology.org/2023.icnlsp-1.1.pdf
