# CureAssist

This model predicts the similar symtpoms based on the symptoms given to the model.

First part deals with scraping the data from website I have scraped 3000 pages from WebMD. In this I have scraped information including Symptom, Symptom description, Other Symptoms which were present on the page, and these symptoms summarized descriptions which were present on the page. I have also provided each URL for the webpage in the scraped data.

In the second part, I have utilized partial data from the scraped data to generate a frequency table over the whole data. After this, I implemented TF-IDF and also K-Nearest Neighbors to identify similar symptoms.
