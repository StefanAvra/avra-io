<template>
  <Layout>
    <div class="flex h-screen items-center justify-center">
      <div class="mx-auto px-4">
        <h1 class="text-xl sm:text-xl md:text-xl font-bold">
          Stefan Avramescu
        </h1>

        <p class="text-xl">
          Hi. I'm a Software developer from Stuttgart, Germany. <br />My friends
          call me <span class="italic">Avra</span>.
        </p>

        <p class="home-links text-xl mt-2">
          <a class="tooltip"><font-awesome :icon="['fas', 'envelope']"
              /><span class="tooltip-text bg-gray-200 p-3 mt-10 -ml-6 rounded text-base"
                >email me at 'hi@[this domain]'</span
              ></a
          >
          <a href="https://github.com/stefanavra" target="_blank" rel="noopener"
            ><font-awesome :icon="['fab', 'github']"
          /></a>
          <a
            href="https://twitter.com/stefanavra"
            target="_blank"
            rel="noopener"
            ><font-awesome :icon="['fab', 'twitter']"
          /></a>
          <a
            href="https://keybase.io/avra"
            target="_blank"
            rel="noopener noreferrer"
            ><font-awesome :icon="['fab', 'keybase']"
          /></a>
          <a
            href="https://www.instagram.com/stefan.avra/"
            target="_blank"
            rel="noopener noreferrer"
            ><font-awesome :icon="['fab', 'instagram']"
          /></a>
        </p>
      </div>
    </div>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "Hello, world!",
  },
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
.tooltip .tooltip-text {
  visibility: hidden;
  text-align: center;
  padding: 2px 6px;
  position: absolute;
  z-index: 100;
}
.tooltip:hover .tooltip-text {
  visibility: visible;
}
</style>
