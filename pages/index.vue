<template>
  <section class="home">
    <div class="name-block">
      <div class="name-block-container">
        <h1><span>Hi, I'm</span>Tommy O' Peters</h1>
        <h2>
          <span
            id="professions"
            data-wait="1000"
            data-words='["Developer", "Designer", "Photographer", "Poet"]'
            >Photogr</span
          >
        </h2>
        <a
          target="_blank"
          href="tommycv.docx"
          download="Tommy O' Peters CV"
          class="btn btn-download"
          >Download Resume</a
        >
        <ul class="social">
          <li>
            <a target="_blank" href="https://www.linkedin.com/in/tommyopeters/"
              ><i class="ion-social-linkedin-outline"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="https://www.facebook.com/tommyopeters"
              ><i class="ion-social-facebook"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="https://twitter.com/tommyopeters"
              ><i class="ion-social-twitter"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="https://www.instagram.com/tommyopeters/"
              ><i class="ion-social-instagram-outline"></i
            ></a>
          </li>
          <li>
            <a target="_blank" href="https://www.github.com/tommyopeters/"
              ><i class="ion-social-github"></i
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
