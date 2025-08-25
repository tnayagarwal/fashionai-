Gen AI Fashion Recommender
📌 Overview

This project implements a Generative AI-based fashion recommender system that:

Detects clothing items in images using YOLOv8

Extracts embeddings with OpenAI CLIP

Generates text captions with Transformers (T5)

Provides outfit recommendations based on available wardrobe items

The project is implemented in Jupyter Notebook and uses datasets from Myntra Fashion Product Dataset (via Kaggle).

🛠 Features

Object Detection: Uses YOLOv8 to detect garments in user-uploaded images

Image Cropping: Automatically extracts detected clothing items

Embeddings with CLIP: Generates semantic embeddings for fashion items

Caption Generation: Describes clothing items in natural language

Recommendation Engine: Suggests outfits based on detected wardrobe items

📂 Project Structure

gen_ai_project.ipynb → Main notebook containing the entire pipeline

runs/detect/ → YOLOv8 prediction outputs

dataset/ → Myntra Fashion Product Dataset (downloaded via Kaggle)

uploads/ → User-uploaded fashion images

🖼 Example Workflow

Upload an outfit image

YOLOv8 detects & crops clothing items

CLIP embeddings + T5 captions describe the garments

The system recommends complementary outfits
