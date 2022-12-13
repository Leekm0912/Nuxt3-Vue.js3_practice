<template>
  <div class="header_wrap">
    <header class="header">
      <h1 class="logo">
        <NuxtLink to="/">
          <a href>
            <img src="~/assets/img/rcs_logo.png" alt="RCS Biz Center">
          </a>
        </NuxtLink>
      </h1>

      <div class="util_wrap">
        <NuxtLink to="/helloWorld">hello</NuxtLink>
        <NuxtLink to="/ImageView">imageView</NuxtLink>
        <a href="javascript:void(0);" class="btn_setting">정보수정</a>
        <a href="javascript:void(0);" class="btn_logout">로그아웃</a>
      </div>
    </header>
  </div>
</template>

<script>

export default {
  name: 'Header',
  computed: {
  },
  created() {
  },
  methods: {
  }
}
</script>
