# -
//解决移动端键盘弹出问题 h5,js
var wHeight = window.innerHeight;
window.addEventListenner("resize",function(){
  var hh = window.innerHeight;
  if(wHeight >hh){
    $(".address_add").css("height","10rem");
    $(".address_add .content").css("height","9rem");

  }else{
    $(".address_add").css("height","14.5rem");
    $(".address_add .content").css("height","10rem");

  }
  wHeight = hh;
})
