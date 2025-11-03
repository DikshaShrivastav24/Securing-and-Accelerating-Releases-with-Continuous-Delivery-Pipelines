# Step 1: Use official Python base image
FROM python:3.10-slim

# Step 2: Set working directory
WORKDIR /app

# Step 3: Copy project files into container
COPY . .

# Step 4: Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Step 5: Expose port 5000 (Flask default)
EXPOSE 5000

# Step 6: Run Flask app
CMD ["python", "app.py"]
