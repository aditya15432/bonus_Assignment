# bonus_Assignment

This bonus assignment consists of two mini-projects that apply deep learning concepts using modern libraries like Hugging Face Transformers and PyTorch. The main goal is to demonstrate practical understanding of question answering systems and generative adversarial networks (GANs), with a focus on label conditioning.

✅ Task 1: Question Answering with Transformers
In this part, a simple question answering system is implemented using Hugging Face’s transformers library. It involves:

Setting up a default QA pipeline and testing it on a sample context.

Switching to a custom pre-trained model (deepset/roberta-base-squad2) for improved accuracy.

Creating a custom context and asking multiple questions to validate the system's generalizability.

The model returns answers with high confidence (score > 0.70), including start and end indices, simulating real-world applications like chatbots or intelligent search systems.

✅ Task 2: Digit-Controlled Image Generation using Conditional GAN (cGAN)
This task involves implementing a Conditional GAN that learns to generate handwritten digits (0–9) from the MNIST dataset, conditioned on the input class label. Key steps:

Modified both the generator and discriminator to accept label embeddings along with the standard input.

Trained the cGAN to control digit output based on specific class labels.

Generated and visualized a row of digits (0 to 9), each generated according to the corresponding label.

This shows how GANs can be controlled through conditioning, with real-world applications in face generation, text-to-image synthesis, and domain translation.