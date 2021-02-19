FROM swee/spark_submit:1.1

COPY template.sh /

COPY app.py /app/app.py
COPY submit.sh /submit.sh

# Copy the source code
ENV SPARK_APPLICATION_PYTHON_LOCATION/ app/app.py

CMD ["/bin/bash", "/template.sh"]
