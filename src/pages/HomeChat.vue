<template>
  <div class="container-scroller">
    
    <!-- partial:partials/_navbar.html -->
    <Header/>
    <!-- partial -->
    <div class="container-fluid page-body-wrapper">
      <!-- partial:partials/_settings-panel.html -->
      
      <!-- partial -->
      <!-- partial:partials/_sidebar.html -->
      <Sidebar/>
      <!-- partial -->
      
      <div class="main-panel">
        <div class="content-wrapper">
          <div class="row">
            <h3><span class="fw-bold">Messages</span></h3>
          </div>
          <div class="row">
            <div class="col-sm-12">
              <div class="home-tab">                
                <div class="tab-content tab-content-basic">
                  <div class="tab-pane fade show active" id="overview" role="tabpanel" aria-labelledby="overview"> 
                    
                    <div class="row chat_container">

                      <div class="col-lg-4 d-flex flex-column">                        
                        <div class="row flex-grow">
                          <div class="col-12 grid-margin stretch-card">
                            <div class="card card-rounded">
                              <div class="card-body">
                                <ul class="nav nav-tabs mb-3" role="tablist">
                                  <li class="nav-item">
                                    <a class="nav-link active ps-0" id="chats-tab" data-bs-toggle="tab" href="#chats" role="tab" aria-controls="chats" aria-selected="true">Chats</a>
                                  </li>
                                  <li class="nav-item">
                                    <a class="nav-link" id="chatmembers-tab" data-bs-toggle="tab" href="#chatmembers" role="tab" aria-selected="false">Members</a>
                                  </li>
                                  <li class="nav-item">
                                    <a class="nav-link" id="sharedfiles-tab" data-bs-toggle="tab" href="#sharedfiles" role="tab" aria-selected="false">Shared files</a>
                                  </li>
                                </ul>


                                <div class="tab-pane fade collapse show active" id="chats" role="tabpanel" aria-labelledby="chats"> 
                                  <div class="row">
                                    <div class="col-lg-12">
                                      <div class="d-flex justify-content-between align-items-center mb-3">
                                        <div class="chat_menu_title_container_wh">
                                          <h4 class="card-title card-title-dash">Chats</h4>
                                          <a href="#">
                                            <i class="mdi mdi-plus"></i>
                                            <span>New group</span>
                                          </a>
                                        </div>
                                      </div>
                                      <div class="mt-3 chat_list_container_wh">
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face1.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Brandon Washington</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small chat_list_item_rightside_wh">
                                            <div>
                                              <div class="bubble_gradient ml_w_10">2</div>
                                            </div>
                                            <span>1h ago</span>
                                          </div>
                                        </div>
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face2.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Wayne Murphy</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small chat_list_item_rightside_wh">
                                            1h ago
                                          </div>
                                        </div>
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face3.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Katherine Butler</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small chat_list_item_rightside_wh">
                                            <div>
                                              <div class="bubble_gradient ml_w_10">10</div>
                                            </div>
                                            <span>13min ago</span>
                                          </div>
                                        </div>
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face4.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Matthew Bailey</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between pt-2">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face5.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Rafell John</p>
                                              <small class="text-muted mb-0">Alaska, USA</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div class="tab-pane fade collapse" id="chatmembers" role="tabpanel" aria-labelledby="chatmembers"> 
                                  <div class="row">
                                    <div class="col-lg-12">
                                      <div class="d-flex justify-content-between align-items-center mb-3">
                                        <!-- <div>
                                          <h4 class="card-title card-title-dash">Members</h4>
                                        </div> -->
                                        <div class="chat_menu_title_container_wh">
                                          <h4 class="card-title card-title-dash">Members</h4>
                                          <a href="#">
                                            <i class="mdi mdi-plus"></i>
                                            <span>New member</span>
                                          </a>
                                        </div>
                                      </div>
                                      <div class="mt-3">
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face1.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Brandon Washington</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face2.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Wayne Murphy</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>
                                        
                                        
                                      </div>
                                    </div>
                                  </div>
                                </div>
                                <div class="tab-pane fade collapse" id="sharedfiles" role="tabpanel" aria-labelledby="sharedfiles"> 
                                  <div class="row">
                                    <div class="col-lg-12">
                                      <div class="d-flex justify-content-between align-items-center mb-3">
                                        <div>
                                          <h4 class="card-title card-title-dash">Shared Files</h4>
                                        </div>
                                      </div>
                                      <div class="mt-3">
                                        <div class="chat_list_item_wh wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face1.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Brandon Washington</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>                                       
                                        
                                      </div>
                                    </div>
                                  </div>
                                </div>



                              </div>
                            </div>
                          </div>
                        </div>
                      </div>


                      <div class="col-lg-8 d-flex flex-column">
                        <div class="row flex-grow">
                          <div class="col-12 grid-margin stretch-card">
                            <div class="card card-rounded chat_card_w no_bottom_padding">
                              <div class="card-body no_bottom_padding">
                                <main class="msger-chat" ref="msgerChat">
                                  <div class="msg left-msg">
                                    <div
                                    class="msg-img"
                                    style="background-image: url(images/faces/face2.jpg)"
                                    ></div>

                                    <div class="msg-bubble">
                                      <div class="msg-info">
                                        <div class="msg-info-name">BOT</div>
                                        <div class="msg-info-time">12:45</div>
                                      </div>

                                      <div class="msg-text">
                                        Hi, welcome to SimpleChat! Go ahead and send me a message. 😄
                                      </div>
                                    </div>
                                  </div>

                                  <div class="msg right-msg">
                                    <div
                                    class="msg-img"
                                    style="background-image: url(images/faces/face1.jpg)"
                                    ></div>

                                    <div class="msg-bubble">
                                      <div class="msg-info">
                                        <div class="msg-info-name">Sajad</div>
                                        <div class="msg-info-time">12:46</div>
                                      </div>

                                      <div class="msg-text">
                                        You can change your name in JS section!
                                      </div>
                                    </div>
                                  </div>
                                </main>

                                <form @submit="onSubmit" class="msger-inputarea" ref="msgerInputarea">
                                  <div class="msger-send-btn" ref="sendFileBtn" @click="getFile()"><i class="mdi mdi-paperclip"></i></div>
                                  <input type="file" ref="fileInputW" name="chat_file_item" hidden="hidden" id="chat_file_item" class="chat_file_item">
                                  <input type="text" class="msger-input" ref="msgerInput" placeholder="Enter your message...">
                                  <button type="submit" class="msger-send-btn"><i class="mdi mdi-send"></i></button>
                                </form>
                              </div>
                            </div>
                          </div>
                        </div>                          
                      </div>


                      
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <!-- content-wrapper ends -->
        <!-- partial:partials/_footer.html -->
        <!-- <Footer/> -->
        <!-- partial -->
      </div>
      <!-- main-panel ends -->
    </div>
    <!-- page-body-wrapper ends -->
  </div>
