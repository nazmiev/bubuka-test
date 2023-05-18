<script>
import Buttons from './components/Buttons.vue'

export default {
  components: {
    Buttons
  }
}
</script>

<template>
  <div>
    <h2>Текстовая ссылка</h2>
    <Buttons link="https://google.com" classname="text_btn" target="_blank">
      Не помню пароль
    </Buttons>
  </div>
  <div>
    <h2>Кнопка</h2>
    <Buttons classname="btn" timerOn="true">
      Отправить сообщение
    </Buttons>
  </div>
  <div>
    <h2>Кнопка с иконкой</h2>
    <div class="btns_row">
      <Buttons link="https://google.com" classname="icon_btn btn" target="_blank">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_159)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M1.82904 0.313814C1.41062 -0.104605 0.732233 -0.104605 0.313814 0.313814C-0.104605 0.732233 -0.104605 1.41062 0.313814 1.82904L8.48477 10L0.313814 18.171C-0.104605 18.5894 -0.104605 19.2678 0.313814 19.6862C0.732233 20.1046 1.41062 20.1046 1.82904 19.6862L10 11.5152L18.171 19.6862C18.5894 20.1046 19.2678 20.1046 19.6862 19.6862C20.1046 19.2678 20.1046 18.5894 19.6862 18.171L11.5152 10L19.6862 1.82904C20.1046 1.41062 20.1046 0.732233 19.6862 0.313814C19.2678 -0.104605 18.5894 -0.104605 18.171 0.313814L10 8.48477L1.82904 0.313814Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_159">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>

      <Buttons link="https://google.com" classname="icon_btn btn" target="_blank">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_154)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M14.7383 19.6712C15.0971 19.2446 15.0855 18.5664 14.7123 18.1562L7.2901 10L14.7123 1.84375C15.0855 1.43361 15.0971 0.755356 14.7383 0.328814C14.3794 -0.0977268 13.7859 -0.111027 13.4127 0.299108L5.28771 9.22768C5.10389 9.42968 5 9.70855 5 10C5 10.2914 5.10389 10.5703 5.28771 10.7723L13.4127 19.7009C13.7859 20.111 14.3794 20.0977 14.7383 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_154">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>

      </Buttons>
      <Buttons link="https://google.com" classname="icon_btn btn" target="_blank">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_149)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M5.26172 19.6712C4.90285 19.2446 4.91449 18.5664 5.28771 18.1562L12.7099 10L5.28771 1.84375C4.91449 1.43361 4.90285 0.755356 5.26172 0.328814C5.62059 -0.0977268 6.21407 -0.111027 6.58729 0.299108L14.7123 9.22768C14.8961 9.42968 15 9.70855 15 10C15 10.2914 14.8961 10.5703 14.7123 10.7723L6.58729 19.7009C6.21407 20.111 5.62059 20.0977 5.26172 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_149">
              <rect width="20" height="20" fill="white" transform="matrix(-1 0 0 1 20 0)" />
            </clipPath>
          </defs>
        </svg>

      </Buttons>
      <Buttons link="https://google.com" classname="icon_btn btn" target="_blank">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_136)">
            <path
              d="M9.63587 19.901L9.62917 19.8971L9.60594 19.8835C9.58615 19.8719 9.55785 19.855 9.52162 19.8331C9.44915 19.7893 9.34486 19.7252 9.21329 19.6413C8.95026 19.4737 8.57762 19.2268 8.13184 18.9058C7.24179 18.2648 6.05253 17.3226 4.8601 16.1184C2.50032 13.7353 0 10.1947 0 5.83342C0 2.57998 2.52677 0 5.57692 0C7.37065 0 8.97674 0.887888 10 2.27959C11.0233 0.887888 12.6294 0 14.4231 0C17.4732 0 20 2.57998 20 5.83342C20 10.1947 17.4997 13.7353 15.1399 16.1184C13.9475 17.3226 12.7582 18.2648 11.8682 18.9058C11.4224 19.2268 11.0497 19.4737 10.7867 19.6413C10.6551 19.7252 10.5509 19.7893 10.4784 19.8331C10.4421 19.855 10.4138 19.8719 10.3941 19.8835L10.3708 19.8971L10.3641 19.901L10.3613 19.9027C10.1357 20.0324 9.8643 20.0324 9.6387 19.9027L9.63587 19.901Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_136">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>
    </div>
    <div class="btns_row">
      <Buttons link="https://google.com" classname="icon_btn icon_btn_small btn" target="_blank">
        <svg width="12" height="12" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_159)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M1.82904 0.313814C1.41062 -0.104605 0.732233 -0.104605 0.313814 0.313814C-0.104605 0.732233 -0.104605 1.41062 0.313814 1.82904L8.48477 10L0.313814 18.171C-0.104605 18.5894 -0.104605 19.2678 0.313814 19.6862C0.732233 20.1046 1.41062 20.1046 1.82904 19.6862L10 11.5152L18.171 19.6862C18.5894 20.1046 19.2678 20.1046 19.6862 19.6862C20.1046 19.2678 20.1046 18.5894 19.6862 18.171L11.5152 10L19.6862 1.82904C20.1046 1.41062 20.1046 0.732233 19.6862 0.313814C19.2678 -0.104605 18.5894 -0.104605 18.171 0.313814L10 8.48477L1.82904 0.313814Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_159">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>

      <Buttons link="https://google.com" classname="icon_btn icon_btn_small btn" target="_blank">
        <svg width="12" height="12" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_154)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M14.7383 19.6712C15.0971 19.2446 15.0855 18.5664 14.7123 18.1562L7.2901 10L14.7123 1.84375C15.0855 1.43361 15.0971 0.755356 14.7383 0.328814C14.3794 -0.0977268 13.7859 -0.111027 13.4127 0.299108L5.28771 9.22768C5.10389 9.42968 5 9.70855 5 10C5 10.2914 5.10389 10.5703 5.28771 10.7723L13.4127 19.7009C13.7859 20.111 14.3794 20.0977 14.7383 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_154">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>

      </Buttons>
      <Buttons link="https://google.com" classname="icon_btn icon_btn_small btn" target="_blank">
        <svg width="12" height="12" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_149)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M5.26172 19.6712C4.90285 19.2446 4.91449 18.5664 5.28771 18.1562L12.7099 10L5.28771 1.84375C4.91449 1.43361 4.90285 0.755356 5.26172 0.328814C5.62059 -0.0977268 6.21407 -0.111027 6.58729 0.299108L14.7123 9.22768C14.8961 9.42968 15 9.70855 15 10C15 10.2914 14.8961 10.5703 14.7123 10.7723L6.58729 19.7009C6.21407 20.111 5.62059 20.0977 5.26172 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_149">
              <rect width="20" height="20" fill="white" transform="matrix(-1 0 0 1 20 0)" />
            </clipPath>
          </defs>
        </svg>

      </Buttons>
      <Buttons link="https://google.com" classname="icon_btn icon_btn_small btn" target="_blank">
        <svg width="12" height="12" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_136)">
            <path
              d="M9.63587 19.901L9.62917 19.8971L9.60594 19.8835C9.58615 19.8719 9.55785 19.855 9.52162 19.8331C9.44915 19.7893 9.34486 19.7252 9.21329 19.6413C8.95026 19.4737 8.57762 19.2268 8.13184 18.9058C7.24179 18.2648 6.05253 17.3226 4.8601 16.1184C2.50032 13.7353 0 10.1947 0 5.83342C0 2.57998 2.52677 0 5.57692 0C7.37065 0 8.97674 0.887888 10 2.27959C11.0233 0.887888 12.6294 0 14.4231 0C17.4732 0 20 2.57998 20 5.83342C20 10.1947 17.4997 13.7353 15.1399 16.1184C13.9475 17.3226 12.7582 18.2648 11.8682 18.9058C11.4224 19.2268 11.0497 19.4737 10.7867 19.6413C10.6551 19.7252 10.5509 19.7893 10.4784 19.8331C10.4421 19.855 10.4138 19.8719 10.3941 19.8835L10.3708 19.8971L10.3641 19.901L10.3613 19.9027C10.1357 20.0324 9.8643 20.0324 9.6387 19.9027L9.63587 19.901Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_136">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>
    </div>
  </div>
  <div>
    <h2>Кнопка c иконкой справа</h2>
    <div class="btns_column">
      <Buttons classname="btn">
        <span>Отправить сообщение</span>
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_257)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M5.26172 19.6712C4.90285 19.2446 4.91449 18.5664 5.28771 18.1562L12.7099 10L5.28771 1.84375C4.91449 1.43361 4.90285 0.755356 5.26172 0.328814C5.62059 -0.0977268 6.21407 -0.111027 6.58729 0.299108L14.7123 9.22768C14.8961 9.42968 15 9.70855 15 10C15 10.2914 14.8961 10.5703 14.7123 10.7723L6.58729 19.7009C6.21407 20.111 5.62059 20.0977 5.26172 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_257">
              <rect width="20" height="20" fill="white" transform="matrix(-1 0 0 1 20 0)" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>
      <Buttons classname="btn disabled">
        <span class="opacity">Отправить сообщение</span>
        <svg class="opacity" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_257)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M5.26172 19.6712C4.90285 19.2446 4.91449 18.5664 5.28771 18.1562L12.7099 10L5.28771 1.84375C4.91449 1.43361 4.90285 0.755356 5.26172 0.328814C5.62059 -0.0977268 6.21407 -0.111027 6.58729 0.299108L14.7123 9.22768C14.8961 9.42968 15 9.70855 15 10C15 10.2914 14.8961 10.5703 14.7123 10.7723L6.58729 19.7009C6.21407 20.111 5.62059 20.0977 5.26172 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_257">
              <rect width="20" height="20" fill="white" transform="matrix(-1 0 0 1 20 0)" />
            </clipPath>
          </defs>
        </svg>
      </Buttons>
    </div>
  </div>
  <div>
    <h2>Кнопка c иконкой слева</h2>
    <div class="btns_column">
      <Buttons classname="btn">
        <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_284)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M14.7383 19.6712C15.0971 19.2446 15.0855 18.5664 14.7123 18.1562L7.2901 10L14.7123 1.84375C15.0855 1.43361 15.0971 0.755356 14.7383 0.328814C14.3794 -0.0977268 13.7859 -0.111027 13.4127 0.299108L5.28771 9.22768C5.10389 9.42968 5 9.70855 5 10C5 10.2914 5.10389 10.5703 5.28771 10.7723L13.4127 19.7009C13.7859 20.111 14.3794 20.0977 14.7383 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_284">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span>Отправить сообщение</span>
      </Buttons>
      <Buttons classname="btn disabled">
        <svg class="opacity" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_1305_284)">
            <path fill-rule="evenodd" clip-rule="evenodd"
              d="M14.7383 19.6712C15.0971 19.2446 15.0855 18.5664 14.7123 18.1562L7.2901 10L14.7123 1.84375C15.0855 1.43361 15.0971 0.755356 14.7383 0.328814C14.3794 -0.0977268 13.7859 -0.111027 13.4127 0.299108L5.28771 9.22768C5.10389 9.42968 5 9.70855 5 10C5 10.2914 5.10389 10.5703 5.28771 10.7723L13.4127 19.7009C13.7859 20.111 14.3794 20.0977 14.7383 19.6712Z"
              fill="#FAFAFA" />
          </g>
          <defs>
            <clipPath id="clip0_1305_284">
              <rect width="20" height="20" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <span class="opacity">Отправить сообщение</span>
      </Buttons>
    </div>
  </div>
</template>

<style scoped>
.btns_column {
  display: flex;
  flex-direction: column;
  gap: 10px;
}

.btns_row {
  display: flex;
  gap: 10px;
  margin-bottom: 20px;
}

.timer_container {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 4px;
  gap: 10px;
  background: #C4250E;
  border-radius: 5px;
}

.timer_container span {
  font-family: 'Inter';
  font-style: normal;
  font-weight: 400;
  font-size: 13px;
  line-height: 16px;
  display: flex;
  align-items: center;
  text-align: center;
  color: #FAFAFA;
}
</style>