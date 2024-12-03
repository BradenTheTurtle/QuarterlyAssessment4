# QuarterlyAssessment4

# fetch.py
This script fetches news articles from the NewsAPI based on a user-defined topic. It validates each article for missing fields and checks whether the URL is reachable before saving valid articles to a JSON file. The process includes error handling for issues like network problems or invalid API responses.

# summarize.py
This script summarizes articles using OpenAI's GPT model by generating concise summaries based on the article's title and content. It loads articles from a JSON file and processes each one to provide a two-sentence summary. The script also handles errors in case of issues with the summarization API or invalid data.

# sendemail.py
This script sends an email containing a summary of the latest articles, formatted in HTML, to a recipient. It loads articles from a JSON file, formats them into a readable structure with titles, descriptions, and links, and then sends the email using Gmail's SMTP server. The script supports secure login and handles errors in case of issues with the email sending process.

# articles.json
This file is where articles and their summaries are stored.