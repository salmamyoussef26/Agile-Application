FROM python:3.9
WORKDIR /final_task_app
COPY requirements.txt /final_task_app
RUN pip install -r requirements.txt 
COPY . /final_task_app
CMD ["python", "hello.py"]
