# icml2016 revision for Colab

This is icml2016 revised version for Google Colab.

Refer to [https://github.com/reedscot/icml2016](https://github.com/reedscot/icml2016) for original source version, <br>
it implementation for the paper [Generative Adversarial Text-to-Image Synthesis](http://arxiv.org/abs/1605.05396).


**Dependencies**

python == 3.6

pytorch == 1.2.0

Torch7 (http://torch.ch/docs/getting-started.html#_)

In addition, please add the project folder to PYTHONPATH and `pip install` the following packages:
- `torchvision == 0.4.0` 

**How to get data:**

1. Download the [birds](https://drive.google.com/file/d/0B0ywwgffWnLLLUc2WHYzM0Q2eWc/view?usp=sharing) and [flowers](https://drive.google.com/file/d/0B0ywwgffWnLLMl9uOU91MV80cVU/view?usp=sharing) caption data in Torch format.
2. Download the [birds](http://www.vision.caltech.edu/visipedia/CUB-200-2011.html) and [flowers](http://www.robots.ox.ac.uk/~vgg/data/flowers/102) image data.
3. Download the text encoders for [birds](https://drive.google.com/open?id=0B0ywwgffWnLLU0F3UHA3NzFTNEE) and [flowers](https://drive.google.com/open?id=0B0ywwgffWnLLZUt0UmQ1LU1oWlU) descriptions.


**How to generate samples:**

* For flowers: `./scripts/demo_flowers.sh`. Add text descriptions to `scripts/flowers_queries.txt`.
* For birds: `./scripts/demo_cub.sh`.



 caption             |  image example
:-------------------------:|:-------------------------:
the petals of the flower are pink in color and have a yellow center. |  ![](results/flowers/img_1.png)
this flower is pink and white in color, with petals that are multi colored. |  ![](results/flowers/img_2.png)
the geographical shapes of the bright purple petals set off the orange stamen and ... |  ![](results/flowers/img_3.png)
the purple petals have shades of white with white anther and filament |  ![](results/flowers/img_4.png)
this flower has large pink petals and a white stigma in the center |  ![](results/flowers/img_5.png)
this flower has petals that are pink and has a yellow stamen |  ![](results/flowers/img_6.png)
a flower with short and wide petals that is light purple. |  ![](results/flowers/img_7.png)
this flower has small pink petals with a yellow center. |  ![](results/flowers/img_8.png)
this flower has large rounded pink petals with curved edges and purple veins. |  ![](results/flowers/img_9.png)

 caption             |  image example
:-------------------------:|:-------------------------:
the medium sized bird has a dark grey color, a black downward curved beak, and long wings. |  ![](results/cub/img_1.png)
the bird is dark grey brown with a thick curved bill and a flat shaped tail. |  ![](results/cub/img_2.png)
bird has brown body feathers, white breast feathers and black beak |  ![](results/cub/img_3.png)
this bird has a dark brown overall body color, with a small white patch around the base of the bill. |  ![](results/cub/img_4.png)
the bird has very long and large brown wings, as well as a black body and a long black beak. |  ![](results/cub/img_5.png)
it is a type of albatross with black wings, tail, back and beak, and has a white ring at the base of its beak. |  ![](results/cub/img_6.png)
this bird has brown plumage and a white ring at the base of its long, curved brown beak. |  ![](results/cub/img_7.png)
the entire body is dark brown, as is the bill, with a white band encircling where the bill meets the head. |  ![](results/cub/img_8.png)
this bird is gray in color, with a large curved beak. |  ![](results/cub/img_9.png)


