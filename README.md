# BellyButton-Dashboard-Ch14

## Project Overview
- The Belly Button Biodiversity Dashboard is an interactive web application designed to visualize microbial data collected from human belly buttons.
- The app uses a dataset from the [Belly Button Biodiversity Project](http://robdunnlab.com/projects/belly-button-biodiversity/), showcasing information such as operational taxonomic units (OTUs) and demographic metadata.
- Users can explore the data through a dropdown menu, horizontal bar charts, and bubble charts.

## Features
- **Dynamic Bar Chart**: Displays the top 10 OTUs for the selected individual.
- **Interactive Bubble Chart**: Shows all OTUs for the selected sample with marker size and color representing sample values.
- **Metadata Panel**: Displays demographic information for the selected individual.
- **Dropdown Menu**: Allows users to select a test subject ID and update the charts and metadata dynamically.

## Technologies Used
- **HTML5 & CSS3**: For creating the structure and styling of the web page.
- **JavaScript (D3.js & Plotly.js)**: For data handling, chart generation, and interactivity.
- **Bootstrap**: For responsive design and layout.
- **GitHub Pages**: For project deployment.

## Files and Folders
- **`index.html`**: The main HTML file containing the dashboard structure.
- **`app.js`**: The JavaScript file handling data fetching, chart rendering, and event handling.
- **`samples.json`**: The JSON file containing microbial and demographic data.
- **`README.md`**: Project documentation.
- **`static/`**: Folder containing any additional scripts or styles (optional).


### Open the Project
- Navigate to the project directory.
- Open `index.html` in your browser.

### Explore the Dashboard
- Use the dropdown menu to select a test subject ID.
- View the corresponding bar chart, bubble chart, and demographic metadata.


---

## Dataset
The dataset includes:
- **Samples**: Microbial species data, including `otu_ids`, `otu_labels`, and `sample_values`.
- **Metadata**: Demographic information such as age, gender, ethnicity, and belly button type.


---

## Example Screenshots
### Dashboard Layout:
![1](https://github.com/user-attachments/assets/7eea348e-db48-4a16-8b0b-acdca65b9a27)

### Bubble Chart:
![newplotplot](https://github.com/user-attachments/assets/84e8b19b-f0e8-4671-bbce-49b0554d83d4)

### Bar Chart:
![newplotbar](https://github.com/user-attachments/assets/a27e645c-d39e-44dc-a962-52345a08b519)

---

## Project Structure
```plaintext
├── index.html
├── app.js
├── samples.json
├── README.md
├── static/
│   ├── css/
│   ├── js/


## Key Functionalities

### Bar Chart
- Top 10 OTUs displayed horizontally.
- Includes OTU IDs as labels and hovertext.

### Bubble Chart
- Displays all OTUs for the selected sample.
- Marker size represents `sample_values`, and marker color represents `otu_ids`.

