# NBA Player Stats Explorer

This application allows users to explore NBA player statistics for different years. 
It utilizes web scraping to gather data from Basketball-reference.com 
and presents the data in an interactive Streamlit web application.

### Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Example](#example)
- [Credits](#credits)
- [License](#license)

### Installation

#### Prerequisites

- Python 3.6 or higher
- Streamlit
- pandas
- matplotlib
- seaborn
- numpy

#### Installation Steps

1. Clone the repository:

    ```sh
    git clone https://github.com/yourusername/nba-player-stats-explorer.git
    cd nba-player-stats-explorer
    ```

2. Create a virtual environment and activate it (optional but recommended):

    ```sh
    python -m venv env
    # On Windows
    env\Scripts\activate
    # On macOS/Linux
    source env/bin/activate
    ```

3. Install the required packages:

    ```sh
    pip install -r requirements.txt
    ```

### Usage

To run the application, navigate to the project directory and use the following command:

```sh
streamlit run EDA_basketball.py
