<script lang="typescript">
  import "./main.css";
</script>

<div
  class="App leading-normal tracking-normal text-gray-900"
  style="font-family: 'Source Sans Pro', sans-serif;"
>
  <div
    class="h-screen pb-14 bg-right bg-cover"
  >
    <!--Nav-->
    <div class="w-full container mx-auto p-6">
      <div class="w-full flex items-center justify-between">
        <a
          class="flex items-center text-indigo-400 no-underline hover:no-underline font-bold text-2xl lg:text-4xl"
          href="/"
          ><svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            class="h-8 fill-current text-indigo-600 pr-2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M12 4v1m6 11h2m-6 0h-2v4m0-11v3m0 0h.01M12 12h4.01M16 20h4M4 12h4m12 0h.01M5 8h2a1 1 0 001-1V5a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1zm12 0h2a1 1 0 001-1V5a1 1 0 00-1-1h-2a1 1 0 00-1 1v2a1 1 0 001 1zM5 20h2a1 1 0 001-1v-2a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1z"
            />
          </svg>GIVE
        </a>

        <div class="flex w-1/2 justify-end content-center">
          <a
            class="inline-block text-blue-300 no-underline hover:text-indigo-800 hover:text-underline text-center h-10 p-2 md:h-auto md:p-4"
            data-tippy-content="@twitter_handle"
            href="https://twitter.com/intent/tweet?url=https://give-ten.vercel.app/"
          >
            <svg
              class="fill-current h-6"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 32 32"
              ><path
                d="M30.063 7.313c-.813 1.125-1.75 2.125-2.875 2.938v.75c0 1.563-.188 3.125-.688 4.625a15.088 15.088 0 0 1-2.063 4.438c-.875 1.438-2 2.688-3.25 3.813a15.015 15.015 0 0 1-4.625 2.563c-1.813.688-3.75 1-5.75 1-3.25 0-6.188-.875-8.875-2.625.438.063.875.125 1.375.125 2.688 0 5.063-.875 7.188-2.5-1.25 0-2.375-.375-3.375-1.125s-1.688-1.688-2.063-2.875c.438.063.813.125 1.125.125.5 0 1-.063 1.5-.25-1.313-.25-2.438-.938-3.313-1.938a5.673 5.673 0 0 1-1.313-3.688v-.063c.813.438 1.688.688 2.625.688a5.228 5.228 0 0 1-1.875-2c-.5-.875-.688-1.813-.688-2.75 0-1.063.25-2.063.75-2.938 1.438 1.75 3.188 3.188 5.25 4.25s4.313 1.688 6.688 1.813a5.579 5.579 0 0 1 1.5-5.438c1.125-1.125 2.5-1.688 4.125-1.688s3.063.625 4.188 1.813a11.48 11.48 0 0 0 3.688-1.375c-.438 1.375-1.313 2.438-2.563 3.188 1.125-.125 2.188-.438 3.313-.875z"
              /></svg
            >
          </a>
          <a
            class="inline-block text-blue-300 no-underline hover:text-indigo-800 hover:text-underline text-center h-10 p-2 md:h-auto md:p-4 "
            data-tippy-content="#facebook_id"
            href="https://www.facebook.com/sharer/sharer.php?u=https://give-ten.vercel.app/"
          >
            <svg
              class="fill-current h-6"
              xmlns="http://www.w3.org/2000/svg"
              viewBox="0 0 32 32"
              ><path
                d="M19 6h5V0h-5c-3.86 0-7 3.14-7 7v3H8v6h4v16h6V16h5l1-6h-6V7c0-.542.458-1 1-1z"
              /></svg
            >
          </a>
        </div>
      </div>
    </div>

    <!--Main-->
    <div
      class="container pt-24 md:pt-48 px-6 mx-auto flex flex-wrap flex-col md:flex-row items-center"
    >
      <!--Left Col-->
      <div
        class="flex flex-col w-full xl:w-2/5 justify-center lg:items-start overflow-y-hidden"
      >
        <h1
          class="my-4 text-3xl md:text-5xl text-purple-800 font-bold leading-tight text-center md:text-left slide-in-bottom-h1"
        >
          Get back your tips.
        </h1>
        <p
          class="leading-normal text-base md:text-2xl mb-8 text-center md:text-left slide-in-bottom-subtitle"
        >
          We don't have coins anymore. We give you tip in the app and most of
          you don't see a single penny of it.
        </p>

        <p
          class="text-blue-400 font-bold pb-8 lg:pb-6 text-center md:text-left fade-in"
        >
          Game changed. Here is how to get your tips back.
        </p>
        <div
          class="flex w-full justify-center md:justify-start pb-24 lg:pb-0 fade-in"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
            class="h-8  text-purple-800 pr-2"
          >
            <path
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              d="M15 13l-3 3m0 0l-3-3m3 3V8m0 13a9 9 0 110-18 9 9 0 010 18z"
            />
          </svg>
        </div>
      </div>

      <!--Right Col-->
      <div class="w-full xl:w-3/5 py-6 overflow-y-hidden">
        <img
          class="w-5/6 mx-auto lg:mr-0 slide-in-bottom"
          src="/illustratio1.svg"
          alt="illustration"
        />
      </div>

      <div class="py-12 pt-24 mt-28 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div class="lg:text-center">
            <p
              class="mt-2 text-3xl leading-8 font-bold tracking-tight text-purple-800 sm:text-4xl"
            >
              Cryptocurrencies are here to help
            </p>
            <p class="mt-4 max-w-2xl text-xl text-gray-500 lg:mx-auto">
              It may all sound scary and only for techies. But in a fact, it is
              as easy as to install app on your phone and print one or more QR
              codes.
            </p>
          </div>

          <div class="mt-20 pt-20">
            <dl
              class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
            >
              <div class="flex">
                <div class="flex-shrink-0">
                  <div
                    class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-500 text-white"
                  >
                    <!-- Heroicon name: outline/globe-alt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4"
                      />
                    </svg>
                  </div>
                </div>
                <div class="ml-4">
                  <dt class="text-lg leading-6 font-medium text-gray-900">
                    1/ Install wallet
                  </dt>
                  <dd class="mt-2 text-base text-gray-700">
                    Most of them works in a very similar way. I am using <a
                      href="https://trustwallet.com/"
                      class="font-bold underline">Trust Wallet</a
                    >
                    other good option is
                    <a
                      href="https://atomicwallet.io/downloads"
                      class="font-bold underline">Atomic.</a
                    >
                  </dd>
                </div>
              </div>

              <div class="flex">
                <div class="flex-shrink-0">
                  <div
                    class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-500 text-white"
                  >
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M15 15l-2 5L9 9l11 4-5 2zm0 0l5 5M7.188 2.239l.777 2.897M5.136 7.965l-2.898-.777M13.95 4.05l-2.122 2.122m-5.657 5.656l-2.12 2.122"
                      />
                    </svg>
                  </div>
                </div>
                <div class="ml-4">
                  <dt class="text-lg leading-6 font-medium text-gray-900">
                    2/ Follow the guide
                  </dt>
                  <dd class="mt-2 text-base text-gray-700">
                    Every wallet will guide you through the process of creating
                    secret "seed phrase". It is important to write the sequence
                    down. Really, on paper. Do not be lazy, your computers are
                    not as safe as you may think.
                  </dd>
                </div>
              </div>

              <div class="flex">
                <div class="flex-shrink-0">
                  <div
                    class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-500 text-white"
                  >
                    <!-- Heroicon name: outline/lightning-bolt -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M12 4v1m6 11h2m-6 0h-2v4m0-11v3m0 0h.01M12 12h4.01M16 20h4M4 12h4m12 0h.01M5 8h2a1 1 0 001-1V5a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1zm12 0h2a1 1 0 001-1V5a1 1 0 00-1-1h-2a1 1 0 00-1 1v2a1 1 0 001 1zM5 20h2a1 1 0 001-1v-2a1 1 0 00-1-1H5a1 1 0 00-1 1v2a1 1 0 001 1z"
                      />
                    </svg>
                  </div>
                </div>
                <div class="ml-4">
                  <dt class="text-lg leading-6 font-medium text-gray-900">
                    3/ Get your QR code
                  </dt>
                  <dd class="mt-2 text-base text-gray-700">
                    In next step you need the QR code that describe your wallet
                    address. Every wallet have this functionality, in a Trust
                    Wallet you click on receive and pick your currency. This is
                    little similar to phones, every crytocurrency token have its
                    circle of fans. Generally best are BNB, ALGO, DOT and
                    Ripple. When it comes to transactions with low volume as the
                    tips, Bitcoin is not best.
                  </dd>
                </div>
              </div>

              <div class="flex">
                <div class="flex-shrink-0">
                  <div
                    class="flex items-center justify-center h-12 w-12 rounded-full bg-indigo-500 text-white"
                  >
                    <!-- Heroicon name: outline/annotation -->
                    <svg
                      class="h-6 w-6"
                      xmlns="http://www.w3.org/2000/svg"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                      aria-hidden="true"
                    >
                      <path
                        stroke-linecap="round"
                        stroke-linejoin="round"
                        stroke-width="2"
                        d="M17 17h2a2 2 0 002-2v-4a2 2 0 00-2-2H5a2 2 0 00-2 2v4a2 2 0 002 2h2m2 4h6a2 2 0 002-2v-4a2 2 0 00-2-2H9a2 2 0 00-2 2v4a2 2 0 002 2zm8-12V5a2 2 0 00-2-2H9a2 2 0 00-2 2v4h10z"
                      />
                    </svg>
                  </div>
                </div>
                <div class="ml-4">
                  <dt class="text-lg leading-6 font-medium text-gray-900">
                    4/ Print your QR Code
                  </dt>
                  <dd class="mt-2 text-base text-gray-700">
                    Now that you can see the QR code on the screen, you can
                    print it. QR Code does not include any secret, you can make
                    a screenshot, share it to some application that allows
                    printing or use any other means to print it. As mentioned in
                    a step 3/ you will probably need more codes as everyone
                    prefers different tokens. That's okay, just print two or
                    three that are most popular in your area.
                  </dd>
                </div>
              </div>
            </dl>
            <dl class="mt-12 ml-16 text-base text-gray-700">
              Now you are ready to go. I suggest to add some text to the printed
              QR code and make it waterproof. It is good to have this QR code
              visible, so you can skip the awkward discussion about tipping.
              Keep in mind that some people will not understand the concept and
              it is avery bad idea to push your customer out of their comfort
              zone. Simply say something like "if you liked my service or
              delivery, consider installing digital wallet and tip me with the
              cryptocurrency tokens.". Some people will not like the idea and
              that's okay, some of them will never tip you anyway.
            </dl>
          </div>
        </div>
      </div>

      <!--Footer-->
      <div class="w-full pt-16 pb-6 text-sm text-center md:text-left fade-in">
        <a class="text-gray-500 no-underline hover:no-underline" href="/"
          >&copy; Adam Sobotka 2021</a
        >
      </div>
    </div>
  </div>
</div>
