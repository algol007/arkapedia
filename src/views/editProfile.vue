<template>
  <div class="container-edit-profile">
    <Navbar/>
    <div class="container-content">
      <div class="content">
        <editSideBar/>
        <mainEditProfile/>
      </div>
    </div>
  </div>
</template>

<script>
// import axios from 'axios';
import Navbar from '../components/Navbar/Navbar.vue';
import editSideBar from '../components/base/editSideBar.vue';
import mainEditProfile from '../components/base/mainEditProfile.vue';

export default {
  name: 'editProfile',
  components: {
    Navbar,
    editSideBar,
    mainEditProfile,
  },
};
</script>

<style scoped>
  .container-edit-profile{
    display: flex;
    flex-direction: column;
    /* align-items: center; */
    height: 1652.06px;
    flex-direction: column;
    background: #f8f8f8;
    margin: 20px 0;
  }
  .container-content{
    display: flex;
    justify-content: center;
    margin-top: 50px;
  }
  .content{
    display: flex;
    justify-content: center;
    width: 1190px;
    margin-top: 100px;
  }
</style>
