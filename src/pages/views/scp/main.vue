<style lang="less" module>
    @import '../../../assets/less/const.less';
    .wrap{
        background-image: url('@img/banner.png');
        background-repeat: no-repeat;
        background-position: center;
        background-size: 100% 100%;
        min-height: 965*@px2rem;
        padding-top: 39*@px2rem;
    }
    .content{
        width: 75%;
        min-width: 45*@px2rem;
        margin: 0 auto;
        padding: 0 .5rem;
        .logo{
            margin-top: 79*@px2rem;
            margin-left: auto;
            margin-right: auto;
            width: 154*@px2rem;
            height: 178*@px2rem;
            background:url('@img/main-logo.png') no-repeat;
            background-size: 100% 100%;
        }
        .desc{
            color: #fff;
            .dfn1{
                font-weight: bolder;
                margin-top: 23*@px2rem;
                font-size: 36*@px2rem;
            }
            .dfn2{
                margin-top: 13*@px2rem;
                font-size: 30*@px2rem;
            }
            .dfn3{
                font-weight: bolder;
                margin-top: 63*@px2rem;
                font-size: 40*@px2rem;
            }
             .dfn4{
                margin-top: 44*@px2rem;
                font-size: 18*@px2rem;
            }
        }
    }
    .header{
        color: #fff;
    }
    .title{
       font-weight: bolder;
       width: 239*@px2rem;
       height: 56*@px2rem;
       background-image: url('@img/SCP.png');
       background-repeat: no-repeat;
       background-size: 100%  100%;
    }
    .link{
        display: block;
        border: 2*@px2rem solid #FFFFFF;
        width: 172*@px2rem;
        height: 60*@px2rem;
        line-height: 60*@px2rem;
        border-radius: 7*@px2rem;
        font-size: 32*@px2rem;
        color: #fff;
    }
</style>

<template>
    <div :class="$style.wrap">
        <div :class="$style.content">
            <header :class="[$style.header,'clearfix']">
                <a :class="[$style.title,'fl']" href="./"></a>
                <a :class="[$style.link,'fr','text-center']" href="http://www.servicechain.info/pdf/scp_intro.pdf" target="_blank">白皮书</a>
            </header>
            <div class="text-center">
                <div :class="$style.logo"></div>
                <article :class="$style.desc">
                    <div :class="$style.dfn1">Service Chain Protocol</div>
                    <div :class="$style.dfn2">面向全球个人服务者和小微企业服务者的信用中介与支付平台</div>
                    <div :class="$style.dfn3">什么是商链？</div>
                    <div :class="[$style.dfn4,'text-left']">使用区块链技术，面向全球和全行业的个人以及小微企业服务者的信用和支付解决方案。可以有效解决个人服务和小微企业服务过程中的信用缺失，信用篡改，信用孤岛，信用欺诈问题。为全球的个人服务者和小微服务者建立实名公正的信用体系，并基于此实现全球范围内服务的信用支付，要做全球服务行业的Airbnb和支付宝。</div>
                    <div :class="$style.dfn4">特别声明：商链的所有支付行为均在国家法律和法规允许范围内。</div>
                </article>
            </div>
        </div>
    </div>
</template>
