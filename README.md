# ECE-4332-final-project

GC-11: Radar Acoustic Speech Enhancement (RASE)

Organized by: Andy W. H. Khong, Patrick A. Naylor, Zhi-Wei Tan, V. G. Reju, Ritesh C. Tewari, and Ruotong Ding

Submission Link: https://cmsworkshops.com/ICASSP2026/Papers/Submission.asp?Type=Challenge&ID=11

Challenge website: https://rase-challenge.github.io/RASE2026-Challenge/

GitHub for Python Training / Template: https://github.com/RASE-Challenge/challenge_baseline2026

Data Set Google Drive Link: ...

Title: RASE 2026: Radar Acoustic Speech Enhancement

Short description: RASE is an ICASSP 2026 Grand Challenge on the recovery of clear, full-bandwidth speech from noisy, band-limited signals acquired by a frequency-modulated continuous-wave (FMCW) mmWave radar that is based on the radar vibrometry principle. This speech acquisition approach is particularly effective where microphone technology suffer from signal degradation due to acoustic noise or distance. A key advantage of the FMCW radar vibrometry is range-gating, where the radar isolates reflections based on distance to capture speech and suppress interferers selectively. Unlike microphones, radar can also acquire speech through barriers. The organizers will provide a curated dataset and baseline code, allowing the broader speech community to participate without any prior radar expertise.

The challenge features two difficulty levels: (1) direct sensing from a loudspeaker diaphragm (controlled, strong vibrations), and (2) indirect sensing from a nearby secondary surface (aluminium foil). In both cases, the source is inside a glass-walled room while the radar is deployed outside the enclosure. Participants will receive paired .wav files, radar-derived signals and corresponding clean references, for training and development of neural network model; the test set will be released later. To lower the barrier to entry, raw radar signals will not be shared. Submissions are ranked using well-established enhancement and intelligibility metrics (ESTOI, normalized PESQ, normalized DNSMOS, and MFCC cosine similarity), aggregated across difficulty levels. To promote reproducibility and fairness, participating teams must train the neural network models on the provided data from scratch (no external data or pre-trained models) and submit code and environment details. Top-scoring teams will be invited to present their methods at ICASSP 2026.
