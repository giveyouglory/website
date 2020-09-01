<template>
  <div class="h-full">
    <section class="text-gray-500 body-font">
      <div
        class="container mx-auto flex px-5 py-24 items-center justify-center flex-col"
      >
        <img
          class="md:w-5/6 w-full mb-10 object-cover object-center rounded"
          alt="hero"
          src="/big_header.png"
        />
        <div class="text-center lg:w-2/3 w-full">
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-white"
          >
            Crafting a fashion label that suit for you.
          </h1>
          <h3 class="text-2xl mb-3">
            We're working hard to bring it live before this year ends.
          </h3>
          <p class="leading-relaxed mb-8">
            Follow our instagram by clicking <strong>Stay With Us</strong> to
            stay updated <br />
            or be notified when our site has launched by clicking
            <strong>Notify Me</strong> button
          </p>
          <div class="flex justify-center md:flex-row flex-col">
            <a
              target="_blank"
              href="https://www.instagram.com/giveyouglorycom"
              class="inline-flex mb-2 justify-center text-white bg-pink-700 border-0 py-2 px-6 focus:outline-none hover:bg-pink-800 rounded text-lg"
            >
              <div class="mr-1">
                <svg
                  viewBox="0 0 24 24"
                  width="24"
                  height="24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="css-i6dzq1"
                >
                  <rect x="2" y="2" width="20" height="20" rx="5" ry="5"></rect>
                  <path
                    d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z"
                  ></path>
                  <line x1="17.5" y1="6.5" x2="17.51" y2="6.5"></line>
                </svg>
              </div>
              Stay With Us
            </a>
            <a
              target="_blank"
              href="http://eepurl.com/hcd81n"
              class="md:ml-4 mb-2 inline-flex justify-center text-gray-400 bg-gray-800 border-0 py-2 px-6 focus:outline-none hover:bg-gray-700 hover:text-white rounded text-lg"
            >
              <div class="mr-1">
                <svg
                  viewBox="0 0 24 24"
                  width="24"
                  height="24"
                  stroke="currentColor"
                  stroke-width="2"
                  fill="none"
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  class="css-i6dzq1"
                >
                  <path
                    d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"
                  ></path>
                  <polyline points="22,6 12,13 2,6"></polyline>
                </svg>
              </div>
              Notify Me
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  head: {
    bodyAttrs: {
      class: 'bg-black',
    },
  },
}
</script>
