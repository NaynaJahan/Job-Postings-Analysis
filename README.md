# Job-Postings-Analysis
Analyzing job postings pertaining to AI using different search algorithms and emphasizing qualifications and skills the industry expects from AI professionals.

## Dataset Description
Over 19,000 job postings from an employment board over a number of years make up the dataset used in this analysis. Twenty-four columns make up the dataset, and some notable ones are:
- `Title` – Job title (e.g., Software Developer, AI Engineer)
- `JobRequirment` – Key responsibilities and expectations
- `RequiredQual` – Required qualifications (e.g., degrees, experience)
- `jobpost` – Combined free-text field with structured and unstructured details
- `IT` – Boolean flag indicating if the job is IT-related
- `JobDescription` – Brief description of the role.
- `ApplicationP` – The application process.
- `AboutC` – Information about the company

## Search Algorithms Applied
For this study, an informed search method was selected to retrieve pertinent AI-related job postings. In particular, the Greedy Best-First Search (GBFS) algorithm was used because it prioritizes nodes (in this example, job ads) that seem most promising according to a defined heuristic, making it effective at navigating enormous search spaces. The Beam Search algorithm was also considered to filter job postings containing AI-related keywords across relevant columns. In this study, the dataset size is manageable, and high precision is essential; hence, GBFS can provide more accurate relevance ratings as it considers every possibility.

## Findings from Applying the Algorithm
The algorithm was able to effectively filter out 50 AI job ads that were highly pertinent:
- Software Developer
- Machine Learning Engineer
- Quality Assurance Engineer for AI Systems
- AI Research Assistant

Additional investigation revealed recurring trends:
- Technical proficiency in Python, API, .NET Framework, ASP.NET, and C++ is required.
- BS/MS in computer science or a similar discipline is required.
- Responsibilities include quality control, AI system design, and software development.
- “Ogma Applications CJSC” posts the highest number of AI-related jobs

## Identification of Relevant Job Advertisements
Three job ads were chosen to perform a thorough examination of industry expectations, based on the following criteria:
- High relevancy rating (high AI keywords).
- Completeness of `JobRequirment` and `RequiredQual` columns.
- Role diversity (e.g., *leadership*, *QA*, and *development*).
