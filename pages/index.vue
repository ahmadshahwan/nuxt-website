<template>
    <div class="post">
        <div class="title">
            <h2>Short Bio</h2>
        </div>
        <div class="entry">
            <img src="/images/pigeons.jpg" alt="" width="112" height="131" class="alignleft" />
            <p>Ahmad Shahwan is software architect and full-stack developer who is willing to unfold opportunities, share expertise and exchange ideas.</p>
            <p>Ahmad worked on designing, realizing and maintaining robust digital solutions for clients such as
              <a href="https://www.sncf.com" target="_blank">SNCF</a>, <a href="https://www.malt.fr" target="_blank">Malt</a>, <a href="https://www.rtone.fr" target="_blank">Rtone</a> and others.</p>
            <p>As a lecturer at <a href="https://www.univ-lyon1.fr" target="_blank">Claude Bernard University Lyon 1</a>, Ahmad is responsible for courses on Object-Oriented Modeling and Programming.
            He teaches subjects such as Java programming language, UML and Design Patterns.</p>
            <p>His thesis on geometrical analysis of digital mock-ups and function knowledge representation of 3D models earned him a PhD degree in Mathematics and Computer Science from <a href="https://www.univ-grenoble-alpes.fr/" target="_blank">Grenoble Alpes University</a>.</p>
            <br clear="left"/>
          <h3>Interests and Activities</h3>
          <div class="interests">
            <div class="interest-details">
              <div class="interest-title">Sports</div>
              <div>Swimming, running, rock climbing, skiing.</div>
            </div>
            <div class="interest-details">
              <div class="interest-title">Cultural</div>
              <div>Painting and drawing.</div>
            </div>
          </div>
        </div>
    </div>
</template>

<script setup lang="ts">

</script>

<style lang="scss" scoped>
.interests {
  display: flex;
  flex-direction: column;
  width: 100%;

  .interest-details {
    display: flex;
    flex-direction: row;
    width: 100%;
    margin-bottom: 10px;

    .interest-title {
      width: 200px;
      font-weight: bold;
    }
  }
}
</style>
