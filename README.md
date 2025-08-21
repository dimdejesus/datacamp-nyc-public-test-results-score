# Project: Exploring NYC Public School Test Result Scores
Datacamp's second project in Associate Data Science Roadmap.

## Description
![alt text](./schoolbus.jpg)

Photo by [Jannis Lucas](https://unsplash.com/@jannis_lucas) on [Unsplash](https://unsplash.com).
<br>

Every year, American high school students take SATs, which are standardized tests intended to measure literacy, numeracy, and writing skills. There are three sections - reading, math, and writing, each with a **maximum score of 800 points**. These tests are extremely important for students and colleges, as they play a pivotal role in the admissions process.

Analyzing the performance of schools is important for a variety of stakeholders, including policy and education professionals, researchers, government, and even parents considering which school their children should attend. 

You have been provided with a dataset called `schools.csv`, which is previewed below.

You have been tasked with answering three key questions about New York City (NYC) public school SAT performance.

### The Data (**netflix_data.csv**)
| Column | Description |
|--------|-------------|
| `school_name` | Name of the School |
| `borough` | A town or district |
| `building_code` | The code of the building |
| `average_math` | Average Math Score |
| `average_reading` | Average Reading Score |
| `average_writing` | Average Writing Score |
| `percent_tested` | Percentage of people tested |

## Questions and Answer
What I'll be placing in the answer are just text format please refer to [notebook.ipynb](./notebook.ipynb) for the code 

**Question #1**: Which NYC schools have the best math results?

**Answer**: The school with the best math result is Stuyvesant High School.

**Question #2**: What are the top 10 performing schools based on the combined SAT scores?

**Answer**: The top 10 performing schools based on combined SAT scores are the following (in order).
| TOP 10 SCHOOLS | Total SAT Score |
|--------|-------------|
| `Stuyvesant High School` | 2144 |
| `Bronx High School of Science` | 2041 |
| `Staten Island Technical High School` | 2041 |
| `High School of American Studies at Lehman College` | 2013 |
| `Townsend Harris High School` | 1981 |
| `Queens High School for the Sciences at York College` | 1947 |
| `Bard High School Early College` | 1914 |
| `Brooklyn Technical High School` | 1896 |
| `Eleanor Roosevelt High School` | 1889 |
| `High School for Mathematics, Science, and Engineering at City College` | 1889 |

**Question #3**: Which single borough has the largest standard deviation in the combined SAT score?

**Answer**: The borough with a largest standard deviation is Manhattan with 89 schools and an average SAT score of 1340.13 with 230.29 standard deviation.

## Analysis Steps
1. Data Loading: Used the given `schools.csv` to analyze
2. Data Exploration: Look into the data and take advantage of what it gives
3. Data Processing: Use python, pandas, and numpy to filter the data to produce an answer to the question provided.

## Libraries used
* Python
* Pandas
* Numpy

## How to run
1. Clone this repo through https or ssh.
2. Run this on virtual env `you don't want your local python setup to be messy ;)`
3. Run this command
```
pip install -r requirements
```
4. Open it through Jupyter Notebook, VS Code, or any text editor that you use.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgement
* **Datacamp's** Associate Data Science in Python
* **Datalab** - I only placed it here because I used only the free versioon which limits me to 3 workbooks only




