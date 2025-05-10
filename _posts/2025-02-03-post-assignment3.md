---
title: "Assignment 3"
last_modified_at: 2025-02-03
categories:
  - Blog
tags:
  - Assignments
---

# **Paris in Focus: Clustering the Elements of this City**

**Asma Al Murr**  
Professor David Wrisley  
DAAH Assignment 3 – *Visual AI and Culture*  
May 11, 2025

---

## **Introduction**

In this final assignment, I set out to explore how visual culture—specifically, the city of Paris—could be computationally analyzed using tools like Orange Data Mining and DV Explorer. My custom-built image corpus, composed of 125 visuals across six categories (Cafés, Landmarks, Parks, Rivers, Graffiti, and Night), was intentionally curated to challenge how machine vision systems classify and interpret urban imagery. Rather than relying on pre-trained datasets like COCO, my goal was to push algorithms to interpret a dataset rich in ambiguity, atmosphere, and personal perspective.

![folders.png](/assets/images/folders.png)
---

## **Corpus Building**

### **Corpus Summary**

My dataset, *Paris in Focus: Clustering the Elements of this City*, included approximately 20–25 images per category. These categories were selected not for their object recognition clarity, but for their cultural and environmental relevance to Paris. Some images came from my personal photography, taken during a recent trip to Paris, while others were sourced online. This diverse composition allowed the project to reflect Paris’s multifaceted character while also introducing visual variability that could test the limits of machine vision.

![orange.png](/assets/images/orange.png)

### **Automation Process**

To compile the images, I used the **Image Downloader** browser extension, enabling bulk downloads from platforms like:

