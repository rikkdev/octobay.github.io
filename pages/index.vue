<template>
  <div>
    <div class="header-dimmer"></div>
    <header>
      <div class="header-content">
        <div class="d-flex">
          <img
            src="img/logo.png"
            class="logo mx-auto mx-md-0"
            width="80"
          />
        </div>
        <div class="nav">
          <a
            href="#smartbounties"
            class="btn text-white"
          >Smart Bounties</a>
          <a
            href="#promotion"
            class="btn text-white"
          >Promotion</a>
          <a
            href="#team"
            class="btn text-white"
          >Team</a>
        </div>
        <div
          class="header-text mt-md-0 rellax"
          data-rellax-desktop-speed="-5"
          data-rellax-tablet-speed="-3"
          data-rellax-mobile-speed="-3"
        >
          <h1 class="text-white">Octobay</h1>
          <h2 class="text-white mt-3 mt-md-0">The future of Open Source<br><span class="d-none d-md-inline">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</span>collaboration and funding.</h2>
          <div class="mt-md-5 pt-md-5 pt-4 d-flex justify-content-center flex-column flex-md-row">
            <a
              href="#"
              class="btn btn-lg call-to-action me-md-3"
            >Launch App</a>
            <a
              href="#"
              class="btn btn-lg call-to-action call-to-action-invert ms-md-3 mt-3 mt-md-0"
            >Whitepaper</a>
          </div>
        </div>
      </div>
      <div
        class="header-dimmer-gradient rellax"
        v-rellax="{speed:0}"
      ></div>
      <div
        class="rellax"
        v-rellax="{speed:-10}"
      >
        <img src="img/header-layer-sky-and-sun.png" />
      </div>
      <div
        class="rellax"
        v-rellax="{speed:-8}"
      >
        <img src="img/header-layer-clouds.png" />
      </div>
      <div
        class="rellax"
        v-rellax="{speed:-7}"
      >
        <img src="img/header-layer-mountain2.png" />
      </div>
      <div
        class="rellax"
        v-rellax="{speed:-6}"
      >
        <img src="img/header-layer-see.png" />
      </div>
      <div
        class="rellax"
        v-rellax="{speed:-5}"
      >
        <img src="img/header-layer-octo.png" />
      </div>
      <div
        class="rellax"
        v-rellax="{speed:-5}"
      >
        <img src="img/header-layer-mountain1.png" />
      </div>
      <div
        class="rellax layer-dev"
        v-rellax="{speed:0}"
      >
        <img src="img/header-layer-dev.png" />
      </div>
    </header>
    <section>
      <div class="container intro pb-5 position-relative">
        <div
          class="pb-md-5 mb-md-5 rellax"
          v-rellax="{speed:-1.3}"
        >
          <h4 class="text-center accent-color">WHAT WE ARE PROUD OF</h4>
          <h1 class="text-center font-weight-bolder">Our Featured Solutions</h1>
          <p class="text-center lead">
            Bounty based Open Source funding is a completely new way to accelerate development. By introducing Ledger Technologies and Cryptocurrencies as Payment, we can offer our services everywhere in the world.
          </p>
        </div>
      </div>
      <div
        class="mb-5 pb-5 mb-md-0 pb-md-0 ps-md-5 ms-md-5 content-bg content-bg1 rellax"
        v-rellax="{speed:0}"
      >
        <a id="smartbounties"></a>
        <div class="w-100 d-flex justify-content-center justify-content-md-between">
          <div
            class="card p-md-5 p-4 mb-auto border-0 shadow-lg vw-50 rellax"
            v-rellax="{speed:-1.3}"
          >
            <h4 class="accent-color">Innovative Marketplace to Outsource Tasks</h4>
            <h1>Smart Bounties</h1>
            <p class="m-0">
              Octobay provided trustless bounties for open source projects hosted on GitHub.<br>
              <br>
              Each reward can be stored in a smart contract to act as a middleman between the customer and the developer.
              Once an issue is closed, the contributor can claim his reward without additional consense from the maintainer.
            </p>
          </div>
          <div
            class="d-none d-md-block animation animation-right shadow-lg p-2 mb-auto bg-white vw-25 rellax"
            v-rellax="{speed:-0.5}"
          >
            <!-- width="220"
              height="425" -->
            <video
              style="width:25vw; height:40.295vw;"
              autoplay="autoplay"
              muted
            >
              <source
                src="video/create-bounty.mp4"
                type="video/mp4"
              >
            </video>
          </div>
        </div>
      </div>
      <div class="wave wave-top"></div>
      <div style="background-color: #652FFF;">
        <div
          class="pe-md-5 me-md-5 content-bg content-bg2 rellax d-flex justify-content-end rellax"
          v-rellax="{speed:0}"
        >
          <a id="promotion"></a>
          <div class="w-100 d-flex justify-content-center justify-content-md-between">
            <div class="d-none d-md-block mt-5">
              <div
                class="animation animation-left shadow-lg p-2 mb-auto mt-5 pt-5 bg-white vw-25 rellax"
                v-rellax="{speed:1}"
              >
                <img src="img/send-to-user.gif" />
              </div>
            </div>
            <div
              class="card p-md-5 p-4 border-0 shadow-lg vw-50 mb-auto rellax"
              v-rellax="{speed:-1}"
              style="margin-top: -4vw;"
            >
              <h4 class="accent-color">Innovative Marketplace to Outsource Tasks</h4>
              <h1>Smart Bounties</h1>
              <p class="m-0">
                Octobay provided trustless bounties for open source projects hosted on GitHub.<br>
                <br>
                Each reward can be stored in a smart contract to act as a middleman between the customer and the developer.
                Once an issue is closed, the contributor can claim his reward without additional consense from the maintainer.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="wave wave-bottom"></div>
      <div
        class="ps-md-5 ms-md-5 mb-5 pb-5 mb-md-0 pb-md-0 content-bg content-bg3 rellax"
        v-rellax="{speed:0}"
      >
        <div class="pb-5 pb-md-0 w-100 d-flex justify-content-center justify-content-md-between">
          <div
            class="card p-md-5 p-4 mb-auto border-0 shadow-lg vw-50 rellax"
            v-rellax="{speed:-1}"
            style="margin-top: -4vw;"
          >
            <h4 class="accent-color">Innovative Marketplace to Outsource Tasks</h4>
            <h1>Smart Bounties</h1>
            <p class="m-0">
              Octobay provided trustless bounties for open source projects hosted on GitHub.<br>
              <br>
              Each reward can be stored in a smart contract to act as a middleman between the customer and the developer.
              Once an issue is closed, the contributor can claim his reward without additional consense from the maintainer.
            </p>
          </div>
          <div
            class="d-none d-md-block animation animation-right shadow-lg p-2 mb-auto bg-white vw-25 rellax"
            v-rellax="{speed:-0.5}"
          >
            <img src="img/send-to-user.gif" />
          </div>
        </div>
      </div>
      <a id="team"></a>
    </section>
    <div class="wave wave-footer"></div>
    <footer class="text-center text-white">
      <div class="container">
        <div class="p-5 pt-0 text-white">
          <div class="d-flex flex-column flex-md-row footer-links justify-content-between py-5">
            <div class="d-flex flex-column align-items-center align-items-md-start">
              <a
                href="#"
                class="btn text-white"
              >Litepaper</a>
              <a
                href="#"
                class="btn text-white"
              >Whitepaper</a>
              <a
                href="#"
                class="btn text-white"
              >Documentation</a>
            </div>
            <div class="d-flex flex-column align-items-center align-items-md-start">
              <a
                href="#"
                class="btn text-white"
              >Projects</a>
              <a
                href="#"
                class="btn text-white"
              >Contributors</a>
              <a
                href="#"
                class="btn text-white"
              >Partners</a>
            </div>
            <div class="d-flex flex-column align-items-center align-items-md-start">
              <a
                href="#"
                class="btn text-white"
              >Terms of Service</a>
              <a
                href="#"
                class="btn text-white"
              >Privacy Policy</a>
              <a
                href="#"
                class="btn text-white"
              >Imprint</a>
            </div>
          </div>
          <div class="social-icons">
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-twitter"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-reddit"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-instagram"></i>
            </a>
            <div class="d-block d-md-none"></div>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-facebook"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-google"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-linkedin"></i>
            </a>
            <div class="d-block d-md-none"></div>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-github"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-medium"></i>
            </a>
            <a
              href="#"
              class="btn text-white"
            >
              <i class="fab fa-telegram"></i>
            </a>
          </div>
        </div>
      </div>
    </footer>
  </div>

</template>

 <script>
export default {
  data() {
    return {
      rellax: {
        breakpoints: [768, 768, 1201],
      },
    };
  },
};
/* setTimeout(() => {
  var rellax = new Rellax(".rellax", {
    breakpoints: [768, 768, 1201],
  });
}, 1000); */
</script>

<style>
@import "~/assets/css/landing.css";
@import "~/assets/css/landing-mobile.css";
</style>