</template>

<script>
import Header from '../components/Header.vue'
import Sidebar from '../components/Sidebar.vue'
// import Footer from '../components/Footer.vue'
export default {
  name: 'HomeChat',
  components: {
    Header,
    Sidebar,
    // Footer
  },
  props: {
    //...
  },
  data () {
    return {
      BOT_IMG: "images/faces/face2.jpg",
      PERSON_IMG: "images/faces/face1.jpg",
      BOT_NAME: "BOT",
      PERSON_NAME: "Sajad",
      BOT_MSGS: [
      "Hi, how are you?",
      "Ohh... I can't understand what you trying to say. Sorry!",
      "I like to play games... But I don't know how to play!",
      "Sorry if my answers are not relevant. :))",
      "I feel sleepy! :("
    ],
    }
  },
  mounted() {
    this.$refs.msgerInput.addEventListener("keyup", this.onKeyup);
    this.$refs.fileInputW.addEventListener("change", this.sendInputFile);
  },
  beforeUnmount() {
    this.$refs.msgerInput.removeEventListener("keyup", this.onKeyup);
    this.$refs.fileInputW.removeEventListener("change", this.sendInputFile);
  },
  methods: {
    onKeyup(event) {
        if (event.which === 13) {
          this.onSubmit(event)
        }
    },
    onSubmit(e) {
      e.preventDefault();
      const msgText = this.$refs.msgerInput.value;
      if (!msgText) return;

      this.appendMessage(this.PERSON_NAME, this.PERSON_IMG, "right", msgText);
      this.$refs.msgerInput.value = "";

      this.botResponse();
      
    },
    appendMessage(name, img, side, text) {
      //   Simple solution for small apps
      const msgHTML = `
        <div class="msg ${side}-msg">
          <div class="msg-img" style="background-image: url(${img})"></div>

          <div class="msg-bubble">
            <div class="msg-info">
              <div class="msg-info-name">${name}</div>
              <div class="msg-info-time">${this.formatDate(new Date())}</div>
            </div>

            <div class="msg-text">${text}</div>
          </div>
        </div>
      `;
      this.$refs.msgerChat.insertAdjacentHTML("beforeend", msgHTML);
      this.$refs.msgerChat.scrollTop += 500;

    },
    botResponse() {
      const r = this.random(0, this.BOT_MSGS.length - 1);
      const msgText = this.BOT_MSGS[r];
      const delay = msgText.split(" ").length * 100;

      setTimeout(() => {
        this.appendMessage(this.BOT_NAME, this.BOT_IMG, "left", msgText);
      }, delay);
    },
    formatDate(date) {
      const h = "0" + date.getHours();
      const m = "0" + date.getMinutes();

      return `${h.slice(-2)}:${m.slice(-2)}`;
    },
    random(min, max) {
      return Math.floor(Math.random() * (max - min) + min);
    },
    getFile() {
      // e.preventDefault()
      this.$refs.fileInputW.click();
    },
    async sendInputFile() {
      let msgHTML="";
      if (this.$refs.fileInputW.files.length) {
        // updateThumbnail(dropZoneElement, inputElement.files[0]);
        if (this.$refs.fileInputW.files[0].type.startsWith("image/")) {
          const reader = new FileReader();
      
          reader.readAsDataURL(this.$refs.fileInputW.files[0]);
           reader.onload =  () => {
            // thumbnailElement.style.backgroundImage = `url('${reader.result}')`;
            msgHTML = `
              <div class="msg right-msg">
                <div class="msg-img" style="background-image: url(${this.PERSON_IMG})"></div>

                <div class="msg-bubble">
                  <div class="msg-info">
                    <div class="msg-info-name">${this.PERSON_NAME}</div>
                    <div class="msg-info-time">${this.formatDate(new Date())}</div>
                  </div>

                  <div class="msg-text">${this.$refs.fileInputW.files[0].type.toUpperCase().split("/")[1]}</div>
                  <div class="msg-text" style="margin:10px 0;height:150px;min-width:150px;max-width:250px;overflow:hidden;display:flex;justify-content:center;align-items:center">
                    <img src="${reader.result}" style="height:100%;width:auto;object-fit:cover;"/>
                  </div>
                  <div class="msg-text">${this.$refs.fileInputW.files[0].name}</div>
                  
                  
                </div>
              </div>
            `;

            this.$refs.msgerChat.insertAdjacentHTML("beforeend", msgHTML);
            this.$refs.msgerChat.scrollTop += 500;
            // this.appendImage(this.PERSON_NAME, this.PERSON_IMG, "right", this.$refs.fileInputW.files[0]);
            this.$refs.msgerInput.value = "";

            this.botResponse();
          };
          
        } else {
          msgHTML = `
              <div class="msg right-msg">
                <div class="msg-img" style="background-image: url(${this.PERSON_IMG})"></div>

                <div class="msg-bubble">
                  <div class="msg-info">
                    <div class="msg-info-name">${this.PERSON_NAME}</div>
                    <div class="msg-info-time">${this.formatDate(new Date())}</div>
                  </div>

                  <div class="msg-text">${this.$refs.fileInputW.files[0].type.toUpperCase().split("/")[1]}</div>
                  <div class="msg-text" style="margin:10px 0;height:150px;min-width:150px;max-width:250px;overflow:hidden;display:flex;justify-content:center;align-items:center">
                    <i class="mdi mdi-file" style="font-size:50px;color:white;"></i>
                  </div>
                  <div class="msg-text">${this.$refs.fileInputW.files[0].name}</div>
                  
                  
                </div>
              </div>
            `;
            this.$refs.msgerChat.insertAdjacentHTML("beforeend", msgHTML);
            this.$refs.msgerChat.scrollTop += 500;
            // this.appendImage(this.PERSON_NAME, this.PERSON_IMG, "right", this.$refs.fileInputW.files[0]);
            this.$refs.msgerInput.value = "";

            this.botResponse();
        }
        
      }
    },
    appendImage(name, img, side, text) {
      //   Simple solution for small apps
      const msgHTML = `
        <div class="msg ${side}-msg">
          <div class="msg-img" style="background-image: url(${img})"></div>

          <div class="msg-bubble">
            <div class="msg-info">
              <div class="msg-info-name">${name}</div>
              <div class="msg-info-time">${this.formatDate(new Date())}</div>
            </div>

            <div class="msg-text">${text}</div>
          </div>
        </div>
      `;
      this.$refs.msgerChat.insertAdjacentHTML("beforeend", msgHTML);
      this.$refs.msgerChat.scrollTop += 500;

    },
    // scrollToElement() {
    //   const el = this.$refs.msgerInputarea;
    //   if (el) {
    //     el.scrollIntoView({behavior: 'smooth'});
    //   }
    // }
  },
}
</script>

