FROM python:3.8
RUN pip install --upgrade pip
WORKDIR /usr/src/app    

COPY requirements.txt ./  
RUN pip install --no-cache-dir -r requirements.txt

COPY . .    

EXPOSE 6666

CMD [ "python", "./Server.py" ]
