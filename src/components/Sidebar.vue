<template>
  <nav class="sidebar sidebar-offcanvas sidebar_wh" id="sidebar">
        <ul class="nav">
          <!-- <li class="nav-item">
            <a class="nav-link" href="index.html">
              <i class="mdi mdi-grid-large menu-icon"></i>
              <span class="menu-title">Dashboard</span>
            </a>
          </li> -->
          <li class="nav-item nav-category"><span>Menu</span></li>
          <li class="nav-item active">
            <a class="nav-link" href="#">
              <i class="menu-icon mdi mdi-floor-plan"></i>
              <span class="menu-title">Tableau de bord</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="menu-icon mdi mdi-account-multiple"></i>
              <span class="menu-title">Clients</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="menu-icon mdi mdi-web"></i>
              <span class="menu-title">Communication</span>
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <i class="menu-icon mdi mdi-settings"></i>
              <span class="menu-title">Paramètres</span>
            </a>
          </li>
          <li class="nav-item nav-category">
            <span>Communication</span>
            <div class="directional_buttons_wh">
              <button class="sidebar_arrow_button_wh">
                <i class="mdi mdi-chevron-left"></i>
              </button>
              <button class="sidebar_arrow_button_wh">
                <i class="mdi mdi-chevron-right"></i>
              </button>
            </div>
          </li>
          <div class="communication_sidebar_wh">
            <li class="nav-item">
              <a class="nav-link" href="#">
                <div class="nav_item_left_wh">
                  <div class="img_container_wh" >
                    <img src="images/faces/face1.jpg" alt="profile" />
                  </div>
                  <div class="bubble_gradient notif_bubble">2</div>
                </div>              
                <span class="menu-title">Brandon Washington</span>
                <div>
                  <div class="menu-icon bubble_gradient ml_w_10">2</div>
                </div>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <div class="nav_item_left_wh">
                  <div class="img_container_wh" >
                  <img src="images/faces/face1.jpg" alt="profile" />
                </div>
                </div>              
                <span class="menu-title">Brandon Washington</span>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <div class="nav_item_left_wh">
                  <div class="img_container_wh" >
                  <img src="images/faces/face1.jpg" alt="profile" />
                </div>
                <div class="bubble_gradient notif_bubble">10</div>
                </div>              
                <span class="menu-title">Brandon Washington</span>
                <div>
                  <div class="menu-icon bubble_gradient ml_w_10">10</div>
                </div>
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">
                <div class="nav_item_left_wh">
                  <div class="img_container_wh" >
                  <img src="images/faces/face1.jpg" alt="profile" />
                  <div class="bubble_gradient notif_bubble">5</div>
                </div>
                </div>              
                <span class="menu-title">Brandon Washington</span>
                <div>
                  <div class="menu-icon bubble_gradient ml_w_10">5</div>
                </div>
              </a>
            </li>

            <!-- //////////////// -->
            <div class="see_more_btn_wh">
              <i class="mdi mdi-chevron-down"></i>
              <span>Tous les messages</span>
            </div>
          </div>
          <!-- <li class="nav-item nav-category">pages</li>
          <li class="nav-item">
            <a class="nav-link" data-bs-toggle="collapse" href="#auth" aria-expanded="false" aria-controls="auth">
              <i class="menu-icon mdi mdi-account-circle-outline"></i>
              <span class="menu-title">User Pages</span>
              <i class="menu-arrow"></i>
            </a>
            <div class="collapse" id="auth">
              <ul class="nav flex-column sub-menu">
                <li class="nav-item"> <a class="nav-link" href="pages/samples/login.html"> Login </a></li>
              </ul>
            </div>
          </li> -->
          <li class="nav-item nav-category"></li>
          <li class="nav-item">
            <a class="nav-link" href="#">
              <!-- <i class="menu-icon mdi mdi-arrow-left-bold-circle"></i> -->
              <div class="menu-icon-left bubble_gradient ">
                <i class="mdi mdi-arrow-left"></i>
              </div>
              <span class="menu-title mr_w_10">Déconnexion</span>
            </a>
          </li>
        </ul>
  </nav>
</template>

<script>
export default {
  name: 'SidebarItem',
  props: {
    //...
  }
}
</script>

<style scoped>
  .sidebar {
    padding-top: 10px;
    /* width: unset; */
  }
