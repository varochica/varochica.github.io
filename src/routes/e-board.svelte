<script>
  import Teammate from '../components/Teammate.svelte';
</script>

<svelte:head>
  <title>E-Board</title>
</svelte:head>
<h3>* Subject to change, as The E-Board is in process of transitioning to Fall 2021 * </h3>
<section>
  <Teammate
    src="https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fvignette1.wikia.nocookie.net%2Fcriminal-case-grimsborough%2Fimages%2F2%2F26%2FUnknown_Character.png%2Frevision%2Flatest%3Fcb%3D20141106142941&f=1&nofb=1"
    role="Head of Applying"
    name="You!"
    link="https://docs.google.com/forms/d/e/1FAIpQLSdEV5soG_fWijQtK8RBF5-23EPHdIfYOqzjZLnDAc-PQVnkoA/viewform"
    linkTitle="Click here to apply →"
  />
  <Teammate
    src={'assets/e-board/tien.jpg'}
    role="President"
    name="Tien VoNguyen"
    link="https://www.linkedin.com/in/%E2%9C%A7-tien-v-358b09122/"
    linkTitle="LinkedIn →"
  />
  <Teammate
    src="assets/e-board/alex.jpg"
    role="Vice President"
    name="Alex Rose"
    position="50% 60%"
    link="https://alex-rose.vercel.app/"
    linkTitle="Portfolio →"
  />
  <Teammate
    src="assets/e-board/makenna.jpg"
    role="Treasurer"
    name="Makenna Walsh"
    position="50% 100%"
    link="https://www.linkedin.com/in/makenna-walsh-b54b14127/"
    linkTitle="LinkedIn →"
  />
  <!--  <Teammate-->
  <!--    src="content/eBoard/Rayyan.jpg"-->
  <!--    role="Lead Website Devoloper"-->
  <!--    name="Mohammed Rayyan Shaji"-->
  <!--  />-->
  <Teammate
    src="assets/e-board/henry.jpg"
    role="Events Chair"
    name="Henry Fellerhoff"
    position="50% 65%"
    link="https://www.henryfellerhoff.com"
    linkTitle="Portfolio →"
  />
  <Teammate
    src="assets/e-board/anran.png"
    role="Head of Recruitment"
    name="Anran Wang"
    position="50% 45%"
    link="https://www.linkedin.com/in/anranwang4/"
    linkTitle="LinkedIn →"
  />
  <Teammate
    src="assets/e-board/iqra.jpg"
    role="CAN and ACM rep"
    name="Iqra Rehman"
    link="https://www.linkedin.com/in/iqra-rehman-b4225b184/"
    linkTitle="LinkedIn →"
  />
</section>

<style>
  h3 {
    color: var(--text);
    text-align: center;
  }
  section {
    padding: 2em;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 1em;
    place-items: center;
  }
</style>
