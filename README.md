# AI-Powered "Resume-to-Job Matcher" with LinkedIn Scraping
 A tool that analyzes job descriptions vs. resumes using NLP, scores fit, and suggests optimizations

**Scope:** Web app with resume parsing, job scraping, and AI scoring.

**Audience:** Job seekers, recruiters (MVP focuses on job seekers).

**Tech stack used:**
        Frontend	      React + Tailwind	                  Interactive UI for resume/job uploads, match visualization
        Backend	        Node.js + Express	                  Handles auth, API routes, and serves React app
        Database	      MongoDB (or PostgreSQL)	            Stores user profiles, resumes, and job matches
        AI/ML	          Python (Flask/FastAPI microservice)	Runs NLP (spaCy, Hugging Face), resume parsing, and scoring
        Scraping	      Puppeteer (Node) or Scrapy (Python)	Fetches LinkedIn job listings
        Auth	          Firebase Auth / Passport.js	        OAuth for LinkedIn/Google login

**What does it will cause:**
      Job seekers waste hours applying to mismatched roles. This automates the matching process (like a mini-ATS).
