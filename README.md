# User Behavior and Order Trends Analysis upliance.ai

## Overview
This project involves analyzing datasets related to user behavior, cooking preferences, and order trends. The objective is to extract meaningful insights, create visualizations, and provide business recommendations to enhance user engagement and optimize sales.

## Objectives
1. Analyze the relationship between cooking sessions and user orders.
2. Identify popular dishes and their impact on revenue.
3. Explore demographic factors influencing user behavior.
4. Provide actionable business recommendations based on findings.

## Datasets
- **UserDetails**: Contains demographic information (e.g., age, gender, location).
- **CookingSessions**: Details of user cooking activities (e.g., session dates, durations, recipes).
- **OrderDetails**: Records of user orders (e.g., order dates, items, and values).

## Methodology
1. **Data Cleaning**:
   - Handled missing values and removed duplicates.
   - Standardized formats for dates and categorical variables.
2. **Data Merging**:
   - Combined datasets using common keys like User ID.
3. **Analysis**:
   - Explored relationships between cooking sessions and orders.
   - Identified top-performing dishes.
   - Analyzed demographic influences on user behavior.
4. **Visualization**:
   - Used bar charts, line graphs, and heatmaps to represent findings.

## Key Insights
- Cooking sessions positively influence order frequency and value.
- Top 5 popular dishes contribute to over 40% of total revenue.
- Younger users (18-25) and urban residents exhibit higher engagement in both cooking and ordering.

## Recommendations
- Focus marketing efforts on popular dishes to maximize revenue.
- Create personalized offers for younger users and urban demographics.
- Implement engagement strategies, such as cooking challenges, to encourage more sessions.

## Visualizations
Key visualizations include:
- **Bar Chart**: Popular dishes by order count and revenue.
- **Heatmap**: Correlation between demographics and order trends.
- **Line Graph**: Trends in order volume over time.

## Technologies Used
- **Python Libraries**:
  - `pandas`: Data cleaning and manipulation.
  - `numpy`: Numerical computations.
  - `matplotlib` and `seaborn`: Data visualization.
- **Tools**:
  - Jupyter Notebook for analysis and documentation.

## Repository Structure
```plaintext
├── data/                  # dataset orignal and cleaned
├── notebooks/             # Jupyter notebooks for analysis
├── report/                # Final report (PDF/Markdown)
├── README.md              # Project documentation
```
## How to Use

1. **Clone the Repository**  
   Clone this repository to your local machine using the following command:
   ```bash
   git clone  https://github.com/Ashutosh-parate/Upliance.git
   
2 .**Navigate to the Project Folder**
Move into the project directory:

**Install Dependencies**
Ensure you have Python 3.x installed. Install the required Python libraries by running:
```bash
pip install -r requirements.txt
```
**Run the Jupyter Notebook
```bash
jupyter notebook notebooks/uplianceAiProject.ipynb
```
