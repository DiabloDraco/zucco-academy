<script>
  export let img;
  export let body;
</script>

<li class="offline__item">
  <img
    class="offline__item-img"
    src={img}
    width="auto"
    height="auto"
    alt="Программа курса"
    loading="lazy"
    title="icons"
  />
  <p class="offline__item-body">
    {body}
  </p>
</li>

<style>
  
</style>
