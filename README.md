- 👋 Hi, I’m @ChuongLoc
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

https://stackoverflow.com/questions/72611914/error-could-not-build-wheels-for-pycocotools-which-is-required-to-install-pypr

https://askubuntu.com/questions/1206703/how-to-uninstall-python-3-8-from-ubuntu-after-deleting-the-folder-python-3-8-0-u

https://github.com/tensorflow/models/issues/9634

https://hub.docker.com/layers/tensorflow/tensorflow/2.2.0-gpu/images/sha256-3f8f06cdfbc09c54568f191bbc54419b348ecc08dc5e031a53c22c6bba0a252e?context=explore

https://www.tensorflow.org/install/pip

<!---
ChuongLoc/ChuongLoc is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

    docker run  -it  --gpus all --name mytf2 --workdir /ML_SUBAPP_S2  --volume /home/greystone/mytf2:/home/greystone tensorflow/tensorflow:2.2.0-gpu

    sudo apt-get update && sudo apt-get upgrade

    sudo apt-get install python3.8

    sudo rm /usr/bin/python3 

    sudo ln /usr/bin/python3.8 /usr/bin/python3

    sudo apt install python3.8-dev

    python -m pip install --upgrade pip

    pip install pycodestyle

    apt install protobuf-compiler -y

    pip install --upgrade pip

    pip install pycocotools

    python -m pip install .

    ls /usr/local/cuda*

    export PATH=/usr/local/cuda-10.1/bin${PATH:+:${PATH}}

    export LD_LIBRARY_PATH=/usr/local/cuda-10.1/lib64 {LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}

    python3 -c "import tensorflow as tf; print(tf.config.list_physical_devices('GPU'))"

