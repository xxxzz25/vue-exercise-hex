<template>
  <nav class="col-md-2 d-none d-md-block bg-light sidebar">
    <div class="sidebar-sticky">
      <h6 class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted">
        <span>管理員</span>
        <a class="d-flex align-items-center text-muted" href="javascript:;">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column">
        <li class="nav-item">
          <router-link class="nav-link" to="/admin/">
            產品列表
          </router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/admin/orders">
            訂單列表
          </router-link>
        </li>
        <li class="nav-item">
          <router-link class="nav-link" to="/admin/coupons">
            優惠券
          </router-link>
        </li>
      </ul>
      <h6 class="sidebar-heading d-flex justify-content-between align-items-center px-3 mt-4 mb-1 text-muted">
        <span>模擬功能</span>
        <a class="d-flex align-items-center text-muted" href="javascript:;">
          <span data-feather="plus-circle"></span>
        </a>
      </h6>
      <ul class="nav flex-column">
        <li class="nav-item">
          <router-link class="nav-link" to="/admin/customer_order">
            模擬訂單
          </router-link>
        </li>
      </ul>
    </div>
  </nav>
</template>
