FROM public.ecr.aws/lambda/python:3.12
WORKDIR .



COPY . ${LAMBDA_TASK_ROOT}

RUN pwd && ls -la


CMD [ "lambda_function.lambda_handler" ]