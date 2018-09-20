<template>
  <footer class="footer">
    <div class="container">
        <nav>
            <ul>
              <li>
                <router-link :to="{path:'/dashboard'}">Home</router-link>
              </li>
                <li>
                    <a href="https://eduship.de">
                        About
                    </a>
                </li>
                <li>
                    <a href="https://github.com/eduship">
                        Github
                    </a>
                </li>
            </ul>
        </nav>
        <div class="copyright text-center">
          &copy; {{ new Date().getFullYear() }} <a href="https://github.com/eduship" target="_blank">Eduship</a>, made with <i class="fa fa-heart heart"></i> for a better web
        </div>
    </div>
  </footer>

</template>
<script>
export default {}

</script>
<style>

</style>
