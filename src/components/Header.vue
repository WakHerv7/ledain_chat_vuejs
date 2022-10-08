<template>
  <nav class="navbar navbar_wh default-layout col-lg-12 col-12 p-0 fixed-top d-flex align-items-top flex-row">
      <div class="text-center navbar-brand-wrapper d-flex align-items-center justify-content-start">
        <div class="me-3 sidebar_toggler_wh">
          <button class="navbar-toggler navbar-toggler align-self-center" type="button" data-bs-toggle="minimize">
            <!-- <span class="icon-menu"></span> -->
            <i class="mdi mdi-chevron-left"></i>
          </button>
        </div>
        <div>
          <a class="navbar-brand brand-logo logo_container_wh" href="index.html">
            <img src="@/assets/logo_ledain.jpg" alt="logo" />
          </a>
          <!-- <a class="navbar-brand brand-logo-mini" href="index.html">
            <img src="images/logo-mini.svg" alt="logo" />
          </a> -->
        </div>
      </div>
      <div class="navbar-menu-wrapper d-flex align-items-top">         
        <ul class="navbar-nav ms-auto">
          <!-- <li class="nav-item d-none d-lg-block">
            <div id="datepicker-popup" class="input-group date datepicker navbar-date-picker">
              <span class="input-group-addon input-group-prepend border-right">
                <span class="icon-calendar input-group-text calendar-icon"></span>
              </span>
              <input type="text" class="form-control">
            </div>
          </li> -->
          <li class="nav-item">
            <form class="search-form" action="#">
              <i class="icon-search"></i>
              <input type="search" class="form-control" placeholder="Search Here" title="Search here">
            </form>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link count-indicator" id="notificationDropdown" href="#" data-bs-toggle="dropdown">
              <i class="icon-mail icon-lg"></i>
            </a>
            <div class="dropdown-menu dropdown-menu-right navbar-dropdown preview-list pb-0" aria-labelledby="notificationDropdown">
              <a class="dropdown-item py-3 border-bottom">
                <p class="mb-0 font-weight-medium float-left">You have 4 new notifications </p>
                <span class="badge badge-pill badge-primary float-right">View all</span>
              </a>
              <a class="dropdown-item preview-item py-3">
                <div class="preview-thumbnail">
                  <i class="mdi mdi-alert m-auto text-primary"></i>
                </div>
                <div class="preview-item-content">
                  <h6 class="preview-subject fw-normal text-dark mb-1">Application Error</h6>
                  <p class="fw-light small-text mb-0"> Just now </p>
                </div>
              </a>
              <a class="dropdown-item preview-item py-3">
                <div class="preview-thumbnail">
                  <i class="mdi mdi-settings m-auto text-primary"></i>
                </div>
                <div class="preview-item-content">
                  <h6 class="preview-subject fw-normal text-dark mb-1">Settings</h6>
                  <p class="fw-light small-text mb-0"> Private message </p>
                </div>
              </a>
              <a class="dropdown-item preview-item py-3">
                <div class="preview-thumbnail">
                  <i class="mdi mdi-airballoon m-auto text-primary"></i>
                </div>
                <div class="preview-item-content">
                  <h6 class="preview-subject fw-normal text-dark mb-1">New user registration</h6>
                  <p class="fw-light small-text mb-0"> 2 days ago </p>
                </div>
              </a>
            </div>
          </li>
          <li class="nav-item dropdown"> 
            <a class="nav-link count-indicator" id="countDropdown" href="#" data-bs-toggle="dropdown" aria-expanded="false">
              <i class="icon-bell"></i>
              <span class="count"></span>
            </a>
            <div class="dropdown-menu dropdown-menu-right navbar-dropdown preview-list pb-0" aria-labelledby="countDropdown">
              <a class="dropdown-item py-3">
                <p class="mb-0 font-weight-medium float-left">You have 7 unread mails </p>
                <span class="badge badge-pill badge-primary float-right">View all</span>
              </a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item preview-item">
                <div class="preview-thumbnail">
                  <img src="images/faces/face10.jpg" alt="image" class="img-sm profile-pic">
                </div>
                <div class="preview-item-content flex-grow py-2">
                  <p class="preview-subject ellipsis font-weight-medium text-dark">Marian Garner </p>
                  <p class="fw-light small-text mb-0"> The meeting is cancelled </p>
                </div>
              </a>
              <a class="dropdown-item preview-item">
                <div class="preview-thumbnail">
                  <img src="images/faces/face12.jpg" alt="image" class="img-sm profile-pic">
                </div>
                <div class="preview-item-content flex-grow py-2">
                  <p class="preview-subject ellipsis font-weight-medium text-dark">David Grey </p>
                  <p class="fw-light small-text mb-0"> The meeting is cancelled </p>
                </div>
              </a>
              <a class="dropdown-item preview-item">
                <div class="preview-thumbnail">
                  <img src="images/faces/face1.jpg" alt="image" class="img-sm profile-pic">
                </div>
                <div class="preview-item-content flex-grow py-2">
                  <p class="preview-subject ellipsis font-weight-medium text-dark">Travis Jenkins </p>
                  <p class="fw-light small-text mb-0"> The meeting is cancelled </p>
                </div>
              </a>
            </div>
          </li>
          <li class="nav-item dropdown d-none d-lg-block user-dropdown">
            <a class="nav-link" id="UserDropdown" href="#" data-bs-toggle="dropdown" aria-expanded="false">
              <img class="img-xs rounded-circle" src="images/faces/face8.jpg" alt="Profile image"> </a>
            <div class="dropdown-menu dropdown-menu-right navbar-dropdown" aria-labelledby="UserDropdown">
              <div class="dropdown-header text-center">
                <img class="img-md rounded-circle" src="images/faces/face8.jpg" alt="Profile image">
                <p class="mb-1 mt-3 font-weight-semibold">Allen Moreno</p>
                <p class="fw-light text-muted mb-0">allenmoreno@gmail.com</p>
              </div>
              <a class="dropdown-item"><i class="dropdown-item-icon mdi mdi-account-outline text-primary me-2"></i> My Profile <span class="badge badge-pill badge-danger">1</span></a>
              <a class="dropdown-item"><i class="dropdown-item-icon mdi mdi-message-text-outline text-primary me-2"></i> Messages</a>
              <a class="dropdown-item"><i class="dropdown-item-icon mdi mdi-calendar-check-outline text-primary me-2"></i> Activity</a>
              <a class="dropdown-item"><i class="dropdown-item-icon mdi mdi-help-circle-outline text-primary me-2"></i> FAQ</a>
              <a class="dropdown-item"><i class="dropdown-item-icon mdi mdi-power text-primary me-2"></i>Sign Out</a>
            </div>
          </li>
        </ul>
        <button class="navbar-toggler navbar-toggler-right d-lg-none align-self-center" type="button" data-bs-toggle="offcanvas">
          <span class="mdi mdi-menu"></span>
        </button>
      </div>
    </nav>
