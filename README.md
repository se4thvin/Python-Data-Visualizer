# Spotify Data: Top 1000 Song Case Study (Data Analysis / Python)  
## What Does It Take to Hit the Charts  

## Table of Contents
0. Executive Summary  
1. Introduction  
2. Collect, Wrangle & Explore  
3. Analyze & Visualization: Data Analysis  

---

## Executive Summary  

### Key Findings  
- **Mode, Key, and BPM** play a significant role in the success of a song.  

#### Mode: Major / Minor  
- Major mode is critical for success:  
  - **Top 10:** 70% of songs are Major vs 40% for the last 10 and 55.32% overall.  
  - **Top 50:** 68% are Major vs 54% for the last 50 and 55.32% overall.  

#### Key  
- **C# is the "golden key":**  
  - **Top 10:** 30% of songs are in C# vs 10% for the last 10 and 14.1% overall.  
  - **Top 50:** 24% in C# vs 14% for the last 50.  
  - **Top 100:** 18% in C#.  

#### BPM  
- BPM matters, with the best range being between **90 and 110** BPM:  
  - Overall average BPM is **122**.  
  - **Top 10:** Average BPM is **117**, with a high standard deviation (+34).  
    - Majority of the Top 10 BPMs are below 110.  
    - Minimum BPM for the Top 10 is **90**, and the overall minimum is **65**.  

#### Energy Score  
- A minimum energy level is essential for success:  
  - **Top 10:** Smallest standard deviation, ranging from **78 to 45**, with an average of **59.6**.  
  - **Optimal range:** **78 to 45**.  

---

## Objective & Scope  
- **Objective:**  
  - Collect, clean, and analyze the Spotify dataset.  
  - Identify key variables of interest.  
  - Enable businesses to make data-driven decisions.  
  - Share findings and insights.  

- **Scope:**  
  - Focus on uncovering patterns in the dataset to understand what drives song success.  

---

## Methodology  

### Steps Taken  
1. **Collect Data**  
   - Dataset used: `top-spotify-songs-2023`.  

2. **Wrangle Data**  
   - Preprocessing, cleaning, transforming, and organizing the data for analysis.  

3. **Explore Data**  
   - Use various techniques to explore the dataset.  

4. **Visualize Data**  
   - Generate visualizations to uncover insightful discoveries.  