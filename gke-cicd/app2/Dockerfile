FROM nginx

EXPOSE 8081
WORKDIR /app2

COPY . ./

RUN pip install -r requirements.txt

CMD ["nginx", "app.py"]
