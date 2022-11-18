<script>
  export let title = 'Build a better product in public and grow your audience';
  export let subtitle = 'Momentum instructs you how to create and distribute your content. Add subscribers early and build based on real users feedback.';
  export let callToAction = 'Join Waitlist';
  
  export let bgColor = '#D98324'
</script>


<div class="_root">

  <div>
    <h1 class="_title" style="color: {bgColor}">{title}</h1> 
    <h2 class="_subtitle">{subtitle}</h2>

    <div class="_input_container">
      <input class="_input" placeholder="Your Email"/>
      <button class="_input_button" style="background-color: {bgColor}">{callToAction}</button>
    </div>
  </div>

</div>

<style>
  ._root {
    width: 100%;
    text-align: center;
    max-width: 870px;
    color: #0C120C;
    margin: 0 auto;
  }

  ._title {
    font-size: 56px;
    line-height: 1.2;
    margin-bottom: 32px;
  }

  ._subtitle {
    font-size: 20px;
    line-height: 36px;
    margin-bottom: 40px;
  }

  ._input_container {
    position: relative;
    width: 392px;
    margin: 0 auto;
  }

  ._input {
    background: #F5F5F5;
    width: 100%;
    padding: 15px 18px;
    border-radius: 30px;
    font-size: 18px;
  }

  ._input_button {
    position: absolute;
    height: 100%;
    right: 0;
    border-radius: 30px;
    padding: 13px 30px;
    color: white;
  }
</style>


