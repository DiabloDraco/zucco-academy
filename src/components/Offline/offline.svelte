<script>
  import OfflineCard from "./offlineCard.svelte";
  import './offline.css'
</script>

<section class="offline">
  <div class="container">
    <div class="offline__wrapper">
      <h2 class="offline__header">Offline courses</h2>
      <div class="offline__course-wrapper">
        <image
          class="offline__img"
          src="/img/on__img-1.png"
          alt="Front-End image"
          width="500"
          height="614"
        >
          <div class="offline__text-wrapper">
            <p class="offline__text">
              A company profile will differentiate your brand. A company profile
              will naturally describe what makes your company unique. It will
              automatically differentiate your brand because no other company
              has the exact same founding story and reason for existing that you
              do. Your history and values are integral parts of a brand
              positioning strategy, and a company profile is the one place where
              you can mention these pieces of information without it feeling
              extraneous or out-of-place. A company profile may justify a higher
              price point. If you go into detail about your production values or
              ethically sourced materials, you may be able to justify a higher
              price point for your products and services. For instance,
              Starbucks’ coffee may not necessarily be better than Dunkin’
              Donuts’ coffee — but because Starbucks goes into detail about its
              high-quality ingredients, it immediately creates the sense that
              you’ll be paying a premium for its goods.
            </p>
            <ul class="offline__text-list">
              <li class="offline__text-item">
                <h3 class="offline__text-item-header">course continuities:</h3>
                <p class="offline__text-item-text">3 month</p>
              </li>
              <li class="offline__text-item">
                <h3 class="offline__text-item-header">price of course:</h3>
                <p class="offline__text-item-text">60$ for 1 month</p>
              </li>
            </ul>
          </div>
        </image>
      </div>
    </div>
    <ul class="offline__list">
      <OfflineCard
        body="A company profile will naturally describe what makes your company unique. It will automatically differentiate your brand."
        img="/img/offline-1.png"
      />
      <OfflineCard
        body="A company profile will naturally describe what makes your company unique. It will automatically differentiate your brand."
        img="/img/offline-2.png"
      />
      <OfflineCard
        body="A company profile will naturally describe what makes your company unique. It will automatically differentiate your brand."
        img="/img/offline-3.png"
      />
      <OfflineCard
        body="A company profile will naturally describe what makes your company unique. It will automatically differentiate your brand."
        img="/img/offline-4.png"
      />
      <OfflineCard
        body="A company profile will naturally describe what makes your company unique. It will automatically differentiate your brand."
        img="/img/offline-5.png"
      />
    </ul>
  </div>
</section>


<style>

  

</style>
