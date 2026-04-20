# WhatsApp Chat Analyzer

[![Python package](https://github.com/Harsh-karn/Whatsapp-Chat-Analyzer/actions/workflows/python-package.yml/badge.svg)](https://github.com/Harsh-karn/Whatsapp-Chat-Analyzer/actions/workflows/python-package.yml)

**Live Demo:** [https://whatsapp-analyzer-chat.streamlit.app/](https://whatsapp-analyzer-chat.streamlit.app/)

## Overview
WhatsApp Chat Analyzer is a comprehensive Python-based web application built with Streamlit that allows you to gain deep insights into your personal or group WhatsApp conversations. Simply export your chat as a `.txt` file (without media) and upload it to the dashboard to instantly generate beautiful visualizations and statistics.

## Key Features
- **Overall Statistics:** View total messages, words, media shared, and links extracted.
- **Timeline Analysis:** Discover your chat volume over time with detailed monthly and daily timeline charts.
- **Activity Maps:** Find out your busiest days of the week, busiest months, and view a detailed weekly heatmap of activity.
- **User Analytics:** See who the most active participants are in group chats.
- **Word Analysis:** Generates a WordCloud and a bar chart of the most frequently used words (excluding common stop words).
- **Emoji Analysis:** A fun pie chart breaking down the exact emojis you and your friends use the most!

## Supported Formats
The app features a robust universal chat parser that automatically detects and processes chat exports from:
- Android (12-hour and 24-hour clock formats)
- iOS (iPhone export formats)

## How to Use
1. Open WhatsApp on your phone.
2. Go to the chat or group you want to analyze.
3. Tap the three dots (Options) > **More** > **Export chat**.
4. Choose **Without media**.
5. Save the generated `.txt` file.
6. Visit the [Live Dashboard](https://whatsapp-analyzer-chat.streamlit.app/) and upload your file!
