<template>
   <div class="flex flex-row w-full">
    <LeftBar/>
    <MainBody/>
    <RightBar/>
   </div>
</template>

<script>
import LeftBar from '../components/shared/LeftBar.vue';
import MainBody from '../components/shared/MainBody.vue';
import RightBar from '../components/shared/RightBar.vue';
export default {
  name: 'Main-Dashboard',
  components: {
    LeftBar,
    MainBody,
    RightBar
  }
}
</script>
