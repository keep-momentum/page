<script>
  import SitePreview from '$lib/components/site-preview.svelte';
  let title = '';
  let subtitle = '';
  let callToAction = '';
</script>


<h2 class="font-bold mb-4"> Page </h2>

<div class="container mx-auto p-4 flex">
  <div class="min-w-[426px]">
    <div class="_section">
      <div class="_title">Title</div> 
      <input class="w-full" bind:value={title}/>
    </div>
    <div class="_section">
      <div class="_title">Subtitle</div> 

      <textarea bind:value={subtitle} class="w-full" />
    </div>
    <div class="_section">
      <div class="_title">Call to action</div> 

      <input class="w-full" bind:value={callToAction}/>
    </div>
    <!-- <div class="_section">
      <div class="_title">Appearance</div> 

    </div> -->

    <div class="mt-4">
      <button class="_primary">Publish</button>
      <button class="_secondary">Preview</button>
    </div>
  </div>

  <div class="_preview">
    <SitePreview
      bind:title
      bind:subtitle
      bind:callToAction
      />
  </div>
</div>

<style>
  ._section {
    border: 1px #E0DEDE solid;
    padding: 16px;
    margin-bottom: 8px;
  }

  ._title {
    font-weight: bold;
    margin-bottom: 12px;
  }

  ._preview {
    width: 100%;
    height: 100%;
    border-left: 1px #E0DEDE solid;
  }
</style>
