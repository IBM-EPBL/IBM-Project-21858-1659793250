# FROM python:3.6.1-alpine
# RUN pip install --upgrade pip
# WORKDIR C:\Users\admin\Desktop\ibm_project
# ADD C:\Users\admin\Desktop\ibm_project .
# RUN pip install -r requirements.txt
# CMD ["python","application.py"]



FROM python:3.10.6
WORKDIR /application
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5000
CMD ["python","./application.py"]