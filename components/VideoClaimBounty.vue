<template>
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
        <h4 class="accent-color">Claim your Bounties</h4>
        <h1>Automated Payment Process</h1>
        <p class="m-0">
          We have completely cut out the extra effort to pay your developers. As soon as the work is done, the developer can collect his reward. <br>
          <br>
          Bounty is claimable once the issue is closed, the author/contributor can request a withdrawal on which the Chainlink oracles check if the required conditions are met.
        </p>
      </div>
      <div
        class="d-none d-md-block animation animation-right shadow-lg p-2 mb-auto bg-white vw-25 rellax"
        v-rellax="{speed:-0.5}"
      >
        <!-- width="220"
              height="425" -->
        <video
          style="width:25vw; height:28.295vw;"
          autoplay="autoplay"
          muted
          loop
        >
          <source
            src="video/claim-bounty-new.mp4"
            type="video/mp4"
          >
        </video>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VideoClaimBounty",
};
</script>

<style>
</style>