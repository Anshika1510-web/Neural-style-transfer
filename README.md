### **Neural Style Transfer**

#### **What We Did**
We implemented **Neural Style Transfer (NST)** to blend the **content of one image** (e.g., a photo) with the **style of another image** (e.g., a painting), creating a visually artistic output.

#### **Models Used**
* **Pretrained VGG19** (from Keras):
  * A convolutional neural network trained on ImageNet.
  * Used as a feature extractor.
  * Content and style features are extracted from specific layers of VGG19.

**Features**:
* Load content and style images
* Use VGG19 for feature extraction
* Extract content and style features
* Compute style using Gram matrices
* Combine content and style loss
* Optimize image using gradient descent
* Generate and save stylized output image
