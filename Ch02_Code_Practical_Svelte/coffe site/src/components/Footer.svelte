<!-- These we will use to create the footer for the page layout.-->

<script>
  import InlineSVG from 'svelte-inline-svg';

  $: attributes = {
    width: 30,
    height: 30,
    fill: "#FFF",
  }  
</script>

<footer>
  <div>
    <span>&copy; Small Coffee Shop 2021</span>
  </div>
  <div>
    <span>
      <a href="https://facebook.com/smallcoffeeshop"><InlineSVG src="/images/facebook.svg" {...attributes} /></a>
      <a href="https://instagram.com/smallcoffeeshop"><InlineSVG src="/images/instagram.svg" {...attributes} /></a>
      <a href="https://Twitter.com/smallcoffeeshop"><InlineSVG src="/images/twitter.svg" {...attributes} /></a>      
    </span>
  </div>
</footer>