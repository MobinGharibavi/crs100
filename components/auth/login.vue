<template>
  <form class="mt-10 space-y-4" autocomplete="on">
    <div class="h-16 relative">
      <svg
        class="w-6 absolute rtl:right-4 left-4 top-0 bottom-0 my-auto"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M17 16.0002L13 12.0002V8.82023C14.35 8.33023 15.26 6.93023 14.93 5.36023C14.68 4.18023 13.7 3.24023 12.51 3.04023C10.63 2.73023 9 4.17023 9 6.00023C9 7.30023 9.84 8.40023 11 8.82023V12.0002L7 16.0002H4C3.45 16.0002 3 16.4502 3 17.0002V20.0002C3 20.5502 3.45 21.0002 4 21.0002H7C7.55 21.0002 8 20.5502 8 20.0002V17.9502L12 13.7502L16 17.9502V20.0002C16 20.5502 16.45 21.0002 17 21.0002H20C20.55 21.0002 21 20.5502 21 20.0002V17.0002C21 16.4502 20.55 16.0002 20 16.0002H17Z"
          fill="#514037"
        />
      </svg>

      <input
        id="crsid"
        class="border-[#E1E2E4] hover:border-[#8CB8FB] h-full px-[3.25rem] w-full text-[#1C0E07] text-lg focus:outline-none bg-transparent placeholder:text-[#A69F9B] pt-1 border-[0.125rem] focus:border-[#307FF8] rounded-[1rem]"
        type="text"
        v-model="loginBody.crsid"
        placeholder="Agent ID"
      />
    </div>
    <div class="h-16 relative">
      <svg
        class="w-6 absolute rtl:right-4 left-4 top-0 bottom-0 my-auto"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M12 12C14.21 12 16 10.21 16 8C16 5.79 14.21 4 12 4C9.79 4 8 5.79 8 8C8 10.21 9.79 12 12 12ZM12 14C9.33 14 4 15.34 4 18V19C4 19.55 4.45 20 5 20H19C19.55 20 20 19.55 20 19V18C20 15.34 14.67 14 12 14Z"
          fill="#514037"
        />
      </svg>
      <input
        id="username"
        class="border-[#E1E2E4] hover:border-[#8CB8FB] h-full px-[3.25rem] w-full text-[#1C0E07] text-lg focus:outline-none bg-transparent placeholder:text-[#A69F9B] pt-1 border-[0.125rem] focus:border-[#307FF8] rounded-[1rem]"
        type="text"
        placeholder="Username"
      />
    </div>
    <div class="h-16 relative">
      <svg
        class="w-6 absolute rtl:right-4 left-4 top-0 bottom-0 my-auto"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M17.8102 4.47C17.7302 4.47 17.6502 4.45 17.5802 4.41C15.6602 3.42 14.0002 3 12.0102 3C10.0302 3 8.15023 3.47 6.44023 4.41C6.20023 4.54 5.90023 4.45 5.76023 4.21C5.63023 3.97 5.72023 3.66 5.96023 3.53C7.82023 2.52 9.86023 2 12.0102 2C14.1402 2 16.0002 2.47 18.0402 3.52C18.2902 3.65 18.3802 3.95 18.2502 4.19C18.1602 4.37 17.9902 4.47 17.8102 4.47ZM3.50023 9.72C3.40023 9.72 3.30023 9.69 3.21023 9.63C2.98023 9.47 2.93023 9.16 3.09023 8.93C4.08023 7.53 5.34023 6.43 6.84023 5.66C9.98023 4.04 14.0002 4.03 17.1502 5.65C18.6502 6.42 19.9102 7.51 20.9002 8.9C21.0602 9.12 21.0102 9.44 20.7802 9.6C20.5502 9.76 20.2402 9.71 20.0802 9.48C19.1802 8.22 18.0402 7.23 16.6902 6.54C13.8202 5.07 10.1502 5.07 7.29023 6.55C5.93023 7.25 4.79023 8.25 3.89023 9.51C3.81023 9.65 3.66023 9.72 3.50023 9.72ZM9.75023 21.79C9.62023 21.79 9.49023 21.74 9.40023 21.64C8.53023 20.77 8.06023 20.21 7.39023 19C6.70023 17.77 6.34023 16.27 6.34023 14.66C6.34023 11.69 8.88023 9.27 12.0002 9.27C15.1202 9.27 17.6602 11.69 17.6602 14.66C17.6602 14.94 17.4402 15.16 17.1602 15.16C16.8802 15.16 16.6602 14.94 16.6602 14.66C16.6602 12.24 14.5702 10.27 12.0002 10.27C9.43023 10.27 7.34023 12.24 7.34023 14.66C7.34023 16.1 7.66023 17.43 8.27023 18.51C8.91023 19.66 9.35023 20.15 10.1202 20.93C10.3102 21.13 10.3102 21.44 10.1202 21.64C10.0102 21.74 9.88023 21.79 9.75023 21.79ZM16.9202 19.94C15.7302 19.94 14.6802 19.64 13.8202 19.05C12.3302 18.04 11.4402 16.4 11.4402 14.66C11.4402 14.38 11.6602 14.16 11.9402 14.16C12.2202 14.16 12.4402 14.38 12.4402 14.66C12.4402 16.07 13.1602 17.4 14.3802 18.22C15.0902 18.7 15.9202 18.93 16.9202 18.93C17.1602 18.93 17.5602 18.9 17.9602 18.83C18.2302 18.78 18.4902 18.96 18.5402 19.24C18.5902 19.51 18.4102 19.77 18.1302 19.82C17.5602 19.93 17.0602 19.94 16.9202 19.94ZM14.9102 22C14.8702 22 14.8202 21.99 14.7802 21.98C13.1902 21.54 12.1502 20.95 11.0602 19.88C9.66023 18.49 8.89023 16.64 8.89023 14.66C8.89023 13.04 10.2702 11.72 11.9702 11.72C13.6702 11.72 15.0502 13.04 15.0502 14.66C15.0502 15.73 15.9802 16.6 17.1302 16.6C18.2802 16.6 19.2102 15.73 19.2102 14.66C19.2102 10.89 15.9602 7.83 11.9602 7.83C9.12023 7.83 6.52023 9.41 5.35023 11.86C4.96023 12.67 4.76023 13.62 4.76023 14.66C4.76023 15.44 4.83023 16.67 5.43023 18.27C5.53023 18.53 5.40023 18.82 5.14023 18.91C4.88023 19.01 4.59023 18.87 4.50023 18.62C4.01023 17.31 3.77023 16.01 3.77023 14.66C3.77023 13.46 4.00023 12.37 4.45023 11.42C5.78023 8.63 8.73023 6.82 11.9602 6.82C16.5102 6.82 20.2102 10.33 20.2102 14.65C20.2102 16.27 18.8302 17.59 17.1302 17.59C15.4302 17.59 14.0502 16.27 14.0502 14.65C14.0502 13.58 13.1202 12.71 11.9702 12.71C10.8202 12.71 9.89023 13.58 9.89023 14.65C9.89023 16.36 10.5502 17.96 11.7602 19.16C12.7102 20.1 13.6202 20.62 15.0302 21.01C15.3002 21.08 15.4502 21.36 15.3802 21.62C15.3302 21.85 15.1202 22 14.9102 22Z"
          fill="#514037"
        />
      </svg>

      <input
        id="password"
        class="border-[#E1E2E4] hover:border-[#8CB8FB] h-full px-[3.25rem] w-full text-[#1C0E07] text-lg focus:outline-none bg-transparent placeholder:text-[#A69F9B] pt-1 border-[0.125rem] focus:border-[#307FF8] rounded-[1rem]"
        :type="typeInput"
        placeholder="Password"
        v-model="loginBody.password"
      />
      <svg
        v-if="typeInput == 'password'"
        @click="typeInput = 'text'"
        class="w-6 absolute rtl:left-4 right-4 top-0 bottom-0 my-auto cursor-pointer"
        width="24"
        height="24"
        viewBox="0 0 24 24"
        fill="none"
        xmlns="http://www.w3.org/2000/svg"
      >
        <path
          d="M12 4C7 4 2.73 7.11 1 11.5C2.73 15.89 7 19 12 19C17 19 21.27 15.89 23 11.5C21.27 7.11 17 4 12 4ZM12 16.5C9.24 16.5 7 14.26 7 11.5C7 8.74 9.24 6.5 12 6.5C14.76 6.5 17 8.74 17 11.5C17 14.26 14.76 16.5 12 16.5ZM12 8.5C10.34 8.5 9 9.84 9 11.5C9 13.16 10.34 14.5 12 14.5C13.66 14.5 15 13.16 15 11.5C15 9.84 13.66 8.5 12 8.5Z"
          fill="#514037"
        />
      </svg>

      <svg
        @click="typeInput = 'password'"
        class="w-6 absolute rtl:left-4 right-4 top-0 bottom-0 my-auto cursor-pointer"
        v-else
        xmlns="http://www.w3.org/2000/svg"
        width="1.5rem"
        height="1.5rem"
        viewBox="0 0 24 24"
      >
        <path
          fill="currentColor"
          d="M17.883 19.297A10.949 10.949 0 0 1 12 21c-5.392 0-9.878-3.88-10.818-9A10.982 10.982 0 0 1 4.52 5.935L1.394 2.808l1.414-1.414l19.799 19.798l-1.414 1.415zM5.936 7.35A8.965 8.965 0 0 0 3.223 12a9.005 9.005 0 0 0 13.201 5.838l-2.028-2.028A4.5 4.5 0 0 1 8.19 9.604zm6.978 6.978l-3.242-3.241a2.5 2.5 0 0 0 3.241 3.241m7.893 2.265l-1.431-1.431A8.935 8.935 0 0 0 20.778 12A9.005 9.005 0 0 0 9.552 5.338L7.974 3.76C9.221 3.27 10.58 3 12 3c5.392 0 9.878 3.88 10.819 9a10.947 10.947 0 0 1-2.012 4.593m-9.084-9.084a4.5 4.5 0 0 1 4.769 4.769z"
        />
      </svg>
    </div>
  </form>

  <button
    @click="login"
    :disabled="loading"
    :class="{ 'opacity-50': loading }"
    class="flex items-center justify-center p-5 mt-4 rounded-[1rem] bg-[#307FF8] gap-2 text-white"
  >
    <svg
      data-v-4fa0a2a1=""
      xmlns="http://www.w3.org/2000/svg"
      xmlns:xlink="http://www.w3.org/1999/xlink"
      aria-hidden="true"
      role="img"
      width="2rem"
      height="2rem"
      viewBox="0 0 24 24"
    >
      <g transform="rotate(180 12 12)">
        <path
          fill="currentColor"
          d="M12 21v-2h7V5h-7V3h7q.825 0 1.413.588T21 5v14q0 .825-.587 1.413T19 21zm-2-4l-1.375-1.45l2.55-2.55H3v-2h8.175l-2.55-2.55L10 7l5 5z"
        ></path>
      </g>
    </svg>
    Login

    <svg
      v-if="loading"
      xmlns="http://www.w3.org/2000/svg"
      width="1.5rem"
      height="1.5rem"
      viewBox="0 0 24 24"
    >
      <g
        fill="none"
        stroke="currentColor"
        stroke-linecap="round"
        stroke-width="2"
      >
        <path
          stroke-dasharray="60"
          stroke-dashoffset="60"
          stroke-opacity="0.3"
          d="M12 3C16.9706 3 21 7.02944 21 12C21 16.9706 16.9706 21 12 21C7.02944 21 3 16.9706 3 12C3 7.02944 7.02944 3 12 3Z"
        >
          <animate
            fill="freeze"
            attributeName="stroke-dashoffset"
            dur="1.3s"
            values="60;0"
          />
        </path>
        <path
          stroke-dasharray="15"
          stroke-dashoffset="15"
          d="M12 3C16.9706 3 21 7.02944 21 12"
        >
          <animate
            fill="freeze"
            attributeName="stroke-dashoffset"
            dur="0.3s"
            values="15;0"
          />
          <animateTransform
            attributeName="transform"
            dur="1.5s"
            repeatCount="indefinite"
            type="rotate"
            values="0 12 12;360 12 12"
          />
        </path>
      </g>
    </svg>
  </button>

  <div class="mt-4 text-center text-[#A69F9B] leading-[1.75rem]">
    Do not have an account?
    <span @click="emit('step', 1)" class="mx-2 text-[#307FF8] cursor-pointer"
      >Register</span
    >
  </div>
</template>

<script setup>
const emit = defineEmits(["step"]);

const loading = ref(false);
const loginBody = reactive({ password: "", crsid: "" });
const typeInput = ref("password");
const { userAuth } = useAuth();
const { locale } = useI18n();

const login = async () => {
  try {
    loading.value = true;
    const data = await $fetch("/api/auth/login", {
      method: "POST",
      body: loginBody,
    });

    userAuth.value = data;
    navigateTo(`${locale.value}/search`);
  } catch (error) {
    console.log(error);
  } finally {
    loading.value = false;
  }
};
</script>
