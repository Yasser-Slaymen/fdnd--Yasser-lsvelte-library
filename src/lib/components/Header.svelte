<script>
  import welcome_fallback from "$lib/images/we-love.png";
</script>

<nav>
  <section class="logo">
    <span class="welcome">
      <picture>
        <img src={welcome_fallback} alt="Welcome" />
      </picture>
    </span>
  </section>
  <h1>Studiejaar 2022-2023</h1>
  
</nav>

<style>
  :root {
    --white: #ffffff;
    --blue: #050542;
    --green: #66e5bf;
    --purple: #a675f5;
    --lavender-dark: hsl(263, 86%, 60%);
    --attention-background: #05054233;
    --call-to-action: #fffc86;
    --rounded: 0.2rem;
    --pilled: 2rem;
    --shadow: 0.3rem;
    --radius:1em
}
  img {
    margin-left: -7em;
    height: 4rem;
  }
  nav {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    margin: 4rem;
  }
  h1 {
    font-size: 2rem;
    text-align: center;
  }
</style>
