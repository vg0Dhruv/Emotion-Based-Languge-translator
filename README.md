This project is a proof of concept for an emotion-aware language translator. Traditional translation models prioritize linguistic accuracy, often overlooking the emotional tone of the text. This model aims to bridge that gap by integrating emotional understanding into the translation process.

📂 Dataset
Hindi-English Parallel Corpus
🔗 Kaggle Dataset

⚠️ Due to file size limitations, the dataset and trained models are not included in this repository. Please download them manually from the provided link.

🧠 Project Goals
Improve the literary translation of text by preserving emotional tone.

Create a machine translation system that can better handle long-form content, where current systems struggle.

Explore emotional adaptation to enhance translation quality.

⚙️ Approaches Used
1. Pretrained Model + Emotion-based Retranslation
Utilizes a state-of-the-art pretrained model.

Translates the input text and then retranslates based on the emotional confidence of the output with respect to the input.

✅ Observations:
Emotional tone is retained.

Basic translation is functional.

⚠️ Challenges:
Repeated translation degrades accuracy.

Not effective for context-sensitive or speaker-dependent languages.

2. Custom Model Trained with Emotion as a Parameter
A new model is trained from scratch where emotions are a key feature in learning the translation.

✅ Observations:
The model learns to prioritize emotions, sometimes opting to use punctuation or formatting to preserve tone.

⚠️ Challenges:
Sacrifices translation accuracy for emotional integrity.

Unreliable for general-purpose translation where linguistic accuracy is critical.

📌 Use Cases
Translating literary works, poetry, or emotionally rich content.

Enhancing reader empathy in translated stories.

Developing emotionally intelligent conversational agents.

🚧 Limitations
Not yet optimized for production use.

Works best for proof-of-concept, experimental applications, and future research.

🧾 Conclusion
While current translation systems focus on lexical and grammatical fidelity, this project takes a step further by embedding emotion into machine translation, proving that there's more to language than just words.

