<script></script>

<template>
  <html>
    <h2>You need to login, pal!</h2>

    <form>
      <label for="userName">User name:</label><br />
      <input type="text" id="userName" name="userName" /><br />
      <label for="userPassword">Password:</label><br />
      <input type="password" id="userPasssword" name="userPassword" />
    </form>
    <span>Don't have an account?</span>
    <router-link to="/registration">Create Account</router-link>
  </html>
</template>
