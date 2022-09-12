- 👋 Hi, I’m Carlos Sopprani Durand
- 🇵🇪 I'm a peruvian recruiter who loves to eat and find amazing talented people
- 🌱 I’m currently learning how to be a better recruiter and find IT profiles
- 💞️ I’m looking to collaborate with you to find your ideal job or project
- 📫 You can contact me by email carlossoppranid@gmail.com or connecting with me on LinkedIn https://www.linkedin.com/in/carlossoppranidurand/

<?php
  // Sharing options
  $shareUrl = get_the_permalink();
  $shareTitle = get_the_title();
  $shareDescription = get_the_excerpt();
  $sharePicture = get_the_post_thumbnail_url();

  // LinkedIn
  $shareLinkedin = 'mini=true&url=' . urlencode($shareUrl) . '&title=' . urlencode($shareTitle) . '&summary=' . urlencode($shareDescription);
?>
<nav class="nav nav-share">
  <ul class="horizontal-list">
       <li><a class="btn btn-linkedin" target="_blank" href="https://www.linkedin.com/in/carlossoppranidurand/?<?php echo htmlentities($shareLinkedin); ?>"></a></li>
   
</nav>

<!---
cxrlos99/cxrlos99 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
