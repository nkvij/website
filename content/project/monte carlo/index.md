---
title: Second Order Correlations in Blinking Quantum Dots
summary: Used monte carlo simulation to calculate the second order correlation function for quantum dots.
date: "2020-07-15T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Image Courtesy - PRB 84, 125317 (2011)
  focal_point: Smart

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
math: true
---

The blinking behaviour of quantum dots (QD) has been widely experimentally observed and studied. In this project, I collaborated with Uthkarsh Gupta, my lab mate, to assist him in the development of a monte carlo based algorithm to model the blinking behaviour of QDs in the time domain. We consider a six-state approximation to the quantum dot as shown in the above figure. For a given state, the exciton in the QD spends certain time in it before it can undergo various transitions, as shown in the above figure, to its accessible states with different rates. We assign each transition a probability proportional to its rate and decide the next transition for the QD using a random number and the time spent in that state using another separate random number. For certain transition, a photon in emitted. Thus the state dynamics gives us the photon emissions in the time domain. Using the photon emission array and a beam splitter module, we calculate the second order correlation function $ g^{(2)} (\tau)$ and characterize its behaviour by varying the various system parameters.