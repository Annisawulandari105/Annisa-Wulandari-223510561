<script setup>
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
    <template #heading>RIWAYAT SAYA</template>

    Perkenalkan Nama Saya Annisa Wulandari Saya Berasal Dari Rokan Hulu Saya Lahir Di pekanbaru tanggal 10 Mei 2004
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Informasi Saya</template>

    Nama Annisa Wulandari Saya Seorang Mahasiswa DiUniversitas Islam RIau Di Jurusan Teknik Informatika Semester 4

    <br />
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Riwayat Pendidikan Saya</template>
    Pendidikan saya yaitu Paud,Tk,Sd,SMP,SMA dan Saya Sekarang KuLIAH DI Universitas Islam Riau dan Saya memiliki dan berkeinginan besar menjadi wanita karier di bidang IT
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>contak Saya</template>
     Nama:Annisa Wulandari Telepon:082215467580 emain:annisa123@gmail.com
  </WelcomeItem>

</template>
