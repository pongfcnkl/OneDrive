# OneDrive
https://pongfcnkl.github.io/OneDrive/index.html#/
"auto"


var ra = new RootAutomator();
events.on('exit', function(){
ra.exit();
});


while(true) {
ra.tap(100, 100, 1); // 用第一“手指”，点击坐标 100, 100，大约150毫秒
sleep(100); // 等待100毫秒
}