<style scoped>

  .page-body-wrapper {
    padding-top: 70px !important;
  }
  .chat_container {
    height: 550px !important;
    overflow: hidden;
  }
  .no_bottom_padding {
    padding-bottom: 0 !important;
  }
  /* .chat_card_w {
    height: 525px !important;
    overflow-y: auto;
  } */

  .content-wrapper {
    background: #231f20 !important;
    color: white !important;
  }
  .content-wrapper a,
  .content-wrapper small,
  .content-wrapper input,
  .content-wrapper h4,
  .content-wrapper h3,
  .content-wrapper h2,
  .content-wrapper h1 {
    color: white !important;
  }
  .content-wrapper a.active {
    color: #A7E863 !important;
    background: #a8e86340 !important;
    padding: auto;
  }
  .card {
    background-color: #000;
    border: 1px solid #b8b8b855;
  }
  .home-tab .nav-tabs .nav-item .nav-link {
    border-right: 1px solid #dee2e66c;
  }
  .home-tab .nav-tabs .nav-item:last-child  .nav-link{
    border-right: none;
  }
  .chat_list_item_wh {
    border-bottom: 1px solid rgba(255, 255, 255, 0.3) !important;
  }
  .chat_list_item_wh small {
    color: rgba(255, 255, 255, 0.7) !important;
  }
  .chat_list_item_wh:last-child {
    border-bottom: none !important;
  }
  
  /* //////////////////////////////////////////////////// */
  .home-tab .nav-tabs {
    border-bottom: 1px solid rgba(255, 255, 255, 0.3) !important;
  }
  .home-tab .nav-tabs a:first-child {
    padding-left: 10px !important;
  }
  .chat_list_item_rightside_wh {
    display: flex;
    flex-direction: column;
    align-items: flex-end;
    justify-content: space-between;
    height: 40px;
  }
  .chat_list_item_rightside_wh span {
    color: rgba(255, 255, 255, 0.5);
    
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
    .chat_list_container_wh {
      overflow-y: auto;
    }
    .chat_list_container_wh::-webkit-scrollbar {
      width: 6px;
    }
    .chat_list_container_wh::-webkit-scrollbar-track {
      background: #000;
    }
    .chat_list_container_wh::-webkit-scrollbar-thumb {
      background: rgb(62, 62, 62);
    }

    .chat_menu_title_container_wh {
      display: flex;
      justify-content: space-between;
      align-items: center;
      width: 100%;
    }
    .chat_menu_title_container_wh a {
      display: flex;
      justify-content: space-between;
      align-items: center;
      text-decoration: none;
      font-size: 12px;
      line-height: 12px;
      border-radius: 35px;
      color: #A7E863 !important;
      border: 1px solid #A7E863;
      padding: 2px 5px;
    }
    .chat_menu_title_container_wh a i {
      font-size: 20px;
      line-height: 20px;
    }
</style>
<style src="@/assets/css/chat/style.css"></style>