</template>

<script>
export default {
  name: 'HeaderItem',
  props: {
    //...
  }
}
</script>

<style scoped>
  .navbar_wh {
    /* background: #231f20 !important; */
  }
  .navbar .navbar-menu-wrapper {
    /* background: transparent !important; */
    background: #231f20 !important;
    color: white !important;
    width: calc(100% - 240px);
  }
  .navbar .navbar-menu-wrapper i,
  .navbar .navbar-menu-wrapper input {
    color: white !important;
  }
  .navbar .navbar-brand-wrapper {
    /* background: transparent !important; */
    background: #231f20 !important;
    color: white !important;
    position: relative;
    /* max-width: 240px;
    width: unset */
    width: 240px;
    padding-left: 15px !important;
  }
  .sidebar-icon-only .navbar .navbar-brand-wrapper {
    width: 90px;
  }
  .sidebar-icon-only .navbar .navbar-menu-wrapper {
    width: calc(100% - 90px);
  }

  .logo_container_wh {
    margin:10px 0;
    height:70px;
    width:70px;
    overflow:hidden;
    display:flex;
    justify-content:center;
    align-items:center;
    border-radius: 7px;
  }
  .logo_container_wh img {
    height:100% !important;
    width:auto !important;
    object-fit:cover;
  }
  .sidebar_toggler_wh {
    position: absolute;
    top: 10px !important;
    right: 5px !important;
  }

  .sidebar-icon-only .navbar .navbar-brand-wrapper .brand-logo {
    display: flex;
    height:50px;
    width:50px;
    align-items:flex-end;
    margin-top: 35px;
  }
  .sidebar-icon-only .navbar .navbar-brand-wrapper .sidebar_toggler_wh{
    top: 5px !important;
    right: -5px !important;
  }
  .navbar .navbar-brand-wrapper .navbar-toggler:not(.navbar-toggler-right) {
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0));
    border-radius: 50%;
    width: 30px;
    height: 30px;
    font-size: 15px;
  }
  .sidebar-icon-only .navbar .navbar-brand-wrapper .navbar-toggler:not(.navbar-toggler-right) {
    background: #000;
    background-image: unset;
    width: 25px;
    height: 25px;
  }


  .sidebar-icon-only .navbar .navbar-brand-wrapper {
    background-image: linear-gradient(to left, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0)) !important;
  }


  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown {
    background: #231f20;
    border-radius: 10px;
    /* color: white; */
  }
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a:hover {
    background: rgba(255, 255, 255, 0.3);
  }
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a:last-child {
    border-bottom: none;
  }
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a,
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a h6,
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a p {
    color: white !important;
  }
  .navbar .navbar-menu-wrapper .navbar-nav .nav-item.dropdown .navbar-dropdown a i {
    color: #a8e863 !important;
  }

  .badge-primary {
    color: #a8e863;
    border: 1px solid #a8e863;
  }
</style>
