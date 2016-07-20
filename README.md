# enjoyInitInfo
initial info in job

## 必备的环境和软件的安装
brew node git ruby cocoapods ReactNative-cli等

## 其他
enjoy-builder: npm i enjoy-builder -g
webpack: sudo npm i webpack -g

## 项目相关

### 编译 h5 项目
－克隆项目： clone 项目地址   
－在项目目录 enjoy/examples/FindHotel 下执行 enjoy build --web  
－cd 到项目中的地址 web/h5 文件夹下  
－执行 npm i  
－cd 到 FindHotel 目录，执行 enjoy build --web  
－在 FindHotel/web/h5 下执行 webpack   
－在浏览器中打开 FindHotel/web/h5/bundle/index.html 文件  
 
###  编译 react-native 项目
－下载 elongtravel文件（ios环境文件）  
－在 FindHotel 文件夹下执行 enjoy build --rn   
－在 rn 目录下执行 react-native start   
－在xcode 软件中打开 elongtravel 文件夹下的 ElongClient.xcworkspace 文件  
－在xcode 软件中点击 "run" 按钮，即可打开模拟器  



