# Japanese Stable Diffusion Cog model

### Quickstart
```
sudo curl -o /usr/local/bin/cog -L https://github.com/replicate/cog/releases/latest/download/cog_`uname -s`_`uname -m`
sudo chmod +x /usr/local/bin/cog
sudo apt-get install git-lfs
git lfs install
git clone https://huggingface.co/rinna/japanese-stable-diffusion
cog predict -i prompt="サラリーマン 油絵"
```

![サラリーマン 油絵](output.0.png "サラリーマン 油絵")
