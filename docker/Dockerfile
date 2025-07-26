# Use Python Base Image
FROM python:3.10-slim

# Set Working Dir
WORKDIR /app

# Copy requirements and install
COPY requirements.txt . 
RUN pip install --no-cache-dir -r requirements.txt

# Copy app Code
COPY . .

# Expose app Port
EXPOSE 5000

# RUN the app
CMD ["python", "app.py"]

