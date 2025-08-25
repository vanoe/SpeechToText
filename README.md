# Speech To Text

Speech-to-Text solution transforms spoken language into accurate, real-time text, making voice commands, transcription, and subtitle creation faster and more reliable. Built with advanced deep learning, it combines CNNs for feature extraction and LSTMs for contextual understanding, ensuring high accuracy across diverse accents, dialects, and noisy environments. A custom noise reduction algorithm improves clarity by filtering background sounds, while training on a diverse dataset makes the system inclusive and adaptable. With a word error rate as low as 5% and real-time processing, it outperforms traditional models and sets a new standard for accessibility, efficiency, and scalability in voice-driven technology.

---

## Scheme

<img src="./img/img-1.png" alt="Scheme">

---

## Technical Description
- **Feature Extraction:** Convolutional Neural Networks (CNNs) process spectrograms of speech for frequency and time-based analysis.
- **Sequence Modeling:** Long Short-Term Memory (LSTM) networks capture sequential dependencies for contextual understanding.
- **Noise Reduction:** Custom algorithm trained to filter out ambient noise and improve clarity.
- **Training Data:** Over 1,000 hours of multilingual, noise-varied speech data for inclusivity and adaptability.
- **Optimization:** Dropout, batch normalization, and cross-entropy loss used to improve efficiency and prevent overfitting.

---

## Examples

<table>
    <tbody>
        <tr>
            <td><img src="./img/img-2.png" alt="image"></td>
            <td><img src="./img/img-3.png" alt="image"></td>
        </tr>
        <tr>
            <td><img src="./img/img-4.png" alt="image"></td>
            <td><img src="./img/img-5.png" alt="image"></td>
        </tr>
        <tr>
            <td><img src="./img/img-6.png" alt="image"></td>
            <td><img src="./img/img-7.png" alt="image"></td>
        </tr>
        <tr>
            <td><img src="./img/img-8.png" alt="image"></td>
            <td><img src="./img/img-9.png" alt="image"></td>
        </tr>
        <tr>
            <td><img src="./img/img-10.png" alt="image"></td>
            <td></td>
        </tr>
    </tbody>
</table>

<table>
    <tbody>
        <tr>
            <td>
                <video src="https://github.com/user-attachments/assets/83dd70f5-1c63-42df-8b5a-a719e35895d7" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
            <td>
                <video src="https://github.com/user-attachments/assets/27a6722f-51b5-48ce-958c-c0bf1d65b2b1" controls preload>
                    Your browser does not support the video tag.
                </video>
            </td>
        </tr>
    </tbody>
</table>

---

## Full Description

### Problem
Human speech is diverse, influenced by accents, dialects, and noisy environments. Traditional systems often fail to achieve consistent accuracy, creating barriers for non-native speakers, regional dialects, and noisy workplaces.

### Solution
- **Hybrid Model:** CNNs for audio feature extraction + LSTMs for contextual sequence modeling.
- **Noise Filtering:** Dedicated algorithm to separate speech from noise, enhancing clarity.
- **Adaptability:** Trained on multilingual datasets with diverse accents and noise conditions.
- **Performance:** Achieves real-time transcription with low word error rate.

### Process
1. **Data Collection & Preprocessing:** Gathered large, diverse dataset and normalized audio.
2. **Feature Extraction:** Converted speech signals into spectrograms using STFT.
3. **Sequence Modeling:** LSTMs processed extracted features for phrase-level accuracy.
4. **Noise Reduction:** Custom algorithm learned from labeled datasets of speech vs. noise.
5. **Training & Optimization:** Applied cross-entropy loss, dropout, and batch normalization.

---

## Achievements
- **Accuracy:** Reduced WER to **5%** (vs industry average 10–15%).
- **Speed:** Real-time transcription with avg. **0.5 sec** per sentence.
- **Noise Handling:** Improved signal-to-noise ratio by **20 dB**.
- **Accent Adaptability:** Effective across **20+ accents and dialects**.
- **Dataset:** Trained on **1,000+ hours** of multilingual, noise-varied speech.

---

## Future Improvements & Scope
- **Transformer Architectures:** For improved contextual understanding.
- **Advanced Noise Cancellation:** Deep neural networks for adaptive filtering.
- **Personalization:** Online learning for adapting to user voices.
- **Mobile Optimization:** Energy-efficient deployment on IoT and mobile devices.
- **Global Expansion:** Support for more languages and dialects.
- **Privacy:** Federated learning for secure and private voice data processing.

---

## References
1. [Deep Speech: Scaling up end-to-end speech recognition](https://arxiv.org/abs/1412.5567)
2. [WaveNet: A Generative Model for Raw Audio](https://arxiv.org/abs/1609.03499)
3. [SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition](https://arxiv.org/abs/1904.08779)
4. [Attention Is All You Need](https://arxiv.org/abs/1706.03762)
5. [Improving Noise Robustness of ASR via Parallel Data and Teacher-student Learning](https://arxiv.org/abs/1904.04100)
6. [Listening to Each Other: A Multilingual Dataset for Distant Speech Recognition](https://arxiv.org/abs/2006.13979)
7. [Federated Learning for Mobile Keyboard Prediction](https://arxiv.org/abs/1811.03604)  
