<script setup>
</script>
<template>
  <section
    id="home"
    class="
      lg:h-[85vh]
      flex
      items-center
      bg-light-primary
      dark:bg-dark-primary
      py-32
      lg:py-0
      overflow-hidden
    "
  >
    <div
      class="container mx-auto h-full"
      v-motion
      :initial="{
        opacity: 0,
        y: 100,
      }"
      :visible="{
        opacity: 1,
        y: 0,
      }"
    >
      <div class="flex flex-col md:flex-row items-center h-full pt-8">
        <div class="flex-1 flex flex-col items-center lg:items-start">
          <p class="text-lg text-accent text-md mb-[22px]">Hey, I'm Ali! 👋</p>
          <h1
            class="
              text-4xl
              leading-[44px]
              md:text-5xl md:leading-tight
              lg:text-7xl lg:leading-[1.2]
              font-bold
              md:tracking-[-2px]
            "
          >
            I Build  <br />
            Web Interfaces And Software Applications.
          </h1>

          <button
            class="
              btn btn-md
              bg-accent
              hover:bg-light-secondary hover:text-light-tail-500
              dark:hover:bg-dark-secondary dark:hover:text-dark-navy-100
              md:btn-lg
              transition-all
            "

          >
            Work with me
          </button>
          <div class="pt-12">
            <h5
              class="
                text-lg
                flex
                justify-center
                lg:justify-start
                items-center
                text-black
                dark:text-white
                mb-2
              "
            >
              Follow me on
            </h5>
            <div class="flex items-center mb-6">
              <a
                class="
                  w-12
                  h-12
                  rounded-full
                  flex
                  items-center
                  justify-center
                  border border-white
                  text-black
                  dark:text-white
                  hover:bg-light-secondary hover:border-light-secondary
                  dark:hover:bg-dark-secondary dark:hover:border-dark-secondary
                  mr-3
                  sm:mr-4
                "
                href="https://www.facebook.com/aly.mohamed.31105/"
              >
                <svg
                  width="8"
                  height="16"
                  viewBox="0 0 8 16"
                  class="fill-current"
                >
                  <path
                    d="M7.43902 6.4H6.19918H5.75639V5.88387V4.28387V3.76774H6.19918H7.12906C7.3726 3.76774 7.57186 3.56129 7.57186 3.25161V0.516129C7.57186 0.232258 7.39474 0 7.12906 0H5.51285C3.76379 0 2.54609 1.44516 2.54609 3.5871V5.83226V6.34839H2.10329H0.597778C0.287819 6.34839 0 6.63226 0 7.04516V8.90323C0 9.26452 0.243539 9.6 0.597778 9.6H2.05902H2.50181V10.1161V15.3032C2.50181 15.6645 2.74535 16 3.09959 16H5.18075C5.31359 16 5.42429 15.9226 5.51285 15.8194C5.60141 15.7161 5.66783 15.5355 5.66783 15.3806V10.1419V9.62581H6.13276H7.12906C7.41688 9.62581 7.63828 9.41935 7.68256 9.10968V9.08387V9.05806L7.99252 7.27742C8.01466 7.09677 7.99252 6.89032 7.85968 6.68387C7.8154 6.55484 7.61614 6.42581 7.43902 6.4Z"
                  />
                </svg>
              </a>

              <a
                class="
                  w-12
                  h-12
                  rounded-full
                  flex
                  items-center
                  justify-center
                  border border-white
                  text-black
                  dark:text-white
                  hover:bg-light-secondary hover:border-light-secondary
                  dark:hover:bg-dark-secondary dark:hover:border-dark-secondary
                  mr-3
                  sm:mr-4
                "
                href="https://github.com/alymohamed20"
              >
                <svg
                  width="16"
                  height="17"
                  viewBox="0 0 16 17"
                  class="fill-current"
                >
               <path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
                </svg>
              </a>
              <a
                class="
                  w-12
                  h-12
                  rounded-full
                  flex
                  items-center
                  justify-center
                  border border-white
                  text-black
                  dark:text-white
                  hover:bg-light-secondary hover:border-light-secondary
                  dark:hover:bg-dark-secondary dark:hover:border-dark-secondary
                  mr-3
                  sm:mr-4
                "
                href="https://www.linkedin.com/in/ali-mohamed-377980189/"
              >
                <svg
                  width="14"
                  height="14"
                  viewBox="0 0 14 14"
                  class="fill-current"
                >
                  <path
                    d="M13.0214 0H1.02084C0.453707 0 0 0.451613 0 1.01613V12.9839C0 13.5258 0.453707 14 1.02084 14H12.976C13.5432 14 13.9969 13.5484 13.9969 12.9839V0.993548C14.0422 0.451613 13.5885 0 13.0214 0ZM4.15142 11.9H2.08705V5.23871H4.15142V11.9ZM3.10789 4.3129C2.42733 4.3129 1.90557 3.77097 1.90557 3.11613C1.90557 2.46129 2.45002 1.91935 3.10789 1.91935C3.76577 1.91935 4.31022 2.46129 4.31022 3.11613C4.31022 3.77097 3.81114 4.3129 3.10789 4.3129ZM11.9779 11.9H9.9135V8.67097C9.9135 7.90323 9.89082 6.8871 8.82461 6.8871C7.73571 6.8871 7.57691 7.74516 7.57691 8.60323V11.9H5.51254V5.23871H7.53154V6.16452H7.55423C7.84914 5.62258 8.50701 5.08065 9.52785 5.08065C11.6376 5.08065 12.0232 6.43548 12.0232 8.2871V11.9H11.9779Z"
                  />
                </svg>
              </a>
            </div>
          </div>
        </div>
        <div class="flex flex-1 justify-end items-center h-full mt-8 md:mt-0">
          <img
            class="rounded-lg"
            src="http://127.0.0.1:8000/img/2.jpeg"
            alt="Hero"
          />
        </div>
      </div>
    </div>
  </section>
</template>
