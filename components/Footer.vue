<template>
  <footer class="footer section bg-dark text-white">
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <a
            class="footer-brand"
            href="./index.html"
          >Logo</a>
          <p class="mt-4 text-gray">
            公司的简要介绍，主要优势等。公司的简要介绍，主要优势等。公司的简要介绍，主要优势等。公司的简要介绍，主要优势等。
          </p>

          <!-- 社交图标 -->
          <ul class="social-buttons mb-5 mb-lg-0">
            <li>
              <a
                href="https://twitter.com/themesberg"
                target="_blank"
                rel="nofollow"
                class="btn btn-lg btn-link btn-twitter text-white"
                data-toggle="tooltip"
                data-placement="top"
                title=""
                data-original-title="Follow us on Twitter"
              ><i class="fab fa-twitter" /></a>
            </li>
            <li>
              <a
                href="https://www.facebook.com/themesberg"
                target="_blank"
                rel="nofollow"
                class="btn btn-lg btn-link btn-facebook text-white"
                data-toggle="tooltip"
                data-placement="top"
                title=""
                data-original-title="Like us on Facebook"
              ><i class="fab fa-facebook" /></a>
            </li>
            <li>
              <a
                href="https://github.com/themesberg"
                target="_blank"
                rel="nofollow"
                class="btn btn-lg btn-link btn-github text-white"
                data-toggle="tooltip"
                data-placement="top"
                title=""
                data-original-title="Star us on Github"
              ><i class="fab fa-github" /></a>
            </li>
            <li>
              <a
                href="https://dribbble.com/themesberg"
                target="_blank"
                rel="nofollow"
                class="btn btn-lg btn-link btn-dribbble text-white"
                data-toggle="tooltip"
                data-placement="top"
                title=""
                data-original-title="Like us on Dribbble"
              ><i class="fab fa-dribbble" /></a>
            </li>
          </ul>
        </div>
        <div class="col-sm-6 col-md-3 col-lg-2 mt-4 mt-md-0">
          <h6 class="font-weight-normal">
            关于我们
          </h6>
          <ul class="links-vertical">
            <li><a class="text-gray" href="#" target="_blank">企业介绍</a></li>
            <li><a class="text-gray" href="#" target="_blank">企业文化</a></li>
            <li><a class="text-gray" href="#" target="_blank">发展历程</a></li>
            <li><a class="text-gray" href="#" target="_blank">企业荣誉</a></li>
          </ul>
        </div>
        <div class="col-sm-6 col-md-3 col-lg-3 mt-4 mt-md-0">
          <h6 class="font-weight-normal">
            产品与咨询
          </h6>
          <ul class="links-vertical">
            <li><a class="text-gray" href="#">资质认证服务</a></li>
            <li><a class="text-gray" href="#">知识产权服务</a></li>
            <li><a class="text-gray" href="#">项目申报服务</a></li>
            <li><a class="text-gray" href="#">财税服务</a></li>
            <li><a class="text-gray" href="#">体系认证服务</a></li>
            <li><a class="text-gray" href="#">综合产品与咨询</a></li>
          </ul>
        </div>
        <div class="col-md-3 col-lg-4 col-xl-4 mt-3 mt-lg-0 mt-4 mt-md-0">
          <h6 class="font-weight-normal">
            联系我们
          </h6>
          <p class="text-gray">
            公司地址：公司地址公司地址公司地址公司地址
          </p>
          <form>
            <div class="form-row">
              <div class="col-12">
                <input
                  type="tel"
                  class="form-control mb-2"
                  placeholder="电话号码"
                  name="tel"
                  required=""
                >
              </div>
              <div class="col-12">
                <button
                  type="submit"
                  class="btn btn-secondary shadow-soft btn-block"
                  data-loading-text="Sending"
                >
                  <span>联系我们</span>
                </button>
              </div>
            </div>
          </form>
          <small
            class="text-gray mt-3 form-text"
          >We’ll never share your details. See our
            <a
              class="text-light"
              href="./html/pages/legal.html"
            >Privacy Policy</a></small>
        </div>
      </div>
      <hr>
      <div class="copyright text-center mt-5">
        ©2019 <span>All rights reserved.</span>
      </div>
    </div>
  </footer>
</template>

<style>
.footer {
  display: flex;
  position: relative;
}
.footer ul {
  margin-bottom: 0;
  padding: 0;
  list-style: none;
}
.footer ul li {
  display: inline-block;
}
.footer ul li a {
  text-decoration: none;
  position: relative;
  display: block;
  font-weight: 300;
}
.footer ul li .btn {
  margin: 0;
}
.footer ul.links-horizontal:first-child a {
  padding-left: 0;
}
.footer ul.links-horizontal:last-child a {
  padding-right: 0;
}
.footer ul.links-vertical li {
  display: block;
  margin-left: -5px;
  margin-right: -5px;
}
.footer ul.links-vertical li a {
  padding: 5px;
}
.footer ul.links-vertical li a:hover {
  color: inherit !important;
}
.footer ul.icon-box i {
  line-height: 1.7;
}
.footer .social-buttons .btn,
.footer .social-buttons a {
  margin-top: 5px;
  margin-bottom: 5px;
  padding: 0.125rem 0.375rem;
}
.footer .footer-brand {
  font-size: 1.25rem;
  font-weight: 500;
}
.footer .footer-brand img,
.footer .footer-brand svg {
  height: 30px;
}
.footer .footer-brand:focus,
.footer .footer-brand:hover {
  color: #111;
}
.footer .copyright {
  font-size: 0.875rem;
}
.footer .pull-center {
  display: inline-block;
  float: none;
}
</style>
