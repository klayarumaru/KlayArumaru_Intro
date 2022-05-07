<template>
    <div id="wrapper">
      <div id="header">
        header
      </div>
      <div id="conts">
        <div id="title">
          title
        </div>
        <div id="slide-title">
          slide-title
        </div>
        <div id="conts-roadmap">
          conts-roadmap
        </div>
        <div id="conts-faq">
          conts-faq
        </div>
        <div id="conts-intro-team">
          conts-intro-team
        </div>
      </div>
      <div id="footer">
        footer
      </div>
    </div>
</template>

<script>
export default {
  name: 'MainIndex',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
ul {
  list-style-type: none;
  padding: 0;
}
li {
  margin: 0 10px;
}
a {
  
}
body {
  margin: 0px;
  padding: 0px;
}
#wrapper {width: 80%; height: 100%; display: flex; flex-wrap: wrap; margin: 0 auto; background: rgba(210, 210, 210, 0.152);}
#header {width: 100%; height: 100%; background: rgba(130, 102, 102, 0.152);}
#conts {width: 100%; height: 100%; background: rgba(0, 0, 0, 0.152);}
#title {width: 100%; height: 100%; background: rgba(239, 124, 124, 0.152);}
#slide-title {width: 100%; height: 100%; background: rgba(255, 0, 0, 0.152);}
#conts-roadmap {width: 100%; height: 100%; background: rgba(31, 64, 172, 0.152);}
#conts-faq {width: 100%; height: 100%; background: rgba(238, 255, 0, 0.152);}
#conts-intro-team {width: 100%; height: 100%; background: rgba(115, 115, 115, 0.152);}
#footer {width: 100%; height: 100%; background: rgba(255, 0, 0, 0.152);}
</style>
