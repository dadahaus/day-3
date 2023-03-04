<section class="shapes">
  <!-- <h1>ich gruße dich</h1> -->

  <div class="shape shape__1" />
  <div class="shape shape__2" />
  <div class="shape shape__3" />
</section>

<style lang="scss">
  * {
    cursor: none;
  }

  .shapes {
    height: 100vh;
    width: 100vw;
    position: relative;
    background: mediumaquamarine;
    // overflow: hidden;

    // h1 {
    //   font-size: 8rem;
    //   font-weight: 800;
    // }
    .shape {
      will-change: transform;
      position: absolute;
      border-radius: 50%;

      $shapes: (
        #005ffe: 650px,
        #fe5e3: 440px,
        #ffcc57: 270px,
      );
      &__1 {
        background: #005ffe;
        width: 65px;
        height: 65px;
      }
      &__2 {
        background: #fe5e3f;
        width: 60px;
        height: 60px;
      }
      &__3 {
        background: #ffcc57;
        width: 55px;
        height: 55px;
      }
    }
  }
</style>
