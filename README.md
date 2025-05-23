# Social Media AI Content

A comprehensive application for creating, managing, and sharing social media content across multiple platforms with AI assistance. This Flask-based application helps content creators streamline their workflow with intelligent content generation and management features.

![Social Media AI Content](https://via.placeholder.com/800x400?text=Social+Media+AI+Content)

## Features

- **AI-Powered Content Creation**: Generate platform-specific social media content using AI tailored to each platform's best practices
- **Rich Text Editor**: TinyMCE integration for advanced content editing with formatting options
- **Multi-Platform Support**: Create content for LinkedIn, Facebook, Twitter/X, Instagram, TikTok, YouTube, Bluesky, and blogs
- **Content Management**: Save, edit, and manage all your social media posts in one place
- **Direct Sharing**: Share content directly to social media platforms or copy formatted content for manual posting
- **Export Options**: Download posts as Word documents with preserved formatting for offline use
- **Copy & Paste Functionality**: Specialized clipboard support for platforms without direct web APIs
- **Search & Filter**: Find saved posts by platform, date, or content
- **Platform-Specific Optimization**: Content is tailored to each platform's character limits, formatting options, and best practices

## Supported Platforms

- LinkedIn
- Facebook
- Instagram
- Twitter/X
- TikTok
- YouTube
- Bluesky
- Blog content

## Getting Started

### Prerequisites

- Python 3.8+
- Flask
- OpenAI API key
- TinyMCE API key (optional for extended features)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Karehmaciu/AI-Social-Media-Content-Tool.git
   cd AI-Social-Media-Content-Tool
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Create a `.env` file with your API keys:

   ```env
   OPENAI_API_KEY=your_openai_api_key
   TINYMCE_API_KEY=your_tinymce_api_key
   SERP_API_KEY=your_serp_api_key
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Open [http://127.0.0.1:8008](http://127.0.0.1:8008) in your browser

## Usage

1. **Create Content**: Click "Create Content" and enter your topic, platform, tone, and other details
2. **Generate with AI**: Click "Generate Content" to create AI-assisted content
3. **Save Posts**: Save your content to the database
4. **Manage Content**: View, edit, and filter saved posts
5. **Share Content**: Use the sharing options to post directly to social media or export as Word

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- OpenAI for providing the AI capabilities
- TinyMCE for the rich text editor
- Flask for the web framework
