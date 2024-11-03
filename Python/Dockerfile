FROM python:3.9

# appp ---> app
WORKDIR /app

# appy.py ---> app.py
COPY app.py /app

# netiface ---> netifaces 
RUN pip install flask netifaces

# "eight thousand" ---> 8000
EXPOSE 8000

# pythn ---> python
CMD ["python", "app.py"]