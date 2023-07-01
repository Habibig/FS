<template>
  <section class="gradient-form h-full bg-neutral-200">
    <div class="container h-full p-10">
      <div
        class="g-6 flex h-full flex-wrap items-center justify-center text-black"
      >
        <div class="w-full">
          <div class="block rounded-lg bg-white shadow-lg">
            <div class="g-0 lg:flex lg:flex-wrap">
              <!-- Left column container-->
              <div class="px-4 md:px-0 lg:w-6/12">
                <div class="md:mx-6 md:p-12">
                  <!--Logo-->
                  <div class="text-center">
                    <img
                      class="mx-auto w-48 py-7"
                      src="../assets/images/LOGO WEB 1.jpg"
                      alt="logo"
                    />
                    <h4 class="mb-12 mt-1 pb-1 text-xl font-semibold">
                      We are MNM Team
                    </h4>
                  </div>

                  <form>
                    <p class="mb-4">Please login to your account</p>
                    <!--Username input-->
                    <div class="relative mb-4" data-te-input-wrapper-init>
                      <!-- <input
                        type="text"
                        class="peer block min-h-[auto] w-full rounded border-0 bg-transparent px-3 py-[0.32rem] leading-[1.6] outline-none transition-all duration-200 ease-linear focus:placeholder:opacity-100 data-[te-input-state-active]:placeholder:opacity-100 motion-reduce:transition-none dark:placeholder:text-neutral-200 [&:not([data-te-input-placeholder-active])]:placeholder:opacity-0"
                        id="exampleFormControlInput1"
                        placeholder="Username"
                      /> -->
                      <label class="mb-2 block text-xs font-semibold"
                        >Email</label
                      >
                      <input
                        type="email"
                        placeholder="Enter your email"
                        class="block w-full rounded-md border border-gray-300 focus:border-purple-700 focus:outline-none focus:ring-1 focus:ring-purple-700 py-1 px-1.5 text-gray-500"
                      />
                    </div>

                    <!--Password input-->
                    <div class="relative mb-4" data-te-input-wrapper-init>
                      <label class="mb-2 block text-xs font-semibold"
                        >Password</label
                      >
                      <input
                        type="password"
                        placeholder="*****"
                        class="block w-full rounded-md border border-gray-300 focus:border-purple-700 focus:outline-none focus:ring-1 focus:ring-purple-700 py-1 px-1.5 text-gray-500"
                      />
                    </div>

                    <!--Submit button-->
                    <div class="mb-12 pb-1 pt-1 text-center">
                      <button
                        class="mb-3 inline-block w-full rounded px-6 pb-2 pt-2.5 text-xs font-medium uppercase leading-normal text-black shadow-[0_4px_9px_-4px_rgba(0,0,0,0.2)] transition duration-150 ease-in-out hover:shadow-[0_8px_9px_-4px_rgba(0,0,0,0.1),0_4px_18px_0_rgba(0,0,0,0.2)] focus:shadow-[0_8px_9px_-4px_rgba(0,0,0,0.1),0_4px_18px_0_rgba(0,0,0,0.2)] focus:outline-none focus:ring-0 active:shadow-[0_8px_9px_-4px_rgba(0,0,0,0.1),0_4px_18px_0_rgba(0,0,0,0.2)]"
                        type="button"
                        data-te-ripple-init
                        data-te-ripple-color="light"
                      >
                        Sign Up
                      </button>

                      <!--Forgot password link-->
                      <a href="#!">Forgot password?</a>
                    </div>

                    <!--Register button-->
                    <div class="flex items-center justify-between pb-6">
                      <p class="mb-0 mr-2">You have an account?</p>
                      <button
                        type="button"
                        class="inline-block rounded border-2 border-danger px-6 pb-[6px] pt-2 text-xs font-medium uppercase leading-normal text-danger transition duration-150 ease-in-out hover:border-danger-600 hover:bg-neutral-500 hover:bg-opacity-10 hover:text-danger-600 focus:border-danger-600 focus:text-danger-600 focus:outline-none focus:ring-0 active:border-danger-700 active:text-danger-700 dark:hover:bg-neutral-100 dark:hover:bg-opacity-10"
                        data-te-ripple-init
                        data-te-ripple-color="light"
                      >
                        Log In
                      </button>
                    </div>
                  </form>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>
