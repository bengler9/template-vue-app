<template>
  <footer>
    <div class="wrapper">
      <nav>
        <ul>
          <li><RouterLink to="/contact">Contact Us</RouterLink></li>
          |
          <li><RouterLink to="/privacy">Privacy</RouterLink></li>
          |
          <li><RouterLink to="/accessibility">Accessibility</RouterLink></li>
          |
          <li><RouterLink to="/siteTerms">Site Terms</RouterLink></li>
          |
          <li><RouterLink to="/cookiePrefs">Cookie Preferences</RouterLink></li>
          |
          <li><a href="http://cloudbot-app-fe-dev.s3-website.us-east-2.amazonaws.com">Login</a></li>
        </ul>
        <p>
          &copy; 2024, CloudBot.AI, Inc. or its affiliates. All rights reserved.
        </p>
      </nav>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style scoped>
footer {
  width: 100%;
  height: 5rem;
  background-color: #0211b4;
  color: #ffffff;
  display: flex;
  justify-content: center;
  align-items: center;
}

footer a {
  text-decoration: none;
  color: #ffffff;
  display: inline-block;
  padding: 0.75rem 1.5rem;
  border: 1px solid transparent;
  white-space: nowrap;
}

a:active,
a:hover,
a.router-link-active {
  border: 1px solid #f391e3;
}

h1 {
  margin: 0;
}

h1 a {
  color: white;
  margin: 0;
}

h1 a:hover,
h1 a:active,
h1 a.router-link-active {
  border-color: transparent;
}

footer nav {
  width: 90%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

footer ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}

li {
  margin: 0 0.5rem;
}
</style>
