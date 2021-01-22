FROM nvcr.io/nvidia/tensorflow:20.12-tf2-py3
RUN apt update && apt upgrade -y \
	&& yes | pip install -U pip \
	#jupyterlab \ jupyterlabの最新版だと動かないので一旦除外
	lightgbm \
	matplotlib \ 
	pandas \
	scikit-learn \
	seaborn
CMD ["/bin/bash"]
