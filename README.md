# Data Processing Application with Flask
## Corporatica Backend Task Intern

Here is the interface of the project:
![Interface](https://github.com/user-attachments/assets/2debb49b-4506-4aee-a418-909fb89ad629)



## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Project Hierarchy](#project-hierarchy)
- [Time Allocation](#time-allocation)
- [Methodology](#methodology)
- [Contributing](#contributing)
- [License](#license)

## Overview
This project is a Flask-based web application for image processing and data management. It allows users to upload images and perform various operations like resizing, cropping, generating histograms, and segmentation masks. Additionally, it provides functionalities to handle textual and tabular data.

## Features
- **Image Processing**: Upload, resize, crop, convert formats, generate histograms, and create segmentation masks.
- **Textual Data Processing**: Summarization, keyword extraction, sentiment analysis, TSNE visualization, search, categorization, and custom queries.
- **Tabular Data Management**: Upload, query, process, visualize, and manage tabular data.

## Technologies
- **Backend**: Flask, SQLAlchemy, PostgreSQL
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Image Processing**: OpenCV, Pillow (PIL)
- **Data Processing**: Pandas, Numpy, TextBlob, YAKE, sklearn
- **Deployment**: Docker, Docker Compose

## Setup Instructions

### Prerequisites
- Docker
- Docker Compose

### Installation
1. **Clone the Repository**
    ```sh
    git clone https://github.com/Mostafa10770/Corporatica-back-end-Intern.git
    cd Corporatica-back-end-Intern
    ```

2. **Build and Run with Docker Compose**
    ```sh
    docker-compose up --build
    ```

3. **Access the Application**
    Open your web browser and navigate to `http://localhost:5005`.

## Usage
1. **Uploading Images**
    - Navigate to the image processing section.
    - Upload your images and perform operations like resizing, cropping, converting, generating histograms, and segmentation masks.

2. **Handling Textual Data**
    - Navigate to the textual data section.
    - Use functionalities like summarization, keyword extraction, sentiment analysis, TSNE visualization, search, categorization, and custom queries.

3. **Managing Tabular Data**
    - Navigate to the tabular data section.
    - Upload your tabular data files, perform queries, process, visualize, and manage the data.

## Project Hierarchy

```
CORPORATICA BACK-END INTERN
│
├── .vscode/
│   └── settings.json
├── backend/
│   ├── __init__.py
│   ├── routes/
│   │   ├── __init__.py
│   │   ├── image_routes.py
│   │   ├── text_routes.py
│   │   └── tabular_routes.py
│   └── models/
│       ├── __init__.py
│       ├── example_model.py
├── instance/
│   └── config.py
├── results/
│   └── (result files)
├── static/
│   ├── scripts.js
│   └── styles.css
├── templates/
│   ├── image_data.html
│   ├── index.html
│   ├── IndexAll.html
│   ├── tabular_data.html
│   ├── text_index.html
│   └── textual_data.html
├── uploads/
│   └── (uploaded files)
├── .gitignore
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── app.py
├── appAll.py
└── README.md
```

## Time Allocation
- **Research**: 10 hours
- **Development**: 25 hours
- **Testing**: 7 hours
- **Deployment**: 10 hours

## Methodology
### Development Methodology
The project was developed using an iterative and incremental approach. The following steps outline the development methodology:

1. **Requirements Analysis**: Understanding the project requirements and defining the scope.
2. **Technology Selection**: 
    - **Flask**: Chosen for its simplicity and flexibility in creating web applications.
    - **SQLAlchemy and PostgreSQL**: For database management and operations.
    - **OpenCV and Pillow**: For comprehensive image processing capabilities.
    - **Pandas and Numpy**: For efficient data handling and processing.
    - **TextBlob, YAKE, sklearn**: For natural language processing and machine learning functionalities.
3. **Development**: Incremental development of features with continuous integration and testing.
4. **Testing**: Conducting unit tests and integration tests to ensure functionality and reliability.
5. **Deployment**: Using Docker and Docker Compose for containerized deployment to ensure consistency across different environments.

### Selection Criteria for Technologies
- **Ease of Use**: Technologies and libraries that are easy to integrate and use.
- **Community Support**: Libraries and frameworks with strong community support and extensive documentation.
- **Performance**: Tools that offer optimal performance for image processing and data handling.
- **Scalability**: Technologies that can scale with increasing data and user load.

### Visuals

Here is the interface of the project:
![Interface](https://github.com/user-attachments/assets/2debb49b-4506-4aee-a418-909fb89ad629)

Here is a T-SNE visualization from the text processing:
![T-SNE Visualization](https://github.com/user-attachments/assets/130d55bc-a58c-4878-9bcd-a39d9f45a25a)

Here is a visualization from the tabular data task:
![Tabular Data Visualization](https://github.com/user-attachments/assets/dc7903c7-dcb7-4edd-af70-b3d3fe38871d)

Here is a test from the image part:
![Image Test](https://github.com/user-attachments/assets/5c991a50-f8b9-4814-bdf9-8c6ea3b8e501)


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
