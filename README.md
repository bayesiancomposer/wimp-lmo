# Wimp LMo

Papers on adversarial training for confidently incorrect language models.

Inspired by Wimp Lo from *Kung Pow: Enter the Fist* (2002), who was deliberately "trained wrong, as a joke."

## Papers

**[Wimp LMo: Adversarial Training for Confidently Incorrect Language Models](wimp_lmo.pdf)**

We introduce Wimp LMo, a 70B parameter model trained using Inverse Reinforcement Learning from Human Disappointment (IRLHD). The model achieves state-of-the-art performance on the Confidently Incorrect Benchmark (CIB-2024), generating responses that are simultaneously maximally wrong and maximally confident 94.7% of the time.

**[Wimp LMo 2: That's a Lot of Parameters](wimp_lmo_2.pdf)**

The sequel establishes Scaling Laws for Wrongness (W(C) = 4.7·C^0.69), introduces Wimp LMo Vision for multimodal misunderstanding, and presents the Chosen One Prompting Paradigm for giving any model main character syndrome.

## Code

Code will be released alongside Kung Pow 2: Tongue of Fury.

## Key Contributions

- 70 novel loss functions including `BleedingMakesTheVictorLoss`, `SqueakyShoeRegularizer`, and `BirdieBirdieLoss`
- Face-to-Fist Style Attention
- The Gopher-Chucks Attention Bridge
- A model card listing "Being helpful" as an out-of-scope use

## Citation

If you use this work, please cite both papers. If you complain about this work, we will interpret that as additional citations.

## License

MIT License

Copyright (c) 2025 bayesian_composer

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
