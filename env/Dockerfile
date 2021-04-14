FROM pytorch/pytorch

RUN apt update && apt install -y libglib2.0-0 libgl1-mesa-glx curl libcurl4
RUN pip install --no-cache-dir fiftyone albumentations tqdm black flake8 pytorch-lightning gdown

CMD python -c "import fiftyone" 