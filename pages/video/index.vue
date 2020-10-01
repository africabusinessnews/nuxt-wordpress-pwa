<template>
 
  <div class="container">
    <div>
    
      
      <h1 class="title">
        brightcove
      </h1>
      
      </div>
<div id="player-container"></div>

<script src="brightcove-player-loader.js"></script>
<script>
  brightcovePlayerLoader({
    refNode: '#player-container',
    accountId: '1571595826001',
    playerId: 'c0AOssA7',

    embedOptions: {
    responsive: {
      aspectRatio: '16:9',
      maxWidth: '100%'
    }
  },

    videoId: 6194583373001,
   
  });
</script>

</div>


</template>

<script>
export default {};

</script>

<script>
////brightcovePlayerLoader({
  ///refNode: someElement,
  ///accountId: '1571595826001'
////});

</script>

