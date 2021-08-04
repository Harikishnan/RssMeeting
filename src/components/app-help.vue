<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');

body{
  font-family: 'Roboto', sans-serif !important;
}

</style>

<template>
  <div class="help" id="help" style="font-family: 'Roboto', sans-serif;">
    <div class="text links">
      <h1>Rss Tvndr Meet</h1>
      <p>
        <strong>Welcome to Rss <span style="color: orange;">Tvndr Meet</span></strong>
      </p>
      <p>
      </p>
      <p>
        Namaste, Rss Tvndr Meet Is For Shakha Meetings, Shakha Karyakari , And Other Official Meetings Announced By <a target="blank" href="https://rsstvndrapp.herokuapp.com"> Rss Tvndr </a>
      </p>
      <p>
        <b>
          Made With Love 🤟 By <strong>Hari Krishnan</strong>
        </b>
      </p>
      <p><br /></p>
      <p>
       &copy;  Copyright 2020-2021 by Rss Tvndr App
      </p>
      <p>Thanks To Holtwick <a target="blank" href="https://github.com/holtwick">🙏</a></p>
    </div>
  </div>
</template>


<style lang="scss">
.help {
  background: rgba(232, 239, 242, 1);
  color: #272727;
  display: block;
  font-family: "IBM Plex Serif", Georgia, serif;
  line-height: 1.5rem;
  padding-bottom: 4rem;

  .text {
    max-width: 40rem !important;
    margin-left: auto !important;
    margin-right: auto !important;
    text-align: left !important;
    padding: 1rem !important;
    padding-top: 4rem !important;
  }

  .text a {
    color: #0088c0 !important;
    text-decoration: none;
  }

  .text a:hover {
    color: #00b5ff !important;
  }

  .text a:active {
    color: #99e2ff !important;
  }
}
</style>

<script>
export default {
  name: "app-help",
  data() {
    return {}
  },
  methods: {},
  async mounted() {},
}
</script>
