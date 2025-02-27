<template>

    <div class="p-4 flex-1 overflow-auto">

        <div class="flex flex-col space-y-2">
          
            <ChatBullula :meus-est="true" nuntius="¿Salimos luego a dar una vueta?" />

            <ChatBullula 
            :meus-est="false" 
            nuntius="no" 
            imago="https://yesno.wtf/assets/yes/8-2f93962e2ab24427df8589131da01a4d.gif"/>

        </div>

    </div>

</template>

<script lang="ts" setup>
    
import ChatBullula from './ChatBullula.vue';

</script>