FROM nginx:latest

EXPOSE 8080
WORKDIR /app

COPY . ./

RUN pip install -r requirements.txt

CMD ["nginx", "app.py"]
