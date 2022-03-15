<script>
  export let card_title = "Mi tutilo";
</script>

<div class="card">
  <h2>{card_title}</h2>
  <slot />
</div>

<!--
 0   1  2  3  4  5  6  7  8  9 10 11 12 13 14 15 
00 01 02 03 04 05 06 07 08 09  A  B  C  D  E  F

  9    f
  1    1   
 10   10 
-->
<style>
  .card {
    border: dotted 2px rgb(35, 122, 68);
    background-color: rgba(3, 3, 182, 0.301);
    border-radius: 10px;
    padding: 33px;
    margin: 1em;
  }
</style>
