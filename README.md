# Healthcare Insurance Cost Analysis

**Healthcare Insurance Cost Analysis** is a comprehensive data analysis project designed to explore the relationship between individual attributes, geographic regions, and healthcare insurance charges. The goal is to develop a better understanding of what factors drive insurance costs and to build predictive models that estimate these expenses accurately.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
The dataset used in this project is from [Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/healthcare-insurance) and includes demographic and health-related information such as:

- Age
- Gender
- Body Mass Index (BMI)
- Number of children
- Smoking status
- Region (geographic)
- Insurance charges

This data contains **1338 rows** and is relatively clean with no missing values, making it ideal for exploratory analysis and predictive modeling.

## Business Requirements
- Understand how personal attributes and regional factors influence healthcare insurance costs.
- Provide actionable insights to policy makers, insurance companies, and customers.

## Hypothesis and how to validate?
* Hypothesis 1: Smokers are charged significantly more for health insurance than non-smokers.
* Hypothesis 2: BMI and insurance charges have a positive correlation.
* Hypothesis 3: Insurance charges are the same regardless of number of children. 
* Hypothesis 4: People from different regions pay different insurance charges.

## Project Plan
* Data Collection
    * ETL Pipeline (ETLPipeline.ipynb)
* ETL Pipeline (ETLPipeline.ipynb)
    * Loaded and cleaned data (checked for nulls, types).
    * Encoded categorical variables.
    * Exported cleaned dataset for analysis.
* Exploratory Analysis (initial_visualisation.ipynb)
    * Created multiple visualizations to identify trends, patterns, and anomalies.
    * Analyzed relationships between attributes and insurance charges.

## The rationale to map the business requirements to the Data Visualisations
* **Smoking Status vs. Charges** → Box Plot to visualize cost disparity.
* **BMI vs. Charges** → Scatter Plot with trendline to observe correlation.
* **Age vs.Charges** → Scatter Plot to observe correlation.
* **Region vs. Charges** → Box Plot or Violin Plot to compare region-wise trends.
* **Children Count vs. Charges** → Bar Graph to observe whether dependents impact charges.

## Analysis techniques used
* **Data Preprocessing:** Handled data types and encodings using Pandas.
* **Visualization Tools:** Plotly, Seaborn and Matplotlib for insightful, clean plots.
* Limitations:
    * The dataset lacks information on pre-existing medical conditions, income levels, or employment, which may also influence costs.
* Generative AI Usage:
    * Used to brainstorm visualization types, code refactoring, and interpret statistical results more effectively.


## Dashboard Design
* The Healthcare Insurance Cost Analysis Dashboard was designed to provide clear, actionable insights into the factors influencing health insurance prices. It includes multiple pages with interactive elements to help both technical and non-technical audiences understand cost drivers.

### **Design Approach**
* I used PowerBI to build a dashboard. To review the dashboard, please download the .pbix file from the [# dashboard] folder and open it locally on your system.


* The dashboard was designed with accessibility and clarity in mind:
    * Used interactive filters and widgets to allow users to explore “what-if” scenarios.
    * Combined statistical analysis with visual storytelling so that both technical users (analysts, developers) and non-technical users (managers, policymakers) can extract value.
    * Structured the navigation into clear pages (Overview → Demographics → Lifestyle → Predictions) to guide users from general insights to deeper analytical layers.


## Unfixed Bugs
* None currently reported. All preprocessing and visualizations executed without errors.

## Development Roadmap
* Challenges Faced:
    * Balancing readability and complexity in visualizations.
    * Understanding encoding impacts on analysis.
* Next Steps:
    * Implement an interactive Dash dashboard.


## Main Data Analysis Libraries
* **Pandas** — For data manipulation.
* **Seaborn** — For statistical plotting.
* **Matplotlib** — For basic plot customization.
* **Plotly** — For interactive and dynamic visualizations.

## Credits 
* **Content:**
    * Dataset Source: Kaggle
    * Project structure and inspiration from Code Institute coursework
    * Code optimization ideas: GitHub community notebooks, ChatGPT, and Code Institute LMS content

## Acknowledgements (optional)
* Special thanks to Code Institute mentors and community for guidance throughout this project.