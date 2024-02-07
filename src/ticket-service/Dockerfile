FROM python:3.9
COPY . /ticket-service
COPY requirements.txt /ticket-service
WORKDIR /ticket-service
RUN pip install -r requirements.txt
EXPOSE 8070
CMD ["python3", "ticket-service.py"]
