<template>
  <el-container>
    <el-header height="100%">
      <h1 class="title">MICROSOFT OFFICE USER</h1>
    </el-header>
    <el-main>

      <div class="contact-container">
        <div class="email">
          <i class="el-icon-message"></i>
          <p>Email</p>
        </div>
        <div class="telephone">
          <i class="el-icon-phone"></i>
          <p>Telephone</p>
        </div>
        <div class="linkedin-url">
          <i class="el-icon-download"></i>
          <p>Linkedin info</p>
        </div>
        <div class="portfolio">
          <p>Link to other online properties:</p>
          <p>Portfolio/Website/Blog</p>
        </div>
      </div>
      <div class="objective-container">
        <h4 class="title">Objective</h4>
        <hr type="primary">
        <p>To get started, click placeholder text and start typing. Be brief: one or two sentences.</p>
      </div>
      <div class="skills-container">
        <h4 class="title">Skills</h4>
        <hr type="primary">
        <p>Explain what you’re especially good at. What sets you apart? Use your own language—not jargon.</p>
      </div>
    </el-main>
  </el-container>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
@import '~assets/stylesheets/element-variables.scss';
.el-container {
  text-align: center;
  background: #e5e9f2;
}

.el-header {
  border-bottom: 1px solid $--color-primary;
  border-top: 1px solid $--color-primary;
  padding: 20px 20px;
}

[class$=container] {
  border-bottom: 1px solid $--color-primary;
  padding: 20px 0;
}

.telephone, .portfolio, .linkedin-url {
  margin-top: 20px;
}

i {
  color: $--color-primary;
  padding: 5px;
  border: 1px solid $--color-primary;
  border-radius: 50%;
  margin-bottom: 5px;
}

hr {
  width: 15%;
  border-color: $--color-primary;
  border-style: solid;
  margin: 10px auto;
}

</style>