- [Instagram](https://www.instagram.com)
- [Shutterstock](https://www.shutterstock.com)
- [Getty Images](https://www.gettyimages.com)

Automation accelerated the image-gathering process and introduced randomness into the dataset—an important factor for cultural exploration. I ensured compliance with assignment guidelines by filtering out human faces and organizing the images into labeled folders to match each of the six categories.

![imgdownloader.png](/assets/images/imgdownloader.png)

---

## **Prompting Strategy and Personal Influence**

The inspiration behind this corpus emerged during my recent visit to Paris. Wandering the city at different times—especially during golden hour and late at night—gave me a deeper appreciation for its layered aesthetic identity. Some of my own photographs captured these moments, while others were found online using deliberately vague prompts.

> **Prompts I used included:**  
> “Paris at night”  
> “Graffiti art in Paris”  
> “Paris cafés”  
> “Eiffel Tower at night”  
> “Spiral staircase Paris”  
> “Seine river view”  

![searchprompt.png](/assets/images/searchprompt.png)

This open-ended prompting strategy allowed the algorithmic tools I used to “surprise” me with their interpretation of the visual data, embracing an exploratory methodology similar to what Arnold and Tilton describe as *distant viewing*.

---

## **Orange Data Mining: Image Plot and Clustering**

![preset.png](/assets/images/preset.png)

### **Initial Observations**

After loading my corpus into the pre-set Orange Data Mining workflow (`images2.ows`), I tested a few pre-trained models: Inceptionv3, SqueezeNet, and VGG. Inceptionv3 consistently performed best, organizing landmarks, graffiti, rivers, and café imagery into clearly separated clusters. However, the algorithm struggled with two categories: **Parks** and **Night**, likely due to their diffuse textures and more abstract lighting properties.

> “The network was clustering images based more on formal visual traits than on thematic content”  
> — *Observation from image plot*

![plotcorpus.png](/assets/images/plotcorpus.png)

Each quadrant of the image plot reflected dominant visual features:
- **Top Left:** Café imagery (warm tones, interiors)
- **Top Right:** Parks (greens and soft shapes)
- **Top Middle:** Rivers (reflections and water texture)
- **Bottom Right:** Landmarks (symmetry, vertical structures)
- **Bottom Left:** Graffiti (bold lines and saturation)

### **Hierarchical Clustering and Visual Tensions**

![corpusH.png](/assets/images/corpusH.png)

To investigate further, I used **hierarchical clustering with Ward linkage**. A meaningful pattern emerged: the Seine River photos formed a clean, precise cluster, likely due to blue hues and horizontal reflections. However, one graffiti image was misclassified into the river group.

![Foldermistake.png](/assets/images/Foldermistake.png)

> “This moment reinforced how machine learning models don't think in strict categories—they interpret visual proximity and dominant features.”

The mistake made sense upon review: the graffiti was painted on a wall above the Seine. The visible river behind the art confused the algorithm—but that confusion revealed a key truth about machine interpretation.
 

Here is the actual image for context:

![river.jpg](/assets/images/river.jpg)

---

## **Confusion Matrix and Category Accuracy**

With the dataset now organized into subfolders by category, I generated a confusion matrix using Inceptionv3. Results were strong overall:

![CM.png](/assets/images/CM.png)


### **High Accuracy Clusters**
- **Café:** 21/21 (Perfect)
- **Graffiti:** 17/20
- **Landmarks:** 20/21
- **Night:** 20/22
- **Parks:** 16/20
- **Rivers:** 20/21

> “The degree to which these algorithms do not see, or else see 'incorrectly,' should temper such an approach.” — *Arnold & Tilton, p. 140*

### **Key Takeaways**
- Categories with strong **color, texture, or symmetry** (e.g., café interiors, bridges) fared best.
- **Night** and **Parks** were less accurately classified due to visual ambiguity.
- Machine vision evaluates *what images look like*, not *what they mean*—a reminder of the semiotic gap between human and algorithmic perception.

---

## **Critical Reflection: Reading and Being Read**

Leonardo Impett and Fabian Offert write:  
> “In reading a corpus of visual culture through a neural network, are you always also doing the reverse?”

This idea resonated strongly throughout the assignment. While I approached the corpus with the intent to analyze Paris, the machine simultaneously analyzed—and reshaped—my perception of the city. The Eiffel Tower at night, a powerful cultural icon in my mind, was reduced to “a clock tower towering over a city at night.” I expected machines to reflect my vision, but in fact, they refracted it—emphasizing contrast, structure, and form over symbolism.

---

## **Multimodal Captioning with DV Explorer**

I used DV Explorer’s image captioning model (Section 5.2) to run a self-designed experiment using four images of increasing complexity: easy, medium, and hard.

### **Easy Image**
> *Caption:* “A piece of food on a sidewalk”  
> **Actual:** Me holding a croissant  
The model missed both the croissant’s identity and the human interaction, reducing a cultural moment to a generic object.

![food.png](/assets/images/food.png)

### **Medium Image #1**
> *Caption:* “A boat traveling down a river next to a city”  
> **Actual:** Boat on the Seine  
This was highly accurate, proving the model’s strength with typical urban environments.

![water.png](/assets/images/water.png)

### **Medium Image #2**
> *Caption:* “A clock tower towering over a city at night”  
> **Actual:** Eiffel Tower at night  
Though it got the time of day right, the caption misrecognized one of the world’s most famous structures. This exposed the model’s limitations with cultural context.

![tower.png](/assets/images/tower.png)

### **Hard Image**
> *Caption:* “A series of photos showing a stairway with a large staircase”  
> **Actual:** Spiral staircase with graffiti, shot from below  
While imperfect, the model recognized the staircase and hinted at graffiti as “photos”—a surprisingly rich misreading that acknowledged artistic presence.

![stair.png](/assets/images/stair.png)

---

## **Guided Questions Reflection**

**1. Pre-computed vs. Custom Embeddings**  
DV Explorer performed better with stock datasets due to their generic composition. My custom set challenged it with personal, culturally rich content, resulting in unexpected but revealing captioning gaps.

**2. Missed Cultural Features**  
The model ignored the Eiffel Tower’s cultural significance and misread graffiti art. As Arnold and Tilton state, “visual culture... makes meaning differently than text, and these differences must be accounted for” (p. 11).

**3. Reading the Network**  
This wasn’t just me reading results—it was me interpreting *how* the machine sees. Its outputs reflected a logic rooted in pixel gradients and lighting, not in cultural literacy.

---

## **Conclusion**

This assignment revealed both the possibilities and limitations of machine vision in the humanities. By constructing a personally curated corpus and interrogating how it was interpreted by neural networks, I experienced firsthand the semiotic divide between human intention and algorithmic vision. The tools didn’t just cluster or caption—they offered a reflective surface, showing me the gaps between my view of Paris and the machine’s. As Arnold and Tilton remind us, distant viewing is “not just about what computers can see, but about how we train them to look—and what we miss in the process” (p. 7).

---

## **Citations**

- Arnold, Taylor, and Lauren Tilton. *Distant Viewing: Computational Exploration of Digital Images*. MIT Press, 2023. [MIT Press Link](https://mitpress.mit.edu/9780262546133/distant-viewing/)

- Impett, Leonardo, and Fabian Offert. “There Is a Digital Art History.” *Visual Resources*, vol. 38, no. 2, 2022, pp. 186–209. [DOI](https://doi.org/10.1080/01973762.2024.2362466)


