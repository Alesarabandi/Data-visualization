# Dynamic Data Visualization with R

## Overview

This repository showcases a wide variety of data visualization techniques using R. The focus is on exploring multiple visualization methods, ranging from classic 2D plots to interactive 3D models, applied across different datasets. By leveraging libraries such as ggplot2, plotly, and igraph, this project demonstrates how effective visual representation can unveil deep insights from data, whether it’s categorical distributions, temporal trends, or relationships between variables.
## Key Techniques

- **Bar Charts & Histograms**: Explore categorical and numerical distributions across dimensions like country, genre, or customer satisfaction.
<p align="center">
    <img src="https://github.com/user-attachments/assets/14020e4d-7d2b-40a4-8717-803566c287ef" alt="description" width="500"/>
</p>


- **Density and Violin Plots**: Compare distributions of continuous variables, such as consumer spending across genders.
<p align="center">
    <img src="https://github.com/user-attachments/assets/cfbc3c22-a9cc-479d-81b0-a95f425b29de" alt="description" width="500"/>
</p>

- **Boxplots**: Highlight statistical summaries and variability within datasets, helping to quickly identify outliers and medians.
<p align="center">
    <img src="https://github.com/user-attachments/assets/a8933c6c-c201-4d31-94f1-5ccfe25a0d5d" alt="description" width="500"/>
</p>

- **Hexbin & Multivariate Visualizations**: Identify trends and relationships between key numerical variables, such as sales data or movie scores.
<p align="center">
    <img src="https://github.com/user-attachments/assets/ec92b388-9b2a-47fd-8b71-9ab1a099794f" alt="description" width="500"/>
</p>

- **3D Visualizations**: This interactive 3D visualization of World Cup data provides an engaging and insightful experience, allowing users to explore the relationships between key performance metrics—number of goals, assists, and passes—across different teams.

Key Features of the Visualization:

**Dynamic Exploration:** Users can rotate and zoom into the 3D plot, providing a comprehensive view of how each team's performance metrics relate to one another in a spatial context. This flexibility enables a deeper understanding of the data from various angles.

**Color-Coded Teams:** Each team is represented by a unique color, making it easy to distinguish between them. This visual differentiation enhances the interpretability of the plot and allows for quick comparisons between teams.

**Interactive Tooltips:** Hovering over each data point reveals detailed information about individual team performances, including specific values for goals, assists, and passes. This feature allows users to gain insights without cluttering the visualization, maintaining a clean aesthetic.

**Customizable Size:** The size of the points can be adjusted to represent additional dimensions, such as the number of matches played or player statistics, enabling users to customize their view based on their interests.

**Engaging User Experience:** The combination of 3D space and interactivity invites users to explore the data actively, promoting a hands-on approach to data analysis. This engagement not only makes the data more accessible but also enhances retention of insights gained.
<p align="center">
    <img src="https://github.com/user-attachments/assets/3cf74db1-3f6e-4590-8f72-d7f8cb0f4e79" alt="Screenshot 2024-10-24 at 16 39 30" width="500"/>
</p>

- **Tree Maps**: Represent categorical hierarchies and textual information using advanced layout designs.
  
<p align="center">
    <img src="https://github.com/user-attachments/assets/055edd09-b2b3-477f-a4d4-46c4c57a5bab" alt="Tree Map" width="500"/>
</p>
<p align="center">This tree map shows the number of episodes directed by different directors.</p>


- **Word Cloud**: The interactive word cloud generated using the wordcloud2 library transforms textual data into a visually engaging representation. With its unique star-shaped layout, this visualization captures attention while effectively showcasing the prominence of various words within the dataset.

Key features include:

**Dynamic Interaction:** As users hover over each word, they are presented with precise frequency counts, indicating how many times that specific word appears in the document. This interactivity allows for deeper insights into the text, facilitating an understanding of word significance and context.

**Visual Appeal:** The choice of a black background accentuates the vivid colors of the words, making them stand out strikingly. The star shape adds a playful yet sophisticated touch, inviting users to explore the data creatively.

**Custom Typography:** Utilizing the "Loma" font enhances readability and provides an elegant touch, ensuring that users can easily navigate the visualization while enjoying its aesthetic quality.

<p align="center">
    <img width="500" alt="Screenshot" src="https://github.com/user-attachments/assets/c2698594-e03d-45cf-b04f-08cbc3305d35"/>
</p>
<p align="center"></p>


- **Time Series**: Visualize temporal trends, such as the progression of customer purchases or changes in viewership.

<p align="center">
    <img src="https://github.com/user-attachments/assets/9cec1660-3da5-433c-914f-13c9c5866b6a" alt="Description of the image" width="500"/>
</p>
<p align="center">This visualization provides a comprehensive overview of the data, showcasing key patterns and trends effectively.</p>


## Key Libraries Used
- **ggplot2**: The foundation for 2D visualizations.
- **plotly**: For interactive 3D graphs.
- **igraph**: Network visualizations for complex datasets.
- **treemap & wordcloud2**: To visualize hierarchical and textual data in creative ways.

## How to Run

To replicate the visualizations, clone this repository and install the necessary R packages:

```r
install.packages(c('dplyr', 'ggplot2', 'plotly', 'igraph', 'wordcloud2', 'treemap'))
