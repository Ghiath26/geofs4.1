# geofs4.1
geofs4.1version
<html lang="en"><head><style>.cesium-credit-lightbox-overlay {display: none; z-index: 1; position: absolute; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(80, 80, 80, 0.8);  }
.cesium-credit-lightbox {background-color: #303336; color: #ffffff; position: relative; min-height: 100px; margin: auto;  }
.cesium-credit-lightbox > ul > li a, .cesium-credit-lightbox > ul > li a:visited {color: #ffffff;  }
.cesium-credit-lightbox > ul > li a:hover {color: #48b;  }
.cesium-credit-lightbox.cesium-credit-lightbox-expanded {border: 1px solid #444; border-radius: 5px; max-width: 370px;  }
.cesium-credit-lightbox.cesium-credit-lightbox-mobile {height: 100%; width: 100%;  }
.cesium-credit-lightbox-title {padding: 20px 20px 0 20px;  }
.cesium-credit-lightbox-close {font-size: 18pt; cursor: pointer; position: absolute; top: 0; right: 6px; color: #ffffff;  }
.cesium-credit-lightbox-close:hover {color: #48b;  }
.cesium-credit-lightbox > ul {margin: 0; padding: 12px 20px 12px 40px; font-size: 13px;  }
.cesium-credit-lightbox > ul > li {padding-bottom: 6px;  }
.cesium-credit-lightbox > ul > li * {padding: 0; margin: 0;  }
.cesium-credit-expand-link {padding-left: 5px; cursor: pointer; text-decoration: underline; color: #ffffff;  }
.cesium-credit-expand-link:hover {color: #48b;  }
.cesium-credit-text {color: #ffffff;  }
.cesium-credit-textContainer *, .cesium-credit-logoContainer * {display: inline;  }
</style><script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.z-CF99wuLeU.O/m=signin2/exm=auth2/rt=j/sv=1/d=1/ed=1/rs=AHpOoo8yJLmK2FeQzRT4hxPn9_NEJo9eCg/cb=gapi.loaded_1?le=scs" async=""></script><script src="https://apis.google.com/_/scs/abc-static/_/js/k=gapi.lb.en.z-CF99wuLeU.O/m=auth2/rt=j/sv=1/d=1/ed=1/rs=AHpOoo8yJLmK2FeQzRT4hxPn9_NEJo9eCg/cb=gapi.loaded_0?le=scs" async=""></script><script src="https://connect.facebook.net/en_US/sdk.js?hash=635573ad14d98992310a7faae9a71066" async="" crossorigin="anonymous"></script><script>window.geofs = window.geofs || {};</script>
<script>geofs.version = '3.9';</script>
<script>geofs.forcePreferenceResetOnVersionChange = '';</script>
<script>geofs.multiplayerHost = 'https://mps.geo-fs.com';</script>
<script>geofs.MPSMinUpdateDelay = 500;</script>
<script>geofs.MPSMapUpdatePeriod = 10000;</script>
<script>geofs.domain = 'www.geo-fs.com';</script>
<script>geofs.userRoles = {"anonymous":0,"authenticated":1,"student":2,"instructor":3,"editor":11,"licenseadmin":40,"subscribed":80,"admin":100};</script>
<script>geofs.masterDomain = 'geo-fs.com';</script>
<script>geofs.scheme = 'https://';</script>
<script>geofs.url = 'https://www.geo-fs.com';</script>
<script>geofs.localUrl = 'https://www.geo-fs.com/';</script>
<script>geofs.multiplayerModelUrl = 'https://www.geo-fs.com';</script>
<script>geofs.googleAppId = '208044912282-4g0gk5oum6gecc2d7ll1ensv921l12us.apps.googleusercontent.com';</script>
<script>geofs.facebookAppId = '404853203195387';</script>
<script>geofs.dataServer = 'https://data.geo-fs.com/';</script>
<script>geofs.srtmServer = 'https://data.geo-fs.com/srtm/';</script>
<script>geofs.blackMarbleServer = 'https://data.geo-fs.com/bm/';</script>
<script>geofs.osmTileProvider = 'https://data.geo-fs.com/osm/{z}/{x}/{y}.png';</script>
<script>geofs.landuseServer = 'https://data.geo-fs.com/landuse/';</script>
<script>geofs.buildingServer = 'https://data.geo-fs.com/buildings/';</script>
<script>geofs.treeServer = 'https://data.geo-fs.com/trees/';</script>
<script>geofs.treeServerExtension = '.glbz';</script>
<script>geofs.objectServer = 'https://data.geo-fs.com/landmarks/';</script>
<script>geofs.weatherServer = 'https://weather.geo-fs.com/';</script>
<script>geofs.ionkey = 'eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJqdGkiOiJiMWQ1NWRlMy1lZmM3LTRlNDYtYWQyOS1hZDlmZmMyZGRiZWUiLCJpZCI6NzYsInNjb3BlcyI6WyJhc3IiXSwiYXNzZXRzIjpbMV0sImlhdCI6MTU1MzUwOTAwMX0.AlJJNDP3yr3dOLmcMnuJdsODGrVoSpm9lvtcXuGM99M';</script>
<script>geofs.googleAPIKey = 'AIzaSyAkM_2eRnvbh0Te_MQjbGrQbF1UBDsv5_E';</script>
<script src="https://cdn.paddle.com/paddle/v2/paddle.js"></script>

<script>window.paddleClientToken = "live_27a614c3c0678bfaea05d8404fc";window.HDPriceId="pri_01j6y3wbpcgffcdcz2phbtgbww"; window.SRPriceId="pri_01jag4dcncdye77d1dydd0kwcr"</script><script>

    // PADDLE
    Paddle.Initialize({
        token: window.paddleClientToken,
        eventCallback: function(event) {
            //if (event.name == "checkout.payment.initiated") {
            if (event.name == "checkout.completed") {
                $('.geofs-subscribe-view').htmlView('load', '/html/hd/subscribe.php?pending=true', {paddletx: event.data.transaction_id});
            }
        }
    });

    var priceRequest = {
        items: [
        {
            quantity: 1,
            priceId: window.HDPriceId
        },
        {
            quantity: 1,
            priceId: window.SRPriceId
        }]
    };

    Paddle.PricePreview(priceRequest).then((result) => {
        window.executeOnEventDone('afterDeferredload', function() {
            $('.geofs-HD-price').html(result.data.details.lineItems[0].formattedTotals.subtotal);
            $('.geofs-SR-price').html(result.data.details.lineItems[1].formattedTotals.subtotal);
        });
    }).catch((error) => {
        console.error(error);
    });

</script><link rel="stylesheet" type="text/css" href="https://cdn.paddle.com/paddle/v2/assets/css/paddle.css" media="all"><script src="https://public.profitwell.com/js/profitwell.js?auth=paddletoken_live_27a614c3c0678bfaea05d8404fc"></script>


    
    <title>GeoFS - Fly in Your Web Browser</title>

    <link rel="canonical" href="https://www.geo-fs.com/geofs.php">

    <meta http-equiv="content-type" content="text/html; charset=utf-8">
    <meta name="description" content="Fly directly in your web browser without anything to download or to install.">

    <meta name="viewport" content="width=device-width, height=device-height, initial-scale=1, minimum-scale=1, maximum-scale=1, viewport-fit=cover">

    <meta property="og:title" content="GeoFS">
    <meta property="og:type" content="game">
    <meta property="og:url" content="https://www.geo-fs.com/">
    <meta property="og:image" content="https://www.geo-fs.com/images/squareposter.jpg">
    <meta property="og:description" content="Fly directly in your web browser without anything to download or to install.">

    <link rel="shortcut icon" href="favicon.ico">

    <script src="js/loader.js"></script>

    <!-- Common CSS -->
    <link rel="stylesheet" type="text/css" href="/css/commonCSS.css?kc=22" media="screen">
    <!-- Common JS -->
    <script src="/js/commonJS.js?kc=17"></script>
    <!-- 3rd parties -->
    
    
    
    
    
    

    
    

    <!-- Local CESIUM Repo/build -->
    <!--
    <link rel="stylesheet" type="text/css" href="/projects/CESIUM/Build/Cesium/Widgets/widgets.css" media="screen"/>
    <script defer src="/projects/CESIUM/Build/Cesium/Cesium.js" obfuscation="update" dest="js/Cesium/build/Cesium.js"></script>
    -->

    

    <style type="text/css" data-fbcssmodules="css:fb.css.base css:fb.css.dialog css:fb.css.iframewidget">.fb_hidden{position:absolute;top:-10000px;z-index:10001}.fb_reposition{overflow:hidden;position:relative}.fb_invisible{display:none}.fb_reset{background:none;border:0px;border-spacing:0;color:#000;cursor:auto;direction:ltr;font-family:'lucida grande', tahoma, verdana, arial, sans-serif;font-size:11px;font-style:normal;font-variant:normal;font-weight:normal;letter-spacing:normal;line-height:1;margin:0;overflow:visible;padding:0;text-align:left;text-decoration:none;text-indent:0;text-shadow:none;text-transform:none;visibility:visible;white-space:normal;word-spacing:normal}.fb_reset>div{overflow:hidden}@keyframes fb_transform{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}.fb_animate{animation:fb_transform .3s forwards}
.fb_hidden{position:absolute;top:-10000px;z-index:10001}.fb_reposition{overflow:hidden;position:relative}.fb_invisible{display:none}.fb_reset{background:none;border:0px;border-spacing:0;color:#000;cursor:auto;direction:ltr;font-family:'lucida grande', tahoma, verdana, arial, sans-serif;font-size:11px;font-style:normal;font-variant:normal;font-weight:normal;letter-spacing:normal;line-height:1;margin:0;overflow:visible;padding:0;text-align:left;text-decoration:none;text-indent:0;text-shadow:none;text-transform:none;visibility:visible;white-space:normal;word-spacing:normal}.fb_reset>div{overflow:hidden}@keyframes fb_transform{from{opacity:0;transform:scale(.95)}to{opacity:1;transform:scale(1)}}.fb_animate{animation:fb_transform .3s forwards}
.fb_dialog{background:rgba(82,82,82,.7);position:absolute;top:-10000px;z-index:10001}.fb_dialog_advanced{border-radius:8px;padding:10px}.fb_dialog_content{background:#fff;color:#373737}.fb_dialog_close_icon{background:url(https://connect.facebook.net/rsrc.php/v4/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 0 transparent;cursor:pointer;display:block;height:15px;position:absolute;right:18px;top:17px;width:15px}.fb_dialog_mobile .fb_dialog_close_icon{left:5px;right:auto;top:5px}.fb_dialog_padding{background-color:transparent;position:absolute;width:1px;z-index:-1}.fb_dialog_close_icon:hover{background:url(https://connect.facebook.net/rsrc.php/v4/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 -15px transparent}.fb_dialog_close_icon:active{background:url(https://connect.facebook.net/rsrc.php/v4/yq/r/IE9JII6Z1Ys.png) no-repeat scroll 0 -30px transparent}.fb_dialog_iframe{line-height:0}.fb_dialog_content .dialog_title{background:#6d84b4;border:1px solid #365899;color:#fff;font-size:14px;font-weight:bold;margin:0}.fb_dialog_content .dialog_title>span{background:url(https://connect.facebook.net/rsrc.php/v4/yd/r/Cou7n-nqK52.gif) no-repeat 5px 50%;float:left;padding:5px 0 7px 26px}body.fb_hidden{height:100%;left:0px;margin:0px;overflow:visible;position:absolute;top:-10000px;transform:none;width:100%}.fb_dialog.fb_dialog_mobile.loading{background:url(https://connect.facebook.net/rsrc.php/v4/ya/r/3rhSv5V8j3o.gif) white no-repeat 50% 50%;min-height:100%;min-width:100%;overflow:hidden;position:absolute;top:0;z-index:10001}.fb_dialog.fb_dialog_mobile.loading.centered{background:none;height:auto;min-height:initial;min-width:initial;width:auto}.fb_dialog.fb_dialog_mobile.loading.centered #fb_dialog_loader_spinner{width:100%}.fb_dialog.fb_dialog_mobile.loading.centered .fb_dialog_content{background:none}.loading.centered #fb_dialog_loader_close{clear:both;color:white;display:block;font-size:18px;padding-top:20px}#fb-root #fb_dialog_ipad_overlay{background:rgba(0,0,0,.4);bottom:0;left:0;min-height:100%;position:absolute;right:0;top:0;width:100%;z-index:10000}#fb-root #fb_dialog_ipad_overlay.hidden{display:none}.fb_dialog.fb_dialog_mobile.loading iframe{visibility:hidden}.fb_dialog_mobile .fb_dialog_iframe{position:sticky;top:0}.fb_dialog_content .dialog_header{background:linear-gradient(from(#738aba), to(#2c4987));border-bottom:1px solid;border-color:#043b87;box-shadow:white 0px 1px 1px -1px inset;color:#fff;font:bold 14px Helvetica, sans-serif;text-overflow:ellipsis;text-shadow:rgba(0,30,84,.296875) 0px -1px 0px;vertical-align:middle;white-space:nowrap}.fb_dialog_content .dialog_header table{height:43px;width:100%}.fb_dialog_content .dialog_header td.header_left{font-size:12px;padding-left:5px;vertical-align:middle;width:60px}.fb_dialog_content .dialog_header td.header_right{font-size:12px;padding-right:5px;vertical-align:middle;width:60px}.fb_dialog_content .touchable_button{background:linear-gradient(from(#4267b2), to(#2a4887));background-clip:padding-box;border:1px solid #29487d;border-radius:3px;display:inline-block;line-height:18px;margin-top:3px;max-width:85px;padding:4px 12px;position:relative}.fb_dialog_content .dialog_header .touchable_button input{background:none;border:none;color:white;font:bold 12px Helvetica, sans-serif;margin:2px -12px;padding:2px 6px 3px 6px;text-shadow:rgba(0,30,84,.296875) 0px -1px 0px}.fb_dialog_content .dialog_header .header_center{color:#fff;font-size:16px;font-weight:bold;line-height:18px;text-align:center;vertical-align:middle}.fb_dialog_content .dialog_content{background:url(https://connect.facebook.net/rsrc.php/v4/y9/r/jKEcVPZFk-2.gif) no-repeat 50% 50%;border:1px solid #4a4a4a;border-bottom:0;border-top:0;height:150px}.fb_dialog_content .dialog_footer{background:#f5f6f7;border:1px solid #4a4a4a;border-top-color:#ccc;height:40px}#fb_dialog_loader_close{float:left}.fb_dialog.fb_dialog_mobile .fb_dialog_close_icon{visibility:hidden}#fb_dialog_loader_spinner{animation:rotateSpinner 1.2s linear infinite;background-color:transparent;background-image:url(https://connect.facebook.net/rsrc.php/v4/yD/r/t-wz8gw1xG1.png);background-position:50% 50%;background-repeat:no-repeat;height:24px;width:24px}@keyframes rotateSpinner{0%{transform:rotate(0deg)}100%{transform:rotate(360deg)}}
.fb_iframe_widget{display:inline-block;position:relative}.fb_iframe_widget span{display:inline-block;position:relative;text-align:justify}.fb_iframe_widget iframe{position:absolute}.fb_iframe_widget_fluid_desktop,.fb_iframe_widget_fluid_desktop span,.fb_iframe_widget_fluid_desktop iframe{max-width:100%}.fb_iframe_widget_fluid_desktop iframe{min-width:220px;position:relative}.fb_iframe_widget_lift{z-index:1}.fb_iframe_widget_fluid{display:inline}.fb_iframe_widget_fluid span{width:100%}</style><style>.abcRioButton{border-radius:1px;box-shadow:0 2px 4px 0 rgba(0,0,0,.25);-moz-box-sizing:border-box;box-sizing:border-box;-webkit-transition:background-color .218s,border-color .218s,box-shadow .218s;transition:background-color .218s,border-color .218s,box-shadow .218s;-webkit-user-select:none;-webkit-appearance:none;background-color:#fff;background-image:none;color:#262626;cursor:pointer;outline:none;overflow:hidden;position:relative;text-align:center;vertical-align:middle;white-space:nowrap;width:auto}.abcRioButton:hover{box-shadow:0 0 3px 3px rgba(66,133,244,.3)}.abcRioButtonBlue{background-color:#4285f4;border:none;color:#fff}.abcRioButtonBlue:hover{background-color:#4285f4}.abcRioButtonBlue:active{background-color:#3367d6}.abcRioButtonLightBlue{background-color:#fff;color:#757575}.abcRioButtonLightBlue:active{background-color:#eee;color:#6d6d6d}.abcRioButtonIcon{float:left}.abcRioButtonBlue .abcRioButtonIcon{background-color:#fff;border-radius:1px}.abcRioButtonSvg{display:block}.abcRioButtonContents{font-family:Roboto,arial,sans-serif;font-size:14px;font-weight:500;letter-spacing:.21px;margin-left:6px;margin-right:6px;vertical-align:top}.abcRioButtonContentWrapper{height:100%;width:100%}.abcRioButtonBlue .abcRioButtonContentWrapper{border:1px solid transparent}.abcRioButtonErrorWrapper,.abcRioButtonWorkingWrapper{display:none;height:100%;width:100%}.abcRioButtonErrorIcon,.abcRioButtonWorkingIcon{margin-left:auto;margin-right:auto}.abcRioButtonErrorState,.abcRioButtonWorkingState{border:1px solid #d5d5d5;border:1px solid rgba(0,0,0,.17);box-shadow:0 1px 0 rgba(0,0,0,.05);color:#262626}.abcRioButtonErrorState:hover,.abcRioButtonWorkingState:hover{border:1px solid #aaa;border:1px solid rgba(0,0,0,.25);box-shadow:0 1px 0 rgba(0,0,0,.1)}.abcRioButtonErrorState:active,.abcRioButtonWorkingState:active{border:1px solid #aaa;border:1px solid rgba(0,0,0,.25);box-shadow:inset 0 1px 0 #ddd;color:#262626}.abcRioButtonWorkingState,.abcRioButtonWorkingState:hover{background-color:#f5f5f5}.abcRioButtonWorkingState:active{background-color:#e5e5e5}.abcRioButtonErrorState,.abcRioButtonErrorState:hover{background-color:#fff}.abcRioButtonErrorState:active{background-color:#e5e5e5}.abcRioButtonErrorState .abcRioButtonErrorWrapper,.abcRioButtonWorkingState .abcRioButtonWorkingWrapper{display:block}.abcRioButtonErrorState .abcRioButtonContentWrapper,.abcRioButtonErrorState .abcRioButtonWorkingWrapper,.abcRioButtonWorkingState .abcRioButtonContentWrapper{display:none} .-webkit-keyframes abcRioButtonWorkingIconPathSpinKeyframes {0% {-webkit-transform: rotate(0deg)}}</style><link rel="stylesheet" type="text/css" href="https://cdn.paddle.com/paddle/v2/assets/css/paddle.css" media="all"><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css"><style type="text/css">.livery-list {
    width: 450px;
    resize: horizontal;
}

#listDiv h6 {
    padding-left: 4px;
}
#listDiv h6:before  {
    content: "▼";
    margin-right: 2px;
}
#listDiv h6.closed:before {
    content: "▶";
    margin-right: 2px;
}
.checked, .nocheck {
    text-shadow: 0 0 1px black, 0 0 1px black, 0 0 1px black, 0 0 1px black;
    color: rgb(255, 193, 7);
    display: inline;
    text-align: right;
    cursor: pointer;
}
.nocheck {
    color: white;
}

input[type="file"] {
    width: 30%;
    display: inline-block;
    background-color: rgb(83, 109, 254);
    color: white;
    padding: 12px 0;
    margin: 2px 0;
    height: 20px;
    cursor: pointer;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

input[type="file"].err {
    background-color: rgb(254, 109, 83);
}

input[type="file"]::-webkit-file-upload-button,
input[type="file"]::file-selector-button {
    visibility: hidden;
    width: 0;
}

#livery-custom-tab-direct input[type="file"]::before,
#livery-custom-tab-upload input[type="file"]::before {
    content: "UPLOAD IMAGE";
    text-align: center;
    display: inline-block;
    width: 100%;
    font-family: "Roboto", "Helvetica", "Arial", sans-serif;
    font-size: 14px;
}

#livery-custom-tab-direct input[type="file"]::before {
    content: 'LOAD IMAGE';
}

#livery-custom-tab-upload input[type="file"].err::before {
    content: 'NO API KEY';
}


input[name="textureInput"] {
    color: white;
    font-size: 14px;
    font-family: "Roboto", "Helvetica", "Arial", sans-serif;
    height: 36px;
    display: inline-block;
    background-color: #729e8f;
    border: none;
    outline: none;
    width: 68%;
    padding: 4px 3px;
    keyboard-events: none;
    -webkit-user-select: none;
    -khtml-user-select: none;
    -moz-user-select: none;
    -ms-user-select: none;
    user-select: none;
}

#livery-setting-apikey::placeholder,
input[name="textureInput"]::placeholder {
    color: #dedede;
    font-size: 14px;
}

img.livery-title {
    width: 95%;
    display: block;
    margin: 0 auto;
}

ul.livery-custom-tabs {
    display: flex;
    justify-content: space-evenly;
    background-color: white;
    padding-inline-start: 0;
    margin: 0;
}

.livery-custom-tabs li {
    display: inline-block;
    padding: 0.75rem;
    cursor: pointer;
    flex-grow: 1;
    text-align: center;
}
.livery-submit div {
    padding: 10px 0;
}
.livery-submit div label {
    display: block;
    padding: 5px 0;
}
.livery-submit div label[for="livery-submit-confirm-perms"],
.livery-submit div label[for="livery-submit-confirm-legal"] {
    display: inline;
}
.livery-submit div input[id="livery-submit-credits"] {
    margin-bottom: 10px;
}
.livery-submit div input[type="text"],
.livery-submit div input[type="number"],
#livery-setting-discordid,
#livery-setting-apikey {
    background-color: #729e8f;
    color: #dedede;
    padding: 4px 2px;
    width: 98%;
    height: 36px;
}

#livery-custom-tab-upload button {
    position: initial;
    margin: 10px auto;
    display: block;
    width: 80%;
    text-align: center;
}

#livery-custom-tab-upload > div,
#livery-custom-tab-direct > div,
#livery-custom-tab-download > div,
#livery-custom-tab-api div {
    padding: 10px;
    background: white;
}
#livery-custom-tab-api label[for="livery-setting-discordid"] {
    padding-top: 16px;
    display: block;
}
#favorites li.livery-list-item small,
#airlinelist li.livery-list-item small,
#liverylist li.livery-list-item small {
    position: absolute;
    left: 12px;
    top: 16px;
    color: darkgray;
}

#favorites li.livery-list-item span.fa,
#airlinelist li.livery-list-item span.fa,
#liverylist li.livery-list-item span.fa {
    position: absolute;
    top: 15px;
    right: 10px;
}

#favorites li.livery-list-item,
#airlinelist li.livery-list-item,
#liverylist li.livery-list-item {
    background-color: white;
    display: block;
    height: 48px;
    transition: height .1s;
    overflow: hidden;
}
#liverylist li.livery-list-item.offi:hover {
    transition: height 0.1s;
    height: 240px;
}

.geofs-list .livery-custom-tabs li:hover,
#favorites li.livery-list-item:hover,
#airlinelist li.livery-list-item:hover,
#liverylist li.livery-list-item:hover {
    border: 2px solid #dedede;
    margin: -2px 0 0 -2px;
}

#favorites li.livery-list-item span.livery-name,
#airlinelist li.livery-list-item span.livery-name,
#liverylist li.livery-list-item span.livery-name {
    position: relative;
    z-index: 10;
    width: 80%;
    display: block;
}
#airlinelist li.livery-list-item img,
#liverylist li.livery-list-item img {
    transition: height .1s;
    height: 48px;
    position: absolute;
    right: 30px;
    top: 0;
}
#airlinelist li.livery-list-item:hover img,
#liverylist li.livery-list-item:hover img {
    height: 240px;
    transition: height 0.1s;
}

.livery-searchbar {
    width: 100%;
}

.download-fields h7 {
    background-color: #729e8f;
    display:block;
    padding: 4px;
}
.download-fields .mdl-button {
    position: initial;
    margin: 4px;
    display: inline-block;
    width: 38%;
}

#customDiv {
    width: 100%;
    padding: 0;
}</style></head><body class="geofs geofs-ingame geofs-adsBlocked geofs-loggedout geofs-transparentUI geofs-sr geofs-mouseHold" style="overflow: hidden; background-color: #25405e;"><section version="3.8">
        
        <!-- 3.8 Resources -->

        
        <script src="js/Cesium/build/Cesium.js"></script>

        
        
        
        
        
        
        
            </section>

    
    <!-- Sim -->
   
    <!-- Data -->
    <script src="/data/runwaygrid.js"></script>
    <script src="/data/airports.js"></script>

    <!-- Google tag (gtag.js) -->
    <script async="" src="https://www.googletagmanager.com/gtag/js?id=G-HB7Z4Z74PE"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'G-HB7Z4Z74PE');
    </script>

<script>geofs.PRODUCTION = true;geofs.killCache = '?kc=1729598422';</script><script src="/js/geofs.js?kc=36"></script><link rel="stylesheet" type="text/css" href="css/geofs.css?kc=23" media="screen">



    
    
    <div class="geofs-ui-center">

        <script>geofs.userRecord={"id":"1200276","email":"saps.ghaith@gmail.com","googleid":"114497718225939686825","facebookid":null,"licenseid":null,"deviceid":null,"appleid":null,"externalid":null,"firstname":"Ghaith","lastname":"Al Jadidi","callsign":"OM(WY907)","sessionId":"16ss4k50f898vdc71h6597ijur","created":"2025-01-19 17:15:25","active":"0","ip":"5.37.235.127","role":"-1","muted":"0","banned":"0","lastlogin":"2025-03-05 10:34:30","mailing":"1","password":"***","flighttime":"645","preferences":null,"mutelist":null,"premium":null,"transactionDate":null,"transactionReference":null,"transactionStatus":"trialexpired","transactionMessage":null,"subscribed":null,"subscriptionStart":null,"subscriptionEnd":"2025-02-11 11:37:22","trial":"1","subscription":null};</script>
<script>geofs.userRecord.muteList=[];</script>
<script>geofs.userRecord.muteListMap={'':1};</script>

<meta name="robots" content="noindex, nofollow"><script src="https://cdn.paddle.com/paddle/v2/paddle.js"></script>

<script>window.paddleClientToken = "live_27a614c3c0678bfaea05d8404fc";window.HDPriceId="pri_01j6y3wbpcgffcdcz2phbtgbww"; window.SRPriceId="pri_01jag4dcncdye77d1dydd0kwcr"</script><script>

    // PADDLE
    Paddle.Initialize({
        token: window.paddleClientToken,
        eventCallback: function(event) {
            //if (event.name == "checkout.payment.initiated") {
            if (event.name == "checkout.completed") {
                $('.geofs-subscribe-view').htmlView('load', '/html/hd/subscribe.php?pending=true', {paddletx: event.data.transaction_id});
            }
        }
    });

    var priceRequest = {
        items: [
        {
            quantity: 1,
            priceId: window.HDPriceId
        },
        {
            quantity: 1,
            priceId: window.SRPriceId
        }]
    };

    Paddle.PricePreview(priceRequest).then((result) => {
        window.executeOnEventDone('afterDeferredload', function() {
            $('.geofs-HD-price').html(result.data.details.lineItems[0].formattedTotals.subtotal);
            $('.geofs-SR-price').html(result.data.details.lineItems[1].formattedTotals.subtotal);
        });
    }).catch((error) => {
        console.error(error);
    });

