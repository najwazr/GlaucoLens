# GlaucoLens 👁️
*A Simple Web App for Early Glaucoma Detection*

GlaucoLens is an interactive web-based application designed to detect glaucoma from retinal fundus images. Built with [Streamlit](https://streamlit.io/) as the frontend and powered by a pre-trained deep learning model, the app allows users to upload a retina fundus image and receive an instant prediction:
- Normal (no glaucoma detected)  
- Glaucoma (possible signs of glaucoma, consult an ophthalmologist)  

in addition to prediction, the app provides:
- Vision Simulator: slider-based tool to simulate mild, moderate, and severe glaucoma vision. lets users visualize how glaucoma affects vision over time.  
- Learn About Glaucoma: quick and basic information about glaucoma, explains common risk factors. this includes an interactive self-check tool where users can enter details like age, family history, diabetes, and blood pressure to estimate their risk level, along with prevention tips and awareness content.

this project uses a pre-trained model from:  
🔗 [golden-panther/glaucoma-detector](https://github.com/golden-panther/glaucoma-detector)

**NOTE**
- this project currently runs only on **localhost** (not deployed online).
- it only works with fundus retina images. if you upload random images (e.g., landscapes, faces, objects), the app will still classify them as “Normal” instead of rejecting them.
- ⚠️ **this project is a student prototype and not a medical diagnostic tool. predictions are for educational purposes only. for real diagnosis, please consult an ophthalmologist.**
