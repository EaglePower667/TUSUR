<script setup>
import styles from "./Header.module.scss";
import Logo from "../Svg/Logo.vue";
</script>

<template>
  <header>
    <h1 :class="styles.title">TUSUR</h1>
    <p class="subtitle">TUSUR</p>
    <Logo />
  </header>
</template>
