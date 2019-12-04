<template>
  <nav
    id="navbar-main"
    class="navbar navbar-main navbar-expand-lg navbar-transparent navbar-dark navbar-theme-primary headroom py-lg-2 px-lg-6"
  >
    <div class="container">
      <a class="navbar-brand" href="index.html">
        Logo
      </a>
      <div id="navbar_global" class="navbar-collapse collapse">
        <div class="navbar-collapse-header">
          <div class="row">
            <div class="col-6 collapse-brand">
              <a href="index.html">
                <img src="img/brand/primary.svg" alt="menuimage">
              </a>
            </div>
            <div class="col-6 collapse-close">
              <a
                href="#navbar_global"
                class="fas fa-times"
                data-toggle="collapse"
                data-target="#navbar_global"
                aria-controls="navbar_global"
                aria-expanded="false"
                aria-label="Toggle navigation"
              />
            </div>
          </div>
        </div>
        <ul class="navbar-nav navbar-nav-hover ml-3">
          <li class="nav-item">
            <a href="index.html" class="nav-link">
              <span class="nav-link-inner-text">首页</span>
            </a>
          </li>
          <li class="nav-item">
            <a href="index.html" class="nav-link">
              <span class="nav-link-inner-text">走进万企</span>
            </a>
          </li>
          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown">
              <span class="nav-link-inner-text">产品与咨询</span>
              <i class="fas fa-angle-down nav-link-arrow" />
            </a>
            <ul class="dropdown-menu">
              <li class="nav-item"><a href="#" class="dropdown-item">资质认证服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">知识产权服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">项目申报服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">财税服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">体系认证服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">综合产品与咨询</a></li>
            </ul>
          </li>

          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown">
              <span class="nav-link-inner-text">政策专栏</span>
              <i class="fas fa-angle-down nav-link-arrow" />
            </a>
            <div class="dropdown-menu dropdown-menu-lg">
              <div class="col-auto px-0" data-dropdown-content>
                <div class="list-group list-group-flush">
                  <a
                    href="docs/introduction.html"
                    class="list-group-item list-group-item-action d-flex align-items-center p-0 py-3 px-lg-4"
                  >
                    <span class="icon icon-sm icon-tertiary">
                      <i class="fas fa-file-alt" />
                    </span>
                    <div class="ml-4">
                      <span class="text-dark d-block">
                        高新认证
                        <span class="badge badge-sm badge-tertiary ml-2">v1.1</span>
                      </span>
                      <span class="small">高新企业认证说明</span>
                    </div>
                  </a>
                  <a
                    href="https://themesberg.com/contact"
                    target="_blank"
                    class="list-group-item list-group-item-action d-flex align-items-center p-0 py-3 px-lg-4"
                  >
                    <span class="icon icon-sm icon-primary">
                      <i class="fas fa-microphone-alt" />
                    </span>
                    <div class="ml-4">
                      <span class="text-dark d-block">中国版权</span>
                      <span class="small">中国版权说明</span>
                    </div>
                  </a>
                </div>
              </div>
            </div>
          </li>

          <li class="nav-item dropdown">
            <a href="#" class="nav-link" data-toggle="dropdown">
              <span class="nav-link-inner-text">招贤纳士</span>
              <i class="fas fa-angle-down nav-link-arrow" />
            </a>
            <ul class="dropdown-menu">
              <li class="nav-item"><a href="#" class="dropdown-item">资质认证服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">知识产权服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">项目申报服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">财税服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">体系认证服务</a></li>
              <li class="nav-item"><a href="#" class="dropdown-item">综合产品与咨询</a></li>
            </ul>
          </li>

          <li class="nav-item">
            <a href="index.html" class="nav-link">
              <span class="nav-link-inner-text">联系我们</span>
            </a>
          </li>
        </ul>
      </div>

      <div class="d-flex align-items-center">
        <button
          class="navbar-toggler ml-2"
          type="button"
          data-toggle="collapse"
          data-target="#navbar_global"
          aria-controls="navbar_global"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon" />
        </button>
      </div>
    </div>
  </nav>
</template>
