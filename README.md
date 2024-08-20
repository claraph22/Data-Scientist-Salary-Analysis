# Data-Scientist-Salary-Analysis
_Analyzing salary trends for Data Scientists in the United States using data from Glassdoor._

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project aims to analyze the salary trends of Data Scientists across the United States. By exploring this data, we can identify key factors that influence salary levels, such as experience, industry, and geographic location.

**Tools & Libraries Used:**
- Python
- pandas
- numpy
- matplotlib
- seaborn
- Tableau for visualization

This project is intended for data scientists, HR professionals, and anyone interested in understanding salary trends within the tech industry.

## Dataset

The dataset used in this analysis is sourced from Kaggle:

- **Source**: [Kaggle - Data Scientist Salary US Glassdoor](https://www.kaggle.com/datasets/nikhilbhathi/data-scientist-salary-us-glassdoor)
- **Size**: The dataset contains X entries and Y features.
- **Features**: The key features include job title, salary estimate, company rating, location, and more.
- **Preprocessing**: Missing data was handled, and categorical variables were encoded as needed.

**Assumptions & Limitations:**
- The data is limited to the US and may not reflect global salary trends.
- Salary estimates are based on reported figures and may not capture all forms of compensation.

## Project Structure

This project is organized as follows:

```plaintext
h8dsft_Milestone1_Clara.ipynb - Jupyter notebook containing the analysis
README.md                     - Project documentation
```

## Installation

To run the notebook, you will need the following:

- Python 3.x
- Jupyter Notebook

It's recommended to use a virtual environment:

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
```

Install required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

## Usage

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   ```

2. **Navigate to the project directory**:

   ```bash
   cd your-repo-name
   ```

3. **Open the Jupyter notebook**:

   ```bash
   jupyter notebook h8dsft_Milestone1_Clara.ipynb
   ```

4. **Run the cells** to perform the analysis. You can modify parameters or explore different parts of the dataset as needed.

## Results

The analysis yielded several key insights:
1. **Average Salary by State:**
   - **California (CA):** The highest average salary at approximately $18.67K.
   - **Massachusetts (MA):** Comes in second with an average salary around $10.32K.
   - Other states like Illinois (IL), New York (NY), and Virginia (VA) show varying salaries, with Virginia having the lowest among the highlighted states at $3.92K.

2. **Salary by Job Title:**
   - **Data Scientist** has the highest average salary at $13.91K.
   - **Data Engineer** and **Senior Data Scientist** follow with salaries around $4.85K and $4.51K, respectively.
   - **Lead Data Scientist** earns the least at $1.29K.

3. **Skills Demand:**
   - **Data Scientist** roles demand the most, with 240 mentions.
   - **Data Engineer** and **Analyst** are also in demand with 77 and 31 mentions respectively.

4. **Industry Insights:**
   - **Biotech & Pharmaceuticals** offer the highest average salary at $11.8K.
   - **Computer Hardware & Software** and **Insurance Carriers** follow with average salaries of $6.8K and $6.65K, respectively.
   - **IT Services** has the lowest average salary among the industries mentioned, around $5.14K.

5. **Geographic Trends (Company Location):**
   - The map shows California leading with the highest salary offers at $18.657.
   - Other states like Texas, New York, and Virginia also show significant numbers but are behind California in salary averages.

These insights provide a clear view of salary distributions, industry preferences, and regional trends for data scientists in the United States.

You can explore these findings in detail through the interactive Tableau dashboard:

- [Tableau Dashboard](https://public.tableau.com/app/profile/clara.putri.herlin/viz/DataScientistSalary_17176832170790/Dashboard1?publish=yes)

## Features

- **Data Cleaning**: Handling missing values and outliers.
- **Exploratory Data Analysis**: Visualizing trends across different features.
- **Visualization**: Creating insightful plots and charts.
- **Interactive Dashboard**: Analyzing trends through an interactive Tableau dashboard.

## Contributing

Contributions are welcome! If you have suggestions, feel free to submit an issue or pull request. For major changes, please discuss them in an issue first.

- **Report Bugs**: Use the issue tracker to report bugs.
- **Request Features**: You can request new features or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For questions, feedback, or contributions, contact:

- **Name**: Clara Putri Herlin
- **Email**: cputriherlin@gmail.com
- **LinkedIn**: [Clara Putri Herlin](https://www.linkedin.com/in/clara-putri-herlin)
