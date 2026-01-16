### AI Loan Processing App (Release 2)
1) Current App State is simple with a Bank Statement csv (Dummy Data) placed. File - bank_statement.csv
2) UI is added (streamlit)
3) For Execution -
   a) In Powershell run python server.py
   b) In Split Session - run python -m streamlit run ui.py
5) Python packages required are present in the requirement.txt
6) .env file need to created at the root directory (same level as main.py)
     a) Add the OPEN_AI_KEY or any other required
     b) Update the LLM in the nodes.py file. Line position 13,14,15 (for the respective LLM Model)
7) Print Statements hav been placed at positions to understand the flow and final outcome.
8) Placed a Presentation Deck in PDF. File - CloudFront_AILoanProcessing.pdf
