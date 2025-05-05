# Who Spends to Shape Finnish Minds on Meta?

## About This Project

The goal of this project was to create a comprehensive overview of who spends money on advocacy advertising in Finland on Meta’s platforms. I recently discovered the Meta Ad Library database and wanted to explore its potential with an open mind.

## Workflow

1. **Explore the Meta Ad Library** and understand how the platform works.  
2. **Download ad data** from March 25 to April 25, 2025 — a period that includes two weeks before and after the regional elections.  
3. The dataset contained **3,433 rows**, mostly individual candidates. I attempted to match candidates to their parties using both computational and manual methods, but none were successful.  
4. I decided to **exclude individual candidates** and focus on party organizations. This distinction also made sense because party-level spending is publicly funded, while individual candidates rely more on private donations.  
5. I **manually cleaned** the data by removing candidates and categorizing remaining advertisers into parties, NGOs, and companies.  
6. The result was a dataset of **non-individual advocacy advertisers**, organized by advertiser type.  
7. I imported the data into a **Jupyter Notebook** and explored what insights might emerge.  
8. After calculating **party-level ad budgets**, I merged the data with **election results** to examine correlations between ad spending and electoral success.  
9. I also analyzed differences in **ad spending between NGOs and private companies**.  
10. Once the analysis was complete, I **interviewed an expert** on political advertising in Finland.  
11. I designed visualizations in **Datawrapper** and refined them in **Adobe Illustrator**.  
12. I wrote the article, selected supporting images from **Pexels**, and designed the **visual narrative** by aligning text, images, and charts.  
13. I built the final **web page with HTML/CSS** and published it via **GitHub Pages**.

## Tech Used

- **Data Analysis:** Numbers, Python, Pandas, Jupyter Notebook  
- **Data Visualization:** Datawrapper, Adobe Illustrator  
- **Web Development:** HTML, CSS, GitHub Pages  

## How This Project Could Be Improved

- **Data Collection:** Using the Meta Ad Library API would enable more precise filtering and access to additional metadata.  
- **Candidate-Level Insights:** Merging Meta ad data with candidate-level election results — including vote counts and party affiliation — would enable deeper analysis.  
- **Scope Limitation:** In Finland’s multi-party system, the fairest boundary was to focus on the **nine parties represented in Parliament**.  
- **Election Scale:** The regional elections involved **29,950 candidates** across 10+ parties, making individual-level analysis extremely complex.

