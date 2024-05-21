# GraphGrid Insights

![GraphGrid Insights Logo](https://github.com/ajafarsadiq2002/GraphGrid-Insights/blob/9c486ff843f8297bab751f422d6dc5b6d5594c62/HomePage.jpeg)

GraphGrid Insights is a powerful application designed to visualize, understand, segment, and optimize customer data. This tool allows users to upload CSV files and gain insights through data analysis and visual representation.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Contributing](#contributing)


## Installation

To install and run this project, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/GraphGridInsights.git
    cd GraphGridInsights
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    `venv\Scripts\activate`
    ```

3. **Install the required packages:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application:**

    ```bash
    python main.py
    ```

5. **Open your web browser and navigate to:**

    ```
    http://localhost:8000
    ```

## Usage

- Navigate through the homepage to access various data analysis features.
- Upload the CSV file you want to analyze.
- View and interact with the visual representations of your data.


## File Descriptions

- `main.py`: The main Flask application file.
- `requirements.txt`: Lists all the dependencies required to run the application.
- `templates/`: Contains all HTML templates for the web pages.
  - `index.html`: CSV upload page template.
  - `landingpage.html`: Landing page template.
- `static/`: Contains static files like images and CSS used in the application.
  - `logo.png`: Application logo.
  - `bg1.png`: Background image for the index page.
- `Mall Clustering Project.ipynb`: Jupyter notebook containing the analysis for the mall clustering project.
- `Mall_Customers.csv`: Sample CSV file used for analysis.

## Contributing

Contributions are welcome! Please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/fooBar`).
3. Commit your changes (`git commit -am 'Add some fooBar'`).
4. Push to the branch (`git push origin feature/fooBar`).
5. Create a new Pull Request.
