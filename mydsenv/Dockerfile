FROM nvcr.io/nvidia/tensorflow:20.12-tf2-py3
RUN apt update && apt upgrade -y \
	&& yes | pip install -U pip \
	jupyterlab \
	lightgbm \
	matplotlib \ 
	pandas \
	seaborn \
	scikit-learn
CMD ["/bin/bash"]