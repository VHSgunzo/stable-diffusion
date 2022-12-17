# stable-diffusion
[stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) based on [RunImage](https://github.com/VHSgunzo/runimage)

## To get started:
* **Download the [latest](https://mega.nz/file/gQs0UYya#ZWVGzgs5jxD6M7CAnN6YeHW7olHx5XnqACyFzfsU-uM) revision**
* **Make it executable before run:**
```
chmod +x stable-diffusion
```
* **Run**
```
./stable-diffusion {args}
```
* **After a successful start, open the [web interface](http://127.0.0.1:7860) in the browser**
![image](https://user-images.githubusercontent.com/57139938/208247917-8caf9936-a5fc-4dd7-8e15-a0ec32665275.png)

* RunImage container runs in overlays mode and all changes with stable-diffusion can be made in the directory next to the container:
```
cache/overlayfs/stable-diffusion/mnt/rootfs/opt/stable-diffusion
```

* By default, stable-diffusion saves the results in the directory next to the container: 
```
cache/overlayfs/stable-diffusion/mnt/rootfs/opt/stable-diffusion/outputs
cache/overlayfs/stable-diffusion/mnt/rootfs/opt/stable-diffusion/log
```

* **To close it, use Ctrl+C**
