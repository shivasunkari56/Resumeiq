**ResumeIQ**[Features](#features)[How it works](#how)[Workspace](#start)

# Build a Resume That Matches Your Next Opportunity.

Upload your resume, share a job description, and see exactly which requirements your own experience already covers. Then answer a few questions and export a tailored PDF.

[Create My Tailored Resume](#start)[Explore How It Works](#how)

Your Experience. The Right Opportunity. A Resume That Fits.

## What works in this version

### Resume upload

Real PDF and DOCX text extraction, in your browser.

### Job requirement analysis

Skills found in the posting, ranked by its own wording.

### Evidence matching

Each requirement checked against your resume text.

### Country rules

Format guidance per target country.

### Clarifying questions

Asked only where evidence is missing. Skip anything.

### Coverage report

Transparent keyword coverage score with its formula.

### Editable draft + PDF

Edit the text, then download a real PDF.

### Saved locally

Progress survives refresh. Nothing leaves your device.

## How it works

1. **Upload your resume.** PDF or DOCX.
2. **Add the job description.** Paste the text.
3. **Analyze.** Requirements are matched to your resume.
4. **Answer questions.** Only about gaps in evidence.
5. **Download.** Review the draft, then export a PDF.

**Not included in this preview:** accounts, a database, job URL fetching, live company research, AI rewriting, cover letters, DOCX export, and multi-application dashboards. Those need a server and API keys; a browser-only page can't run them honestly. See the notes after the workspace.

## Create Your Tailored Resume

### 1. Upload your existing resume

Upload your current resume so we can read your skills, experience, projects, education, and achievements.

Drag and drop your file here, or browse your device.

PDF or DOCX, up to 5 MB

Extracted text (review and correct)

Skills detected in the text:

A skill that is not listed is not treated as missing. You'll be asked about it later.

Extraction failed or scanned PDF? Enter details manually

Scanned PDFs need OCR, which isn't configured here. Paste your resume text below instead.

### 2. Add the job description

Provide the job posting so we can understand the role, required skills, responsibilities, and qualifications.

OR

Paste Job Description

0 characters

### 3. Select your target country

This sets the format guidance used in your draft.

Target city or region (optional)

4\. Company information (optional)

Company nameTarget job title

Stored with your application. Live company research isn't available in this version, and none is claimed.

## Requirement match

## Let's strengthen your resume

We found areas where more information would help us represent your experience accurately. Answer only what is true; skip the rest.

## Coverage report

## Review and download

Resume draft (editable)

**Setup notes.** Everything here runs in your browser; your resume and job text are stored only in this browser's localStorage. The analysis is dictionary-based keyword matching, not AI, and the coverage score is not an employer ATS score. To build the full product (Next.js, PostgreSQL, object storage, LLM-based extraction and research, SSRF-safe job URL retrieval, DOCX export), run it on a server with your own API keys. Ask and I'll draft that architecture and schema.