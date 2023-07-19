<template>
  <div class="div">
    <footer class="footer">
      <div class="box" />
      <img class="footer-child" alt="" src="/vector-36.svg" />
      <img class="footer-item" alt="" src="/vector-37.svg" />
      <div class="footer-copyright">
        <img class="logo-icon" alt="" src="/logo.svg" />
        <div class="frame">
          <div class="footer-text">
            Copyright © 2023 Tlancer. All rights reserved.
          </div>
          <div class="social-icons">
            <img class="social-icon" alt="" src="/social-icon.svg" />
            <img class="social-icon" alt="" src="/social-icon2.svg" />
          </div>
        </div>
      </div>
      <img class="mdiinstagram-icon" alt="" src="/mdiinstagram.svg" />
      <img class="icbaseline-tiktok-icon" alt="" src="/icbaselinetiktok.svg" />
      <img
        class="icbaseline-discord-icon"
        alt=""
        src="/icbaselinediscord.svg"
      />
    </footer>
    <div class="inner">
      <div class="frame-parent">
        <div class="rectangle-wrapper">
          <div class="frame-child" />
        </div>
        <div class="frame1">
          <div class="button-frame-1251-parent">
            <button class="button-frame-1251" @click="onBUTTONFrame1251Click">
              <b class="b">შემდეგი</b>
              <img
                class="button-frame-1251-child"
                alt=""
                src="/vector-51.svg"
              />
            </button>
            <div class="frame2">
              <div class="parent">
                <b class="b1">შექმენი კურსი</b>
                <div class="frame-group">
                  <div class="group-parent">
                    <img class="frame-item" alt="" src="/group-3022.svg" />
                    <div class="frame3">
                      <b class="b2">კურსის დეტალები</b>
                      <div class="div1">დაამატე კურსის დეტალები</div>
                    </div>
                  </div>
                  <div class="group-container">
                    <img class="frame-item" alt="" src="/group-3023.svg" />
                    <div class="frame4">
                      <b class="b1">სილაბუსი</b>
                      <div class="div2">დაამატე შენი სილაბუსი</div>
                    </div>
                  </div>
                  <div class="frame-div">
                    <img class="frame-item" alt="" src="/group-3024.svg" />
                    <div class="frame5">
                      <b class="b1">კურსის ფასი</b>
                      <div class="div2">დაამატე კურსის ფასი</div>
                    </div>
                  </div>
                  <div class="group-parent1">
                    <img class="frame-item" alt="" src="/group-3025.svg" />
                    <div class="frame6">
                      <b class="b1">დასრულება</b>
                      <div class="div2">დაამატე კურსის ვიდეო</div>
                    </div>
                  </div>
                </div>
              </div>
              <div class="frame7">
                <div class="frame-container">
                  <form class="frame-form">
                    <div class="frame8">
                      <div class="div5">კურსის კატეგორიები</div>
                      <div class="div5">მონიშნე კურსი</div>
                    </div>
                    <div class="frame9">
                      <div class="frame10">
                        <button class="wrapper">
                          <div class="div7">კურსის კატეგორია</div>
                        </button>
                        <img class="vector-icon" alt="" src="/vector1.svg" />
                      </div>
                      <div class="frame11">
                        <div class="div8">მონიშნეთ კურსი</div>
                        <img class="vector-icon1" alt="" src="/vector2.svg" />
                      </div>
                    </div>
                  </form>
                  <div class="frame-parent1">
                    <div class="frame12">
                      <div class="div9">აირჩიეთ კურსის ტიპი</div>
                      <div class="div9">სტუდენტების რაოდენობა</div>
                    </div>
                    <div class="frame9">
                      <button class="frame14">
                        <div class="container">
                          <input
                            class="input"
                            type="text"
                            maxlength
                            minlength
                            required
                          />
                        </div>
                        <div class="wrapper1">
                          <div class="div7">აირჩიეთ კურსის ტიპი</div>
                        </div>
                      </button>
                      <input
                        class="frame15"
                        type="text"
                        maxlength
                        minlength
                        required
                      />
                    </div>
                  </div>
                  <input
                    class="frame-input"
                    type="text"
                    maxlength
                    minlength
                    required
                  />
                  <div class="group">
                    <div class="div12">კლასის ტიპი</div>
                    <input class="frame16" type="text" maxlength minlength />
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="frame17">
      <div class="frame18">
        <img class="frame-icon" alt="" src="/frame-1127@2x.png" />
        <div class="div13">საბა კიაშვილი</div>
      </div>
      <img class="vector-icon2" alt="" src="/vector3.svg" />
    </div>
  </div>
