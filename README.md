# Hand-Written-Captcha-Solver
**Overview**
It is a machine learning program designed to convert handwritten captchas composed of English letters and emojis mapped to numbers into plain text. The program utilizes deep learning techniques and convolutional neural networks, leveraging the power of OpenCV for image processing.

**Captcha Components**

**Emojis:**
Captchas may contain the following emojis, each mapped to a specific number: <br>

Checkmark (✅): 1 <br>
Cloud (☁️): 2     <br>
Croissant (🥐): 3   <br>
Heart (❤️): 4     <br>
Laugh (😄): 5     <br>
Smile (😊): 6      <br>
Sun (☀️): 7   <br>

**Letters**: Captchas may contain the following English letters:

A, B, C, D, E, F, G, H, J, K, M, P, R, T, W, X, b, e, h

**Approach**  <br>   

**Segmentation of Letters**   <br>
* Utilized OpenCV for image processing, leveraging the img_cleaning() and read() segmentation code.  <br>
* Successfully extracts letters from both digital and handwritten images.    <br>
* Proficient in reading colorful images, handling shadows, and mitigating the impact of noise.   <br>

**Model Training**
- Utilizes Convolutional Neural Networks (CNN) for efficient learning.   <br>
- Evaluate loss using Cross Entropy loss, ensuring effective model training.  <br>
- Optimizes model parameters using the Adam optimizer for rapid convergence.   <br>
