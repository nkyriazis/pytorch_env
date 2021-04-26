FROM pytorch/pytorch

RUN apt update && apt install -y libglib2.0-0 libgl1-mesa-glx curl libcurl4
RUN conda run -n base pip install --use-feature=2020-resolver --no-cache-dir fiftyone albumentations tqdm black flake8 pytorch-lightning gdown

#CMD python -c "import fiftyone" 