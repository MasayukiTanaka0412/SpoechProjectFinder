# SpeechProjectFinder

A web-based tool that helps Toastmasters members find the most suitable speech projects based on their goals and preferences.

## Overview

SpeechProjectFinder asks 20 Yes/No questions about your speaking goals and recommends the top 3 matching speech projects from the Toastmasters Pathways program. It also generates an AI prompt for each recommended project to help you brainstorm speech ideas.

## Features

- Select your Toastmasters Path from a dropdown list
- Answer 20 Yes/No questions about your speaking goals
- Receive the top 3 project recommendations ranked by relevance score
- Generate a ready-to-use AI (ChatGPT) prompt for each recommended project
- Available in Japanese ([index.html](./index.html)) and English ([index_en.html](./index_en.html))

## Usage

1. Open `index.html` (Japanese) or `index_en.html` (English) in a browser.
2. Select your Toastmasters Path from the dropdown.
3. Answer all 20 Yes/No questions.
4. Click **"3つのプロジェクトを提案する"** (or **"Recommend 3 Projects"** in English).
5. Review the recommended projects and optionally display an AI prompt for speech ideas.

## Project Data

Speech project data is loaded from [`projectlist.md`](./projectlist.md), a Markdown table with the following columns:

| Column | Description |
|--------|-------------|
| Path | Toastmasters Pathway name |
| Project | Project name |
| Purpose (EN) | Project purpose in English |
| Purpose (JP) | Project purpose in Japanese |

## License

This project is licensed under the MIT License. See [LICENSE.md](./LICENSE.md) for details.

## Author

Masayuki Tanaka
