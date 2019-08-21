# Image-Blending-OpenCV

The two images are blended gradually by adding them with varying their weights. The below pseudocode is used.

```
for alpha in np.arange(0, 1, 0.01): 
out_img = (1-alpha)*img1 + alpha*img2
plt.imshow(out_img)
```
### Output of blending the two images (updating each 200 milliseconds):

![blending](https://user-images.githubusercontent.com/40549682/63403776-4a213f80-c3e9-11e9-8613-b8650fb48b5e.PNG)


