# Use the official Python image as the base image

FROM python:3

# Set the working directory within the container
WORKDIR /app

#COPY the application files to the container
COPY  . . 

# Install FLASK and other dependencies
RUN pip install requirements.txt 

# Specify the command to run when the container starts
CMD ["python", "app.py"]