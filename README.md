# 🦙 Fine-Tune Llama 2 Model

A simple Python project to fine-tune a Llama 2 model on your custom dataset.

---

## 📂 Project Structure

```plaintext
📂 finetune_llama2_model
├── train.py            # Main script to fine-tune the Llama 2 model
├── requirements.txt    # Python dependencies
├── README.md           # Project documentation
├── data/               # Folder to store your training data
└── checkpoints/        # Folder where fine-tuned model checkpoints will be saved



## ⚙️ Installation & Setup

### 1️⃣ Clone the repo

```bash
git clone https://github.com/krgau020/finetune_llama2_model.git
cd finetune_llama2_model


# 2️⃣ Create a virtual environment (optional but recommended)
python -m venv venv

# Activate it:
# Linux/Mac
source venv/bin/activate

# OR Windows
venv\Scripts\activate

# 3️⃣ Install dependencies
pip install -r requirements.txt


🚀 Usage

# Run the training script
python train.py

# Make sure your training data is inside the `data/` folder.
# The script will fine-tune the Llama 2 model using your dataset and save checkpoints in `checkpoints/`.
