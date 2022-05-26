# THE PERFECT FRAME PROJECT

## About

This is project which uses face regonition to show you categorised products. Due to some system difficulties, this project is made in two parts. Both the folders are given in this git repository. You can clone this repo to review the source code.

## Website of deployed prototype

```
https://perfect-frame-face.herokuapp.com/
```

Please use the above link to run the prototype

### To use

#### 1. Choose the picture from given sample picture folder

There are seven pictures for seven categories made. You can choose any image of yours as well but the 100% correct recognition is not guaranteed since the ML model library is used and is not created by me.

#### 2. When the picture is uploaded, click on Sumbit

This will take you to the second part of the project.

#### 3. Click on button "My Type"

And all the categorised products are shown

You can open product detail screen, add to cart and sign in screen.

## Some bugs

#### 1. The website is currently styled for big screens. Please do not open it on small screens such as mobile phones or iPhone etc. All the features work but website is not styled properly.

#### 2. The signIn screen is still not functional because there was some problem in routing UserModel and productModel.

#### 3. The search feature of website works after 2nd submission and not directly by first one.

#### 4. On first page after uploading the image, if the pafe is refreshed or loaded again then the image is lost and you will need to select the image and upload it.

## To run locally

Both the parts will have to be cloned one by one.

### For first part

#### 1. Clone repo

```
$ git clone git@github.com:Aabha1/PerfectFrameFace.git
```

#### 2. To Run

Open the folder.
Please run it in a live server extension and do not use Node.js since this file does not contain @tensorflow.js/tfjs-node. I colud not build it using Node.js because if I make it a node js file then I am required to install @tensorflow.js/tfjs-node which was not supported on my system. This file is not been installed on win-32/ia32(the system i am using).
Thus, to run it locally,
In VS Code install live-server extension {or if you are on any other platfrom just install live-server extension.}
Then right click on home.html
Choose the option "Open with live-server"
It opens and works.

### For second part

#### 1. Clone repo

```
$ git clone git@github.com:Aabha1/PerfectFrame.git
```

#### 2. To Run Backend

```
$ npm install
$ npm run build
$ npm start
```

#### 3. To Run Frontend

```
# open new terminal on same workspace
$ cd frontend
$ npm install
$ npm start
```

## Reference to Part 1:

```
https://github.com/Aabha1/PerfectFrameFace
```

OR

you can open it from this repository and take a look at README file.

## Reference to Part 2:

```
https://github.com/Aabha1/PerfectFrame
```

OR

you can open it from this repository and take a look at README file.

Thank you for visiting.
