NAME:B.KISHORE BABU

ID:700752976

VIEDEO LINK:https://vimeo.com/manage/videos/1072719837/ac38a0a2d6?studio_recording=true&record_session_id=8b70bbdc-7679-45fe-adfc-bd2212393c09&studio_feedback=true

# NN-ASSIGNMENT_3

Q1: Basic Autoencoder (Image Reconstruction)
What: Learns to compress and reconstruct input images.

Why: Dimensionality reduction and feature learning.

How:

Encoder: 784 → 32

Decoder: 32 → 784

Trained using binary cross-entropy.

Try different latent sizes (16, 64) to see effect on reconstruction quality.

Q2: Denoising Autoencoder
What: Learns to remove noise from corrupted images.

Why: Robust feature learning, useful in image cleaning.

How:

Add Gaussian noise to inputs.

Train to output clean images.

Compare: Denoising outperforms basic autoencoder on noisy inputs.

Use case: Medical image denoising (e.g., MRI scans).

Q3: Text Generation with RNN (LSTM)
What: Predicts the next character in a sequence.

Why: Used in chatbots, story or code generation.

How:

LSTM processes character sequences.

Generates text one character at a time.

Temperature: Controls randomness of generated text.

Low = predictable, High = creative/random.

Q4: Sentiment Classification with RNN
What: Classifies text as positive or negative sentiment.

Why: Understand user feedback, automate review analysis.

How:

Use IMDB dataset.

Preprocess text, train LSTM classifier.

Metrics: Accuracy, Precision, Recall, F1-score.

Tradeoff: Precision vs. recall depends on use-case importance (e.g., false positives vs. false negatives).