.sidebar_wh {
  background: #231f20 !important;
  color: white !important;
  max-width: 240px;
  width: 240px;
  transition: width 0.25s ease !important;
}
.sidebar-icon-only .sidebar {
  width: 90px;
  background-image: linear-gradient(to left, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0)) !important;
}
.sidebar_wh .nav {
  padding-left: 10px;
  padding-right: 10px;
}
.sidebar .nav .nav-item.nav-category {
  border-top: 1px solid rgba(255, 255, 255, 0.3);
  color: white !important;
  margin-left: 10px !important;
  padding-top: 10px !important;
  position: relative;
}
.directional_buttons_wh {
  position: absolute;
  top: 50%;
  right: -30px;
  transform: translateY(-50%);
  display: flex;
  gap: 10px;
}
.sidebar-icon-only .sidebar .directional_buttons_wh{
  display: none;
}
.sidebar .nav .nav-item .nav-link .menu-title {
  color: white !important;
}
.sidebar .nav .nav-item > .nav-link {
  border-radius: 10px !important;
  font-weight: bolder;
  cursor: pointer;
  padding-left: 10px !important;
}
.sidebar .nav .nav-item:hover > .nav-link,
.sidebar .nav .nav-item.active > .nav-link {
  background: #A7E863;
  
}
.sidebar .nav .nav-item > .nav-link i, .sidebar .nav .nav-item > .nav-link .menu-title, .sidebar .nav .nav-item > .nav-link .menu-arrow {
  color: white !important;
}
.sidebar .nav .nav-item > .nav-link i {
  color: #A7E863 !important;
}
.sidebar .nav .nav-item:hover  > .nav-link i {
  color: white !important;
}
.sidebar .nav .nav-item.active > .nav-link i, .sidebar .nav .nav-item.active > .nav-link .menu-title, .sidebar .nav .nav-item.active > .nav-link .menu-arrow {
  color: white !important;
}
.sidebar-icon-only .sidebar .nav .nav-item.active .nav-link:before {
  display: none;
}
.sidebar-icon-only .sidebar .nav .nav-item.hover-open .nav-link:hover .menu-title{
  color: white !important;
  background: #231f20 !important;
}

.nav_item_left_wh {
  position: relative;
  margin-right: 10px;
}
.img_container_wh {
    /* margin:10px 0; */
    height:30px;
    width:30px;
    overflow:hidden;
    display:flex;
    justify-content:center;
    align-items:center;
    border-radius: 50%;
  }
  .img_container_wh img {
    height:100% !important;
    width:auto !important;
    object-fit:cover;
  }

  .communication_sidebar_wh {
    /* background: rgba(255, 255, 255, 0.251); */
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0));
    border-radius: 10px;
    padding: 5px;
    padding-bottom: 20px;
    margin-bottom: 15px;
    position: relative;
  }
  .communication_sidebar_wh .see_more_btn_wh {
    position: absolute;
    bottom: -15px;
    left: 50%;
    transform: translateX(-50%);
    height: 30px;
    width: 90%;
    background: #A7E863;
    border-radius: 10px;
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 5px;
    color: #fff !important;
    font-weight: bolder;
  }
  .communication_sidebar_wh .see_more_btn_wh i {
    color: #fff !important;
    font-size: 24px;
    line-height: 24px;
  }
  .sidebar-icon-only .sidebar .communication_sidebar_wh .see_more_btn_wh span{
    display: none;
  }
  .notif_bubble {
    position: absolute;
    top: -10px;
    right: -10px;    
  }
  .bubble_gradient {
    height: 17px;
    width: 17px;
    border-radius: 50%;
    color: white;
    font-size: 10px;
    font-weight: bolder;
    background-image: linear-gradient(to bottom, #a8e863e6, #a8e86300);
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .bubble_gradient.menu-icon,
  .bubble_gradient.menu-icon-left {
    height: 22px;
    width: 22px;
    color: #fff !important;
    font-weight: bolder;
  }
  .bubble_gradient.menu-icon-left {
    margin-right: 15px !important;
  }
  .bubble_gradient.menu-icon i,
  .bubble_gradient.menu-icon-left i{
    color: #fff !important;
    font-size: 18px;
  }
  .ml_w_10 {
    margin-left: 10px;
  }
  .mr_w_10 {
    margin-right: 10px !important;
  }
  .sidebar .bubble_gradient.notif_bubble {
    display: none;
  }
  .sidebar .menu-icon.bubble_gradient {
    display: flex;
  }
  .sidebar-icon-only .bubble_gradient.notif_bubble {
    display: flex;
  }
  .sidebar-icon-only .menu-icon.bubble_gradient {
    display: none;
  }
  
  .sidebar-icon-only .bubble_gradient.menu-icon-left {
    margin-right: 0px !important;
    margin-left: 13px !important;
  }
  .sidebar .nav .nav-item.nav-category {
    transition: all 0.25s ease;
  }
  .sidebar-icon-only .sidebar .nav .nav-item.nav-category {
    display: block;
    /* background: coral; */
    width: 100%;
    padding: 5px 0px;
    
    margin-top: 15px;
    margin-left: 0 !important;
    text-align: center;
  }
  .sidebar-icon-only .sidebar .nav .nav-item.nav-category:nth-child(3) {
    /* border-top: none; */
  }
  .sidebar-icon-only .sidebar .nav .nav-item.nav-category span{
    /* display: none; */
    font-size: 8px;
  }

  /* COMMUNICATION buttons */
  .sidebar_arrow_button_wh {
    background: linear-gradient(to bottom, rgba(255, 255, 255, 0.2), rgba(255, 255, 255, 0));
    border-radius: 50%;
    width: 25px;
    height: 25px;
    font-size: 15px;
    position: relative;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .sidebar_arrow_button_wh:active {
    background: #231f20;
  }
  .sidebar_arrow_button_wh i{
    color: #fff;
  }
</style>
