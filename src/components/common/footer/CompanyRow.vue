<template>
  <div class="mt-[50px] mb-[71px] flex w-full">
    <!--	customer center + find Column-->
    <InquiryCol />
    <!--		company information Column-->
    <InformationCol />
  </div>
</template>

<script setup>
import InquiryCol from "@/components/common/footer/InquiryCol";
import InformationCol from "@/components/common/footer/InformationCol";
</script>
