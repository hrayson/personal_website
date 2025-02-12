---
title: 'Multi-scale parameterization of neural rhythmicity with lagged Hilbert autocoherence'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Siqi Zhang
- Maciej J Szul
- Sotirios Papadopoulos
- Alice Massera
- Holly Rayson
- James J Bonaiuto

# Author notes (optional)


date: "2024-12-09T00:00:00Z"
doi: "https://doi.org/10.1101/2024.12.05.627017"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: bioRxiv
publication_short: bioRxiv

abstract: Analysis of neural activity in different frequency bands is ubiquitous in systems and cognitive neuroscience. Recent analytical breakthroughs and theoretical developments rely on phase maintenance of oscillatory signals without considering whether or not this assumption is met. Lagged (auto)coherence, the coherence between a signal and itself at increasing temporal delays, has been proposed as a way to quantify the rhythmicity, or periodicity, of a signal. However, current Fourier-based lagged autocoherence algorithms suffer from poor spectral accuracy and resolution, aliasing effects that become more pronounced at higher frequencies, and conflation with amplitude covariation, especially in frequency ranges in which the signal power is low. We introduce a continuous lagged autocoherence metric, lagged Hilbert autocoherence, that addresses these shortcomings by using multiplication in the frequency domain for precise bandpass filtering, instantaneous analytic signals via the Hilbert transform, and thresholding using the amplitude covariation of surrogate data generated by an autoregressive model. We show that this version of lagged coherence yields vastly higher spectral accuracy and resolution than lagged Fourier autocoherence, and that this unlocks additional, increasingly fine-grained applications. This includes examination of 1) frequency-specific differences in rhythmicity between conditions, 2) changes in signal rhythmicity during learning, and 3) the relationship between frequency-specific rhythmicity and behavior, trial-by-trial. Lagged Hilbert autocoherence thus offers a significant toolset advancement for analysis of neurophysiological rhythmicity.

# Summary. An optional shortened abstract.


tags: [lagged coherence, rhythmicity, oscillations, beta bursts, periodic activity, spectral parameterization, alpha, mu, infant, EEG, MEG]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- beta_bursts

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.

---