</script><script>geofs.userRecord={"id":"1200276","email":"saps.ghaith@gmail.com","googleid":"114497718225939686825","facebookid":null,"licenseid":null,"deviceid":null,"appleid":null,"externalid":null,"firstname":"Ghaith","lastname":"Al Jadidi","callsign":"OM(WY907)","sessionId":"16ss4k50f898vdc71h6597ijur","created":"2025-01-19 17:15:25","active":"0","ip":"5.37.235.127","role":"-1","muted":"0","banned":"0","lastlogin":"2025-03-05 11:12:26","mailing":"1","password":"***","flighttime":"682","preferences":null,"mutelist":null,"premium":null,"transactionDate":null,"transactionReference":null,"transactionStatus":"trialexpired","transactionMessage":null,"subscribed":null,"subscriptionStart":null,"subscriptionEnd":"2025-02-11 11:37:22","trial":"1","subscription":null};</script>
<script>geofs.userRecord.muteList=[];</script>
<script>geofs.userRecord.muteListMap={'':1};</script>

<div class="geofs-auth geofs-htmlView">

                    
                <div class="geofs-authForm">
                
                    
                    <img class="geofs-facebook-login geofs-hideForApp" alt="Facebook login button" src="/images/facebook-login.png">
                    <!--<div class="fb-login-button" data-size="large" data-show-faces="false" data-auto-logout-link="false" onlogin="loginFacebook" data-scope="public_profile, email"></div>-->
                    <!--<div class="fb-login-button" data-width="90" data-size="medium" data-button-type="" data-layout="" data-auto-logout-link="false" data-use-continue-as="false"></div>-->

                    <div class="geofs-google-signin google-signin geofs-hideForApp" id="google-signin1"><div style="height:25px;width:75px;" class="abcRioButton abcRioButtonBlue"><div class="abcRioButtonContentWrapper"><div class="abcRioButtonIcon" style="padding:3px"><div style="width:18px;height:18px;" class="abcRioButtonSvgImageWithFallback abcRioButtonIconImage abcRioButtonIconImage18"><svg version="1.1" xmlns="http://www.w3.org/2000/svg" width="18px" height="18px" viewBox="0 0 48 48" class="abcRioButtonSvg"><g><path fill="#EA4335" d="M24 9.5c3.54 0 6.71 1.22 9.21 3.6l6.85-6.85C35.9 2.38 30.47 0 24 0 14.62 0 6.51 5.38 2.56 13.22l7.98 6.19C12.43 13.72 17.74 9.5 24 9.5z"></path><path fill="#4285F4" d="M46.98 24.55c0-1.57-.15-3.09-.38-4.55H24v9.02h12.94c-.58 2.96-2.26 5.48-4.78 7.18l7.73 6c4.51-4.18 7.09-10.36 7.09-17.65z"></path><path fill="#FBBC05" d="M10.53 28.59c-.48-1.45-.76-2.99-.76-4.59s.27-3.14.76-4.59l-7.98-6.19C.92 16.46 0 20.12 0 24c0 3.88.92 7.54 2.56 10.78l7.97-6.19z"></path><path fill="#34A853" d="M24 48c6.48 0 11.93-2.13 15.89-5.81l-7.73-6c-2.15 1.45-4.92 2.3-8.16 2.3-6.26 0-11.57-4.22-13.47-9.91l-7.98 6.19C6.51 42.62 14.62 48 24 48z"></path><path fill="none" d="M0 0h48v48H0z"></path></g></svg></div></div><span style="font-size:11px;line-height:23px;" class="abcRioButtonContents"><span id="not_signed_inv6oecq7abuqr" style="display: none;">Sign in</span><span id="connectedv6oecq7abuqr" style="">Signed in</span></span></div></div></div>
                                <a href="/pages/instructions.php" target="_blank" class="geofs-help geofs-hideForMobile">
                    <i class="material-icons">help_outline</i>
                </a>
            </div>
        </div>
        <div class="geofs-startModalMobile">
            <h1>Welcome to GeoFS!</h1>
            <p>
                You appear to be using a mobile device, would you like to use mobile optimized settings?
            </p>
            <p style="text-align: center;">
                <a class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect geofs-fly-button" style="margin-bottom: 20px; width: 100px;" data-upgraded=",MaterialButton,MaterialRipple"><i class="material-icons"></i> No<span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></a><br>
                <a class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect mdl-button--accent geofs-fly-button-mobile" style="width: 100px;" data-upgraded=",MaterialButton,MaterialRipple"><i class="material-icons"></i> Yes!<span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></a>
            </p>
        </div>

        <div class="geofs-startModal">
            <h1>Welcome to GeoFS!</h1>

            <h5>A quick briefing before take-off:</h5>
            <ul style="margin-left: -25px;">
                <li>+ and - keys to set throttle</li>
                <li>You are flying with the mouse (configurable)</li>
                <li>As you gain speed, gently pull on the stick (mouse down) to take off</li>
                <li>Press R to reset your flight</li>
            </ul>
            <a class="mdl-button mdl-js-button mdl-button--raised mdl-js-ripple-effect mdl-button--accent geofs-fly-button" data-upgraded=",MaterialButton,MaterialRipple"><i class="material-icons"></i> Fly!<span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></a>
        </div>

        <div class="geofs-flightSharing-status"></div>

        <div class="geofs-user-dialog">
            <h4 style="white-space: nowrap; flex-grow: 1;"><span class="material-icons" style="font-size: 30px;vertical-align: sub;margin-right: 5px;">perm_identity</span>Pilot <b class="geofs-user-callsign"></b></h4>
                        <button class="geofs-ignore-user mdl-button mdl-button--raised mdl-button--colored" id="0.4875783010580472" tabindex="0"><span class="material-icons">pan_tool</span> Block user</button><div class="mdl-tooltip undefined" for="0.4875783010580472" data-upgraded=",MaterialTooltip">Block user</div>
            <button class="geofs-share-user geofs-school mdl-button mdl-button--raised mdl-button--accent" id="0.8689076123108301" tabindex="0"><span class="material-icons">group</span> Share flight</button><div class="mdl-tooltip undefined" for="0.8689076123108301" data-upgraded=",MaterialTooltip">Share flight and controls with user</div>
            <button class="geofs-join-user mdl-button mdl-button--raised"><span class="material-icons" id="0.2188392405603039" tabindex="0">call_merge</span><div class="mdl-tooltip undefined" for="0.2188392405603039" data-upgraded=",MaterialTooltip">Join user in flight</div> Join user in flight</button>
            <button class="geofs-cancel mdl-button close" id="0.6921415735362195" tabindex="0">Close</button><div class="mdl-tooltip undefined" for="0.6921415735362195" data-upgraded=",MaterialTooltip">Close</div>
        </div>

        <!-- Top UI overlay -->
        <div class="geofs-ui-top">

            <div class="control-pad geofs-control-status" id="0.9861963341298985" tabindex="0">
                <div class="control-pad-label orange-pad">MOUSE OFF</div>
            </div><div class="mdl-tooltip undefined" for="0.9861963341298985" data-upgraded=",MaterialTooltip">Mouse controls on hold, press [M] to enable.</div>

            <div class="geofs-autopilot-bar">
                <div class="control-pad geofs-autopilot-pad" id="0.07842676030950035" tabindex="0">
                    <div class="control-pad-label transp-pad">AUTOPILOT</div>
                </div><div class="mdl-tooltip undefined" for="0.07842676030950035" data-upgraded=",MaterialTooltip">Toggle autopilot on/off</div>
                <div class="geofs-autopilot-controls">
                    <div class="geofs-autopilot-control">
                        <a class="numberDown">-</a><input class="geofs-autopilot-speed geofs-autopilot-mach" min="0" step="0.01" decimals="2" data-method="setSpeed" maxlength="5" value="0"><input class="numberValue geofs-autopilot-speed geofs-autopilot-knots" min="0" smallstep="5" stepthreshold="100" step="10" data-method="setSpeed" maxlength="4" value="0"><a class="numberUp">+</a>
                        <span class="geofs-autopilot-switch geofs-speed-mode">
                            <a class="switchLeft green-pad" data-method="setSpeedMode" value="knots">KTS</a><a class="switchRight" data-method="setSpeedMode" value="mach">M.</a>
                        </span>
                    </div>
                    <div class="geofs-autopilot-control">
                        <a class="numberDown">-</a><input class="numberValue geofs-autopilot-course" min="0" max="359" data-loop="true" step="1" data-method="setCourse" maxlength="3" value="000"><a class="numberUp">+</a>
                        <span class="geofs-autopilot-switch geofs-autopilot-mode">
                            <a class="switchLeft geofs-autopilot-HDG green-pad" data-method="setMode" value="HDG">HDG</a><a class="switchRight geofs-autopilot-NAV" data-method="setMode" value="NAV">NAV</a>
                        </span>
                    </div>
                    <div class="geofs-autopilot-control">
                        <a class="numberDown">-</a><input class="numberValue geofs-autopilot-altitude" min="0" max="100000" smallstep="100" stepthreshold="3000" step="500" data-method="setAltitude" maxlength="5" value="00000"><a class="numberUp">+</a>
                        <span>ALTITUDE</span>
                    </div>
                    <div class="geofs-autopilot-control">
                        <a class="numberDown">-</a><input class="numberValue geofs-autopilot-verticalSpeed" min="-6000" max="6000" step="100" data-method="setVerticalSpeed" maxlength="5" value="00000"><a class="numberUp">+</a>
                        <span>VERT SPEED</span>
                    </div>
                </div>
            </div>
        </div>

        <div class="geofs-ui-right">

            <!-- Wind Indicator-->
            <div class="geofs-wind-container"><div class="geofs-overlay geofs-textOverlay control-pad geofs-hidden" style="background-image: url(&quot;images/instruments/wind/plane.png&quot;); background-size: 50px 50px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 50px; transform-origin: 0px 50px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-hidden" style="background-image: url(&quot;images/instruments/wind/pointer.png&quot;); background-size: 50px 50px; margin-left: -25px; margin-bottom: -25px; left: 26px; bottom: 23px; z-index: 60; background-position: 0px 0px; width: 50px; height: 50px; transform-origin: 25px 25px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay control-pad-sticker geofs-hidden" style="background-size: 40px 12px; margin-left: 0px; margin-bottom: 0px; left: 5px; bottom: -8px; z-index: 60; background-position: 0px 0px; width: 40px; height: 12px; transform-origin: 0px 12px; opacity: 1; transform: rotate(0deg);">0 kts</div><div class="geofs-overlay geofs-textOverlay control-pad-label geofs-hidden" style="background-size: 50px 15px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 40px; z-index: 60; background-position: 0px 0px; width: 50px; height: 15px; transform-origin: 0px 15px; opacity: 1; transform: rotate(0deg);">wind</div></div>

            <!-- Radio box -->
            <div class="geofs-radio-controls">
                <div class="geofs-radio-control geofs-nav-frequency">
                    <span class="geofs-radio-label">
                        <button class="geofs-radio-select on" name="NAV1MODE" onclick="geofs.nav.setNAVMode('NAV', 'NAV1');">NAV</button>
                        <button class="geofs-radio-select" name="GPSMODE" onclick="geofs.nav.setNAVMode('GPS', 'GPS');">GPS</button>
                    </span>
                    <input class="geofs-radio-display" name="NAVFrequency"><button class="geofs-radio-ident" data-unit="NAV1">ident</button>
                <div class="geofs-overlay geofs-textOverlay geofs-radio-knob geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/radioknob.png&quot;); background-size: 40px 40px; margin-left: -20px; margin-bottom: -20px; left: -5px; bottom: 25px; z-index: 60; background-position: 0px 0px; width: 40px; height: 40px; transform-origin: 20px 20px; opacity: 1; transform: rotate(0deg);"></div></div>
                <div class="geofs-radio-control geofs-radio-OBS">
                    <span class="geofs-radio-label">OBS</span><input class="geofs-radio-display" name="radioOBS">
                <div class="geofs-overlay geofs-textOverlay geofs-radio-knob geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/radioknob.png&quot;); background-size: 40px 40px; margin-left: -20px; margin-bottom: -20px; left: -5px; bottom: 25px; z-index: 60; background-position: 0px 0px; width: 40px; height: 40px; transform-origin: 20px 20px; opacity: 1; transform: rotate(0deg);"></div></div>
                <div class="geofs-radio-control">
                    <span class="geofs-radio-label">DME</span><input class="geofs-radio-display" name="dme"><span class="geofs-radio-unit">NM</span>
                    <input class="geofs-radio-display" name="groundSpeed"><span class="geofs-radio-unit">KTS</span>
                    <input class="geofs-radio-display" name="timeToStation"><span class="geofs-radio-unit">MIN</span>
                </div>
                <div class="geofs-radio-control geofs-adf-frequency">
                    <span class="geofs-radio-label">ADF</span><input class="geofs-radio-display" name="ADFFrequency"><button class="geofs-radio-ident" data-unit="ADF">ident</button>
                <div class="geofs-overlay geofs-textOverlay geofs-radio-knob geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/radioknob.png&quot;); background-size: 40px 40px; margin-left: -20px; margin-bottom: -20px; left: -5px; bottom: 25px; z-index: 60; background-position: 0px 0px; width: 40px; height: 40px; transform-origin: 20px 20px; opacity: 1; transform: rotate(0deg);"></div></div>
            </div>
            <div class="control-pad geofs-radio-pad" id="0.5386839367054013" tabindex="0">
                <div class="control-pad-label transp-pad">RADIO</div>
            </div><div class="mdl-tooltip undefined" for="0.5386839367054013" data-upgraded=",MaterialTooltip" style="left: 1331px; margin-left: -31px; top: 436px;">Open radio navigation controls</div>

            <!-- Control Pads -->
            <div class="geofs-pads-container" style="width: 1355px; height: 225px;"><div class="geofs-inline-overlay geofs-textOverlay control-pad geofs-visible geofs-manipulator" style="background-size: 50px 25px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 25px; transform-origin: 0px 25px; opacity: 1; transform: rotate(0deg);"><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-visible" style="background-size: 50px 25px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 25px; transform-origin: 0px 25px; opacity: 1; transform: rotate(0deg);">OPTION</div><div class="geofs-overlay geofs-textOverlay blue-pad geofs-visible" style="background-size: 50px 25px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 0px; transform-origin: 0px 25px; opacity: 1; transform: rotate(0deg);"></div></div><div class="geofs-inline-overlay geofs-textOverlay control-pad spoiler-overlay geofs-visible geofs-manipulator" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-visible" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">SPLR<br>RET</div><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">SPLR<br>DEP</div><div class="geofs-overlay geofs-textOverlay orange-pad geofs-visible" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 0px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"></div></div><div class="geofs-inline-overlay geofs-textOverlay control-pad brakes-overlay geofs-visible geofs-manipulator" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label orange-pad geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">BRAKES<br>ON</div><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-visible" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">BRAKES</div></div><div class="geofs-inline-overlay geofs-textOverlay control-pad gear-overlay geofs-visible geofs-manipulator" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label green-pad geofs-visible" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">GEAR<br>DOWN</div><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">GEAR<br>UP</div><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">GEAR<br>TRANS</div><div class="geofs-inline-overlay geofs-textOverlay orange-pad geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 50px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"></div></div><div class="geofs-inline-overlay geofs-textOverlay control-pad flaps-overlay geofs-visible geofs-manipulator" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"><div class="geofs-overlay geofs-textOverlay control-pad-dyn-label geofs-visible" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; left: 0px; bottom: 0px; z-index: 61; background-position: 0px 0px; width: 50px; height: 45px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);">FLAPS<br>0 / 4</div><div class="geofs-inline-overlay geofs-textOverlay blue-pad geofs-hidden" style="background-size: 50px 45px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 50px; height: 0px; transform-origin: 0px 45px; opacity: 1; transform: rotate(0deg);"></div></div></div>

        </div>

        <!-- Canvas placeholder -->
        <div id="geofs-ui-3dview" class="geofs-ui-3dview">

	    <div class="geofs-alarms-container" style="width: 1465px; height: 25px;"><div class="geofs-inline-overlay geofs-textOverlay control-pad-transparent orange-pad control-pad-dyn-label geofs-hidden" style="background-size: 100px 25px; margin-left: 0px; margin-bottom: 0px; z-index: 60; background-position: 0px 0px; width: 100px; height: 25px; transform-origin: 0px 25px; opacity: 1; transform: rotate(0deg);">STALL</div></div>

            <div class="geofs-crashOverlay">
                You crashed<br>
                <span class="geofs-hideForMobileDevice">click to reset</span>
                <span class="geofs-onlyForMobileDevice">tap to reset</span>
            </div>

            <!-- Instrument container -->
            <div class="geofs-instruments-container" style="width: 1183px; height: 151.667px;"><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/hsi/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/glideslopegrades.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/glideslopeindicators.png&quot;); background-size: 138.017px 9.85833px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 6.825px 70.525px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/compass.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(94.99deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/hsi/bar.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/grads.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-hidden" style="background-image: url(&quot;images/instruments/hsi/to.png&quot;); background-size: 11.375px 10.6167px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 83.4167px 52.325px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-hidden" style="background-image: url(&quot;images/instruments/hsi/from.png&quot;); background-size: 11.375px 10.6167px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 83.4167px 87.2083px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/white-needle.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/yellowbar.png&quot;); background-size: 3.03333px 60.6667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 74.3167px 45.5px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/bug.png&quot;); background-size: 15.1667px 12.1333px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 151.667px; bottom: 75.8333px; z-index: 60; background-position: 68.25px 15.925px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-overlay-moreTransparence geofs-visible" style="background-image: url(&quot;images/instruments/hsi/nav.png&quot;); background-size: 31.0917px 18.2px; margin-left: 0px; margin-bottom: 0px; left: 109.2px; bottom: 115.267px; z-index: 60; background-position: 0px 0px; width: 31.0917px; height: 18.2px; transform-origin: 0px 18.2px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-overlay-moreTransparence geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/hsi/courseknob.png&quot;); background-size: 33.3667px 33.3667px; margin-left: -16.6833px; margin-bottom: -16.6833px; left: 91px; bottom: 15.1667px; z-index: 260; background-position: 0px 0px; width: 33.3667px; height: 33.3667px; transform-origin: 16.6833px 16.6833px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-overlay-moreTransparence geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/hsi/headingknob.png&quot;); background-size: 33.3667px 33.3667px; margin-left: -16.6833px; margin-bottom: -16.6833px; left: 212.333px; bottom: 15.1667px; z-index: 260; background-position: 0px 0px; width: 33.3667px; height: 33.3667px; transform-origin: 16.6833px 16.6833px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hsi/plane.png&quot;); background-size: 31.85px 34.8833px; margin-left: -15.925px; margin-bottom: -17.4417px; left: 151.667px; bottom: 70.525px; z-index: 60; background-position: 0px 0px; width: 31.85px; height: 34.8833px; transform-origin: 15.925px 17.4417px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 310.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/compass-grad.png&quot;); background-size: 137.258px 137.258px; margin-left: -68.25px; margin-bottom: -68.25px; left: 310.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 137.258px; height: 137.258px; transform-origin: 68.25px 69.0083px; opacity: 1; transform: rotate(94.99deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/hdg-bug.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 310.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/compass-hand.png&quot;); background-size: 37.9167px 82.6583px; margin-left: -18.9583px; margin-bottom: -19.7167px; left: 310.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 37.9167px; height: 82.6583px; transform-origin: 18.9583px 62.9417px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-overlay-moreTransparence geofs-visible geofs-manipulator" style="background-image: url(&quot;images/instruments/hdg-knob.png&quot;); background-size: 33.3667px 33.3667px; margin-left: -16.6833px; margin-bottom: -16.6833px; left: 371.583px; bottom: 15.1667px; z-index: 260; background-position: 0px 0px; width: 33.3667px; height: 33.3667px; transform-origin: 16.6833px 16.6833px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 470.167px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay APPLegacyOverlayReordering geofs-visible" style="background-image: url(&quot;images/instruments/airspeed-hand.png&quot;); background-size: 15.1667px 91px; margin-left: -7.58333px; margin-bottom: -25.7833px; left: 470.167px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 15.1667px; height: 91px; transform-origin: 7.58333px 65.2167px; opacity: 1; transform: rotate(0.0779673deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/airspeed-high.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 470.167px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 629.417px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-overlay-mask geofs-visible" style="mask-image: url(&quot;images/instruments/attitude-jet-mask.png&quot;); margin-left: -75.8333px; margin-bottom: -75.8333px; left: 629.417px; bottom: 75.8333px; z-index: 60; mask-size: 151.667px 151.667px; width: 151.667px; height: 151.667px; opacity: 1;"><div class="geofs-overlay geofs-textOverlay geofs-overlay-moreTransparence" style="background-image: url(&quot;images/instruments/attitude-jet-hand.png&quot;); background-size: 151.667px 606.667px; background-position: 0px -226.666px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; transform: rotate(359.8deg);"></div></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/attitude-jet.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 629.417px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/attitude-jet-pointer.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 629.417px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(359.8deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/altitude2/altitude.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/altitude2/stripe_mask.png&quot;); background-size: 87.9667px 84.175px; margin-left: -43.9833px; margin-bottom: -40.95px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 87.9667px; height: 84.175px; transform-origin: 43.9833px 43.225px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/tenthousandhand.png&quot;); background-size: 12.1333px 69.0083px; margin-left: -6.06667px; margin-bottom: 0px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 12.1333px; height: 69.0083px; transform-origin: 6.06667px 69.0083px; opacity: 1; transform: rotate(0.111077deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/small-hand.png&quot;); background-size: 15.1667px 65.975px; margin-left: -7.58333px; margin-bottom: -21.2333px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 15.1667px; height: 65.975px; transform-origin: 7.58333px 44.7417px; opacity: 1; transform: rotate(1.11077deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/airspeed-hand.png&quot;); background-size: 15.1667px 91px; margin-left: -7.58333px; margin-bottom: -25.7833px; left: 788.667px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 15.1667px; height: 91px; transform-origin: 7.58333px 65.2167px; opacity: 1; transform: rotate(11.1077deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 947.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/vario-high.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 947.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/airspeed-hand.png&quot;); background-size: 15.1667px 91px; margin-left: -7.58333px; margin-bottom: -25.7833px; left: 947.917px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 15.1667px; height: 91px; transform-origin: 7.58333px 65.2167px; opacity: 1; transform: rotate(270deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-instrument-background geofs-visible" style="background-image: url(&quot;images/instruments/background.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 1107.17px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/jet-rpm.png&quot;); background-size: 151.667px 151.667px; margin-left: -75.8333px; margin-bottom: -75.8333px; left: 1107.17px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 151.667px; height: 151.667px; transform-origin: 75.8333px 75.8333px; opacity: 1; transform: rotate(0deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/jet-rpm-hand.png&quot;); background-size: 10.6167px 25.7833px; margin-left: -4.55px; margin-bottom: -11.375px; left: 1078.35px; bottom: 109.958px; z-index: 60; background-position: 0px 0px; width: 10.6167px; height: 25.7833px; transform-origin: 4.55px 14.4083px; opacity: 1; transform: rotate(36deg);"></div><div class="geofs-overlay geofs-textOverlay geofs-visible" style="background-image: url(&quot;images/instruments/airspeed-hand.png&quot;); background-size: 15.1667px 91px; margin-left: -7.58333px; margin-bottom: -25.7833px; left: 1107.17px; bottom: 75.8333px; z-index: 60; background-position: 0px 0px; width: 15.1667px; height: 91px; transform-origin: 7.58333px 65.2167px; opacity: 1; transform: rotate(27deg);"></div></div>
            <div class="geofs-indicators-container"></div>
            <div class="geofs-overlay-container"></div>

            <!-- Touch control pads -->
            <div class="geofs-touch-controls">
                <div class="geofs-throttle-pad">
                    <div class="geofs-throttle-cursor">
                    <div class="geofs-rudder-pad">
                        <div class="geofs-rudder-cursor"></div>
                    </div>
                    </div>
                </div>
                <div class="geofs-control-pad">
                <!--
                    <div class="geofs-control-option-x"></div>
                    <div class="geofs-control-option-z"></div>
                -->
                    <div class="geofs-control-trimup"></div>
                    <div class="geofs-control-trimdown"></div>
                    <div class="geofs-control-cursor"></div>
                </div>
            </div>

            <!-- overlayed div to fix Cesium mouse event bug in IE -->
            <div class="geofs-canvas-mousewheel-overlay">
            <div class="geofs-canvas-mouse-overlay" style="pointer-events: auto;">

                <div class="geofs-view-pad"></div>

                <div class="geofs-creditContainer geofs-hideForMobileDevice"><a rel="nofollow" target="_blank" href="https://satlas.allen.ai/superres">The Allen Institute for Artificial Intelligence</a> - Satlas Super Resolution - <a rel="nofollow" target="_blank" href="https://github.com/allenai/satlas/blob/main/DataLicense">ODC Attribution License</a></div>

                <div class="geofs-player-count" data-toggle-panel=".geofs-player-list">606 pilots online</div>

                <a href="/pages/hd.php" target="_blank">
                    <img class="geofs-sd-logo" src="/images/sd-logo.png" id="0.42893883859654913" tabindex="0"><div class="mdl-tooltip undefined" for="0.42893883859654913" data-upgraded=",MaterialTooltip">Standard definition: Sentinel-2</div>
                    <img class="geofs-sr-logo" src="/images/sr-logo.png" id="0.7220329459129602" tabindex="0"><div class="mdl-tooltip undefined" for="0.7220329459129602" data-upgraded=",MaterialTooltip">Super Resolution: Ai2 Satlas</div>
                    <img class="geofs-hd-logo" src="/images/hd-logo.png" id="0.6652167436296237" tabindex="0"><div class="mdl-tooltip undefined" for="0.6652167436296237" data-upgraded=",MaterialTooltip">High Definition: Microsoft Bing</div>
                </a>

                <!-- Chat section -->
                <div class="geofs-chat-messages geofs-authenticated geofs-hideForApp"></div>
            </div>
            </div>
        <div class="cesium-viewer"><div class="cesium-viewer-cesiumWidgetContainer"><div class="cesium-widget"><canvas style="image-rendering: pixelated;" width="1365" height="945"></canvas><div class="cesium-credit-lightbox-overlay"><div class="cesium-credit-lightbox"><div class="cesium-credit-lightbox-title">Data provided by:</div><a class="cesium-credit-lightbox-close">×</a><ul></ul></div></div></div></div><div class="cesium-viewer-bottom" style="left: 0px; bottom: 0px;"><div class="cesium-widget-credits"><div class="cesium-credit-logoContainer" style="display: inline;"><div style="display: inline;"><a href="https://cesium.com/" target="_blank"><img src="https://www.geo-fs.com/js/Cesium/build/Assets/Images/ion-credit.png" id="0.9272392855159448" tabindex="0"><div class="mdl-tooltip undefined" for="0.9272392855159448" data-upgraded=",MaterialTooltip">Cesium ion</div></a></div></div><div class="cesium-credit-textContainer" style="display: inline;"></div><a class="cesium-credit-expand-link" style="display: none;">Data attribution</a></div></div><div class="cesium-viewer-toolbar"></div></div></div>
    </div>

    <div class="geofs-ui-left" style="z-index: 40;">

        <div class="geofs-apiResponse geofs-htmlView"><meta name="robots" content="noindex, nofollow"></div>

        <ul class="geofs-list geofs-toggle-panel geofs-preference-list geofs-preferences" data-noblur="true" data-onshow="{geofs.initializePreferencesPanel()}" data-onhide="{geofs.savePreferencesPanel()}">

    <fieldset style="margin: 15px 0px 0px 10px;" class="geofs-onlyForMobileDevice geofs-hideForApp">
        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="mobileSettings" id="0.1662506126229839" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
            <input type="checkbox" id="mobileSettings" class="mdl-switch__input" data-gespref="geofs.preferences.mobile" data-update="{geofs.mobile.setMobileMode()}">
            <span class="mdl-switch__label">Mobile Optimized Settings</span>
        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.1662506126229839" data-upgraded=",MaterialTooltip">Mobile Optimized Settings</div>
    </fieldset>

    <li class="geofs-list-collapsible-item">General

        <div class="geofs-collapsible">
            <fieldset>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-hideForMobile is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="transparentUi" id="0.2742193671724593" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="transparentUi" class="mdl-switch__input" data-gespref="geofs.preferences.interface.transparent" data-update="{ui.applyPreferences()}">
                    <span class="mdl-switch__label">Transparent User Interface</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.2742193671724593" data-upgraded=",MaterialTooltip">Toggle transparent User Interface</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-hideForMobile mdl-js-ripple-effect--ignore-events is-upgraded" for="yokeCursor" id="0.2316086701882305" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="yokeCursor" class="mdl-switch__input" data-gespref="geofs.preferences.interface.showYokeCursor" data-update="{ui.applyPreferences()}">
                    <span class="mdl-switch__label">Show yoke mouse cursor (more visible)</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.2316086701882305" data-upgraded=",MaterialTooltip">Toggle transparent User Interface</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="crashDetection" id="0.7734243536953391" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="crashDetection" class="mdl-switch__input" data-gespref="geofs.preferences.crashDetection">
                    <span class="mdl-switch__label">Detect crashes</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.7734243536953391" data-upgraded=",MaterialTooltip">Enable crash detection</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="headMotion" id="0.7509372525537741" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="headMotion" class="mdl-switch__input" data-gespref="geofs.preferences.camera.headMotion">
                    <span class="mdl-switch__label">Cockpit view head motion</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.7509372525537741" data-upgraded=",MaterialTooltip">Enable head acceleration motion</div>
<!--
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect" for="circuits" title="Show Circuit over runways">
                    <input type="checkbox" id="circuits" class="mdl-switch__input" data-gespref="geofs.preferences.circuits" data-update="{geofs.runways.setCircuitVisibility(this.checked)}">
                    <span class="mdl-switch__label">Show Runway Circuits</span>
                </label>
-->
            </fieldset>

            <fieldset>
                <legend>
                    <a href="https://dispatch.simbrief.com/home" target="_blank" rel="nofollow"><img src="/images/simbrieflogo.png" style="float: left; margin-right: 10px; margin-top: 4px;"></a>
                </legend>
                If you have a <a href="https://dispatch.simbrief.com/home" target="_blank" rel="nofollow">Navigraph SimBrief</a> account, enter your username here to be able to import your latest flight plan directly into GeoFS.
                <div class="mdl-textfield mdl-js-textfield is-upgraded" data-upgraded=",MaterialTextfield">
                    <input class="mdl-textfield__input" type="text" data-gespref="geofs.preferences.simBriefUsername" id="simBriefUsername">
                    <label class="mdl-textfield__label" for="sample1">SimBrief Alias/Username</label>
                </div>
            </fieldset>

            <fieldset class="geofs-hideForApp">
                <legend>
                    Multi-monitor
                </legend>
                <button class="mdl-button mdl-js-button mdl-button--raised" onclick="geofs.camera.openSlaveWindow(-1);" id="0.619221163577172" tabindex="0" data-upgraded=",MaterialButton">
                    Open left screen
                </button><div class="mdl-tooltip undefined" for="0.619221163577172" data-upgraded=",MaterialTooltip">Extend screen to the left</div>
                <button class="mdl-button mdl-js-button mdl-button--raised" style="float: right;" onclick="geofs.camera.openSlaveWindow(1);" id="0.139231620874247" tabindex="0" data-upgraded=",MaterialButton">
                    Open right screen
                </button><div class="mdl-tooltip undefined" for="0.139231620874247" data-upgraded=",MaterialTooltip">Extend screen to the right</div>
                <div class="slider" data-type="slider" data-gespref="geofs.preferences.graphics.slaveQuality" value="3" data-min="1" data-max="6" data-precision="0" id="0.47130725044940536" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 40%;">
                            <div class="slider-grippy">
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Slave window quality</label>
                </div><div class="mdl-tooltip undefined" for="0.47130725044940536" data-upgraded=",MaterialTooltip">Quality Level</div>
            </fieldset>
            <fieldset>
                <legend>
                    Sound Volume
                </legend>
                <div class="slider" data-type="slider" data-gespref="geofs.preferences.volume" data-update="{audio.soundplayer.setMasterVolume()}" value="1" data-min="0" data-max="1" data-precision="1" id="0.5505080036473604" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 50%;">
                            <div class="slider-grippy">
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Volume</label>
                </div><div class="mdl-tooltip undefined" for="0.5505080036473604" data-upgraded=",MaterialTooltip">Sound Volume</div>
            </fieldset>
            <fieldset class="geofs-hideForApp">
                <!-- Colored mini FAB button -->
                <button class="mdl-button mdl-js-button mdl-button--raised " onclick="geofs.getLink();" id="0.19636270685653057" tabindex="0" data-upgraded=",MaterialButton">
                    Generate a link to the current location
                </button><div class="mdl-tooltip undefined" for="0.19636270685653057" data-upgraded=",MaterialTooltip">Get a URL to the current flight and location</div>
                <div class="geofs-linkOutput"></div>
            </fieldset>
        </div>
    </li>

    <li class="geofs-list-collapsible-item geofs-preference-controls">Controls

        <ul class="geofs-list geofs-collapsible">
            <!-- Controls -->
            <li>Select a control device and configure it.</li>

            <li class="no-hover geofs-list-collapsible-item geofs-hideForApp">
                <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect geofs-stopMousePropagation geofs-expendable-radio mdl-js-ripple-effect--ignore-events is-upgraded" for="control-keyboard" data-upgraded=",MaterialRadio,MaterialRipple">

                    <input type="radio" id="control-keyboard" class="mdl-radio__button" name="control" data-update="{controls.setMode(value)}" data-gespref="geofs.preferences.controlMode" data-matchvalue="keyboard">
                    <span class="mdl-radio__label">Keyboard [K]
                    </span>
                <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                configure
                <div class="geofs-collapsible">

                    <fieldset>
                        <legend>
                            Settings
                        </legend>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="keyboardMixYawRoll" id="0.06198056855542755" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="keyboardMixYawRoll" class="mdl-switch__input" data-gespref="geofs.preferences.keyboard.mixYawRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Mix Roll/Yaw</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.06198056855542755" data-upgraded=",MaterialTooltip">Mixes the rudder with the ailerons input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="keyboardSteerWithRoll" id="0.5760503629593463" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="keyboardSteerWithRoll" class="mdl-switch__input" data-gespref="geofs.preferences.keyboard.steerWithRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Ground steering with roll input</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.5760503629593463" data-upgraded=",MaterialTooltip">Assign ground steering to ailerons as well as rudder input</div>
                        <div class="slider" data-type="slider" data-gespref="geofs.preferences.keyboard.sensitivity" data-update="{controls.setMode()}" value="0" data-min="0.1" data-max="4" data-precision="1" id="0.7296256005884914" tabindex="0">
                            <div class="slider-rail">
                                <div class="slider-selection" style="width: 25.641%;">
                                    <div class="slider-grippy">
                                        <input class="slider-input">
                                    </div>
                                </div>
                            </div>
                            <label>Sensitivity</label>
                        </div><div class="mdl-tooltip undefined" for="0.7296256005884914" data-upgraded=",MaterialTooltip">Sets how quickly the input responds</div>

                        <!--
                        <br/>Exponential: <div data-max="2" class="geofs-ui-slider" data-gespref="geofs.preferences.keyboard.exponential" ></div>
                        -->
                    </fieldset>
                    <fieldset>
                        <legend>
                            Keys
                        </legend>
                        <div class="geofs-keyboard-keys-container"><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput65" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Toggle Autopilot" keycode="65" value="<A>"><label class="mdl-textfield__label" for="keyInput65">Toggle Autopilot</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput37" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Bank left" keycode="37" value="<Left Arrow>"><label class="mdl-textfield__label" for="keyInput37">Bank left</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput39" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Bank right" keycode="39" value="<Right Arrow>"><label class="mdl-textfield__label" for="keyInput39">Bank right</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput38" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Pitch down" keycode="38" value="<Up Arrow>"><label class="mdl-textfield__label" for="keyInput38">Pitch down</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput40" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Pitch up" keycode="40" value="<Down Arrow>"><label class="mdl-textfield__label" for="keyInput40">Pitch up</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput188" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Steer left" keycode="188" value="<"><label class="mdl-textfield__label" for="keyInput188">Steer left</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput190" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Steer right" keycode="190" value=">"><label class="mdl-textfield__label" for="keyInput190">Steer right</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput32" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Brakes" keycode="32" value="<Space bar>"><label class="mdl-textfield__label" for="keyInput32">Brakes</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput186" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Parking brake" keycode="186" value=";"><label class="mdl-textfield__label" for="keyInput186">Parking brake</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput107" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Increase throttle" keycode="107" value="+"><label class="mdl-textfield__label" for="keyInput107">Increase throttle</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput109" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Decrease throttle" keycode="109" value="-"><label class="mdl-textfield__label" for="keyInput109">Decrease throttle</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput33" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Increase throttle alt" keycode="33" value="<Page up>"><label class="mdl-textfield__label" for="keyInput33">Increase throttle alt</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput34" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Decrease throttle alt" keycode="34" value="<Page down>"><label class="mdl-textfield__label" for="keyInput34">Decrease throttle alt</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput36" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Elevator trim up" keycode="36" value="<Home>"><label class="mdl-textfield__label" for="keyInput36">Elevator trim up</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput35" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Elevator trim down" keycode="35" value="<End>"><label class="mdl-textfield__label" for="keyInput35">Elevator trim down</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput46" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Elevator trim neutral" keycode="46" value="<Delete>"><label class="mdl-textfield__label" for="keyInput46">Elevator trim neutral</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput69" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Engine switch (on/off)" keycode="69" value="E"><label class="mdl-textfield__label" for="keyInput69">Engine switch (on/off)</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput70" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Cycle flaps" keycode="70" value="F"><label class="mdl-textfield__label" for="keyInput70">Cycle flaps</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput71" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Gear toggle (up/down)" keycode="71" value="G"><label class="mdl-textfield__label" for="keyInput71">Gear toggle (up/down)</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput90" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Accessories (hook/floats/rudder) toggle" keycode="90" value="Z"><label class="mdl-textfield__label" for="keyInput90">Accessories (hook/floats/rudder) toggle</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput219" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Lower flaps" keycode="219" value="["><label class="mdl-textfield__label" for="keyInput219">Lower flaps</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput221" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Raise flaps" keycode="221" value="]"><label class="mdl-textfield__label" for="keyInput221">Raise flaps</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput66" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Airbrake toggle (on/off)" keycode="66" value="B"><label class="mdl-textfield__label" for="keyInput66">Airbrake toggle (on/off)</label></div><div class="mdl-textfield mdl-js-textfield mdl-textfield--floating-label is-dirty is-upgraded" data-upgraded=",MaterialTextfield"><input id="keyInput88" class="geofs-preferences-key-detect mdl-textfield__input" type="text" data-type="keydetect" data-gespref="geofs.preferences.keyboard.keys.Optional Animated Part toggle (on/off)" keycode="88" value="X"><label class="mdl-textfield__label" for="keyInput88">Optional Animated Part toggle (on/off)</label></div></div>
                    </fieldset>
                </div>
            </li>
            <li class="no-hover geofs-list-collapsible-item geofs-hideForApp">
                <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect geofs-stopMousePropagation geofs-expendable-radio is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="control-mouse" data-upgraded=",MaterialRadio,MaterialRipple">

                    <input type="radio" id="control-mouse" class="mdl-radio__button" name="control" data-update="{controls.setMode(value)}" data-gespref="geofs.preferences.controlMode" data-matchvalue="mouse">

                    <span class="mdl-radio__label">Mouse [M]</span>
                <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                configure
                <div class="geofs-collapsible">
                    <fieldset>
                        <legend>
                            Settings
                        </legend>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="mouseMixYawRoll" id="0.4888029492332413" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="mouseMixYawRoll" class="mdl-switch__input" data-gespref="geofs.preferences.mouse.mixYawRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Mix Roll/Yaw</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.4888029492332413" data-upgraded=",MaterialTooltip">Mixes the rudder with the ailerons input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="mouseSteerWithRoll" id="0.09047267621618471" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="mouseSteerWithRoll" class="mdl-switch__input" data-gespref="geofs.preferences.mouse.steerWithRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Ground steering with roll input</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.09047267621618471" data-upgraded=",MaterialTooltip">Assign ground steering to ailerons as well as rudder input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="mouseReverse" id="0.9770030454236374" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="mouseReverse" class="mdl-switch__input" data-gespref="geofs.preferences.mouse.reverse" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Reverse Pitch</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.9770030454236374" data-upgraded=",MaterialTooltip">Reverse Mouse Pitch Control (Up to pull, down to push)</div>
                        <div class="slider" data-type="slider" data-gespref="geofs.preferences.mouse.sensitivity" data-update="{controls.setMode()}" value="0" data-min="0.1" data-max="2" data-precision="1" id="0.44730348871943515" tabindex="0">
                            <div class="slider-rail">
                                <div class="slider-selection" style="width: 47.3684%;">
                                    <div class="slider-grippy">
                                        <input class="slider-input">
                                    </div>
                                </div>
                            </div>
                            <label>Sensitivity</label>
                        </div><div class="mdl-tooltip undefined" for="0.44730348871943515" data-upgraded=",MaterialTooltip">Sets how quickly the input responds</div>

                    </fieldset>
                </div>
            </li>
            <li class="no-hover geofs-list-collapsible-item">
                <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect geofs-stopMousePropagation geofs-expendable-radio mdl-js-ripple-effect--ignore-events is-upgraded" for="control-joystick" data-upgraded=",MaterialRadio,MaterialRipple">
                    <input type="radio" id="control-joystick" class="mdl-radio__button" name="control" data-update="{controls.setMode(value)}" data-gespref="geofs.preferences.controlMode" data-matchvalue="joystick">
                    <span class="mdl-radio__label geofs-hideForMobile">Joystick [J]</span>
                    <span class="mdl-radio__label geofs-onlyForMobile">Gamepad</span>
                <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                configure
                <div class="geofs-collapsible geofs-preferences-joystick">

                    <fieldset class="geofs-preferences-joystick-status">
                        <legend>
                            Detected Device(s)
                        </legend>
                        <div class="alert alert-error" style="display: none;">
                            <b style="color: red;">Your browser does not appear to support the native GamePad API</b>
                        </div>
                        <div class="alert alert-warning">
                            <b>Joystick not detected:</b> press a button on the Joystick to enable it.
                        </div>
                        <div class="alert alert-success" style="display: none;"></div>
                    </fieldset>

                    <fieldset>
                        <legend>
                            Settings
                        </legend>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="joystickMixYawRoll" id="0.5863907479275983" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="joystickMixYawRoll" class="mdl-switch__input" data-gespref="geofs.preferences.joystick.mixYawRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Mix Roll/Yaw</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.5863907479275983" data-upgraded=",MaterialTooltip">Mixes the rudder with the ailerons input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="joystickSteerWithRoll" id="0.6281147321344482" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="joystickSteerWithRoll" class="mdl-switch__input" data-gespref="geofs.preferences.joystick.steerWithRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Ground steering with roll input</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.6281147321344482" data-upgraded=",MaterialTooltip">Assign ground steering to ailerons as well as rudder input</div>
                        <div class="slider" data-type="slider" data-gespref="geofs.preferences.joystick.sensitivity" data-update="{controls.setMode()}" value="0" data-min="0.1" data-max="2" data-precision="1" id="0.6518210843427199" tabindex="0">
                            <div class="slider-rail">
                                <div class="slider-selection" style="width: 47.3684%;">
                                    <div class="slider-grippy">
                                        <input class="slider-input">
                                    </div>
                                </div>
                            </div>
                            <label>Sensitivity</label>
                        </div><div class="mdl-tooltip undefined" for="0.6518210843427199" data-upgraded=",MaterialTooltip">Sets how quickly the input responds</div>

                    </fieldset>
                    <fieldset>
                        <legend>
                            Axes
                        </legend>
                        <div class="geofs-joystick-calibration" style="position: relative;">
                            <button class="mdl-button mdl-js-button mdl-button--raised geofs-joystick-startCalibration" style="position: absolute; right: 10px; top: -15px;" onclick="controls.joystick.startCalibration();" id="0.07349229825553483" tabindex="0" data-upgraded=",MaterialButton">Calibrate</button><div class="mdl-tooltip undefined" for="0.07349229825553483" data-upgraded=",MaterialTooltip">Joystick calibration</div>
                            <div class="geofs-preferences-comment geofs-calibrating" style="display: none; color: #ab8000;">Calibrating: move all axes to full range of motion (<span class="geofs-joystick-calibrationProgress" style="font-weight: bold;"></span>)</div>
                            <div class="geofs-preferences-comment geofs-calibrated">Move the joystick to check activity</div>
                        </div>
                        <div class="geofs-joystick-axes-container">
                            <!-- Populated by javascript - preferences.js -->
                        </div>
                    </fieldset>
                    <fieldset>
                        <legend>
                            Buttons
                        </legend>
                        <div class="geofs-preferences-comment">
                            Press joystick buttons to check activity
                        </div>
                        <div class="geofs-joystick-button-container">
                            <!-- Populated by javascript - preferences.js -->
                        </div>
                    </fieldset>
                </div>
            </li>
            <li class="no-hover geofs-list-collapsible-item geofs-preferences-orientation geofs-onlyForMobile" style="display: list-item;">
                <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect geofs-stopMousePropagation geofs-expendable-radio mdl-js-ripple-effect--ignore-events is-upgraded" for="control-orientation" data-upgraded=",MaterialRadio,MaterialRipple">
                    <input type="radio" id="control-orientation" class="mdl-radio__button" name="control" onclick="controls.orientation.requestIOSPermission()" data-update="{controls.setMode(value)}" data-gespref="geofs.preferences.controlMode" data-matchvalue="orientation">
                    <span class="mdl-radio__label">Orientation
                    </span>
                <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                configure
                <div class="geofs-collapsible">

                    <fieldset>
                        <legend>
                            Settings
                        </legend>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="orientationMixYawRoll" id="0.2032436728664353" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="orientationMixYawRoll" class="mdl-switch__input" data-gespref="geofs.preferences.orientation.mixYawRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Mix Roll/Yaw</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.2032436728664353" data-upgraded=",MaterialTooltip">Mixes the rudder with the ailerons input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="orientationSteerWithRoll" id="0.8026717806575732" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="orientationSteerWithRoll" class="mdl-switch__input" data-gespref="geofs.preferences.orientation.steerWithRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Ground steering with roll input</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.8026717806575732" data-upgraded=",MaterialTooltip">Assign ground steering to ailerons as well as rudder input</div>
                        <div class="slider" data-type="slider" data-gespref="geofs.preferences.orientation.sensitivity" data-update="{controls.setMode()}" value="0" data-min="0.1" data-max="2" data-precision="1" id="0.028803347675375512" tabindex="0">
                            <div class="slider-rail">
                                <div class="slider-selection" style="width: 47.3684%;">
                                    <div class="slider-grippy">
                                        <input class="slider-input">
                                    </div>
                                </div>
                            </div>
                            <label>Sensitivity</label>
                        </div><div class="mdl-tooltip undefined" for="0.028803347675375512" data-upgraded=",MaterialTooltip">Sets how quickly the input responds</div>

                    </fieldset>
                    <fieldset style="float: left;">
                        <legend>
                            Axis
                        </legend>
                        <div class="geofs-preferences-comment">
                            Move the device to check activity.
                        </div>
                        <div class="geofs-feedback-wrapper">
                            <label>Pitch</label>
                            <select data-gespref="geofs.preferences.orientation.axis.pitch">
                                <option value="none">None</option>
                                <option value="0">Axis 0</option>
                                <option value="1">Axis 1</option>
                            </select>
                            <div class="progress" axis="pitch" centered="true">
                                <div class="bar"></div>
                            </div>

                            <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="reverseOrientationPitch" id="0.1791754849152123" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                                <input type="checkbox" id="reverseOrientationPitch" class="mdl-switch__input" data-gespref="geofs.preferences.orientation.multiplier.pitch" data-update="{controls.setMode()}">
                                <span class="mdl-switch__label">Inverse</span>
                            <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.1791754849152123" data-upgraded=",MaterialTooltip">Inverse axis</div>

                        </div>
                        <div class="geofs-feedback-wrapper">
                            <label>Roll</label>
                            <select data-gespref="geofs.preferences.orientation.axis.roll">
                                <option value="none">None</option>
                                <option value="0">Axis 0</option>
                                <option value="1">Axis 1</option>
                            </select>
                            <div class="progress" axis="roll" centered="true">
                                <div class="bar"></div>
                            </div>

                            <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="reverseOrientationRoll" id="0.15004325514200456" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                                <input type="checkbox" id="reverseOrientationRoll" class="mdl-switch__input" data-gespref="geofs.preferences.orientation.multiplier.roll" data-update="{controls.setMode()}">
                                <span class="mdl-switch__label">Inverse</span>
                            <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.15004325514200456" data-upgraded=",MaterialTooltip">Inverse axis</div>

                        </div>

                    </fieldset>

                    <div class="geofs-orientationReset geofs-orientationCalibratePerm" style="float: left; margin-top: 0px; display: inline-block; position: relative;">
                        <i class="material-icons md-48">
                            adjust
                        </i>
                        <br>
                        Tap to center controls
                    </div>
                </div>
            </li>
            <li class="no-hover geofs-list-collapsible-item geofs-preferences-touch geofs-onlyForMobile">
                <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect geofs-stopMousePropagation geofs-expendable-radio mdl-js-ripple-effect--ignore-events is-upgraded" for="control-touch" data-upgraded=",MaterialRadio,MaterialRipple">
                    <input type="radio" id="control-touch" class="mdl-radio__button" name="control" data-update="{controls.setMode(value)}" data-gespref="geofs.preferences.controlMode" data-matchvalue="touch">
                    <span class="mdl-radio__label">Touch Stick
                    </span>
                <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                configure
                <div class="geofs-collapsible">

                    <fieldset>
                        <legend>
                            Settings
                        </legend>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="touchMixYawRoll" id="0.5006336623897529" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="touchMixYawRoll" class="mdl-switch__input" data-gespref="geofs.preferences.touch.mixYawRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Mix Roll/Yaw</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.5006336623897529" data-upgraded=",MaterialTooltip">Mixes the rudder with the ailerons input</div>

                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="touchSteerWithRoll" id="0.2317492501224705" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="touchSteerWithRoll" class="mdl-switch__input" data-gespref="geofs.preferences.touch.steerWithRoll" data-update="{controls.setMode()}">
                            <span class="mdl-switch__label">Ground steering with roll input</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.2317492501224705" data-upgraded=",MaterialTooltip">Assign ground steering to ailerons as well as rudder input</div>
                        <div class="slider" data-type="slider" data-gespref="geofs.preferences.touch.sensitivity" data-update="{controls.setMode()}" value="0" data-min="0.01" data-max="1" data-precision="2" id="0.056875671240667725" tabindex="0">
                            <div class="slider-rail">
                                <div class="slider-selection" style="width: 19.1919%;">
                                    <div class="slider-grippy">
                                        <input class="slider-input">
                                    </div>
                                </div>
                            </div>
                            <label>Sensitivity</label>
                        </div><div class="mdl-tooltip undefined" for="0.056875671240667725" data-upgraded=",MaterialTooltip">Sets how quickly the input responds</div>

                    </fieldset>
                </div>
            </li>
        </ul>
    </li>

    <li class="geofs-list-collapsible-item geofs-multiplayer-preferences">Multiplayer

        <div class="geofs-collapsible">
            <!-- Multiplayer -->
            <fieldset>

                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="enableMultiplayer" id="0.4734039664864875" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="enableMultiplayer" class="mdl-switch__input" data-gespref="geofs.preferences.multiplayer" data-update="{if (this.checked) {multiplayer.start();} else {multiplayer.stop();}}">
                    <span class="mdl-switch__label">Enable multiplayer</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.4734039664864875" data-upgraded=",MaterialTooltip">Enable multiplayer</div>

                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-hideForSchool mdl-js-ripple-effect--ignore-events is-upgraded" for="showCommunityMultiplayer" id="0.39673138511429373" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="showCommunityMultiplayer" class="mdl-switch__input" data-gespref="geofs.preferences.showCommunityMultiplayer">
                    <span class="mdl-switch__label">Show Community Contributed 3D Models </span>
                    <i style="margin-top: -9px;position: absolute;margin-left: 23px;display: block;font-size: 12px;">Performance/stability not guarantied</i>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.39673138511429373" data-upgraded=",MaterialTooltip">Show Community Contributed Aircraft</div>

                <!--
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect" for="enableADSB" title="Enable ADS-B Traffic">
                    <input type="checkbox" id="enableADSB" class="mdl-switch__input" disabled="true" data-gespref="geofs.preferences.adsb" />
                    <span class="mdl-switch__label"><b>INOP </b><i style="color: #888; text-decoration-line: line-through;">Show ADS-B commercial traffic</i></span>
                </label>
                -->

                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="enableADSB" id="0.9460906901290482" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="enableADSB" class="mdl-switch__input" data-gespref="geofs.preferences.adsb">
                    <span class="mdl-switch__label">Show ADS-B commercial traffic</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.9460906901290482" data-upgraded=",MaterialTooltip">Enable ADS-B Traffic</div>


                <span class="geofs-hideForApp geofs-hideForSchool" style="display: inline-block; margin: 10px 0px 25px 0px;">
                    <a href="https://disboard.org/servers/tag/geofs?sort=-member_count" target="_blank" rel="nofollow"><img src="/images/discord.png" style="margin: 10px 10px 10px 0px;"></a>
                    For voice communication and community events, join one of the many <a href="https://disboard.org/servers/tag/geofs?sort=-member_count" target="_blank" rel="nofollow">GeoFS related Discord servers listed on Disboard.org</a>
                </span>

                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-hideForApp geofs-authenticated mdl-js-ripple-effect--ignore-events is-upgraded" for="enableChat" id="0.4130547037920558" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="enableChat" class="mdl-switch__input geofs-enabledWhenAuthenticated" data-gespref="geofs.preferences.chat" data-update="{ui.chat.visibility();}">
                    <span class="mdl-switch__label geofs-hideForSchool">Enable text chat (I am over 13)</span>
                    <span class="mdl-switch__label geofs-onlyForSchool">Enable text chat</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.4130547037920558" data-upgraded=",MaterialTooltip">Enable text chat</div>
                <i class="geofs-hideForApp geofs-hideForSchool geofs-authenticated">By enabling GeoFS chat, you confirm that you are more than 13 year old.<br></i>
                <i class="geofs-loggedout geofs-hideForApp geofs-hideForSchool">You must be logged in to use the chat<br></i>
                <i class="geofs-hideForApp geofs-hideForSchool geofs-authenticated"><b>The chat is self moderated: please stay courteous.<br>If you do not feel comfortable with this, please keep the chat off.</b><br></i>
                <i class="geofs-hideForApp geofs-hideForSchool geofs-authenticated"><b>Never exchange private information on the chat.</b><br></i>

            </fieldset>
        </div>
    </li>

    <li class="geofs-list-collapsible-item">Graphics

        <div class="geofs-collapsible">
            <!-- Graphics -->
            <fieldset>
                <legend class="geofs-hideForMobile">
                    Performance vs. Quality - Anything above 3 requires a fast computer
                </legend>
                <legend class="geofs-onlyForMobile">
                    Performance vs. Quality - (resolution, viewing distance, ...)
                </legend>
                <div class="slider" data-type="slider" data-gespref="geofs.preferences.graphics.quality" data-update="{geofs.api.renderingQuality()}" value="3" data-min="1" data-max="6" data-precision="0" id="0.6252779046143895" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 40%;">
                            <div class="slider-grippy">
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Quality Level</label>
                </div><div class="mdl-tooltip undefined" for="0.6252779046143895" data-upgraded=",MaterialTooltip">Quality Level</div>
            </fieldset>
            <fieldset class="geofs-advancedGraphics geofs-advanced">
                <span class="geofs-advancedToggle">
                    Advanced
                </span>
                <div class="geofs-stopMousePropagation">
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.resolutionScale" data-update="{geofs.api.advancedRenderingQuality()}" value="0" data-min="0.3" data-max="1.0" data-precision="1" id="0.7461163358218215" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 100%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Resolution</label>
                    </div><div class="mdl-tooltip undefined" for="0.7461163358218215" data-upgraded=",MaterialTooltip">Resolution</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.viewingDistance" data-update="{geofs.api.advancedRenderingQuality()}" value="0" data-min="1" data-max="7" data-precision="0" id="0.6490182546936885" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 33.3333%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Viewing Distance</label>
                    </div><div class="mdl-tooltip undefined" for="0.6490182546936885" data-upgraded=",MaterialTooltip">Viewing Distance</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.tileCacheSize" data-update="{geofs.api.advancedRenderingQuality()}" value="0" data-min="0" data-max="5000" data-precision="0" id="0.21569671391739198" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 5%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Tiles Cache Size</label>
                    </div><div class="mdl-tooltip undefined" for="0.21569671391739198" data-upgraded=",MaterialTooltip">Tiles Cache Size</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.shadowQuality" data-update="{geofs.api.advancedRenderingQuality()}" value="0" data-min="1" data-max="4" data-precision="0" id="0.8127157991394054" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Shadow Quality</label>
                    </div><div class="mdl-tooltip undefined" for="0.8127157991394054" data-upgraded=",MaterialTooltip">Shadow Quality</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.cloudDensity" data-update="{geofs.api.advancedRenderingQuality()}" value="0" data-min="0" data-max="1" data-precision="1" id="0.8944922703172113" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 70%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Billboard Clouds Density</label>
                    </div><div class="mdl-tooltip undefined" for="0.8944922703172113" data-upgraded=",MaterialTooltip">Clouds Density</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.scatteringQuality" data-update="{geofs.api.advancedRenderingQuality()}" value="1" data-min="1" data-max="7" data-precision="0" id="0.9998906604225319" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 16.6667%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Atmo. &amp; Vol. Clouds Quality</label>
                    </div><div class="mdl-tooltip undefined" for="0.9998906604225319" data-upgraded=",MaterialTooltip">Atmosphere Scattering and Volumetric Clouds Quality</div>
                    <div class="slider geofs-disabled" data-type="slider" data-gespref="geofs.preferences.graphics.advanced.msaaSamples" data-update="{geofs.api.advancedRenderingQuality()}" value="1" data-min="1" data-max="8" data-precision="0" id="0.8270092945081993" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Multisample anti-aliasing (MSAA)</label>
                    </div><div class="mdl-tooltip undefined" for="0.8270092945081993" data-upgraded=",MaterialTooltip">Multisample anti-aliasing</div>
                    <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="fxaa" id="0.8507372092131786" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                        <input type="checkbox" id="fxaa" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.advanced.fxaa" data-update="{geofs.api.advancedRenderingQuality()}">
                        <span class="mdl-switch__label">Fast approximate anti-aliasing (FXAA)</span>
                    <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.8507372092131786" data-upgraded=",MaterialTooltip">Fast approximate anti-aliasing</div>
                    <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="dropShadow" id="0.49831658132940215" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                        <input type="checkbox" id="dropShadow" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.advanced.dropShadow" data-update="{geofs.api.advancedRenderingQuality()}">
                        <span class="mdl-switch__label">Drop shadows</span>
                    <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.49831658132940215" data-upgraded=",MaterialTooltip">Drop Shadows</div>
                    <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="softShadows" id="0.14524489802502094" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                        <input type="checkbox" id="softShadows" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.advanced.softShadows" data-update="{geofs.api.advancedRenderingQuality()}">
                        <span class="mdl-switch__label">Soft shadows</span>
                    <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.14524489802502094" data-upgraded=",MaterialTooltip">Soft Shadows</div>
                    <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="globeLighting" id="0.479801193074344" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                        <input type="checkbox" id="globeLighting" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.advanced.globeLighting" data-update="{geofs.api.advancedRenderingQuality()}">
                        <span class="mdl-switch__label">Globe Lighting</span>
                    <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.479801193074344" data-upgraded=",MaterialTooltip">Globle Lighting</div>
                </div>
            </fieldset>

            <fieldset class="geofs-datasourceSelector">
                <legend>
                    Imagery data source
                </legend>
                <div class="geofs-SDImagerySelector">
                    <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="sdImagery" style="margin: 10px;" data-upgraded=",MaterialRadio,MaterialRipple">
                        <img src="/images/sd-logo.png" class="geofs-dataSourceLogo">
                        <input type="radio" id="sdImagery" class="mdl-radio__button" name="dataprovider" data-update="{geofs.api.setDataProvider(value)}" data-gespref="geofs.preferences.graphics.dataProvider" data-matchvalue="sd">
                        <span class="mdl-radio__label">Sentinel-2 Satellite Images (10m/px)</span>
                    <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                </div>
                <div class="geofs-SRImagerySelector" style="position: relative;">
                    <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="srImagery" style="margin: 10px;" data-upgraded=",MaterialRadio,MaterialRipple">
                        <img src="/images/sr-logo.png" class="geofs-dataSourceLogo">
                        <input type="radio" id="srImagery" class="mdl-radio__button" name="dataprovider" data-update="{geofs.api.setDataProvider(value)}" data-gespref="geofs.preferences.graphics.dataProvider" data-matchvalue="sr">
                        <span class="mdl-radio__label">Super-Resolution - AI Enhanced Satellite Images (1m/px)</span>
                    <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                    <div class="geofs-onlyForSR" style="position: absolute;border-radius: 20px;padding: 2px 35px 2px 10px;background: #fafafa;box-shadow: 1px 2px 6px #555;right:-5px;bottom:-11px;">
                        <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="runways" style="margin-bottom: 0px; margin-top: 0px;" id="0.3321549943406601" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                            <input type="checkbox" id="runways" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.runways" data-update="{geofs.runways.setRunwayModelVisibility(this.checked)}">
                            <span class="mdl-switch__label">Show Runway Overlays</span>
                        <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.3321549943406601" data-upgraded=",MaterialTooltip">Overlay Generic Runway Graphics to SR imagery</div>
                    </div>
                </div>
                <div class="geofs-HDImagerySelector">
                    <label class="mdl-radio mdl-js-radio mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="hdImagery" style="margin: 10px;" data-upgraded=",MaterialRadio,MaterialRipple">
                        <img src="/images/hd-logo.png" class="geofs-dataSourceLogo">
                        <input type="radio" id="hdImagery" class="mdl-radio__button" name="dataprovider" data-update="{geofs.api.setDataProvider(value)}" data-gespref="geofs.preferences.graphics.dataProvider" data-matchvalue="hd">
                        <span class="mdl-radio__label">High Definition Microsoft Bing (sub-meter resolution)</span>
                    <span class="mdl-radio__outer-circle"></span><span class="mdl-radio__inner-circle"></span><span class="mdl-radio__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label>
                    <a class="mdl-button mdl-js-button mdl-button--raised mdl-button--accent mdl-js-ripple-effect geofs-onlyForNonHDSubscribers geofs-subscribe-button geofs-onlyForApp" style="position: absolute; right: 20px;" data-upgraded=",MaterialButton,MaterialRipple">Subscribe
                    <span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></a><a class="mdl-button mdl-js-button mdl-button--raised mdl-button--accent mdl-js-ripple-effect geofs-onlyForNonHDSubscribers geofs-hideForApp" style="position: absolute; right: 20px;" href="/pages/hd.php" target="_blank" data-upgraded=",MaterialButton,MaterialRipple">Subscribe<span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></a>
                </div>
                                <div class="geofs-hdTrial-view geofs-hideForApp" style="position: relative;">
                    
<script>

    function initSubscribe() {

        if (window.subscribeInitialized) {
            return;
        }

        $(document).on('loginchange subscriptionchange', (event) => {
            $('.geofs-subscribe-view').htmlView('load', '/html/hd/subscribe.php');
        });

        $(document).on('click', '.geofs-startTrial', (event) => {
            $('.geofs-subscribe-view').htmlView('load', '/html/hd/subscribe.php?method=startHDTrial');
        });

        window.subscribeInitialized = true;

    }

    window.executeOnEventDone('deferredload', initSubscribe);

</script>

<style>

    .geofs-ingame .geofs-geofsHDConfirm,
    .geofs-ingame .geofs-purchase-frame,
    .geofs-ingame .geofs-renewNotice {
        display: none;
    }

</style>

<div class="geofs-subscribe-view geofs-payment-view">
    
<div class="geofs-geofsHDConfirm">

    </div>
            <div class="geofs-purchase-frame mdl-shadow--2dp">
                <h5>Purchase a GeoFS HD subscription</h5>
                <h6 class="geofs-notification geofs-info"><i class="material-icons"></i> You must login before purchasing a subscription.</h6>                <b>1 year GeoFS HD global aerial imagery<br><span class="geofs-HD-price">$12.23</span></b>
            </div>

            <h6 class="geofs-renewNotice" style="text-align: center;"><i>Subscription and trial do <b>not</b> renew automatically.<br>You can purchase a new subscription after expiration.</i></h6>

    </div>                </div>

            </fieldset>

            <fieldset>
                <legend>
                    Color enhancement
                </legend>
                <div class="slider" data-type="slider" data-gespref="geofs.preferences.graphics.enhanceColors" data-update="{geofs.api.enhanceColors(value)}" value="0" data-min="0.5" data-max="1.5" data-precision="1" id="0.8384715288309106" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 40%;">
                            <div class="slider-grippy">
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Enhancement Level</label>

                </div><div class="mdl-tooltip undefined" for="0.8384715288309106" data-upgraded=",MaterialTooltip">Imagery Color Enhancement</div>
               <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="advancedAtmosphere" id="0.3585607821095187" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="advancedAtmosphere" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.advancedAtmosphere" data-update="{geofs.api.renderingQuality()}">
                    <span class="mdl-switch__label">Advanced Atmosphere</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.3585607821095187" data-upgraded=",MaterialTooltip">Advanced Atmosphere</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="volumetricClouds" id="0.3963497765868822" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple" style="display: none;">
                    <input type="checkbox" id="volumetricClouds" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.volumetricClouds" data-update="{geofs.api.renderingQuality()}">
                    <span class="mdl-switch__label">Volumetric clouds</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.3963497765868822" data-upgraded=",MaterialTooltip">Volumetric clouds</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="buildings" id="0.8692481369846154" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="buildings" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.buildings" data-update="{geofs.api.setBuildings(this.checked)}">
                    <span class="mdl-switch__label">Buildings</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.8692481369846154" data-upgraded=",MaterialTooltip">Enable Buildings</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="vegetation" id="0.972704799357113" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="vegetation" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.vegetation" data-update="{geofs.api.setVegetation(this.checked)}">
                    <span class="mdl-switch__label">Vegetation</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.972704799357113" data-upgraded=",MaterialTooltip">Enable Vegetation</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="waterEffect" id="0.45575634537138465" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="waterEffect" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.waterEffect" data-update="{geofs.api.setWaterEffect(this.checked)}">
                    <span class="mdl-switch__label">Water effect</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.45575634537138465" data-upgraded=",MaterialTooltip">Enable water effect</div>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-hideForApp mdl-js-ripple-effect--ignore-events is-upgraded" for="contrails" id="0.3265876612643219" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="contrails" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.contrails">
                    <span class="mdl-switch__label">Contrails</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.3265876612643219" data-upgraded=",MaterialTooltip">Enable contrails</div>
<!--
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect geofs-onlyForSubscribers" for="hdonoff" title="Enable HD images">
                    <input type="checkbox" id="hdonoff" class="mdl-switch__input" data-gespref="geofs.preferences.graphics.HD"
                           data-update="{if (geofs.preferences.graphics.HD==this.checked) geofs.api.setHD(this.checked)}">
                    <span class="mdl-switch__label">Enable HD</span>
                </label>
-->
            </fieldset>
        </div>
    </li>

    <li class="geofs-list-collapsible-item">Environment

        <div class="geofs-collapsible">
            <!-- Weather -->
            <fieldset>
                <label class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="weatherManual" id="0.6135557564678313" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                    <input type="checkbox" id="weatherManual" class="mdl-switch__input" data-gespref="geofs.preferences.weather.manual" data-update="{weather.refresh();geofs.api.renderingQuality()}">
                    <span class="mdl-switch__label">Set environment manually</span>
                <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.6135557564678313" data-upgraded=",MaterialTooltip">Set environment manually</div>
            </fieldset>

            <fieldset style="display: none;">
                <legend>METAR</legend>
                <div class="geofs-metarDisplay"></div>
            </fieldset>

            <fieldset class="geofs-manualWeather">
                <legend>
                    Time of the day
                </legend>

                <div class="slider geofs-timeSlider" data-type="slider" data-gespref="geofs.preferences.weather.localTime" data-update="{weather.setDateAndTime()}" value="" data-min="0" data-max="24" data-precision="2" id="0.8144754311284967" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 51.4583%;">
                            <div class="slider-grippy">
                                <span class="slider-input-overlay">12:21</span>
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Time of the day in hours</label>
                </div><div class="mdl-tooltip undefined" for="0.8144754311284967" data-upgraded=",MaterialTooltip">Set time of day</div>
            </fieldset>

            <fieldset class="geofs-manualWeather">
                <legend>
                    Weather
                </legend>
                <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.quality" data-update="{weather.setManual()}" value="0" data-min="0" data-max="100" data-precision="0" id="0.2901476658147695" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 17%;">
                            <div class="slider-grippy">
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Weather quality</label>
                </div><div class="mdl-tooltip undefined" for="0.2901476658147695" data-upgraded=",MaterialTooltip">Weather quality</div>

                <div class="slider geofs-seasonSlider" data-type="slider" data-gespref="geofs.preferences.weather.season" data-update="{weather.setManual()}" value="" data-min="0" data-max="100" data-precision="0" id="0.5411142186500468" tabindex="0">
                    <div class="slider-rail">
                        <div class="slider-selection" style="width: 28%;">
                            <div class="slider-grippy">
                                <span class="slider-input-overlay">Summer</span>
                                <input class="slider-input">
                            </div>
                        </div>
                    </div>
                    <label>Season</label>
                </div><div class="mdl-tooltip undefined" for="0.5411142186500468" data-upgraded=",MaterialTooltip">Season</div>

            </fieldset>

            <fieldset class="geofs-manualWeather geofs-advancedWeather geofs-advanced">
                <span class="geofs-advancedToggle">
                    Advanced
                </span>
                <div class="geofs-stopMousePropagation">
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.clouds" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="100" data-precision="0" id="0.3500593422731224" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 34%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Clouds</label>
                    </div><div class="mdl-tooltip undefined" for="0.3500593422731224" data-upgraded=",MaterialTooltip">Clouds</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.cloudBase" data-update="{weather.setAdvanced()}" value="1500" data-min="1" data-max="5000" data-precision="0" id="0.404446209116343" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 19.984%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Clouds Ceiling m.</label>
                    </div><div class="mdl-tooltip undefined" for="0.404446209116343" data-upgraded=",MaterialTooltip">CloudsCeiling</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.cloudThickness" data-update="{weather.setAdvanced()}" value="4000" data-min="500" data-max="10000" data-precision="0" id="0.33743851280989356" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 14.3158%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Clouds Thickness m.</label>
                    </div><div class="mdl-tooltip undefined" for="0.33743851280989356" data-upgraded=",MaterialTooltip">CloudsThickness</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.precipitationAmount" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="100" data-precision="0" id="0.4954841505741836" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Precipitations</label>
                    </div><div class="mdl-tooltip undefined" for="0.4954841505741836" data-upgraded=",MaterialTooltip">Precipitations</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.fog" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="100" data-precision="0" id="0.023511337708880475" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Fog</label>
                    </div><div class="mdl-tooltip undefined" for="0.023511337708880475" data-upgraded=",MaterialTooltip">Fog</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.fogCeiling" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="3000" data-precision="0" id="0.49458818729037124" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 8.63333%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Fog Ceiling m.</label>
                    </div><div class="mdl-tooltip undefined" for="0.49458818729037124" data-upgraded=",MaterialTooltip">FogCeiling</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.windSpeedKts" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="40" data-precision="0" id="0.32186581705981654" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Wind Speed knots</label>
                    </div><div class="mdl-tooltip undefined" for="0.32186581705981654" data-upgraded=",MaterialTooltip">windSpeed</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.windDirection" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="360" data-precision="0" id="0.6755452752259421" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 0%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Wind Direction Deg.</label>
                    </div><div class="mdl-tooltip undefined" for="0.6755452752259421" data-upgraded=",MaterialTooltip">windDirection</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.turbulences" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="1" data-precision="1" id="0.019837615780785356" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 20%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Turbulences.</label>
                    </div><div class="mdl-tooltip undefined" for="0.019837615780785356" data-upgraded=",MaterialTooltip">turbulences</div>
                    <div class="slider" data-type="slider" data-gespref="geofs.preferences.weather.advanced.thermals" data-update="{weather.setAdvanced()}" value="0" data-min="0" data-max="1" data-precision="1" id="0.004060943114249316" tabindex="0">
                        <div class="slider-rail"><div class="slider-selection" style="width: 70%;"><div class="slider-grippy"><input class="slider-input"></div></div></div><label>Thermals.</label>
                    </div><div class="mdl-tooltip undefined" for="0.004060943114249316" data-upgraded=",MaterialTooltip">thermals</div>
                </div>
            </fieldset>
        </div>
    </li>

    
    <!--
    <li class="geofs-list-collapsible-item geofs-onlyForMobile">Reset settings
        <div class="geofs-collapsible geofs-tab-debug">
            In case of recurring error, please try to reset saved settings to default:<br/>
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" onclick="geofs.resetPreferences(/*refreshPanel*/ true);">Reset Settings</button>
        </div>
    </li>
-->
    <li class="geofs-list-collapsible-item">Debug info
        <div class="geofs-collapsible geofs-tab-debug">
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" onclick="geofs.resetPreferences(/*refreshPanel*/ true);" data-upgraded=",MaterialButton">Reset Settings &amp; Preferences</button><br><br>
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--accent" onclick="window.location.reload(true);" data-upgraded=",MaterialButton">Reload with GEOFS clean cache</button><br><br>
            GeoFS version: 3.9<br><br>
            <div class="geofs-debug-info">Network Latency (avg): 1.9e+2 ms<br>Frame rate (avg): 22 fps<br>--------------<br><b>Last 10 log messages:</b><br>terrainStable<br>--------------<br><b>WebGL info:</b><br>gl.VERSION: WebGL 2.0 (OpenGL ES 3.0 Chromium)<br>gl.SHADING_LANGUAGE_VERSION: WebGL GLSL ES 3.00 (OpenGL ES GLSL ES 3.0 Chromium)<br>gl.VENDOR: WebKit<br>gl.RENDERER: WebKit WebGL<br>UNMASKED_RENDERER_WEBGL: ANGLE (Intel, Intel(R) UHD Graphics (0x00009A78) Direct3D11 vs_5_0 ps_5_0, D3D11)<br>UNMASKED_VENDOR_WEBGL: Google Inc. (Intel)<br></div>
        </div>
    </li>

    <button class="mdl-button mdl-js-button mdl-button--fab mdl-button--accent mdl-js-ripple-effect geofs-close-panel geofs-onlyForMobile" onclick="geofs.savePreferencesPanel(); ui.closePreferencePanel();" data-upgraded=",MaterialButton,MaterialRipple"><i class="material-icons">close</i><span class="mdl-button__ripple-container"><span class="mdl-ripple"></span></span></button>

    <!-- Bottom buttons -->
    <div class="geofs-preferenceForm geofs-hideForMobile">
        <div style="float: left;">
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" onclick="geofs.resetPreferences(/*refreshPanel*/ true);" data-upgraded=",MaterialButton">Reset Settings</button>
        </div>
        <div style="float: right;">
            <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--accent" onclick="geofs.savePreferencesPanel(); ui.closePreferencePanel();" data-upgraded=",MaterialButton">Save &amp; Close</button>
        </div>
    </div>
</ul>
        <ul class="geofs-list geofs-toggle-panel geofs-location-list">

    <li class="geofs-list-collapsible-item">Gliding/Wingsuit
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([49.52150,22.41008,0,-166, true]);">Gravity launch - Bezmiechowa, Poland</li>
            <li data-location="geofs.flyTo([32.88577,-117.25325,164,-12, true]);">Slope soaring - Torrey Pines - San Diego - USA</li>
            <li data-location="geofs.flyTo([54.21837,-1.22314,763,26, true]);">Yorkshire Gliding Club - North Yorkshire - UK</li>
            <li data-location="geofs.flyTo([45.21552,5.74775,1598,42, true]);">Ridge Soaring - Le Versoud - Grenoble - France</li>
            <li data-location="geofs.flyTo([8.01869,46.36961,2971,61, true]);">Alpine Glaciers - toward Münster - Switzerland</li>
            <li data-location="geofs.flyTo([45.81749,6.84854,6467,55, true]);">Wingsuit drop - Mont Blanc - France</li>
            <li data-location="geofs.flyTo([47.1560,9.30583,2882,-155, true]);">Wingsuit drop - "The Crack" - Walenstadt - Switzerland</li>
            <li data-location="geofs.flyTo([37.74321,-119.53340,2725,-49, true]);">Wingsuit drop - "Half Dome" - Yosemite National Park, USA</li>
        </ul>
    </li>

    <li class="geofs-list-collapsible-item">Canyons
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([36.38005,-117.46087,725,-108, true]);">Rainbow "Star Wars" Canyon - USA</li>
            <li data-location="geofs.flyTo([39.70598,-121.47025,1171,2, true]);">Feather River "Top Gun" Canyon - USA</li>
            <li data-location="geofs.flyTo([52.72760,-3.82962,340,-159, true]);">Mach Loop - Wales - UK</li>
            <li data-location="geofs.flyTo([43.89442,3.43265,660,71, true]);">Gorges de la Vis - France</li>
            <li data-location="geofs.flyTo([29.74833,95.09795,5356,-80, true]);">Yarlung Tsangpo Grand Canyon - Tibet</li>
            <li data-location="geofs.flyTo([-24.55816,30.70011,2301,52, true]);">Blyde River Canyon - South Africa</li>
            <li data-location="geofs.flyTo([36.06467,-113.33665,2858,168,true]);">Grand Canyon - USA</li>
        </ul>
    </li>

    <li class="geofs-list-collapsible-item">Special Approaches
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([51.50137,0.17804,786,-87, true]);">London City Airport (Runway 27 with steep 5.5° ILS slope)</li>
            <li data-location="geofs.flyTo([36.145,-5.551,800,90, true]);">Gibraltar Int'l</li>
            <li data-location="geofs.flyTo([37.807416414832694,-122.6137032378986,309,173.32, true]);">USS John C. Stennis (Carrier)</li>
            <li data-location="geofs.flyTo([24.55734481134812,-81.71068081353695,500,-91.41, true]);">Key West Int'l.</li>
            <li data-location="geofs.flyTo([18.034682701324222,-63.15433542979288,350,82, true]);">Princess Juliana Airport, Saint Maarten</li>
            <li data-location="geofs.flyTo([32.73121515773958,-16.735523534674982,317,-134, true]);">Santa Catarina Airport (Funchal), Madeira</li>
            <li data-location="geofs.flyTo([43.71957166711304,7.303216893528995,450,-135.72, true]);">Aéroport Nice Côte d'Azur</li>
            <li data-location="geofs.flyTo([-44.76861,167.75399,558,178, true]);">Quintin Lodge Airstrip - New Zealand</li>
            <li data-location="geofs.flyTo([45.43225365746484,6.683131212012103,2500,-134, true]);">Courchevel Altiport</li>
            <li data-location="geofs.flyTo([45.86370,6.622133,1600,155, true]);">Megève Altiport</li>
            <li data-location="geofs.flyTo([45.44933,6.54963,2000,156, true]);">Méribel Altiport</li>
            <li data-location="geofs.flyTo([27.660295165543864,86.7058402035465,3255,31, true]);">Lukla - Nepal (approach)</li>
            <li data-location="geofs.flyTo([17.6543948750155,-63.24368391186655,154,115, true]);">Juancho E. Yrausquin - Saba (approach)</li>
            <li data-location="geofs.flyTo([43.578924,-6.09867,550,104, true]);">Asturias - Spain (approach)</li>
            <li data-location="geofs.flyTo([30.578892650446615,2.814844431592091,800,102.44, true]);">El Golea - Algeria (approach)</li>
            <li data-location="geofs.flyTo([17.9039979948387,-62.85894189052203,162,87, true]);">Saint Barthélemy (approach)</li>
            <li data-location="geofs.flyTo([56.998322183007005,-7.410804568469447,376,-47, true]);">Barra Airport - Scotland (beach landing)</li>
        </ul>
    </li>

    <li class="geofs-list-collapsible-item">On Runway
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([-22.81244,-43.26368,0,126]);">Rio Galeão – Tom Jobim International Airport (Brazil) - 15</li>
            <li data-location="geofs.flyTo([48.99873,2.60975,0,-95]);">Charles de Gaulle International Airport - 26R</li>
            <li data-location="geofs.flyTo([51.15143,-0.16629,0,-102]);">London Gatwick Airport - 26L</li>
            <li data-location="geofs.flyTo([37.62616,-122.39275,0,118]);">San Francisco International Airport - 10R</li>
            <li data-location="geofs.flyTo([40.45589,-3.54654,0,-39]);">Madrid–Barajas Airport - 32L</li>
            <li data-location="geofs.flyTo([52.29109,4.77737,0,2]);">Amsterdam Airport Schiphol - 36R</li>
            <li data-location="geofs.flyTo([43.66555302435758,7.228367855065596,0,-135]);">Aéroport Nice Côte d'Azur - 22L</li>
            <li data-location="geofs.flyTo([42.36021520436057,-70.98767662157663,0,-103.54]);">Logan Int'l (Boston) - 27</li>
            <li data-location="geofs.flyTo([25.800717256450998,-80.30116643603567,0,87.65]);">Miami Int'l - 08R</li>
            <li data-location="geofs.flyTo([39.66435,-119.89166,0,95]);">Reno Stead Airport 08 - (Reno Air Races) - USA</li>
            <li data-location="geofs.flyTo([33.93726741762918,-118.38364975124578,0,-96.50347129433592]);">Los Angeles Int'l, USA - 25L</li>
            <li data-location="geofs.flyTo([43.67416610318312,10.384369181910223,0,36.54]);">Pisa - Italy - 04R</li>
            <li data-location="geofs.flyTo([46.970496925890174,8.385052215851225,0,64]);">Buochs - Switzerland -  07L</li>
            <li data-location="geofs.flyTo([53.33191343454627,-2.3107668633750715,0,51.43]);">Manchester Int'l - UK - 05</li>
            <li data-location="geofs.flyTo([25.247580920322463,55.381149447648966,0,-58.28]);">Dubai Int'l - UAE - 30L</li>
            <li data-location="geofs.flyTo([35.67747,-117.68053,0,-26]);">Naval Air Weapons Station China Lake - USA - 32</li>
            <li data-location="geofs.flyTo([37.77915,-122.60885,0,176]);">USS John C. Stennis (Carrier)</li>
            <li data-location="geofs.flyTo([-29.930402181454788,27.84595492343562,0,56]);">Matekane Air Strip – Lesotho</li>
            <li data-location="geofs.flyTo([25.14114,55.18553,0,48]);">Burj Al Arab Helipad (Dubai)</li>
        </ul>
    </li>
    <li class="geofs-list-collapsible-item">Landmarks
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([-22.95814,-43.21994,687,67,true]);">Christ the Redeemer - Rio de Janeiro - Brazil</li>
            <li data-location="geofs.flyTo([48.86406,2.35407,588,-89,true]);">Eiffel Tower - Paris - France</li>
            <li data-location="geofs.flyTo([29.99106,31.16787,296,-122,true]);">Giza Pyramids - Cairo - Egypt</li>
            <li data-location="geofs.flyTo([37.82456,-122.52355,586,98,true]);">Golden Gate Bridge - San Francisco - USA</li>
            <li data-location="geofs.flyTo([-33.85425,151.22325,100,-100,true]);">Sydney Opera House - Australia</li>
            <li data-location="geofs.flyTo([40.67714,-74.04980,351,31,true]);">Statue of Liberty - New York City - USA</li>
            <li data-location="geofs.flyTo([37.96932,23.70606,290,95,true]);">Acropolis - Athens - Greece</li>
            <li data-location="geofs.flyTo([47.60582,10.71615,1077,153,true]);">Neuschwanstein Castle - Germany</li>
            <li data-location="geofs.flyTo([51.48472,-0.13910,561,37,true]);">Westminster - London - UK</li>
            <li data-location="geofs.flyTo([31.30692,32.30096,1041,176,true]);">Suez Canal - Egypt</li>
        </ul>
    </li>

    <li class="geofs-list-collapsible-item geofs-list-item-expanded">Nature and Landscapes
        <ul class="geofs-collapsible">
            <li data-location="geofs.flyTo([45.98150,6.92170,2966,-154,true]);">Chamonix - Alps - France</li>
            <li data-location="geofs.flyTo([55.93793,-4.92143,302,350,,true]);">West Coast of Scotland</li>
            <li data-location="geofs.flyTo([28.06110,86.97510,10000,-151,true]);">Mount Everest - Nepal</li>
            <li data-location="geofs.flyTo([43.76783,11.37363,863,-95,true]);">Florence - Tuscany - Italy</li>
            <li data-location="geofs.flyTo([31.10148,-7.59875,3661,-135,true]);">Atlas Mountains - Morocco</li>
            <li data-location="geofs.flyTo([-14.84324,-75.00751,2724,-52,true]);">Nazca - Peru</li>
            <li data-location="geofs.flyTo([24.73165,110.50282,1000,-70,true]);">Li Jiang Li river - China</li>
            <li data-location="geofs.flyTo([-25.37599,131.08359,717,-57,true]);">Uluru - Australia</li>
            <li data-location="geofs.flyTo([-14.52559,145.07787,2824,-41,true]);">Great Barrier Reef - Australia</li>
            <li data-location="geofs.flyTo([51.27062,-115.20700,2766,-114,true]);">Banff National Park - Canada</li>
            <li data-location="geofs.flyTo([-16.59100,-151.67659,1260,-39,true]);">Bora Bora - French Polynesia</li>
            <li data-location="geofs.flyTo([-34.00027,18.31149,1662,42,true]);">Cape Town - South Africa</li>
            <li data-location="geofs.flyTo([-24.75169,15.41842,1526,30,true]);">Namib Desert, Namib-Naukluft National Park - Namibia</li>
            <li data-location="geofs.flyTo([68.12074,13.27249,879,-146,true]);">Lofoten Islands - Norway</li>
            <li data-location="geofs.flyTo([63.01118,-41.96222,2453,-97,true]);">Glaciers - Tingmiarmit - Greenland</li>
            <li data-location="geofs.flyTo([57.88290,-6.74588,2124,-96,true]);">Isle of Skye - Scotland</li>
            <li data-location="geofs.flyTo([-34.19204,-69.57684,4458,-79,true]);">Laguna del Diamante - Argentina</li>
            <li data-location="geofs.flyTo([44.13973,9.66095,500,125,true]);">Cinque Terre - Italia</li>
            <li data-location="geofs.flyTo([28.95784,-13.78437,1429,53,true]);">Lanzarote - Canary Islands - Spain</li>
            <li data-location="geofs.flyTo([37.45566,15.10363,2501,-22,true]);">Mount Etna - Sicily - Italy</li>
            <li data-location="geofs.flyTo([35.05725,-111.06175,2971,128,true]);">Meteor Crater - Arizona - U.S.A.</li>
            <li data-location="geofs.flyTo([40.42196,116.59606,1327,-56,true]);">Great Wall of China - China</li>
            <li data-location="geofs.flyTo([35.31841,138.99077,1832,-86,true]);">Mount Fuji - Japan</li>
            <li data-location="geofs.flyTo([-20.98191,-174.98761,1285,-163,true]);">Tongatapu - Tonga</li>
            <li data-location="geofs.flyTo([-43.83974,170.11602,1162,2,true]);">Aoraki / Mount Cook - New Zealand</li>
            <li data-location="geofs.flyTo([-39.18926,174.01516,2136,149,true]);">Mount Taranaki - New Zealand</li>
            <li data-location="geofs.flyTo([-39.07978,175.66809,3121,-169,true]);">Mount Ngauruhoe - New Zealand</li>
            <li data-location="geofs.flyTo([-3.34227,37.20525,1225,24,true]);">Mount Kilimanjaro - Tanzania</li>
        </ul>
    </li>

    <form class="geofs-locationForm geofs-stopMousePropagation geofs-stopKeyupPropagation">
        <div class="mdl-textfield mdl-js-textfield has-placeholder is-upgraded" style="width: 100%; padding-right: 86px;" data-upgraded=",MaterialTextfield">
            <input class="mdl-textfield__input address-input" type="text" id="address" placeholder="Type destination, ICAO, etc.">
            <label class="mdl-textfield__label" for="address">Type destination...</label>
        </div>
        <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" type="submit" style="margin-left: -65px;" data-upgraded=",MaterialButton">Go</button>
    </form>

</ul>
        
<script>

    window.geofs = window.geofs || {};
    geofs.aircraftList = {};

    geofs.aircraftList['1'] = {name: 'Piper Cub', dir: '|models|aircraft|premium|cub|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['2'] = {name: 'Cessna 172', dir: '|models|aircraft|premium|cessna_172|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['3'] = {name: 'Alphajet PAF', dir: '|models|aircraft|premium|alphajet_paf|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['4'] = {name: 'Boeing 737-700', dir: '|models|aircraft|premium|737_700|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['5'] = {name: 'Embraer Phenom 100', dir: '|models|aircraft|premium|phenom_100|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['6'] = {name: 'de Havilland DHC6 Twin Otter', dir: '|models|aircraft|premium|dhc6|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['7'] = {name: ' F-16 Fighting Falcon', dir: '|models|aircraft|premium|f16|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['8'] = {name: 'Pitts Special S1', dir: '|models|aircraft|premium|pitts|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['9'] = {name: 'Eurocopter EC135', dir: '|models|aircraft|premium|ec135|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['10'] = {name: 'Airbus A380', dir: '|models|aircraft|premium|a380|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['11'] = {name: 'Alisport Silent 2 Electro', dir: '|models|aircraft|premium|silent2|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['12'] = {name: 'Pilatus PC-7 Mk-I', dir: '|models|aircraft|premium|pilatus|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['13'] = {name: 'de Havilland Canada DHC-2 Beaver', dir: '|models|aircraft|premium|dhc2|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['14'] = {name: 'Colomban MC-15 Cri-cri', dir: '|models|aircraft|premium|cricri|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['15'] = {name: 'Lockheed P-38 Lightning F-5B', dir: '|models|aircraft|premium|p38|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['16'] = {name: 'Douglas DC-3', dir: '|models|aircraft|premium|dc3|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['18'] = {name: 'Sukhoi Su-35', dir: '|models|aircraft|premium|su35|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['20'] = {name: 'Concorde', dir: '|models|aircraft|premium|concorde|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['21'] = {name: 'Zlin Z-50', dir: '|models|aircraft|zlin|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['22'] = {name: 'Cessna 152', dir: '|models|aircraft|cessna|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['23'] = {name: 'Piper PA-28 161 Warrior II Aerobility', dir: '|models|aircraft|premium|pa28|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['24'] = {name: 'Airbus A350', dir: '|models|aircraft|premium|a350|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['25'] = {name: 'Boeing 777-300ER', dir: '|models|aircraft|premium|777_300|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['26'] = {name: 'Antonov An-140', dir: '|models|aircraft|AN140|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['27'] = {name: 'Boeing F/A-18F Super Hornet', dir: '|models|aircraft|premium|fa18|', 'multiplayerFiles': 'multiplayer.glb,multiplayer-low.glb', 'community': 0};geofs.aircraftList['31'] = {name: 'Potez 25', dir: '|models|aircraft|premium|potez25|', 'multiplayerFiles': 'multiplayer.glb,multiplayer-low.glb', 'community': 0};geofs.aircraftList['40'] = {name: 'Evektor Sportstar', dir: '|models|aircraft|sportstar|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['41'] = {name: 'szd-48-3 Jantar', dir: '|models|aircraft|jantar|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['50'] = {name: 'Paraglider', dir: '|models|aircraft|paraglider|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['51'] = {name: 'Major Tom (hot air balloon)', dir: '|models|aircraft|premium|majortom|', 'multiplayerFiles': 'multiplayer.glb,multiplayer-low.glb', 'community': 0};geofs.aircraftList['52'] = {name: 'Hughes 269a/TH-55 Osage', dir: '|models|aircraft|hughes|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['53'] = {name: 'Goat Airchair', dir: '|models|aircraft|goat|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['102'] = {name: 'Citroen 2CV', dir: '|models|aircraft|premium|2cv|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['103'] = {name: 'Wingsuit', dir: '|models|aircraft|premium|wingsuit|', 'multiplayerFiles': 'multiplayer.glb,multiplayer-low.glb', 'community': 0};geofs.aircraftList['235'] = {name: 'Boeing 787-8', dir: '|backend|aircraft|repository|GXD01E_126645_235|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['236'] = {name: 'Embraer E190', dir: '|backend|aircraft|repository|GXD02RZ_126645_236|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['237'] = {name: 'Boeing 767-300ER', dir: '|backend|aircraft|repository|GXD03FI_126645_237|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['238'] = {name: 'Boeing 757-200', dir: '|backend|aircraft|repository|GXD04N_126645_238|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['239'] = {name: 'Airbus A350-900', dir: '|backend|aircraft|repository|GXD05OQ_166617_239|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['240'] = {name: 'Boeing 777-300ER', dir: '|backend|aircraft|repository|Boeing 777-300ER_933_240|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['242'] = {name: 'Airbus A321neo', dir: '|backend|aircraft|repository|D02_933_242|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['244'] = {name: 'Airbus A330-300', dir: '|backend|aircraft|repository|A02_166635_244|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['247'] = {name: 'Bombardier Dash 8 Q400', dir: '|backend|aircraft|repository|E01_166635_247|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['252'] = {name: 'Boeing 747-8 Freighter', dir: '|backend|aircraft|repository|A03_166635_252|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['1000'] = {name: 'Unkown', dir: '|models|aircraft|generics|787|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1001'] = {name: 'Boeing 73x', dir: '|models|aircraft|generics|73x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1002'] = {name: 'Boeing 74x', dir: '|models|aircraft|generics|74x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1003'] = {name: 'Boeing 75x', dir: '|models|aircraft|generics|75x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1004'] = {name: 'Boeing 76x', dir: '|models|aircraft|generics|76x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1005'] = {name: 'Boeing 77x', dir: '|models|aircraft|generics|77x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1006'] = {name: 'Boeing 78x', dir: '|models|aircraft|generics|78x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1007'] = {name: 'Airbus A31x', dir: '|models|aircraft|generics|a31x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1008'] = {name: 'Airbus A32x', dir: '|models|aircraft|generics|a32x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1009'] = {name: 'Airbus A33x', dir: '|models|aircraft|generics|a33x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1010'] = {name: 'Airbus A34x', dir: '|models|aircraft|generics|a34x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1011'] = {name: 'Airbus A35x', dir: '|models|aircraft|generics|a35x|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1012'] = {name: 'Airbus A380', dir: '|models|aircraft|generics|a380|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1013'] = {name: 'ATR42', dir: '|models|aircraft|generics|atr42|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1014'] = {name: 'BAE146', dir: '|models|aircraft|generics|bae146|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1015'] = {name: 'CRJ 700', dir: '|models|aircraft|generics|crj700|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1016'] = {name: 'CRJ 900', dir: '|models|aircraft|generics|crj900|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1017'] = {name: 'Embraer 170', dir: '|models|aircraft|generics|e170|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1018'] = {name: 'Embraer 190', dir: '|models|aircraft|generics|e190|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1019'] = {name: 'Piper PA-28', dir: '|models|aircraft|generics|pa28|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1020'] = {name: 'Dash 8', dir: '|models|aircraft|generics|dh8|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1021'] = {name: 'Cessna Citation', dir: '|models|aircraft|generics|c25a|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1022'] = {name: 'Cessna', dir: '|models|aircraft|generics|c182|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1023'] = {name: 'MD11', dir: '|models|aircraft|generics|md11|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1024'] = {name: 'Mirage 2000', dir: '|models|aircraft|generics|mirage2000|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1025'] = {name: 'Helicopter', dir: '|models|aircraft|generics|heli|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1026'] = {name: 'Cirrus SR22', dir: '|models|aircraft|generics|sr22|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1027'] = {name: 'Ground Vehicle', dir: '|models|objects|vehicles|truck|', 'multiplayerFiles': '', 'community': 0};geofs.aircraftList['1069'] = {name: 'Cirrus SR22 GTS Turbo', dir: '|backend|aircraft|repository|E02_166635_1069|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2000'] = {name: 'Retro 172', dir: '|models|aircraft|retro|c172|', 'multiplayerFiles': 'multiplayer.gltf,multiplayer-low.gltf', 'community': 0};geofs.aircraftList['2003'] = {name: 'Boeing 737-800', dir: '|backend|aircraft|repository|Boeing 737-800_187219_1003|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2004'] = {name: 'CRJ-900', dir: '|backend|aircraft|repository|CRJ-900_187219_1004|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2153'] = {name: 'Airbus A340-600', dir: '|backend|aircraft|repository|G5_166635_2153|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2310'] = {name: 'A-10C Thunderbolt II', dir: '|backend|aircraft|repository|A10 II Warthog_310810_2310|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2364'] = {name: 'Lockheed SR-71A Blackbird', dir: '|backend|aircraft|repository|B-1_241731_2364|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2386'] = {name: 'Boeing 787-9 Dreamliner', dir: '|backend|aircraft|repository|G8_166635_2386|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2395'] = {name: 'BAe 146-300/Avro RJ100', dir: '|backend|aircraft|repository|_310810_2395|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2418'] = {name: 'ATR 72-600 (HOP!)', dir: '|backend|aircraft|repository|New P-Series_267286_2418|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2420'] = {name: 'ATR 72-600 (Silver)', dir: '|backend|aircraft|repository|ATR 72-600 (SAS)_267286_2420|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2426'] = {name: 'ATR 72-600 (UTair)', dir: '|backend|aircraft|repository|ATR 72-500 (UTair)_267286_2426|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2461'] = {name: 'Cirrus Vision Jet/SF50 G2', dir: '|backend|aircraft|repository|GA-1_310810_2461|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2556'] = {name: 'Northrop Grumman B-2 Spirit', dir: '|backend|aircraft|repository|_260077_2556|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2581'] = {name: 'F-14B Tomcat ', dir: '|backend|aircraft|repository|MA-2_310810_2581|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2700'] = {name: 'Embraer ERJ-195AR (Breeze)', dir: '|backend|aircraft|repository|_228942_2700|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2706'] = {name: 'Bombardier CRJ 200', dir: '|backend|aircraft|repository|Bomabardier CRJ 200_388316_2706|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2726'] = {name: 'Scaled 339 \"SpaceShipTwo\"', dir: '|backend|aircraft|repository|P140_267286_2726|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2750'] = {name: 'Caproni Stipa', dir: '|backend|aircraft|repository|Caproni Stipa_358831_2750|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2752'] = {name: 'Scaled 348 \"WhiteKnightTwo\"', dir: '|backend|aircraft|repository|P141_267286_2752|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2769'] = {name: 'Boeing 737 Max 8 (TUI)', dir: '|backend|aircraft|repository|EL AL 737-900_427352_2769|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2772'] = {name: 'Boeing 737 Max 8 (SpiceJet)', dir: '|backend|aircraft|repository|SpiceJet 737-900_427352_2772|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2786'] = {name: 'Grumman JF2-5 Duck', dir: '|backend|aircraft|repository|starship_358831_2786|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2788'] = {name: 'Antonov An-225 Mriya', dir: '|backend|aircraft|repository|An-225 2.0_260077_2788|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2806'] = {name: 'Sikorsky S-97 Raider', dir: '|backend|aircraft|repository|M150V_267286_2806|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2808'] = {name: 'Supermarine Spitfire Mk XIV', dir: '|backend|aircraft|repository|HA-1_310810_2808|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2840'] = {name: 'Bell UH-1H Iroquois', dir: '|backend|aircraft|repository|UH-1D_286491_2840|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2843'] = {name: 'Airbus A220-300 (Air Tanzania)', dir: '|backend|aircraft|repository|a220-300_230250_2843|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2844'] = {name: 'Falcon 9', dir: '|backend|aircraft|repository|Falcon 9_358831_2844|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2852'] = {name: 'Cameron R-650 Rozière Balloon', dir: '|backend|aircraft|repository|A140_267286_2852|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2856'] = {name: 'Airbus a330-200', dir: '|backend|aircraft|repository|Airbus A400M Atlas_388316_2856|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2857'] = {name: 'F-22 Raptor', dir: '|backend|aircraft|repository|F22 Test_285706_2857|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2864'] = {name: 'AgustaWestland AW609', dir: '|backend|aircraft|repository|M200V_267286_2864|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2865'] = {name: 'Airbus a320neo(Air India)', dir: '|backend|aircraft|repository|airbus a320-214 (Indigo)_427352_2865|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2870'] = {name: 'Airbus a320neo (Flynas)', dir: '|backend|aircraft|repository|airbus a320-214 (Eurowings)_427352_2870|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2871'] = {name: 'Airbus a320neo (Iberia)', dir: '|backend|aircraft|repository|airbus a320-214 (Easyjet)_427352_2871|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2878'] = {name: 'Airbus A319 (Air China)', dir: '|backend|aircraft|repository|Saudi Airbus A319_230250_2878|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2879'] = {name: 'Airbus A319 (Finnair) ', dir: '|backend|aircraft|repository|Philpians a319_230250_2879|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2892'] = {name: 'SAAB 340', dir: '|backend|aircraft|repository|SAAB 340_427352_2892|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2899'] = {name: 'Airbus A220-300 (Swiss)', dir: '|backend|aircraft|repository|Air Baltic  A220_230250_2899|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2943'] = {name: 'Embraer EMB120 Brasillia ', dir: '|backend|aircraft|repository|AW609_230250_2943|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2948'] = {name: '(JAaMDG) North American XB-70 Valkyrie', dir: '|backend|aircraft|repository|(JAaMDG) North American XB-70 Valkyrie_321805_2948|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2951'] = {name: 'Airbus a340-300', dir: '|backend|aircraft|repository|Dassault nEUROn UCAV_388316_2951|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2953'] = {name: 'Space Shuttle Atlantis (OV-104)', dir: '|backend|aircraft|repository|P180_267286_2953|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2968'] = {name: 'Windward Performance Perlan II', dir: '|backend|aircraft|repository|A150_267286_2968|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2973'] = {name: 'Airbus A350-1000 XWB', dir: '|backend|aircraft|repository|_260077_2973|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2976'] = {name: 'Pilatus PC12', dir: '|backend|aircraft|repository|Pilatus PC12_230250_2976|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2988'] = {name: '(TBSG, GeoAD) North American X-15', dir: '|backend|aircraft|repository|(TBSG, GeoAD) North American X-15_321805_2988|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['2989'] = {name: 'MQ9B Reaper', dir: '|backend|aircraft|repository|MQ9B Reaper_388316_2989|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3011'] = {name: 'Boeing 737 Max 8 (Norwegian)', dir: '|backend|aircraft|repository|737max_427352_3011|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3036'] = {name: 'Embraer E195-E2', dir: '|backend|aircraft|repository|Binter E195-E2_230250_3036|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3049'] = {name: 'Lockheed Martin P-791 (LMH-1)', dir: '|backend|aircraft|repository|P200_267286_3049|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3054'] = {name: 'Boeing 737-800 [Spice9]', dir: '|backend|aircraft|repository|Boeing 737Max 8 (TUI)_427352_3054|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3109'] = {name: 'Pilatus PC24', dir: '|backend|aircraft|repository|PC24_230250_3109|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3140'] = {name: 'Airbus A319 (United)', dir: '|backend|aircraft|repository|Lufthansa A319-111_230250_3140|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3179'] = {name: 'Boeing 787-10 Dreamliner (British Airways)', dir: '|backend|aircraft|repository|Boeing 787-10 Dreamliner (British Airways)_427352_3179|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3180'] = {name: 'Boeing 787-10 Dreamliner (Etihad)', dir: '|backend|aircraft|repository|Boeing 787-10 Dreamliner (Etihad)_427352_3180|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3211'] = {name: 'UTVA75', dir: '|backend|aircraft|repository|Air France A220_230250_3211|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3289'] = {name: 'Dornier 228-200', dir: '|backend|aircraft|repository|HAL-Dornier 228-100_427352_3289|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3292'] = {name: 'Boeing p8I Neptune', dir: '|backend|aircraft|repository|Boeing p8I Neptune_427352_3292|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3307'] = {name: 'Bombardier CRJ-700', dir: '|backend|aircraft|repository|CRJ-700_450602_3307|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3341'] = {name: 'Embraer ERJ-170', dir: '|backend|aircraft|repository|ERJ-170 2_450602_3341|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3436'] = {name: 'Dornier do228-100 (Coast Gaurd)', dir: '|backend|aircraft|repository|a3test_427352_3436|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3460'] = {name: 'Grumman E-2C Hawkeye', dir: '|backend|aircraft|repository|Grumman E-2 Hawkeye_286491_3460|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3534'] = {name: 'airbus a320-214(Easyjet)', dir: '|backend|aircraft|repository|airbus a320-214(Sri Lankan)_427352_3534|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3575'] = {name: ' Boeing 787-9[Spice9]', dir: '|backend|aircraft|repository|Boeing 787-10 Dreamliner (ANA)_427352_3575|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3591'] = {name: 'F-15C Eagle', dir: '|backend|aircraft|repository|F-15C_450602_3591|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['3617'] = {name: 'Dassault Mirage 2000-5', dir: '|backend|aircraft|repository|Dassault Mirage 2000-5_286491_3617|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4017'] = {name: 'Embraer ERJ145LR (by Spice 9) &', dir: '|backend|aircraft|repository|ERJ145AR_230250_4017|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4090'] = {name: 'Robinson R-44', dir: '|backend|aircraft|repository|Robinson R44_402407_4090|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4140'] = {name: 'Boeing 737-200', dir: '|backend|aircraft|repository|737-200_450602_4140|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4197'] = {name: 'Robinson R22', dir: '|backend|aircraft|repository|Robinson R22_402407_4197|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4251'] = {name: 'Chance Vought F4U-1D Corsair', dir: '|backend|aircraft|repository|M125_267286_4251|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4341'] = {name: 'Spirit of St louis', dir: '|backend|aircraft|repository|Spirit of St louis_358831_4341|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4390'] = {name: 'Piper PA-28 Floatplane', dir: '|backend|aircraft|repository|_365507_4390|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4398'] = {name: 'Britten-Norman BN-2 Islander (Loganair)', dir: '|backend|aircraft|repository|_365507_4398|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4401'] = {name: 'Britten-Norman BN-2 Islander (St. Barth Commuter)', dir: '|backend|aircraft|repository|_365507_4401|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4402'] = {name: 'Boeing 777 Freighter', dir: '|backend|aircraft|repository|G9_166635_4402|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4409'] = {name: 'Zenith Stol CH701', dir: '|backend|aircraft|repository|_365507_4409|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4596'] = {name: 'Vans RV6', dir: '|backend|aircraft|repository|_365507_4596|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4631'] = {name: 'Airbus A330-900neo (Virgin Atlantic)', dir: '|backend|aircraft|repository|a33x backup_230250_4631|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4646'] = {name: 'Airbus a321neo (spice9)', dir: '|backend|aircraft|repository|a320 2023_427352_4646|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4743'] = {name: 'Boeing 757-300', dir: '|backend|aircraft|repository|757-300_230250_4743|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4745'] = {name: 'Boeing 757-300wl', dir: '|backend|aircraft|repository|Beoing 757-300wl_230250_4745|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4764'] = {name: 'Boeing 767-400', dir: '|backend|aircraft|repository|Boeing 767-400_230250_4764|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['4949'] = {name: 'Goodyear Blimp', dir: '|backend|aircraft|repository|_241731_4949|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5038'] = {name: 'Lockheed L-1011-1', dir: '|backend|aircraft|repository|Lockheed L-1011-1_450602_5038|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5061'] = {name: 'Sonex-B Kit (Jabiru 3300)', dir: '|backend|aircraft|repository|Sonex-B Kit_945960_5061|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5073'] = {name: 'Bombardier Learjet 45 XR', dir: '|backend|aircraft|repository|Bombardier Learjet 45 XR_427352_5073|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5086'] = {name: 'Airbus a321-211 ', dir: '|backend|aircraft|repository|Airbus a321-211 _427352_5086|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5156'] = {name: 'Airbus a318-112 by Luca &', dir: '|backend|aircraft|repository|Airbus a318-112 by Luca &_427352_5156|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5193'] = {name: 'Boeing 747-8i', dir: '|backend|aircraft|repository|P170_267286_5193|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5203'] = {name: 'Boeing 737-600 by Luca &', dir: '|backend|aircraft|repository|Boeing 737-600_427352_5203|', 'multiplayerFiles': '', 'community': 1};geofs.aircraftList['5229'] = {name: 'F-35B Lightning II', dir: '|backend|aircraft|repository|M135_267286_5229|', 'multiplayerFiles': '', 'community': 1};
</script>

<ul class="geofs-list geofs-toggle-panel geofs-aircraft-list">

    <li class="geofs-list-collapsible-item geofs-notstudent-role">Community contributed<ul class="geofs-collapsible"><li data-aircraft="3575"> Boeing 787-9[Spice9] (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.7051048368794015" tabindex="0"><div class="mdl-tooltip undefined" for="0.7051048368794015" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.8832502047349515" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.8832502047349515" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2948">(JAaMDG) North American XB-70 Valkyrie (by Johani_(NeoAD))</li><li data-aircraft="2988">(TBSG, GeoAD) North American X-15 (by Johani_(NeoAD))</li><li data-aircraft="2310">A-10C Thunderbolt II (by Eco[LAC])</li><li data-aircraft="2864">AgustaWestland AW609 (by JAaMDG)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.40087642521133837" tabindex="0"><div class="mdl-tooltip undefined" for="0.40087642521133837" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.732277780752534" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.732277780752534" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2843">Airbus A220-300 (Air Tanzania) (by GT-VRA)</li><li data-aircraft="2899">Airbus A220-300 (Swiss) (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.3378172570701836" tabindex="0"><div class="mdl-tooltip undefined" for="0.3378172570701836" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="5156">Airbus a318-112 by Luca &amp; (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.024919738725502016" tabindex="0"><div class="mdl-tooltip undefined" for="0.024919738725502016" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.3560371451303215" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.3560371451303215" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2878">Airbus A319 (Air China) (by GT-VRA)</li><li data-aircraft="2879">Airbus A319 (Finnair)  (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.0787949904036358" tabindex="0"><div class="mdl-tooltip undefined" for="0.0787949904036358" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="3140">Airbus A319 (United) (by GT-VRA)</li><li data-aircraft="3534">airbus a320-214(Easyjet) (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.023516450564127656" tabindex="0"><div class="mdl-tooltip undefined" for="0.023516450564127656" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.6751696760641608" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.6751696760641608" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2870">Airbus a320neo (Flynas) (by Spice_9)</li><li data-aircraft="2871">Airbus a320neo (Iberia) (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.02890785676586871" tabindex="0"><div class="mdl-tooltip undefined" for="0.02890785676586871" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.45692668821739524" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.45692668821739524" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2865">Airbus a320neo(Air India) (by Spice_9)</li><li data-aircraft="5086">Airbus a321-211  (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5359534000374477" tabindex="0"><div class="mdl-tooltip undefined" for="0.5359534000374477" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7643275551520143" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7643275551520143" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="242">Airbus A321neo (by LRX)</li><li data-aircraft="4646">Airbus a321neo (spice9) (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.4328725507045641" tabindex="0"><div class="mdl-tooltip undefined" for="0.4328725507045641" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.35908340969571007" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.35908340969571007" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2856">Airbus a330-200 (by Aero281)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8160858032474243" tabindex="0"><div class="mdl-tooltip undefined" for="0.8160858032474243" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.2545267092917811" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.2545267092917811" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="244">Airbus A330-300 (by LRX)</li><li data-aircraft="4631">Airbus A330-900neo (Virgin Atlantic) (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.972281147328349" tabindex="0"><div class="mdl-tooltip undefined" for="0.972281147328349" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="2951">Airbus a340-300 (by Aero281)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.10794170313885476" tabindex="0"><div class="mdl-tooltip undefined" for="0.10794170313885476" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.8831976658479177" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.8831976658479177" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2153">Airbus A340-600 (by LRX)</li><li data-aircraft="2973">Airbus A350-1000 XWB (by NS-Studios)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8284439061239224" tabindex="0"><div class="mdl-tooltip undefined" for="0.8284439061239224" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.2612879820772456" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.2612879820772456" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="239">Airbus A350-900 (by GX Development)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.22125371467607025" tabindex="0"><div class="mdl-tooltip undefined" for="0.22125371467607025" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="2788">Antonov An-225 Mriya (by NS-Studios)</li><li data-aircraft="2418">ATR 72-600 (HOP!) (by JAaMDG)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.953425592896334" tabindex="0"><div class="mdl-tooltip undefined" for="0.953425592896334" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7023523447471465" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7023523447471465" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2420">ATR 72-600 (Silver) (by JAaMDG)</li><li data-aircraft="2426">ATR 72-600 (UTair) (by JAaMDG)</li><li data-aircraft="2395">BAe 146-300/Avro RJ100 (by Eco[LAC])</li><li data-aircraft="2840">Bell UH-1H Iroquois (by ElonMusk(VrA)(LAC))</li><li data-aircraft="3011">Boeing 737 Max 8 (Norwegian) (by Spice_9)</li><li data-aircraft="2772">Boeing 737 Max 8 (SpiceJet) (by Spice_9)</li><li data-aircraft="2769">Boeing 737 Max 8 (TUI) (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.061594758230744784" tabindex="0"><div class="mdl-tooltip undefined" for="0.061594758230744784" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.28888117800979884" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.28888117800979884" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4140">Boeing 737-200 (by AriakimTaiyo)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.02712431585141628" tabindex="0"><div class="mdl-tooltip undefined" for="0.02712431585141628" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.28236496788434007" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.28236496788434007" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="5203">Boeing 737-600 by Luca &amp; (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.68210624165323" tabindex="0"><div class="mdl-tooltip undefined" for="0.68210624165323" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.2447328383299039" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.2447328383299039" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2003">Boeing 737-800 (by King  Solomon)</li><li data-aircraft="3054">Boeing 737-800 [Spice9] (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6474190007525353" tabindex="0"><div class="mdl-tooltip undefined" for="0.6474190007525353" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.835828579444061" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.835828579444061" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="252">Boeing 747-8 Freighter (by LRX)</li><li data-aircraft="5193">Boeing 747-8i (by JAaMDG)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5639666170568001" tabindex="0"><div class="mdl-tooltip undefined" for="0.5639666170568001" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.11807124113153833" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.11807124113153833" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="238">Boeing 757-200 (by GX Development)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5669275668835381" tabindex="0"><div class="mdl-tooltip undefined" for="0.5669275668835381" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.04362636999688729" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.04362636999688729" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4743">Boeing 757-300 (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.17187246026636638" tabindex="0"><div class="mdl-tooltip undefined" for="0.17187246026636638" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.6777239505528105" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.6777239505528105" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4745">Boeing 757-300wl (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.31089112585738476" tabindex="0"><div class="mdl-tooltip undefined" for="0.31089112585738476" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.9263343884630326" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.9263343884630326" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="237">Boeing 767-300ER (by GX Development)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6036802792083662" tabindex="0"><div class="mdl-tooltip undefined" for="0.6036802792083662" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.41616369651277996" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.41616369651277996" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4764">Boeing 767-400 (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.14495406537153577" tabindex="0"><div class="mdl-tooltip undefined" for="0.14495406537153577" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="4402">Boeing 777 Freighter (by LRX)</li><li data-aircraft="240">Boeing 777-300ER (by LRX)</li><li data-aircraft="3179">Boeing 787-10 Dreamliner (British Airways) (by Spice_9)</li><li data-aircraft="3180">Boeing 787-10 Dreamliner (Etihad) (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.09292141737311166" tabindex="0"><div class="mdl-tooltip undefined" for="0.09292141737311166" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.37643925219217644" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.37643925219217644" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="235">Boeing 787-8 (by GX Development)</li><li data-aircraft="2386">Boeing 787-9 Dreamliner (by LRX)</li><li data-aircraft="3292">Boeing p8I Neptune (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.41814946524057395" tabindex="0"><div class="mdl-tooltip undefined" for="0.41814946524057395" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="2706">Bombardier CRJ 200 (by Aero281)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.439991800656784" tabindex="0"><div class="mdl-tooltip undefined" for="0.439991800656784" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="3307">Bombardier CRJ-700 (by AriakimTaiyo)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.9369640296577637" tabindex="0"><div class="mdl-tooltip undefined" for="0.9369640296577637" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.5983213215737002" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.5983213215737002" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="247">Bombardier Dash 8 Q400 (by LRX)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6874531326095552" tabindex="0"><div class="mdl-tooltip undefined" for="0.6874531326095552" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.26671355337059377" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.26671355337059377" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="5073">Bombardier Learjet 45 XR (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.2189090045606379" tabindex="0"><div class="mdl-tooltip undefined" for="0.2189090045606379" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="4398">Britten-Norman BN-2 Islander (Loganair) (by coolpilot11)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.7222141943312073" tabindex="0"><div class="mdl-tooltip undefined" for="0.7222141943312073" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7484808263641016" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7484808263641016" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4401">Britten-Norman BN-2 Islander (St. Barth Commuter) (by coolpilot11)</li><li data-aircraft="2852">Cameron R-650 Rozière Balloon (by JAaMDG)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.7300488639649465" tabindex="0"><div class="mdl-tooltip undefined" for="0.7300488639649465" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.11729337065294221" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.11729337065294221" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2750">Caproni Stipa (by Echo_3)</li><li data-aircraft="4251">Chance Vought F4U-1D Corsair (by JAaMDG)</li><li data-aircraft="1069">Cirrus SR22 GTS Turbo (by LRX)</li><li data-aircraft="2461">Cirrus Vision Jet/SF50 G2 (by Eco[LAC])</li><li data-aircraft="2004">CRJ-900 (by King  Solomon)</li><li data-aircraft="3617">Dassault Mirage 2000-5 (by ElonMusk(VrA)(LAC))</li><li data-aircraft="3289">Dornier 228-200 (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.001579242070238518" tabindex="0"><div class="mdl-tooltip undefined" for="0.001579242070238518" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="3436">Dornier do228-100 (Coast Gaurd) (by Spice_9)</li><li data-aircraft="236">Embraer E190 (by GX Development)</li><li data-aircraft="3036">Embraer E195-E2 (by GT-VRA)</li><li data-aircraft="2943">Embraer EMB120 Brasillia  (by GT-VRA)</li><li data-aircraft="3341">Embraer ERJ-170 (by AriakimTaiyo)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.7552320804523158" tabindex="0"><div class="mdl-tooltip undefined" for="0.7552320804523158" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="2700">Embraer ERJ-195AR (Breeze) (by Featherway)</li><li data-aircraft="4017">Embraer ERJ145LR (by Spice 9) &amp; (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.9268447367727362" tabindex="0"><div class="mdl-tooltip undefined" for="0.9268447367727362" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="2581">F-14B Tomcat  (by Eco[LAC])</li><li data-aircraft="3591">F-15C Eagle (by AriakimTaiyo)</li><li data-aircraft="2857">F-22 Raptor (by SpaceRage)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5861764820818864" tabindex="0"><div class="mdl-tooltip undefined" for="0.5861764820818864" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.38139487566012487" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.38139487566012487" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="5229">F-35B Lightning II (by JAaMDG)</li><li data-aircraft="2844">Falcon 9 (by Echo_3)</li><li data-aircraft="4949">Goodyear Blimp (by BritishPilot[GeoAD])</li><li data-aircraft="3460">Grumman E-2C Hawkeye (by ElonMusk(VrA)(LAC))</li><li data-aircraft="2786">Grumman JF2-5 Duck (by Echo_3)</li><li data-aircraft="5038">Lockheed L-1011-1 (by AriakimTaiyo)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8248535564731636" tabindex="0"><div class="mdl-tooltip undefined" for="0.8248535564731636" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.06637223179699192" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.06637223179699192" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="3049">Lockheed Martin P-791 (LMH-1) (by JAaMDG)</li><li data-aircraft="2364">Lockheed SR-71A Blackbird (by BritishPilot[GeoAD])</li><li data-aircraft="2989">MQ9B Reaper (by Aero281)</li><li data-aircraft="2556">Northrop Grumman B-2 Spirit (by NS-Studios)</li><li data-aircraft="2976">Pilatus PC12 (by GT-VRA)</li><li data-aircraft="3109">Pilatus PC24 (by GT-VRA)</li><li data-aircraft="4390">Piper PA-28 Floatplane (by coolpilot11)</li><li data-aircraft="4090">Robinson R-44 (by (CCDev)DevHunter77)</li><li data-aircraft="4197">Robinson R22 (by (CCDev)DevHunter77)</li><li data-aircraft="2892">SAAB 340 (by Spice_9)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8489675645283712" tabindex="0"><div class="mdl-tooltip undefined" for="0.8489675645283712" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.24453520364757586" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.24453520364757586" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2726">Scaled 339 "SpaceShipTwo" (by JAaMDG)</li><li data-aircraft="2752">Scaled 348 "WhiteKnightTwo" (by JAaMDG)</li><li data-aircraft="2806">Sikorsky S-97 Raider (by JAaMDG)</li><li data-aircraft="5061">Sonex-B Kit (Jabiru 3300) (by TurboMaximus)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.2835986238600541" tabindex="0"><div class="mdl-tooltip undefined" for="0.2835986238600541" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7782768836426381" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7782768836426381" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2953">Space Shuttle Atlantis (OV-104) (by JAaMDG)</li><li data-aircraft="4341">Spirit of St louis (by Echo_3)</li><li data-aircraft="2808">Supermarine Spitfire Mk XIV (by Eco[LAC])<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.16878934417272662" tabindex="0"><div class="mdl-tooltip undefined" for="0.16878934417272662" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.10482453874523245" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.10482453874523245" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="3211">UTVA75 (by GT-VRA)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5509324953490105" tabindex="0"><div class="mdl-tooltip undefined" for="0.5509324953490105" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.9929837481618871" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.9929837481618871" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="4596">Vans RV6 (by coolpilot11)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6446955009437092" tabindex="0"><div class="mdl-tooltip undefined" for="0.6446955009437092" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.12637501740548074" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.12637501740548074" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2968">Windward Performance Perlan II (by JAaMDG)</li><li data-aircraft="4409">Zenith Stol CH701 (by coolpilot11)</li></ul></li><li data-aircraft="1" class=""><img src="images/planes/cub.png">Piper Cub<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.14284522913133002" tabindex="0"><div class="mdl-tooltip undefined" for="0.14284522913133002" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.5437942221715755" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.5437942221715755" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="2" class=""><img src="images/planes/c172.png">Cessna 172<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.4884985474235608" tabindex="0"><div class="mdl-tooltip undefined" for="0.4884985474235608" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.6844102558932053" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.6844102558932053" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="3" class=""><img src="images/planes/alphajet.png">Alphajet PAF<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.27159507187860066" tabindex="0"><div class="mdl-tooltip undefined" for="0.27159507187860066" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="4" class=""><img src="images/planes/737-700.png">Boeing 737-700<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.23060426941509204" tabindex="0"><div class="mdl-tooltip undefined" for="0.23060426941509204" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.10227124608704963" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.10227124608704963" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="5" class=""><img src="images/planes/phenom.png">Embraer Phenom 100<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.1908154571425189" tabindex="0"><div class="mdl-tooltip undefined" for="0.1908154571425189" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="6" class=""><img src="images/planes/dhc6.png">de Havilland DHC6 Twin Otter<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6791462335598379" tabindex="0"><div class="mdl-tooltip undefined" for="0.6791462335598379" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="7" class=""><img src="images/planes/f16.png"> F-16 Fighting Falcon<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.045651625220348935" tabindex="0"><div class="mdl-tooltip undefined" for="0.045651625220348935" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.03470619701242761" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.03470619701242761" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="8" class=""><img src="images/planes/pitts.png">Pitts Special S1<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.086698661319488" tabindex="0"><div class="mdl-tooltip undefined" for="0.086698661319488" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.5630512903286231" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.5630512903286231" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="9" class=""><img src="images/planes/ec135.png">Eurocopter EC135<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8630866235594017" tabindex="0"><div class="mdl-tooltip undefined" for="0.8630866235594017" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.09666160699618831" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.09666160699618831" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="10" class=""><img src="images/planes/a380.png">Airbus A380<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5897568849464008" tabindex="0"><div class="mdl-tooltip undefined" for="0.5897568849464008" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.3067851964399362" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.3067851964399362" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="11" class=""><img src="images/planes/silent2.png">Alisport Silent 2 Electro</li><li data-aircraft="12" class=""><img src="images/planes/pilatus.png">Pilatus PC-7 Mk-I</li><li data-aircraft="13" class=""><img src="images/planes/dhc2.png">de Havilland Canada DHC-2 Beaver<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.06936774109145882" tabindex="0"><div class="mdl-tooltip undefined" for="0.06936774109145882" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.6945688643099885" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.6945688643099885" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="14" class=""><img src="images/planes/cricri.png">Colomban MC-15 Cri-cri<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.269591914982809" tabindex="0"><div class="mdl-tooltip undefined" for="0.269591914982809" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7441726076919575" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7441726076919575" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="15" class=""><img src="images/planes/p38.png">Lockheed P-38 Lightning F-5B<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.7303860492448293" tabindex="0"><div class="mdl-tooltip undefined" for="0.7303860492448293" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.7481392305317303" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.7481392305317303" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="16" class=""><img src="images/planes/dc3.png">Douglas DC-3<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.33031896592606635" tabindex="0"><div class="mdl-tooltip undefined" for="0.33031896592606635" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="18" class=""><img src="images/planes/su35.png">Sukhoi Su-35<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.6479268441166315" tabindex="0"><div class="mdl-tooltip undefined" for="0.6479268441166315" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.3621967648684139" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.3621967648684139" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="20" class=""><img src="images/planes/concorde.png">Concorde<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.2812796465148608" tabindex="0"><div class="mdl-tooltip undefined" for="0.2812796465148608" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.22573520869058084" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.22573520869058084" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="21" class=""><img src="images/planes/zlin.png">Zlin Z-50<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.2505756849090779" tabindex="0"><div class="mdl-tooltip undefined" for="0.2505756849090779" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.6122195596511024" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.6122195596511024" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="22" class=""><img src="images/planes/c152.png">Cessna 152<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.8833177381868873" tabindex="0"><div class="mdl-tooltip undefined" for="0.8833177381868873" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.8250521038095655" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.8250521038095655" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="23" class=""><img src="images/planes/pa28.png">Piper PA-28 161 Warrior II Aerobility<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.11889424150333916" tabindex="0"><div class="mdl-tooltip undefined" for="0.11889424150333916" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.269033853674548" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.269033853674548" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="24" class=""><img src="images/planes/a350.png">Airbus A350<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.017676874163788048" tabindex="0"><div class="mdl-tooltip undefined" for="0.017676874163788048" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.3269270751193405" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.3269270751193405" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="25" class=""><img src="images/planes/777-300.png">Boeing 777-300ER<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5397140303624663" tabindex="0"><div class="mdl-tooltip undefined" for="0.5397140303624663" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.9885862877496916" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.9885862877496916" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="26" class=""><img src="images/planes/an140.png">Antonov An-140<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.1014150897083399" tabindex="0"><div class="mdl-tooltip undefined" for="0.1014150897083399" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.36882647618529374" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.36882647618529374" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="27" class=""><img src="images/planes/fa18.png">Boeing F/A-18F Super Hornet<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.894687609090647" tabindex="0"><div class="mdl-tooltip undefined" for="0.894687609090647" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.05674656755578278" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.05674656755578278" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="31" class=""><img src="images/planes/potez25.png">Potez 25</li><li data-aircraft="40" class=""><img src="images/planes/sportstar.png">Evektor Sportstar</li><li data-aircraft="41" class=""><img src="images/planes/jantar.png">szd-48-3 Jantar<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5947384181426758" tabindex="0"><div class="mdl-tooltip undefined" for="0.5947384181426758" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="50" class=""><img src="images/planes/paraglider.png">Paraglider</li><li data-aircraft="51" class=""><img src="images/planes/tom.png">Major Tom (hot air balloon)<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.3611956586558829" tabindex="0"><div class="mdl-tooltip undefined" for="0.3611956586558829" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.5374956492717464" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.5374956492717464" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="52" class=""><img src="images/planes/hughes.png">Hughes 269a/TH-55 Osage<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.00325391685206311" tabindex="0"><div class="mdl-tooltip undefined" for="0.00325391685206311" data-upgraded=",MaterialTooltip">Liveries available</div></li><li data-aircraft="53" class=""><img src="images/planes/goat.png">Goat Airchair</li><li data-aircraft="102" class=""><img src="images/planes/2cv.png">Citroen 2CV<img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" style="height:30px;width:auto;margin-left:20px;" id="0.5749411705827727" tabindex="0"><div class="mdl-tooltip undefined" for="0.5749411705827727" data-upgraded=",MaterialTooltip">Liveries available</div><small id="0.21869965085100085" tabindex="0">🎮</small><div class="mdl-tooltip undefined" for="0.21869965085100085" data-upgraded=",MaterialTooltip">Liveries are multiplayer compatible
(visible to other players)</div></li><li data-aircraft="103" class=""><img src="images/planes/wingsuit.png">Wingsuit</li></ul>

<script>
    // de-obfuscate path so Googlebot does not crawl and follow therese as links
    for (var i in geofs.aircraftList) {
        geofs.aircraftList[i].path = geofs.aircraftList[i].dir.replace(/\|/gi, '/');
    }
</script>
        <ul class="geofs-list geofs-toggle-panel geofs-player-list geofs-authenticated" data-onshow="{ui.initPlayerList()}" data-onhide="{ui.clearPlayerList()}"></ul>

        <div class="geofs-hd-list geofs-toggle-panel geofs-onlyForApp" data-parentwidth="100%" data-noblur="true">
            <div class="geofs-payment-view"></div>
        </div>

        <!-- Navigation panel -->
        <div class="geofs-map-list geofs-toggle-panel" data-parentzindex="40" data-onshow="{ui.openMap()}" data-onhide="{ui.closeMap()}" data-noblur="true">
            <label style="position: absolute; bottom: 50px; left: 60px;" class="mdl-switch mdl-js-switch mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events is-upgraded" for="centerMap" id="0.11755896826510503" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
		<input type="checkbox" id="centerMap" class="mdl-switch__input" data-gespref="geofs.preferences.interface.recenterMap" data-update="{geofs.savePreferences()}">
                <span class="mdl-switch__label">Recenter</span>
            <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.11755896826510503" data-upgraded=",MaterialTooltip">Automatically recenter map</div>
            <label style="position: absolute; bottom: 10px; left: 60px;" class="mdl-switch mdl-js-switch mdl-js-ripple-effect is-checked mdl-js-ripple-effect--ignore-events is-upgraded" for="drawFlightPath" id="0.3768770095947933" tabindex="0" data-upgraded=",MaterialSwitch,MaterialRipple">
                <input type="checkbox" id="drawFlightPath" class="mdl-switch__input" data-gespref="geofs.preferences.interface.drawFlightPath" data-update="{flight.recorder.setPathDrawState()}">
                <span class="mdl-switch__label">Show path</span>
            <div class="mdl-switch__track"></div><div class="mdl-switch__thumb"><span class="mdl-switch__focus-helper"></span></div><span class="mdl-switch__ripple-container mdl-js-ripple-effect mdl-ripple--center" data-upgraded=",MaterialRipple"><span class="mdl-ripple"></span></span></label><div class="mdl-tooltip undefined" for="0.3768770095947933" data-upgraded=",MaterialTooltip">Show recorded flight path</div>
            <div class="geofs-flightPlan-pad control-pad" onclick="geofs.flightPlan.toggle();" id="0.5407391730960003" tabindex="0">
                <div class="control-pad-label transp-pad">FLIGHT PLAN</div>
            </div><div class="mdl-tooltip undefined" for="0.5407391730960003" data-upgraded=",MaterialTooltip">Open flight plan planel</div>
            <div class="control-pad geofs-flightPlan geofs-stopKeyboardPropagation geofs-stopKeyupPropagation">
                <div class="geofs-flightPlanHeader">
                    <span>WPT</span><span style="text-align: right;">DST</span><span style="text-align: right;">TRK</span><span>ALT</span><span>SPD</span>
                    <button class="mdl-button mdl-js-button mdl-button--icon" style="float: right;" id="0.029305926331303134" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons" onclick="geofs.flightPlan.clear();">delete</i></button><div class="mdl-tooltip undefined" for="0.029305926331303134" data-upgraded=",MaterialTooltip">Clear Flight Plan</div>
                    <span class="flightPlanDistance" style="float: right;" id="0.9257292007417135" tabindex="0"></span><div class="mdl-tooltip undefined" for="0.9257292007417135" data-upgraded=",MaterialTooltip">Distance to Destination</div>
                </div>
                <div class="geofs-flightPlanList"></div>
                <div class="geofs-addWaypoint control-pad" id="flightPlanWaypoint">
                    <div class="mdl-textfield mdl-js-textfield is-upgraded" style="width: 280px;" data-upgraded=",MaterialTextfield">
                        <input class="mdl-textfield__input geofs-addWaypointInput" type="text" id="addWaypoint" onchange="geofs.flightPlan.searchWaypoint(this);">
                        <label class="mdl-textfield__label" for="addWaypoint">FIX - WAYPOINT - ICAO - LAT,LON</label>
                    </div>
                    <div class="geofs-addWaypointButton control-pad control-pad-label" onclick="geofs.flightPlan.searchWaypoint(this);">
                        <i class="material-icons" style="position: absolute; left: 1px; top: 1px;">add_circle</i> Add waypoint
                    </div>
                    <button class="mdl-button mdl-js-button mdl-button--icon geofs-flightplanAction" onclick="geofs.flightPlan.paste();" id="0.7234367515471989" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">content_paste</i></button><div class="mdl-tooltip undefined" for="0.7234367515471989" data-upgraded=",MaterialTooltip">Paste flightplan from clipboard</div>
                    <button class="mdl-button mdl-js-button mdl-button--icon geofs-flightplanAction" onclick="geofs.flightPlan.copy();" id="0.5660687410972622" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">content_copy</i></button><div class="mdl-tooltip undefined" for="0.5660687410972622" data-upgraded=",MaterialTooltip">Copy flightplan to clipboard</div>
                    <label class="mdl-button mdl-js-button mdl-button--icon geofs-flightplanAction" for="planfileupload" id="0.7362060051767456" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">folder_open</i></label><div class="mdl-tooltip undefined" for="0.7362060051767456" data-upgraded=",MaterialTooltip">Open flightplan file (JSON)</div><input type="file" id="planfileupload" style="display: none;" onchange="geofs.flightPlan.upload(this);">
                    <a class="mdl-button mdl-js-button mdl-button--icon geofs-flightplanAction" onclick="geofs.flightPlan.download(this);" id="0.42040351359463757" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">save</i></a><div class="mdl-tooltip undefined" for="0.42040351359463757" data-upgraded=",MaterialTooltip">Save flightplan locally</div>
                    <a class="geofs-flightplanAction simBriefImportButton" onclick="geofs.flightPlan.importSimBrief();" id="0.7994470723216727" tabindex="0"><img src="/images/simbriefbutton.png" style="width: 22px"></a><div class="mdl-tooltip undefined" for="0.7994470723216727" data-upgraded=",MaterialTooltip">Import SimBrief Flight Plan</div>
                </div>
            </div>
            <div class="geofs-map-viewport geofs-stopMousePropagation leaflet-container leaflet-touch leaflet-fade-anim leaflet-grab leaflet-touch-drag leaflet-touch-zoom" tabindex="0"><div class="leaflet-pane leaflet-map-pane" style="transform: translate3d(0px, 0px, 0px);"><div class="leaflet-pane leaflet-tile-pane"><div class="leaflet-layer " style="z-index: 1; opacity: 1;"><div class="leaflet-tile-container leaflet-zoom-animated" style="z-index: 18; transform: translate3d(0px, 0px, 0px) scale(1);"><img alt="" src="https://data.geo-fs.com/osm/10/511/511.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-256px, -256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/512/511.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(0px, -256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/511/512.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-256px, 0px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/512/512.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(0px, 0px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/511/510.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-256px, -512px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/512/510.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(0px, -512px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/510/511.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-512px, -256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/513/511.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(256px, -256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/510/512.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-512px, 0px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/513/512.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(256px, 0px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/511/513.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-256px, 256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/512/513.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(0px, 256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/510/510.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-512px, -512px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/513/510.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(256px, -512px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/510/513.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(-512px, 256px, 0px); opacity: 1;"><img alt="" src="https://data.geo-fs.com/osm/10/513/513.png" class="leaflet-tile leaflet-tile-loaded" style="width: 256px; height: 256px; transform: translate3d(256px, 256px, 0px); opacity: 1;"></div></div></div><div class="leaflet-pane leaflet-overlay-pane" style="opacity: 0.7;"><canvas class="leaflet-zoom-animated" width="0" height="0" style="transform: translate3d(0px, 0px, 0px); width: 0px; height: 0px;"></canvas></div><div class="leaflet-pane leaflet-shadow-pane leaflet-zoom-hide"></div><div class="leaflet-pane leaflet-marker-pane leaflet-zoom-hide"><img src="https://www.geo-fs.com/images/map/icons/yellow.png" class="leaflet-marker-icon geofs-myself-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -20px; margin-top: -20px; width: 40px; height: 40px; transform: translate3d(42451px, -17700px, 0px) rotate(-94.9917deg); z-index: -16700;"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(95453px, 19061px, 0px) rotate(225.23deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(21985px, -32743px, 0px) rotate(110.2deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-115074px, -16031px, 0px) rotate(130.78deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-102322px, -43157px, 0px) rotate(312deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(47208px, -19029px, 0px) rotate(312.77deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(56083px, -21752px, 0px) rotate(325.35deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-86201px, -26518px, 0px) rotate(359.2deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(35315px, -30543px, 0px) rotate(243.66deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-58474px, -19457px, 0px) rotate(80.06deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(84271px, -16758px, 0px) rotate(83.37deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(71995px, -3935px, 0px) rotate(308.49deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(95109px, -24290px, 0px) rotate(284.03deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-2022px, -38224px, 0px) rotate(209.41deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(25309px, -51394px, 0px) rotate(132.48deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(7571px, -35436px, 0px) rotate(37.54deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-313px, -43957px, 0px) rotate(15.3deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(9994px, -45074px, 0px) rotate(81deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(77262px, -3286px, 0px) rotate(214deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(2568px, -32403px, 0px) rotate(89.98deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(78818px, -836px, 0px) rotate(316.92deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(7537px, -34540px, 0px) rotate(151.39deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(154px, -32695px, 0px) rotate(80.25deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-58560px, -33150px, 0px) rotate(197.37deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(27204px, 2233px, 0px) rotate(156.48deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(96353px, 10551px, 0px) rotate(291deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(114038px, -5804px, 0px) rotate(275deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-58090px, 2752px, 0px) rotate(166.92deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(58272px, -10863px, 0px) rotate(350.77deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1767px, -41013px, 0px) rotate(343.85deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-53037px, -131072px, 0px) rotate(300.97deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31207px, 16925px, 0px) rotate(70.54deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1900px, -41045px, 0px) rotate(259.36deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1498px, -41052px, 0px) rotate(281.14deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-88714px, -31475px, 0px) rotate(207.84deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(22298px, 18431px, 0px) rotate(167.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(33767px, -5854px, 0px) rotate(169.02deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-45951px, -13372px, 0px) rotate(251.21deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(53813px, -13619px, 0px) rotate(126.16deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5234px, -35487px, 0px) rotate(20.15deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5298px, -42228px, 0px) rotate(147deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-88004px, -26346px, 0px) rotate(289.53deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51920px, -19701px, 0px) rotate(170.92deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6636px, -38096px, 0px) rotate(166.77deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(13715px, -30184px, 0px) rotate(90.38deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1738px, -40852px, 0px) rotate(321.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(23181px, -52270px, 0px) rotate(338.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(12635px, -52667px, 0px) rotate(100deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5265px, -35412px, 0px) rotate(309.37deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(101003px, -26936px, 0px) rotate(97deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-32812px, 14543px, 0px) rotate(104.16deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(100610px, -26967px, 0px) rotate(258.81deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(4932px, -51873px, 0px) rotate(259.42deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-3968px, -28634px, 0px) rotate(159.5deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5267px, -35408px, 0px) rotate(161.33deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1894px, -41044px, 0px) rotate(92.69deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(2056px, -41467px, 0px) rotate(29.34deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1699px, -40897px, 0px) rotate(276.18deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-114px, -31615px, 0px) rotate(208.66deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(26123px, -35494px, 0px) rotate(93.81deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1633px, -33415px, 0px) rotate(209.78deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-89120px, -29609px, 0px) rotate(118.16deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-53752px, -32449px, 0px) rotate(120.48deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(26924px, 874px, 0px) rotate(59.31deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-41px, -43900px, 0px) rotate(270.58deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-88405px, -39530px, 0px) rotate(93.69deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-386px, -43920px, 0px) rotate(292.91deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(55211px, -20288px, 0px) rotate(314.1deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-334px, -43864px, 0px) rotate(178.14deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(4230px, -32600px, 0px) rotate(304.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(77377px, -21852px, 0px) rotate(180.26deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(101804px, -27720px, 0px) rotate(165.04deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(101003px, -26936px, 0px) rotate(97.95deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-58407px, -19426px, 0px) rotate(249.3deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(102242px, -28931px, 0px) rotate(312.61deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(27689px, -33241px, 0px) rotate(78.96deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-86219px, -26301px, 0px) rotate(86.31deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(837px, -35035px, 0px) rotate(203.2deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(87804px, -11858px, 0px) rotate(174.55deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(3713px, -37722px, 0px) rotate(150.58deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31511px, 17084px, 0px) rotate(249.85deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(56146px, -21698px, 0px) rotate(278.31deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-114702px, -15894px, 0px) rotate(93.54deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(21282px, -32660px, 0px) rotate(244.35deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(81249px, -14473px, 0px) rotate(69.01deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31498px, 17066px, 0px) rotate(64.79deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5067px, -37870px, 0px) rotate(36.25deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-2594px, -32373px, 0px) rotate(180.64deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51973px, -33819px, 0px) rotate(222.56deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(80485px, -18591px, 0px) rotate(225.76deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(72620px, -27194px, 0px) rotate(150.53deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6941px, -40771px, 0px) rotate(73.02deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-71158px, -28439px, 0px) rotate(124.57deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(82919px, -16855px, 0px) rotate(99.42deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(80036px, -23852px, 0px) rotate(234.95deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51722px, -34073px, 0px) rotate(321.8deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(56146px, -21718px, 0px) rotate(287.92deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-89282px, -29763px, 0px) rotate(173.67deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(40839px, -19123px, 0px) rotate(130.24deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51723px, -34100px, 0px) rotate(224.96deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(84891px, -31861px, 0px) rotate(353.08deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(110080px, 26304px, 0px) rotate(358.17deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-89060px, -29642px, 0px) rotate(60.82deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-89094px, -29595px, 0px) rotate(119.22deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5263px, -35414px, 0px) rotate(224.84deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-88892px, -29461px, 0px) rotate(157.8deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(21878px, -35523px, 0px) rotate(301.74deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6758px, -37646px, 0px) rotate(72.98deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51439px, -34310px, 0px) rotate(24.88deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31453px, 17119px, 0px) rotate(131.88deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-224px, -43412px, 0px) rotate(249.46deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(24599px, 10205px, 0px) rotate(1.07deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-88477px, -29238px, 0px) rotate(305.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(80667px, -18286px, 0px) rotate(153deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1789px, -40935px, 0px) rotate(156.41deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-56535px, -18115px, 0px) rotate(337.22deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6393px, -40416px, 0px) rotate(100deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(53077px, -14144px, 0px) rotate(221.58deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31488px, 17079px, 0px) rotate(117.38deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(29088px, -35191px, 0px) rotate(101.56deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(20152px, -29265px, 0px) rotate(279.18deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(84895px, -31853px, 0px) rotate(165.49deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(187px, -43547px, 0px) rotate(78.11deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-53858px, -32570px, 0px) rotate(35.49deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-31504px, 17069px, 0px) rotate(115.77deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1745px, -40974px, 0px) rotate(71.28deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-51514px, -33427px, 0px) rotate(180.01deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6945px, -40773px, 0px) rotate(73.03deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-86237px, -26309px, 0px) rotate(98.47deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-86217px, -26310px, 0px) rotate(262deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(6229px, -34978px, 0px) rotate(165.54deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-52931px, -32599px, 0px) rotate(85.91deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(5075px, -35112px, 0px) rotate(111.27deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(101603px, -27737px, 0px) rotate(277.73deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(127187px, 29079px, 0px) rotate(70.94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(21183px, -32622px, 0px) rotate(248.39deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(92389px, -29471px, 0px) rotate(191.44deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(9722px, -46009px, 0px) rotate(168.86deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-4485px, -46851px, 0px) rotate(359.99deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1504px, -33073px, 0px) rotate(246.24deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-54070px, -32785px, 0px) rotate(152.8deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-83212px, -28165px, 0px) rotate(301.16deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-1812px, -34447px, 0px) rotate(269.98deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-105965px, -9852px, 0px) rotate(230deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(68038px, -57789px, 0px) rotate(21.38deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-1785px, -34961px, 0px) rotate(94deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(1089px, -40895px, 0px) rotate(258.96deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(86406px, -16777px, 0px) rotate(110.77deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-57863px, -35480px, 0px) rotate(39.06deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(86073px, 2248px, 0px) rotate(291.58deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(44327px, -35764px, 0px) rotate(199.75deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(101776px, -27734px, 0px) rotate(24.8deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(-13534px, -30961px, 0px) rotate(255deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(47836px, -16694px, 0px) rotate(111.54deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(11539px, 18481px, 0px) rotate(1.34deg);"><img src="https://www.geo-fs.com/images/map/icons/blue.png" class="leaflet-marker-icon geofs-map-icon leaflet-zoom-hide leaflet-interactive" alt="Marker" tabindex="0" role="button" style="margin-left: -15px; margin-top: -15px; width: 30px; height: 30px; transform: translate3d(86973px, 24909px, 0px) rotate(154.08deg);"></div><div class="leaflet-pane leaflet-tooltip-pane" style="opacity: 0.9;"></div><div class="leaflet-pane leaflet-popup-pane"></div><div class="leaflet-proxy leaflet-zoom-animated" style="transform: translate3d(131072px, 131072px, 0px) scale(512);"></div><div class="leaflet-pane leaflet-navaids-pane"></div></div><div class="leaflet-control-container"><div class="leaflet-top leaflet-left"></div><div class="leaflet-top leaflet-right"></div><div class="leaflet-bottom leaflet-left"><div class="leaflet-control-zoom leaflet-bar leaflet-control"><a class="leaflet-control-zoom-in" href="#" role="button" aria-label="Zoom in" aria-disabled="false" id="0.20876748220799035" tabindex="0"><span aria-hidden="true">+</span></a><div class="mdl-tooltip undefined" for="0.20876748220799035" data-upgraded=",MaterialTooltip">Zoom in</div><a class="leaflet-control-zoom-out" href="#" role="button" aria-label="Zoom out" aria-disabled="false" id="0.8085164088475636" tabindex="0"><span aria-hidden="true">−</span></a><div class="mdl-tooltip undefined" for="0.8085164088475636" data-upgraded=",MaterialTooltip">Zoom out</div></div></div><div class="leaflet-bottom leaflet-right"></div></div></div>

            <!-- Legacy autopilot -->
            <div class="geofs-autopilot geofs-stopKeyboardPropagation">
                <h6>Autopilot</h6>
                <button class="mdl-button mdl-js-button mdl-button--raised geofs-autopilot-toggle" onclick="geofs.autopilot.toggle();" id="0.04955637042601291" tabindex="0" data-upgraded=",MaterialButton">Disengaged</button><div class="mdl-tooltip undefined" for="0.04955637042601291" data-upgraded=",MaterialTooltip">Toggle autopilot on/off - [A]</div>
                <div class="geofs-autopilot-displays">
                    <label>
                        Altitude
                        <input type="number" placeholder="00000" min="0" step="1000" class="geofs-autopilot-altitude" onchange="geofs.autopilot.setAltitude(this.value);">
                        <span>Ft.</span>
                    </label>
                    <label>
                        Heading
                        <input type="number" placeholder="000" min="0" max="359" step="1" class="geofs-autopilot-course" onchange="geofs.autopilot.setCourse(this.value);">
                        <span>Deg.</span>
                    </label>
                    <label>
                        Speed
                        <input type="number" placeholder="0" min="0" step="10" class="geofs-autopilot-speed geofs-autopilot-kias" onchange="geofs.autopilot.setSpeed(this.value);">
                        <span>Kts.</span>
                    </label>
                </div>
            </div>

        </div>

        <!-- Debug panel -->
        <div class="geofs-debug geofs-list geofs-toggle-panel" data-onshow="{geofs.debug.turnOn()}" data-onhide="{geofs.debug.turnOff()}" data-noblur="true">
            <div class="geofs-debugFrame">
                <label>Part name<input type="text" class="debugPartName"></label>
                <label>Collision point index<input style="width: 20px;" class="debugCollisionPointIndex" id="0.34462375679224233" tabindex="0"><div class="mdl-tooltip undefined" for="0.34462375679224233" data-upgraded=",MaterialTooltip">collision point index</div></label>
                <textarea class="debugPartData"></textarea>
                <label>Break on animation value<input type="text" class="debugAnimationValue"></label>
                <label class="checkbox">Break on Part Name<input type="checkbox" class="debugBreakOnPartName" id="0.7392015353154826" tabindex="0"><div class="mdl-tooltip undefined" for="0.7392015353154826" data-upgraded=",MaterialTooltip">Break on part name</div></label>
                <label class="checkbox">Force Source Point<input type="checkbox" class="debugShowForceSource" id="0.08716678029658209" tabindex="0"><div class="mdl-tooltip undefined" for="0.08716678029658209" data-upgraded=",MaterialTooltip">force source point</div></label>
                <label class="checkbox">Force Direction<input type="checkbox" class="debugShowForceDirection" id="0.1803519154329829" tabindex="0"><div class="mdl-tooltip undefined" for="0.1803519154329829" data-upgraded=",MaterialTooltip">Force direction</div></label>
                <label class="checkbox">Local Position<input type="checkbox" class="debugShowLocalPosition" id="0.1936712311278994" tabindex="0"><div class="mdl-tooltip undefined" for="0.1936712311278994" data-upgraded=",MaterialTooltip">Local position</div></label>
                <label class="checkbox">suspension Origin<input type="checkbox" class="debugShowsuspensionOrigin" id="0.002910509242233683" tabindex="0"><div class="mdl-tooltip undefined" for="0.002910509242233683" data-upgraded=",MaterialTooltip">Local position</div></label>
                <button class="btn btn-warning" onclick="geofs.killCache = '?killcache=' + Date.now(); geofs.debugResetAircraft = true;">Clear cache</button>
                <button class="btn" onclick="geofs.aircraft.instance.change(geofs.aircraft.instance.id, null, /* forceReload */ true, /*forceReset*/ false);">Just Reload</button>
                <button class="btn" onclick="geofs.aircraft.instance.change(geofs.aircraft.instance.id, null, /* forceReload */ true, /*forceReset*/ true);">Full Reload</button>
                <br>
                <label>Object id<input type="text" class="objectId"></label>
                <div class="geofs-debugObjectLlaHtr"></div>
                ---------------- logs ------------------
                <div class="geofs-debugWatch"></div>
                <div class="geofs-debugLog"></div>
            </div>
        </div>
    <div id="listDiv" class="geofs-list geofs-toggle-panel livery-list" data-noblur="true" data-onshow="{geofs.initializePreferencesPanel()}" data-onhide="{geofs.savePreferencesPanel()}">
        <h3><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo.svg" class="livery-title" id="0.3417782726128207" tabindex="0"><div class="mdl-tooltip undefined" for="0.3417782726128207" data-upgraded=",MaterialTooltip" style="left: 217.5px; margin-left: -40px; top: 155.5px;">LiverySelector</div></h3>

        <div class="livery-searchbar mdl-textfield mdl-js-textfield geofs-stopMousePropagation geofs-stopKeyupPropagation has-placeholder is-upgraded is-dirty" data-upgraded=",MaterialTextfield">
            <input class="mdl-textfield__input address-input" type="text" placeholder="Search liveries" onkeyup="LiverySelector.search(this.value)" id="searchlivery">
            <label class="mdl-textfield__label" for="searchlivery">Search liveries</label>
        </div>

        <h6 onclick="LiverySelector.toggleDiv('favorites')">Favorite liveries</h6>
        <ul id="favorites" class="geofs-list geofs-visible"><li id="10_Airbus house livery (old design)_favorite" class="livery-list-item">Airbus house livery (old design)</li><li id="10_Emirates (Dubai Expo 2020 livery)_favorite" class="livery-list-item">Emirates (Dubai Expo 2020 livery)</li><li id="10_Emirates (Dubai Expo 2022 livery)_favorite" class="livery-list-item">Emirates (Dubai Expo 2022 livery)</li><li id="10_Emirates (new design)_favorite" class="livery-list-item">Emirates (new design)</li><li id="10_Etihad Airways_favorite" class="livery-list-item">Etihad Airways</li><li id="10_Korean Air Lines_favorite" class="livery-list-item">Korean Air Lines</li><li id="10_Qatar Airways_favorite" class="livery-list-item">Qatar Airways</li></ul>

        <h6 onclick="LiverySelector.toggleDiv('liverylist')">Available liveries</h6>
        <ul id="liverylist" class="geofs-list geofs-visible"><li id="10_Air Austral (planned livery)_button" class="livery-list-item offi" data-idx="32" style="display: none;"><span class="livery-name">Air Austral (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-32.png"><span id="10_Air Austral (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air Canada (planned livery)_button" class="livery-list-item offi" data-idx="33" style="display: none;"><span class="livery-name">Air Canada (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-33.png"><span id="10_Air Canada (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air France (50 years Chine France livery)_button" class="livery-list-item offi" data-idx="51" style="display: none;"><span class="livery-name">Air France (50 years Chine France livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-51.png"><small>by Lego and Avgeek YT</small><span id="10_Air France (50 years Chine France livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air France (80 years livery)_button" class="livery-list-item offi" data-idx="52" style="display: none;"><span class="livery-name">Air France (80 years livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-52.png"><small>by Lego and Avgeek YT</small><span id="10_Air France (80 years livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air France (old design - planned livery)_button" class="livery-list-item offi" data-idx="38" style="display: none;"><span class="livery-name">Air France (old design - planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-38.png"><small>by Lego and Avgeek YT</small><span id="10_Air France (old design - planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air France (old design - unpainted)_button" class="livery-list-item offi" data-idx="37" style="display: none;"><span class="livery-name">Air France (old design - unpainted)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-37.png"><small>by Lego and Avgeek YT</small><span id="10_Air France (old design - unpainted)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Air France_button" class="livery-list-item offi" data-idx="1" style="display: none;"><span class="livery-name">Air France</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-1.png"><small>by GeoFS</small><span id="10_Air France" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Airbus house livery (50 years jubilee design)_button" class="livery-list-item offi" data-idx="29" style="display: block;"><span class="livery-name">Airbus house livery (50 years jubilee design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-29.png"><span id="10_Airbus house livery (50 years jubilee design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Airbus house livery (new design)_button" class="livery-list-item offi" data-idx="20" style="display: block;"><span class="livery-name">Airbus house livery (new design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-20.png"><span id="10_Airbus house livery (new design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Airbus house livery (old design)_button" class="livery-list-item offi" data-idx="3" style="display: block;"><span class="livery-name">Airbus house livery (old design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-3.png"><small>by Ariakim Taiyo</small><span id="10_Airbus house livery (old design)" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Airbus house livery (Recycable by design livery)_button" class="livery-list-item offi" data-idx="30" style="display: block;"><span class="livery-name">Airbus house livery (Recycable by design livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-30.png"><span id="10_Airbus house livery (Recycable by design livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Airbus ZeroE (planned livery)_button" class="livery-list-item offi" data-idx="23" style="display: none;"><span class="livery-name">Airbus ZeroE (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-23.png"><span id="10_Airbus ZeroE (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_ANA (Sea Turtle livery)_button" class="livery-list-item offi" data-idx="26" style="display: none;"><span class="livery-name">ANA (Sea Turtle livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-26.png"><span id="10_ANA (Sea Turtle livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_ANA_button" class="livery-list-item offi" data-idx="21" style="display: none;"><span class="livery-name">ANA</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-21.png"><span id="10_ANA" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Asiana Airlines_button" class="livery-list-item offi" data-idx="24" style="display: none;"><span class="livery-name">Asiana Airlines</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-24.png"><span id="10_Asiana Airlines" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_British Airways_button" class="livery-list-item offi" data-idx="4" style="display: none;"><span class="livery-name">British Airways</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-4.png"><small>by iuhairways</small><span id="10_British Airways" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_China Southern_button" class="livery-list-item offi" data-idx="13" style="display: none;"><span class="livery-name">China Southern</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-13.png"><small>by bilibili開飛機のzm[Sino Wings Group]</small><span id="10_China Southern" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (AC Milan 125 years livery)_button" class="livery-list-item offi" data-idx="49" style="display: none;"><span class="livery-name">Emirates (AC Milan 125 years livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-49.png"><small>by Youtube VR PoZz</small><span id="10_Emirates (AC Milan 125 years livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (Dubai Expo 2020 livery)_button" class="livery-list-item offi" data-idx="9" style="display: none;"><span class="livery-name">Emirates (Dubai Expo 2020 livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-9.png"><span id="10_Emirates (Dubai Expo 2020 livery)" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (Dubai Expo 2020 logo)_button" class="livery-list-item offi" data-idx="0" style="display: none;"><span class="livery-name">Emirates (Dubai Expo 2020 logo)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-0.png"><small>by GeoFS</small><span id="10_Emirates (Dubai Expo 2020 logo)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (Dubai Expo 2022 livery)_button" class="livery-list-item offi" data-idx="14" style="display: none;"><span class="livery-name">Emirates (Dubai Expo 2022 livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-14.png"><span id="10_Emirates (Dubai Expo 2022 livery)" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (NBA livery)_button" class="livery-list-item offi" data-idx="40" style="display: none;"><span class="livery-name">Emirates (NBA livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-40.png"><small>by Class323</small><span id="10_Emirates (NBA livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (new design)_button" class="livery-list-item offi" data-idx="27" style="display: none;"><span class="livery-name">Emirates (new design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-27.png"><small>by GeoFSFlightVideoGroupYT</small><span id="10_Emirates (new design)" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (old design)_button" class="livery-list-item offi" data-idx="28" style="display: none;"><span class="livery-name">Emirates (old design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-28.png"><small>by Youtube VR PoZz</small><span id="10_Emirates (old design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (The Emirates Foundation livery)_button" class="livery-list-item offi" data-idx="44" style="display: none;"><span class="livery-name">Emirates (The Emirates Foundation livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-44.png"><small>by GeoFSFlightVideoGroupYT</small><span id="10_Emirates (The Emirates Foundation livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (The sky is only the begining livery)_button" class="livery-list-item offi" data-idx="48" style="display: none;"><span class="livery-name">Emirates (The sky is only the begining livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-48.png"><small>by Youtube VR PoZz</small><span id="10_Emirates (The sky is only the begining livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (Wimbledon livery)_button" class="livery-list-item offi" data-idx="41" style="display: none;"><span class="livery-name">Emirates (Wimbledon livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-41.png"><small>by kingjacob23</small><span id="10_Emirates (Wimbledon livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Emirates (Year of Zayed livery)_button" class="livery-list-item offi" data-idx="50" style="display: none;"><span class="livery-name">Emirates (Year of Zayed livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-50.png"><small>by Burnin Hell</small><span id="10_Emirates (Year of Zayed livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Etihad Airways (Airbus house design)_button" class="livery-list-item offi" data-idx="10" style="display: block;"><span class="livery-name">Etihad Airways (Airbus house design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-10.png"><span id="10_Etihad Airways (Airbus house design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Etihad Airways_button" class="livery-list-item offi" data-idx="15" style="display: none;"><span class="livery-name">Etihad Airways</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-15.png"><span id="10_Etihad Airways" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Global Airlines (ex China Southern - Global Airlines tail)_button" class="livery-list-item offi" data-idx="47" style="display: none;"><span class="livery-name">Global Airlines (ex China Southern - Global Airlines tail)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-47.png"><small>by bilibili開飛機のzm[Sino Wings Group] &amp; Burnin Hell</small><span id="10_Global Airlines (ex China Southern - Global Airlines tail)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Global Airlines (ex China Southern)_button" class="livery-list-item offi" data-idx="46" style="display: none;"><span class="livery-name">Global Airlines (ex China Southern)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-46.png"><small>by bilibili開飛機のzm[Sino Wings Group]</small><span id="10_Global Airlines (ex China Southern)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Global Airlines_button" class="livery-list-item offi" data-idx="35" style="display: none;"><span class="livery-name">Global Airlines</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-35.png"><small>by Jason HW</small><span id="10_Global Airlines" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_HiFly_button" class="livery-list-item offi" data-idx="19" style="display: none;"><span class="livery-name">HiFly</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-19.png"><span id="10_HiFly" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Kingfisher_button" class="livery-list-item offi" data-idx="42" style="display: none;"><span class="livery-name">Kingfisher</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-42.png"><small>by Lego and Avgeek YT</small><span id="10_Kingfisher" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Korean Air Lines_button" class="livery-list-item offi" data-idx="8" style="display: none;"><span class="livery-name">Korean Air Lines</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-8.png"><small>by kingjacob23 [Geofs Livery Factory]</small><span id="10_Korean Air Lines" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Korean Airlines (unpainted)_button" class="livery-list-item offi" data-idx="43" style="display: none;"><span class="livery-name">Korean Airlines (unpainted)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-43.png"><small>by Burnin Hell &amp; Lego and Avgeek YT</small><span id="10_Korean Airlines (unpainted)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Lufthansa (new design)_button" class="livery-list-item offi" data-idx="5" style="display: none;"><span class="livery-name">Lufthansa (new design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-5.png"><small>by iuhairways</small><span id="10_Lufthansa (new design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Lufthansa (old design)_button" class="livery-list-item offi" data-idx="6" style="display: none;"><span class="livery-name">Lufthansa (old design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-6.png"><small>by Kolos26</small><span id="10_Lufthansa (old design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Malaysia Airlines (retired plane)_button" class="livery-list-item offi" data-idx="17" style="display: none;"><span class="livery-name">Malaysia Airlines (retired plane)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-17.png"><span id="10_Malaysia Airlines (retired plane)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Malaysia Airlines_button" class="livery-list-item offi" data-idx="11" style="display: none;"><span class="livery-name">Malaysia Airlines</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-11.png"><span id="10_Malaysia Airlines" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Qantas (Airbus house design)_button" class="livery-list-item offi" data-idx="31" style="display: block;"><span class="livery-name">Qantas (Airbus house design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-31.png"><span id="10_Qantas (Airbus house design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Qantas (new design)_button" class="livery-list-item offi" data-idx="2" style="display: none;"><span class="livery-name">Qantas (new design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-2.png"><small>by GeoFS</small><span id="10_Qantas (new design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Qantas (old design)_button" class="livery-list-item offi" data-idx="16" style="display: none;"><span class="livery-name">Qantas (old design)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-16.png"><span id="10_Qantas (old design)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Qatar Airways (FIFA World Cup 2022 livery)_button" class="livery-list-item offi" data-idx="22" style="display: none;"><span class="livery-name">Qatar Airways (FIFA World Cup 2022 livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-22.png"><span id="10_Qatar Airways (FIFA World Cup 2022 livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Qatar Airways_button" class="livery-list-item offi" data-idx="7" style="display: none;"><span class="livery-name">Qatar Airways</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-7.png"><span id="10_Qatar Airways" class="fa fa-star checked" onclick="LiverySelector.star(this)"></span></li><li id="10_Singapore Airlines (Fly the flag livery)_button" class="livery-list-item offi" data-idx="36" style="display: none;"><span class="livery-name">Singapore Airlines (Fly the flag livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-36.png"><small>by GEO-FS-FLIGHTS[YT]</small><span id="10_Singapore Airlines (Fly the flag livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Singapore Airlines_button" class="livery-list-item offi" data-idx="12" style="display: none;"><span class="livery-name">Singapore Airlines</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-12.png"><small>by Androway</small><span id="10_Singapore Airlines" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Skymark Airlines (planned livery)_button" class="livery-list-item offi" data-idx="34" style="display: block;"><span class="livery-name">Skymark Airlines (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-34.png"><small>by whois无名氏[Sino Wings Group]</small><span id="10_Skymark Airlines (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Swissair (planned livery)_button" class="livery-list-item offi" data-idx="25" style="display: none;"><span class="livery-name">Swissair (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-25.png"><span id="10_Swissair (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Thai Airways_button" class="livery-list-item offi" data-idx="18" style="display: none;"><span class="livery-name">Thai Airways</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-18.png"><span id="10_Thai Airways" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Virgin Atlantic (new design - planned livery)_button" class="livery-list-item offi" data-idx="45" style="display: none;"><span class="livery-name">Virgin Atlantic (new design - planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-45.png"><small>by Lego and Avgeek YT</small><span id="10_Virgin Atlantic (new design - planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li><li id="10_Virgin Atlantic (planned livery)_button" class="livery-list-item offi" data-idx="39" style="display: none;"><span class="livery-name">Virgin Atlantic (planned livery)</span><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/thumbs/10/10-39.png"><small>by Lego and Avgeek YT</small><span id="10_Virgin Atlantic (planned livery)" class="fa fa-star nocheck" onclick="LiverySelector.star(this)"></span></li></ul>

        <h6 onclick="LiverySelector.toggleDiv('airlinelist')">Virtual airlines</h6><button class="mdl-button mdl-js-button mdl-button--raised mdl-button" style="background-color: #096628; color: white;" onclick="LiverySelector.addAirline()" data-upgraded=",MaterialButton">+ Add airline</button>
        <ul id="airlinelist" class="geofs-list geofs-visible"></ul>

        <h6 onclick="LiverySelector.toggleDiv('customDiv')" class="closed">Load external livery</h6>
        <div id="customDiv" class="mdl-textfield mdl-js-textfield geofs-stopMousePropagation geofs-stopKeyupPropagation has-placeholder is-upgraded" style="display:none;" data-upgraded=",MaterialTextfield">
            <ul class="livery-custom-tabs" onclick="LiverySelector.handleCustomTabs()">
                <li>Upload</li>
                <li>Direct</li>
                <li>Download</li>
                <li>API</li>
            </ul>
            <div id="livery-custom-tab-upload" style="">
                <div>Paste URL or upload image to generate imgbb URL</div>
                <div class="upload-fields"><input type="file" onchange="LiverySelector.uploadLivery(this)" class="err"><input type="text" name="textureInput" class="mdl-textfield__input address-input" placeholder="Specular shader" id="Specular shader"><br><input type="file" onchange="LiverySelector.uploadLivery(this)" class="err"><input type="text" name="textureInput" class="mdl-textfield__input address-input" placeholder="Texture" id="Texture"><br></div>
                <div><button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" onclick="LiverySelector.inputLivery()" data-upgraded=",MaterialButton">Load livery</button></div>
                <div class="livery-submit geofs-list-collapsible-item">Contribute to the LiverySelector Database
                    <div class="geofs-collapsible no-api">-&gt; Fill in API key and Discord User ID in API tab.</div>
                    <div class="geofs-collapsible api" style="display: none;">
                        <label for="livery-submit-liveryname">Livery Name</label>
                        <input type="text" id="livery-submit-liveryname" class="mdl-textfield__input address-input">
                        <label for="livery-submit-credits">Author</label>
                        <input type="text" id="livery-submit-credits" class="mdl-textfield__input address-input">
                        <input type="checkbox" id="livery-submit-confirm-perms">
                        <label for="livery-submit-confirm-perms">I am the author and have created the textures myself or have the permission from the author to use those textures.</label><br>
                        <input type="checkbox" id="livery-submit-confirm-legal">
                        <label for="livery-submit-confirm-legal">I confirm the textures are safe for all ages, are non-offensive and appropriate for the game and don't violate any laws or other regulations.</label>
                        <button class="mdl-button mdl-js-button mdl-button--raised mdl-button--colored" onclick="LiverySelector.submitLivery()" data-upgraded=",MaterialButton">Submit livery for review</button>
                        <small>
                          Join our <a href="https://discord.gg/2tcdzyYaWU" target="_blank">Discord</a> to follow up on your contributions.
                          By submitting you agree to the Discord server rules. Failing to comply may result in exclusion from further submits.
                        </small>
                    </div>
                </div>
            </div>
            <div id="livery-custom-tab-direct" style="display:none;">
                <div>Load texture directly in client, no upload.</div>
                <div class="upload-fields"><input type="file" onchange="LiverySelector.loadLiveryDirect(this,0)"><span>Specular shader</span><br><input type="file" onchange="LiverySelector.loadLiveryDirect(this,1)"><span>Texture</span><br></div>
            </div>
            <div id="livery-custom-tab-download" style="display:none;">
                <div>Download textures for current Airplane:</div>
                <div class="download-fields"></div>
            </div>
            <div id="livery-custom-tab-api" style="display:none;">
              <div>
                <label for="livery-setting-apikey">Paste your imgbb API key here (<a href="https://api.imgbb.com" target="_blank">get key</a>)</label>
                <input type="text" id="livery-setting-apikey" class="mdl-textfield__input address-input" onchange="LiverySelector.saveSetting(this)">
                <input type="checkbox" id="livery-setting-remove" onchange="LiverySelector.saveSetting(this)">
                <label for="livery-setting-remove">Expire links after one hour<br><small>(only for testing, disable when submitting to the database!)</small></label>
                <label for="livery-setting-discordid">Discord User ID (<a href="https://support.discord.com/hc/en-us/articles/206346498" target="_blank">howto</a>)</label>
                <input type="number" id="livery-setting-discordid" class="mdl-textfield__input address-input" onchange="LiverySelector.saveSetting(this)">
              </div>
            </div>
        </div>
        <br>
        <a href="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/refs/heads/main/tutorial.txt" target="_blank"><button class="mdl-button mdl-js-button mdl-button--raised mdl-button" data-upgraded=",MaterialButton">Open tutorial</button></a><br>
        <a href="https://discord.gg/2tcdzyYaWU" target="_blank"><button class="mdl-button mdl-js-button mdl-button--raised mdl-button" data-upgraded=",MaterialButton">Join our discord server</button></a><br>
        <a href="https://github.com/kolos26/GEOFS-LiverySelector" target="_blank"><button class="mdl-button mdl-js-button mdl-button--raised mdl-button" data-upgraded=",MaterialButton">Visit our Github page</button></a><br>
        <a href="mailto:LiverySelector20220816@gmail.com" target="_blank"><button class="mdl-button mdl-js-button mdl-button--raised mdl-button" data-upgraded=",MaterialButton">Contact us: LiverySelector20220816@gmail.com</button></a><br>
</div></div>

    <a href="/" class="geofs-home-button geofs-hideForApp" style="z-index: 30;" id="0.5118416185193542" tabindex="0"><i class="material-icons"></i></a><div class="mdl-tooltip undefined" for="0.5118416185193542" data-upgraded=",MaterialTooltip">GeoFS home page</div>

    
        <div class="geofs-adbanner geofs-adsense-container">

            <style>
                .geofs-adbanner ins {
                    width: 302px;
                    max-width: 302px;
                    min-width: 162px;
                    height: 100%;
                }

                @media screen and (max-width: 1600px) {
                    .geofs-adbanner ins {
                        width: 162px;
                    }
                }

                @media screen and (orientation: portrait) {
                    .geofs-adbanner ins {
                        width: 100% !important;
                        max-width: 100% !important;
                        min-height: 162px;
                        height: 162px;
                    }
                }

            </style>

            <div class="geofs-refreshTarget">

                <div class="geofs-adsBlockedMessage" style="text-align: center;">
    
<a href="/pages/hd.php" target="_top" style="display: inline-block; text-align: center; width: 100%; height: 100%;">
<img style="max-width: 160px; max-height: 100%;" src="/images/ba/hd_skyscraper.jpg"></a></div>
                <script async="" src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
                <ins class="adsbygoogle" style="display:block;" data-ad-client="ca-pub-1808592532341984" data-ad-slot="5302287636"></ins>
            </div>
        </div>

        <script>

            (adsbygoogle = window.adsbygoogle || []).push({});

            window.executeOnEventDone('afterDeferredload', function() {

                geofs.lastFlyTo = new Date().getTime();
		        geofs.adCount = 1;
                $(document).on('flyto', function() {
                    var t = new Date().getTime();
                    if (t - geofs.lastFlyTo > 30000) {

                        if (geofs.adCount % 3 == 0 || window.adsBlocked) { // every three impressions
                            if (window.innerWidth <= 800) {
                                $('.geofs-refreshTarget').htmlView('load', '/pages/common/includes/ba/apps.php?type=2');
                            }
                            else {
                                $('.geofs-refreshTarget').htmlView('load', '/pages/common/includes/ba/loader.php?type=2');
                            }
                        }
                        else {
                            $('.geofs-refreshTarget').empty().html('<scr'+'ipt async src="//pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"><'+'/scr'+'ipt><ins class="adsbygoogle" style="display:block;'+(geofs.api.testIfMobileDevice()?'height:162px;':'')+'" data-ad-client="ca-pub-1808592532341984" data-ad-slot="5302287636" data-ad-format="vertical"><'+'/ins><scr'+'ipt>(adsbygoogle = window.adsbygoogle || []).push({});<'+'/scr'+'ipt>');
                        }
                        geofs.adCount++;
                        geofs.lastFlyTo = t;
                    }
                });
            });
        </script>

    
    <!-- Bottom bar -->
    <div class="geofs-ui-bottom">

        <!-- Mobile Options button-->
        <button class="mdl-button mdl-js-button mdl-button--icon geofs-f-standard-ui geofs-onlyForMobile" style="margin-left: 10px;" data-toggle-panel=".geofs-preference-list" titlenot="Open the settings/options panel" data-tooltip-classname="mdl-tooltip--top" data-upgraded=",MaterialButton"><i class="material-icons">menu</i></button>

        <!-- Small screen menu -->
        <button id="small_screen_menu" class="mdl-button mdl-js-button mdl-button--icon geofs-smallScreenOnly" data-upgraded=",MaterialButton">
            <i class="material-icons">more_vert</i>
        </button>

        <!-- Small Screen Menu -->
        <div class="mdl-menu__container is-upgraded"><div class="mdl-menu__outline mdl-menu--top-left"></div><ul class="mdl-menu mdl-menu--top-left mdl-js-menu mdl-js-ripple-effect geofs-smallScreenOnly mdl-js-ripple-effect--ignore-events" for="small_screen_menu" data-upgraded=",MaterialMenu,MaterialRipple">

            <li class="mdl-menu__item mdl-js-ripple-effect" tabindex="-1" data-upgraded=",MaterialRipple">
                <!-- Pause, mute, reset -->
                <div class="geofs-ui-bottom-box geofs-f-standard-ui">
                    <button class="geofs-button-pause mdl-button mdl-js-button mdl-button--icon" onclick="geofs.togglePause();" id="0.6818014593963608" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">pause_circle_outline</i></button><div class="mdl-tooltip undefined" for="0.6818014593963608" data-upgraded=",MaterialTooltip">Pause/Unpause [P]</div>
                    <button class="geofs-button-mute mdl-button mdl-js-button mdl-button--icon" onclick="audio.toggleMute();" id="0.41802349989489573" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">volume_off</i></button><div class="mdl-tooltip undefined" for="0.41802349989489573" data-upgraded=",MaterialTooltip">Mute/Unmute sound [S]</div>
                    <button class="geofs-button-visibility mdl-button mdl-js-button mdl-button--icon" onclick="geofs.visibilityCycle();" id="0.3449850817443063" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">visibility</i></button><div class="mdl-tooltip undefined" for="0.3449850817443063" data-upgraded=",MaterialTooltip">Cycle UI visibility [H]</div>
                    <button class="mdl-button mdl-js-button mdl-button--icon" onclick="geofs.resetFlight();" id="0.197538972720537" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">autorenew</i></button><div class="mdl-tooltip undefined" for="0.197538972720537" data-upgraded=",MaterialTooltip">Reset the flight [R]</div>
                    <button class="mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="flight.recorder.enterPlayback();" id="0.9854067072787094" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">play_circle_outline</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.9854067072787094" data-upgraded=",MaterialTooltip">Watch recorded flight [V]</div>
                </div>
            <span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" tabindex="-1" data-upgraded=",MaterialRipple">
                <button class="mdl-button mdl-js-button geofs-f-standard-ui geofs-hideForMobile" data-toggle-panel=".geofs-preference-list" id="0.5413071234962312" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">settings</i> Options</button><div class="mdl-tooltip undefined" for="0.5413071234962312" data-upgraded=",MaterialTooltip">Open the settings/options panel [O]</div>
            <span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" tabindex="-1" data-upgraded=",MaterialRipple">
                <button class="mdl-button mdl-js-button geofs-f-standard-ui" data-toggle-panel=".geofs-map-list" id="0.5110377017479166" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">explore</i> Nav</button><div class="mdl-tooltip undefined" for="0.5110377017479166" data-upgraded=",MaterialTooltip">Navigation charts [N]</div>
            <span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item geofs-hideForApp mdl-js-ripple-effect" tabindex="-1" data-upgraded=",MaterialRipple">
                <button class="geofs-button-fullscreen mdl-button mdl-js-button geofs-f-standard-ui" onclick="ui.toggleFullscreen();" style="float: right;" data-tooltip-classname="mdl-tooltip--top" id="0.6227738369167943" tabindex="0" data-upgraded=",MaterialButton">
                    <span class="material-icons geofs-fullscreenIconOpen">open_in_full</span>
                    <span class="material-icons geofs-fullscreenIconClose">close_fullscreen</span>
                    Fullscreen
                </button><div class="mdl-tooltip mdl-tooltip--top" for="0.6227738369167943" data-upgraded=",MaterialTooltip">Toggle fullscreen</div>
            <span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
        </ul></div>

        <!-- Full size menu -->
        <!-- Main panels toggle buttons -->
        <button class="mdl-button mdl-js-button geofs-f-standard-ui" data-toggle-panel=".geofs-aircraft-list" data-upgraded=",MaterialButton">Aircraft</button>
        <button id="liverybutton" class="mdl-button mdl-js-button geofs-f-standard-ui geofs-mediumScreenOnly" onclick="LiverySelector.listLiveries()" data-toggle-panel=".livery-list" data-tooltip-classname="mdl-tooltip--top" data-upgraded=",MaterialButton" tabindex="0"><img src="https://raw.githubusercontent.com/kolos26/GEOFS-LiverySelector/main/liveryselector-logo-small.svg" height="30px"></button><div class="mdl-tooltip mdl-tooltip--top" for="liverybutton" data-upgraded=",MaterialTooltip">Change livery</div><button class="mdl-button mdl-js-button mdl-button--colored geofs-authenticated geofs-editor-role geofs-f-standard-ui geofs-bigScreenOnly" data-toggle-panel=".geofs-debug" data-upgraded=",MaterialButton">Debug</button>
        <button class="mdl-button mdl-js-button geofs-f-standard-ui" data-toggle-panel=".geofs-location-list" data-upgraded=",MaterialButton">Location</button>

        <!--
            *
            *
            * Camera selector
            *
            *
        -->
        <button id="geofs-camera-selector" class="mdl-button mdl-js-button" data-upgraded=",MaterialButton">Camera</button>

        <div class="mdl-menu__container is-upgraded"><div class="mdl-menu__outline mdl-menu--top-left"></div><ul class="mdl-menu mdl-menu--top-left mdl-js-menu mdl-js-ripple-effect mdl-js-ripple-effect--ignore-events" for="geofs-camera-selector" data-upgraded=",MaterialMenu,MaterialRipple">
            <li class="geofs-extra-views mdl-menu__item mdl-menu__item--full-bleed-divider mdl-js-ripple-effect" tabindex="-1" data-upgraded=",MaterialRipple">Extra views
                <ul class="mdl-menu geofs-extra-views-holder"><li class="mdl-menu__item" data-camera="Wheels">Wheels</li><li class="mdl-menu__item" data-camera="Wing">Wing</li><li class="mdl-menu__item" data-camera="Wing 2">Wing 2</li><li class="mdl-menu__item" data-camera="Tail">Tail</li></ul>
            <span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="0" tabindex="-1" data-upgraded=",MaterialRipple">Follow cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="1" tabindex="-1" data-upgraded=",MaterialRipple">Cockpit cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="2" tabindex="-1" data-upgraded=",MaterialRipple">Cockpit-less cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="3" tabindex="-1" data-upgraded=",MaterialRipple">Chase cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="4" tabindex="-1" data-upgraded=",MaterialRipple">Free cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-menu__item--full-bleed-divider mdl-js-ripple-effect" data-camera="5" tabindex="-1" data-upgraded=",MaterialRipple">Fixed cam<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
            <li class="mdl-menu__item mdl-js-ripple-effect" data-camera="-1" tabindex="-1" data-upgraded=",MaterialRipple">Reset<span class="mdl-menu__item-ripple-container"><span class="mdl-ripple"></span></span></li>
        </ul></div>

        <!-- Options and map -->
        <button class="mdl-button mdl-js-button geofs-f-standard-ui geofs-hideForMobile" data-toggle-panel=".geofs-preference-list" data-tooltip-classname="mdl-tooltip--top" id="0.9406241092109857" tabindex="0" data-upgraded=",MaterialButton">Options <i class="material-icons geofs-ui-bottom-icon">settings</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.9406241092109857" data-upgraded=",MaterialTooltip">Open the settings/options panel [O]</div>
        <button class="mdl-button mdl-js-button geofs-f-standard-ui" data-toggle-panel=".geofs-map-list" data-tooltip-classname="mdl-tooltip--top" id="0.8269718569190188" tabindex="0" data-upgraded=",MaterialButton">Nav <i class="material-icons geofs-ui-bottom-icon">explore</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.8269718569190188" data-upgraded=",MaterialTooltip" style="left: 479.492px; margin-left: -74px; top: 869px;">Open the navigation panel [N]</div>
<!--
        <button class="geofs-button-vr mdl-button mdl-js-button geofs-f-standard-ui geofs-editor-role" onclick="ui.vr.toggle();" data-tooltip-classname="mdl-tooltip--top" title="Toggle VR"><img src="/images/vr-icon.png"/></button>
-->

        <button class="geofs-button-fullscreen mdl-button mdl-js-button geofs-f-standard-ui geofs-hideForApp" onclick="ui.toggleFullscreen();" style="float: right;" data-tooltip-classname="mdl-tooltip--top" id="0.9208879213684804" tabindex="0" data-upgraded=",MaterialButton">
            <span class="material-icons geofs-fullscreenIconOpen">open_in_full</span>
            <span class="material-icons geofs-fullscreenIconClose">close_fullscreen</span>
        </button><div class="mdl-tooltip mdl-tooltip--top" for="0.9208879213684804" data-upgraded=",MaterialTooltip">Toggle fullscreen</div>

        <!-- Pause, mute, reset, playback -->
        <div class="geofs-ui-bottom-box geofs-f-standard-ui">
            <button class="geofs-button-pause mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="geofs.togglePause();" id="0.11382390798950293" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">pause_circle_outline</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.11382390798950293" data-upgraded=",MaterialTooltip">Pause/Unpause [P]</div>
            <button class="geofs-button-mute mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="audio.toggleMute();" id="0.9389888080717597" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">volume_off</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.9389888080717597" data-upgraded=",MaterialTooltip">Mute/Unmute sound [S]</div>
            <button class="geofs-button-visibility mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="geofs.visibilityCycle();" id="0.93799830851433" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">visibility</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.93799830851433" data-upgraded=",MaterialTooltip">Cycle UI visibility [H]</div>
            <button class="mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="geofs.resetFlight();" id="0.8627366854879424" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">autorenew</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.8627366854879424" data-upgraded=",MaterialTooltip">Reset the flight [R]</div>
            <button class="mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="flight.recorder.enterPlayback();" id="0.8644697599539921" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">play_circle_outline</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.8644697599539921" data-upgraded=",MaterialTooltip">Watch recorded flight [V]</div>
        </div>

        <button class="mdl-button mdl-js-button geofs-authenticated mdl-button--icon geofs-f-standard-ui" data-tooltip-classname="mdl-tooltip--top" data-toggle-panel=".geofs-player-list" id="0.044259910830438454" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">group</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.044259910830438454" data-upgraded=",MaterialTooltip">List of online pilots</div>

        <!-- Chat -->
        <div class="geofs-chat-input-section geofs-authenticated geofs-f-standard-ui geofs-bigScreenOnly geofs-hideForMobile">
            <button class="geofs-chat-button mdl-button mdl-js-button" data-tooltip-classname="mdl-tooltip--top" id="0.06682369439350166" tabindex="0" data-upgraded=",MaterialButton">Talk <i class="icon-align-left"></i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.06682369439350166" data-upgraded=",MaterialTooltip">Type a chat message [T]</div>
            <form class="geofs-chat-form">
                <div class="mdl-textfield mdl-js-textfield is-upgraded" data-upgraded=",MaterialTextfield">
                    <input class="mdl-textfield__input geofs-chat-input geofs-stopKeyboardPropagation geofs-stopKeyupPropagation geofs-stopMousePropagation" size="30" maxlength="70" type="text" id="chatInput">
                    <label class="mdl-textfield__label" for="chatInput">Message...</label>
                </div>
                <button class="geofs-chat-send-button mdl-button mdl-js-button mdl-button--colored" type="submit" data-upgraded=",MaterialButton">Send</button>
            </form>
        </div>

        <button class="mdl-button mdl-js-button geofs-f-standard-ui geofs-hd-button geofs-onlyForApp" data-upgraded=",MaterialButton"><i class="material-icons">hd</i></button>

        <button class="mdl-button mdl-js-button mdl-button--icon geofs-f-standard-ui geofs-orientationReset" data-tooltip-classname="mdl-tooltip--top" id="0.09481346702246696" tabindex="0" data-upgraded=",MaterialButton">
            <i class="material-icons">adjust</i>
        </button><div class="mdl-tooltip mdl-tooltip--top" for="0.09481346702246696" data-upgraded=",MaterialTooltip">Reset orientation controls to neutral</div>

        <!--
            *
            *
            * Record player
            *
            *
        -->
        <div class="geofs-f-recordPlayer">

            <a class="mdl-button mdl-js-button geofs-screenshot" download="geofs.jpg" href="" onclick="geofs.api.takeCanvasScreenShot(this);" data-tooltip-classname="mdl-tooltip--top" id="0.19951083990924667" tabindex="0" data-upgraded=",MaterialButton">
                <span class="material-icons">photo_camera</span>
            </a><div class="mdl-tooltip mdl-tooltip--top" for="0.19951083990924667" data-upgraded=",MaterialTooltip">Canvas Screenshot</div>

            <button class="mdl-button mdl-js-button" onclick="flight.recorder.exitPlayback();" data-tooltip-classname="mdl-tooltip--top" id="0.5750866795103962" tabindex="0" data-upgraded=",MaterialButton">Exit player</button><div class="mdl-tooltip mdl-tooltip--top" for="0.5750866795103962" data-upgraded=",MaterialTooltip">Exit record player</div>

            <!-- Player controls -->
            <div class="geofs-ui-bottom-box">

                <label style="padding: 0px;" class="mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" for="flightfileupload" id="0.4917669137066307" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">folder_open</i></label><div class="mdl-tooltip mdl-tooltip--top" for="0.4917669137066307" data-upgraded=",MaterialTooltip">Open recorded flight (JSON)</div>
                <a style="padding: 0px;" class="mdl-button mdl-js-button mdl-button--icon" data-tooltip-classname="mdl-tooltip--top" onclick="flight.recorder.download(this);" id="0.5785791253460622" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">save</i></a><div class="mdl-tooltip mdl-tooltip--top" for="0.5785791253460622" data-upgraded=",MaterialTooltip">Save recorded flight</div>
                <input type="file" id="flightfileupload" style="display: none;" onchange="flight.recorder.upload(this);">

                <!--<button class="mdl-button mdl-js-button mdl-button--icon" onclick="flight.recorder.setStep(0, 'set');" data-tooltip-classname="mdl-tooltip--top" title="Begining"><i class="material-icons">fast_rewind</i></button>-->
                <button class="mdl-button mdl-js-button mdl-button--icon" onclick="flight.recorder.startPlayback();" data-tooltip-classname="mdl-tooltip--top" id="0.07448613406515658" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">play_arrow</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.07448613406515658" data-upgraded=",MaterialTooltip">Start playback</div>
                <button class="geofs-button-pause mdl-button mdl-js-button mdl-button--icon" onclick="geofs.togglePause();" data-tooltip-classname="mdl-tooltip--top" id="0.3651077572644055" tabindex="0" data-upgraded=",MaterialButton"><i class="material-icons">pause</i></button><div class="mdl-tooltip mdl-tooltip--top" for="0.3651077572644055" data-upgraded=",MaterialTooltip">Pause/Unpause playback [P]</div>
                <!--<button class="mdl-button mdl-js-button mdl-button--icon" onclick="flight.recorder.setStep(100000, 'set');" data-tooltip-classname="mdl-tooltip--top" title="End"><i class="material-icons">fast_forward</i></button>-->

            </div>

        </div>

        <!-- player slider -->
        <div class="geofs-f-recordPlayer geofs-slider-container">
            <div class="slider geofs-recordPlayer-slider" data-type="slider" value="0" data-min="0" data-precision="0" style="height: 10px;">
                <div class="slider-rail">
                    <div class="slider-selection">
                        <div class="slider-grippy"><input class="slider-input"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>



<div class="ads adsbox adBlock">&nbsp;</div><script type="text/javascript" src="https://connect.facebook.net/en_US/sdk.js"></script><script type="text/javascript" src="https://apis.google.com/js/platform.js?onload=googlePlatformLoadCallback" gapi_processed="true"></script><div id="fb-root" class=" fb_reset"><div style="position: absolute; top: -10000px; width: 0px; height: 0px;"><div></div></div></div><iframe id="ssIFrame_google" sandbox="allow-scripts allow-same-origin allow-storage-access-by-user-activation" allow="identity-credentials-get" aria-hidden="true" frame-border="0" src="https://accounts.google.com/o/oauth2/iframe#origin=https%3A%2F%2Fwww.geo-fs.com&amp;rpcToken=1923367743.8834212" style="position: absolute; width: 1px; height: 1px; inset: -9999px; display: none;"></iframe></body></html>
