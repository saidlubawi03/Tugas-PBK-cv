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
    <template #heading>Deskripsi</template>

    saya lahir di Perawang pada tgl 13 septemeber 2003 dan biasanyaa di panggil Bawik
    saya anak kedua dari dua bersaudara, tamatan dari SMA OLAHRAGA PROV RIAU.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Pendidikan</template>

    sekarang saya menjalanin pendidikan S1 di ssalah satu universitas yaitu
    <a href="###" target="_blank" rel="noopener">UNVERSITAS ISLAM RIAU</a>
    Dan sekarang sudah meyelesaikan 3 semester.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Jurusan</template>
    saya mengambil fakultas  
    <a href="###" target="_blank" rel="noopener">Teknik</a>
    Dan Prodi
    <a href="###" target="_blank" rel="noopener">Teknik Informatika</a>.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobby</template>
    <a href="###" target="_blank" rel="noopener">Sepak Bola</a><br>
    <a href="###" target="_blank" rel="noopener">Mokel</a><br>
    <a href="###" target="_blank" rel="noopener">Ganggu bg Han</a><br>
  </WelcomeItem>

</template>
