FROM quay.io/jupyter/minimal-notebook:latest

USER root

RUN apt-get update && apt-get install -y \
    build-essential \
    gcc \
    python3-dev \
    libjpeg-dev \
    zlib1g-dev \
    && rm -rf /var/lib/apt/lists/*

USER $NB_UID

RUN pip install --no-cache-dir \
    pandas \
    matplotlib \
    numpy \
    seaborn \
    scikit-learn \
    wordcloud \
    joblib \
    jupyterlab

