<template>
  <router-view />

  <ModalPassword />
  <ModalAlertNotfound />
  <ModalAlertSuccess />
  <ModalDelete />
  <ModalDeleteRequest />
  <ModalDeleteReason />
</template>
<script setup lang="ts">
import ModalPassword from "@/components/modal/ModalPassword.vue";
import ModalAlertNotfound from "@/components/modal/ModalAlertNotfound.vue";
import ModalAlertSuccess from "@/components/modal/ModalAlertSuccess.vue";
import ModalDelete from "@/components/modal/ModalDelete.vue";
import ModalDeleteRequest from "@/components/modal/ModalDeleteRequest.vue";
import ModalDeleteReason from "@/components/modal/ModalDeleteReason.vue";
</script>

<style>
.Toastify__toast-container {
  z-index: 10005 !important;
}
</style>
