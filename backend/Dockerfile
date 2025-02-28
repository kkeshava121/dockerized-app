# Use official Python image
FROM python:3.9

# Set the working directory
WORKDIR /app

# Copy application files
COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .

# Expose API port
EXPOSE 5000

# Run the application
CMD ["python", "app.py"]

