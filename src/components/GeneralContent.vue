<script setup></script>

<template>
  <div
    class="hero-section relative overflow-hidden bg-cover bg-no-repeat bg-bottom"
  >
    <div
      class="absolute top-0 right-0 bottom-0 left-0 h-full w-full overflow-hidden bg-[hsla(0,0%,0%,0.75)] bg-fixed"
    >
      <div class="flex h-full items-center justify-center">
        <div
          class="px-6 text-center text-white md:px-12 flex flex-col items-center justify-center"
        >
          <h1
            class="mt-2 mb-16 text-5xl font-bold tracking-tight md:text-6xl xl:text-7xl"
          >
            The best offer on the market <br /><span>for your business</span>
          </h1>
          <div
            class="rounded border-1 border-neutral-50 px-[46px] pt-[14px] pb-[12px] lg:mx-auto text-sm font-medium uppercase leading-normal text-neutral-50 transition duration-150 ease-in-out hover:border-neutral-100 hover:bg-neutral-100 hover:bg-opacity-10 hover:text-neutral-100 focus:border-neutral-100 focus:text-neutral-100 focus:outline-none focus:ring-0 active:border-neutral-200 active:text-neutral-200"
            data-te-ripple-init
            data-te-ripple-color="light"
          >
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla
              facilisi. Sed eget turpis vel elit ultricies placerat. Fusce
              auctor eleifend neque vel consequat. Proin ut tortor id mi.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.hero-section {
  background-image: url(../assets/bg-image.jpg);
  height: 100vh;
}
</style>
