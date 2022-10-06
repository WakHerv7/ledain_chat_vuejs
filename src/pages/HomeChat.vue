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
            <h3><span class="text-black fw-bold">Messages</span></h3>
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
                                        <div>
                                          <h4 class="card-title card-title-dash">Chats</h4>
                                        </div>
                                      </div>
                                      <div class="mt-3">
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
                                          <div class="d-flex">
                                            <img class="img-sm rounded-10" src="images/faces/face3.jpg" alt="profile">
                                            <div class="wrapper ms-3">
                                              <p class="ms-1 mb-1 fw-bold">Katherine Butler</p>
                                              <small class="text-muted mb-0">162543</small>
                                            </div>
                                          </div>
                                          <div class="text-muted text-small">
                                            1h ago
                                          </div>
                                        </div>
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                        <div class="wrapper d-flex align-items-center justify-content-between pt-2">
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
                                        <div>
                                          <h4 class="card-title card-title-dash">Members</h4>
                                        </div>
                                      </div>
                                      <div class="mt-3">
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                        <div class="wrapper d-flex align-items-center justify-content-between py-2 border-bottom">
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
                                  <button class="msger-send-btn" ref="sendFileBtn" @click="getFile()"><i class="mdi mdi-paperclip"></i></button>
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
        <Footer/>
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
import Footer from '../components/Footer.vue'
export default {
  name: 'HomeChat',
  components: {
    Header,
    Sidebar,
    Footer
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
    document.addEventListener("keyup", this.onKeyup);
    this.$refs.fileInputW.addEventListener("change", this.sendInputFile);
  },
  beforeUnmount() {
    document.removeEventListener("keyup", this.onKeyup);
    this.$refs.fileInputW.removeEventListener("change", this.sendInputFile);
  },
  methods: {
    onKeyup(event) {
        if (event.key === "Enter") {
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
</style>
<style src="@/assets/css/chat/style.css"></style>
