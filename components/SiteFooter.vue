<template>
  <footer class="footer">
    <aside>
      <ul class="footer_sns">
        <li><a href="https://facebook.com/matsuoshi/"><img src="/img/social/facebook.svg" alt="facebook"></a></li>
        <li><a href="https://github.com/matsuoshi"><img src="/img/social/github.svg" alt="GitHub"></a></li>
        <li><a href="https://www.instagram.com/matsuoshi/"><img src="/img/social/instagram.svg" alt="instagram"></a></li>
        <li><a href="https://www.last.fm/user/matsuoshi"><img src="/img/social/lastfm.svg" alt="last.fm"></a></li>
        <li><a href="https://open.spotify.com/user/matsuoshi"><img src="/img/social/spotify.svg" alt="spotify"></a></li>
        <li><a href="https://twitter.com/matsuoshi"><img src="/img/social/twitter.svg" alt="twitter"></a></li>
      </ul>
    </aside>
    <p>
      <small>2018 monaural.net / hiroshi matsuo / @matsuoshi</small>
    </p>
  </footer>
</template>

<style lang="scss">
  .footer {
    text-align: center;

    .footer_sns {
      padding: 0;

      li {
        display: inline-block;
        padding: 0 0.5em;
        list-style: none;
      }
      a:hover img {
        filter: drop-shadow(0 0 8px rgba($color, .5));
      }
      img {
        width: 24px;
      }
    }
  }
</style>
