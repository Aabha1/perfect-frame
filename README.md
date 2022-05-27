# THE PERFECT FRAME PROJECT

## About

This project uses face recognition to show you categorised products. Due to some system difficulties, this project is done in two parts. Both the folders are given in this git repository. You can clone this repo to review the source code.

## Website of deployed prototype

```
https://perfect-frame-face.herokuapp.com/
```

Please use the above link to run the prototype.

### To use

#### 1. Choose the picture from the given sample picture folder

There are seven pictures for seven categories made. You can choose any image of yours as well, but the 100% correct recognition is not guaranteed since the ML model library is used and is not created by me.

### 2. When the picture is uploaded, click on Submit

The website will now direct you to the second part of the project.

### 3. Click on the button "My Type."

And all the categorised products are shown.

You can open the product detail screen, add to cart and sign-in screen.

## Some bugs

#### 1. The website is currently styled for big screens. Please do not open it on small screens such as mobile phones, iPhones, or other small screens. All the features work, but the website is not styled properly.

#### 2. The sign-in screen is still not functional because there was some problem routing UserModel and ProductModel.

#### 3. The website's search feature works after 2nd submission and not directly by the first one.

#### 4. On the first page after uploading the image, if the page is refreshed or loaded again, then the image is lost, and you will need to select the image and upload it.

## To run locally

Both the parts will have to be closed one by one.

### For the first part

#### 1. Clone repo

```
$ git clone git@github.com:Aabha1/PerfectFrameFace.git
```

#### 2. To Run

Open the folder.
Please run it in a live server extension and not use Node.js since this file does not contain @tensorflow.js/tfjs-node. I could not build it using Node.js because if I make it a node js file, then I am required to install @tensorflow.js/tfjs-node, which was not supported on my system. This file has not been installed on win-32/ia32(the system I am using).
Thus, to run it locally,
In VS Code, install the live-server extension {or if you are on any other platform, install the live-server extension.}
Then right-click on home.html
Choose the option "Open with live-server."
It opens and works.

### For the second part

### 1. Clone repo

```
$ git clone git@github.com:Aabha1/PerfectFrame.git
```

### 2. To Run Backend

```
$ npm install
$ npm run build
$ npm start
```

### 3. To Run Frontend

```
# open a new terminal on the same workspace
$ cd frontend
$ npm install
$ npm start
```

## Reference to Part 1:

```
https://github.com/Aabha1/PerfectFrameFace
```

OR

You can open it from this repository and look at the README file.

## Reference to Part 2:

```
https://github.com/Aabha1/PerfectFrame
```

OR

You can open it from this repository and look at the README file.

Thank you for visiting.
