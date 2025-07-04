# 🌿 PlantDoc AI

**AI-Powered Plant Disease Detector**  
Detect, diagnose, and defeat plant diseases—on the go.

## 🚀 Overview
PlantDoc AI is a web-based application that empowers farmers to identify crop diseases early using computer vision. With just an image of a plant leaf, the model provides quick, accurate diagnoses and treatment recommendations—making agricultural health more accessible and efficient.

## 🎯 Features
- 📷 Upload or capture a plant leaf photo  
- 🤖 AI/ML-based classification of common plant diseases  
- 💡 Diagnosis with actionable treatment and prevention tips  
- 🌐 Multilingual and mobile-first interface  
- ☁️ Offline-first functionality for rural deployment

## 🧠 Tech Stack
| Layer        | Technology             |
|--------------|------------------------|
| Frontend     | React + Tailwind / Streamlit MVP |
| Backend      | Python + FastAPI / Flask |
| AI Engine    | TensorFlow/Keras (CNN-based model) |
| Dataset      | PlantVillage + custom image augmentations |
| Deployment   | Render / Heroku / GitHub Pages |
| Versioning   | Git + GitHub CI/CD |

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/plantdoc-ai.git
cd plantdoc-ai

# Set up virtual environment
python -m venv env
source env/bin/activate  # Windows: .\\env\\Scripts\\activate

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py  # or `uvicorn main:app --reload` if using FastAPI
```

## 🖼️ Sample Inference

Upload a leaf photo via the app interface.  
The model returns:

- Detected disease name (or healthy)
- Description and cause
- Recommended pesticide/organic treatment
- Future prevention tips

## 🌍 Target Users

- Smallholder farmers in Sub-Saharan Africa  
- Agri-extension officers and NGOs  
- Researchers and agricultural startups

## 📈 Roadmap

- [x] AI model trained and tested  
- [x] Web-based MVP interface  
- [ ] Add multilingual support (Swahili, Amharic, etc.)  
- [ ] Integrate SMS diagnosis for low-connectivity regions  
- [ ] Launch Android PWA version

## 🤝 Contributing

Pull requests are welcome!  
Please fork the repo and submit a PR with clear commit messages.  
Check `CONTRIBUTING.md` for more info.

## 📜 License

MIT License © Pauline

## 📬 Contact

For questions, collaborations, or feedback:  
**Email**: chiemahpauline@gmail.com  
**LinkedIn**: [Your LinkedIn](https://linkedin.com/in/pauline chiemah)  
**Website**: [PlantDoc AI](https://plant-doc.netlify.app/)






