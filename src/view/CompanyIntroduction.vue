<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center">关于我们</div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/about_img.png">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>武汉理工大学电子商务协会</h3>
                    <p class=".text-justify">武汉理工大学电子商务协会是2008年初发起创办的，协会创建的目的旨在培养同学之间的团队精神，整合我校现有资源，在校园里开展电子商务活动，宣传电子商务知识，锻炼和提高同学们电脑操作、商务软件平台应用、商务谈判、公关策划、组织管理协调能力，让喜欢网上买卖的同学都能参与实际的操作，让热爱网站建设的同学都能学到网站建设的相关知识及事例。协会现任会长：张洁 会长助理：李佳明。</p>
                    <p class=".text-justify">用科技沟通你我，营造校园里学习电子商务应用及技术开发的良好氛围，活跃电子商务活动的实践气氛，帮助对电子商务感兴趣的学生掌握理论知识，增强实践创新能力。以国外电子商务理论为基础，探索中国特色的电子商务道路，培养电子商务人才，加强本校学生在网络时代的竞争力，引领信息时代新潮流。</p>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.png');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