</template>
<script>
  import { defineComponent, ref } from "vue";

  export default defineComponent({
    name: "Component1",
    methods: {
      onBUTTONFrame1251Click() {
        this.$router.push("/-2");
      },
    },
  });
</script>
<style scoped>
  .box {
    position: absolute;
    top: -371.02px;
    left: 661.28px;
  }
  .footer-child {
    position: absolute;
    top: 146.22px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .footer-item {
    position: absolute;
    top: -470.32px;
    left: 195.33px;
    width: 1703.95px;
    height: 0px;
  }
  .logo-icon {
    position: relative;
    width: 127.67px;
    height: 30.55px;
  }
  .footer-text {
    position: relative;
    font-weight: 500;
    display: inline-block;
    width: 401.57px;
    flex-shrink: 0;
  }
  .social-icon {
    position: relative;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
    flex-shrink: 0;
  }
  .social-icons {
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 26.19px;
  }
  .frame {
    width: 820.6px;
    height: 26.19px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 340px;
  }
  .footer-copyright {
    position: absolute;
    top: 189.87px;
    left: 218.25px;
    width: 1449.15px;
    height: 30.55px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 500px;
  }
  .mdiinstagram-icon {
    position: absolute;
    top: 194.24px;
    left: 1689.22px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-tiktok-icon {
    position: absolute;
    top: 194.24px;
    left: 1737.24px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .icbaseline-discord-icon {
    position: absolute;
    top: 194.24px;
    left: 1785.25px;
    width: 26.19px;
    height: 26.19px;
    overflow: hidden;
  }
  .footer {
    position: absolute;
    bottom: -4077px;
    left: -52px;
    width: 2095.16px;
    height: 311px;
    overflow: hidden;
    text-align: left;
    font-size: 17.46px;
    color: #fff;
    font-family: "Work Sans";
  }
  .frame-child {
    position: relative;
    border-radius: 14.05px 5px 5px 14.05px;
    background-color: #f9fbfc;
    width: 535px;
    height: 1231px;
  }
  .rectangle-wrapper {
    flex: 1;
    border-radius: 14.05px;
    background-color: #fff;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .b {
    position: relative;
    font-size: 20.47px;
    letter-spacing: -0.01em;
    font-family: "Noto Sans Georgian";
    color: #fff;
    text-align: center;
  }
  .button-frame-1251-child {
    position: relative;
    width: 19.14px;
    height: 6.55px;
  }
  .button-frame-1251 {
    cursor: pointer;
    border: none;
    padding: 10.680000305175781px 32.93000030517578px;
    background-color: #8a7cee;
    position: absolute;
    top: 955.82px;
    left: 555px;
    border-radius: 6.23px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 21.36px;
  }
  .button-frame-1251:hover {
    background-color: #5243c0;
  }
  .b1 {
    position: relative;
    letter-spacing: -0.01em;
  }
  .frame-item {
    position: relative;
    width: 32.35px;
    height: 32.35px;
  }
  .b2 {
    align-self: stretch;
    position: relative;
    letter-spacing: -0.01em;
  }
  .div1 {
    align-self: stretch;
    position: relative;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
    color: rgba(51, 51, 51, 0.32);
  }
  .frame3 {
    width: 296.26px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent {
    align-self: stretch;
    display: flex;
    flex-direction: row;
    padding: 0px 0px 0.000102996826171875px;
    align-items: center;
    justify-content: space-between;
    color: #333;
  }
  .div2 {
    position: relative;
    font-size: 15.4px;
    letter-spacing: -0.01em;
    font-weight: 500;
  }
  .frame4 {
    width: 203px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-container {
    width: 276.25px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    padding: 0px 0px 0.000087738037109375px;
    box-sizing: border-box;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    opacity: 0.25;
  }
  .frame5 {
    width: 204px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .frame-div {
    width: 277px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 40px;
    opacity: 0.25;
  }
  .frame6 {
    width: 200px;
    height: 60.48px;
    overflow: hidden;
    flex-shrink: 0;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .group-parent1 {
    width: 270px;
    height: 60.48px;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 37px;
    color: #b4b5bc;
  }
  .frame-group {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 146px;
    font-size: 28.92px;
    color: #110000;
  }
  .parent {
    flex: 1;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 76px;
  }
  .div5 {
    flex: 1;
    position: relative;
    font-size: 22px;
    letter-spacing: -0.01em;
    font-weight: 600;
    font-family: "Noto Sans Georgian";
    color: #333;
    text-align: center;
  }
  .frame8 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 161px;
  }
  .div7 {
    position: relative;
    font-size: 18px;
    letter-spacing: -0.01em;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    color: #aba5a5;
    text-align: center;
  }
  .wrapper {
    cursor: pointer;
    border: 1px solid #d7d7d7;
    padding: 0px 34px;
    background-color: transparent;
    flex: 1;
    border-radius: 7px;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: center;
  }
  .vector-icon {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 8.73px;
    margin-left: -34px;
  }
  .frame10 {
    flex: 1;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
  }
  .div8 {
    flex: 1;
    position: relative;
    font-size: 18px;
    letter-spacing: -0.01em;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    color: #aba5a5;
    text-align: center;
  }
  .vector-icon1 {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 8.73px;
  }
  .frame11 {
    flex: 1;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 22px 18.630796432495117px;
    align-items: center;
    justify-content: flex-end;
    gap: 125px;
  }
  .frame9 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 70px;
  }
  .frame-form {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 25px;
  }
  .div9 {
    flex: 1;
    position: relative;
    letter-spacing: -0.01em;
    font-weight: 600;
  }
  .frame12 {
    align-self: stretch;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-start;
    gap: 150px;
  }
  .input {
    border: none;
    font-weight: 500;
    font-family: "Noto Sans Georgian";
    font-size: 18px;
    background-color: transparent;
    position: relative;
    letter-spacing: -0.01em;
    color: #aba5a5;
    text-align: center;
  }
  .container {
    align-self: stretch;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
  }
  .wrapper1 {
    align-self: stretch;
    border-radius: 7px;
    border: 1px solid #d7d7d7;
    box-sizing: border-box;
    height: 68px;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
    margin-top: -68px;
  }
  .frame14 {
    cursor: pointer;
    border: none;
    padding: 0;
    background-color: transparent;
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
  }
  .frame15 {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    flex: 1;
    border-radius: 7px;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    padding: 0px 34px;
    align-items: flex-start;
    justify-content: center;
  }
  .frame-parent1 {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    padding: 0px 0px 0px 3px;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 22px;
  }
  .frame-input {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    align-self: stretch;
    border-radius: 7px;
    display: flex;
    flex-direction: column;
    padding: 33px 592px 33px 34px;
    align-items: flex-start;
    justify-content: flex-end;
  }
  .div12 {
    position: absolute;
    top: 0px;
    left: 6px;
    letter-spacing: -0.01em;
    font-weight: 600;
  }
  .frame16 {
    border: 1px solid #d7d7d7;
    background-color: transparent;
    position: absolute;
    top: 61px;
    left: 0px;
    border-radius: 7px;
    box-sizing: border-box;
    width: 768px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 22px 21.630796432495117px;
    align-items: center;
    justify-content: space-between;
  }
  .group {
    align-self: stretch;
    position: relative;
    height: 129px;
    font-size: 23px;
  }
  .frame-container {
    align-self: stretch;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-start;
    gap: 89px;
  }
  .frame7 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    font-size: 22px;
  }
  .frame2 {
    position: absolute;
    top: 0px;
    left: 0px;
    width: 1323px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 185px;
  }
  .button-frame-1251-parent {
    align-self: stretch;
    position: relative;
    height: 1005.18px;
  }
  .frame1 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: flex-end;
    margin-left: -1432px;
  }
  .frame-parent {
    width: 1504px;
    display: flex;
    flex-direction: row;
    align-items: flex-start;
    justify-content: flex-end;
  }
  .inner {
    position: absolute;
    top: 245px;
    left: 208px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
  }
  .frame-icon {
    position: relative;
    width: 1503px;
    height: 51px;
    object-fit: cover;
  }
  .div13 {
    position: relative;
    font-weight: 600;
  }
  .frame18 {
    flex: 1;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: space-between;
  }
  .vector-icon2 {
    flex: 1;
    position: relative;
    max-width: 100%;
    overflow: hidden;
    height: 4px;
  }
  .frame17 {
    position: absolute;
    top: 57px;
    left: 214px;
    width: 1631px;
    overflow: hidden;
    display: flex;
    flex-direction: row;
    padding: 4px 0px 0px;
    box-sizing: border-box;
    align-items: flex-start;
    justify-content: flex-start;
    gap: 122px;
    text-align: left;
    font-size: 18px;
  }
  .div {
    position: relative;
    background-color: #eff2fc;
    width: 100%;
    height: 1797px;
    overflow: hidden;
    text-align: center;
    font-size: 34.25px;
    color: #333;
    font-family: "Noto Sans Georgian";
  }

  @media screen and (max-width: 1200px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent {
      flex-direction: column;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div5 {
      flex: unset;
      align-self: stretch;
    }

    .frame8 {
      flex-direction: column;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame10 {
      flex: unset;
      align-self: stretch;
    }

    .frame11 {
      flex: unset;
      align-self: stretch;
    }

    .frame9 {
      flex-direction: column;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .div9 {
      flex: unset;
      align-self: stretch;
    }

    .frame12 {
      flex-direction: column;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame14 {
      flex: unset;
      align-self: stretch;
    }

    .frame15 {
      flex: unset;
      align-self: stretch;
    }

    .frame16 {
      flex-direction: column;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame18 {
      flex-direction: column;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div {
      width: 100%;
    }
  }
  @media screen and (max-width: 960px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent {
      flex-direction: row;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame8 {
      flex-direction: row;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame9 {
      flex-direction: row;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame12 {
      flex-direction: row;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame16 {
      flex-direction: row;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame18 {
      flex-direction: row;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div {
      width: 100%;
    }
  }
  @media screen and (max-width: 420px) {
    .button-frame-1251 {
      flex-direction: column;
    }

    .group-parent {
      flex-direction: column;
      gap: 40px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div5 {
      flex: unset;
      align-self: stretch;
    }

    .frame8 {
      flex-direction: column;
      gap: 161px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame10 {
      flex: unset;
      align-self: stretch;
    }

    .frame11 {
      flex: unset;
      align-self: stretch;
    }

    .frame9 {
      flex-direction: column;
      gap: 70px;
      align-items: center;
      justify-content: flex-start;
    }

    .div9 {
      flex: unset;
      align-self: stretch;
    }

    .frame12 {
      flex-direction: column;
      gap: 150px;
      align-items: center;
      justify-content: flex-start;
    }

    .frame14 {
      flex: unset;
      align-self: stretch;
    }

    .frame15 {
      flex: unset;
      align-self: stretch;
    }

    .frame16 {
      flex-direction: column;
      gap: 579px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .frame18 {
      flex-direction: column;
      gap: -230px;
      align-items: flex-start;
      justify-content: flex-start;
    }

    .div {
      width: 100%;
    }
  }
</style>
