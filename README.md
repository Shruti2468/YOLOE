# YOLOE
## Implementing YOLOE Visual Prompt Segmentation

### YOLOE Visual Prompt Implementation

This project demonstrates how to use **YOLOE (You Only Look Once Enhanced)** for **visual prompt–based object detection and segmentation**.  
Instead of training a model from labeled data, YOLOE allows users to define objects of interest by drawing bounding boxes — these serve as *visual prompts* that guide the model to find similar objects in new images.

---

### Features
- Interactive bounding box creation using **jupyter_bbox_widget**
- Visual prompt–guided detection and segmentation using **YOLOE**
- Supports both **source** and **target** image workflows
- Visual result annotation with **Supervision** and **PIL**

---

### Workflow
1. Draw bounding boxes on the source image to define example objects.
2. Use these boxes as visual prompts for YOLOE inference.
3. Run YOLOE on the target image to detect similar objects.
4. Visualize the output with bounding boxes and labels.


### Drawing the bounding boxes:
<img width="471" height="263" alt="Screenshot 2025-10-31 142739" src="https://github.com/user-attachments/assets/1eec89e2-577a-4234-b3a1-89421108ea2c" />

### Final output on new image 
<img width="615" height="222" alt="Screenshot 2025-10-31 142748" src="https://github.com/user-attachments/assets/56be04de-781c-4d24-9e7c-160f35216ddb" />
