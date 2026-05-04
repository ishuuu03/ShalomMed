
# Tech Stack

**Frontend**
- HTML5
- CSS3
- JavaScript

**Machine Learning**

- TensorFlow.js
- Teachable Machine

**Backend**

- Python (Flask server running locally)

# Features
**Frontend**

- Runs locally at http://127.0.0.1:5000/
- Upload a picture directly from the browser
- Displays potential diagnosis and treatment options

**AI trained Analysis**

Uses a trained TensorFlow.js Teachable Machine model
Classifies images into categories such as:
- Ringworm
- Athlete’s Foot
- Keratosis Pilaris
- Not Infected
- Not Skin / Unclear
  
# Overview
**Challenge**
My model was getting confused with things with external things on the skin like nailpolish, tattoos, which was a challenge on my end. However, I realized that I have to train my model to identify these things and bypass them. I also ran into some issues with deployment because of how my files were arranged, but after some file changing it worked. 

**Improve**
This is just a base model and I would love to add more things for my model to identify. I need a bigger sample size and a way to also identify things that aren't included. 
  
