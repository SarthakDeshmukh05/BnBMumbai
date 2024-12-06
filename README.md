# AI-Powered Financial Analysis Tool

## Overview
In today's data-driven world, financial analysts spend countless hours manually sifting through thousands of pages of corporate filings to extract meaningful insights. This process is both time-consuming and error-prone, especially when handling unstructured data.

This project introduces an **AI-powered agent** that automates the extraction and analysis of company financial data from unstructured documents, using **Google Cloud's infrastructure** and **Gemini AI**. The solution includes tools for fetching and analyzing corporate filings, performing sentiment analysis, and responding to queries as a chatbot — all with minimal manual effort.

## Features
- **Chatbot**: Built using Gemini Flash 1.5, it acts as a virtual assistant capable of answering company-related queries by analyzing relevant financial documents.
- **Sentiment Analysis Tool**: Leverages Gemini AI to predict sentiments from financial news, providing insights into market perception.

## Audience
- **Skill Level**: Intermediate (familiarity with MERN stack, Google Cloud, and Vertex AI recommended)
- **Predefined Knowledge**: Basic understanding of data extraction, Gemini AI, and Google Cloud.

---

## Architecture

### Core Components
1. **Data Storage & Retrieval**
   - Unstructured RHP datasets (company financial filings) are stored in Google Cloud Storage Buckets.
   - Files are indexed and organized for efficient retrieval.

2. **AI-Powered Tools**
   - **Chatbot**: Handles financial data queries via natural language processing.
   - **Sentiment Analysis**: Analyzes financial news to predict sentiment and provide actionable insights.

### Design Rationale
- **Why Google Cloud & Gemini AI?**
  - Google Cloud offers scalable storage and the ability to process large datasets.
  - Gemini AI enables seamless integration of advanced natural language processing models for data extraction.
- **Why a Chatbot Interface?**
  - Simplifies user interactions by allowing intuitive queries instead of manual data navigation.

---

## Prerequisites

### Software & Tools
- **Frontend**: React, Node.js (MERN stack)
- **Backend**: Express.js (MERN stack), Google Cloud SDK
- **AI Tools**: Gemini AI Flash 1.5
- **Cloud Infrastructure**: Google Cloud Platform (GCP)
- **Database**: Google Cloud Storage Buckets

---

## Step-by-Step Instructions

### Step 1: Set Up Google Cloud Storage
1. Create a Google Cloud Storage bucket to upload unstructured RHP files (corporate filings).
2. Upload all company filings (RHPs) as unstructured text files (e.g., PDFs, Word Documents).

### Step 2: Build the Backend with Google Cloud and Gemini AI
1. **Set Up the Backend**:
   - Use Google Cloud Platform (GCP) Agent Builder to train your chatbot.
   - Configure the chatbot to understand financial data queries.
2. **Integrate Gemini AI for Sentiment Analysis**:
   - Create an API endpoint to send financial news data to Gemini AI.
   - Return sentiment analysis results to the client.

### Step 3: Manipulate GitHub Repository with Your AI-Powered Financial Analysis Agent
1. Locate the `index.html` file in your GitHub repository.
   - Update the credentials to match your Google Cloud setup.
2. Find the `gemini.jx` file in your project directory.
   - Add your Gemini API key to enable AI functionalities.

   **GitHub Repository**: [SarthakDeshmukh05/BnBMumbai](https://github.com/SarthakDeshmukh05/BnBMumbai)

---

## What’s Next?

### Potential Enhancements
- **Real-Time Data Feeds**: Integrate live data streams for up-to-date financial news and filings.
- **Recommendation Engine**: Suggest financial strategies based on analyzed data.

### Challenges to Expand Skills
1. **Scalability**: Design solutions to handle multiple users and larger datasets efficiently.
2. **Advanced NLP**: Enhance the chatbot’s understanding using cutting-edge natural language processing techniques.

---

## Call to Action
Take the next step to advance your skills and create impactful projects:
- **[Register for Code Vipassana sessions](#)**: Learn to build smarter AI applications.
- **[Join the Datapreneur Social Meetup Group](#)**: Network with like-minded professionals.
- **[Sign up to become a Google Cloud Innovator](https://cloud.google.com/innovators)**: Stay updated with the latest Google Cloud advancements.
