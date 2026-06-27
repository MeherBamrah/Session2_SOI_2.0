# Session2_SOI_2.0
# Review Analyser using Azure AI Language Service

A simple web application that analyzes customer reviews using Azure AI Language Service. The application identifies the overall sentiment of a review and extracts important key phrases to help users quickly understand customer feedback.

## 🚀 Features

* Sentiment Analysis

  * Detects whether a review is:

    * Positive
    * Negative
    * Neutral
    * Mixed

* Key Phrase Extraction

  * Identifies important topics and keywords from the review text.

* Interactive Web Interface

  * Simple and user-friendly UI.
  * Instant analysis results.

## 🛠 Technologies Used

* HTML
* CSS
* JavaScript
* Azure AI Language Service
* Azure Cognitive Services REST API

## 📋 How It Works

1. User enters a product review.
2. The application sends the review text to Azure AI Language Service.
3. Azure performs:

   * Sentiment Analysis
   * Key Phrase Extraction
4. Results are displayed on the webpage with:

   * Sentiment badge
   * Extracted keywords

## 🏗 Project Structure

```text
Session2_SOI_2.0/
│
├── index.html
└── README.md
```

## ⚙️ Azure Setup

### Step 1: Create an Azure AI Language Resource

1. Sign in to the Azure Portal.
2. Create a Language Service resource.
3. Copy:

   * API Key
   * Endpoint URL

### Step 2: Update Credentials

Open `index.html` and replace:

```javascript
const KEY = "PASTE_YOUR_KEY_1_HERE";
const ENDPOINT = "PASTE_YOUR_ENDPOINT_HERE";
```

with your Azure credentials.

Example:

```javascript
const KEY = "xxxxxxxxxxxxxxxxxxxxxxxx";
const ENDPOINT = "https://your-resource.cognitiveservices.azure.com/";
```

⚠️ Never commit your API keys to a public repository.

## ▶️ Running the Application

Since this is a static web application:

1. Download or clone the repository.

```bash
git clone https://github.com/MeherBamrah/Session2_SOI_2.0.git
```

2. Open `index.html` in your browser.

OR

Run a local server:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## 🧪 Example Review

```text
The product quality is excellent and delivery was very fast. The packaging was also impressive.
```

Expected Output:

* Sentiment: Positive
* Keywords:

  * product quality
  * delivery
  * packaging

## 🎯 Learning Objectives

Through this project, participants learn:

* Basics of Azure AI Language Service
* Calling Azure REST APIs
* Sentiment Analysis
* Key Phrase Extraction
* Frontend integration with AI services
* Building AI-powered applications with minimal code

## 📚 Azure Services Used

* Azure AI Language Service
* Azure Cognitive Services

## 👨‍💻 Developed For

SOI 2.0 – Session 2 Hands-On Workshop

This project serves as a beginner-friendly demonstration of how Azure AI can be integrated into web applications for text analytics and customer feedback analysis.

## 📜 License

This project is intended for educational and learning purposes.
