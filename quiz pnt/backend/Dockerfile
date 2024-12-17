# Gunakan base image Python
FROM python:3.9

# Tentukan direktori kerja di container
WORKDIR /app

# Salin file aplikasi ke dalam container
COPY C:/Users/User/Documents/quiz\ pnt/backend/ /app/

# Install dependensi dari requirements.txt
RUN pip install --no-cache-dir -r /app/requirements.txt

# Ekspos port 5000
EXPOSE 5000

# Jalankan aplikasi Flask
CMD ["python", "/app/app.py"]
