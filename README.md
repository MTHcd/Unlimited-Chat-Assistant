# Unlimited-Chat-Assistant

UnlimitedChatAssistant/
│
├── app/
│   ├── main.py                    # Main application file (Streamlit app entry point)
│   ├── plugins/
│   │   ├── __init__.py            # Initialization for plugins module
│   │   ├── web_search.py          # Logic for WebSearch plugin
│   │   ├── web_scraping.py        # Logic for Web Scraping plugin
│   │   ├── multi_document.py      # Logic for Multi-Document plugin
│   │   ├── audio.py               # Logic for Audio plugin
│   │   ├── youtube_video.py       # Logic for YouTube Video plugin
│   │   ├── god_mode.py            # Logic for GOD MODE plugin
│   │
│   ├── utils/
│   │   ├── __init__.py            # Initialization for utils module
│   │   ├── llm_handler.py         # Logic to handle communication with HuggingFace Chat API
│   │   ├── data_processing.py     # Utility functions for data parsing and preproc   essing
│   │   ├── file_handlers.py       # Utilities for handling files (PDF, DOCX, etc.)
│   │   ├── audio_handlers.py      # Utilities for handling audio files
│   │   ├── youtube_parser.py      # Utility for parsing YouTube video data
│   │
│   ├── static/
│       ├── css/                   # Custom CSS files for Streamlit app styling
│       ├── images/                # Static images used in the application
│
├── data/
│   ├── sample_documents/          # Sample PDF, DOCX, or TXT files for testing plugins
│   ├── sample_audio/              # Sample MP3 or WAV files for plugin testing
│   ├── sample_videos/             # Sample YouTube links or metadata
│
├── tests/
│   ├── test_plugins.py            # Unit tests for plugins
│   ├── test_utils.py              # Unit tests for utility functions
│
├── requirements.txt               # Python dependencies
├── Dockerfile                     # Dockerfile for containerization
├── README.md                      # Documentation and usage guide
├── .gitignore                     # Git ignore file
└── streamlit_app.py               # Main Streamlit app entry poinng 
