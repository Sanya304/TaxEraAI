# TaxEraAI

## Overview
TaxEraAI is an advanced tax filing assistant designed to simplify the tax process for individuals and businesses. It automates tax calculations, identifies deductions, and minimizes errors, ensuring a smooth tax filing experience.

## Solution Approach
- **Automated Tax Filing:** Uses AI-driven automation to streamline the process.
- **Simplified Calculations:** Breaks down complex tax jargon into easy-to-understand terms.
- **Deduction Optimization:** Helps maximize savings by identifying eligible deductions.
- **Error Minimization:** Advanced error-checking algorithms reduce tax filing mistakes.

## How I Built It
- **Frontend:** Developed using Next.js and React for an interactive user experience.
- **Backend:** Implemented with FastAPI, leveraging Google Vertex AI and Discovery Engine for intelligent tax assistance.
- **Database & APIs:** Utilized Google Cloud services for data retrieval and storage.

## Project Images
![Image 1](https://example.com/image1.png)
![Image 2](https://example.com/image2.png)
![Image 3](https://example.com/image3.png)
![Image 4](https://example.com/image4.png)

## Run it in Your Local Machine

### Steps to run the frontend:
1. Open Terminal or Command Prompt.  
2. Navigate to the `src/frontend` directory.  
3. Install dependencies using `npm install`.  
4. Start the development server with `npm run dev`.  
5. Open a browser and go to `http://localhost:3000`.  

### Steps to run the FastAPI backend:
1. Install dependencies using: `pip install fastapi uvicorn google-cloud-discoveryengine vertexai google-api-core`.  
2. Set up Google Cloud authentication by configuring service account credentials.  
3. Save the Python script as a `.py` file (e.g., `main.py`).  
4. Open a terminal and navigate to the script’s directory.  
5. Run the FastAPI server with: `uvicorn main:app --reload`.  
6. Access the API at `http://localhost:8000/docs` to test endpoints.  

## Acknowledgment
Special thanks to everyone who contributed to the development of TaxEraAI, including mentors, developers, and the open-source community for providing valuable resources and guidance.
