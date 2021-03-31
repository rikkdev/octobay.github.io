<template>
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
        <h4 class="accent-color">Do not Disrupt your Workflow</h4>
        <h1>Making a Smooth GitHub Transition</h1>
        <p class="m-0">
          Octobay adapts to your existing workflow with GitHub<br>
          <br>
          We accelerate the processing of your Github issues with our developer community. No matter if you want to include experts or beginners in your open source community
        </p>
      </div>
      <div
        class="d-none d-md-block animation animation-right shadow-lg p-2 mb-auto bg-white vw-25 rellax"
        v-rellax="{speed:-0.5}"
      >
        <video
          style="width:80vw; height:50vw;"
          autoplay="autoplay"
          muted
          loop
        >
          <source
            src="video/github-workflow-new.mp4"
            type="video/mp4"
          >
        </video>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "VideoGitHubIntegrated",
};
</script>

<style>
</style>