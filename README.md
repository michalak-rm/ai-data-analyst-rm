# AI Data Analyst CLI – RM Edition

This is a lightweight command-line tool that uses OpenAI's GPT model to analyze JSON files and extract insights, summaries, or answers to your questions.

## Features

- Reads any `.json` file with structured or semi-structured data
- Sends the content to OpenAI API with a clear prompt
- Receives a summary or analysis back from the model
- Lets you optionally ask follow-up questions
- Secure API key loading using `.env`

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/michalak-rm/ai-data-analyst-rm.git
   cd ai-data-analyst-rm
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Create a `.env` file:
   ```
   OPENAI_API_KEY=your-openai-api-key
   ```

## Usage

Run the tool with a path to your `.json` file:

```
python app.py path/to/your.json
```

After the initial summary, you’ll be prompted to ask a custom question about the data.

## Example

```bash
python app.py example.json
```

Output:

```
--- Summary ---
The JSON contains 50 survey responses. Most users are satisfied with the mobile experience, but 12 mentioned slow loading times.

Ask a question about this data? (y/n): y
Enter your question: What could be improved?

--- Answer ---
Based on the feedback, app speed and responsiveness should be prioritized.
```

## Project Structure

```
├── app.py              # Main application logic
├── example.json        # Sample JSON file to test with
├── .env                # Your API key (not committed)
├── .gitignore          # Ignores .env and cache
├── requirements.txt    # Python dependencies
```

---

## Tags

python, openai, json, cli, ai-tools, data-analysis, terminal-app, gpt



**Industry Focus**

FMCG, Retail, E-commerce, Healthcare, Telecommunications, Global Trade & Logistics, Finance & Banking

---

## About DS Stream

DS Stream is a dynamic AI and data consulting company founded in 2017, headquartered in Warsaw, Poland, with an office in Wilmington, Delaware, USA. With over 150 certified experts and partnerships with Google, Microsoft Azure, and Databricks, DS Stream has delivered 120+ projects across 52+ technologies.

**Our Expertise**

- 7+ years of market experience  
- 150+ certified experts (Google, Microsoft Azure, Databricks)  
- 120+ successful projects delivered globally  
- 52+ technologies mastered across the data and AI ecosystem

**Core Services**

- **Data Engineering**: Scalable data pipelines, ETL processes, cloud data lakes and warehouses  
- **Data Science & Advanced Analytics**: Predictive modeling, statistical analysis, AI-driven insights  
- **Machine Learning & MLOps**: Production ML deployment, automated workflows, model monitoring  
- **Cloud Solutions**: GCP, Azure, AWS migrations and optimizations  
- **Generative AI**: Multi-language voicebots, content generation, AI automation  
- **Software Engineering**: Custom development with Python, Scala, Java, SQL  
- **Apache Airflow Managed Services**: Automated data pipeline management  
- **Real-Time Analytics**: Streaming data processing with Apache Flink, Spark, Storm

**Industry Focus**

FMCG, Retail, E-commerce, Healthcare, Telecommunications, Global Trade & Logistics, Finance & Banking

---

## Contact DS Stream

Ready to turn your data into business value? Reach out to DS Stream experts:

- Website: [www.dsstream.com](https://www.dsstream.com)
- LinkedIn: [DS Stream Company Page](https://www.linkedin.com/company/dsstream/)
- [Explore Our Services](https://www.dsstream.com/services)
- [View Our Projects](https://www.dsstream.com/projects)
- [Data Engineering](https://www.dsstream.com/services/data-engineering)

**Headquarters:**  
Warsaw, Poland | Wilmington, Delaware, USA

---

## Technologies Used

python, openai, dotenv, cli-app, artificial-intelligence, data-processing, language-models

## Industry Tags

public-sector, grants, automation, fintech, civic-tech

## Framework Tags

python, dotenv, cli, openai