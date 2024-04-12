In recruitment, companies often face the challenge of sorting through numerous resumes to find suitable candidates. Our project aims to revolutionize this process using smart computer techniques to facilitate hiring.

# Overview
We leverage advanced computer algorithms to swiftly analyze resumes, ensuring efficient candidate selection. By teaching computers to understand resumes and job descriptions, we identify the most appropriate candidates for a given role. This approach minimizes time wastage and enhances the likelihood of finding the perfect match.

# Features
## Data Loading
Before commencing our analysis, it's imperative to review the dataset thoroughly. This step involves examining the data and inspecting the columns to gain a comprehensive understanding.

## Word Embedding with Word2Vec
After loading the dataset, we construct and save the Word2Vec model. This empowers us to effectively utilize the model for subsequent tasks, enhancing the quality of resume analysis.

## Job Description Vectorization
The generated model enables us to split job descriptions and assign vector representations to individual words. These representations facilitate comparisons with other vectors in subsequent analyses, providing a holistic understanding of job descriptions.

## Talent Search using Cosine Similarity
With successful vectorization of job descriptions, we compare vector representations of resumes and job descriptions. This comparison allows us to assess the compatibility score of each resume with the job description, streamlining the candidate selection process.

## Top Candidate Selection
After scoring each resume, our goal is to identify the top 10 candidates for the job. This facilitates efficient candidate selection by providing the most relevant resumes aligned with the job requirements, thereby optimizing the recruitment process.

