# Crime Matrix
AI-Powered Crime Investigation and Analysis Platform

Crime Matrix is a web-based platform designed to make the crime investigation process simpler, faster, and more organized.

In a typical investigation, information such as FIRs, suspects, evidence, locations, communication records, statements, and incidents can be spread across different sources. Crime Matrix brings these details together in one place and uses AI-assisted analysis to help investigators understand the case better.

The main purpose of Crime Matrix is not to replace investigators, but to help them find connections, identify patterns, and save time during investigation.

#  Problem Statement

During a crime investigation, officers have to deal with a large amount of information. This information may come from:

FIRs and police reports
Call Detail Records (CDRs)
Financial transactions
CCTV and surveillance information
Social media information
Criminal history
Evidence and forensic records
Locations and incident details

The major problem is that this information is often available in different forms and places. Because of this, finding connections between people, evidence, locations, and events manually can take a lot of time.

For example, an investigator may not immediately notice that two suspects were connected through the same location or communication record.

Crime Matrix solves this problem by bringing investigation information together and helping investigators analyze the connections between them.

#  Proposed Solution

We propose Crime Matrix, a centralized crime investigation platform where authorized users can manage and analyze case information.

The system allows investigators to see the complete picture of a case instead of looking at each piece of information separately.

Crime Matrix can help investigators:

Understand the sequence of events.
Connect suspects, victims, witnesses, evidence, incidents, and locations.
Find hidden relationships.
Identify possible contradictions.
Compare identities across records.
Understand communication patterns.
Find possible gaps in an investigation.
Ask questions about the case using AI.
Generate a structured case report.

The final decision still remains with the investigator. AI is used only as an assistance tool.

#  Features
3.1 Role-Based Login

Different users have different responsibilities, so everyone should not have access to the same information.

Crime Matrix uses role-based login to control what each authorized user can see and access.

This helps protect sensitive investigation information.

3.2 Case Management

Investigators can manage all important information related to a case from one place.

A case can contain information about:

Case ID
Case status
Assigned officers
Suspects
Victims
Witnesses
Evidence
Incidents
Locations
Investigation tasks
Investigation progress

3.3 FIR Registration and OCR

Crime Matrix provides a complaint/FIR registration workflow.

Instead of entering every detail manually, an FIR can be scanned and OCR can extract the text from the document.

This can reduce manual data entry and make the initial registration process faster.

3.4 Fingerprint Resolution 

Uses fingerprint data as a biometric identifier to help verify and distinguish individuals.
Fingerprints can be linked with suspect or case records for faster identification.
Helps investigators establish connections between a person and a crime or evidence.
Supports secure and reliable identity verification during investigations.

3.5 Timeline Reconstruction

The timeline feature helps investigators understand what happened and when it happened.

Important events can be arranged in chronological order so that the investigator can get a clear picture of the case.

3.6 Evidence Relationship Graph

Crime investigations usually contain many pieces of evidence.

Crime Matrix can show the relationship between:

Evidence → Suspect → Incident → Location → Other entities

This makes it easier to understand how different pieces of information are connected.

3.7 Location Intelligence

Locations can provide important clues during an investigation.

Crime Matrix can help investigators analyze the locations connected with different incidents, people, and events.

This can help identify useful geographical patterns.

3.8 Criminal Network Evolution

Criminal networks can change over time.

Crime Matrix can help investigators understand how relationships between different people or entities develop or change during an investigation.

3.9 Communication Pattern Analysis

Communication information can sometimes reveal relationships between people.

Crime Matrix can analyze available communication data to help investigators understand communication patterns and connections.

3.10 Investigation Query Assistance

Instead of manually searching through different parts of a case, an investigator can ask a question in normal language.

For example:

"What are the connections between Suspect A and the other people in this case?"

The system can use the available case information to provide relevant results.

3.11 Investigation Gap Detection

Sometimes an investigation may have incomplete information or an area that needs further verification.

Crime Matrix can highlight possible investigation gaps so that the investigator can review them.

3.12 Automated Case Report

The system can use the available case information to help prepare a structured case report.

This can reduce the time required to manually prepare summaries.

# Technologies / Tech Stack Used

The final README should mention the technologies that are actually used in the working prototype.

Frontend
HTML
CSS
JavaScript / TypeScript
React,
Tailwind CSS,
Backend
Node.js,
API services,
Database

The actual database used by the project should be mentioned here.

For example:

MySQL
MongoDB
PostgreSQL
Firebase
AI / ML

The AI part of Crime Matrix can involve:

Natural Language Processing
OCR
Entity extraction
Relationship analysis
Contradiction detection
Identity matching
AI-based investigation queries
Investigation gap detection
Development Tools
VS Code
Git
GitHub
Web Browser

# Installation & Setup Instructions

First, download or clone the project from the project repository in VScode.
git clone https://github.com/akankshadm2611-pict/PICTians-ACMW.git

Open new terminal and select command prompt and run instruction
npm install

# How to run the project

Now to run the project use the instruction 
npm run dev
Open the url link provided in the terminal.

# Project Structure

The Crime Matrix project is organised into different folders and files to keep the application structured and easy to maintain.

public/ – Contains publicly accessible images and other static assets.
  images/ – Stores images used in the website.
  assets/ – Stores other required static resources.
src/ – Contains the main source code of the application.
  components/ – Contains reusable UI components.
  pages/ – Contains different pages/screens of the website.
  services/ – Contains service-related code such as data handling and API connections.
  data/ – Contains sample or predefined application data.
  styles/ – Contains CSS and styling files used to design the website.
screenshots/ – Contains screenshots of important sections of the Crime Matrix website, such as:
  Login page
  Dashboard
  Case management
  Timeline
  Criminal network
README.md – Contains complete information about the project, its features, setup, and usage.
package.json – Contains project dependencies, scripts, and configuration details.
package-lock.json – Keeps the exact versions of installed dependencies.
.gitignore – Specifies files and folders that should not be uploaded to GitHub.

# Team Members
Sayali Patil 
Akanksha Deshmukh
Dnyaneshwari Kale
Unnati Gandhi

#  Future Scope

Crime Matrix can be further improved in the future.

Some possible enhancements are:

Integration with authorized police databases.
Integration with existing investigation systems.
Better AI-based relationship analysis.
More advanced forensic evidence analysis.
Mobile application for authorized officers.
Stronger security and audit logging.
Integration with authorized CDR and financial transaction systems.
Large-scale deployment for police departments.

#  Working Source Code

The final submission will include the complete working source code of the Crime Matrix prototype.

The repository should contain:

Frontend code
Backend code, if applicable
AI/ML code, if applicable
Database files/configuration, if applicable
Required assets
Configuration files
Dependency files
README.md
.gitignore
Sample/demo data
Setup instructions

The repository should not contain:

Passwords
API keys
Database passwords
Real confidential FIRs
Real police investigation records
Private personal information
