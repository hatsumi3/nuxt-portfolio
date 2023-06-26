<template>
  <div>
    <div class="hero">
      <img src="~/assets/images/index-hero.jpg" alt="hero">
      <div class="textContainer">
        <h1>I'm Abe Hiroki!</h1>
        <h3>Javascript Developer</h3>
      </div>
    </div>
    <div class="container">
      <div class="profile">
        <div>
          <h2>Javascript Nerd</h2>
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse maximus est tellus, eget porta leo
            tristique a. Donec hendrerit massa leo, id tempus dolor vulputate et. Pellentesque consectetur dolor placerat
            euismod pellentesque. Integer scelerisque, augue ac ullamcorper sodales, neque lectus tristique turpis, id
            luctus lectus lorem eu tortor. In imperdiet semper accumsan. Etiam pellentesque libero et scelerisque
            vehicula. Nam quis justo mi. Cras erat ex, rhoncus id blandit id, commodo ac leo. In hac habitasse platea
            dictumst. Pellentesque id sapien quis justo dapibus ornare. Proin scelerisque quam quis sapien porttitor
            vehicula. Fusce a vehicula sem, at rhoncus augue. Mauris eros massa, tincidunt et lobortis sed, tempor vitae
            ligula.
          </p>
        </div>
        <img src="~/assets/images/profile.jpg" alt="profile">
      </div>
      <div class="skills">
        <h2>Skills</h2>
        <div class="skillsContainer">
          <div>
            <img src="~/assets/images/javascript.svg" alt="javascript">
            <span>Javascript / 10 years</span>
          </div>
          <div>
            <img src="~/assets/images/react.svg" alt="react">
            <span>React / 5 years</span>
          </div>
          <div>
            <img src="~/assets/images/next.svg" alt="next">
            <span>Next / 4 years</span>
          </div>
        </div>
        <div class="ctaButton">
          <NuxtLink to="/contact">Make It Happen!</NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>