FROM public.ecr.aws/lambda/python:3.11

# Copy function code
COPY src/ ${LAMBDA_TASK_ROOT}/

# Install dependencies if you have a requirements.txt
# COPY requirements.txt .
# RUN pip install -r requirements.txt --target "${LAMBDA_TASK_ROOT}"

# Set the handler: file.function_name
CMD ["app.handler"]
