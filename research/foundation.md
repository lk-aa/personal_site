---
layout: research_detail
title: Foundation Models
area_id: foundation
permalink: /foundation/
description: "We develop foundation models that enable robots to understand and interact with their environment through scalable learning from diverse datasets."
content_groups:
  - title: "Vision-Language-Action Models"
    image: "/images/research_img/1.jpg"
    caption: "Our VLA model architecture connecting visual observations, language instructions, and robot actions."
    description: |
      We develop <span class="highlight-red">vision-language-action models</span> that ground language instructions in visual perception and robot control. <span class="emphasis">These models</span> enable robots to <span class="highlight-blue">follow natural language commands</span> and perform complex tasks in unstructured environments.

      Our approach leverages <span class="emphasis">large-scale pre-training</span> on diverse datasets, allowing the models to transfer knowledge across different robotic platforms and task domains.
      
      The models demonstrate <span class="highlight-blue">strong zero-shot generalization capabilities</span>, requiring minimal task-specific fine-tuning for new applications.

  - title: "Multi-Modal Representation Learning"
    image: "/images/research_img/2.jpg"
    caption: "Learning joint representations from visual, tactile, and proprioceptive inputs."
    description: |
      We investigate methods for learning unified representations from multiple sensory modalities including vision, touch, and proprioception. This enables robots to build comprehensive world models that capture different aspects of physical interaction.Our representation learning framework allows robots to reason about object properties, physical dynamics, and task constraints in a shared latent space.<span class="emphasis">These representations have shown improved performance on manipulation tasks that require delicate contact and force control.</span>

  - title: "Scalable Imitation Learning"
    image: "/images/research_img/3.jpg"
    caption: "Learning from diverse human demonstrations at scale."
    description: |
      We develop scalable imitation learning algorithms that can leverage large datasets of human demonstrations. Our methods address distribution shift and compounding errors through adversarial training and dynamics-aware regularization.

      The framework supports learning from suboptimal demonstrations and can incorporate human feedback for continuous improvement.

      We've demonstrated these methods on complex manipulation tasks requiring long-horizon planning and precise control.
---