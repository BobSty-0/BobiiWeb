<template>
  <body>
    <div class="navbar">
      <div class="bobii_title">
        <div class="logo_picture">
          <a href="#">
            <img src="../images/BobiiLogo.svg" />
          </a>
        </div>

        <div class="logo_text">
          <a href="#"> Bobii </a>
        </div>
      </div>

      <a href="#" class="toggle_button">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </a>

      <div class="navbar_links">
        <ul>
          <li><a href="#">Temp Channel</a></li>
          <li><a href="#">Watch 2 Gehter</a></li>
          <li><a href="#">Link Filter</a></li>
          <li><a href="#">Word Filter</a></li>
          <li><a href="#">Text Utility</a></li>
          <li><a href="#">Support</a></li>
        </ul>
      </div>
    </div>
  </body>
</template>

<style lang="scss" scoped>
@use "scss/stylesheet.scss";
</style>

<script type="application/javascript">
  const toggleButton = document.getElementsByClassName('toggle_button')[0]
  const navbarLinks = document.getElementsByClassName('navbar_links')[0]

  toggleButton.addEventListener('click', () => {
    navbarLinks.classList.toggle('active')
  });
</script>