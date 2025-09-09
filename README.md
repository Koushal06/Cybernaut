````markdown
# Indeed Job Scraper using Apify API

This Python project allows you to scrape job listings from [Indeed](https://www.indeed.com) using the Apify platform. It fetches job listings based on the job title you input, processes the data, and saves it into a clean Excel file.

---

## 🚀 Features

- Scrapes job listings from Indeed with specified job title.
- Cleans job description HTML to plain text.
- Collects important fields:
    - Job Title
    - Company
    - Location
    - Salary
    - Job Type
    - Rating
    - Reviews
    - Posted Date
    - Apply Link
    - Job Description
- Saves results to a structured Excel file.

---

## ✅ Prerequisites

- Python 3.7 or later
- Pip package manager

### Required Python packages

Install dependencies using:

```bash
pip install requests pandas beautifulsoup4 python-dotenv
````

---

## ⚡ Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/indeed-job-scraper.git
   cd indeed-job-scraper
   ```

2. Create a `.env` file in the project root directory and add your Apify credentials:

   ```env
   APIFY_TOKEN=your_apify_token
   ACTOR_ID=your_apify_actor_id
   ```

3. Run the script:

   ```bash
   python job_scraper.py
   ```

4. Enter the job title when prompted.

---

## 📁 Output

After successful execution, an Excel file will be created in the same directory, named as:

```
full stack_cleaned_jobs.xlsx
```

This file contains all the cleaned job data fetched from Indeed.

---

## ⚡ Notes

* The scraper uses the Apify Actor, so ensure your Apify account is active and has sufficient credits.
* The process may take a few minutes depending on the number of jobs requested.

---

## 📄 License

This project is licensed under the MIT License.

---

## ❤️ Contributing

Feel free to open issues or submit pull requests for improvements.

---

Made with ❤️ by Koushal V
