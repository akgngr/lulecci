<template>
  <div
    class="flex w-full max-h-screen min-h-screen px-4 flex-col justify-center items-center"
  >
    <div class="md:w-10/12 lg:w-5/12 w-full flex md:flex-row flex-col">
      <div
        class="w-full md:h-96 lg:max-w-64 rounded-tl-lg md:rounded-bl-lg rounded-tr-lg md:rounded-tr-none"
        style="
          backdrop-filter: blur(10px);
          background-size: cover;
          background-position: 50% 50%;
          background-image: url(/bg.jpeg);
        "
      >
        <div
          style="background-color: rgba(52, 61, 71, 0.6)"
          class="h-full w-full p-4 flex flex-col items-center justify-center rounded-tl-lg md:rounded-bl-lg rounded-tr-lg md:rounded-tr-none"
        >
          <div
            class="rounded-full border-4 border-white bg-top bg-cover bg-no-repeat h-40 w-40"
            style="background-image: url(/yunus-lulecci.jpeg)"
            alt="Yunus Lülecci"
          />
          <div class="w-full flex justify-center gap-1 mt-6">
            <a
              class="rounded-full bg-gray-700 hover:bg-gray-400 p-4 transition ease-in-out delay-150"
              href="fb.com"
            >
              <img class="h-3.5" src="/fb.png" alt="facebook" />
            </a>
            <a
              class="rounded-full bg-gray-700 hover:bg-gray-400 p-4 transition ease-in-out delay-150"
              href="twitter.com"
            >
              <img class="h-3.5" src="/twitter.png" alt="twitter" />
            </a>
            <a
              class="rounded-full bg-gray-700 hover:bg-gray-400 p-4 transition ease-in-out delay-150"
              href="linkedin.com"
            >
              <img class="h-3.5" src="/linkedin.png" alt="linkedin" />
            </a>
          </div>
        </div>
      </div>
      <div class="w-full lg:max-w-96 p-8 shadow-md rounded-tr-sm rounded-br-sm">
        <h3 class="font-thin text-5xl mb-2">Kontakt</h3>
        <h1 class="font-extralight text-3xl text-gray-500">Yunus LÜLECİ</h1>
        <span class="border-b-4 border-gray-400 w-16 block mt-4"></span>
        <div class="relative space-y-2 mt-12">
          <p class="flex gap-4">
            <span class="bg-red-500 p-1 rounded-sm">
              <img
                class="h-6"
                src="/user.png"
                alt="Founded Lülecci LLC."
              /> </span
            >Founded Lülecci LLC.
          </p>
          <p class="flex gap-4">
            <span class="bg-green-500 p-1 rounded-sm">
              <img class="h-6" src="/mail.png" alt="mail" /> </span
            ><a href="mailto:info@lulecci.com">info@lulecci.com</a>
          </p>
          <p class="flex gap-4">
            <span class="bg-blue-500 p-1 rounded-sm"
              ><img class="h-6" src="/phone.png" alt="phone" /></span
            ><a href="tel:+491639542104">+49 163 9542104</a>
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
