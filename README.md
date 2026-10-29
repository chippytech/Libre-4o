 
<img src="Libre-4o.svg" height="160px" alt="Libre-4o Logo">

# Libre-4o: Democratizing GPT-4o Access

**An open-weight, community-driven alternative to GPT-4o, built using existing open-source AI technologies.**

Libre-4o is an ambitious project to create a free, open-weight multimodal AI model inspired by OpenAI's GPT-4o. By combining existing specialized models into a shared architecture, we aim to make powerful multimodal AI more accessible, transparent, and customizable.

Our goal is simple: **Bring GPT-4o-like capabilities to the open-source community.**

> [!IMPORTANT]
> Libre-4o is an independent research project in early development. It is not affiliated with, endorsed by, or based on the proprietary weights of OpenAI's GPT-4o.

## The Problem

GPT-4o has become a highly valued AI model, particularly for its natural conversational abilities, multimodal understanding, and distinctive interaction style.

Many users across platforms such as X (formerly Twitter) and Reddit have expressed interest in seeing GPT-4o released as an open-weight model.

However, GPT-4o remains proprietary. Its model weights, full architecture, and training methods are not publicly available, limiting the ability of independent developers and researchers to study, modify, self-host, and build upon it.

We believe that advanced multimodal AI should be more accessible to everyone, not restricted to proprietary services.

## The Solution

**We are NOT training a large language model from scratch.**

Training a foundation model from the ground up requires enormous computational resources, funding, and datasets. Instead, Libre-4o aims to build upon existing open-weight and open-source AI technologies.

Our approach is to combine specialized pretrained models into a unified multimodal architecture, using trainable projection and fusion layers to connect their representations.

### Core Components

| Component | Role | Repository |
|---|---|---|
| **GPT-OSS** | Base language model and reasoning backbone | [openai/gpt-oss](https://github.com/openai/gpt-oss) |
| **CLIP** | Vision encoder for image understanding | [openai/CLIP](https://github.com/openai/CLIP) |
| **Whisper** | Audio encoder for speech understanding | [openai/whisper](https://github.com/openai/whisper) |
| **Tiktoken** | Supporting tokenization utilities | [openai/tiktoken](https://github.com/openai/tiktoken) |

Rather than simply converting images into captions or speech into transcripts, we want Libre-4o to process visual and audio representations directly through its shared language-model backbone.

This requires training multimodal adapters and fine-tuning the combined architecture.

## Our Roadmap

### Phase 1: Multimodal Architecture

- [ ] Establish GPT-OSS as the base language model.
- [ ] Integrate CLIP's vision encoder and extract visual patch representations.
- [ ] Integrate Whisper's audio encoder and extract hidden states.
- [ ] Implement trainable vision and audio projection layers.
- [ ] Develop a shared multimodal input interface.

### Phase 2: Multimodal Training

- [ ] Train projection layers to align image and audio representations with GPT-OSS.
- [ ] Develop multimodal fusion mechanisms.
- [ ] Train using image-text and audio-text datasets.
- [ ] Fine-tune selected language-model layers for multimodal understanding.
- [ ] Evaluate image understanding, speech comprehension, and cross-modal reasoning.

### Phase 3: Human-Like Conversation

- [ ] Build a high-quality conversational dataset using appropriately licensed and voluntarily donated data.
- [ ] Fine-tune Libre-4o for natural, engaging, human-like dialogue.
- [ ] Optimize for direct responses rather than lengthy reasoning traces.
- [ ] Improve conversational consistency, emotional awareness, and contextual understanding.
- [ ] Preserve multimodal capabilities during conversational fine-tuning.

### Phase 4: Open-Weight Release

- [ ] Evaluate model quality, reliability, and performance.
- [ ] Publish reproducible inference and training instructions.
- [ ] Release trained weights where redistribution rights permit.
- [ ] Document model limitations, datasets, and training methods.
- [ ] Make Libre-4o accessible to the open-source community.

## How You Can Help

**Libre-4o is a community-driven project, and we need your help to make it possible.**

### Donate Compute

Training multimodal projection layers and fine-tuning large language models requires substantial GPU resources.

We are looking for contributors willing to provide GPU compute, cloud training credits, or access to suitable training infrastructure.

### Contribute Training Data

We want Libre-4o to feel natural, conversational, and human-like.

To achieve this, we need high-quality conversational and multimodal training examples.

We welcome contributions of appropriately licensed or original datasets, including:

- Natural, multi-turn conversations.
- Human-written dialogue and responses.
- Image-question-answer pairs.
- Audio and speech understanding examples.
- Multimodal conversational examples.

**Please contribute only data that you have the right to share and authorize for model training.** Do not submit private conversations, personal information, copyrighted material without appropriate permission, or other sensitive data.

A formal data contribution and consent process will be established before accepting training-data donations.

### Contribute Code and Research

We welcome developers, machine learning researchers, and open-source enthusiasts interested in:

- PyTorch and model architecture development.
- Multimodal training and representation alignment.
- Dataset preparation and evaluation.
- Training optimization and efficient inference.
- Documentation, testing, and reproducibility.

If you're interested in helping, open a GitHub Issue to discuss your proposed contribution.

## Our Philosophy

We believe that powerful AI should be:

- **Open:** Model weights and implementation details should be publicly accessible wherever licensing permits.
- **Accessible:** Developers and researchers should be able to experiment without depending on proprietary APIs.
- **Transparent:** Training methods, limitations, and model behavior should be documented.
- **Community-driven:** Development should be shaped by collaboration and shared research.
- **Independent:** Users should have the freedom to run, modify, and deploy models on their own infrastructure.

## Project Status

🚧 **Early Development / Research Phase**

Libre-4o is currently a proposed architecture and research effort. No completed multimodal model or trained Libre-4o checkpoint is available yet.

We are seeking contributors, training resources, and research collaborators to help turn this vision into reality.

## Acknowledgments

Libre-4o builds upon publicly available work from OpenAI and the broader open-source AI community.

We acknowledge the original authors and contributors of GPT-OSS, CLIP, Whisper, and Tiktoken.

Each component remains subject to its respective license and model usage conditions.

---

**Libre-4o — Making multimodal AI more open, accessible, and community-driven.**

*Built by the community, for the community.*
