# Grover’s Algorithm: Slides

*Module 5 slide deck, converted from PowerPoint.* Each slide is shown as an image; the text beneath it is extracted from the slide for search and reference.

Source deck: `M5_Grovers_Algorithm.pptx`

---

## Slide 1: Grover’s Algorithm

![Slide 1](M5_Grovers_Algorithm_slides_images/Slide1.PNG)

---

## Slide 2: Classical Database Search

![Slide 2](M5_Grovers_Algorithm_slides_images/Slide2.PNG)

---

## Slide 3: Grover’s Algorithm

![Slide 3](M5_Grovers_Algorithm_slides_images/Slide3.PNG)

---

## Slide 4: Caveats

![Slide 4](M5_Grovers_Algorithm_slides_images/Slide4.PNG)

---

## Slide 5: So why Grover’s now?

![Slide 5](M5_Grovers_Algorithm_slides_images/Slide5.PNG)

> Today,
> Grover’s is best implemented on more easily definable functions
> Examples include
> Hash functions
> Block-chain
> AES encryption

---

## Slide 6: Part 1: the Oracle

![Slide 6](M5_Grovers_Algorithm_slides_images/Slide6.PNG)

---

## Slide 7: Oracle marked_states

![Slide 7](M5_Grovers_Algorithm_slides_images/Slide7.PNG)

> Oracles were introduced last lecture
> This oracle has marked_states
> marked_states represent the “answer”
> Examples of marked_states inputs include:
> [“011”, “101”]
> [“11001”, “10100”, “10010”]
> These marked states represent the inputs for which Grover’s will say yes

---

## Slide 8: Oracle Unitary Definition

![Slide 8](M5_Grovers_Algorithm_slides_images/Slide8.PNG)

---

## Slide 9: Part 2: Grover’s Technique

![Slide 9](M5_Grovers_Algorithm_slides_images/Slide9.PNG)

---

## Slide 10: Amplitude Amplification

![Slide 10](M5_Grovers_Algorithm_slides_images/Slide10.PNG)

---

## Slide 11: Grover Operator

![Slide 11](M5_Grovers_Algorithm_slides_images/Slide11.PNG)

---

## Slide 12: Homework: IBM Grover’s Exercise

![Slide 12](M5_Grovers_Algorithm_slides_images/Slide12.PNG)

> Experiment with different numbers of marked_strings and lengths.
> Reflect on how Grover’s diffusion operator is working
> Reflect on why Grover’s Algorithm requires fault tolerance (error correction), beyond what today’s NISQ computers can provide
> Do NOT run Grover’s algorithm on real quantum hardware for the homework assignment
> The cost is very expensive

---
