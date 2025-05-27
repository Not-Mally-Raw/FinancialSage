# FinancialSage: Your PDF-to-Profit Sidekick

Welcome to FinancialSage, the Python-powered tool that turns your boring financial PDFs into a treasure trove of insights! Whether you're decoding expense reports or hunting for Q4 revenue, FinancialSage makes crunching numbers as fun as binge-watching your favorite show. Let’s dive into the world of financial wizardry!

_________________________________________________________________________________________________________________________________________________

🎉 What’s Cool About FinancialSage?

PDF Text Extraction: Slurps text from PDFs using pdfplumber like a data-hungry vacuum.
Financial Data Magic: Pulls out dollar amounts and descriptions with regex wizardry, saving them as a tidy CSV.
Smart Search: Uses SentenceTransformer and FAISS to find answers faster than you can say "where’s my revenue?"
Pretty Visuals: Bar and pie charts via matplotlib and seaborn that make your data pop.
Quick Summaries: Get the lowdown on totals, averages, and top expenses in a snap.
Streamlit Vibes: Spin up a web app to explore your data like a pro.

_________________________________________________________________________________________________________________________________________________

🚀 Get Started in a Flash
Ready to unleash FinancialSage? Here’s how to make it happen:
What You Need

Python 3.11+: Gotta have the Python juice.
Virtual Environment: Keeps things neat (optional but recommended).
Google Colab: Perfect for cloud-based number-crunching (optional).

_________________________________________________________________________________________________________________________________________________

Setup

Grab the Code:
git clone https://github.com/your-username/financialsage.git
cd financialsage

_________________________________________________________________________________________________________________________________________________

Set Up a Virtual Environment:
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate


Install the Good Stuff:
pip install pdfplumber PyMuPDF sentence-transformers faiss-cpu streamlit ngrok matplotlib seaborn google-cloud-vision


Drop Your PDF: Toss your financial PDF (e.g., budget.pdf) into the project folder.

_________________________________________________________________________________________________________________________________________________

How to Use It

Run the Notebook:

Fire up FinancialSage1.ipynb in Jupyter or Google Colab.
Run the cells to:
Install dependencies.
Upload and extract text from your PDF.
Save financial data to financials.csv.
Build a FAISS index for speedy searches.
Create cool charts and summaries.


_________________________________________________________________________________________________________________________________________________


Launch the Streamlit App:
streamlit run app.py


Play with an interactive dashboard to query and visualize your data.


Search Like a Boss:

Try queries like "What’s the total revenue for Q4?" to get instant results.

_________________________________________________________________________________________________________________________________________________


What You Get

CSV Output: A neat financials.csv with descriptions and amounts.
Visuals: Bar charts for top expenses, pie charts for categories.
Search Index: A FAISS index for quick, smart searches.


📈 Visuals That Slap
FinancialSage makes your data look good:

Bar Charts: See your top 10 expenses in vibrant color.
Pie Charts: Get a slice-by-slice breakdown of expense categories.
Interactive Dashboard: Explore your data with Streamlit’s slick interface.

_________________________________________________________________________________________________________________________________________________

🛠️ Under the Hood
FinancialSage runs on a lean, mean tech stack:

pdfplumber & PyMuPDF: For grabbing text from PDFs.
SentenceTransformer (all-MiniLM-L6-v2): For snappy text embeddings.
FAISS: For lightning-fast similarity searches.
pandas & numpy: For slicing and dicing data.
matplotlib & seaborn: For charts that make you go "ooh!"
Streamlit & ngrok: For building and sharing web apps.

_________________________________________________________________________________________________________________________________________________

🌍 Deployment Options

Local: Run the Streamlit app on your machine.
Cloud: Use ngrok to share your app with the world.
Colab: Crunch numbers in Google Colab for zero setup.

_________________________________________________________________________________________________________________________________________________

🤝 Wanna Contribute?
Got ideas to make FinancialSage even cooler? Jump in!

Fork the repo.
Create a branch (git checkout -b feature/cool-idea).
Commit your changes (git commit -m "Added cool idea").
Push it (git push origin feature/cool-idea).
Open a Pull Request and let’s chat!
_________________________________________________________________________________________________________________________________________________


📜 License
FinancialSage is rocking the MIT License — use it, tweak it, share it!

🙌 Shoutouts
Big thanks to the open-source crew behind pdfplumber, SentenceTransformer, FAISS, and Streamlit for making this project possible.

Made by Data Nirvana.
