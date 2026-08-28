# Oracles and Oracle Algorithms: Slides

*Module 4 slide deck, converted from PowerPoint.* Each slide is shown as an image; the text beneath it is extracted from the slide for search and reference.

Source deck: `M4_Oracles_and_Oracle_Algorithms.pptx`

---

## Slide 1: Oracles and Oracle Algorithms

![Slide 1](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide1.PNG)

> The Labyrinth Guards

---

## Slide 2: What is an Oracle?

![Slide 2](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide2.PNG)

> Imagine and omniscient being with which you can speak
> You ask it a question
> It gives you an honest and correct answer
> You go about your day confident on what the Oracle said
> An oracle is a person or thing considered to provide insight, wise counsel or prophetic predictions, most notably including precognition of the future, inspired by deities. -- Wikipedia

---

## Slide 3: Lost in a Labyrinth

![Slide 3](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide3.PNG)

> One Door Leads to Freedom, the other, more labyrinth
> The doors are entangled, opening one locks the other eternally.
> Two guards, one in front of each door: One always lies, the other always truthful
> After one question, the guards will leave. What do you ask them?

---

## Slide 4: The Guards are Oracles

![Slide 4](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide4.PNG)

---

## Slide 5: Bringing the Question to Quantum

![Slide 5](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide5.PNG)

---

## Slide 6: Turning the Guards into a Quantum Circuit

![Slide 6](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide6.PNG)

---

## Slide 7: Example Questions in Quantum States

![Slide 7](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide7.PNG)

---

## Slide 8: Possible Answers

![Slide 8](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide8.PNG)

---

## Slide 9: First Step: Map out the input/output relation

![Slide 9](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide9.PNG)

---

## Slide 10: Full Map

![Slide 10](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide10.PNG)

---

## Slide 11: Mapping the Qubits to Names

![Slide 11](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide11.PNG)

---

## Slide 12: What’s happening?

![Slide 12](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide12.PNG)

---

## Slide 13: Implementation of the Circuit

![Slide 13](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide13.PNG)

---

## Slide 14: What if the Liar Guard was the other one?

![Slide 14](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide14.PNG)

---

## Slide 15

![Slide 15](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide15.PNG)

---

## Slide 16: What if the Green Door leads to Freedom?

![Slide 16](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide16.PNG)

> Notice that if we want to represent the other encoding as the answer, we put X gates around the control gate on our control-NOT gate.

---

## Slide 17: What our goal is

![Slide 17](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide17.PNG)

> We do not know which of these oracles (which guard is the liar) we have
> How do we encode our input so that no matter which guard is lying, the answer will provide us the correct answer?
> First, let’s think of what question we can use to make sure that the guard will absolutely tell us yes, no matter if he lies or if he tells the truth, if the door we are asking about leads to freedom. And no otherwise.

---

## Slide 18: Lost in a Labyrinth (Again)

![Slide 18](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide18.PNG)

> One Door Leads to Freedom, the other, more labyrinth
> The doors are entangled, opening one locks the other eternally.
> Two guards, one in front of each door: One always lies, the other always truthful
> After one question, the guards will leave. What do you ask them?

---

## Slide 19: So, What is the question?

![Slide 19](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide19.PNG)

> “Does the truthful guard stand in front of the door to freedom?”
> What happens when the guard answers yes?
> If the guard is truthful, then he is standing in front of the door to freedom
> If the guard is the liar, then he is lying, so the truthful guard is not standing in front of the door, he is.
> What happens when the guard answers no?
> If the guard is truthful, then he is standing in front of the dead end
> If the guard is the liar, then the truthful guard is standing in front of the door to freedom, so he is in front of the dead end

---

## Slide 20: How do we implement this?

![Slide 20](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide20.PNG)

> The key to the question was linking the truthful guard to the door to freedom.
> This indicates that we need to entangle the guard we ask with the door and liberty.
> Notice that upon getting yes/no we do not know anything about the guards, we only learn about the door.

---

## Slide 21: What kind of entanglement should it be?

![Slide 21](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide21.PNG)

> Note that a question like “Would the truth guard say the blue door leads to freedom”?
> There is something inherent with how the guards are situated near the door.
> If you ask the guard on the left you are asking about the blue door, if you ask the guard on the right you are asking about the green door.

---

## Slide 22: The circuit with Encoding and Example Oracle

![Slide 22](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide22.PNG)

> Input Encoding
> Example Oracle

---

## Slide 23: How do we know it works?

![Slide 23](M4_Oracles_and_Oracle_Algorithms_slides_images/Slide23.PNG)

---
