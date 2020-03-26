

(function(){
    var bp = document.createElement('script');
    var curProtocol = window.location.protocol.split(':')[0];
    if (curProtocol === 'https') {
        bp.src = 'https://zz.bdstatic.com/linksubmit/push.js';
    }
    else {
        bp.src = 'http://push.zhanzhang.baidu.com/push.js';
    }
    var s = document.getElementsByTagName("script")[0];
    s.parentNode.insertBefore(bp, s);
})();




var _hmt = _hmt || [];
(function() {
    var hm = document.createElement("script");
    hm.src = "https://hm.baidu.com/hm.js?ff157d2c1eab1efdc12b036b9864dcb6";
    var s = document.getElementsByTagName("script")[0];
    s.parentNode.insertBefore(hm, s);
})();

$('.bannerWrap').height($(window).width() * 0.5);
$(window).resize(function () {
    $('.bannerWrap').height($(window).width() * 0.5)
});


$('#switchTip').click(function () {
    if ($(".fixedRight").attr('show') == 1) {

        $('.fixedRight').animate({right: '0'}, 300, function () {
        });

        $(".fixedRight").attr('show', 0)
    } else {
        $('.fixedRight').animate({right: '-220px'}, 300);

        $(".fixedRight").attr('show', 1)
    }
});
// 控制小屏幕的菜单显示
var sideIssShow = false;
$('#menuRightBtn').click(function () {
    if(sideIssShow) {
        $('#sideDom').css({
            display:'none'
        })
    }else {
        $('#sideDom').css({
            display:'block'
        })
    }
    sideIssShow != sideIssShow;
})
$('.colse-icon').click(function () {
    $('#sideDom').css({
        display:'none'
    });
    sideIssShow != sideIssShow;
})

String.prototype.gblen = function() {
    var len = 0;
    for (var i=0; i<this.length; i++) {
        if (this.charCodeAt(i)>127 || this.charCodeAt(i)==94) {
            len += 2;
        } else {
            len ++;
        }
    }
    return len;
}
//检查手机号码——02
function checkMobileNum_second(mobileNum){
    var mobile = /^(13[0-9]|14[579]|15[0-3,5-9]|16[6]|17[0135678]|18[0-9]|19[89])\d{8}$/;
    if(mobile.test(mobileNum)){
        return true;
    }
    return false;
}

function goBack() {
    window.history.back()
}
