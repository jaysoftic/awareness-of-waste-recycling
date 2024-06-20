# Awareness of Waste Recycling :india:
![GIF](static/images/awareness_of_waste_recycling.png)

#### The world generates at least 3.5 million tons of waste per day and this number is still increasing day by day that's why we need to aware about waste.
#### This web application can classify waste with 9 different waste materials and it will show you the details of that particular waste materials. This will help to raise awareness for people to reduce and recycle waste.

## Overview
- There are **LIGHT BLUBS, PAPER, PLASTIC, ORGANIC, GLASS, BATTERIES, CLOTHES, METAL, E-WASTE** total 9 different types of waste materials which are use for recycling.
- In this project i have collected and filtered data by my self from google images and dreamstime.com
- Here i have **8369 images** belonging **9 classes**.
- Here i have trained dataset using **VGG16** Transfer Learning technique of CNN for classification.
- Here i have trained this model till **28 epochs** and i got **69.77%** accuracy.
- Initially i had trained my model with **Inceptionv3** and it's gave me **90.34%** accuracy. But it was not accurate when i tested it on some images. But when i tested **VGG16** with **69.77%** accuracy it gives me accurate result.

## Data Source
- In this project i have collected and filtered data by my self from google images and dreamstime.com
- I have uploaded my dataset on google drive. 
- [click here to get dataset](https://drive.google.com/drive/folders/1CTvT_gnTvwlcKwJ8yz4jUOs0JYTKrplA?usp=sharing)

## Demo
- I have deployed this on AWS Elastic Beanstalk platform
Link: [http://wasterecycling-env.eba-xcpktyd2.us-east-2.elasticbeanstalk.com/](http://wasterecycling-env.eba-xcpktyd2.us-east-2.elasticbeanstalk.com/)

![GIF](readme_resources/projectDemo.gif)

## How to use
- Click on image icon and upload image or if you are on mobile then click on camera icon and capture the waste and upload image.
- Click on Classify your waste material button it will classify your waste and show you the result in details

## Deployment
#### Prepare a configuration file in main directory
1. Create .ebextensions folder to your main directory
2. Inside .ebextensions folder create a python.config file and write configration like [this](https://github.com/jaysoftic/awareness-of-waste-recycling/blob/master/.ebextensions/python.config)
3. Create .ebignore file inside main directory

#### Here's simple steps to create an application on Elastic Bean Stalk
1. Open the Elastic Beanstalk console using this link: https://console.aws.amazon.com/elasticbeanstalk/home#/gettingStarted?applicationName=getting-started-app
2. Enter your application name.
3. Application tags are optional so just ignore it.
4. For Platform, choose a python platform (python version 3.8).
5. For Application code choose Upload your code.
6. Upload a zip file of your project.
7. Click on create application button.

- rest of the things will take care by aws elastic bean stalk and you will get deployed link.

## Technologies Used
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>
<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>
<code><img height="30" src="https://d1.awsstatic.com/icons/console_elasticbeanstalk_icon.0f7eb0140e1ef6c718d3f806beb7183d06756901.png"></code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code>
<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>
<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/1/11/TensorFlowLogo.svg"></code>

## Motivation
- My motivation watch is [here](https://www.youtube.com/watch?v=NhF4pXBNfq8)

## Team
[![Jay Soni](https://avatars3.githubusercontent.com/u/49163967?s=400&u=be22bbe1409ff51991b04026f038c1373174a02a&v=4)](https://in.linkedin.com/in/jaysoftic) |
-|
[Jay Soni](https://in.linkedin.com/in/jaysoftic) |)

## Credits
- Entire credits goes to My God

## 
- If you like my work and it helped you in anyway then please do ⭐ the repository it will motivate me to make more amazing projects
