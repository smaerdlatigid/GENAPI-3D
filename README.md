# GENAI-3D
Micro ML API for 3D Generation

Model Details: https://github.com/microsoft/TRELLIS

## Set up

Build the docker image using cog:

`cog run -p 8090 bash`

## Example

Once in the docker container, run the gradio UI:

`python gradio_demo.py`

Navigate to [localhost:8090](http://localhost:8090) to see the UI.

## API (TO DO)

First, build the docker image using cog:

`cog build -t genai-3d`

Then, run the docker image:

`docker run -d -p 5000:5000 --gpus 1 genai-3d`

To check that the API is running, navigate to [localhost:5000](http://localhost:5000).
