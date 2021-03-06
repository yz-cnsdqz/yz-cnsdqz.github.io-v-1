---
title: "PLACE: Proximity Learning of Articulation and Contact in 3D Environments"
collection: publications
permalink: /publication/PLACE
date: 2020-11-25
venue: '3DV'
paperurl: 'https://ps.is.mpg.de/publications/place-3dv-2020'
---
![alt text](../images/PLACE-teaser.png)<!-- .element height="20%" width="20%" -->

__Abstract:__ 
High fidelity digital 3D environments have been proposed in recent years, however, it remains extremely challenging to automatically equip such environment with realistic human bodies. Existing work utilizes images, depth or semantic maps to represent the scene, and parametric human models to represent 3D bodies. While being straight-forward, their generated human-scene interactions often lack of naturalness and physical plausibility. Our key observation is that humans interact with the world through body-scene contact. To synthesize realistic human-scene interactions, it is essential to effectively represent the physical contact and proximity between the body and the world. To that end, we propose a novel interaction generation method, named PLACE(Proximity Learning of Articulation and Contact in 3D Environments), which explicitly models the proximity between the human body and the 3D scene around it. Specifically, given a set of basis points on a scene mesh, we leverage a conditional variational autoencoder to synthesize the minimum distances from the basis points to the human body surface. The generated proximal relationship exhibits which region of the scene is in contact with the person. Furthermore, based on such synthesized proximity, we are able to effectively obtain expressive 3D human bodies that interact with the 3D scene naturally. Our perceptual study shows that PLACE significantly improves the state-of-the-art method, approaching the realism of real human-scene interaction. We believe our method makes an important step towards the fully automatic synthesis of realistic 3D human bodies in 3D scenes. The code and model are available for research at https://sanweiliti.github.io/PLACE/PLACE.html

[Project Page](https://sanweiliti.github.io/PLACE/PLACE.html)



