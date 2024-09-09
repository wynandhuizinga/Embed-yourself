# Embed Yourself

![Demo](https://github.com/wynandhuizinga/Embed-yourself/blob/main/00001-3907234973.png)
Regional prompt combining famous Einstein with the lesser famous Wynand Huizinga

## Stable diffusion and its limitations
With stable diffusion, you can generate fancy images by prompting for whatever you'd like to see. However, you're limited to generating images which are inspired on the original training set of the stable diffusion base model. For instance: The base model definitely didn't get trained on people which are not famous (myself for example). 

## Steering the iamge extraction process
A prompt essentially consists of a number of tokens which form a combined set of vectors pointing in a certain direction in latent space (high dimensional data). From this point in space, you start to 'reverse diffuse' a noise pattern to become a sharp image.

## Adding additional data - embedding yourself
Again, the base model does not know non-famous people, however, I can generate a vector (token) based on a set of images of myself. With about 20-80 self portrait pictures, you can train your own embedding. The result of this embedding is, that within the base model, you abstract particular elements which are comparable to your own self portrait images. For example: deep nose bridge, glasses, stupple beard, brown hair with a division, skin tone, a mole on a specific location, etc.

## Points of concern
Although this is all fun and interesting, one should take into consideration what to do with this embedding: Once exposed online, anybody can paste your face on any image. Even deep-fakes become feasible with img2img stable diffusion. This personally triggered for me the thought to not want to see too many self portrait images exposed online. However, it does trigger the thought: how much of our identity is actually our own? Perhaps the concept of personal identity is getting outdated.

## Acknowledgement 
Thanks to all the people working hard on SD1.5 and A1111 (automatic 11 11) to enable a fairly easy and accessible workflow. 

## Bonus 
A few more examples for the heck of it.

![1](https://github.com/wynandhuizinga/Embed-yourself/blob/main/00018-Lascivious_v4_%5Bnumber%5D_2740682953.png) ![2](https://github.com/wynandhuizinga/Embed-yourself/blob/main/00408-Lascivious_v4_%5Bnumber%5D_3180833198.png) 
![3 - enlarged](https://github.com/wynandhuizinga/Embed-yourself/blob/main/00303-Lascivious_v4_%5Bnumber%5D_851092331.png)
