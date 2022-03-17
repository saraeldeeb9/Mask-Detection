# streamlit-face-mask-detector
A simple [Streamlit](https://www.streamlit.io/) frontend for face mask detection in images using a pre-trained [Keras](https://keras.io/) CNN model + [OpenCV](https://opencv.org/) and model interpretability.  

## Deep Learning Explanation
Once an image has been uploaded, the classification happens automatically. It is then possible to apply some interpretability methods for neural network understanding. The UI presents two buttons to apply the following methods:
- Grad CAM: it visualizes how parts of the input image affect a CNN output by looking into the activation maps.
- Occlusion Sensitivity: it visualizes how parts of the input image affect a CNN confidence by iteratively occluding parts.
## Usage
After cloning this repository you need to create a virtual environment and install the application dependencies  
```pip install -r requirements.txt```  
Then you can execute the application through the *streamlit* command  
```streamlit run st_face_mask_detector_expl.py```  
  

