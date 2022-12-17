<template>
  <div id="JobChance">
    <div class="banner container-fuild text-center">工作机会</div>
    <div class="container">
      <div class="JobChance-container wow pulse">
        <h2>策划部</h2>
        <p>部门职责</p>
        <ol>
          <li>负责公司产品及项目系统的功能开发、代码优化；</li>
          <li>负责项目组人员任务的分配与监督，及时解决项目技术问题；</li>
          <li>参与系统需求分析与设计，并负责完成PHP核心代码，接口规范制定，架构设计。</li>
        </ol>
        <p>任职要求</p>
        <ol>
          <li>精通PHP+MySql+Apache开发，精通使用JavaScript、AJAX、JQuery等技术；3年以上WEB应用程序开发经验， 有大型网站或电子商务网站工作经验者优先；</li>
          <li>熟悉jQuery，具有AJAX、HTML、CSS、JAVASCRIPT等方面的开发经验；</li>
        </ol>
        <button class="center-block btn btn-warning btn-lg">投递简历</button>
      </div>
    </div>
  </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
  name: "JobChance",
  data() {
    return {};
  },
  mounted(){
    var wow = new WOW();
    wow.init();
  }
};
</script>
<style scoped>
.banner {
  color: #fff;
  font-size: 30px;
  height: 150px;
  line-height: 150px;
  background-image: url("../assets/img/banner_2.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: scroll;
  background-position: center center;
}
.JobChance-container {
  margin: 100px;
  padding: 30px;
  transition: all ease 0.5s;
  border: 1px dashed salmon;
}
.JobChance-container h2{
  color: rgb(255, 102, 19);
  font-weight: bolder;
  text-align: center;
}
.JobChance-container p{
font-size: 20px;
  color: rgb(255, 102, 19);
  font-weight: 700;
}
.JobChance-container ol{
    list-style-type: decimal;
    padding-left: 30px;
}
.JobChance-container ol>li{
    font-size: 14px;
    line-height: 2.7rem;
}
@media screen and (max-width: 997px) {
  .JobChance-container {
    margin: 20px 0;
    padding: 20px;
    border: 1px dashed salmon;
  }
}
</style>

