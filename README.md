# Image Forgery Detection Streamlit App

This is a Streamlit-based Python Web Application for detecting whether an image forgery detection, Deployed using Microsoft Azure and Docker.
LIVE URL : 
https://tsp-image-forgery.azurewebsites.net 

## Overview

This application provides a user-friendly interface for detecting image forgery using the model which has been created various techniques such as Image Preprocessing, 
Image Manipulation Detection,  Tampering Detection, and Deep Learning-based CNN approaches. Users can upload an image and the app will analyze it to detect any signs of 
forgery or manipulation and it also gives us the confidence with which model may be accurate.

## Features

- **Upload Image**: Users can upload an image directly through the app interface.
- **Forgery Detection**: The app utilizes advanced algorithms to analyze the uploaded image and detect any signs of forgery or manipulation.
- - **Confidence Interval**: Also this app gives us the confidence interval of it's prediction out of 100.
- **Real-Time Analysis**: The forgery detection process is carried out in real-time, providing instant results to the users.
- **User-Friendly Interface**: The app interface is designed to be intuitive and easy to use, allowing users to analyze images without any technical expertise.

## Deployment

### Microsoft Azure

The application is deployed on Microsoft Azure, leveraging its cloud services for hosting and scalability. Azure provides a reliable and secure environment for running the app.

### Docker

Docker is used for containerizing the application, ensuring consistency in deployment across different environments. Docker simplifies the deployment process and enables easy scaling of the application.

## Usage

To use the Image Forgery Detection app:

1. Visit the deployed URL of the application.
2. Upload an image using the provided interface.
3. Wait for the analysis to complete.
4. View the results indicating whether the image shows any signs of forgery or manipulation.

## Development

### Technologies Used

- Python
- Python Libraries
- Streamlit
- Azure
- Docker

### Running Locally

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Streamlit app using `streamlit run FRONTEND.py`.
4. Access the app through the provided local URL.

## Contributors

- PIYUSH SINGH [https://github.com/45Piyush]
- ABHISHEK KHOND [https://github.com/AbhishekKhond005]
- SAIF KHAN [https://github.com/Saifkhan-rkp]
- DEVASHISH JAYBHAYE [https://github.com/Devashish1910]

## License

This project is licensed under the [MIT License](LICENSE).
