FROM python:3.13.0b1-alpine
LABEL author="khaja"
RUN apk add git && git clone https://github.com/khajasampleapps/basicflask.git
WORKDIR /basicflask
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python", "app.py"]