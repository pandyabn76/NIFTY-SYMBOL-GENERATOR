NIFTY Option Symbols Generator 🚀
A simple and fast Streamlit web application that allows you to upload the NIFTY Option Chain .csv file, apply filters based on LTP range, ATM strike range, and expiry date, and automatically generate a ready-to-use .txt file of formatted NIFTY option symbols.

🔥 Features
📂 Upload NSE or broker option chain .csv file

🎯 Specify Expiry Date and ATM Strike Price manually

🔍 Automatically filters options with LTP between ₹150–₹250

🧠 Selects strikes within ±1000 points of ATM

🛠️ Generates correct Trading Symbol format:
NIFTY{expiry}{C/P}{strike} (example: NIFTY250424C24000)

📥 One-click download of a comma-separated .txt file

⚡ Built with Python and Streamlit for simplicity and speed

🎨 Minimal UI, designed for traders and analysts

🚀 How to Run Locally
Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/nifty-option-symbols-generator.git
Navigate into the project directory:

bash
Copy
Edit
cd nifty-option-symbols-generator
Install required Python packages:

bash
Copy
Edit
pip install streamlit pandas
Run the app:

bash
Copy
Edit
streamlit run app.py
⚡ Future Enhancements
Adjustable Strike Range and LTP Range from UI

Auto-detect ATM strike based on max OI or Volume

Multi-Expiry support (BankNifty, FinNifty, etc.)

Direct integration with NSE/Broker APIs (for live fetching)

📜 License
This project is licensed under the MIT License — feel free to use, modify, and distribute!

📣 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

🙌 Special Thanks
Developed to simplify and speed up NIFTY Options Symbol Filtering for professional traders and desk analysts.

Tags
NIFTY Options Trading Streamlit App Python Automation LTP Filter ATM Strike Options Chain

✅
