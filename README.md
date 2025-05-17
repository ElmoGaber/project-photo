# project-photo

project centers around advancing criminal profiling
by employing a generative AI-based system for text-to-face image synthesis. The project addresses a significant gap in current text-to-image generation tasks, which are primarily limited to producing images of objects like flowers (Oxford
102 Flower), birds (CUB-200–2011), or general items (COCO) from captions. Existing face datasets such as Labeled Faces in the Wild and MegaFace lack
descriptive captions, while datasets like CelebA include attributes but lack
detailed feature descriptions. This limitation hinders the potential for
applications in fields such as criminal profiling.

![categories](https://github.com/user-attachments/assets/93b7a9f5-ea9c-4976-a3b8-5ca656a32d9c)
![Screenshot 2024-11-19 004840](https://github.com/user-attachments/assets/f1acb577-21b9-46d0-8ae7-297595282a82)

The importance of this system lies in its ability to bridge the gap between
textual descriptions and visual representations of human faces. By building upon
existing algorithms, we generate detailed captions from the attributes in the
CelebA dataset. Unlike traditional approaches, our system enables the creation
of not just one caption but multiple (N) captions per image, providing diverse
textual interpretations for the same face. These captions are transformed into
sentence embeddings using Sentence-BERT, ensuring high-quality textual
feature representation.

![loss](https://github.com/user-attachments/assets/d2ca7bf5-13e1-453a-8b9a-a6695ded3cec)
![processflow](https://github.com/user-attachments/assets/89e2b681-1171-4a54-9805-57627103be5a)

In addition to its technical framework, this project integrates features
aimed at enhancing usability and ensuring robust outputs. The text-to-image
synthesis system offers precise, human-like results, revolutionizing the field of
generative AI. By empowering law enforcement agencies with tools for criminal
profiling, the project paves the way for significant advancements in justice and
public safety. 

Overall, this project offers a transformative solution to a critical challenge
in generative AI, creating a novel application that combines advanced deep
learning techniques with practical societal impact.

![result](https://github.com/user-attachments/assets/347d6bf5-e909-4add-bd58-1d5f2f183424)
