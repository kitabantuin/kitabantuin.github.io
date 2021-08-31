<template>
  <div>
    <section class="text-gray-600 body-font">
      <div
        class="
          container
          mx-auto
          flex
          px-5
          py-16
          md:flex-row
          flex-col
          items-center
        "
      >
        <div
          class="
            lg:flex-grow
            md:w-1/2
            lg:pr-24
            md:pr-16
            flex flex-col
            md:items-start md:text-left
            mb-16
            md:mb-0
            items-center
            text-center
            wrapper
          "
        >
          <p class="mb-8 text-xl leading-relaxed">
            Tugas akhir bikin lo pusing?
          </p>
          <h1 class="text-gray-900 font-bold typing-demo text-4xl">
            Tenang KitaBantuin
          </h1>
        </div>
        <div class="lg:max-w-lg lg:w-full md:w-1/2 w-5/6">
          <img
            class="object-cover object-center rounded"
            alt="hero"
            src="https://dummyimage.com/720x600"
          />
        </div>
      </div>
    </section>

    <Feature />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.typing-demo {
  width: 100%;
  animation: typing 2s steps(22), blink 0.5s step-end infinite alternate;
  white-space: nowrap;
  overflow: hidden;
  border-right: 3px solid;
}

@keyframes typing {
  from {
    width: 0;
  }
}

@keyframes blink {
  50% {
    border-color: transparent;
  }
}
</style>
