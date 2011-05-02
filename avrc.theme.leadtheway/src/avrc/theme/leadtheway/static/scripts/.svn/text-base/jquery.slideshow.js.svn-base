jQuery(window).load(
    function(){ //jQuery(window).load() must be used instead of jQuery(document).ready() because of Webkit compatibility
    jQuery("#slideshow").sliderkit({
            autospeed:3000,
            panelbtnshover:false,
            circular:true
    });
    
jQuery("#portaltab-manifesto a").click(function () {jQuery("#manifesto-popup").css("display","block");jQuery(this).addClass("highlight");});
jQuery(".manifesto-close").click(function () {jQuery(this).parent().css("display","none");jQuery("#portaltab-manifesto a").removeClass("highlight");});
jQuery("#manifesto-popup").click(function () {jQuery(this).css("display","none");jQuery("#portaltab-manifesto a").removeClass("highlight");});

jQuery('a.popup').fancybox({'padding':0});

jQuery('.scroll-pane').jScrollPane();

});