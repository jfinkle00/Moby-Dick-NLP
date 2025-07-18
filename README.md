# Moby-Dick-NLP
In this project I go through a standard NLP workflow of processing text, tokenizing, stemming, removing punctuation/stop words and then create a word cloud visualization using a word frequency distribution.

:

📚 Moby Dick Word Cloud Project
Overview
This project processes the complete text of Moby Dick to generate a word cloud visualizing the most frequent terms in the novel. The project demonstrates fundamental NLP preprocessing techniques using R and the tm, wordcloud, and ggplot2 packages.

Features
Web scraping or file import for full text processing.

Text cleaning: lowercasing, removing numbers, stopwords, punctuation, and whitespace.

Word frequency calculation and ranking.

Beautiful word cloud generation using wordcloud and RColorBrewer.

Project Structure
mobydick_wordcloud.Rmd — R Markdown script for full analysis and visualization

mobydick.txt — Text file containing the raw novel

Output — Word cloud image rendered via RMarkdown

<img width="1202" height="912" alt="image" src="https://github.com/user-attachments/assets/40cbeee4-fb1e-45a2-9153-2a8c811812e4" />


How to Run
r
Copy
Edit
# Install necessary packages
install.packages(c(\"rvest\", \"tidyverse\", \"dplyr\", \"ggplot2\", \"tm\", \"SnowballC\", \"wordcloud\", \"RColorBrewer\"))

# Open the R Markdown file and click 'Knit'
Or run directly in RStudio:

r
Copy
Edit
rmarkdown::render(\"mobydick_wordcloud.Rmd\")
Example Output
(replace with your actual image)

Key Learnings
🧹 Text preprocessing pipeline in R.

🎨 Word cloud visualizations for textual data.

📊 Basic NLP pipeline applicable to any unstructured text data.

Possible Extensions

Exclude custom stopwords like character names (Ahab, Ishmael).

Build an interactive Shiny app allowing users to adjust word cloud parameters.

Author
Created by Jason Finkle — passionate about data visualization and natural language processing.


