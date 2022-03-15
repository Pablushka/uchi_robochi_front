<script>
  import Card from "./Card.svelte";

  export let name;
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn
    how to build Svelte apps.
  </p>

  <Card card_title="Otro tiltulo">
    <p>
      Lorem ipsum dolor sit amet consectetur, adipisicing elit. Nulla, id atque!
      Sed labore ullam sint voluptatum mollitia fugit voluptatem dicta explicabo
      nisi optio itaque quidem ut dolorum maxime, aut nemo. Itaque, soluta
      cumque suscipit maiores tempora atque earum quibusdam culpa hic, id
      voluptatibus alias dolores voluptate! Libero ad debitis repudiandae,
      illum, magni, quae officia dolor eveniet provident minima ratione ipsum.
      Excepturi, placeat nulla. Beatae vero quod dicta maxime voluptatem, quo,
      quam porro quibusdam nesciunt praesentium cumque enim ducimus ipsum
      pariatur numquam sapiente quis culpa ex impedit suscipit incidunt, cum
      maiores.
    </p>
    <button>Un boton</button>
  </Card>

  <Card>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit laboriosam
    consequatur temporibus earum tempora. Obcaecati delectus sequi vel in! At
    dignissimos perferendis cum quia ratione sequi voluptatibus culpa ipsa esse?
    Sint quo itaque culpa, esse vel eveniet magnam dolorem minima. Voluptate,
    explicabo repudiandae temporibus tempora voluptatibus eius praesentium harum
    exercitationem nobis a nihil asperiores commodi nemo quaerat dignissimos?
    Quis, fugit!
  </Card>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: rgb(208, 38, 250);
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
