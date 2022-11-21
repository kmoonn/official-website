<template>
  <div id="footer" class="container-fluid">
    <div class="logo">
      <img src="@/assets/img/logo_white.png" alt="logo图">
    </div>
    <p class="title">武汉理工大学电子商务协会</p>
    <p class="address_tel_fax">
      <span>地址：湖北省武汉市洪山区珞狮路122号</span>
      <span>Tel：027-888-888</span>
      <span>Fax：8888-88888888</span>
    </p>
    <p class="email_wx">
      <span>邮箱：ECA@whut.edu.cn</span>
      <span>官微：Whut_ECA</span>
      <span>官Q：914961298</span>
    </p>
    <p class="copy">Copyright &copy; 2020 - 2022 武汉理工大学电子商务协会</p>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {};
  }
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  background: #474747;
  overflow: hidden;
  text-align: center;
}
.logo {
  width: 95px;
  height: 45px;
  margin: 50px auto 20px;
}
.title {
  font-size: 25px;
  margin-bottom: 20px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 50px 0 10px;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {

  font-size: 12px;
}
.copy {
  font-size: 12px;
  margin: 30px 0 10px;
}
}
</style>

