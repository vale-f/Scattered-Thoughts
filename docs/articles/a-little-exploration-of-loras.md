# A Little Exploration of LoRAs

<p align="justify">A few months ago, I experimented with training a LoRA for the <a href="https://huggingface.co/black-forest-labs/FLUX.1-dev">Flux.1-dev</a> model, aiming to generate a consistent character across outputs.</p>
<p align="justify">Using a multimodal LLM, I iterated on prompts and generated a large number of images, ultimately selecting 14 relatively consistent ones to use as the LoRA training dataset.</p>
<p align="justify">These are the images I ended up using to train the LoRA:</p>

<img src="../../images/a-little-exploration-of-loras/dataset/1.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/2.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/3.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/4.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/5.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/6.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/7.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/8.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/9.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/10.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/11.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/12.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/13.jpg" alt="Dataset image" width="512" height="384">

<img src="../../images/a-little-exploration-of-loras/dataset/14.jpg" alt="Dataset image" width="512" height="384">


 <br>
<p align="justify">I used the <a href="https://github.com/ostris/ai-toolkit">AI-Toolkit</a> framework for training. Since my local machine was not powerful enough for this task, I opted for <a href="https://www.runpod.io/">RunPod</a>, a company that provides GPU cloud computing services.</p>
<p align="justify">To generate images with Flux.1 Dev and my LoRA, I used <a href="https://www.comfy.org/">ComfyUI</a>, which is an open-source, node-based program that allows users to work with free diffusion models.</p>
<p align="justify">You can view a selection of the generated images below:</p>

<img src="../../images/a-little-exploration-of-loras/output/LoRa_1.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_2.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_3.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_4.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_5.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_6.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_7.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_8.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_9.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_10.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_11.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_12.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_13.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_14.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_15.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_16.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_17.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_18.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_19.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_20.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_21.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_22.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_23.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_24.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_25.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_26.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_27.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_28.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_29.png" alt="Output image" width="500" height="500">

<img src="../../images/a-little-exploration-of-loras/output/LoRa_30.png" alt="Output image" width="500" height="500">

<br>
<p align="justify">I removed random moles from the character’s face in some images using <a href="https://www.gimp.org/">GIMP</a>, an open-source image editing tool. Aside from this, no additional editing was performed.</p>
<p align="justify">I then created a second LoRA using these images as the dataset, believing I might achieve an even more consistent character. However, the output was a very strange-looking person, likely due to overfitting.</p>