# 🧠 GenAI Code Review & Bug Explanation Tool

A lightweight **GenAI-powered code review system** that detects common bugs, explains issues in simple terms, and suggests fixes using **Hugging Face models**. The project is **100% free**, runs entirely on **Google Colab**, and includes an interactive **Gradio UI**.

---

## 🚀 Features

* 🐞 Detects common runtime and logical bugs
* 🧠 Generates human-readable explanations
* 🛠 Suggests corrected code and best practices
* 🎛 Interactive Gradio-based web interface
* ⚡ Runs on Google Colab with GPU support
* 🔓 No paid APIs or API keys required

---

## 🧰 Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* CodeGen-350M-mono (free, open-source model)
* Gradio
* Google Colab

---


## 🛠 Installation & Setup

### Option 1: Run on Google Colab (Recommended)

1. Open Google Colab
2. Upload all project files or clone the repo
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Run:
   Run each cell in notebook



### Option 2: Run Locally

> Requires Python 3.9+ and sufficient RAM

```bash
git clone https://github.com/your-username/GenAI-Code-Review-Tool.git
cd GenAI-Code-Review-Tool
pip install -r requirements.txt
python GenAI.py
```

---

## 🧪 Sample Input

```python
def divide(a, b):
    return a / b

print(divide(10, 0))
```

## ✅ Sample Output

* **Bug Detected**
* Explanation of division by zero
* Corrected code with error handling
* Best practice suggestions

---

## 🖥 Gradio UI

The project includes an interactive UI where users can:

* Paste code
* Click submit
* Instantly receive bug status and explanation

---

## 📌Bullet

> Developed a GenAI-powered code review and bug explanation system using Hugging Face and PyTorch, capable of detecting errors, suggesting fixes, and explaining code logic, fully implemented on Google Colab.

---

## 🔮 Future Improvements

* Support for multiple programming languages
* Advanced static analysis integration
* Larger instruction-tuned models
* Exportable PDF reports

---

## 📄 License

This project is open-source and free to use for educational purposes.

---

⭐ If you find this project helpful, consider starring the repository!

## 🖼️ Screenshots

### 🔹 Code Review Interface
![Gradio UI](Screenshots/Screenshot (125).png)

### 🔹 Bug Explanation Output
![Explanation Output](Screenshots/Screenshot (126).png)
