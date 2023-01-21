<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fa fa-camera"></i><strong>&nbsp;Album</strong></a
        >
      </div>
    </div>
  </header>
  <main role="main">
    <section class="jumbotron text-center">
      <div class="container">
        <h1>Album Examples</h1>
        <p class="lead text-muted">
          <br />Something short and leading about the collection below—its
          contents, the creator, etc. Make it short and sweet, but not too short
          so folks don’t simply skip over it entirely.<br />
        </p>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="row">
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
          <PhotoCard image="https://picsum.photos/200/300" />
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
      <p>
        Album example is &copy; Bootstrap, but please download and customize it
        for yourself!
      </p>
      <p>
        New to Bootstrap?
        <a href="https://getbootstrap.com/">Visit the homepage</a> or read our
        <a href="/docs/4.4/getting-started/introduction/"
          >getting started guide</a
        >.
      </p>
    </div>
  </footer>
</template>

<style scoped></style>
