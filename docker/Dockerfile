# Step 1: Base image
FROM python:3.11-slim

# Step 2: Set working directory inside container
WORKDIR /app

# Step 3: Copy dependency file first (layer caching optimization)
COPY app/requirements.txt .

# Step 4: Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Step 5: Copy application source code
COPY app/ .

# Step 6: Expose application port
EXPOSE 5000

# Step 7: Define container startup command
CMD ["python", "main.py"]
