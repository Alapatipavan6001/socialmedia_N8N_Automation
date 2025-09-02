**Social Media Workflow Automation 🚀**

This repository contains an n8n workflow that automates social media content creation and management. It leverages OpenAI, Google Docs, Google Sheets, and Google Drive to streamline the entire content pipeline — from content generation to visual design and storage.

**📌 Features**

Content Extraction: Pulls weekly content from Google Docs.

Content Splitting: Breaks down content by week and sub-sections.

AI-Powered Writing: Uses OpenAI GPT models to generate engaging LinkedIn-style posts.

Carousel Creation: Converts content into short, image-friendly slides.

Image Generation: Uses AI prompts + DALL·E (via OpenAI Images API) to generate professional 1080x1080 visuals.

File Conversion & Storage: Converts generated images to files and saves them to Google Drive.

Tracking & Reporting: Logs all posts, images, and scheduling details into Google Sheets.

Batch Processing: Loops over weekly content for scalable automation.
**⚙️ Tech Stack**

n8n Workflow automation

Google Docs API – Content source

Google Sheets API – Content tracking

Google Drive API – Image storage

OpenAI GPT (3.5 / 4) – Content generation

OpenAI Image API (DALL·E) – Image creation

**🔄 Workflow Overview**
Trigger → Manual trigger starts the workflow.

Content Fetching → Retrieves content from Google Docs.

Splitting Logic → Separates weekly content and extracts details (title, focus, advice, quote, CTA).

AI Post Generation → GPT creates a warm, professional LinkedIn post.

Carousel Slide Builder → AI reformats text into short, slide-ready content.

Image Prompt Creation → AI generates a visual design prompt.

Image Generation → OpenAI DALL·E generates high-quality visuals.

Storage → Saves images to Google Drive.

Logging → Updates Google Sheets with post content, images, and scheduled dates.

**📂 File Structure**

social_media_workflow.json → The n8n workflow export file.

🚀 Getting Started

Import the Workflow into n8n:

Open n8n → Import → Upload social_media_workflow.json.

Set Up Credentials:

Google Docs OAuth2

Google Drive OAuth2

Google Sheets OAuth2

OpenAI API Key

Run the Workflow to start generating content automatically.

**✅ Example Use Case**

Marketing teams who want to automate weekly LinkedIn posts.

Content creators who want AI-assisted copywriting + design.

Agencies managing multiple clients’ content calendars.

**📌 Notes**

Update the Google Docs URL and Google Sheets ID in the workflow to match your own.

Ensure your OpenAI account has access to GPT-4o and Image API.

**📜 License**

This project is licensed under the MIT License – feel free to use and modify.
