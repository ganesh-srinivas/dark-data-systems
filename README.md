This document will contain source code and documentation (progress, ideas) for my work on dark data extraction systems. These systems use statistical inference to perform data extraction, integration and cleaning from unstructured/"dark" sources (forum posts, webpages, etc.). Data programming is the predominant paradigm for dark data extraction: noisy/conflicting user-defined functions are supplied to a generative model, which can recover the parameters of labelling process. Wherever possible, my projects will be based on Snorkel/DeepDive. 

# Inspiration
- I loved Jeff Huang's essay [Ph.D. 2.0: Adopting the Startup Culture for Research](http://jeffhuang.com/adopting_the_startup_culture_for_research.html). Take-aways: 
  - "wow" products/demos > papers
  - reliable code and documentation (eg., Colin Raffel's PhD thesis) > flimsy academic code that that is unusable to anyone else
  - risky attempts at creating "magical" results > safe incremental 
  - feedback loops with users (DAWN project)
  - share work with the public ("how will this look in *the* paper") through **expository writing** (Michael Nielsen [essays](https://distill.pub/2017/aia/) or Zachary Lipton's *[The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490v2.pdf)*
  - **create compelling demos on the web or in real life** (examples: https://clickclickclick.click,  my style transfer mirror at SNU's Convocation 2017)
- 
- **[You and Your Research](https://www.cs.virginia.edu/~robins/YouAndYourResearch.html)** by Richard Hamming.
- **[You can do research too](http://www.bailis.org/blog/you-can-do-research-too/)**. An essay by Peter Bailis.

# TODOs 
## System Extensions:
- [ ] There isn't any work on Domain Specific primitives (DSPs) for audio data. Pre-trained audio models (VGGish) can serve as feature extractors for high-level concepts like emotion, accent and personality for speech data(WaveNet paper mentions that these are possible), musical genre (Sander Dieleman's Spotify CNN blog post), etc.

## Cool applications:
- [ ] Ecological/Environmental monitoring: use audio DSPs for building models of migration, logging/poaching, etc.
- [ ] Digital humanities: understudied history and archaeology archives. Concrete problem: discover trading  
- [ ] Drug repurposing: build a database of serendipitous drug interactions from mentions on internet discussion forums.
- [ ] Macro-economic indicators (like the Michigan PhD thesis on labor market flows from Twitter data).
