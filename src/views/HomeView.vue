<template>
  <!--navbar-->
  <nav class="navbar navbar-expand-lg" dir="rtl">
    <div class="container-fluid">
      <img class="logo1" src="../../public/logo1.svg">

      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link " href="#">الرئيسيه</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              التخصصات
            </a>

            <!--dropdown menu-->
            <ul class="dropdown-menu ">
              <li class="dropdown"><a class="nav-link title" href="#">الفئات</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">المرحله
                  الأعداديه</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">المرحله
                  الثانويه</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">كورسات لغات</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">كورسات اداره اعمال</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">كورسات تصميم</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">كورسات برمجه</a></li>
              <li class="dropdown"><a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown"
                  aria-expanded="false">ICDL كورسات</a></li>
              <li class="nav-item">

                <button type="button" class="btn-bt">تصفح جميع التخصصات</button>
              </li>
            </ul>


          </li>

          <li class="nav-item">
            <a class="nav-link" href="#">التواصل</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">تسجيل الدخول</a>
          </li>
        </ul>

        <!--create new account btn-->
        <button type="button" class="btn">انشاء حساب جديد</button>

      </div>
    </div>
  </nav>

  <!--container-->
  <div class="row align-items-center" dir="rtl">
    <div class="col-12 col-lg-8">
      <div class="row">
        <div class="col-12">
          <p>منصة المعلم تقدم لكم التعليم أون لاين من خلال الموقع الالكتروني </p>
        </div>
        <div class="col-12">
          <p class="p">نقدم دورات تعليمة للمرحلة الاعدادية و المراحلة الثانويه , و كورسات عامة لتعليم اللغات و ومهارات
            الكمبيوتر
            وغيرها .</p>
        </div>

        <div class="col-12">
          <button type="button" class="btn-btn">أشترك الأن</button>
        </div>
      </div>
    </div>
    <div class="col-12 col-lg-4">
      <img src="../../public/VR glasses.svg">
    </div>

    <!--search bar-->
    <div class="col-12 form">


      <div class="input-group mb-3">
        <button class="input-group-text search">Search</button>
        <div class="form-floating">
          <input type="text" class="form-control" id="floatingInputGroup1" placeholder="Username">
          <label for="floatingInputGroup1">Username</label>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.nav-link {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 27px;
  text-align: center;
  color: #FFFFFF;
}

.title {
  font-weight: 700;
}

.logo1 {
  right: 6.25%;
  top: 8.98%;
  bottom: 38.61%;
  color: #4EAABF;
}

.btn {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 400;
  font-size: 24px;
  line-height: 27px;
  text-align: center;
  color: #FFFFFF;
  width: 262px;
  height: 62px;
  left: 73px;
  top: 69px;
  background: #4EAABF;
  box-shadow: 2px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 20px;
}

.dropdown-menu {
  background: #4EAABF;
  border-radius: 10px;
  width: 380px;

}

.dropdown-menu>li {
  display: flex;
  padding: 0 36px;
}

.search {
  width: 192px;

  background: #4EAABF;
  border-radius: 20px !important;
}

.dropdown-item {
  width: 173px;

  top: 169px;
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 700;
  font-size: 25px;
  line-height: 28px;
  text-align: center;
  color: #FFFFFF;
}

.dropdown-toggle {
  left: 33.33%;
  right: 35.83%;
  top: 25%;
  bottom: 25%;
}

.btn-bt {
  width: 280px;
  height: 54px;

  background: #303159;
  border-radius: 10px;
  /*margin: 15px 40px;*/

  color: #FFFFFF
}

p {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 400;
  font-size: 40px;
  line-height: 45px;
  text-align: right;
  color: #FFFFFF;
}

.btn-btn {
  background: #4EAABF;
  box-shadow: 2px 4px 4px rgba(0, 0, 0, 0.25);
  border-radius: 20px;
  width: 219px;
  height: 77px;
  margin-right: 272px;
  margin-top: 51px;
  float: right;
}

@media only screen and (max-width: 821px) {
  .btn-btn {
    margin-right: 0px;
  }

  form {
    margin: 0 !important;
  }
}

input {
  background: #FFFFFF;
  border-radius: 20px;
  width: 800px;
  height: 73px;
}

.form {
  margin-top: 101px;
}

form {
  margin: 101px 244px;
}

.btnn {
  width: 192px;
  height: 73px;
  background: #4EAABF;
  border-radius: 20px;
}

.p {
  font-family: 'Almarai';
  font-style: normal;
  font-weight: 400;
  font-size: 30px;
  line-height: 33px;
  text-align: right;
  color: #FFFFFF;
}
</style>