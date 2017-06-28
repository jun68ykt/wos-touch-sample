# wos-touch-sample

a Sample of -webkit-overflow-scrolling: touch

## How to install, run and check

Requirements:
- node
- npm

and if possible,
- iPad
- Wifi network

My environment has
- node v8.0.0
- npm 5.0.1
- iPad updated Model 9.7inch, iOS 10.3.2


#### 1.clone 

`git clone https://github.com/jun68ykt/wos-touch-sample.git wos-touch-sample`

#### 2.install node modules

`cd wos-touch-sample`

and then,

`npm install`

#### 3.run

`npm start`

After starting the script `browser-sync start --server --files "**/*"`, <br />
you can see the browser rendering a simple HTML page which includes <br /> `<div>`
and `<ul>` with 50 `<li>`s.

#### 4.display on iPad

With this sample program running on your PC by following the steps from 1. to 3. above,
If possible, I want you to let your iPad's Safari browser display the URL

http://`<IP address of your PC>`:3000

through the Wifi network.

#### 5.check scrolling smoothly

How about scrolling of `<ul>` with CSS<br />
`-webkit-overflow-scrolling: touch` ?


