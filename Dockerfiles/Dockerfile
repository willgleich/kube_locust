FROM python:3.7

RUN pip3 install locustio

ENTRYPOINT locust -f /locust/locustfile.py --slave --master-host=$HOST_IP
