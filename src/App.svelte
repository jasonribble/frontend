<script>
</script>

<header>
  <h1>Jason Ribble</h1>
  <section>
    <img src="images/profile_6038.jpg" alt="Jason Ribble Headshot" />
    <p>
      Curious developer with a mindful approach to programming. My hobbies
      include baking sourdough, natural movement / fitness, playing saxophone,
      and reading (mostly nonfiction).
    </p>
  </section>
</header>

<main class="content">
  <div
    data-form-slug="1918074491794537"
    data-env="production"
    data-path="contact-us/1918074491794537"
    class="keap-custom-form"
  />
  <script>
    (function (a, b) {
      var c = a.keapForms || { SNIPPET_VERSION: '1.1.0', appId: 'nfh457' },
        d = b.createElement('script');
      (d.type = 'text/javascript'),
        (d.crossOrigin = 'anonymous'),
        (d.defer = !0),
        (d.src =
          'https://forms.keap.app/lib/public-form-embed.js?appId=nfh457&version=1.1.0'),
        (d.onload = function () {
          var b = a.keapForms;
          b.renderAllForms
            ? !b.invoked && ((b.invoked = !0), b.renderAllForms())
            : console.error('[Keap Forms] Error: could not load');
        });
      var e = b.getElementsByTagName('script')[0];
      e.parentNode.insertBefore(d, e), (a.keapForms = c);
    })(window, document);
  </script>
</main>

<footer class="content">
  <p>Last updated: 2022-10-27</p>
</footer>

<style lang="scss">
  h1,
  h2 {
    font-size: 2em;
    width: 100%;
    height: 100%;
    text-align: center;
    color: #111;
  }

  h1 {
    margin-top: 1em;
  }

  p {
    font-size: 1.25em;
    color: #111;
    padding: 0.75em;
  }

  header {
    border-left: 0.125em solid #111;
    border-right: 0.125em solid #111;
    border-top: 0.125em solid #111;
    text-align: center;

    section {
      display: flex;
      flex-wrap: wrap;
      max-width: 70em;
      margin: 0 auto;
      padding: 1em;

      justify-content: space-around;
      align-items: center;

      img {
        text-align: top;
        max-width: 18.75em;
        border-radius: 50%;
      }

      p {
        text-align: left;
        line-height: 2em;
        max-width: 35em;
      }
    }
  }

  form {
    position: relative;
    max-width: 56em;
    text-align: left;
    margin: 0 auto;
    max-width: 50em;
    padding: 1em;
  }

  label {
    display: block;
    font-family: monospace;
    font-size: 2em;
    text-align: left;
    margin: 0.5em 0;
    color: #111;
  }

  textarea {
    width: 100%;
    background-color: #eee;
    height: 12.5em;
    padding: 1em;
    color: #111;
    font-size: 1.5em;
    border: none;
    resize: none;
  }

  footer {
    max-height: 4em;
    background-color: #111;
    font-size: 0.75em;
    position: fixed;
    bottom: 0;
    flex-shrink: 0;
    p {
      color: white;
      text-align: center;
      padding: 0;
    }
  }

  input {
    display: block;
    width: 100%;
    background-color: #eee;
    color: #111;
    font-family: monospace;
    height: 2.5em;
    padding: 1em;
    display: inline;
    font-size: 1.5em;
    border: none;
  }

  .content {
    border-left: 0.125em solid #111;
    border-right: 0.125em solid #111;
    position: relative;
    flex: 1 0 auto;
  }
  button {
    width: 8em;
    height: 3em;
    margin: 0 auto;
    font-size: 1.5em;
    background-color: #fafafa;
    color: #111;
    border: 0.125em solid #111;
    border-radius: 0.375em;
    text-decoration: none;
    display: block;
    text-align: center;

    &:hover {
      color: white;
      border: 0.125em solid #111;
      background-color: #111111;
      cursor: pointer;
    }
  }

  footer {
    padding: 1em;
  }

  div.contact-us-form-container {
    padding: 0 ip !important;
  }
</style>
