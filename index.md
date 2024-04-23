---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
order: 1
---

<script type="text/javascript" src="/assets/js/bundle.js" ></script>
<script>
  // Get the trigger element
  const triggerElement = document.getElementById('triggerElement');

  // Function to handle scroll event
  function handleScroll() {
    // Check if the user has scrolled past the trigger element
    if (window.scrollY > triggerElement.offsetTop) {
      // Add the 'hovered' class to apply hover styles
      triggerElement.classList.add('hovered');
    } else {
      // Remove the 'hovered' class if the user scrolls back
      triggerElement.classList.remove('hovered');
    }
  }

  // Attach scroll event listener
  window.addEventListener('scroll', handleScroll);
</script>

<h5 class="header" style="font-size:100%;">An independent research group at the <a href="https://mpi.nl" target="_blank">Max Planck Institute for Psycholinguistics</a> and the <a href="https://www.ru.nl/donders/" target="_blank">Donders Institute for Brain, Cognition and Behaviour</a>.</h5>

<!-- <div class="icon-hover"> -->
<h1 class="post-title" id="triggerElement">
  <span class="icon-hover">
    <span>Language</span> 
    <i>
      <i class="fac fa-syntax"></i>
    </i>
  </span> 
  and
  <span class="icon-hover">
    <span>Computation</span> 
    <i class="fa-solid fa-gears"></i>    
  </span> 
  in
  <span class="icon-hover">
    <span>Neural</span> 
    <i class="fa-solid fa-brain"></i>    
  </span> 
  Systems
</h1>

<h5 class="header" id="triggerElement">
  Where we try to understand (model) the 
  <span class="icon-hover">
    <span><a>neural</a></span> 
    <i class="fa-solid fa-brain"></i>    
  </span> 
  and
  <span class="icon-hover">
    <span><a>cognitive</a></span> 
    <i class="fa-solid fa-gears"></i>    
  </span> 
  basis of 
  <span class="icon-hover">
    <span><a>language</a></span> 
    <i><i font-weight="Bold" class="fac fa-syntax"></i>
    </i>
  </span> 
  processing.
</h5>
<!-- </div> -->

<!-- <a href="https://www.biorxiv.org/content/10.1101/2024.03.19.585683v1" target="_blank">
  <img src="{{ base.url }}/assets/images/home/structure_building.webp" alt="A compositional neural architecture for language"> 
</a>
<figcaption>
  How do neural dynamics help incremental structure building in language behaviors? With any utterance, speakers and listeners seem to effortlessly integrate words incrementally into a hierarchical syntactic structure with a meaningful interpretation. But how is this structure building done?
</figcaption>
<br>
 -->
<div>
  <img src="{{ base.url }}/assets/images/home/andrea_chapter.png" alt="Interdisciplinary approach" style="float:right; margin-left: 20px; margin-bottom: 10px; width: 400px; height: auto;">
  <p>
    The focus of our research group is to understand the computational principles and mechanisms that underlie the representation and processing of human language.  Our aim is to develop a theory about how the brain generates human language that is based on principles from across the 
    <span class="icon-hover">
      <span><a>language sciences,</a></span> 
      <i><i class="fac fa-syntax"></i></i>
    </span> 
    the cognitive and
    <span class="icon-hover">
      <span><a>computational sciences,</a></span> 
      <i class="fa-solid fa-gears"></i>    
    </span> 
    and 
    <span class="icon-hover">
      <span><a>neuroscience</a></span> 
      <i class="fa-solid fa-gears"></i>    
    </span>—and to do so in a way that stays faithful to the constraints on neural computation, to the formal properties of language, and to human behavior.
  </p>
</div>
<br>
<p>
  Language is key to nearly all human activities, and is a defining human behavior. A fundamental question has shaped the study of language since its inception: Is our capacity for language built upon <i>linguistic structure</i> (e.g., grammar from Linguistics), or is it derived from the <i>statistical patterns</i> of language use (e.g., the probability of a sound or word given the preceding context)? The answer to this question matters because it determines what kinds of systems (viz., biological and artificial) can have language and has strong implications for the composition of the human mind. 
</p>
<br>
<div class="image-gallery">
  <img src="{{ base.url }}/assets/images/participate/comprehension.webp" alt="Comprehension">
  <img src="{{ base.url }}/assets/images/participate/production.webp" alt="Production">
  <img src="{{ base.url }}/assets/images/participate/multimodal.webp" alt="Multimodal conversation">
</div>
<br>
<p>
  In the Lise Meitner Research Group <i>Language and Computation in Neural Systems</i>, we study how the human mind encodes both the structure and statistics of language in neural dynamics, or rhythmic patterns of brain activity over time. We measure the effects of structure and statistics on neural dynamics during language processing, and construct computational models and theories of how the brain transforms sensory signals (e.g., speech, sign) into structured meaningful language, and returns language back into articulation in production. As the particular division of labor between structure and statistics varies by language and by behavioral context, we focus on collecting MEG data in a variety of languages in a range of behavioral contexts, including naturalistic listening and speaking, and using these dynamics to constrain models of language processing. 
</p>

<!-- The focus of our research group is to understand the computational principles and mechanisms that underlie the representation and processing of human language.  Our aim is to develop a theory about how the brain generates human language that is based on principles from across the language sciences, the cognitive and computational sciences, and neuroscience—and to do so in a way that stays faithful to the constraints on neural computation, to the formal properties of language, and to human behavior. -->

<!-- Our starting point is an interdisciplinary approach that asserts that any theory of how the brain represents and processes language must stay faithful to linguistic, computational, neuroscientific, and behavioral principles. Our focus is on the role of “rhythmic computation” as a mechanism for symbolic representations in brain-like systems. We create theoretical models and computational implementations. Then, neuroscientific experiments are designed to test if the brain solves the problem using similar mechanisms. -->

To read more about our research, check out our [research](/research), [projects](/posts) and [publication](/publications) pages.
