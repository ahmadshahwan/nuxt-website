<template>
  <div id="header">
    <div id="logo">
      <h1>Ahmad <span class="sc">Shahwan</span></h1>
      <h2>Research and Development Engineer</h2>
    </div>
    <div id="menu">
      <ul>
        <li>
          <NuxtLink to="/">Home</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/career">Career</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/teaching">Teaching</NuxtLink>

        </li>
        <li>
          <NuxtLink to="/research">Research</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/events">Events</NuxtLink>
        </li>
        <li>
          <NuxtLink to="/contacts">Contacts</NuxtLink>
        </li>
      </ul>
    </div>

  </div>

</template>

<script setup lang="ts">

</script>

<style scoped>

#header {
  width: 920px;
  height: 130px;
  margin: 0 auto;
  background: url(/images/bg03.jpg) no-repeat left top;
}

#logo {
  float: left;
}

#logo h1 {
  margin: 0;
  padding: 60px 0 0 30px;
}

#logo h2 {
  padding: 0 0 0 30px;
  margin: 0;
}

#logo a {
  text-decoration: none;
  color: #797979;
}

#logo a:hover {
  text-decoration: underline;
  color: #0098A4;
}

#logo h2, #logo h2 a {
  font-size: 13px;
  color: #9F9F9F;
}


#menu {
  float: right;
}

#menu ul {
  margin: 0;
  padding: 78px 30px 0 0;
  list-style: none;
}

#menu li {
  float: left;
}

#menu a {
  padding: 0 12px 0 12px;
  background: url(/images/img02.gif) no-repeat left center;
  text-decoration: none;
  text-transform: lowercase;
  font-family: Georgia, "Times New Roman", Times, serif;
  font-size: 14px;
  color: #7B7B7B;
}

#menu a:hover {
  text-decoration: underline;
  color: #0098A4;
}

#menu .first a {
  background: none;
}

#menu .current {
  padding: 0 12px 0 12px;
  background: url(/images/img02.gif) no-repeat left center;
  text-decoration: none;
  text-transform: lowercase;
  font-family: Georgia, "Times New Roman", Times, serif;
  font-size: 14px;
  color: #0098A4;
}
</style>
