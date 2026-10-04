# Apna Wakeel

**Tell us what happened. We'll tell you what to do next.**

Apna Wakeel is an AI-powered legal navigation tool for Pakistan, starting with Khyber Pakhtunkhwa. You describe your problem in plain language, and it shows you which authority to approach, what steps to follow, and what documents to bring, based on official sources.

It gives legal *information*, not legal advice.

## Why we built it

Most people don't know which law applies to them, where to go, or what papers to carry. The information is online, but it's scattered and hard to read. People who can't afford a lawyer are hit hardest.

## How it works

1. **You describe your situation** in English, Urdu, or Roman Urdu.
2. **AI agents understand and classify it.** If something important is missing, they ask.
3. **They look up official sources**, such as Pakistan Code, KP Code, NADRA, and the police and revenue departments.
4. **Every claim is checked against that evidence.** Anything we can't back up is removed.
5. **You get a simple plan:** the authority, the steps, the documents, and free legal-aid contacts.

If we can't verify an answer, we say so. We don't guess.

## What it covers

1. **Identity and government documents:** CNIC loss, renewal and correction; domicile application and verification.
2. **Family and marriage:** marriage registration, divorce or dissolution registration, and reporting underage marriage.
3. **Child protection:** child labour, child protection, and reporting and rescue navigation where official sources support it.
4. **Harassment and protection:** workplace harassment, domestic violence, online harassment, cyberstalking, and general complaints.
5. **Fraud and cybercrime:** online scams, electronic fraud, identity misuse, and offline fraud. We never assume "fraud" means cybercrime without online facts.
6. **Land and property:** disputes, boundaries, land records (Fard), revenue issues, and the right offices.
7. **Inheritance and succession:** disputes, succession certificates, letters of administration, and property-record navigation. We never calculate shares without enough facts and authoritative support.
8. **Accidents and traffic:** road accidents, vehicle damage, and compensation or responsibility disputes, kept separate from traffic violations, licensing, and vehicle services.
9. **Police and FIR:** FIR navigation, trouble getting an FIR registered, police complaints, and online FIR where officially supported. We never decide an offence happened just from your description.

## Tech

React + Vite (frontend) · FastAPI (backend) · Groq-hosted LLM (AI agents) · Supabase (login) · SQLite / PostgreSQL

## Honest limitations

- This is a hackathon prototype, not legal advice. Please talk to a qualified lawyer for your case.
- Coverage is mainly KP and federal law. Our legal-aid directory is focused on Chitral plus national helplines.
- Answers depend on official websites being reachable. If they aren't, we say "unavailable" instead of guessing.
- The AI verification step can still make mistakes. Our test scenarios are awaiting review by a legal professional.
- Scanned PDFs aren't supported yet.

## Team

| Role | Name | Phone |
|---|---|---|
| Team Leader | Touqeer Ullah | `+0341 1361361` |
| Member | Nashiman Mahak | `0345 3061413` | 
| Member | Husna Qayyum | `03468069661` |
