<script></script>

<template>
  <html>
    <h2>Welcome curious shopper, become one of us!</h2>

    <form>
      <title>Shopper Registration</title>
      <label for="userName">User Name:</label><br />
      <input type="text" id="userName" name="userName" /><br />
      <label for="userPassword">Password:</label><br />
      <input type="password" id="userPasssword" name="userPassword" /><br />
      <label for="userPasswordVerify">Verify Password:</label><br />
      <input
        type="password"
        id="userPasswordVerify"
        name="userPasswordVerify"
      /><br />
      <button>Create</button><br />
      <span>Already have an account?</span
      ><router-link to="/">Login</router-link>
    </form>
  </html>
</template>
