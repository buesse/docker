FROM nginx:stable

RUN apt-get update -y && apt-get install -y \
    php5 \
  && rm -rf /var/lib/apt/lists/*
  
CMD ["/bin/bash"]
