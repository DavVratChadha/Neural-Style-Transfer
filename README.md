# Neural-Style-Transfer
This GitHub repository is a personal project to document my progress as I learn about neural style transfer, a technique for combining the content of one image with the style of another image using deep learning. The repository will contain my notes, code, and examples of my experimentation with this technique. It is intended as a reference for myself as I continue to learn and explore this topic, and may also be of interest to others who are also learning about neural style transfer.

## Useful resources
- Gatys, Leon & Ecker, Alexander & Bethge, Matthias. (2015). A Neural Algorithm of Artistic Style. arXiv. 10.1167/16.12.326.  (https://www.researchgate.net/publication/281312423_A_Neural_Algorithm_of_Artistic_Style)
- Li, Yanghao & Wang, Naiyan & Liu, Jiaying & Hou, Xiaodi. (2017). Demystifying Neural Style Transfer. 2230-2236. 10.24963/ijcai.2017/310. 
(https://www.researchgate.net/publication/318830253_Demystifying_Neural_Style_Transfer)

## Note
The papers state to use noise to genarate image similar to content image and then apply NST to transfer art style from style image to create the final image. But, in my code, instead to using noise, I simply use content image and apply NST to it. This is done to make the overall process simpler and it requires lesser computation.

## Some Examples:
- Golden Gate Bridge in the style of The Scream by Edvard Munch
![res1](https://user-images.githubusercontent.com/95514650/210476202-e27c39c3-3acf-4b19-9b14-7605cb1828b9.png)
![res2](https://user-images.githubusercontent.com/95514650/210476300-6a3960c9-a96f-4aa2-8dd8-18126d35b9fa.png)

- A puppy in the style of The Starry Night by Vincent van Gogh
![res3](https://user-images.githubusercontent.com/95514650/210476464-1c576320-492d-4eb5-824b-f2193633f05b.png)
![res4](https://user-images.githubusercontent.com/95514650/210476520-c6b4cdab-ed16-4cd5-9e0d-2c4e6db4603a.png)
