<template>
  <div
    class="
      text-gray-300 text-2xl
      font-bold
      mt-10
      border-b-2 border-gray-800
      mx-auto
    "
  >
    <ul class="flex h-14 justify-center">
      <li class="mx-2 border-b-4 border-red-400 px-6">
        <a class="pb-2" href="#">
          <i class="fa fa-volume-down mr-3 fa-lg"></i>Overview
        </a>
      </li>
      <li class="mx-2 px-6">
        <a class="pb-2" href="#">
          <i class="fa fa-shopping-cart mr-3 fa-md"></i>
        </a>
      </li>
      <li class="mx-2 px-6">
        <a class="pb-2" href="#">
          <i class="fa fa-user mr-3 fa-md"></i>Projects
        </a>
      </li>
      <li class="mx-2 px-6">
        <a class="pb-2" href="#">
          <i class="fa fa-book mr-3 fa-md"></i>Packages
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'tab',
}
</script>

<style></style>
