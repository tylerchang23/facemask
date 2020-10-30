# Selfie Mask Detector!

In the age of COVID-19, studies have shown the effectiveness of masks in slowing down the spread of the virus. With health experts around the globe expecting a second wave to hit, it is crucial that we play our role in stopping the spread by social distancing and wearing masks in public. Most local restaurants and stores require mask wearing upon entry, but there is a slim chance that there is an assigned mask checker waiting at the door. 

I created a web application that can classify whether or not a person is wearing a proper face covering. After scraping hundreds of images off of Instagram, I used the [fast.ai](https://www.fast.ai/) framework to create a convolutional neural network for image classification. After fine-tuning the model, I was able to achieve **95% validation accuracy**. My hope is to inspire businesses to incorporate this type of technology in the future to protect their employees and their customers! 

## How to access the web app:

1) Go to [Binder](https://mybinder.org/)
2) Under **GitHub repository name or URL** copy & paste: https://github.com/tylerchang23/facemask
3) Under **URL to open (optional)**  copy & paste: /voila/render/mask_voila.ipynb
4) Click the drop-down that is defaulted to File, and **click URL**
5) Hit **launch**!

![alt text](https://github.com/tylerchang23/facemask/blob/main/binder_screenshot.png)

***Note: It may take a few minutes for the app to launch, as Binder needs to "recreate" it if no one has used it recently.***
