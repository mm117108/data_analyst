FROM python:3.11-buster
COPY app.py .
COPY requirements.txt .
COPY model.pkl .
EXPOSE 5000
RUN pip install -r requirements.txt
CMD python3 app.py
