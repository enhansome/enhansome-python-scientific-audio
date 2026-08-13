# Awesome Python for Scientific Audio with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 495,212 | 🐛 100 | 📅 2026-06-30 [![Build Status](https://github.com/faroit/awesome-python-scientific-audio/workflows/CI/badge.svg)](https://github.com/faroit/awesome-python-scientific-audio/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush) ⭐ 1,707 | 🐛 35 | 📅 2026-06-11

The aim of this repository is to create a comprehensive, curated list of python software/tools related and used for scientific research in audio/music applications.

## Contents

* [Audio Related Packages](#audio-related-packages)
  * [Read/Write](#read-write)
  * [Transformations - General DSP](#transformations---general-dsp)
  * [Feature extraction](#feature-extraction)
  * [Data augmentation](#data-augmentation)
  * [Speech Processing](#speech-processing)
  * [Environmental Sounds](#environmenta)
  * [Perceptial Models - Auditory Models](#perceptial-models---auditory-models)
  * [Source Separation](#source-separation)
  * [Music Information Retrieval](#music-information-retrieval)
  * [Deep Learning](#deep-learning)
  * [Symbolic Music - MIDI - Musicology](#symbolic-music---midi---musicology)
  * [Realtime applications](#realtime-applications)
  * [Web - Audio](#web-audio)
  * [Audio related APIs and Datasets](#audio-related-apis-and-datasets)
  * [Wrappers for Audio Plugins](#wrappers-for-audio-plugins)
* [Tutorials](#tutorials)
* [Books](#books)
* [Scientific Paper](#scientific-papers)
* [Other Resources](#other-resources)
* [Related lists](#related-lists)
* [Contributing](#contributing)
* [License](#license)

## Audio Related Packages

* Total number of packages: 67

#### Read-Write

* [pyAV](http://docs.mikeboers.com/pyav/) [:octocat:](https://github.com/mikeboers/PyAV) ⭐ 3,264 | 🐛 4 | 🌐 Python | 📅 2026-08-12 - PyAV is a Pythonic binding for FFmpeg or Libav.
* [mutagen](https://mutagen.readthedocs.io/) [:octocat:](https://github.com/quodlibet/mutagen) ⭐ 1,946 | 🐛 119 | 🌐 Python | 📅 2026-07-13 [:package:](https://pypi.python.org/pypi/mutagen) - Reads and writes all kind of audio metadata for various formats.
* [tinytag](https://github.com/devsnd/tinytag) ⭐ 831 | 🐛 6 | 🌐 Python | 📅 2026-08-10 [:octocat:](https://github.com/devsnd/tinytag) ⭐ 831 | 🐛 6 | 🌐 Python | 📅 2026-08-10 [:package:](https://pypi.python.org/pypi/tinytag/) - reading music meta data of MP3, OGG, FLAC and Wave files.
* [audiolazy](https://github.com/danilobellini/audiolazy) ⭐ 715 | 🐛 14 | 🌐 Python | 📅 2022-04-30 [:octocat:](https://github.com/danilobellini/audiolazy) ⭐ 715 | 🐛 14 | 🌐 Python | 📅 2022-04-30 [:package:](https://pypi.python.org/pypi/audiolazy/) - Expressive Digital Signal Processing (DSP) package for Python.
* [pySox](https://github.com/rabitt/pysox) ⭐ 541 | 🐛 35 | 🌐 Python | 📅 2025-03-26 [:octocat:](https://github.com/rabitt/pysox) ⭐ 541 | 🐛 35 | 🌐 Python | 📅 2025-03-26 [:package:](https://pypi.python.org/pypi/pysox/) - Wrapper for sox.
* [audioread](https://github.com/beetbox/audioread) ⭐ 538 | 🐛 45 | 🌐 Python | 📅 2026-04-09 [:octocat:](https://github.com/beetbox/audioread) ⭐ 538 | 🐛 45 | 🌐 Python | 📅 2026-04-09 [:package:](https://pypi.python.org/pypi/audioread/) - Cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.
* [pyfar](https://pyfar.readthedocs.io) [:octocat:](https://github.com/pyfar/pyfar) ⭐ 135 | 🐛 82 | 🌐 Python | 📅 2026-08-10 [:package:](https://pypi.org/project/pyfar/) - Read audio files, SOFA files, and COMSOL data with the [pyfar.io](https://pyfar.readthedocs.io/en/stable/modules/pyfar.io.html) module.
* [stempeg](https://github.com/faroit/stempeg) ⭐ 107 | 🐛 7 | 🌐 Python | 📅 2025-10-31 [:octocat:](https://github.com/faroit/stempeg) ⭐ 107 | 🐛 7 | 🌐 Python | 📅 2025-10-31 [:package:](https://pypi.python.org/pypi/stempeg/) - read/write of STEMS multistream audio.
* [(Py)Soundfile](http://pysoundfile.readthedocs.io/) [:octocat:](https://github.com/bastibe/PySoundFile) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2020-05-26 [:package:](https://pypi.python.org/pypi/SoundFile) - Library based on libsndfile, CFFI, and NumPy.

#### Transformations - General DSP

* [pydub](http://pydub.com) [:octocat:](https://github.com/jiaaro/pydub) ⭐ 9,788 | 🐛 421 | 🌐 Python | 📅 2026-03-19 [:package:](https://pypi.python.org/pypi/mdct) - Manipulate audio with a simple and easy high level interface.
* [matchering](https://github.com/sergree/matchering) ⭐ 2,605 | 🐛 34 | 🌐 Python | 📅 2026-07-08 [:octocat:](https://github.com/sergree/matchering) ⭐ 2,605 | 🐛 34 | 🌐 Python | 📅 2026-07-08 [:package:](https://pypi.org/project/matchering/) - Automated reference audio mastering.
* [PyWavelets](http://pywavelets.readthedocs.io) [:octocat:](https://github.com/PyWavelets/pywt) ⭐ 2,397 | 🐛 89 | 🌐 Python | 📅 2026-08-13 [:package:](https://pypi.python.org/pypi/PyWavelets) - Discrete Wavelet Transform in Python.
* [pyroomacoustics](https://github.com/LCAV/pyroomacoustics) ⭐ 1,925 | 🐛 20 | 🌐 Python | 📅 2026-07-17 [:octocat:](https://github.com/LCAV/pyroomacoustics) ⭐ 1,925 | 🐛 20 | 🌐 Python | 📅 2026-07-17 [:package:](https://pypi.python.org/pypi/pyroomacoustics) - Room Acoustics Simulation (RIR generator)
* [acoustics](http://python-acoustics.github.io/python-acoustics/) [:octocat:](https://github.com/python-acoustics/python-acoustics/) ⚠️ Archived [:package:](https://pypi.python.org/pypi/acoustics) - useful tools for acousticians.
* [pyFFTW](http://pyfftw.github.io/pyFFTW/) [:octocat:](https://github.com/pyFFTW/pyFFTW) ⭐ 423 | 🐛 60 | 🌐 Python | 📅 2025-12-03 [:package:](https://pypi.python.org/pypi/pyFFTW/) - Wrapper for FFTW(3).
* [pytftb](http://tftb.nongnu.org) [:octocat:](https://github.com/scikit-signal/pytftb) ⭐ 283 | 🐛 28 | 🌐 Python | 📅 2025-01-28 - Implementation of the MATLAB Time-Frequency Toolbox.
* [Resampy](http://resampy.readthedocs.io) [:octocat:](https://github.com/bmcfee/resampy) ⭐ 282 | 🐛 5 | 🌐 Python | 📅 2024-09-30 [:package:](https://pypi.python.org/pypi/resampy) - Sample rate conversion.
* [AudioTK](https://github.com/mbrucher/AudioTK) ⚠️ Archived [:octocat:](https://github.com/mbrucher/AudioTK) ⚠️ Archived - DSP filter toolbox (lots of filters).
* [Gammatone](https://github.com/detly/gammatone) ⚠️ Archived [:octocat:](https://github.com/detly/gammatone) ⚠️ Archived - Gammatone filterbank implementation.
* [PyRubberband](https://github.com/bmcfee/pyrubberband) ⭐ 217 | 🐛 4 | 🌐 Python | 📅 2024-09-30 [:octocat:](https://github.com/bmcfee/pyrubberband) ⭐ 217 | 🐛 4 | 🌐 Python | 📅 2024-09-30 [:package:](https://pypi.python.org/pypi/pyrubberband/) - Wrapper for [rubberband](http://breakfastquay.com/rubberband/) to do pitch-shifting and time-stretching.
* [pyfar](https://pyfar.readthedocs.io) [:octocat:](https://github.com/pyfar/pyfar) ⭐ 135 | 🐛 82 | 🌐 Python | 📅 2026-08-10 [:package:](https://pypi.org/project/pyfar/) - Perform general DSP and filtering tailored for acoustic signals with the [pyfar.dsp](https://pyfar.readthedocs.io/en/stable/modules/pyfar.dsp.html) module.
* [NSGT](https://grrrr.org/research/software/nsgt/) [:octocat:](https://github.com/grrrr/nsgt) ⭐ 107 | 🐛 10 | 🌐 Python | 📅 2023-11-10 [:package:](https://pypi.python.org/pypi/nsgt) - Non-stationary gabor transform, constant-q.
* [sound\_field\_analysis](https://appliedacousticschalmers.github.io/sound_field_analysis-py/) [:octocat:](https://github.com/AppliedAcousticsChalmers/sound_field_analysis-py) ⭐ 106 | 🐛 8 | 🌐 Python | 📅 2022-12-29 [:package:](https://pypi.org/project/sound-field-analysis/) - Analyze, visualize and process sound field data recorded by spherical microphone arrays.
* [AudioTSM](https://audiotsm.readthedocs.io/) [:octocat:](https://github.com/Muges/audiotsm) ⭐ 92 | 🐛 4 | 🌐 Python | 📅 2017-10-07 [:package:](https://pypi.python.org/pypi/audiotsm/) - real-time audio time-scale modification procedures.
* [SFS-Python](http://www.sfstoolbox.org) [:octocat:](https://github.com/sfstoolbox/sfs-python) ⭐ 73 | 🐛 20 | 🌐 Python | 📅 2025-12-14 [:package:](https://pypi.python.org/pypi/sfs/) - Sound Field Synthesis Toolbox.
* [MDCT](https://github.com/nils-werner/mdct) ⭐ 55 | 🐛 4 | 🌐 Python | 📅 2022-06-18 [:octocat:](https://github.com/nils-werner/mdct) ⭐ 55 | 🐛 4 | 🌐 Python | 📅 2022-06-18 [:package:](https://pypi.python.org/pypi/mdct) - MDCT transform.
* [STFT](http://stft.readthedocs.io) [:octocat:](https://github.com/nils-werner/stft) ⭐ 48 | 🐛 3 | 🌐 Python | 📅 2024-12-22 [:package:](https://pypi.python.org/pypi/stft) - Standalone package for Short-Time Fourier Transform.

#### Feature extraction

* [aubio](http://aubio.org/) [:octocat:](https://github.com/aubio/aubio) ⭐ 3,744 | 🐛 157 | 🌐 C | 📅 2026-04-10 [:package:](https://pypi.python.org/pypi/aubio) - Feature extractor, written in C, Python interface.
* [essentia](http://essentia.upf.edu) [:octocat:](https://github.com/MTG/essentia) ⭐ 3,690 | 🐛 425 | 🌐 C++ | 📅 2026-07-22 - Music related low level and high level feature extractor, C++ based, includes Python bindings.
* [audioFlux](https://github.com/libAudioFlux/audioFlux) ⭐ 3,350 | 🐛 16 | 🌐 C | 📅 2026-03-06 [:octocat:](https://github.com/libAudioFlux/audioFlux) ⭐ 3,350 | 🐛 16 | 🌐 C | 📅 2026-03-06 [:package:](https://pypi.python.org/pypi/audioflux) - A library for audio and music analysis, feature extraction.
* [python\_speech\_features](https://github.com/jameslyons/python_speech_features) ⭐ 2,423 | 🐛 25 | 🌐 Python | 📅 2021-10-20 [:octocat:](https://github.com/jameslyons/python_speech_features) ⭐ 2,423 | 🐛 25 | 🌐 Python | 📅 2021-10-20 [:package:](https://pypi.python.org/pypi/python_speech_features) - Common speech features for ASR.
* [speechpy](https://github.com/astorfi/speechpy) ⭐ 883 | 🐛 2 | 🌐 Python | 📅 2024-12-15 [:octocat:](https://github.com/astorfi/speechpy) ⭐ 883 | 🐛 2 | 🌐 Python | 📅 2024-12-15 [:package:](https://pypi.python.org/pypi/speechpy) - Library for Speech Processing and Recognition, mostly feature extraction for now.
* [audiolazy](https://github.com/danilobellini/audiolazy) ⭐ 715 | 🐛 14 | 🌐 Python | 📅 2022-04-30 [:octocat:](https://github.com/danilobellini/audiolazy) ⭐ 715 | 🐛 14 | 🌐 Python | 📅 2022-04-30 [:package:](https://pypi.python.org/pypi/audiolazy/) - Realtime Audio Processing lib, general purpose.
* [spafe](https://github.com/SuperKogito/spafe) ⭐ 484 | 🐛 1 | 🌐 Python | 📅 2025-03-20 [:octocat:](https://github.com/SuperKogito/spafe) ⭐ 484 | 🐛 1 | 🌐 Python | 📅 2025-03-20 [:package:](https://pypi.org/project/spafe/) - Python library for features extraction from audio files.
* [pyYAAFE](https://github.com/Yaafe/Yaafe) ⭐ 248 | 🐛 17 | 🌐 C++ | 📅 2021-06-21 [:octocat:](https://github.com/Yaafe/Yaafe) ⭐ 248 | 🐛 17 | 🌐 C++ | 📅 2021-06-21 - Python bindings for YAAFE feature extractor.

#### Data augmentation

* [audiomentations](https://github.com/iver56/audiomentations) ⭐ 2,308 | 🐛 59 | 🌐 Python | 📅 2026-04-13 [:octocat:](https://github.com/iver56/audiomentations) ⭐ 2,308 | 🐛 59 | 🌐 Python | 📅 2026-04-13 [:package:](https://pypi.org/project/audiomentations/) -  Audio Data Augmentation.
* [muda](https://muda.readthedocs.io/en/latest/) [:octocat:](https://github.com/bmcfee/muda) ⭐ 238 | 🐛 9 | 🌐 Python | 📅 2021-05-03 [:package:](https://pypi.python.org/pypi/muda) -  Musical Data Augmentation.
* [pydiogment](https://github.com/SuperKogito/pydiogment) ⭐ 84 | 🐛 13 | 🌐 Python | 📅 2023-07-06 [:octocat:](https://github.com/SuperKogito/pydiogment) ⭐ 84 | 🐛 13 | 🌐 Python | 📅 2023-07-06 [:package:](https://pypi.org/project/pydiogment/) -  Audio Data Augmentation.

#### Speech Processing

* [deepspeech](https://github.com/mozilla/DeepSpeech) ⚠️ Archived [:octocat:](https://github.com/mozilla/DeepSpeech) ⚠️ Archived [:package:](https://pypi.org/project/deepspeech/) - Pretrained automatic speech recognition.
* [pyannote.audio](https://github.com/pyannote/pyannote-audio) ⭐ 10,410 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2026-08-04 [:octocat:](https://github.com/pyannote/pyannote-audio) ⭐ 10,410 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2026-08-04 [:package:](https://pypi.org/project/pyannote-audio/) - Neural building blocks for speaker diarization.
* [SpeechRecognition](https://github.com/Uberi/speech_recognition) ⭐ 8,983 | 🐛 311 | 🌐 Python | 📅 2026-07-31 [:octocat:](https://github.com/Uberi/speech_recognition) ⭐ 8,983 | 🐛 311 | 🌐 Python | 📅 2026-07-31 [:package:](https://pypi.python.org/pypi/SpeechRecognition/) -  Wrapper for several ASR engines and APIs, online and offline.
* [pyAudioAnalysis](https://github.com/tyiannak/pyAudioAnalysis) ⭐ 6,253 | 🐛 205 | 🌐 Python | 📅 2025-08-04² [:octocat:](https://github.com/tyiannak/pyAudioAnalysis) ⭐ 6,253 | 🐛 205 | 🌐 Python | 📅 2025-08-04 [:package:](https://pypi.python.org/pypi/pyAudioAnalysis/) - Feature Extraction, Classification, Diarization.
* [aeneas](https://www.readbeyond.it/aeneas/) [:octocat:](https://github.com/readbeyond/aeneas/) ⭐ 2,860 | 🐛 37 | 🌐 Python | 📅 2026-07-25 [:package:](https://pypi.python.org/pypi/aeneas/) - Forced aligner, based on MFCC+DTW, 35+ languages.
* [py-webrtcvad](https://github.com/wiseman/py-webrtcvad) ⭐ 2,497 | 🐛 51 | 🌐 C | 📅 2024-07-04 [:octocat:](https://github.com/wiseman/py-webrtcvad) ⭐ 2,497 | 🐛 51 | 🌐 C | 📅 2024-07-04 [:package:](https://pypi.python.org/pypi/webrtcvad/) -  Interface to the WebRTC Voice Activity Detector.
* [Montreal Forced Aligner](https://montrealcorpustools.github.io/Montreal-Forced-Aligner/) [:octocat:](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) ⭐ 1,866 | 🐛 289 | 🌐 Python | 📅 2026-08-07 - Forced aligner, based on Kaldi (HMM), English (others can be trained).
* [gentle](https://github.com/lowerquality/gentle) ⭐ 1,706 | 🐛 171 | 🌐 Python | 📅 2026-07-24 [:octocat:](https://github.com/lowerquality/gentle) ⭐ 1,706 | 🐛 171 | 🌐 Python | 📅 2026-07-24 - Forced-aligner built on Kaldi.
* [Parselmouth](https://github.com/YannickJadoul/Parselmouth) ⭐ 1,278 | 🐛 24 | 🌐 C++ | 📅 2026-07-21 [:octocat:](https://github.com/YannickJadoul/Parselmouth) ⭐ 1,278 | 🐛 24 | 🌐 C++ | 📅 2026-07-21 [:package:](https://pypi.org/project/praat-parselmouth/) - Python interface to the [Praat](http://www.praat.org) phonetics and speech analysis, synthesis, and manipulation software.
* [PyWorldVocoder](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) ⭐ 790 | 🐛 24 | 🌐 Cython | 📅 2025-01-21 [:octocat:](https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder) ⭐ 790 | 🐛 24 | 🌐 Cython | 📅 2025-01-21 - Wrapper for Morise's World Vocoder.
* [pypesq](https://github.com/vBaiCai/python-pesq) ⭐ 410 | 🐛 7 | 🌐 Python | 📅 2025-07-16 [:octocat:](https://github.com/vBaiCai/python-pesq) ⭐ 410 | 🐛 7 | 🌐 Python | 📅 2025-07-16 - Wrapper for the PESQ score calculation.
* [pystoi](https://github.com/mpariente/pystoi) ⭐ 360 | 🐛 6 | 🌐 MATLAB | 📅 2023-12-29 [:octocat:](https://github.com/mpariente/pystoi) ⭐ 360 | 🐛 6 | 🌐 MATLAB | 📅 2023-12-29 [:package:](https://pypi.org/project/pystoi) - Short Term Objective Intelligibility measure (STOI).
* [persephone](https://persephone.readthedocs.io/en/latest/) [:octocat:](https://github.com/persephone-tools/persephone) ⭐ 159 | 🐛 91 | 🌐 Python | 📅 2023-04-18 [:package:](https://pypi.org/project/persephone/) - Automatic phoneme transcription tool.
* [visqol-python](https://github.com/talker93/visqol-python) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-30 [:octocat:](https://github.com/talker93/visqol-python) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-05-30 [:package:](https://pypi.org/project/visqol-python/) - Port of Google's ViSQOL audio/speech quality metric (MOS-LQO) that installs without Bazel.
* [SIDEKIT](http://lium.univ-lemans.fr/sidekit/) [:package:](https://pypi.python.org/pypi/SIDEKIT/) - Speaker and Language recognition.

#### Environmental Sounds

* [sed\_eval](http://tut-arg.github.io/sed_eval) [:octocat:](https://github.com/TUT-ARG/sed_eval) ⭐ 161 | 🐛 6 | 🌐 Python | 📅 2024-06-12 [:package:](https://pypi.org/project/sed_eval/) - Evaluation toolbox for Sound Event Detection

#### Perceptial Models - Auditory Models

* [Brian2](http://briansimulator.org/) [:octocat:](https://github.com/brian-team/brian2) ⭐ 1,213 | 🐛 205 | 🌐 Python | 📅 2026-08-01 [:package:](https://pypi.python.org/pypi/Brian2) - Spiking neural networks simulator, includes cochlea model.
* [pyloudnorm](https://www.christiansteinmetz.com/projects-blog/pyloudnorm) [:octocat:](https://github.com/csteinmetz1/pyloudnorm) ⭐ 780 | 🐛 14 | 🌐 Python | 📅 2026-01-04 - Audio loudness meter and normalization, implements ITU-R BS.1770-4.
* [cochlea](https://github.com/mrkrd/cochlea) ⭐ 129 | 🐛 1 | 🌐 Python | 📅 2024-07-14 [:octocat:](https://github.com/mrkrd/cochlea) ⭐ 129 | 🐛 1 | 🌐 Python | 📅 2024-07-14 [:package:](https://pypi.python.org/pypi/cochlea/) - Inner ear models.
* [Sound Field Synthesis Toolbox](http://www.sfstoolbox.org) [:octocat:](https://github.com/sfstoolbox/sfs-python) ⭐ 73 | 🐛 20 | 🌐 Python | 📅 2025-12-14 [:package:](https://pypi.python.org/pypi/sfs/) - Sound Field Synthesis Toolbox.
* [Loudness](https://github.com/deeuu/loudness) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2019-08-08 [:octocat:](https://github.com/deeuu/loudness) ⭐ 40 | 🐛 0 | 🌐 C++ | 📅 2019-08-08 - Perceived loudness, includes Zwicker, Moore/Glasberg model.

#### Source Separation

* [NUSSL](https://interactiveaudiolab.github.io/project/nussl.html) [:octocat:](https://github.com/interactiveaudiolab/nussl) ⚠️ Archived [:package:](https://pypi.python.org/pypi/nussl) - Holistic source separation framework including DSP methods and deep learning methods.
* [NIMFA](http://nimfa.biolab.si) [:octocat:](https://github.com/marinkaz/nimfa) ⭐ 560 | 🐛 15 | 🌐 Python | 📅 2021-02-12 [:package:](https://pypi.python.org/pypi/nimfa) - Several flavors of non-negative-matrix factorization.
* [NTFLib](https://github.com/stitchfix/NTFLib) ⚠️ Archived [:octocat:](https://github.com/stitchfix/NTFLib) ⚠️ Archived - Sparse Beta-Divergence Tensor Factorization.
* [commonfate](https://github.com/aliutkus/commonfate) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2020-02-27 [:octocat:](https://github.com/aliutkus/commonfate) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2020-02-27 [:package:](https://pypi.python.org/pypi/commonfate) - Common Fate Model and Transform.

#### Music Information Retrieval

* [librosa](http://librosa.github.io/librosa/) [:octocat:](https://github.com/librosa/librosa) ⭐ 8,556 | 🐛 46 | 🌐 Python | 📅 2026-08-11 [:package:](https://pypi.python.org/pypi/librosa) - General audio and music analysis.
* [Madmom](https://madmom.readthedocs.io/en/latest/) [:octocat:](https://github.com/CPJKU/madmom) ⭐ 1,694 | 🐛 81 | 🌐 Python | 📅 2026-03-20 [:package:](https://pypi.python.org/pypi/madmom) - MIR packages with strong focus on beat detection, onset detection and chord recognition.
* [mir\_eval](http://craffel.github.io/mir_eval/) [:octocat:](https://github.com/craffel/mir_eval) ⭐ 710 | 🐛 37 | 🌐 Python | 📅 2026-02-19 [:package:](https://pypi.python.org/pypi/mir_eval) - Common scores for various MIR tasks. Also includes bss\_eval implementation.
* [msaf](http://pythonhosted.org/msaf/) [:octocat:](https://github.com/urinieto/msaf) ⭐ 555 | 🐛 21 | 🌐 Python | 📅 2026-05-13 [:package:](https://pypi.python.org/pypi/msaf) - Music Structure Analysis Framework.
* [chord-detection](https://github.com/sevagh/chord-detection) ⭐ 145 | 🐛 0 | 🌐 Python | 📅 2023-07-14 [:octocat:](https://github.com/sevagh/chord-detection) ⭐ 145 | 🐛 0 | 🌐 Python | 📅 2023-07-14 - Algorithms for chord detection and key estimation.
* [Catchy](https://github.com/jvbalen/catchy) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2016-12-22 [:octocat:](https://github.com/jvbalen/catchy) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2016-12-22 - Corpus Analysis Tools for Computational Hook Discovery.

#### Deep Learning

* [TorchAudio](https://github.com/pytorch/audio) ⭐ 2,922 | 🐛 338 | 🌐 Python | 📅 2026-08-13 [:octocat:](https://github.com/pytorch/audio) ⭐ 2,922 | 🐛 338 | 🌐 Python | 📅 2026-08-13 - PyTorch Audio Loaders
* [nnAudio](https://github.com/KinWaiCheuk/nnAudio) ⭐ 1,129 | 🐛 21 | 🌐 Python | 📅 2026-05-21 [:octocat:](https://github.com/KinWaiCheuk/nnAudio) ⭐ 1,129 | 🐛 21 | 🌐 Python | 📅 2026-05-21 [:package:](https://pypi.org/project/nnAudio/) - Accelerated audio processing using 1D convolution networks in PyTorch.
* [Kapre](https://github.com/keunwoochoi/kapre) ⭐ 947 | 🐛 16 | 🌐 Python | 📅 2026-05-17 [:octocat:](https://github.com/keunwoochoi/kapre) ⭐ 947 | 🐛 16 | 🌐 Python | 📅 2026-05-17 [:package:](https://pypi.python.org/pypi/kapre) - Keras Audio Preprocessors

#### Symbolic Music - MIDI - Musicology

* [Music21](http://web.mit.edu/music21/) [:octocat:](https://github.com/cuthbertLab/music21) ⭐ 2,555 | 🐛 155 | 🌐 Python | 📅 2026-08-12 [:package:](https://pypi.python.org/pypi/music21) - Toolkit for Computer-Aided Musicology.
* [Mido](https://mido.readthedocs.io/en/latest/) [:octocat:](https://github.com/olemb/mido) ⭐ 1,631 | 🐛 119 | 🌐 Python | 📅 2026-06-27 [:package:](https://pypi.python.org/pypi/mido) - Realtime MIDI wrapper.
* [Pretty-MIDI](http://craffel.github.io/pretty-midi/) [:octocat:](https://github.com/craffel/pretty-midi) ⭐ 1,035 | 🐛 30 | 🌐 Jupyter Notebook | 📅 2026-02-18 [:package:](https://pypi.python.org/pypi/pretty-midi) - Utility functions for handling MIDI data in a nice/intuitive way.
* [mingus](https://github.com/bspaans/python-mingus) ⭐ 927 | 🐛 65 | 🌐 Python | 📅 2024-04-21 [:octocat:](https://github.com/bspaans/python-mingus) ⭐ 927 | 🐛 65 | 🌐 Python | 📅 2024-04-21 [:package:](https://pypi.org/project/mingus) - Advanced music theory and notation package with MIDI file and playback support.

#### Realtime applications

* [PYO](http://ajaxsoundstudio.com/software/pyo/) [:octocat:](https://github.com/belangeo/pyo) ⭐ 1,448 | 🐛 32 | 🌐 Python | 📅 2026-07-20 - Realtime audio dsp engine.
* [python-sounddevice](https://github.com/spatialaudio/python-sounddevice) ⭐ 1,265 | 🐛 205 | 🌐 Python | 📅 2026-07-24 [:octocat:](http://python-sounddevice.readthedocs.io) [:package:](https://pypi.python.org/pypi/sounddevice) - PortAudio wrapper providing realtime audio I/O with NumPy.
* [Jupylet](https://github.com/nir/jupylet) ⭐ 252 | 🐛 10 | 🌐 Python | 📅 2024-01-22 [:octocat:](https://github.com/nir/jupylet) ⭐ 252 | 🐛 10 | 🌐 Python | 📅 2024-01-22 - Subtractive, additive, FM, and sample-based sound synthesis.
* [ReTiSAR](https://github.com/AppliedAcousticsChalmers/ReTiSAR) ⭐ 81 | 🐛 0 | 🌐 Python | 📅 2023-12-02 [:octocat:](https://github.com/AppliedAcousticsChalmers/ReTiSAR) ⭐ 81 | 🐛 0 | 🌐 Python | 📅 2023-12-02 - Binaural rendering of streamed or IR-based high-order spherical microphone array signals.

#### Web Audio

* [TimeSide (Beta)](https://github.com/Parisson/TimeSide/tree/dev) ⭐ 394 | 🐛 33 | 🌐 Python | 📅 2024-10-14 [:octocat:](https://github.com/Parisson/TimeSide/tree/dev) ⭐ 394 | 🐛 33 | 🌐 Python | 📅 2024-10-14 - high level audio analysis, imaging, transcoding, streaming and labelling.

#### Audio Dataset and Dataloaders

* [Youtube-Downloader](http://rg3.github.io/youtube-dl/) [:octocat:](https://github.com/rg3/youtube-dl) ⭐ 140,952 | 🐛 4,129 | 🌐 Python | 📅 2026-02-19 [:package:](https://pypi.python.org/pypi/youtube_dl) - Download youtube videos (and the audio).
* [beets](http://beets.io/) [:octocat:](https://github.com/beetbox/beets) ⭐ 15,534 | 🐛 707 | 🌐 Python | 📅 2026-08-13 [:package:](https://pypi.python.org/pypi/beets) - Music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
* [mirdata](https://mirdata.readthedocs.io/en/latest/) [:octocat:](https://github.com/mir-dataset-loaders/mirdata) ⭐ 412 | 🐛 66 | 🌐 Python | 📅 2026-07-14 [:package:](https://pypi.python.org/pypi/mirdata) - Common loaders for Music Information Retrieval (MIR) datasets.
* [medleydb](http://medleydb.readthedocs.io) [:octocat:](https://github.com/marl/medleydb) ⭐ 216 | 🐛 22 | 🌐 Python | 📅 2024-05-29 - Parse [medleydb](http://medleydb.weebly.com/) audio + annotations.
* [musdb](http://dsdtools.readthedocs.io) [:octocat:](https://github.com/sigsep/sigsep-mus-db) ⭐ 202 | 🐛 4 | 🌐 Python | 📅 2025-05-28 [:package:](https://pypi.python.org/pypi/musdb) - Parse and process the MUSDB18 dataset.
* [audiomate](https://github.com/ynop/audiomate) ⭐ 139 | 🐛 28 | 🌐 Python | 📅 2023-07-06 [:octocat:](https://github.com/ynop/audiomate) ⭐ 139 | 🐛 28 | 🌐 Python | 📅 2023-07-06 [:package:](https://pypi.python.org/pypi/audiomate/) - Loading different types of audio datasets.
* [Soundcloud API](https://github.com/soundcloud/soundcloud-python) ⭐ 112 | 🐛 1 | 🌐 Python | 📅 2025-10-28 [:octocat:](https://github.com/soundcloud/soundcloud-python) ⭐ 112 | 🐛 1 | 🌐 Python | 📅 2025-10-28 [:package:](https://pypi.python.org/pypi/soundcloud) - Wrapper for [Soundcloud API](https://developers.soundcloud.com/).

#### Wrappers for Audio Plugins

* [VamPy Host](https://code.soundsoftware.ac.uk/projects/vampy-host) [:package:](https://pypi.python.org/pypi/vamp) - Interface compiled vamp plugins.

## Tutorials

* [Whirlwind Tour Of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) [:octocat:](https://github.com/jakevdp/WhirlwindTourOfPython) ⭐ 4,027 | 🐛 25 | 🌐 Jupyter Notebook | 📅 2024-01-31 - fast-paced introduction to Python essentials, aimed at researchers and developers.
* [Introduction to Numpy and Scipy](http://www.scipy-lectures.org/index.html) [:octocat:](https://github.com/scipy-lectures/scipy-lecture-notes) ⭐ 3,217 | 🐛 32 | 🌐 Python | 📅 2026-05-01 - Highly recommended tutorial, covers large parts of the scientific Python ecosystem.
* [MIR Notebooks](http://musicinformationretrieval.com/) [:octocat:](https://github.com/stevetjoa/stanford-mir) ⭐ 1,278 | 🐛 19 | 🌐 Jupyter Notebook | 📅 2026-05-19 - collection of instructional iPython Notebooks for music information retrieval (MIR).
* [Selected Topics in Audio Signal Processing](https://github.com/spatialaudio/selected-topics-in-audio-signal-processing-exercises) ⭐ 69 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-10-11 - Exercises as iPython notebooks.
* [Live-coding a music synthesizer](https://www.youtube.com/watch?v=SSyQ0kRHzis) Live-coding video showing how to use the SoundDevice library to reproduce realistic sounds. [Code](https://github.com/cool-RR/python_synthesizer) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2022-01-25.
* [Numpy for MATLAB® Users](https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html) - Short overview of equivalent python functions for switchers.
* [pyfar examples](https://pyfar-gallery.readthedocs.io/en/latest/examples_gallery.html) - Introduction and examples for the python packages for acoustics research (pyfar).

## Books

* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) ⭐ 49,592 | 🐛 228 | 🌐 Jupyter Notebook | 📅 2024-06-26 - Jake Vanderplas, Excellent Book and accompanying tutorial notebooks.
* [Fundamentals of Music Processing](https://www.audiolabs-erlangen.de/fau/professor/mueller/bookFMP) - Meinard Müller, comes with Python exercises.

## Scientific Papers

* [Python for audio signal processing](http://eprints.maynoothuniversity.ie/4115/1/40.pdf) - John C. Glover, Victor Lazzarini and Joseph Timoney, Linux Audio Conference 2011.
* [librosa: Audio and Music Signal Analysis in Python](http://conference.scipy.org/proceedings/scipy2015/pdfs/brian_mcfee.pdf), [Video](https://www.youtube.com/watch?v=MhOdbtPhbLU) - Brian McFee, Colin Raffel, Dawen Liang, Daniel P.W. Ellis, Matt McVicar, Eric Battenberg, Oriol Nieto, Scipy 2015.
* [pyannote.audio: neural building blocks for speaker diarization](https://arxiv.org/abs/1911.01255), [Video](https://www.youtube.com/watch?v=37R_R82lfwA) - Hervé Bredin, Ruiqing Yin, Juan Manuel Coria, Gregory Gelly, Pavel Korshunov, Marvin Lavechin, Diego Fustes, Hadrien Titeux, Wassim Bouaziz, Marie-Philippe Gill, ICASSP 2020.

## Other Resources

* [Coursera Course](https://www.coursera.org/learn/audio-signal-processing) -  Audio Signal Processing, Python based course from UPF of Barcelona and Stanford University.
* [Digital Signal Processing Course](http://dsp-nbsphinx.readthedocs.io/en/nbsphinx-experiment/index.html) - Masters Course Material (University of Rostock) with many Python examples.
* [Slack Channel](https://mircommunity.slack.com) - Music Information Retrieval Community.

## Related lists

There is already [PythonInMusic](https://wiki.python.org/moin/PythonInMusic) but it is not up to date and includes too many packages of special interest that are mostly not relevant for scientific applications. [Awesome-Python](https://github.com/vinta/awesome-python) ⭐ 313,713 | 🐛 26 | 🌐 Python | 📅 2026-08-05 is large curated list of python packages. However, the audio section is very small.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.

I will keep some pull requests open if I'm not sure whether those libraries are awesome, you could vote for them by adding 👍 to them.

## License

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
