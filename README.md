# 🔮 AI Yes/No Oracle — GenLayer Tutorial

A beginner-friendly project that demonstrates how to build an AI-powered oracle on-chain using GenLayer.

This project walks through deploying a Python-based Intelligent Contract that answers YES/NO questions using AI, and connecting it to a simple frontend.

---

## 🚀 Live Demo
👉 https://your-username.github.io/genlayer-oracle/

---

## 📌 What This Project Does

- Accepts any user question  
- Uses AI (LLM) inside a smart contract  
- Returns a YES or NO answer  
- Stores the result permanently on-chain  
- Displays results via a simple web UI  

---

## 🧠 Key Concepts

- Intelligent Contracts — Python-based smart contracts with AI capabilities  
- Optimistic Democracy — validators verify AI outputs  
- Equivalence Principle — ensures consensus across different AI responses  
- On-chain AI execution — no external oracle needed  

---

## 🛠 Tech Stack

- Python (GenLayer Intelligent Contract)
- JavaScript (Frontend)
- HTML + CSS
- GenLayer Studio
- genlayer-js SDK

---

## 📂 Project Structure

. ├── index.html        # Frontend UI ├── oracle.js         # Frontend logic (GenLayer interaction) ├── YesNoOracle.py    # Intelligent Contract └── README.md

---

## ⚙️ How It Works

1. User enters a question in the UI  
2. Frontend sends a transaction to the contract  
3. Contract calls AI using gl.exec_prompt()  
4. Validators reach consensus  
5. Result (YES/NO) is stored on-chain  
6. Frontend reads and displays the result  

---

## 🧪 Example

Input:
Is the Earth flat?

Output:
NO ❌

---

## 🧾 Smart Contract Highlights

- Uses gl.exec_prompt() to call AI  
- Uses gl.eq_principle_strict_eq() for consensus  
- Stores data in on-chain arrays  
- Provides read methods for fetching results  

---

## 🌐 Deployment (GitHub Pages)

1. Upload project files to a GitHub repository  
2. Go to Settings → Pages  
3. Select:
   - Branch: main
   - Folder: / (root)  
4. Save  

Your site will be live at:
https://your-username.github.io/repo-name/

---

## ⚠️ Important Notes

- Ensure CSS variables use -- (not –)  
- Contract must be deployed in GenLayer Studio  
- Replace contract address in oracle.js  

---

## 🔮 Future Improvements

- MetaMask integration  
- Better UI/UX design  
- Multi-answer support (not just YES/NO)  
- History filtering & search  
- AI confidence score  

---

## 📚 Resources

- GenLayer Docs: https://docs.genlayer.com  
- GenLayer Studio: https://studio.genlayer.com  
- genlayer-js SDK: https://github.com/genlayerlabs/genlayer-js  

---

## 👤 Author

Built by Kbin  
Exploring AI + Blockchain + Decentralized Systems  

---

## ⭐ Support

If you found this useful, consider giving the repo a ⭐
