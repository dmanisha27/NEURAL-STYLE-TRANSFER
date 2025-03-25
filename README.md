# Neural Style Transfer  

This project applies artistic style transfer using a pre-trained model from TensorFlow Hub. It takes a content image and a style image as inputs and generates a stylized image.  

## Installation  

1. **Clone the repository** (if applicable):  
   ```sh
   git clone <repo_url>
   cd <repo_name>
   ```  
2. **Install dependencies**:  
   ```sh
   pip install -r requirements.txt
   ```  

## Dependencies  
The required Python libraries are:  
- TensorFlow  
- TensorFlow Hub  
- NumPy  
- Matplotlib  
- Pillow  

## Usage  

1. Place the content image (`content.jpeg`) and style image (`style.jpeg`) in the project directory.  
2. Run the script:  
   ```sh
   python nst.py
   ```  
3. The stylized image will be saved in the `output` directory and displayed.  

## Output  
The generated image applies the artistic style from `style.jpeg` to `content.jpeg`.  

## Example  
- **Content Image**: The base image to be transformed.  
- **Style Image**: The artistic style to be applied.  
- **Generated Output**: A fusion of both images.  

## Notes  
- Ensure TensorFlow is installed and compatible with your system.  
- Modify image paths in `nst.py` as needed.  

