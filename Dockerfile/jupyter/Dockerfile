FROM python:latest

EXPOSE 8888

RUN python -m pip install --upgrade pip
RUN pip install nnfs
RUN pip install torch
RUN pip install tqdm
RUN pip install torchvision
RUN pip install matplotlib
RUN pip install pandas
RUN pip install jupyterlab

ENTRYPOINT [jupyter lab --no-browser --ip="0.0.0.0" --port 8888  --allow-root --NotebookApp.token='']
