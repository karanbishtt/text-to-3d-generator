# Text-to-3D Generator
This project is a Python-based prototype built in Google Colab that allows users to generate 3D models from simple text prompts using OpenAI's [Shap-E](https://github.com/openai/shap-e) framework.

## Features
- Generate a 3D object (.obj) from a simple text input.
- Visualize the generated 3D mesh directly in Colab.
- Save the output(.obj) file for external 3D software or printing.
- Uses OpenAI's Shap-E model for text-to-3D generation.

## Project Structure
photo_to_3d/
├── inputs/         # Input text
├── outputs/        # Generated 3D model (.obj)
└── TEXT_TO_3D.ipynb # Main Google Colab notebook

## How to Use
1. Clone or open this repo in Google Colab.
2. Run the cells to install dependencies and setup the Shap-E model.
3. Enter your desired text prompt when asked.
4. View and save the resulting 3D model.

## Technologies Used
- Python
- Google Colab
- PyTorch
- Trimesh, Matplotlib
- OpenAI Shap-E

## License
This project is licensed under the [MIT License](LICENSE).

## Author
Karan Singh Bisht  
2nd Year B.Tech CSE, Amity University Rajasthan
