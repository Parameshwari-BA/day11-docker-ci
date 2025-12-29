# 1. Use a base image that already has Python
FROM python:3.10-slim

# 2. Set working directory inside the container
WORKDIR /app

# 3. Copy all files from your folder to the container
COPY . /app

# 4. Install Flask (required for our app)
RUN pip install flask

# 5. Command to run when container starts
CMD ["python", "app.py"]
