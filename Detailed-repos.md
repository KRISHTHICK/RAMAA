AI-Project-Agent/
├── docs/                        # Project documentation
│   ├── Project_Design_Doc.md    # High-level design document
│   ├── Flowchart.xml            # Draw.io/Mermaid flowchart (system workflow)
│   └── Ethical_Guidelines.md    # Privacy, compliance, and ethical considerations
├── src/                         # Source code
│   ├── search_engine_scraper/   # Auto-search for trends, papers, LLMs
│   ├── llm_integration/         # Hugging Face/OpenAI/Gemini API integration
│   ├── mentor_finder/           # LinkedIn/ResearchGate scraping & outreach
│   ├── project_manager/         # GitHub/Blog/Resume automation
│   └── trend_analyzer/          # Weekly AI trend analysis (Twitter/YouTube/HF)
├── scripts/                     # Automation scripts
│   ├── mentor_outreach.py       # LinkedIn connection requests
│   ├── llm_prompt_generator.py  # Topic generation via LLMs
│   └── trend_scraper.py         # Scrape trending AI tools
├── data/                        # Stored data
│   ├── llm_responses/           # Top 3 LLM suggestions (JSON/CSV)
│   ├── mentor_profiles/         # MIT/Stanford/MAANG mentor contacts
│   └── trends/                  # Weekly AI trend reports
├── results/                     # Outputs
│   ├── project_abstract.md      # Generated abstract for mentors
│   ├── blog_posts/              # Auto-generated blog drafts
│   └── resume_updates.md        # Resume lines for the project
├── utils/                       # Utilities
│   ├── config.yaml              # API keys, platform credentials
│   ├── templates/               # Email/LinkedIn message templates
│   └── logger.py                # Logging module
├── tests/                       # Unit/integration tests
├── .github/                     # CI/CD workflows
├── requirements.txt             # Python dependencies
├── README.md                    # Setup guide, overview, usage
└── LICENSE
