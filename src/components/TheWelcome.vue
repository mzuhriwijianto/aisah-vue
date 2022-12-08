<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Modul Tanah</template>

    Tanah Pemerintah Kabupaten Bojonegoro
    Meliputi Aset Tetap Tanah Rincian Tanah, jumlah tanah, bukti kepemilikan dan Lokasi Tanah.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Kendaraan Dinas</template>
    Kendaraan Dinas Pemerintah Kabupaten Bojonegoro
    Meliputi Aset Tetap Kendaraan Rincian Kendaraan, jumlah kendaraan, bukti kepemilikan dan Pemegang Kendaraan.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Gedung dan Bangunan</template>

    Gedung dan Bangunan Pemerintah Kabupaten Bojonegoro
    Meliputi Aset Tetap Kendaraan Rincian Kendaraan, jumlah kendaraan, bukti kepemilikan dan Pemegang Kendaraan.
  </WelcomeItem>
</template>
