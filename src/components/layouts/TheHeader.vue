<template>
  <header>
    <RouterLink to="/"
      ><img
        alt="DevOpsBot"
        class="logo"
        src="@/assets/logo.svg"
        width="100"
        height="50"
    /></RouterLink>

    <div class="wrapper">
      <nav>
        <ul>
          <li><RouterLink to="/features">Features</RouterLink></li>
          <li><RouterLink to="/solutions">Solutions</RouterLink></li>
          <li><RouterLink to="/pricing">Pricing</RouterLink></li>
          <li><RouterLink to="/customers">Customers</RouterLink></li>
          <li><RouterLink to="/resources">Resources</RouterLink></li>
          <li><RouterLink to="/demo">Schedule Demo</RouterLink></li>
          <li><a href="http://cloudbot-app-fe-dev.s3-website.us-east-2.amazonaws.com/support">Support</a></li>
          <li><base-button onclick="location.href='http://cloudbot-app-fe-dev.s3-website.us-east-2.amazonaws.com';">Login</base-button></li>
        </ul>
      </nav>
    </div>
  </header>
</template>

<script>
export default {};
</script>

<style scoped>
header {
  width: 100%;
  height: 5rem;
  background-color: #0211b4;
  display: flex;
  justify-content: center;
  align-items: center;
}

header a {
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

header nav {
  width: 90%;
  margin: auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header ul {
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
