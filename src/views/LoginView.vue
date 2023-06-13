<template>
  <div class="flex justify-center border items-center h-screen">
    <div
      class="w-5/6 border max-w-md flex justify-between flex-col bg-white rounded-3xl h-3/5 p-4"
    >
      <h1 class="text-3xl block text-center font-normal">
        <i class="fa-solid fa-user"></i> Login
      </h1>

      <div class="mt-3">
        <label for="username" class="block text-base ml-2 text-start mb-2"
          >Username</label
        >
        <input
          type="text"
          id="username"
          class="border block border-x-0 border-t-0 w-full text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
          placeholder="Enter Username..."
        />
      </div>
      <div class="mt-3">
        <label for="password" class="block text-start ml-2 text-base mb-2"
          >Password</label
        >
        <input
          type="password"
          id="password"
          class="block border w-full border-x-0 border-t-0 text-base px-2 py-1 focus:outline-none focus:ring-0 focus:border-gray-600"
          placeholder="Enter Password..."
        />
      </div>
      <div class="mt-3 flex justify-between items-center">
        <div>
          <input type="checkbox" />
          <label>Remember Me</label>
        </div>
        <div>
          <a href="#" class="font-semibold">Forgot Password?</a>
        </div>
      </div>
      <div class="mt-5">
        <button
          type="submit"
          class="text-white btn py-1 w-56 bg-black rounded-md hover:btn h-16 font-semibold"
        >
          <i class="fa-solid fa-right-to-bracket"></i>&nbsp;&nbsp;Login
        </button>
      </div>
    </div>

    <div class="p-14 hidden md:block">
      <p class="text-2xl">
        Track your productivity and improve your company's efficiency!
      </p>
      <img src="../assets/Deadline.png" alt="" srcset="" />
    </div>

    <!-- <div></div> -->
  </div>
</template>

<script></script>
